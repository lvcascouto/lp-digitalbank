<div align="center">

## <img src="assets/svg/logo-dark.svg" width="220" height="220" alt="Logo Digitalbank"/>

**Landing Page desenvolvida a partir de um desafio do Frontend Mentor**

*Projeto de estudo e prática com arquitetura AXIS*

[![Status](https://img.shields.io/badge/status-concluído-e8e4de?style=flat-square&labelColor=10b981&color=1c1b2e)](https://lvcascouto.github.io/lp-digitalbank/)&nbsp;
[![Desenvolvido com AXIS](https://img.shields.io/badge/desenvolvido%20com-AXIS-e8e4de?style=flat-square&labelColor=3437e6&color=1c1b2e)](https://github.com/lvcascouto/axis)&nbsp;
[![Finalidade](https://img.shields.io/badge/finalidade-estudo-e8e4de?style=flat-square&labelColor=orange&color=1c1b2e)](https://github.com/lvcascouto/axis)&nbsp;
[![Licença](https://img.shields.io/badge/licença-MIT-e8e4de?style=flat-square&labelColor=ef4444&color=1c1b2e)](./LICENSE)

</div>

<p align="center">
  <a href="#projeto">Projeto</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#o-que-pratiquei">O que pratiquei</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#tecnologias">Tecnologias</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#estrutura">Estrutura</a>
</p>

<br>

## PROJETO

Solução desenvolvida para o desafio [Digitalbank Landing Page](https://www.frontendmentor.io/challenges/digital-bank-landing-page-WaUhkoDN) do **Frontend Mentor**, utilizada como exercício prático para aplicar e validar o [AXIS](https://github.com/lvcascouto/axis), minha arquitetura Sass própria.

O objetivo foi além da reprodução visual do layout. O projeto foi desenvolvido para consolidar práticas de organização de estilos, utilização de design tokens, criação de componentes e construção de interfaces responsivas com menor dependência de media queries e conceitos imprecindíveis de acessibilidade.

A implementação também teve foco em **acessibilidade, tipografia fluida, composição de layouts com Flexbox e Grid e otimização do CSS para produção**.

🌐 [Acesse o projeto](https://lvcascouto.github.io/lp-digitalbank/)

## O QUE PRATIQUEI

- **Arquitetura AXIS** — aplicação das cinco camadas da arquitetura: abstracts, base, layout, components e sections
- **Design tokens semânticos** — organização de cores, tipografia, espaçamento e interações por meio de partials
- **Design fluido** — utilização de `clamp()`, Flexbox e Grid para criar layouts adaptáveis e reduzir a dependência de media queries
- **Responsividade** — utilização do mixin `respond()` para controle dos breakpoints e adaptação de elementos complexos
- **Acessibilidade** — aplicação de atributos ARIA, navegação por teclado com `:focus-visible`, links expansíveis via CSS sem quebrar o fluxo do leitor de tela e estrutura semântica
- **SEO e compartilhamento social** — configuração de meta tags, Open Graph, Twitter Card e URL canônica
- **Otimização de produção** — remoção de estilos não utilizados (UnCSS Online) e minificação do CSS via Live Sass Compiler para produção

## TECNOLOGIAS

| Tecnologia | Uso |
|---|---|
| HTML5 | Estrutura semântica e acessível |
| Sass/SCSS | Arquitetura modular AXIS e organização dos estilos |
| CSS3 | Layout, responsividade, tipografia fluida e interações |
| Live Sass Compiler | Compilação e minificação dos arquivos Sass/SCSS |
| UnCSS | Remoção de estilos não utilizados na versão de produção |
| Git/GitHub | Versionamento e publicação do projeto |

## ESTRUTURA

```
lp-digitalbank/
├── assets/
│   ├── favicon/             → favicon.png e apple-touch-icon.png
│   ├── fonts/               → ClashDisplay-Variable.ttf
│   ├── media/img/           → Mockups do hero e imagens dos articles
│   └── svg/                 → Logo e ícones
├── dist/
│   └── main.min.css         → CSS minificado e purgado (produção)
├── src/
│   ├── css/
│   │   └── main.css         → CSS compilado (desenvolvimento)
│   └── sass/
│       ├── abstracts/       → Tokens, funções e mixins (AXIS)
│       ├── base/            → Reset, tipografia, estilos globais e utilitários (AXIS)
│       ├── layout/          → Container e estruturas de layout (AXIS)
│       ├── components/      → Componentes reutilizáveis (AXIS)
│       ├── sections/        → Estilos específicos de cada seção
│       └── main.scss        → Ponto de entrada da arquitetura
└── index.html               → Página principal
```

## LICENÇA

O código deste projeto está licenciado sob a licença MIT — veja o arquivo [LICENSE](./LICENSE).  
O design original pertence ao [Frontend Mentor](https://www.frontendmentor.io) e está sujeito aos [termos de uso](https://www.frontendmentor.io/terms) da plataforma.

## AUTOR

Desenvolvido por [Lucas Couto](https://linkedin.com/in/lucascouto-dev).  
Veja meu trabalho em [Lucas Code](https://lvcascode.com.br).
