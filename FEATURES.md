# ✨ GameForge Features

This document outlines the key features of the GameForge application.

---

## 🧬 Game Genome Structure

Each game has DNA consisting of:

**Physics Traits:**

- Gravity strength
- Player speed
- Jump force
- Friction

**Level Design Traits:**

- Platform count
- Enemy count
- Collectible frequency

**Scoring Traits:**

- Collectible value
- Lives count

**Visual Style Traits:**

- Color palette (8 presets: vibrant, pastel, neon, retro, nature, fire, ice, cyberpunk)

---

## 🎮 Game Genres (Evolvable Templates)

### **1. Platformer Evolution**

Classic side-scrolling platformer with evolving:

- Jump mechanics and feel
- Platform layouts and challenges
- Enemy patterns and behaviors

### **2. Endless Runner Evolution**

Auto-runner with evolving:

- Speed progression
- Obstacle patterns
- Lane switching mechanics

---

## 🧬 Genetic Algorithm Features

### **Selection Methods:**

- **Play-based Fitness**: Players rate fun (1-5 stars).
- **Performance Fitness**: Calculated from score and survival time.

### **Evolution Controls:**

- **Population Size**: 10-50 games per generation (adjustable).
- **Mutation Rate**: 1-50% (adjustable).
- **Elitism**: Preserves the top 30% of the population.

### **Fitness Environments:**

Apply a modifier to the fitness calculation to favor certain types of games.

- 🎯 **Balanced**: Fun, fair, replayable
- 🔥 **Intense**: Fast, difficult, skill-based
- 😌 **Casual**: Relaxing, forgiving, accessible
- 🎲 **Chaotic**: Unpredictable, varied, surprising
- 🏆 **Competitive**: Score-focused, leaderboard-worthy
- 🧠 **Strategic**: Puzzle-like, planning required
- 👶 **Beginner**: Easy to learn, low punishment

---

## 🎨 Visual & UI Features

### **Real-Time Gameplay Canvas**

- Smooth 60 FPS rendering.
- Responsive controls.
- Visual feedback with particles.
- Score, lives, and time overlay.

### **Game DNA Display**

A real-time display shows the underlying gene values for the current game as a series of bars, giving insight into its construction.

### **Saved Games Library**

- Save your favorite evolved games to a library.
- The library is persisted in the browser's `localStorage`.
- Load, delete, and export games from the library.

### **Exporting**

- Export a single game's DNA as a JSON file.
- Export the entire game library as a single JSON file.

---

## 🎓 Educational Value

### **Teaches:**

- Genetic algorithms in practice
- Game design principles
- Physics simulation
- Balance and difficulty tuning
- Procedural generation

### **Demonstrates:**

- Emergent gameplay
- Player-driven evolution
- Game feel and polish
