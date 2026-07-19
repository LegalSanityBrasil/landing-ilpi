# Legal Sanity Brasil — Site Institucional

Site estático em HTML/CSS/JS puro. Hospedado na Vercel via GitHub.

## Stack
- HTML5 puro (sem framework)
- CSS puro com variáveis (design responsivo)
- JavaScript vanilla (sem dependências)
- Fontes: Fraunces, Inter, IBM Plex Mono (Google Fonts)

## Estrutura
```
/
├── index.html          ( página única com todas as seções )
├── assets/
│   ├── icon.png        ( ícone usado no cabeçalho e rodapé )
│   └── logo.png        ( backup/referência )
├── opencode.json       ( config do OpenCode )
└── AGENTS.md           ( contexto do projeto )
```

## Seções do site (âncoras)
- `#inicio` — Hero com selo animado e CTAs
- `#problema` — Riscos de não estar regularizado
- `#servicos` — Grid de 8 serviços
- `#segmentos` — Segmentos atendidos
- `#processo` — Etapas do processo
- `#diferenciais` — Diferenciais da empresa
- `#kits` — Kits de documentação (ILPI, Estética, Alimentos)
- `#faq` — Perguntas frequentes (accordion)
- `#contato` — CTA final

## Cores (variáveis CSS em :root)
- --navy: #112941
- --green: #2BAB4E
- --gold: #B98526
- --paper: #F6F7F2

## Contato
- WhatsApp: (12) 99163-2742
- E-mail: contato@legalsanitybrasil.com.br
- Instagram: @legalsanitybrasil

## Observações importantes
- O site é uma página única (single page)
- O selo giratório usa animação CSS
- Menu mobile é toggle com JavaScript
- Reveal on scroll usa IntersectionObserver
- JSON-LD para dados estruturados (SEO)
- Meta tags Open Graph e Twitter Cards
