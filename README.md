<div align="center">
  <svg width="860" height="260" viewBox="0 0 860 260" fill="none" xmlns="http://www.w3.org/2000/svg">
    <defs>
      <radialGradient id="mesh-glow" cx="50%" cy="30%" r="65%">
        <stop offset="0%" stop-color="#4C1D95" stop-opacity="0.6"/>
        <stop offset="45%" stop-color="#1E1035" stop-opacity="0.4"/>
        <stop offset="100%" stop-color="#05030A" stop-opacity="0.95"/>
      </radialGradient>

   <linearGradient id="neon-cyan-violet" x1="0%" y1="0%" x2="100%" y2="0%">
        <stop offset="0%" stop-color="#00F0FF"/>
        <stop offset="35%" stop-color="#A78BFA"/>
        <stop offset="70%" stop-color="#F43F5E"/>
        <stop offset="100%" stop-color="#8B5CF6"/>
      </linearGradient>

  <linearGradient id="border-shimmer" x1="0%" y1="0%" x2="100%" y2="100%">
        <stop offset="0%" stop-color="#00F0FF" stop-opacity="0.8"/>
        <stop offset="25%" stop-color="#8B5CF6" stop-opacity="0.3"/>
        <stop offset="75%" stop-color="#38BDF8" stop-opacity="0.2"/>
        <stop offset="100%" stop-color="#C084FC" stop-opacity="0.9"/>
      </linearGradient>

  <pattern id="dot-grid" width="22" height="22" patternUnits="userSpaceOnUse">
        <circle cx="2" cy="2" r="1" fill="#8B5CF6" fill-opacity="0.22"/>
      </pattern>

  <filter id="ultra-bloom" x="-30%" y="-30%" width="160%" height="160%">
        <feGaussianBlur stdDeviation="6" result="blur1"/>
        <feGaussianBlur stdDeviation="15" result="blur2"/>
        <feMerge>
          <feMergeNode in="blur2"/>
          <feMergeNode in="blur1"/>
          <feMergeNode in="SourceGraphic"/>
        </feMerge>
      </filter>

   <filter id="soft-glow" x="-20%" y="-20%" width="140%" height="140%">
        <feGaussianBlur stdDeviation="3" result="glow"/>
        <feMerge>
          <feMergeNode in="glow"/>
          <feMergeNode in="SourceGraphic"/>
        </feMerge>
      </filter>
    </defs>

  <path d="M 28 8 L 832 8 L 852 28 L 852 232 L 832 252 L 28 252 L 8 232 L 8 28 Z" fill="#06030D" stroke="url(#border-shimmer)" stroke-width="1.8"/>
    <path d="M 28 8 L 832 8 L 852 28 L 852 232 L 832 252 L 28 252 L 8 232 L 8 28 Z" fill="url(#mesh-glow)"/>
    <path d="M 28 8 L 832 8 L 852 28 L 852 232 L 832 252 L 28 252 L 8 232 L 8 28 Z" fill="url(#dot-grid)"/>

  <path d="M 8 55 L 8 28 L 28 8 L 65 8" stroke="#00F0FF" stroke-width="2.5" fill="none" filter="url(#soft-glow)"/>
    <path d="M 852 205 L 852 232 L 832 252 L 795 252" stroke="#A78BFA" stroke-width="2.5" fill="none" filter="url(#soft-glow)"/>

  <g transform="translate(36, 32)">
      <circle cx="5" cy="5" r="4" fill="#00F0FF" filter="url(#soft-glow)"/>
      <circle cx="5" cy="5" r="8" stroke="#00F0FF" stroke-width="0.8" stroke-opacity="0.5"/>
      <text x="22" y="9" fill="#94A3B8" font-family="'JetBrains Mono', 'Fira Code', monospace" font-size="11" font-weight="700" letter-spacing="2.5">PORTFOLIO.SYS // ONLINE</text>
      <text x="788" y="9" fill="#A78BFA" font-family="'JetBrains Mono', monospace" font-size="10.5" font-weight="600" text-anchor="end" letter-spacing="1.5">DATA LABS • v2.6</text>
    </g>

  <line x1="36" y1="48" x2="824" y2="48" stroke="#3B1C66" stroke-width="1" stroke-opacity="0.6"/>

  <g transform="translate(40, 116)">
      <text x="0" y="8" fill="url(#neon-cyan-violet)" font-family="'Montserrat', 'Space Grotesk', -apple-system, sans-serif" font-weight="900" font-size="52" letter-spacing="3.5" filter="url(#ultra-bloom)">P. SRISAI</text>
    </g>

  <g transform="translate(40, 142)">
      <rect x="0" y="0" width="10" height="2" fill="#00F0FF" filter="url(#soft-glow)"/>
      <line x1="16" y1="1" x2="820" y2="1" stroke="#261543" stroke-width="1"/>
    </g>

  <g transform="translate(40, 168)">
      <foreignObject x="0" y="0" width="790" height="65">
        <div xmlns="http://www.w3.org/1999/xhtml">
          <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&amp;weight=600&amp;size=16&amp;duration=3600&amp;pause=1200&amp;color=38BDF8&amp;background=00000000&amp;vCenter=true&amp;width=790&amp;height=55&amp;lines=AI+%26+Data+Science+Student+%7C+Developer;Building+with+Python%2C+Kotlin+%26+Machine+Learning;Exploring+ideas+through+code." alt="P. Srisai - AI and Data Science Bio"/>
        </div>
      </foreignObject>
    </g>

  <rect x="36" y="240" width="24" height="2" fill="#8B5CF6"/>
    <rect x="66" y="240" width="8" height="2" fill="#00F0FF"/>
  </svg>
