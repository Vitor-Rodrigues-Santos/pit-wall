# 🏎️ Exercício Prático - PitWall (GP de São Paulo) 🏁

[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)]()
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)]()
[![Status](https://img.shields.io/badge/Status-Concluído-brightgreen?style=for-the-badge)]()

Este repositório contém o código front-end da página **PitWall**, desenvolvida como parte da atividade prática focada na estruturação semântica de uma *landing page* temática de Fórmula 1 (GP de São Paulo — Autódromo de Interlagos) e na estilização consistente em tema escuro (*dark mode*), garantindo total responsividade para dispositivos móveis e desktops.

---

## 🚀 Tecnologias Utilizadas

- **HTML5** (Estruturação semântica, navegação por âncoras, tabela de classificação e formulário completo de reserva)
- **CSS3** (Estilização centralizada, Variáveis nativas, CSS Grid, Flexbox, Gradientes e Media Queries)

---

## 📋 Atividade Desenvolvida

### 🖥️ 1. Estruturação da Página (`index.html`)
- **Descrição:** Construção de uma *landing page* temática completa sobre o Grande Prêmio de São Paulo de Fórmula 1, organizada em seções navegáveis e interativas.
- **Seções desenvolvidas:**
  - **Cabeçalho (`topbar`):** Barra de navegação fixa no topo com logotipo estilizado, links internos (`#pilotos`, `#classificacao`, `#ingressos`) e botão de chamada para ação.
  - **Banner Principal (`hero`):** Seção de destaque com título em tipografia de alto impacto, informações do evento em Interlagos (Novembro de 2026), botões de ação rápida e painel com dados técnicos do circuito (71 voltas, 4.309 km por volta e 15 curvas), seguido por uma faixa zebrada (`kerb`).
  - **Grid de Pilotos (`#pilotos`):** Vitrine em formato de *cards* destacando pilotos do grid (Charles Leclerc, Oscar Piastri, George Russell e Gabriel Bortoleto) com numeração estilizada e identificação visual por escuderia.
  - **Tabela de Classificação (`#classificacao`):** Área com campos de filtro por nome e equipe, além da tabela de pontuação com posições, vitórias, diferença para o líder e destaque visual para o primeiro colocado.
  - **Ingressos e Reserva (`#ingressos`):** Bloco informativo com alerta de disponibilidade, lista de preços por setor (Arquibancada A, Setor da Reta e Box VIP) e formulário completo para reserva de ingressos, envio de foto da torcida e mensagem para o piloto.
  - **Rodapé (`footer`):** Identificação do projeto de estudo e créditos de desenvolvimento.

### 🎨 2. Estilização e Design System (`style.css`)
- **Descrição:** Criação da identidade visual inspirada no automobilismo utilizando um único arquivo de estilos, focado em contraste, reaproveitamento de classes e adaptação para diferentes resoluções.
- **Recursos e técnicas aplicadas:**
  - **Paleta de Cores no `:root`:** Definição de variáveis globais (`--black`, `--panel`, `--line`, `--red`, `--white`, `--muted`) e variáveis específicas para cada equipe (`--ferrari`, `--mclaren`, `--mercedes`, `--audi`) para facilitar a manutenção e garantir consistência visual.
  - **Efeitos Visuais Temáticos:** Uso de `linear-gradient` diagonal combinado com imagem de fundo no banner principal e `repeating-linear-gradient` para construir a zebra de pista (`.kerb`) na transição entre seções.
  - **CSS Grid & Flexbox:** Organização dos *cards* de pilotos, da área de ingressos e dos campos do formulário em grade (`grid-template-columns`), aliada ao uso de Flexbox para alinhamento do cabeçalho, botões, filtros e estatísticas do circuito.
  - **Responsividade (Mobile & Desktop):** Uso de *media queries* (`@media (max-width: 900px)` e `@media (max-width: 600px)`) adaptando o banner principal, empilhando colunas de *cards*, formulários e filtros, além de aplicar rolagem horizontal controlada na tabela de classificação.
  - **Componentização UI:** Criação de classes reutilizáveis para botões (`.btn-primary`, `.btn-outline`, `.btn-filter`), indicadores de posição (`.pos-box`, `.pos-1`), barras de cor por equipe e avisos de destaque.

---

## 👤 Repositório desenvolvido por:

**Nome:** Vitor Rodrigues Santos  
**Turma:** 1ID-DS
