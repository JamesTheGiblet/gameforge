# 👋 Welcome to GameForge

> **Evolve Playable Games Through Genetic Algorithms**

This project is an exploration into evolutionary game design. You can create and evolve playable mini-games using genetic algorithms, guiding the process with your own ratings of what's fun.

---

## 🎯 What is GameForge?

GameForge is a **web-based evolutionary game design system** that:

- **Generates** unique playable games from genetic code (DNA)
- **Evolves** games based on your feedback and play performance
- **Learns** what makes games fun through natural selection
- **Creates** endless variations you'd never design manually

Think of it as **Darwin meets Game Dev** - where the fittest (most fun) games survive and reproduce!

---

## 🧬 Core Concept

GameForge treats game design as **genetic traits**:

```txt
Game DNA = Physics + Level Design + Enemies + Scoring + Visuals

Each trait can:
├─ Mutate (random changes)
├─ Cross over (blend with other games)
└─ Evolve (improve through selection)
```

**Your role:** Play games, rate their fun factor, and watch evolution create better variants!

---

## 🚀 Quick Navigation

### **New Users - Start Here!**

- **[QUICK_START.md](./QUICK_START.md)** - Get running in 5 minutes ⚡
  - How to run the app
  - Basic controls
  - Your first evolution

### **Learn the System**

- **[FEATURES.md](./FEATURES.md)** - Complete feature list 📋
  - Game genome structure
  - Evolution environments
  - All available controls

### **Reference**

- **[README.md](./README.md)** - Full project documentation 📖
  - Technical details
  - Use cases
  - Development roadmap

- **[PACKAGE_CONTENT.md](./PACKAGE_CONTENT.md)** - File structure 📦
  - What's included
  - File organization

---

## 🎮 What You Can Do

### **Play Evolved Games**

- Platformers with unique physics
- Endless runners with varying difficulty
- (More genres coming soon!)

### **Guide Evolution**

- Rate games 1-5 stars
- Like/Skip for quick feedback
- Choose evolution environments
- Set mutation rates

### **Build Your Library**

- Save favorite games
- Export as JSON
- Share with others
- Import evolved games

### **Experiment**

- Try different environments (Intense, Casual, Chaotic)
- Adjust mutation rates (1-50%)
- Compare generations
- Create game families

---

## 🎯 Recommended Learning Path

### **1. Try It Out (5 minutes)**

→ Go to **[QUICK_START.md](./QUICK_START.md)**

- Open the HTML file
- Play a game
- Rate it
- Hit "Evolve"

### **2. Understand the System (10 minutes)**

→ Read **[FEATURES.md](./FEATURES.md)**

- Learn about game DNA
- Understand fitness environments
- Explore all controls

### **3. Master Evolution (30 minutes)**

→ Experiment with the app

- Try all 7 environments
- Test different mutation rates
- Build your game library
- Export your favorites

### **4. Deep Dive (Optional)**

→ Read **[README.md](./README.md)**

- Technical implementation
- Genetic algorithm details
- Future enhancements
- Use cases

---

## 🌟 Key Concepts

### **Genome = Game DNA**

Every game has genetic traits:

- **Physics**: Gravity, speed, jump force
- **Level**: Platform count, spacing, obstacles
- **Enemies**: Count, speed, behavior patterns
- **Scoring**: Collectible values, time bonuses
- **Style**: Color palette, effects

### **Fitness = How Fun**

Games are scored on:

- **Your ratings** (1-5 stars) - 70% weight
- **Performance** (score, survival time) - 30% weight
- **Environment modifiers** (based on selected style)

### **Evolution = Improvement**

Each generation:

1. **Select** - Best games chosen (tournament selection)
2. **Breed** - Winners create offspring (crossover)
3. **Mutate** - Random variations (controlled chaos)
4. **Replace** - New generation replaces old (keep 30% elite)

### **Environments = Selection Pressure**

Different styles reward different traits:

- 🎯 **Balanced** - Well-rounded fun
- 🔥 **Intense** - High difficulty
- 😌 **Casual** - Easy, forgiving
- 🎲 **Chaotic** - Extreme variations
- 🏆 **Competitive** - High scores
- 🧠 **Strategic** - Puzzle-like
- 👶 **Beginner** - Very accessible

---

## 💡 Quick Tips

### **For Best Results:**

- ✅ Play games before rating (not just watching)
- ✅ Rate honestly (the system learns from you)
- ✅ Try different environments
- ✅ Save good games early
- ✅ Let evolution run 10+ generations

### **Common Mistakes:**

- ❌ Only using Like/Skip without star ratings
- ❌ High mutation + short evolution = chaos
- ❌ Not saving intermediate results
- ❌ Ignoring environment settings
- ❌ Expecting instant perfection

---

## 🎨 Project Philosophy

**GameForge is about:**

- 🧪 **Experimentation** - Try weird combinations
- 🎲 **Emergence** - Discover unexpected fun
- 🎓 **Learning** - Understand game design principles
- 🎨 **Creativity** - Generate novel mechanics
- 🤝 **Collaboration** - You + AI = Better Games

**GameForge is NOT:**

- ❌ A replacement for human game designers
- ❌ Guaranteed to make "good" games
- ❌ A one-click game generator
- ❌ Magic (it's science!)

---

## 🚀 Ready to Start?

### **Option 1: Jump Right In**

→ **[QUICK_START.md](./QUICK_START.md)** - 5 minute guide

### **Option 2: Learn First**

→ **[FEATURES.md](./FEATURES.md)** - Understand the system

### **Option 3: Technical Details**

→ **[README.md](./README.md)** - Deep dive

---

## 🆘 Need Help?

**Can't run the app?**

- Make sure you're using a modern browser (Chrome, Firefox, Edge)
- Just open the HTML file - no installation needed
- Check that JavaScript is enabled

**Games not evolving?**

- Rate at least 5-10 games before evolving
- Make sure fitness values are > 0
- Try increasing mutation rate

**Lost your progress?**

- Games are saved in browser localStorage
- Export your library regularly (JSON backup)
- Don't clear browser data

**Something else?**

- Check the detailed docs: [README.md](./README.md)
- Review [FEATURES.md](./FEATURES.md) for capabilities
- Experiment with settings

---

## 🎯 What's Next?

After getting started:

1. **Experiment** with different evolution strategies
2. **Build** a library of unique games
3. **Share** your best evolved games (JSON export)
4. **Learn** about genetic algorithms and game design
5. **Extend** the system (it's open source!)

---

## 📚 Documentation Structure

```txt
GameForge/
├─ START_HERE.md (You are here! 📍)
│  └─ Welcome + Navigation
│
├─ QUICK_START.md
│  └─ 5-minute getting started guide
│
├─ FEATURES.md
│  └─ Complete feature documentation
│
├─ README.md
│  └─ Full technical documentation
│
├─ PACKAGE_CONTENT.md
│  └─ File structure reference
│
└─ gameforge.html
   └─ The actual application!
```

---

## 🎮 Let's Forge Some Games

**You're all set!** Pick your path above and start evolving.

Remember: The best games emerge from **experimentation + patience + iteration**.

**Happy Forging!** 🎮✨

---

*Part of the Evolution Trilogy: [Primordial](https://github.com/jamesthegiblet/Primordial) (Art) • [MelodyForge](#) (Music) • **GameForge** (Games)*
