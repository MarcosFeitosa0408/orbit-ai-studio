# ORBIT AI Studio — Content Intelligence

**Protótipo interativo de análise de conteúdo e criação de campanhas** desenvolvido para demonstração de recursos de Business Intelligence, visualização de dados e storytelling.

## Abrir a aplicação

Depois de habilitar GitHub Pages em **Settings → Pages → Deploy from a branch → main → /(root)**:

https://marcosfeitosa0408.github.io/orbit-ai-studio/

Você também pode baixar e abrir `index.html` no navegador, sem instalar dependências.

## Funcionalidades implementadas
- Dashboard de publicações com indicadores, gráficos e ranking
- Upload de CSV e validações de dados, sem envio a servidores
- Conjunto fictício de demonstração e exportação de CSV
- Estúdio editorial: ganchos, legendas, roteiro e carrossel de 7 cards por **templates locais**
- Apresentação navegável em 9 slides e impressão em PDF pelo navegador
- Interface responsiva com navegação e interações em JavaScript

## Modelo de CSV

Campos obrigatórios:

`titulo;plataforma;visualizacoes;curtidas;comentarios;compartilhamentos;cliques;data`

Campo opcional: `tema`. Datas ISO (`AAAA-MM-DD`) ou `DD/MM/AAAA`. Números inteiros não negativos.

## Limitações
Este é um **protótipo funcional**, não uma integração ativa com modelos generativos ou agentes autônomos. O fluxo multiagente é ilustrativo. Não existe busca automática de tendências, publicação nas redes sociais ou autenticação. Não introduza tokens ou credenciais privadas no HTML.

## Próximas etapas
Backend Python/FastAPI, persistência PostgreSQL, integração com LLM, orquestração de agentes, autenticação, logs e testes.

Inspirado conceitualmente no guia sobre Hermes Agent; projeto independente, sem afiliação à Nous Research.

**Autor:** Marcos Feitosa — https://marcosfeitosa-dev.com.br/
