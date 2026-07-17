# Legal Sanity Brasil — site institucional

Site estático em HTML puro (sem build), pronto para GitHub + Vercel.

## Estrutura
```
/
├── index.html
├── assets/
│   └── logo.png
└── README.md
```

## Como publicar

### 1. GitHub
1. Crie um repositório novo (ex: `legal-sanity-brasil`).
2. Suba estes arquivos mantendo a pasta `assets/` junto do `index.html` (a imagem é referenciada como `assets/logo.png`, então o caminho relativo precisa ser preservado).

### 2. Vercel
1. Em vercel.com, clique em **Add New → Project**.
2. Importe o repositório do GitHub.
3. Framework preset: **Other** (site estático). Não é necessário build command nem output directory — deixe em branco ou aponte para a raiz (`.`).
4. Clique em **Deploy**.
5. Depois, em **Settings → Domains**, adicione `legalsanitybrasil.com.br` e siga as instruções de DNS mostradas pela Vercel (geralmente um registro `A` ou `CNAME` no seu provedor de domínio).

## O que já está pronto
- Botão de WhatsApp funcional (topo, seção final e botão flutuante) apontando para (12) 99163-2742, com mensagem pré-preenchida.
- Link de e-mail para contato@legalsanitybrasil.com.br.
- Link para o Instagram @legalsanitybrasil.
- Meta tags de SEO (título, descrição, Open Graph) e dado estruturado (JSON-LD) para aparecer melhor em buscas.
- Site responsivo (celular, tablet, desktop).

## O que você pode querer trocar depois
- **Cores**: estão centralizadas no topo do `<style>`, dentro de `:root { ... }`.
- **Textos**: todos em português, direto no HTML — busque pela seção pelo `id` (ex: `id="servicos"`) para editar.
- **Domínio no `<link rel="canonical">` e nas meta tags Open Graph**: já apontam para `https://legalsanitybrasil.com.br/`.
