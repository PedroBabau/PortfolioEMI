# 🌐 PORTFOLIO EMI – Projetos de Edições de Multimédia Interativas

Este repositório contém um portfólio interativo com temática **cyberpunk** desenvolvido no âmbito da Unidade Curricular **Edições de Multimédia Interativas**. O portfólio apresenta **8 projetos** organizados em **4 pares lógicos**, onde cada par partilha um repositório GitHub e cada projeto individual tem a sua própria página interativa.

---

## 🎯 Estrutura Geral do Portfólio

| Par | Tema | Projeto 1 | Projeto 2 |
|-----|------|-----------|-----------|
| 1 | Coding Interativo | Particle Storm | Sound Painter |
| 2 | Experiências 3D | Visualizador Orbital 3D | Realizador de Cinema |
| 3 | Dashboards | Dashboard GeoPulse | Dashboard API Explorer |
| 4 | AR & VR | NeonDex | CyberGallery |

Cada par possui:
- **Botão "REPOSITÓRIO"** → Acede ao repositório GitHub que contém ambos os projetos.
- **Botão "PÁGINA DO PROJETO"** (por projeto) → Acede à demonstração interativa hospedada (GitHub Pages / itch.io).

---

## 📁 Par 1: Coding Interativo
**Repositório:** [Coding_Interativo](https://pedrobabau.github.io/Coding_Interativo/)

### 🎨 Projeto 1.1 – Particle Storm
| Campo | Descrição |
|-------|-----------|
| **Objetivo** | Simular um sistema de partículas com comportamento emergente e interação em tempo real. |
| **Tecnologias** | JavaScript (Canvas/WebGL), HTML5, CSS3 |
| **Funcionalidades** | - Geração de centenas de partículas com física básica <br>- Interação com rato/teclado <br>- Efeitos visuais neon e rastros luminosos |
| **Acesso** | [Particle Storm Demo](https://pedrobabau.github.io/Coding_Interativo/projeto1/index.html) |

### 🎨 Projeto 1.2 – Sound Painter
| Campo | Descrição |
|-------|-----------|
| **Objetivo** | Pintar visualmente utilizando input de áudio (microfone ou ficheiros). |
| **Tecnologias** | Web Audio API, Canvas, JavaScript |
| **Funcionalidades** | - Análise de frequências em tempo real <br>- Mapeamento som → cor/intensidade <br>- Exportação de frames como imagem |
| **Acesso** | [Sound Painter Demo](https://pedrobabau.github.io/Coding_Interativo/projeto2/index.html) |

**Como se complementam:**  
Ambos exploram *multimédia interativa em tempo real* – um focado em simulação física visual, outro em resposta a áudio.

---

## 🎮 Par 2: Experiências 3D
**Repositório:** [Projeto_2_Experiencias_3D_Interativas_Unity](https://pedrobabau.github.io/Projeto_2_Experiencias_3D_Interativas_Unity/)

### 🚀 Projeto 2.1 – Visualizador Orbital 3D
| Campo | Descrição |
|-------|-----------|
| **Objetivo** | Visualizador 3D interativo com câmera orbital controlada por Slider UI. Aproxima e afasta a câmara em torno do objeto 3D. |
| **Tecnologias** | Unity, WebGL, C# |
| **Funcionalidades** | - Movimento orbital sobre a nave. <br>- Controlo de câmara com rato <br>- Interface com informações da posição da câmera face à nave |
| **Acesso** | [itch.io – Projeto A](https://pedrobpinheiro.itch.io/projeto-a-visualizador-orbital-3d) |

### 🎬 Projeto 2.2 – Realizador de Cinema
| Campo | Descrição |
|-------|-----------|
| **Objetivo** | Simular uma interface de realizador cinematográfico com gestão de cenas e câmaras. |
| **Tecnologias** | Unity, WebGL, Timeline |
| **Funcionalidades** | - Corte entre múltiplas câmaras <br>- Timeline para sequências pré-definidas <br>- Efeitos de pós-produção básicos |
| **Acesso** | [itch.io – Projeto B](https://pedrobpinheiro.itch.io/projeto-b-realizador-de-cinema) |

**Como se complementam:**  
Ambos utilizam motores 3D (Unity) para criar experiências imersivas – um focado em *espaço*, outro em *narrativa cinematográfica*.

---

## 📊 Par 3: Dashboards
**Repositório:** [MyDashboards](https://pedrobabau.github.io/MyDashboards/)

### 📈 Projeto 3.1 – Dashboard Analytics A
| Campo | Descrição |
|-------|-----------|
| **Objetivo** | Visualização artística baseada na sua localização geográfica real. Um globo 3D interativo que reage a país, cidade, coordenadas e fuso horário. |
| **Tecnologias** | Chart.js / D3.js, HTML/CSS, JavaScript |
| **Funcionalidades** | - Informação de localização em tempo real <br>- Animação em WebGL <br>- Design responsivo e dark mode |
| **Acesso** | [Dashboard 1](https://pedrobabau.github.io/MyDashboards/dashboard1/) |

### 📉 Projeto 3.2 – Dashboard Analytics B
| Campo | Descrição |
|-------|-----------|
| **Objetivo** | Explore dados de uma API gratuita (JSONPlaceholder). Carregue utilizadores aleatórios e interaja com o avatar: mude a cor e o tamanho em tempo real. |
| **Tecnologias** | Chart.js, WebSockets (simulado), JavaScript |
| **Funcionalidades** | - Randomizer de Utilizador <br>- Alertas visuais para thresholds <br>- Capacidade de alterar o estilo do avatar |
| **Acesso** | [Dashboard 2](https://pedrobabau.github.io/MyDashboards/dashboard2/) |

**Como se complementam:**  
Ambos exploram *visualização de dados* – um focado em informações em tempo real, outro em aleatoridade de formação de informação e manipulação estética da mesma.

---

## 🥽 Par 4: AR & VR
**Repositório:** [ProjetoARVR](https://pedrobabau.github.io/ProjetoARVR/)

### 🕶️ Projeto 4.1 – NeonDex
| Campo | Descrição |
|-------|-----------|
| **Objetivo** | Experiência de Realidade Aumentada baseada em marcador personalizado. Alimente e dê água a um animal 3D interativo. |
| **Tecnologias** | AR.js (ou A-Frame), JavaScript, HTML5 |
| **Funcionalidades** | - Deteção de marcadores <br>- Modelos 3D animados com efeitos <br>- Interação toque/clique |
| **Acesso** | [Projeto ARVR Demo](https://pedrobabau.github.io/ProjetoARVR/AR/index.html) |

### 🌌 Projeto 4.2 – CyberGallery
| Campo | Descrição |
|-------|-----------|
| **Objetivo** | Experiência de Realidade Virtual imersiva com cenários 360° e navegação por olhar (gaze). |
| **Tecnologias** | A-Frame / Three.js, JavaScript |
| **Funcionalidades** | - Navegação por mapas virtuais <br>- Robô feito com formas geométricas simples <br>- Suporte a dispositivos móveis com giroscópio |
| **Acesso** | [Projeto ARVR Demo](https://pedrobabau.github.io/ProjetoARVR/VR/index.html) *(mesmo link, diferentes secções)* |

**Como se complementam:**  
Ambos exploram *realidade aumentada/virtual* – um com foco em AR por marcadores, outro com galeria VR imersiva.

---

## 🎨 Interface Cyberpunk – Funcionalidades Técnicas

| Elemento | Descrição |
|----------|-----------|
| **Efeito Glitch** | Título com animação de tremor e sombras magenta/ciano |
| **Scanlines** | Overlay de linhas horizontais que simula ecrã CRT antigo |
| **Cards Neon** | Bordas brilhantes (#0ff) com glow ao hover e transições suaves |
| **Botões** | Estilo transparente com bordas neon, invertem cor ao hover |
| **Responsividade** | Layout adapta-se a telemóveis/tablets (max-width: 780px) |
| **Acessibilidade** | Links abrem em nova aba com `noopener/noreferrer` |

---
