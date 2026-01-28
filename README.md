<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0cba0c&height=120&section=header&text=FLAPPY_MARIO&fontSize=40&fontColor=ffffff&animation=fadeIn&fontAlignY=35"/>
  
  <br>

  <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white">
  <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white">
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black">
  <br>
  
  <h3>🍄 Meu primeiro passo no Desenvolvimento de Jogos</h3>
</div>

<br>

## 📖 Sobre o Projeto

O **Flappy_Mario** tem um valor especial: foi o meu **"Hello World"** no universo de Game Development. 

Desenvolvido com base em um tutorial para estudo de lógica, o objetivo aqui não foi criar um jogo comercial, mas sim **entender como um jogo funciona "por baixo do capô"**. Antes de partir para engines robustas como Unity, eu queria compreender como construir um **Game Loop**, detectar **colisões** e manipular **física básica** utilizando apenas JavaScript puro e o DOM.

---

## ⚙️ O que eu aprendi (Tech Breakdown)

Neste projeto, apliquei conceitos fundamentais de Front-End focados em jogos:

### 🧠 Lógica e JavaScript
* **Game Loop Manual:** Uso de `setInterval` para verificar o estado do jogo a cada 10ms.
* **Colisão Matemática:** Cálculo da posição dos elementos (`offsetLeft` e `bottom`) para detectar o momento exato em que o Mario encosta no tubo.
* **Controle de Estados:** Lógica para adicionar/remover classes CSS para simular o pulo e parar o jogo no "Game Over".

### 🎨 CSS e Animações
* **Keyframes:** Uso de `@keyframes` para criar o movimento infinito do cenário (Parallax simples nas nuvens e movimento do chão/tubos).
* **Performance:** Animações via CSS para deixar a thread do JavaScript livre para a lógica pesada.

---

## 🎮 Como Jogar

1.  Abra o arquivo `index.html` no navegador.
2.  Pressione a tecla **Espaço** para pular.
3.  Tente sobreviver o máximo de tempo possível!

---

## 🚀 Como Executar

```bash
# Clone o repositório
$ git clone [https://github.com/SEU-USUARIO/Flappy_Mario.git](https://github.com/SEU-USUARIO/Flappy_Mario.git)

# Acesse a pasta do projeto
$ cd Flappy_Mario

# Abra o index.html no navegador
