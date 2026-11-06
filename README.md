<div align="center">
  <svg width="840" height="230" viewBox="0 0 840 230" fill="none" xmlns="http://www.w3.org/2000/svg">
    <defs>
      <!-- Background Cyber Matrix Pattern -->
      <pattern id="grid" width="24" height="24" patternUnits="userSpaceOnUse">
        <path d="M 24 0 L 0 0 0 24" fill="none" stroke="#8B5CF6" stroke-width="0.75" stroke-opacity="0.12"/>
      </pattern>

      <!-- Glow Filters -->
      <filter id="neon-glow-violet" x="-30%" y="-30%" width="160%" height="160%">
        <feGaussianBlur stdDeviation="5" result="blur1"/>
        <feGaussianBlur stdDeviation="12" result="blur2"/>
        <feMerge>
          <feMergeNode in="blur2"/>
          <feMergeNode in="blur1"/>
          <feMergeNode in="SourceGraphic"/>
        </feMerge>
      </filter>

      <filter id="cyan-glow" x="-20%" y="-20%" width="140%" height="140%">
        <feGaussianBlur stdDeviation="4" result="blur"/>
        <feMerge>
          <feMergeNode in="blur"/>
          <feMergeNode in="SourceGraphic"/>
        </feMerge>
      </filter>

      <!-- Linear Gradients -->
      <linearGradient id="frame-grad" x1="0" y1="0" x2="840" y2="230" gradientUnits="userSpaceOnUse">
        <stop offset="0%" stop-color="#A855F7"/>
        <stop offset="40%" stop-color="#3B82F6" stop-opacity="0.2"/>
        <stop offset="70%" stop-color="#06B6D4" stop-opacity="0.3"/>
        <stop offset="100%" stop-color="#8B5CF6"/>
      </linearGradient>

      <linearGradient id="core-bg" x1="0" y1="0" x2="0" y2="230" gradientUnits="userSpaceOnUse">
        <stop offset="0%" stop-color="#0D061A"/>
        <stop offset="100%" stop-color="#030206"/>
      </linearGradient>

      <linearGradient id="text-gradient" x1="0%" y1="0%" x2="100%" y2="0%">
        <stop offset="0%" stop-color="#FFFFFF"/>
        <stop offset="35%" stop-color="#E9D5FF"/>
        <stop offset="70%" stop-color="#C084FC"/>
        <stop offset="100%" stop-color="#38BDF8"/>
      </linearGradient>
    </defs>

    <!-- Main Chassis Frame with Chamfered Tech Corners -->
    <path d="M 25 10 
             L 815 10 
             L 830 25 
             L 830 205 
             L 815 220 
             L 25 220 
             L 10 205 
             L 10 25 Z" 
          fill="url(#core-bg)" 
          stroke="url(#frame-grad)" 
          stroke-width="1.8"/>

    <!-- Grid Texture Overlay -->
    <path d="M 25 10 L 815 10 L 830 25 L 830 205 L 815 220 L 25 220 L 10 205 L 10 25 Z" fill="url(#grid)"/>

    <!-- Top Left Futuristic Brackets -->
    <path d="M 10 50 L 10 25 L 25 10 L 55 10" stroke="#C084FC" stroke-width="2.5" fill="none" filter="url(#neon-glow-violet)"/>
    <rect x="62" y="8" width="18" height="4" fill="#38BDF8" filter="url(#cyan-glow)"/>

    <!-- Bottom Right Brackets -->
    <path d="M 830 180 L 830 205 L 815 220 L 785 220" stroke="#C084FC" stroke-width="2.5" fill="none" filter="url(#neon-glow-violet)"/>
    <rect x="760" y="218" width="18" height="4" fill="#A855F7"/>

    <!-- Top Telemetry & System Header Row -->
    <g transform="translate(32, 34)">
      <!-- Pulsing Node Indicator -->
      <circle cx="6" cy="6" r="4.5" fill="#22C55E" filter="url(#cyan-glow)"/>
      <circle cx="6" cy="6" r="8" stroke="#22C55E" stroke-width="0.75" stroke-opacity="0.6"/>
      <text x="24" y="10" fill="#E2E8F0" font-family="'JetBrains Mono', 'Fira Code', monospace" font-size="11" font-weight="700" letter-spacing="2.5">CORE.SYS // SECURE EXECUTION CONTEXT</text>

      <!-- Right Telemetry Chips -->
      <text x="770" y="10" fill="#A78BFA" font-family="'JetBrains Mono',

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
