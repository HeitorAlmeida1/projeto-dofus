# AGENTS.md

## Visão geral

Neste projeto acadêmico com o foco no tema musical "Da lama a musica", tenho como objetivo central explicar fases da minha vida por meio de musicas marcantes. Como atividade obrigatoria, preciso ter uma dashboard e para alimentar ela com informacoes irei fazer uma parte do site com uma especie de calculadora, com musicas/itens predefinidos para o usuario informar valores (nota, frequencia ou impacto), e com um calculo interno mostrar na dashboard quais sao os destaques e quais sao menos relevantes.

## Tecnologias

Neste projeto irei manter uma base de dados interna escrita a mao com musicas, artistas, categorias e metadados necessarios para os calculos da dashboard. As tecnologias principais sao HTML, CSS, JavaScript, Node.js, Express e MySQL, com suporte da API/base disponibilizada pelo professor para este projeto individual academico.

## Comandos

Comandos principais para trabalhar com o projeto:
- npm install
- npm run dev
- npm start

Observacao: configure o arquivo .env com os dados do banco antes de iniciar o servidor.

## Arquitetura

Estrutura principal do projeto:
- public/: telas do site, incluindo paginas publicas, dashboard, css, js e assets.
- src/controllers/: regras de entrada e saida das requisicoes HTTP.
- src/models/: consultas e operacoes no banco de dados.
- src/routes/: definicao das rotas da aplicacao.
- src/database/: scripts e configuracoes de banco.
- app.js: inicializacao do servidor Express e vinculacao das rotas.

Fluxo padrao de requisicao:
- Front-end (public/js) faz requisicao HTTP para uma rota em src/routes.
- A rota chama um controller em src/controllers.
- O controller valida dados e chama o model correspondente.
- O model acessa o banco via src/database.
- A resposta volta para o controller e retorna para a interface.

Onde criar novas funcionalidades:
- Nova tela: criar em public/ e organizar estilos/scripts em public/css e public/js.
- Nova funcionalidade de API: criar rota em src/routes, controller em src/controllers e model em src/models.
- Nova tabela/ajuste de dados: registrar scripts em src/database.

## Padrões de desenvolvimento

Exemplos:
- Use apenas let pois é a única variavel que aprendi e que uso no meu dia a dia.
- Mantenha sempre o padrão imposta ja achado nos arquivos, em variaveis sempre nomeia_com_undescore, nunca nomeiaComMaisculo.
- Para commit nao precisa ter um padrão pois irei fazer isto manualmente.

Padrao da identidade visual (baseado em public/identidade.html):
- Tema principal: "Da lama a musica", visual de colagem/recorte, sem estilo generico.
- Cores base: preto lama (#14110F), marrom mangue (#3B2A1E), vermelho caranguejo (#D9381E), amarelo sol (#F2B705), verde mangue (#2E6B3F), branco papel (#F1E9D8).
- Tipografia: Permanent Marker para titulos e Special Elite para textos.
- Componentes: sem cantos arredondados, com bordas retas e contraste forte.
- Icones: traco de 2px, arredondado nas pontas, somente contorno e preferencia para amarelo sol.

## Cuidados e restrições

Sempre que eu te pedir alguma ajuda nunca faça nada sem a minha pessoa aprovar, e se possivel nunca escreva nada apenas me oriente como eu chego naquele resultado, e sempre peça a minha validação para quaisquer que seja a tomada de decisão, pois como eu ja mencionei este projeto é acadêmico, estou  produzindo isto a fim de um aprendizado então eu preciso sim quebrar a cabeça, então sempre me deixe quebrar a cabeça nunca me de respostas faceis ou faça o serviço pela minha pessoa.

Em qualquer ajuste de interface, respeitar primeiro a identidade visual definida em public/identidade.html (cores, fontes, iconografia e componentes).


## Regra geral: 
Antes de implementar uma alteração, siga as tecnologias, arquitetura, convenções e restrições descritas neste documento. Caso alguma informação esteja ausente, analise o código existente e siga os padrões já adotados no projeto.
