# 📱 Browser Guess PT-BR

> Um jogo estilo *Heads Up!* / *Charadas* web-first, criado para jogar diretamente no navegador do celular. Coloque o aparelho na testa e deixe os amigos darem dicas enquanto você acerta ou pula inclinando o celular ou usando gestos!

---

## ✨ Funcionalidades

* 🔄 **Controle por Sensores (Giroscópio):** Incline o celular para baixo (tela para o chão) para **Acertar** ou para cima (tela para o teto) para **Pular**[cite: 2].
* 👆 **Alternativa por Toque/Deslize:** Funciona também com gestos de deslizar na tela (*swipe*) ou toques diretos.
* 📚 **Diversos Temas Ampliados:** Inclui Animais, Comidas, Músicas & Bandas, Famosos, Filmes, Desenhos & Animes, Esportes, Profissões, Lugares Famosos, **Ciências** (teoremas, equações e conceitos exatos), Games, Objetos da Casa, Mímica (Ações) e um modo **Misto**!
* ⏱️ **Tempos Personalizados:** Escolha entre rodadas de 30s, 1min, 1m30s ou 2 minutos.
* 🔊 **Efeitos Sonoros & Vibração:** Feedback tátil e sonoro nativo utilizando a Web Audio API (sequências de notas, som de acerto, erro/pular, contagem regressiva e combos).
* 🎨 **Layout Dinâmico e Responsivo:** Otimizado para encaixar perfeitamente na tela do celular sem necessidade de rolagem vertical, com suporte a modo paisagem e retrato.
* 🌐 **Pronto para Web (HTTPS):** Totalmente compatível com APIs de orientação de tela em navegadores mobile modernos via PWA/GitHub Pages.

---

## 🚀 Como Jogar

1. Acesse o site oficial do jogo pelo navegador do seu smartphone (Certifique-se de que está rodando em **HTTPS** para liberar os sensores de movimento).
2. Na tela inicial, escolha o **Tema** desejado e o **Tempo** da rodada.
3. Clique em **Jogar agora**, posicione o celular na testa com a tela virada para os seus amigos.
4. O jogo iniciará uma contagem regressiva de 3 segundos.
5. **Para Pontuar:**
   * **Acertou:** Incline o celular para baixo (ou deslize/toque na tela)[cite: 2].
   * **Pulou:** Incline o celular para cima (ou deslize/toque para pular)[cite: 2].
6. Ao final do tempo, confira o resumo detalhado de todas as palavras da rodada e sua pontuação final!

---

## 🛠️ Tecnologias Utilizadas

* **HTML5** & **CSS3** (Variáveis CSS, Grid, Flexbox, Animações e Design Responsivo).
* **JavaScript Vanilla (ES6+)** (Lógica de jogo, manipulação de estado, Web Audio API e rotação de arrays).
* **Device Orientation API** (Leitura de sensores de inclinação `beta` e `gamma` para detecção de movimento na testa).
* **Font Awesome** (Ícones modernos).
* **Google Fonts** (Tipografia *Fredoka*).

---

## 📦 Como Instalar e Rodar Localmente

Como o jogo utiliza os sensores de orientação do dispositivo (`DeviceOrientationEvent`), os navegadores modernos exigem um ambiente seguro (**HTTPS**) para liberar o acesso ao giroscópio no celular. A forma mais fácil de testar é hospedando gratuitamente no **GitHub Pages**:

1. Clone este repositório ou baixe o arquivo `index.html`:
   ```bash
   
   [https://github.com/seu-usuario/browser-guess-ptbr.git]([https://github.com/seu-usuario/browser-guess-ptbr.git])
