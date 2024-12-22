<h1 align="center">
  LDTS_L03G05 - Jumping Jack
</h1>

## **FAZER ATÉ DIA 24 12:00 -> EM FALTA: IMPLEMENTED FEATURES, MOCKUPS, TESTS, UML, SELF EVALUATION**

**Jumping Jack** is a 2D platform game where players collect coins while navigating through levels filled with sharp spikes and holes. The main goal is to gather as many coins as possible while skillfully avoiding obstacles that could lead to a Game Over. With progressively difficulty, **Jumping Jack** offers an engaging experience, testing players' reflexes and strategy as they strive to achieve the highest score in order to see the suprising ending.

> Developed by **Matilde Silva** (up202305722@edu.fe.up.pt), **Sérgio Almeida** (up202305946@edu.fe.up.pt), and **Tiago Almeida** (up202303450@edu.fe.up.pt) for **LDTS 2024** at **FEUP**.
---

## **IMPLEMENTED FEATURES**

* **Character Movement**:
  * `^`: Jump
  * `<`: Move left
  * `>`: Move right

* **Main Menu**:
  * Navigate with arrow keys (up and down).
  * Options:
    * **Play**: Start the game in level 1
    * **Exit**: Exit the game
    * **Levels**: Access different levels
  *Escape to stop exectuting the game.
      
* **Platforms**:
  *
      
* **Collision Detection**:
  * Detects when the player touches spikes, restarting the level.

* **Levels**:
  * There are 10 different levels with progressive difficulty by increasing challenging obstacles.

* **Spikes and Holes**:
  *


* **Coins**:
  * + sound of collecting coin

* **Gravity**:
  *
---

## **DESIGN**

### **General Structure**

* **Problem Context**:
  * Designing an interactive and dynamic environment was challenging, especially ensuring smooth movement and responsive collision mechanics.
    
* **Mockups**:
  -Menu
  ![image](https://github.com/user-attachments/assets/4e65e5ed-a3d9-48b5-ae70-44e42a693fe8)

  -Levels
  ![image](https://github.com/user-attachments/assets/ce295470-6a21-4078-8495-0310317488b8)

  -Instructions
  (> arrow to run in front)
  ![image](https://github.com/user-attachments/assets/5f968aff-387b-4533-8f72-e45cf3ce2cf9)
  
  (^ arrow to jump for the green platform, otherwise the player will loose, by falling in the hole)
  ![image](https://github.com/user-attachments/assets/1d7dac38-5087-4e2e-98c9-9b33c9c5af0b)

  (the player lose if he doesn't jump over the spike)
  ![image](https://github.com/user-attachments/assets/679696ba-327f-4947-9804-95b25039c50d)
  (once the player loose, it shows that the character died)
  ![image](https://github.com/user-attachments/assets/4654b976-a382-4def-b9da-a97ab5cbdd87)

  
  ![image](https://github.com/user-attachments/assets/b098799e-6a13-450a-985c-0eece7d10544)

  


* **Not implemented features: Mockups in Pixel Art**:
  * In our project, we aimed to incorporate pixel art mockups to enhance the game's visual appeal. However, given our limited experience in pixel art and the project's other priorities, we opted for a more basic design approach. This decision allowed us to focus on core gameplay mechanics and ensure a timely delivery. So these are features we're keen to delve deeper into for future implementations.

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
    
    -The player lose if he doesn't jump over the spike
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
* **Tiago Almeida**: ??%
