[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/rUa5vdmg)

# **Entrega Intermédia do Relatório do Projeto de LDTS**

## **Descrição Geral**
Até ao momento, conseguimos implementar algumas funcionalidades fundamentais do jogo e estabelecer uma estrutura sólida para o design e as mecânicas de jogo. Este relatório da entrega intermédia detalha as funcionalidades já implementadas, as funcionalidades ainda planeadas e os padrões de design adotados.

---

## **Funcionalidades Implementadas até ao Momento e que Iremos Implementar até à Data de Entrega Final do Trabalho**

### **Movimentação da Personagem**
- O jogador pode controlar a personagem através das teclas do teclado:
  - **W**: para saltar.
  - **A**: para mover para a esquerda.
  - **D**: para mover para a direita.
  - **S**: para parar.
(?)
(VER ATÉ SGEUNDA SE É COM WADS OU COM SETAS DO TECLADO)(?)
No jogo, o controlo é feito com as teclas **WASD**.

### **Apanhar Moedas**
- A personagem irá recolher moedas espalhadas pelo cenário, acumulando pontos no sistema de **Score**.

### **Menu do Jogo**  
(?) **VER ATÉ SEGUNDA SE JÁ SE IMPLEMENTOU ISTO** (?)
O menu inicial do jogo irá dispor de três opções principais:
- **Play**: para iniciar o jogo.
- **Score**: para visualizar a quantidade de moedas recolhidas.
- **Levels**: para aceder aos diferentes níveis do jogo.

No menu, a interação é realizada através do **mouse** ou **touchpad**.

---

## **Funcionalidades Planeadas**

As próximas etapas do desenvolvimento incluirão as seguintes adições:

### **Novos Obstáculos para Aumento Gradual da Dificuldade**  
(?) **VER ATÉ SEGUNDA SE JÁ SE IMPLEMENTOU ISTO** (?)
- A introdução de obstáculos adicionais, como **picos**, fará com que, caso o personagem caia sobre eles, se não saltar no tempo correto, e precise recomeçar.
- Implementação de obstáculos com aparência semelhante a um arbusto com olhos, que introduzirão um elemento visual e funcional ao jogo, de forma a aumentar o nível de dificuldade à medida que o jogador avança pelos diferentes níveis.

---

## **Design do Jogo**

### **Mockups em Pixel Art**
- Utilizámos **mockups** em pixel art para representar a personagem, as moedas, os obstáculos e os diversos cenários do jogo.  
Assegurámos que todas as imagens da personagem estão preparadas no formato correto (PNG) e que possuem as dimensões adequadas (16x16 pixels).

### **Interface do Utilizador**
- A interação no **jogo** é realizada com as teclas **WASD**, enquanto no **menu** é feita através do **mouse** ou **touchpad**, como referido anteriormente.

---

## **Estrutura de Design**

Até ao momento, aplicámos os seguintes padrões de design:

### **Modelo-Visão-Controlador (MVC)**
- A separação das responsabilidades do jogo em três camadas principais:
  - **Modelo**: lógica do jogo e gestão de dados.
  - **Visão**: interface gráfica e apresentação dos elementos.
  - **Controlador**: manipulação de eventos e coordenação entre modelo e visão.

### **Singleton**
- Utilização do padrão **Singleton** para a **gestão do estado do jogo**, permitindo que informações como a pontuação, o nível e o progresso sejam acessíveis de forma centralizada.

---

## **Próximos Passos**

Com base no progresso até ao momento, o nosso objetivo é implementar as seguintes funcionalidades e melhorias:

1. **A implementação de novos obstáculos para aumento dos níveis de dificuldade**, incluindo o arbusto com olhos e os picos, para aumentar a complexidade do jogo e adicionar desafios ao jogador.
2. **Melhoria do menu**, para exibir de forma concreta as moedas recolhidas ao clicar no **Score** e para permitir o acesso aos níveis de dificuldade através da opção **Levels**.
3. **Implementação dos mockups no jogo**, incluindo a integração de todos os elementos visuais preparados, garantindo que a experiência de jogo seja consistente com a estética em pixel art.

---

### Notas:
- **(?) VER ATÉ SEGUNDA SE JÁ SE IMPLEMENTOU ISTO (?)**: Fica a indicação para verificar até a data limite se os itens relacionados ao **Menu do Jogo** e aos **Novos Obstáculos** (picos) já estão implementados ou se ainda são necessários para a entrega intermédia.



## **Mockups da personagem:**
-Running in Front, a partir da tecla D para se mover para a direita.
![IMG-20241122-WA0041](https://github.com/user-attachments/assets/0b8ce8d4-558f-44f1-af59-c7de05402c76)

-Running backwards, a partir da tecla A para se mover para a esquerda.
![IMG-20241122-WA0042](https://github.com/user-attachments/assets/3948330a-c2c4-4b2c-ab3b-4f9f21d9810d)

-Jump, a partir da tecla W para saltar.
![IMG-20241122-WA0039](https://github.com/user-attachments/assets/06c21202-536e-4f2a-9ad9-141dc0c18e96)

-Collecting coins (demonstração)
![IMG-20241122-WA0043](https://github.com/user-attachments/assets/f2463dae-0122-4e67-853d-b8d77d8df71f)

-Game Over, demonstração com a implementação de "picos" que a dificuldade acresce com este novo obstáculo.
![IMG-20241122-WA0040](https://github.com/user-attachments/assets/39ddf583-f01e-45bb-a39c-d26bc911a4d0)

-Game Over, demonstração com a implementação de "picos" e "arbustro verde com olhos" que a dificuldade acresce ainda mais com este novo obstáculo além do já existente, os "picos".
