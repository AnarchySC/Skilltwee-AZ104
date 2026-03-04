<div align="center">

```
╔═══════════════════════════════════════════════════════╗
║                                                       ║
║   ████ █   █ █ █    █    █████ █   █ ███████ ███████  ║
║   █    █  █  █ █    █      █   █   █ █       █        ║
║   ████ ███   █ █    █      █   █ █ █ █████   █████    ║
║      █ █  █  █ █    █      █   ██ ██ █       █        ║
║   ████ █   █ █ ████ ████   █   █   █ ███████ ███████  ║
║   ░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░ ║
║   IRL Skill Trees — Gamified Learning Platform        ║
║   Level up real-world skills like an RPG              ║
║                                                       ║
╚═══════════════════════════════════════════════════════╝
```

[![MIT](https://img.shields.io/badge/license-MIT-E85D04?style=flat-square)](https://opensource.org/licenses/MIT)
[![Web](https://img.shields.io/badge/platform-Web-00d4ff?style=flat-square)]()
[![JavaScript](https://img.shields.io/badge/language-HTML/CSS/JS-FAA307?style=flat-square)]()
[![AnarchyGames](https://img.shields.io/badge/by-AnarchyGames.org-E85D04?style=flat-square)](https://anarchygames.org)

*Building things that should exist.*

</div>

---

Transform your learning journey into an RPG-style adventure! Interactive skill trees, quests, and progress tracking — no frameworks, no backend, just open an HTML file.

## Features

- **Interactive Skill Trees** - Visual progression paths with unlockable tiers
- **Quest System** - Hands-on tasks and challenges for each skill
- **Progress Tracking** - Local storage saves your progress automatically
- **XP & Achievements** - Earn points and unlock new skill tiers
- **Curated Resources** - Links to free learning materials for each skill
- **Responsive Design** - Works on desktop, tablet, and mobile
- **Dark Mode** - Easy on the eyes for late-night learning
- **Zero Dependencies** - Pure HTML/CSS/JS, no frameworks needed

## Available Skill Trees

### AZ-104 Azure Administrator (`index.html`)
Microsoft Azure certification preparation — **30 skills** aligned with all 5 exam domains.

### Python Developer Path (`skilltwee-core.html`)
Complete Python learning journey from variables to web frameworks — **30 skills** across 6 domains.

### Python Interactive Lessons (`skilltwee-foundations.html`)
Step-by-step interactive tutorials with built-in Python interpreter (Skulpt).

### AZ-140 Azure Virtual Desktop (Coming Soon)
AVD specialist certification prep — **25 skills** covering AVD architecture.

## Quick Start

### GitHub Pages
1. Fork this repository
2. Go to Settings → Pages → Deploy from branch → main → /root
3. Access at `https://[your-username].github.io/Skilltwee-AZ104/`

### Local
```bash
git clone https://github.com/AnarchySC/Skilltwee-AZ104.git
cd Skilltwee-AZ104
xdg-open index.html  # Linux
open index.html      # macOS
start index.html     # Windows
```

No server required — just open any HTML file in your browser.

## How to Play

1. **Choose Your Path** - Open the skill tree for your topic
2. **Start with Tier 1** - Foundation skills are unlocked by default
3. **Click Skills** - View quests, resources, and track progress
4. **Complete Quests** - Check off completed tasks
5. **Master Skills** - Complete all quests to master a skill
6. **Unlock New Tiers** - Master 80% of a tier to unlock the next level

## Creating Your Own Skill Tree

Copy any HTML file as a template and modify the `skillQuests` object:

```javascript
const skillQuests = {
    'skill-id': {
        icon: '🎯',
        quests: {
            'Category': ['Task 1', 'Task 2']
        },
        resources: [
            { name: 'Resource Name', url: 'https://...' }
        ]
    }
};
```

## Technical Details

- **Frontend**: Pure HTML5, CSS3, JavaScript (ES6+)
- **Storage**: localStorage for progress persistence
- **Python Interpreter**: Skulpt.js (for interactive lessons)
- **No Backend Required** - Fully client-side

### Browser Support
Chrome 90+ | Firefox 88+ | Safari 14+ | Edge 90+ | Mobile

---

<div align="center">

## Support

If Skilltwee helps you learn, consider buying me a coffee.

[![Ko-fi](https://img.shields.io/badge/Ko--fi-Support_Skilltwee-FF5E5B?style=for-the-badge&logo=ko-fi&logoColor=white)](https://ko-fi.com/cassettefuture)

---

MIT License.

An [AnarchyGames.org](https://anarchygames.org) project.

</div>
