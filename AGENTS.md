# AGENTS.md

## Visao geral

Projeto academico baseado em Dofus, com foco no site KamaFarm.

Objetivo inicial:
- criar pagina principal
- criar login e cadastro
- criar dashboard simples

## Tecnologias (inicio)

- Node.js
- Express
- MySQL
- HTML, CSS e JavaScript puro

## Arquitetura basica

Manter o fluxo simples:
1. Front-end em `public/` chama `fetch(...)`
2. Rota em `src/routes/`
3. Controller em `src/controllers/`
4. Model em `src/models/`
5. Query executada por `src/database/config.js`

## Padrao de implementacao

- seguir estrutura por recurso: rota + controller + model
- manter codigo didatico e simples para iniciante
- evitar mudancas grandes sem necessidade

## Identidade visual v2 (base atual)

Esta identidade deve ser usada como referencia principal neste momento.

### Cores principais

- `#8AB922` verde principal (botao Jogar e destaque)
- `#0F3B0B` verde escuro (botao secundario)
- `#F4C020` amarelo (acoes e titulos de destaque)
- `#F0A83A` laranja-ouro (subtitulos)
- `#FFFFFF` branco (titulos e menu)
- `#BDBDBD` cinza claro (textos secundarios e links de rodape)

### Fundos

- `#120D08` fundo geral da pagina
- `#16110E` barra/menu do topo
- `#2A1D14` secoes de apoio
- `#2D2050` cartoes/area de noticias
- `#0F2A2E` secao de forum
- `#000000` rodape

### Fontes

- `Montserrat`: menu, titulos grandes, botoes e subtitulos
- `Bebas Neue`: titulos de secao e botoes amarelos
- `Roboto`: textos corridos e conteudo geral
- `Cinzel`: uso opcional em destaque visual

### Componentes visuais (inicio)

- menu superior escuro com links brancos
- botao principal verde e botao secundario verde escuro
- botao amarelo para CTA de destaque
- secoes com fundo escuro e contraste alto
- rodape preto com links em cinza claro

### Rodape obrigatorio

"Projeto academico sem fins lucrativos. Dofus e suas imagens pertencem a Ankama Games. Dados e imagens: DofusDB."

## Regra geral

Para este comeco, manter tudo simples, consistente e alinhado com a identidade visual v2. Depois podemos expandir este AGENTS.md aos poucos.
