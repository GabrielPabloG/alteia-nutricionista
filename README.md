# Dra. Alteia Semiramis – Landing Page

Site profissional da nutricionista Dra. Alteia Semiramis.

## Estrutura

```
alteia-nutricionista/
├── index.html          # Página principal
├── src/
│   └── style.css       # Fonte CSS (Tailwind + custom styles)
├── style.css           # CSS compilado (gerado pelo build)
├── package.json        # Dependências e scripts npm
├── images/
│   └── alteia.jpg      # Foto da profissional
└── .gitignore
```

## Tecnologias

- **Tailwind CSS v4** — utilitário CSS via `@tailwindcss/cli`
- **HTML5** semântico com acessibilidade (skip-to-content, aria, focus trap)
- **CSS3** com variáveis, flexbox e media queries
- **Font Awesome 6.5** (CDN)
- **Google Fonts**: Playfair Display + Poppins
- **JSON-LD** — structured data (LocalBusiness + Person)

## Scripts

```bash
npm run dev    # Compila CSS em modo watch
npm run build  # Compila e minifica para produção
```

## Como rodar

```bash
npm install
npm run dev    # watch mode — abre index.html no navegador
```

Ou apenas abra `index.html` diretamente (sem servidor).
