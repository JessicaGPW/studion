# StudiOn · Homepage 🎤

Página institucional da **StudiOn**, empresa de produção de eventos e serviços. Projeto *front-end* feito a partir de um layout em Photoshop (`_design/home.psd`).

> **EN:** Responsive landing page built from a PSD layout, using modular CSS, a jQuery image slider and a newsletter form.

## Destaques técnicos

- **Do design ao código:** layout convertido a partir do arquivo `.psd`
- **CSS modular:** estilos divididos por componente (`_navbar`, `_hero`, `_home`, `_btn`, `_footer`, `_contacts`) com variáveis globais (`_variable.css`) e utilitários (`_utils.css`)
- **Slider de banners** com jQuery + Slick (autoplay e setas personalizadas)
- **Seção parallax** e página de **contato**
- **Formulário de newsletter** com envio de e-mail via SMTP.js *(credenciais de exemplo; não configurado para produção)*

## Stack

HTML5 · CSS3 · JavaScript · jQuery · Slick Carousel · live-server

## Estrutura

```
studion/
├── SRC/
│   ├── index.html        # Home
│   ├── contact.html      # Contato
│   ├── style.css         # importa os módulos de CSS
│   ├── CSS/              # _base, _navbar, _hero, _home, _footer...
│   ├── script.js         # slider e newsletter
│   └── images/
└── _design/home.psd      # layout original
```

## Como executar

```bash
git clone https://github.com/JessicaGPW/studion.git
cd studion
npm install
npx live-server SRC/
```

## Próximos passos

- [ ] Trocar o envio de e-mail no front-end por um endpoint seguro (ex.: função serverless)
- [ ] Publicar no GitHub Pages
- [ ] Adicionar capturas de tela a este README

## Autora

**Jessica Baptista** · [GitHub](https://github.com/JessicaGPW) · [LinkedIn](https://www.linkedin.com/in/baptistajessica/)
