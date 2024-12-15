# Relatório de Entrega Final – RUNCOLLECTOR

## **Descrição do Jogo**

O **RUNCOLLECTOR**  o jogador assume o papel de uma personagem que deve atravessar níveis repletos de obstáculos, especialmente picos afiados. A principal tarefa é evitar o contacto com esses picos, uma vez que tocá-los resulta em perda de progresso, e num Game Over. Ao longo do jogo, o jogador deve recolher moedas espalhadas pelos diferentes cenários, o que leva ao aumento da pontuação. Com o avanço nos níveis, a dificuldade cresce, aumentando a complexidade do jogo. O objetivo do jogo é o jogador então ultrapassar os obstáculos e recolher o maior número possível de moedas, enquanto tenta alcançar o melhor resultado possível.

Este projeto foi desenvolvido por Matilde Silva (up202305722@edu.fe.up.pt), Tiago Almeida (up202303450@edu.fe.up.pt) e Sérgio Almeida (up202305946@edu.fe.up.pt) para a disciplina de LDTS 2024, na FEUP.

---

## **Funcionalidades Implementadas**

### **Movimentação da Personagem**

O jogador pode controlar a personagem com as teclas W, A, D:
- **W**: para saltar.
- **A**: para mover para a esquerda.
- **D**: para mover para a direita.

### **Menu do Jogo**
O jogador pode navegar, com a seta para cima e para baixo, pelo Menu Principal com as opções:
- **Play**: para iniciar o jogo.
- **Score**: para ver o seu score, que é dado pelas moedas recolhidas que se encontrão espalhadas pelo cenário.
- **Levels**: para aceder aos diferentes níveis do jogo.

### **Interface do Utilizador**
- A interação no **jogo** é realizada com as teclas **WAD**, enquanto no **menu** é feita através da seta para baixo e para cima, como referido anteriormente. Para além disso, para fechar o jogo usa-se a tecla Escape.

---
### **Deteção de colisões**

O jogo deteta colisões entre o jogador e obstáculos, os picos, fazendo com que o jogador recomece quando colide com um.

### **Diferentes níveis**
1.
???
O jogo inclui níveis com dificuldade crescente, onde os obstáculos se tornam mais desafiadores.

---

## **Funcionalidades Planeadas**

Todas as funcionalidades planeadas foram implementadas com sucesso, pois decidimos não colocar mais nenhum obstáculo para além dos picos.

### **Interface Gráfica**

Introduziu-se elementos gráficos para melhorar a experiência visual do jogo.

---

2. ??## **Design**
##**UML** ???
### **Estrutura Geral**
3.??
#### **Problema no Contexto**
4.??
A criação de um ambiente interativo e dinâmico foi um desafio, especialmente no que diz respeito à movimentação e resposta aos obstáculos.

####**Mockups em Pixel Art**
-	Utilizámos mockups em pixel art para representar a personagem, as moedas, os obstáculos e os diversos cenários do jogo.
Assegurámos que todas as imagens da personagem estão preparadas no formato correto (PNG) e que possuem as dimensões adequadas (16x16 pixels). Os restantes mockups mostram as fases do jogo, estas dimensionadas a 64x64 pixels.
## **Mockups da personagem e de etapas do jogo (*):**
-Menu (demonstração). 
![menu_este](https://github.com/user-attachments/assets/1ad101d7-86f5-42a4-819a-33d75dce36e7)
-Running in Front, a partir da tecla D para se mover para a direita (demonstração em pixel art 16x16). 
![IMG-20241122-WA0041](https://github.com/user-attachments/assets/0b8ce8d4-558f-44f1-af59-c7de05402c76)
-Running backwards, a partir da tecla A para se mover para a esquerda (demonstração em pixel art 16x16).
![IMG-20241122-WA0042](https://github.com/user-attachments/assets/3948330a-c2c4-4b2c-ab3b-4f9f21d9810d)
-Jump, a partir da tecla W para saltar (demonstração em pixel art 16x16).
![IMG-20241122-WA0039](https://github.com/user-attachments/assets/06c21202-536e-4f2a-9ad9-141dc0c18e96)
-Collecting coins (demonstração em pixel art 64x64).
![IMG-20241122-WA0043](https://github.com/user-attachments/assets/f2463dae-0122-4e67-853d-b8d77d8df71f)
-Game Over caso personagem não salte, com a implementação de "picos" mostra-se que a dificuldade acresce com este novo obstáculo. (demonstração em pixel art 64x64)
![IMG-20241122-WA0040](https://github.com/user-attachments/assets/39ddf583-f01e-45bb-a39c-d26bc911a4d0)

#### **Padrões de Design**
5. ?????
Foram utilizados os seguintes padrões de design:
### **Modelo-Visão-Controlador (MVC)**
- A separação das responsabilidades do jogo em três camadas principais:
  - **Modelo**: lógica do jogo e gestão de dados.
  - **Visão**: interface gráfica e apresentação dos elementos.
  - **Controlador**: manipulação de eventos e coordenação entre modelo e visão.

### **Singleton**
- Utilização do padrão **Singleton** para a **gestão do estado do jogo**, permitindo que informações como a pontuação, o nível e o progresso sejam acessíveis de forma centralizada.

---
#### **Implementação**
6.????
O código foi estruturado com base em princípios de design orientados a objetos, utilizando os padrões para modularizar as diferentes partes do sistema.

#### **Consequências**
7.???
Esses padrões trouxeram maior clareza ao código, facilitaram a manutenção e a adição de novas funcionalidades.

---

### **Observadores e Listeners**
8.???
O padrão **?** foi utilizado para tratar a comunicação eficiente entre os eventos de input e o estado do jogo.
---

### **Diferentes Tipos de Comandos**
9.???
???O padrão **?** foi utilizado para tratar as interações do jogador com o jogo...???

---

### Interface Gráfica (GUI)
10.??
???O padrão **?** foi aplicado para simplificar a interação com a biblioteca Lanterna, tornando o código mais organizado.

---
## Problemas conhecidos de código

Todos os erros conhecidos foram corrigidos, e não há problemas significativos no código.

---

## Testes
11.
???

### Testes de mutação
12.
??
---

## Autoavaliação
13.
??
A distribuição de tarefas foi feita de forma ??. Este trabalho ajudou a melhorar os nossos conhecimentos em Java e em princípios de design.

- **Matilde Silva**: ?%
- **Tiago Almeida**: ?%
- **Sérgio Almeida**: ?%

