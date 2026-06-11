## 🌎 Visão Geral do Projeto: **Regenera Terra**

O **Regenera Terra** é uma landing page conceitual, interativa e imersiva para uma *Climate Tech* focada em agricultura regenerativa. O site funciona como uma experiência de "rolagem vertical" que leva o usuário em uma jornada que vai desde o topo da atmosfera até as profundezas do subsolo terrestre, ensinando sobre sustentabilidade e tecnologia no campo.

---

## 🛠️ Funcionalidades Principais

* **Jornada em Camadas (Scroll Visual):** O site é dividido em quatro seções temáticas (Atmosfera, Dossel Vivo, Nível do Solo e Subsolo). Conforme o usuário rola a página, a cor do fundo muda suavemente usando a API `IntersectionObserver` do JavaScript, criando uma transição natural de ambientes.
* **Termômetro do Equilíbrio (Gamificação):** Um elemento fixo na lateral monitora a saúde ecológica da fazenda virtual.
* **Botões de Ações Positivas** (como "Ativar Biofertilizantes") aumentam a pontuação e dão um feedback visual brilhante e verde.
* **Botões de Ações Negativas** (como "Uso de Pesticidas Químicos") reduzem a pontuação, deixando o termômetro em estado de alerta (vermelho).


* **Cápsula do Tempo Dinâmica:** Na última seção, o usuário pode digitar seu nome e uma mensagem para os agricultores do futuro (ano 2050). Ao enviar, os dados são salvos no navegador (`localStorage`), o formulário desaparece com uma animação fluida e dá lugar a um certificado.
* **Emissão e Impressão de Certificado:** O usuário recebe um "Certificado Digital de Compromisso com a Terra" gerado em tempo real com seu nome e a data atual, contendo uma função em JavaScript para abrir a janela de impressão do sistema.

---

## 📐 Estrutura de Arquivos e Design

### 🗂️ Arquivos do Projeto

1. **`index.html`:** Estrutura semântica do site, utilizando tags modernas do HTML5 como `<section>`, `<aside>` e organizando o conteúdo de forma acessível.
2. **`style.css`:** Identidade visual baseada em um estilo moderno de *Glassmorphism* (efeito de vidro fosco com `backdrop-filter`). Utiliza variáveis CSS para fácil manutenção de cores, tipografia fluida com `clamp()` e total responsividade para dispositivos móveis.
3. **`script.js`:** Concentra toda a lógica do site (mudança de cor de fundo, cálculo da pontuação do termômetro, manipulação do DOM na cápsula do tempo e o script de impressão do certificado).

### 🎨 Paleta de Cores Dinâmica

O CSS e o JavaScript trabalham juntos para alternar entre as cores das camadas da Terra:

* **Atmosfera:** Azul claro (`#9ddcff`)
* **Dossel Vivo:** Verde floresta (`#2d8f5d`)
* **Nível do Solo:** Marrom terra (`#9b7349`)
* **Subsolo:** Marrom escuro/Preto (`#1d120c`)

---

## 🚀 Tecnologias Utilizadas

* **HTML5** (Estrutura Semântica)
* **CSS3 moderno** (Grid Layout, Flexbox, Variáveis CSS, Glassmorphism, Media Queries)
* **JavaScript Vanilla** (Manipulação de DOM, Event Listeners, LocalStorage, API `IntersectionObserver`, Window Management)

