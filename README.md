<h1 align="center">
  LDTS_L03G05 - RunCollector
</h1>

## **FAZER ATÉ DIA 24 12:00 -> EM FALTA: IMPLEMENTED FEATURES, MOCKUPS, TESTS, UML, SELF EVALUATION**

<p align="center">
  <img src="https://github.com/user-attachments/assets/2a55d3d7-4e24-4259-bc18-be80ece03937" alt="Logo do Jogo"/>
</p>


**RunCollector** is a game where players collect coins while navigating through levels filled with sharp spikes and other hazards. The main objective is to gather as many coins as possible while skillfully avoiding obstacles that could lead to a Game Over. With progressively difficulty, **RunCollector** offers an engaging experience, testing players' reflexes and strategy as they strive to achieve the highest score.

> Developed by **Matilde Silva** (up202305722@edu.fe.up.pt), **Sérgio Almeida** (up202305946@edu.fe.up.pt), and **Tiago Almeida** (up202303450@edu.fe.up.pt) for **LDTS 2024** at **FEUP**.
---

## **IMPLEMENTED FEATURES**

* **Character Movement**:
  * `W`: Jump
  * `A`: Move left
  * `D`: Move right

* **Main Menu**:
  * Navigate with arrow keys (up and down).
  * Options:
    * **Play**: Start the game
    * **Exit**: Exit the game
    * **Levels**: Access different levels

* **User Interaction**:
  * Use `W`, `A`, `D` for in-game actions.
  * Use arrow keys for menu navigation.
  * Press `Escape` to exit the game.

* **Collision Detection**:
  * Detects when the player touches spikes, restarting the level.

* **Levels**:
  * Progressive difficulty with increasingly challenging obstacles.

FAZER

---

## **DESIGN**

### **General Structure**

* **Problem Context**:
  * Designing an interactive and dynamic environment was challenging, especially ensuring smooth movement and responsive collision mechanics.

* **Mockups in Pixel Art**:
  * Used pixel art mockups for characters, coins, obstacles, and various scenarios.
  * Character images: **16x16 pixels**.
  * Game levels: **64x64 pixels**.
    
    Characters and level design created with pixel art:
    -Menu
    ![IMG-20241217-WA0010](https://github.com/user-attachments/assets/6a8f33c1-c9c2-4e32-b5cd-518d36dc4fc5)
    -Running in Front (D)
    ![IMG-20241122-WA0041](https://github.com/user-attachments/assets/0b8ce8d4-558f-44f1-af59-c7de05402c76)
    -Running backwards (A)
    ![IMG-20241122-WA0042](https://github.com/user-attachments/assets/3948330a-c2c4-4b2c-ab3b-4f9f21d9810d)
    -Jump (W)
    ![IMG-20241122-WA0039](https://github.com/user-attachments/assets/06c21202-536e-4f2a-9ad9-141dc0c18e96)
    -Collecting coins 
    ![IMG-20241122-WA0043](https://github.com/user-attachments/assets/f2463dae-0122-4e67-853d-b8d77d8df71f)
    -How to lose
    ![IMG-20241122-WA0040](https://github.com/user-attachments/assets/39ddf583-f01e-45bb-a39c-d26bc911a4d0)


### **Design Patterns**

* **Model-View-Controller (MVC)**:
  * **Model**: Handles game logic and data management.
  * **View**: Manages graphical representation.
  * **Controller**: Handles event management and coordination.

* **Singleton**:
  * Centralized management of game state, including score, level, and progress.

* **Observer**:
  * Efficient event handling between player input and game state.

* **Command**:
  * Manages interactions between the player and the game.

* **Facade**:
  * Simplifies interaction with the **Lanterna** library for better code organization.

---

## **KNOWN ISSUES**

* No significant bugs were identified during testing.

---

## **TESTING**
FAZER

* Mutation testing was conducted to ensure code robustness.

---

## **RESOURCES**

* **Tools**:
  * **Lanterna**: Used for graphical interface and gameplay rendering.
    
---

## **UML CLASS STRUCTURES AND OVERVIEW**
FAZER

## **TEAM CONTRIBUTIONS**
COMPLETAR

* **Sérgio Almeida **: ??%
* **Matilde Silva**: ??%
* **Sérgio Almeida**: ??%
