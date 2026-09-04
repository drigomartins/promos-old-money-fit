# Promos Old Money Fit

Landing page estática para captação de membros do grupo de promoções fitness com estética Old Money.

## Visão geral

A página foi construída em HTML com estilização baseada em Tailwind via CDN e CSS customizado inline.

Principais objetivos:

- Apresentar proposta de valor do grupo
- Reforçar prova social com depoimentos
- Direcionar o usuário para o grupo de WhatsApp por CTA

## Estrutura do projeto

- `index.html`: página principal
- `images/`: imagens e logo usados na landing page

## Tecnologias usadas

- HTML5
- Tailwind CSS (CDN)
- Iconify (CDN)
- CSS customizado

## Como executar localmente

Como é um projeto estático, você pode abrir o arquivo `index.html` diretamente no navegador.

Opcionalmente, rode um servidor local para facilitar testes:

### Com Python

```bash
python -m http.server 5500
```

Depois acesse:

```text
http://localhost:5500
```

## Personalizações comuns

- Trocar logo: substitua o arquivo em `images/` e ajuste o `src` no `header`
- Alterar link do grupo: edite o `href` do botão principal (id `hero-cta`)
- Atualizar cores: edite as variáveis CSS em `:root`
- Ajustar textos: edite títulos, subtítulos e depoimentos no `index.html`

## Publicação

Pode ser publicado em qualquer host estático:

- GitHub Pages
- Netlify
- Vercel (modo estático)
- Cloudflare Pages

## Licença

Uso privado/comercial conforme necessidade do projeto. Ajuste esta seção caso queira uma licença específica (MIT, Apache-2.0 etc.).
