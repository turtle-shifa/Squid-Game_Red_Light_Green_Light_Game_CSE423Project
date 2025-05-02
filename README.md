# Red Light, Green Light - Squid Game

## Group Project Members

1. **A K M Jubaeir Islam** - ID: 24341196  
2. **Mahmudul Hasan Shifa** - ID: 24241215  
3. **Ayan Sarkar** - ID: 22201684  

## Features

### 1. Player Character System
- 3D player model  
- Articulated body parts for potential animation (e.g., walking, falling)  
- WASD keyboard controls for movement  
- First-person and third-person camera modes (toggle with F key)  

### 2. Character Movement Mechanics
- Movement allowed only during "Green Light" phase  
- Movement detection system that checks for illegal movement during "Red Light"  
- Elimination if player moves during "Red Light"  

### 3. Doll Character (Watcher System)
- 3D model of iconic doll character  
- Faces away from player during "Green Light" and toward them during "Red Light"  
- Red bullet firing animation when a player is eliminated  

### 4. Light State & Timing System
- Randomized "Red Light" and "Green Light" intervals (1–8 seconds)  
- Visual state indicator (traffic light or on-screen text)  
- Smooth transitions between light states  

### 5. Player Detection & Elimination
- Tracks player position frame-by-frame  
- If movement is detected during "Red Light", trigger elimination:  
  - Fall animation  
  - Red bullet fired from doll  
  - Display “Game Over” message  

### 6. Win/Loss Conditions
- Victory: Reach finish line within time limit  
- Game Over:  
  - Caught moving during red light  
  - Time runs out before reaching finish line  
- Context-specific end screen messages  

### 7. Countdown Timer System
- 60-second time limit to complete the game  
- Real-time countdown displayed on screen  
- Triggers automatic Game Over when timer hits zero  

### 8. Restart & Reset Functionality
- Press 'R' to fully reset game state:  
  - Player position  
  - Timer  
  - Light phase  
  - Game state/message  
- Instant reset without reloading the application  

### 9. Environment & Visual Design
- Realistic game field with start and checkered finish line  
- Decorative pine trees lining the track  
- Gradient-colored path with semi-transparent stripes  
- Sky dome with fluffy clouds and bright lighting  
- Red-jumpsuited guards at the finish line  
- Boundary walls to define play area  

### 10. Camera & Visual Feedback
- Third-person follow camera and first-person view  
- Toggle between views with smooth transitions  
- Clear on-screen indicators:  
  - Current light state  
  - Time left  
  - Win/lose messages  

---

## 🔧 Controls
| Key | Action |
|-----|--------|
| W/A/S/D | Move Player |
| F | Toggle First/Third Person View |
| R | Restart Game |

---

## 🛠️ Technologies Used
- **C++**
- **OpenGL**
- **GLUT / GLFW (for window management and input)**
- Custom 3D modeling using primitive shapes

---

## 🚧 Future Improvements
- Sound effects and background music
- Additional animations and polish (falling, walking)
- More detailed textures and lighting effects

---

## 📷 Screenshots
*Add your gameplay screenshots here*

---

## 📁 Project Setup
To build and run the project: 
