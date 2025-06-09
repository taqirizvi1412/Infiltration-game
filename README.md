# 🎮 Adaptive Stealth Infiltration Game

A browser-based 2D stealth game featuring adaptive AI guards that learn from player behavior. Guards become smarter and more challenging as they memorize your infiltration patterns!

![Game Preview](https://img.shields.io/badge/Status-Active-success)
![License](https://img.shields.io/badge/License-MIT-blue)
![Version](https://img.shields.io/badge/Version-1.0.0-orange)

## 🌟 Features

### Adaptive AI System
- **Learning Guards**: AI guards track and memorize player movement patterns
- **Heat Map System**: Guards patrol areas where players frequently travel
- **Progressive Difficulty**: Guards adapt their strategies based on both successes and failures
- **Persistent Memory**: AI knowledge accumulates across multiple attempts

### Gameplay Mechanics
- **Stealth Movement**: Use WASD/Arrow keys to navigate, hold Shift to crouch
- **Vision Cones**: Realistic line-of-sight mechanics with wall occlusion
- **Safe Zones**: Blue areas where players cannot be detected
- **Dynamic Difficulty**: Every 5 wins spawns an additional guard with increased vision range

### Guard Behaviors
- **Smooth Movement**: Physics-based movement with natural wall avoidance
- **Three States**: Patrol, Investigate, and Chase modes
- **Cooperative Learning**: Guards share knowledge about player tactics
- **Smart Pathfinding**: Guards navigate around obstacles naturally

## 🚀 Play Online

Simply open `index.html` in a modern web browser - no installation required!

## 🎯 How to Play

1. **Objective**: Reach the green target without being detected
2. **Movement**: 
   - WASD or Arrow keys to move
   - Hold Shift to crouch (slower but stealthier)
   - R to restart current level
   - ESC to reset all progress
3. **Safe Zones**: Blue areas are safe - guards cannot detect you there
4. **Strategy**: Vary your routes as guards learn from your patterns!

## 🛠️ Technical Details

- **Pure JavaScript**: No dependencies or frameworks required
- **HTML5 Canvas**: Smooth rendering and animations
- **Responsive Design**: Scales to fit different screen sizes
- **Browser Storage**: Game state persists in memory during session

## 📊 AI Learning System

The game features a sophisticated learning system:
- Guards maintain a "heat map" of player activity
- Failed attempts strengthen guard memory of used routes
- Successful runs also contribute to AI learning (with slight decay)
- Guards dynamically adjust patrol routes based on accumulated data

## 🤝 Contributing

Contributions are welcome! Feel free to:
- Report bugs via GitHub Issues
- Submit pull requests with improvements
- Suggest new features or gameplay mechanics

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- Inspired by classic stealth games like Metal Gear Solid
- Built with modern web technologies
- Designed for learning and entertainment

## 🔮 Future Enhancements

- [ ] Multiple levels with increasing complexity
- [ ] Power-ups and tools (smoke bombs, distractions)
- [ ] Score system with online leaderboards
- [ ] Level editor for custom challenges
- [ ] Mobile touch controls
- [ ] Sound effects and background music

---

**Made with ❤️ by [Your Name]**
