# Iron Fit Bragança

**Landing Page Premium para Crossfit, Treinamento Funcional & Performance**

---

## Sobre o Projeto

O **Iron Fit Bragança** é uma landing page de alta conversão desenvolvida para uma box de Crossfit e academia em Bragança Paulista. O projeto foi reconstruído com padrão de agência internacional: **glassmorphism**, gradientes sutis, sombras em camadas, tipografia fluida e um sistema de animações próprio baseado em **Intersection Observer** — sem dependências de animação externas.

Faz parte do portfólio de demonstração da **Akamine Web Studio**, estúdio de desenvolvimento web sediado em Bragança Paulista.

---

## Destaques

- **UI/UX premium:** glassmorphism, bordas com gradiente em hairline, aurora gradients ambientes, grão sutil e grid no padrão de agência top.
- **Animações próprias (sem AOS):** reveals com *stagger*, parallax suave no hero, contadores animados, *marquee* de modalidades, micro-interações e *hover states* sofisticados — tudo com `transform`/`opacity` acelerados por GPU.
- **Tipografia fluida:** títulos e textos escalam com `clamp()` para harmonia perfeita do mobile ao desktop.
- **Mobile-first real:** menu *hamburger* animado (morph para “X”), painel glass e navegação por âncoras com *scroll* suave.
- **Performance:** `preconnect`/`dns-prefetch`, *lazy loading* via Intersection Observer com *skeleton shimmer*, imagem do hero com `fetchpriority="high"`, scripts `defer` e animações *GPU-accelerated*.
- **Acessibilidade (WCAG AA):** *skip link*, `aria-label`/`aria-expanded`, *focus states* visíveis, tabela com `scope`/`caption`, status do formulário com `aria-live` e suporte completo a `prefers-reduced-motion`.

---

## Stack Tecnológica

| Tecnologia | Uso |
|------------|-----|
| HTML5 | Estrutura semântica e acessível (single-file) |
| Tailwind CSS (CDN) | Design system utilitário e responsivo |
| CSS custom + Intersection Observer | Reveals, parallax, contadores e lazy loading |
| Lucide Icons (CDN) | Ícones modernos e consistentes |
| Google Fonts | Space Grotesk (títulos) + Inter (corpo) |
| JavaScript Vanilla | Interatividade, menu, formulário e observers |

---

## Seções do Site

1. **Hero** — Full-screen com parallax, badge glass, estatísticas com contador animado e card visual flutuante
2. **Marquee** — Faixa contínua com as modalidades (prova social/identidade)
3. **Modalidades** — 6 cards glass com hover de imagem e *stagger reveal*
4. **Diferenciais** — Por que escolher a Iron Fit, com imagem e grid de benefícios
5. **Planos** — 3 tiers (Starter, Athlete, Elite) com destaque visual no plano popular
6. **Horários** — Tabela semanal acessível, gerada via JS
7. **Aula Experimental** — Formulário com *loading state* e confirmação acessível
8. **Footer** — Contato, redes sociais, funcionamento e créditos

---

## Sistema de Cores

- **Base:** `#08090b` / `#0d0f12` (ink)
- **Ember (primária):** `#FF6A2C`
- **Lime (secundária):** `#34D399`
- **Texto:** `#e7e9ee` · **Mist (mutado):** `#9aa3b2`

A identidade fitness/energia é mantida com a dupla laranja + verde, agora em tons mais refinados e com gradientes suaves.

---

## Como Visualizar

Abra o arquivo `index.html` diretamente em qualquer navegador moderno. Não requer build ou servidor.

```bash
# Ou inicie um servidor local simples
npx serve .
```

---

## Créditos

- **Desenvolvimento:** [JulioAkaminee](https://github.com/JulioAkaminee)
- **Design & Estratégia:** [Akamine Web Studio](https://akaminewebstudio.com.br)
- **Localização:** Bragança Paulista, SP

---

## Licença

Este projeto é de uso exclusivo para demonstração e portfólio da Akamine Web Studio.