</div>

## About Me

I'm **Sri Sai**, an AI & Data Science student interested in building practical software, exploring machine learning, and developing useful applications.

- Currently building **FocusFlow**, a productivity-focused Android application.
- Interested in **Artificial Intelligence, Data Science, Android development, and backend systems**.
- Learning by building projects and experimenting with new technologies.
- Focused on writing useful, maintainable code and continuously improving my skills.

## Tech Stack

<p>
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python" />
  <img src="https://img.shields.io/badge/Kotlin-7F52FF?style=for-the-badge&logo=kotlin&logoColor=white" alt="Kotlin" />
  <img src="https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white" alt="SQL" />
  <img src="https://img.shields.io/badge/PHP-777BB4?style=for-the-badge&logo=php&logoColor=white" alt="PHP" />
  <img src="https://img.shields.io/badge/Android_Studio-3DDC84?style=for-the-badge&logo=androidstudio&logoColor=white" alt="Android Studio" />
  <img src="https://img.shields.io/badge/Streamlit-FF4B4B?style=for-the-badge&logo=streamlit&logoColor=white" alt="Streamlit" />
  <img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white" alt="Git" />
  <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub" />
</p>

## Featured Projects

### [FocusFlow — Android productivity app](https://github.com/srisai-git/flow)
A productivity-focused Android application designed around study sessions, subjects, schedules, and consistency tracking.

**Tech:** Kotlin · Android Studio

### [Flow Backend](https://github.com/srisai-git/flow-backend)
Backend development for the Flow / FocusFlow application.

**Tech:** PHP · Backend development

### Weather Data Smoothing & Pattern Identification
A data analysis project exploring Chennai weather patterns from 2020–2024 using the Moving Average algorithm and a Streamlit dashboard.

**Tech:** Python · Pandas · Streamlit · Data visualization

---

## Contribution Activity

<p align="center">
  <img src="https://raw.githubusercontent.com/srisai-git/srisai-git/output/github-contribution-grid-snake.svg" alt="Animated GitHub contribution snake" width="100%" />
</p>

---

## Connect

- **GitHub:** [@srisai-git](https://github.com/srisai-git)
- **Email:** [saiprince7329@gmail.com](mailto:saiprince7329@gmail.com)

<p align="center"><sub>Learning · Building · Improving</sub></p>
