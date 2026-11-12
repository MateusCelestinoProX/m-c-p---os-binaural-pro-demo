# 🎧 Binaural Labs Pro — Interactive Portfolio Demo

[![Live Demo](https://img.shields.io/badge/Production-Live%20Demo-black?logo=vercel&logoColor=white)](https://m-c-p-os-binaural-pro-demo.vercel.app)
[![Demo Edition](https://img.shields.io/badge/Demo-Interactive%20Showcase-FF1E27.svg)](https://m-c-p-os-binaural-pro-demo.vercel.app)
[![Web Audio API](https://img.shields.io/badge/Web%20Audio-DSP%20Chain-30D158.svg)](https://developer.mozilla.org/en-US/docs/Web/API/Web_Audio_API)
[![Audio Bitrate](https://img.shields.io/badge/Bitrate-320%20kbps%20Stereo-FF9500.svg)](https://m-c-p-os-binaural-pro-demo.vercel.app)
[![WebGL](https://img.shields.io/badge/Shaders-37%20WebGL%20Effects-007AFF.svg)](https://m-c-p-os-binaural-pro-demo.vercel.app)
[![Offline Ready](https://img.shields.io/badge/Storage-IndexedDB%20Cache-9B51E0.svg)](https://m-c-p-os-binaural-pro-demo.vercel.app)

Instância de demonstração interativa de alta fidelidade do **Binaural Labs Pro**, concebida para portfólio de engenharia de software e áudio digital front-end. O software combina processamento de sinal em tempo real (DSP) com Web Audio API, aceleração por GPU via WebGL e uma experiência visual inspirada em glassmorphism e design Apple VisionOS.

🔗 **Acesse a Demonstração Online:** [https://m-c-p-os-binaural-pro-demo.vercel.app](https://m-c-p-os-binaural-pro-demo.vercel.app)

---

## ✨ Destaques da Experiência Demo

- **Tela Base de Apresentação & Entrada Coreografada:** A demonstração se inicia em uma base com telemetria visual de inicialização dos motores DSP. Ao entrar (automaticamente ou via clique), todo o layout do software é carregado através de uma animação suave em cascata escalonada (*staggered entrance*).
- **Catálogo Sanitizado em 320 kbps:** Áudios binaurais em estéreo de alta precisão substituem dados proprietários para preservação de privacidade, garantindo fidelidade acústica real:
  1. **Alpha Flow Wave (10 Hz):** Foco criativo, estado de flow e lucidez mental.
  2. **Theta Deep State (6 Hz):** Meditação profunda, intuição e sincronização hemisférica.
  3. **Delta Restorative (2.5 Hz):** Sono reparador, regeneração neural e repouso celular.
  4. **Gamma Hyper-Focus (40 Hz):** Cognição avançada, raciocínio rápido e alta concentração.
  5. **Solfeggio Frequency (528 Hz):** Ressonância harmônica e transformação energética.
  6. **Schumann Resonance (7.83 Hz):** Pulso eletromagnético da Terra e estabilidade neural.
- **Botão de Rever Apresentação:** Permite revisitar a tela base e a coreografia de animação a qualquer momento diretamente pelo cabeçalho.

---

## 🛠️ Arquitetura Técnica

### 1. Web Audio DSP Chain (Anti-Clipping & Amplificação)
Cada faixa de áudio e o canal master passam por uma cadeia de nós Web Audio API:
- `GainNode`: Controle preciso de volume e amplificação de ganho limpo até 4.0x.
- `DynamicsCompressorNode`: Limitador analógico simulado com curva suave para evitar distorção digital (*hard clipping*).
- `AnalyserNode`: Amostragem FFT em tempo real alimentando o canvas visualizador de espectro.

### 2. Mixagem Paralela e Time-Stretching
- Permite reproduzir múltiplas faixas simultaneamente sem conflito de áudio.
- Controle individual de `playbackRate` de **0.5x até 5.0x** com preservação de pitch e sincronia de loop.

### 3. Motor WebGL com 37 Shaders Nativos
- Shader engine baseado em WebGL/OGL com renderização a 60 FPS capped.
- Suspensão automática via `visibilitychange` (0% CPU/GPU quando a aba está em background).
- Efeitos visuais dinâmicos: *Aurora, Plasma Wave, Beams 3D, Liquid Chrome, Ferrofluid, Balatro Vortex, Dark Veil*, entre outros.

### 4. Persistência Offline com IndexedDB & Service Worker
- Banco de dados `BinauralLabsOfflineDB` que armazena os arquivos MP3 completos como `Blob` binário.
- Suporte a cache completo PWA offline sem interrupção de reprodução.

---

## 🚀 Como Executar Localmente

### Pré-requisitos
- Node.js 18+ ou qualquer servidor HTTP estático.

### Execução Rápida
```bash
# Clonar o repositório demo
git clone https://github.com/MateusCelestinoProX/m-c-p---os-binaural-pro-demo.git
cd m-c-p---os-binaural-pro-demo

# Iniciar servidor local
npm start
```
Ou utilizando `npx serve`:
```bash
npx serve . -l 3000
```
Abra seu navegador em `http://localhost:3000`.

---

## 👤 Autor

**Mateus Celestino**  
Engenheiro de Software & Desenvolvedor Full-Stack  
GitHub: [@MateusCelestinoProX](https://github.com/MateusCelestinoProX)
