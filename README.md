# AWJE | High-End Corporate Interface 💎

Interface institucional desenvolvida para o setor de **Infraestrutura de Missão Crítica**. O projeto une estética *High-End* com rigor técnico, focando em performance, hierarquia visual matemática e experiência do usuário (UX) imersiva.

![Project Status](https://img.shields.io/badge/Status-Finished-00f2ff?style=for-the-badge)
![Design System](https://img.shields.io/badge/Design-High--End-25d366?style=for-the-badge)

## 🎨 Engenharia de Design (Style System)

Este projeto não utiliza frameworks prontos (como Bootstrap). Todo o sistema visual foi construído do zero com base em **Psicologia da Gestalt** e **Matemática Visual**:

* **Ritmo Vertical de 160px:** Implementação de uma "Régua de Ouro" de espaçamento (`160px`) entre todas as seções mestras. Em áreas de transição, utilizamos a soma lógica de blocos (80px + 80px) para manter a consistência geométrica perfeita.
* **Glassmorphism Ancorado:** Uso de containers translúcidos (`rgba(255,255,255,0.02)`) com bordas sutis para agrupar métricas, evitando a sensação de "flutuação" de conteúdo e melhorando a carga cognitiva.
* **Tipografia Escalonável:** Títulos e textos responsivos utilizando `clamp()` e unidades relativas (`rem`), garantindo leitura fluida de celulares a telas 4K.

## 🚀 Performance & Otimização

O código foi auditado para garantir carregamento instantâneo e nota máxima em Core Web Vitals:

* **Zero Bloatware:** Javascript Vanilla (Puro) sem dependências externas pesadas.
* **Ativos Otimizados:** Imagens comprimidas via **TinyPNG** e ícones vetorizados (SVG) para nitidez infinita com peso mínimo.
* **Código Minificado:** CSS e JS processados via **Minifier.org** para redução de requisições.
* **Trava de Layout:** CSS robusto com `max-width: 100vw` e `overflow-x: hidden` para impedir quebra de layout em dispositivos móveis.

## 🛠️ Tecnologias

* **HTML5 Semântico:** Estrutura acessível e otimizada para SEO.
* **CSS3 Advanced:**
    * CSS Variables (`:root`) para consistência de paleta.
    * Flexbox & CSS Grid para layouts complexos.
    * Media Queries fluídas para Mobile First.
    * Animações via `cubic-bezier` para suavidade "premium".
* **JavaScript (ES6+):** Manipulação de DOM para menu responsivo e efeitos de scroll.

## 📂 Instalação e Visualização

1.  **Clone o repositório:**
    ```bash
    git clone [https://github.com/SEU-USUARIO/awje.git](https://github.com/SEU-USUARIO/awje.git)
    ```
2.  **Abra o projeto:**
    Basta abrir o arquivo `index.html` em qualquer navegador moderno.

---

### 💡 Nota da Desenvolvedora
Este projeto é um estudo de caso sobre como transformar interfaces corporativas tradicionais em experiências digitais de alto valor agregado, priorizando o "Respiro" (White Space) e a precisão no alinhamento.

Desenvolvido por **[Indianara Bueno / AWJE]**.