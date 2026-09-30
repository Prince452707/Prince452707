<svg width="1200" height="260" viewBox="0 0 1200 260" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <linearGradient id="bg" x1="0" y1="0" x2="1" y2="1">
      <stop offset="0%" stop-color="#0f172a"/>
      <stop offset="50%" stop-color="#0f766e"/>
      <stop offset="100%" stop-color="#1e293b"/>
    </linearGradient>

    <linearGradient id="accent" x1="0" y1="0" x2="1" y2="0">
      <stop offset="0%" stop-color="#22c55e"/>
      <stop offset="100%" stop-color="#38bdf8"/>
    </linearGradient>

    <filter id="glow">
      <feGaussianBlur stdDeviation="8" result="blur"/>
      <feColorMatrix in="blur" type="matrix"
        values="0 0 0 0 0.13
                0 0 0 0 0.96
                0 0 0 0 0.75
                0 0 0 0.7 0"/>
    </filter>
  </defs>

  <!-- Background -->
  <rect width="1200" height="260" fill="url(#bg)" rx="24"/>

  <!-- Subtle grid -->
  <g opacity="0.15" stroke="#0f172a">
    <line x1="80" y1="40" x2="80" y2="220"/>
    <line x1="160" y1="40" x2="160" y2="220"/>
    <line x1="240" y1="40" x2="240" y2="220"/>
    <line x1="320" y1="40" x2="320" y2="220"/>
    <line x1="400" y1="40" x2="400" y2="220"/>
  </g>

  <!-- Glow orb -->
  <circle cx="1020" cy="70" r="40" fill="#22c55e" opacity="0.12" filter="url(#glow)"/>
  <circle cx="1040" cy="90" r="22" fill="#38bdf8" opacity="0.4"/>

  <!-- Main text -->
  <text x="110" y="110" fill="#e5e7eb" font-size="36" font-family="system-ui, -apple-system, BlinkMacSystemFont, 'Segoe UI', sans-serif" font-weight="700">
    Prince Kumar · Crypto Dev & Founder
  </text>

  <text x="110" y="150" fill="#9ca3af" font-size="20" font-family="system-ui, -apple-system, BlinkMacSystemFont, 'Segoe UI', sans-serif">
    Building Vecontra – data-driven crypto intelligence for Indian users
  </text>

  <!-- Tag pills -->
  <rect x="110" y="185" rx="18" ry="18" width="210" height="34" fill="#0b1120" stroke="#1f2937"/>
  <text x="125" y="207" fill="#e5e7eb" font-size="16" font-family="system-ui, -apple-system, BlinkMacSystemFont, 'Segoe UI', sans-serif">
    Flutter · APIs · Crypto Research
  </text>

  <rect x="340" y="185" rx="18" ry="18" width="260" height="34" fill="#0b1120" stroke="#1f2937"/>
  <text x="355" y="207" fill="#e5e7eb" font-size="16" font-family="system-ui, -apple-system, BlinkMacSystemFont, 'Segoe UI', sans-serif">
    Reels · Shorts · Educational Content
  </text>

  <!-- Right-side badge -->
  <rect x="820" y="165" rx="18" ry="18" width="270" height="54" fill="#0b1120" stroke="url(#accent)"/>
  <text x="840" y="198" fill="#e5e7eb" font-size="18" font-family="system-ui, -apple-system, BlinkMacSystemFont, 'Segoe UI', sans-serif" font-weight="600">
    Vecontra · Real-Time Crypto Analytics
  </text>
</svg>
