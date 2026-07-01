<!-- Paste this directly into your README.md -->
<svg xmlns="http://www.w3.org/2000/svg" width="960" height="240" viewBox="0 0 960 240">
  <defs>
    <linearGradient id="g1" x1="0" x2="1">
      <stop offset="0" stop-color="#071233"/>
      <stop offset="1" stop-color="#041129"/>
    </linearGradient>
    <filter id="glow" x="-50%" y="-50%" width="200%" height="200%">
      <feGaussianBlur stdDeviation="8" result="b"/>
      <feMerge><feMergeNode in="b"/><feMergeNode in="SourceGraphic"/></feMerge>
    </filter>
  </defs>
  <rect width="100%" height="100%" fill="url(#g1)" rx="8"/>
  <!-- Left text block -->
  <g transform="translate(40,36)">
    <text x="0" y="44" font-family="Inter, Roboto, system-ui, sans-serif" font-size="48" fill="#FFFFFF" font-weight="700">AI Loops</text>
    <text x="0" y="86" font-family="Inter, Roboto, system-ui, sans-serif" font-size="18" fill="#00E5FF" font-weight="600">Complete Guide to AI Agent Loops</text>
    <g transform="translate(0,116)" font-family="Inter, Roboto, system-ui, sans-serif" font-size="16" fill="#FFFFFF">
      <text x="0" y="0">Reason</text>
      <text x="84" y="0" fill="#FF6B6B">→</text>
      <text x="102" y="0" fill="#00E5FF">Act</text>
      <text x="170" y="0" fill="#FF6B6B">→</text>
      <text x="188" y="0" fill="#FFFFFF">Observe</text>
      <text x="292" y="0" fill="#FF6B6B">→</text>
      <text x="310" y="0" fill="#00E5FF">Repeat</text>
    </g>
    <rect x="0" y="146" rx="6" ry="6" width="120" height="28" fill="rgba(255,255,255,0.03)"/>
    <text x="12" y="166" font-size="12" fill="#00E5FF" font-family="Inter, Roboto, sans-serif">2026 Edition</text>
  </g>

  <!-- Right abstract loop illustration -->
  <g transform="translate(620,36)">
    <g filter="url(#glow)">
      <circle cx="120" cy="72" r="64" fill="none" stroke="rgba(0,229,255,0.12)" stroke-width="6"/>
      <circle cx="120" cy="72" r="44" fill="none" stroke="rgba(255,107,107,0.08)" stroke-width="6"/>
      <circle cx="120" cy="72" r="24" fill="none" stroke="rgba(0,229,255,0.18)" stroke-width="5"/>
    </g>
    <!-- icons as simple shapes -->
    <g transform="translate(60,40)" fill="#00E5FF">
      <rect x="-6" y="-6" width="12" height="12" rx="2" fill="#00E5FF" opacity="0.95"/>
    </g>
    <g transform="translate(120,32)" fill="#FF6B6B">
      <rect x="-6" y="-6" width="12" height="12" rx="2"/>
    </g>
    <g transform="translate(160,88)" fill="#FFFFFF">
      <rect x="-6" y="-6" width="12" height="12" rx="2"/>
    </g>
    <!-- dashed connectors -->
    <path d="M84 44 C100 20, 140 20, 156 44" stroke="#00E5FF" stroke-width="2" stroke-dasharray="6 6" fill="none" opacity="0.9" />
    <path d="M156 100 C140 124, 100 124, 84 100" stroke="#FF6B6B" stroke-width="2" stroke-dasharray="6 6" fill="none" opacity="0.7" />
  </g>
</svg>
