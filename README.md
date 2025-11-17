# My_readme
 **Game Title: Zombie Outbreak: Defense Protocol**

## 👤 **Creator of the Game**
Tyreke Bowman

---

Honesty Statement
I, Tyreke Bowman, confirm that this project idea was my own.  
All gameplay mechanics, coding, design choices, and implementation work were completed by me.  
I did not download or copy any existing Unity project, script, or asset as my own work.  
Any outside assets used (such as models, textures, or audio) are credited in the sections below.

---

## 🛠️ **Unity Version Used**
Unity 6 

---

## 🎮 **Player Control**
- The player controls a **3D character** in a survival environment.
- Movement uses **WASD** for walking/strafe movement.
- The mouse is used to **aim** and **shoot projectiles**.
- The player’s gun fires bullets using a *GunController* script.
- A muzzle flash particle effect plays every time the gun fires.

---

## 🧟 **Basic Gameplay (Game Description)**
### **Goal / Objective**
Survive waves of spawning zombies and eliminate as many enemies as possible before your health reaches zero.

### **Full Gameplay Explanation**
- Zombies spawn around the map and walk toward the player.
- The player must aim and shoot to defeat the zombies.
- Each zombie takes damage until their health reaches zero.
- When a zombie dies, a **dust burst particle effect** plays, signaling destruction.
- The player can collect **power-ups** such as:
  - Rapid fire (faster shooting)
  - Temporary shield (blocks damage)
  - Add health to base

### **How the Game Ends**
- The game ends when the player's health or base health reaches **0**.


---

## ⚙️ **Game Mechanics**
- **Health System:**  
  The player has a max health value. Health decreases on zombie damage unless the shield power-up is active.

- **Shooting & Gun System:**  
  Uses a fire rate system with cooldown, muzzle flash, and projectile spawning from the fire point.
  Zombies walk toward the player using a simple follow AI script.

- **Power-Ups:**  
  - **Rapid Fire:** Temporarily increases bullet firing speed.  
  - **Shield:** Prevents damage for a short period.

- **Particle Effects:**  
  - Gun muzzle flash  
  - Zombie death dust burst  
  

- **Progression:**
  - Zombies spawn faster and in larger numbers as the game continues.
  - Player score increases per zombie eliminated.

---

## 🖥️ **User Interface**
### **3D Objects / Assets Included**
- Player character model  
- Zombie enemy model  
- Bullet projectile  
- Environment (ground plane, walls, props)  
- Power-up objects  
- Particle effects (gun flash, dust burst)

### **Where Assets Came From**
- Unity Asset Store (free packages)
- Built-in Unity particle effects
- Simple objects created inside Unity (cubes, spheres, planes)

### **Scoring System**
- 100 points for each zombie defeated   

---

## 🔊 **Sound Effects & Particles**
n/a

### **Particle Effects**
- Muzzle flash on gun fire  
- Dust burst when zombies die  
(Triggered through particle system Play())

### **Background Music**
n/a

---



---

## ✔️ End of README
