# Cliente Todo Dia — Landing page (Astro)

Conversão para Astro da página `Cliente_Todo_Dia.html`.

```bash
npm install
npm run dev      # http://localhost:4321
npm run build    # gera dist/
```

- `src/pages/index.astro` — a página. No topo ficam as configurações da oferta
  (`checkoutUrl`, `spotsLeft`, `showSticky`, `showProvaSocial`).
- `src/components/ImageSlot.astro` — espaços de imagem ainda vazios. Para preencher,
  passe `src`, ex.: `<ImageSlot src={minhaFoto} ... />` (import de `src/assets`).
- `src/styles/colors_and_type.css` — design system Fi Digital (cores + fonte Sofia Pro).
- `public/fonts/` — arquivos da fonte Sofia Pro.
