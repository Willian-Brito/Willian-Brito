<h1 align="center">Bem vindo! Meu nome é Willian Ferreira Brito...</h1> 
<h3 align="center">Trabalho como Desenvolvedor Web Full Stack, e sou Apaixonado por Tecnologia 🤩</h3>

<div align="center">
  <!-- galaxy header -->
  <svg xmlns="http://www.w3.org/2000/svg" width="850" height="280" viewBox="0 0 850 280">
    <defs>
      <style>
        .star-bg {
          animation: twinkle-slow 7s ease-in-out infinite;
        }
        .star-mid {
          animation: twinkle-mid 5s ease-in-out infinite;
        }
        .star-fg {
          animation: twinkle-fast 3s ease-in-out infinite;
        }
        @keyframes twinkle-slow {
          0%, 100% { opacity: 0.08; }
          50% { opacity: 0.3; }
        }
        @keyframes twinkle-mid {
          0%, 100% { opacity: 0.15; }
          50% { opacity: 0.5; }
        }
        @keyframes twinkle-fast {
          0%, 100% { opacity: 0.4; }
          50% { opacity: 0.8; }
        }
        .core-ring {
          animation: pulse-core 3s ease-in-out infinite;
        }
        .core-ring-inner {
          animation: pulse-core 3s ease-in-out infinite 1.5s;
        }
        @keyframes pulse-core {
          0%, 100% { stroke-opacity: 0.3; transform: scale(1); transform-origin: 425px 155px; }
          50% { stroke-opacity: 0.8; transform: scale(1.06); transform-origin: 425px 155px; }
        }
        .shooting-star {
          opacity: 0;
          animation: shoot linear infinite;
        }
        @keyframes shoot {
          0% { opacity: 0; transform: translate(0, 0); }
          5% { opacity: 0.9; }
          15% { opacity: 0.6; transform: translate(var(--shoot-tx), var(--shoot-ty)); }
          20% { opacity: 0; transform: translate(var(--shoot-tx), var(--shoot-ty)); }
          100% { opacity: 0; }
        }
      </style>
  
      <filter id="nebula-outer">
        <feGaussianBlur stdDeviation="60"/>
      </filter>
      <filter id="nebula-inner">
        <feGaussianBlur stdDeviation="30"/>
      </filter>
  
      <filter id="label-glow" x="-20%" y="-20%" width="140%" height="140%">
        <feGaussianBlur stdDeviation="2" result="blur"/>
      </filter>
      <filter id="core-bright-glow" x="-100%" y="-100%" width="300%" height="300%">
        <feGaussianBlur stdDeviation="4"/>
      </filter>
  
      <radialGradient id="core-haze-gradient" cx="50%" cy="50%" r="50%">
        <stop offset="0%" stop-color="#00d4ff" stop-opacity="0.5"/>
        <stop offset="50%" stop-color="#a78bfa" stop-opacity="0.2"/>
        <stop offset="100%" stop-color="#00d4ff" stop-opacity="0"/>
      </radialGradient>
  
      <radialGradient id="core-inner-gradient" cx="50%" cy="50%" r="50%">
        <stop offset="0%" stop-color="#ffffff" stop-opacity="0.6"/>
        <stop offset="40%" stop-color="#00d4ff" stop-opacity="0.3"/>
        <stop offset="100%" stop-color="#00d4ff" stop-opacity="0"/>
      </radialGradient>
  
      <linearGradient id="shoot-grad" x1="0%" y1="0%" x2="100%" y2="0%">
        <stop offset="0%" stop-color="#ffffff" stop-opacity="0.8"/>
        <stop offset="100%" stop-color="#ffffff" stop-opacity="0"/>
      </linearGradient>
  
      <filter id="star-glow-0" x="-100%" y="-100%" width="300%" height="300%">
        <feGaussianBlur stdDeviation="3" result="blur"/>
        <feFlood flood-color="#a78bfa" flood-opacity="0.5" result="color"/>
        <feComposite in="color" in2="blur" operator="in" result="glow"/>
        <feMerge>
          <feMergeNode in="glow"/>
          <feMergeNode in="SourceGraphic"/>
        </feMerge>
      </filter>
      <filter id="star-glow-1" x="-100%" y="-100%" width="300%" height="300%">
        <feGaussianBlur stdDeviation="3" result="blur"/>
        <feFlood flood-color="#00d4ff" flood-opacity="0.5" result="color"/>
        <feComposite in="color" in2="blur" operator="in" result="glow"/>
        <feMerge>
          <feMergeNode in="glow"/>
          <feMergeNode in="SourceGraphic"/>
        </feMerge>
      </filter>
      <filter id="star-glow-2" x="-100%" y="-100%" width="300%" height="300%">
        <feGaussianBlur stdDeviation="3" result="blur"/>
        <feFlood flood-color="#ffb020" flood-opacity="0.5" result="color"/>
        <feComposite in="color" in2="blur" operator="in" result="glow"/>
        <feMerge>
          <feMergeNode in="glow"/>
          <feMergeNode in="SourceGraphic"/>
        </feMerge>
      </filter>
    </defs>
  
    <!-- 1. Background -->
    <rect x="0" y="0" width="850" height="280" rx="12" ry="12" fill="#080c14"/>
  
    <!-- 2. Outer nebula -->
      <circle cx="245" cy="125" r="120" fill="#a78bfa" opacity="0.015" filter="url(#nebula-outer)"/>
      <circle cx="625" cy="175" r="100" fill="#ffb020" opacity="0.012" filter="url(#nebula-outer)"/>
      <circle cx="425" cy="195" r="140" fill="#00d4ff" opacity="0.01" filter="url(#nebula-outer)"/>
  
    <!-- 3. Star field (3 layers) -->
      <circle cx="765.4" cy="162.6" r="0.74" fill="#00d4ff" opacity="0.21" class="star-bg" style="animation-delay: 1.7s"/>
      <circle cx="48.7" cy="199.8" r="0.63" fill="#ffffff" opacity="0.23" class="star-bg" style="animation-delay: 2.0s"/>
      <circle cx="91.4" cy="36.9" r="0.70" fill="#ffffff" opacity="0.16" class="star-bg" style="animation-delay: 1.5s"/>
      <circle cx="305.2" cy="255.7" r="0.76" fill="#ffffff" opacity="0.21" class="star-bg" style="animation-delay: 1.8s"/>
      <circle cx="232.7" cy="114.7" r="0.44" fill="#a78bfa" opacity="0.09" class="star-bg" style="animation-delay: 1.6s"/>
      <circle cx="381.2" cy="234.1" r="0.63" fill="#ffffff" opacity="0.09" class="star-bg" style="animation-delay: 2.1s"/>
      <circle cx="148.7" cy="110.3" r="0.42" fill="#ffffff" opacity="0.15" class="star-bg" style="animation-delay: 2.0s"/>
      <circle cx="485.7" cy="87.3" r="0.72" fill="#ffffff" opacity="0.23" class="star-bg" style="animation-delay: 2.1s"/>
      <circle cx="507.3" cy="216.7" r="0.67" fill="#ffb020" opacity="0.12" class="star-bg" style="animation-delay: 1.6s"/>
      <circle cx="654.1" cy="109.6" r="0.49" fill="#ffffff" opacity="0.30" class="star-bg" style="animation-delay: 2.3s"/>
      <circle cx="340.0" cy="91.0" r="0.67" fill="#ffffff" opacity="0.16" class="star-bg" style="animation-delay: 2.1s"/>
      <circle cx="813.7" cy="188.2" r="0.47" fill="#ffffff" opacity="0.23" class="star-bg" style="animation-delay: 2.7s"/>
      <circle cx="310.7" cy="203.4" r="0.47" fill="#00d4ff" opacity="0.10" class="star-bg" style="animation-delay: 1.6s"/>
      <circle cx="554.4" cy="17.1" r="0.60" fill="#ffffff" opacity="0.10" class="star-bg" style="animation-delay: 1.7s"/>
      <circle cx="360.5" cy="191.5" r="0.47" fill="#ffffff" opacity="0.08" class="star-bg" style="animation-delay: 1.7s"/>
      <circle cx="240.1" cy="23.3" r="0.51" fill="#ffffff" opacity="0.08" class="star-bg" style="animation-delay: 2.4s"/>
      <circle cx="70.7" cy="217.5" r="0.61" fill="#a78bfa" opacity="0.15" class="star-bg" style="animation-delay: 2.5s"/>
      <circle cx="722.0" cy="86.5" r="0.66" fill="#ffffff" opacity="0.19" class="star-bg" style="animation-delay: 2.3s"/>
      <circle cx="731.6" cy="98.3" r="0.69" fill="#ffffff" opacity="0.22" class="star-bg" style="animation-delay: 1.7s"/>
      <circle cx="524.2" cy="126.4" r="0.75" fill="#ffffff" opacity="0.17" class="star-bg" style="animation-delay: 2.0s"/>
      <circle cx="600.8" cy="81.6" r="0.63" fill="#ffb020" opacity="0.18" class="star-bg" style="animation-delay: 2.6s"/>
      <circle cx="154.5" cy="87.5" r="0.61" fill="#ffffff" opacity="0.09" class="star-bg" style="animation-delay: 2.0s"/>
      <circle cx="596.7" cy="225.5" r="0.77" fill="#ffffff" opacity="0.08" class="star-bg" style="animation-delay: 1.5s"/>
      <circle cx="404.2" cy="243.0" r="0.63" fill="#ffffff" opacity="0.18" class="star-bg" style="animation-delay: 2.4s"/>
      <circle cx="151.4" cy="192.1" r="0.75" fill="#00d4ff" opacity="0.12" class="star-bg" style="animation-delay: 2.4s"/>
      <circle cx="773.1" cy="32.7" r="0.48" fill="#ffffff" opacity="0.15" class="star-bg" style="animation-delay: 2.4s"/>
      <circle cx="776.5" cy="157.2" r="0.54" fill="#ffffff" opacity="0.26" class="star-bg" style="animation-delay: 2.3s"/>
      <circle cx="455.1" cy="231.3" r="0.62" fill="#ffffff" opacity="0.18" class="star-bg" style="animation-delay: 2.6s"/>
      <circle cx="810.6" cy="76.2" r="0.68" fill="#a78bfa" opacity="0.21" class="star-bg" style="animation-delay: 2.5s"/>
      <circle cx="382.0" cy="25.1" r="0.53" fill="#ffffff" opacity="0.22" class="star-bg" style="animation-delay: 2.2s"/>
      <circle cx="311.3" cy="44.1" r="0.33" fill="#ffffff" opacity="0.28" class="star-bg" style="animation-delay: 1.9s"/>
      <circle cx="603.2" cy="163.6" r="0.65" fill="#ffffff" opacity="0.26" class="star-bg" style="animation-delay: 2.7s"/>
      <circle cx="520.7" cy="131.5" r="0.33" fill="#ffb020" opacity="0.27" class="star-bg" style="animation-delay: 2.2s"/>
      <circle cx="682.1" cy="60.4" r="0.41" fill="#ffffff" opacity="0.21" class="star-bg" style="animation-delay: 1.9s"/>
      <circle cx="130.6" cy="124.6" r="0.56" fill="#ffffff" opacity="0.15" class="star-bg" style="animation-delay: 2.1s"/>
      <circle cx="421.9" cy="170.0" r="0.44" fill="#ffffff" opacity="0.29" class="star-bg" style="animation-delay: 2.0s"/>
      <circle cx="76.2" cy="39.2" r="0.63" fill="#00d4ff" opacity="0.12" class="star-bg" style="animation-delay: 2.7s"/>
      <circle cx="210.5" cy="139.0" r="0.60" fill="#ffffff" opacity="0.28" class="star-bg" style="animation-delay: 2.4s"/>
      <circle cx="825.7" cy="138.5" r="0.62" fill="#ffffff" opacity="0.26" class="star-bg" style="animation-delay: 2.0s"/>
      <circle cx="192.2" cy="78.3" r="0.32" fill="#ffffff" opacity="0.29" class="star-bg" style="animation-delay: 2.1s"/>
      <circle cx="272.8" cy="126.8" r="0.68" fill="#00d4ff" opacity="0.24" class="star-mid" style="animation-delay: 1.8s"/>
      <circle cx="193.9" cy="197.7" r="0.87" fill="#ffffff" opacity="0.41" class="star-mid" style="animation-delay: 1.9s"/>
      <circle cx="550.5" cy="132.7" r="1.04" fill="#ffffff" opacity="0.34" class="star-mid" style="animation-delay: 1.5s"/>
      <circle cx="644.1" cy="224.6" r="1.02" fill="#ffffff" opacity="0.45" class="star-mid" style="animation-delay: 1.5s"/>
      <circle cx="70.1" cy="204.7" r="1.08" fill="#a78bfa" opacity="0.32" class="star-mid" style="animation-delay: 1.9s"/>
      <circle cx="324.1" cy="164.9" r="0.71" fill="#ffffff" opacity="0.39" class="star-mid" style="animation-delay: 1.8s"/>
      <circle cx="675.6" cy="56.1" r="0.61" fill="#ffffff" opacity="0.48" class="star-mid" style="animation-delay: 2.1s"/>
      <circle cx="407.2" cy="231.7" r="1.07" fill="#ffffff" opacity="0.36" class="star-mid" style="animation-delay: 1.3s"/>
      <circle cx="50.6" cy="160.1" r="1.11" fill="#ffb020" opacity="0.30" class="star-mid" style="animation-delay: 1.4s"/>
      <circle cx="377.5" cy="173.4" r="1.02" fill="#ffffff" opacity="0.31" class="star-mid" style="animation-delay: 1.6s"/>
      <circle cx="445.2" cy="189.9" r="1.12" fill="#ffffff" opacity="0.49" class="star-mid" style="animation-delay: 1.3s"/>
      <circle cx="143.4" cy="73.1" r="1.07" fill="#ffffff" opacity="0.44" class="star-mid" style="animation-delay: 2.0s"/>
      <circle cx="690.3" cy="10.2" r="0.61" fill="#00d4ff" opacity="0.31" class="star-mid" style="animation-delay: 1.1s"/>
      <circle cx="716.3" cy="20.2" r="0.86" fill="#ffffff" opacity="0.40" class="star-mid" style="animation-delay: 1.5s"/>
      <circle cx="526.1" cy="106.3" r="0.71" fill="#ffffff" opacity="0.33" class="star-mid" style="animation-delay: 1.4s"/>
      <circle cx="536.8" cy="238.4" r="0.88" fill="#ffffff" opacity="0.47" class="star-mid" style="animation-delay: 1.6s"/>
      <circle cx="812.7" cy="35.3" r="0.73" fill="#a78bfa" opacity="0.20" class="star-mid" style="animation-delay: 2.0s"/>
      <circle cx="778.6" cy="258.0" r="0.83" fill="#ffffff" opacity="0.35" class="star-mid" style="animation-delay: 1.2s"/>
      <circle cx="419.8" cy="250.7" r="1.08" fill="#ffffff" opacity="0.22" class="star-mid" style="animation-delay: 2.0s"/>
      <circle cx="752.4" cy="12.3" r="0.66" fill="#ffffff" opacity="0.30" class="star-mid" style="animation-delay: 1.1s"/>
      <circle cx="77.8" cy="205.4" r="1.52" fill="#00d4ff" opacity="0.57" class="star-fg" style="animation-delay: 0.9s"/>
      <circle cx="523.0" cy="12.3" r="1.16" fill="#ffffff" opacity="0.60" class="star-fg" style="animation-delay: 1.2s"/>
      <circle cx="614.5" cy="105.0" r="1.72" fill="#ffffff" opacity="0.44" class="star-fg" style="animation-delay: 1.2s"/>
      <circle cx="109.7" cy="232.9" r="1.20" fill="#ffffff" opacity="0.59" class="star-fg" style="animation-delay: 1.2s"/>
      <circle cx="652.6" cy="182.6" r="1.48" fill="#a78bfa" opacity="0.69" class="star-fg" style="animation-delay: 1.1s"/>
      <circle cx="325.1" cy="103.2" r="1.19" fill="#ffffff" opacity="0.48" class="star-fg" style="animation-delay: 1.3s"/>
      <circle cx="91.6" cy="176.5" r="1.48" fill="#ffffff" opacity="0.41" class="star-fg" style="animation-delay: 1.3s"/>
      <circle cx="338.4" cy="235.5" r="1.31" fill="#ffffff" opacity="0.60" class="star-fg" style="animation-delay: 1.3s"/>
      <circle cx="809.3" cy="89.8" r="1.20" fill="#ffb020" opacity="0.63" class="star-fg" style="animation-delay: 0.8s"/>
      <circle cx="195.8" cy="258.6" r="1.72" fill="#ffffff" opacity="0.68" class="star-fg" style="animation-delay: 1.2s"/>
  
    <!-- 4. Inner nebula -->
      <circle cx="425" cy="155" r="70" fill="#00d4ff" opacity="0.04" filter="url(#nebula-inner)"/>
      <circle cx="365" cy="135" r="50" fill="#a78bfa" opacity="0.035" filter="url(#nebula-inner)"/>
      <circle cx="495" cy="170" r="45" fill="#ffb020" opacity="0.03" filter="url(#nebula-inner)"/>
  
    <!-- 5. Shooting stars -->
      <line x1="120" y1="30" x2="140" y2="35" stroke="url(#shoot-grad)" stroke-width="1.2" stroke-linecap="round" class="shooting-star" style="animation-delay: 0.0s; --shoot-tx: 200px; --shoot-ty: 80px; animation-duration: 6s"/>
      <line x1="650" y1="20" x2="670" y2="25" stroke="url(#shoot-grad)" stroke-width="1.2" stroke-linecap="round" class="shooting-star" style="animation-delay: 2.5s; --shoot-tx: 180px; --shoot-ty: 70px; animation-duration: 8s"/>
      <line x1="400" y1="250" x2="420" y2="255" stroke="url(#shoot-grad)" stroke-width="1.2" stroke-linecap="round" class="shooting-star" style="animation-delay: 5.0s; --shoot-tx: 160px; --shoot-ty: 60px; animation-duration: 7s"/>
  
    <!-- 6. Spiral arm paths (segmented fade) -->
      <path d="M 425.0 155.0 Q 425.0 155.0 429.6 155.8 Q 434.3 156.7 437.5 157.9 Q 440.8 159.2 442.3 160.7 Q 443.8 162.2 443.2 163.9 Q 442.6 165.6 439.8 167.4 Q 437.1 169.1 432.0 170.7 Q 427.0 172.3 419.9 173.6 L 412.7 174.9" fill="none" stroke="#a78bfa" stroke-width="2.0" opacity="0.50" stroke-linecap="round">
        <animate attributeName="opacity" values="0.40;0.60;0.40" dur="8s" begin="0s" repeatCount="indefinite"/>
      </path>
      <path d="M 412.7 174.9 Q 412.7 174.9 403.7 175.8 Q 394.7 176.8 384.3 177.1 Q 373.8 177.5 362.5 177.2 Q 351.1 176.9 339.3 175.9 Q 327.6 174.9 316.2 173.2 Q 304.9 171.4 294.5 169.0 Q 284.2 166.5 275.6 163.3 L 267.0 160.1" fill="none" stroke="#a78bfa" stroke-width="1.7" opacity="0.40" stroke-linecap="round">
        <animate attributeName="opacity" values="0.30;0.50;0.30" dur="8s" begin="0s" repeatCount="indefinite"/>
      </path>
      <path d="M 267.0 160.1 Q 267.0 160.1 260.8 156.3 Q 254.6 152.5 251.4 148.3 Q 248.2 144.0 248.5 139.4 Q 248.8 134.8 252.9 130.0 Q 257.1 125.3 265.2 120.6 Q 273.4 115.9 285.6 111.6 Q 297.8 107.2 313.9 103.3 L 330.0 99.4" fill="none" stroke="#a78bfa" stroke-width="1.4" opacity="0.30" stroke-linecap="round">
        <animate attributeName="opacity" values="0.20;0.40;0.20" dur="8s" begin="0s" repeatCount="indefinite"/>
      </path>
      <path d="M 330.0 99.4 Q 330.0 99.4 349.7 96.3 Q 369.3 93.2 391.9 91.0 Q 414.4 88.8 439.3 87.6 Q 464.1 86.5 490.4 86.7 Q 516.6 86.8 543.3 88.2 Q 570.0 89.7 596.0 92.5 Q 622.1 95.3 646.4 99.4 L 670.7 103.6" fill="none" stroke="#a78bfa" stroke-width="1.1" opacity="0.20" stroke-linecap="round">
        <animate attributeName="opacity" values="0.10;0.30;0.10" dur="8s" begin="0s" repeatCount="indefinite"/>
      </path>
      <path d="M 425.0 155.0 Q 425.0 155.0 419.6 155.5 Q 414.3 156.0 408.4 155.9 Q 402.5 155.9 396.7 155.3 Q 390.9 154.8 385.7 153.7 Q 380.5 152.6 376.5 151.0 Q 372.5 149.4 370.2 147.5 Q 367.9 145.5 367.8 143.3 L 367.6 141.0" fill="none" stroke="#00d4ff" stroke-width="2.0" opacity="0.50" stroke-linecap="round">
        <animate attributeName="opacity" values="0.40;0.60;0.40" dur="8s" begin="1s" repeatCount="indefinite"/>
      </path>
      <path d="M 367.6 141.0 Q 367.6 141.0 369.8 138.6 Q 372.0 136.2 376.8 133.9 Q 381.7 131.5 389.1 129.3 Q 396.5 127.1 406.5 125.2 Q 416.4 123.4 428.6 122.0 Q 440.7 120.6 454.7 119.9 Q 468.7 119.2 483.9 119.2 L 499.1 119.3" fill="none" stroke="#00d4ff" stroke-width="1.7" opacity="0.40" stroke-linecap="round">
        <animate attributeName="opacity" values="0.30;0.50;0.30" dur="8s" begin="1s" repeatCount="indefinite"/>
      </path>
      <path d="M 499.1 119.3 Q 499.1 119.3 514.9 120.2 Q 530.7 121.1 546.4 122.8 Q 562.0 124.6 576.8 127.3 Q 591.5 130.0 604.4 133.6 Q 617.4 137.2 627.8 141.6 Q 638.2 145.9 645.4 151.0 Q 652.5 156.0 655.8 161.6 L 659.1 167.2" fill="none" stroke="#00d4ff" stroke-width="1.4" opacity="0.30" stroke-linecap="round">
        <animate attributeName="opacity" values="0.20;0.40;0.20" dur="8s" begin="1s" repeatCount="indefinite"/>
      </path>
      <path d="M 659.1 167.2 Q 659.1 167.2 658.0 173.0 Q 656.9 178.9 651.1 184.9 Q 645.3 190.8 634.6 196.6 Q 623.9 202.4 608.5 207.8 Q 593.0 213.2 573.1 217.9 Q 553.1 222.6 529.1 226.4 Q 505.1 230.1 477.7 232.8 L 450.3 235.5" fill="none" stroke="#00d4ff" stroke-width="1.1" opacity="0.20" stroke-linecap="round">
        <animate attributeName="opacity" values="0.10;0.30;0.10" dur="8s" begin="1s" repeatCount="indefinite"/>
      </path>
      <path d="M 425.0 155.0 Q 425.0 155.0 425.6 153.6 Q 426.1 152.1 428.7 150.8 Q 431.3 149.5 435.8 148.4 Q 440.3 147.3 446.4 146.5 Q 452.5 145.8 459.8 145.6 Q 467.1 145.3 475.1 145.6 Q 483.1 145.9 491.2 146.8 L 499.3 147.7" fill="none" stroke="#ffb020" stroke-width="2.0" opacity="0.50" stroke-linecap="round">
        <animate attributeName="opacity" values="0.40;0.60;0.40" dur="8s" begin="2s" repeatCount="indefinite"/>
      </path>
      <path d="M 499.3 147.7 Q 499.3 147.7 506.9 149.2 Q 514.5 150.8 520.9 152.9 Q 527.4 155.0 532.1 157.6 Q 536.9 160.3 539.3 163.3 Q 541.8 166.4 541.5 169.8 Q 541.3 173.1 538.0 176.6 Q 534.6 180.2 528.1 183.6 L 521.5 187.1" fill="none" stroke="#ffb020" stroke-width="1.7" opacity="0.40" stroke-linecap="round">
        <animate attributeName="opacity" values="0.30;0.50;0.30" dur="8s" begin="2s" repeatCount="indefinite"/>
      </path>
      <path d="M 521.5 187.1 Q 521.5 187.1 511.6 190.4 Q 501.8 193.6 488.7 196.5 Q 475.7 199.3 459.8 201.5 Q 443.9 203.8 425.7 205.2 Q 407.4 206.7 387.3 207.2 Q 367.3 207.8 346.2 207.3 Q 325.1 206.8 303.8 205.2 L 282.6 203.6" fill="none" stroke="#ffb020" stroke-width="1.4" opacity="0.30" stroke-linecap="round">
        <animate attributeName="opacity" values="0.20;0.40;0.20" dur="8s" begin="2s" repeatCount="indefinite"/>
      </path>
      <path d="M 282.6 203.6 Q 282.6 203.6 262.0 200.9 Q 241.5 198.1 222.6 194.3 Q 203.8 190.4 187.6 185.5 Q 171.4 180.6 158.6 174.8 Q 145.9 169.0 137.5 162.4 Q 129.2 155.9 125.7 148.7 Q 122.3 141.6 124.4 134.2 L 126.5 126.8" fill="none" stroke="#ffb020" stroke-width="1.1" opacity="0.20" stroke-linecap="round">
        <animate attributeName="opacity" values="0.10;0.30;0.10" dur="8s" begin="2s" repeatCount="indefinite"/>
      </path>
  
    <!-- 7. Arm particles -->
      <circle r="1.5" fill="#a78bfa" opacity="0.6">
        <animateMotion dur="12s" begin="0s" repeatCount="indefinite" path="M 425.0 155.0 Q 425.0 155.0 429.6 155.8 Q 434.3 156.7 437.5 157.9 Q 440.8 159.2 442.3 160.7 Q 443.8 162.2 443.2 163.9 Q 442.6 165.6 439.8 167.4 Q 437.1 169.1 432.0 170.7 Q 427.0 172.3 419.9 173.6 Q 412.7 174.9 403.7 175.8 Q 394.7 176.8 384.3 177.1 Q 373.8 177.5 362.5 177.2 Q 351.1 176.9 339.3 175.9 Q 327.6 174.9 316.2 173.2 Q 304.9 171.4 294.5 169.0 Q 284.2 166.5 275.6 163.3 Q 267.0 160.1 260.8 156.3 Q 254.6 152.5 251.4 148.3 Q 248.2 144.0 248.5 139.4 Q 248.8 134.8 252.9 130.0 Q 257.1 125.3 265.2 120.6 Q 273.4 115.9 285.6 111.6 Q 297.8 107.2 313.9 103.3 Q 330.0 99.4 349.7 96.3 Q 369.3 93.2 391.9 91.0 Q 414.4 88.8 439.3 87.6 Q 464.1 86.5 490.4 86.7 Q 516.6 86.8 543.3 88.2 Q 570.0 89.7 596.0 92.5 Q 622.1 95.3 646.4 99.4 Q 670.7 103.6 692.1 109.0 L 713.6 114.5"/>
        <animate attributeName="opacity" values="0;0.7;0.3;0" dur="12s" begin="0s" repeatCount="indefinite"/>
      </circle>
      <circle r="1.5" fill="#a78bfa" opacity="0.6">
        <animateMotion dur="12s" begin="6s" repeatCount="indefinite" path="M 425.0 155.0 Q 425.0 155.0 429.6 155.8 Q 434.3 156.7 437.5 157.9 Q 440.8 159.2 442.3 160.7 Q 443.8 162.2 443.2 163.9 Q 442.6 165.6 439.8 167.4 Q 437.1 169.1 432.0 170.7 Q 427.0 172.3 419.9 173.6 Q 412.7 174.9 403.7 175.8 Q 394.7 176.8 384.3 177.1 Q 373.8 177.5 362.5 177.2 Q 351.1 176.9 339.3 175.9 Q 327.6 174.9 316.2 173.2 Q 304.9 171.4 294.5 169.0 Q 284.2 166.5 275.6 163.3 Q 267.0 160.1 260.8 156.3 Q 254.6 152.5 251.4 148.3 Q 248.2 144.0 248.5 139.4 Q 248.8 134.8 252.9 130.0 Q 257.1 125.3 265.2 120.6 Q 273.4 115.9 285.6 111.6 Q 297.8 107.2 313.9 103.3 Q 330.0 99.4 349.7 96.3 Q 369.3 93.2 391.9 91.0 Q 414.4 88.8 439.3 87.6 Q 464.1 86.5 490.4 86.7 Q 516.6 86.8 543.3 88.2 Q 570.0 89.7 596.0 92.5 Q 622.1 95.3 646.4 99.4 Q 670.7 103.6 692.1 109.0 L 713.6 114.5"/>
        <animate attributeName="opacity" values="0;0.7;0.3;0" dur="12s" begin="6s" repeatCount="indefinite"/>
      </circle>
      <circle r="1.5" fill="#00d4ff" opacity="0.6">
        <animateMotion dur="12s" begin="4s" repeatCount="indefinite" path="M 425.0 155.0 Q 425.0 155.0 419.6 155.5 Q 414.3 156.0 408.4 155.9 Q 402.5 155.9 396.7 155.3 Q 390.9 154.8 385.7 153.7 Q 380.5 152.6 376.5 151.0 Q 372.5 149.4 370.2 147.5 Q 367.9 145.5 367.8 143.3 Q 367.6 141.0 369.8 138.6 Q 372.0 136.2 376.8 133.9 Q 381.7 131.5 389.1 129.3 Q 396.5 127.1 406.5 125.2 Q 416.4 123.4 428.6 122.0 Q 440.7 120.6 454.7 119.9 Q 468.7 119.2 483.9 119.2 Q 499.1 119.3 514.9 120.2 Q 530.7 121.1 546.4 122.8 Q 562.0 124.6 576.8 127.3 Q 591.5 130.0 604.4 133.6 Q 617.4 137.2 627.8 141.6 Q 638.2 145.9 645.4 151.0 Q 652.5 156.0 655.8 161.6 Q 659.1 167.2 658.0 173.0 Q 656.9 178.9 651.1 184.9 Q 645.3 190.8 634.6 196.6 Q 623.9 202.4 608.5 207.8 Q 593.0 213.2 573.1 217.9 Q 553.1 222.6 529.1 226.4 Q 505.1 230.1 477.7 232.8 Q 450.3 235.5 420.4 236.8 L 390.5 238.1"/>
        <animate attributeName="opacity" values="0;0.7;0.3;0" dur="12s" begin="4s" repeatCount="indefinite"/>
      </circle>
      <circle r="1.5" fill="#00d4ff" opacity="0.6">
        <animateMotion dur="12s" begin="10s" repeatCount="indefinite" path="M 425.0 155.0 Q 425.0 155.0 419.6 155.5 Q 414.3 156.0 408.4 155.9 Q 402.5 155.9 396.7 155.3 Q 390.9 154.8 385.7 153.7 Q 380.5 152.6 376.5 151.0 Q 372.5 149.4 370.2 147.5 Q 367.9 145.5 367.8 143.3 Q 367.6 141.0 369.8 138.6 Q 372.0 136.2 376.8 133.9 Q 381.7 131.5 389.1 129.3 Q 396.5 127.1 406.5 125.2 Q 416.4 123.4 428.6 122.0 Q 440.7 120.6 454.7 119.9 Q 468.7 119.2 483.9 119.2 Q 499.1 119.3 514.9 120.2 Q 530.7 121.1 546.4 122.8 Q 562.0 124.6 576.8 127.3 Q 591.5 130.0 604.4 133.6 Q 617.4 137.2 627.8 141.6 Q 638.2 145.9 645.4 151.0 Q 652.5 156.0 655.8 161.6 Q 659.1 167.2 658.0 173.0 Q 656.9 178.9 651.1 184.9 Q 645.3 190.8 634.6 196.6 Q 623.9 202.4 608.5 207.8 Q 593.0 213.2 573.1 217.9 Q 553.1 222.6 529.1 226.4 Q 505.1 230.1 477.7 232.8 Q 450.3 235.5 420.4 236.8 L 390.5 238.1"/>
        <animate attributeName="opacity" values="0;0.7;0.3;0" dur="12s" begin="10s" repeatCount="indefinite"/>
      </circle>
      <circle r="1.5" fill="#ffb020" opacity="0.6">
        <animateMotion dur="12s" begin="8s" repeatCount="indefinite" path="M 425.0 155.0 Q 425.0 155.0 425.6 153.6 Q 426.1 152.1 428.7 150.8 Q 431.3 149.5 435.8 148.4 Q 440.3 147.3 446.4 146.5 Q 452.5 145.8 459.8 145.6 Q 467.1 145.3 475.1 145.6 Q 483.1 145.9 491.2 146.8 Q 499.3 147.7 506.9 149.2 Q 514.5 150.8 520.9 152.9 Q 527.4 155.0 532.1 157.6 Q 536.9 160.3 539.3 163.3 Q 541.8 166.4 541.5 169.8 Q 541.3 173.1 538.0 176.6 Q 534.6 180.2 528.1 183.6 Q 521.5 187.1 511.6 190.4 Q 501.8 193.6 488.7 196.5 Q 475.7 199.3 459.8 201.5 Q 443.9 203.8 425.7 205.2 Q 407.4 206.7 387.3 207.2 Q 367.3 207.8 346.2 207.3 Q 325.1 206.8 303.8 205.2 Q 282.6 203.6 262.0 200.9 Q 241.5 198.1 222.6 194.3 Q 203.8 190.4 187.6 185.5 Q 171.4 180.6 158.6 174.8 Q 145.9 169.0 137.5 162.4 Q 129.2 155.9 125.7 148.7 Q 122.3 141.6 124.4 134.2 Q 126.5 126.8 134.3 119.4 L 142.1 111.9"/>
        <animate attributeName="opacity" values="0;0.7;0.3;0" dur="12s" begin="8s" repeatCount="indefinite"/>
      </circle>
      <circle r="1.5" fill="#ffb020" opacity="0.6">
        <animateMotion dur="12s" begin="14s" repeatCount="indefinite" path="M 425.0 155.0 Q 425.0 155.0 425.6 153.6 Q 426.1 152.1 428.7 150.8 Q 431.3 149.5 435.8 148.4 Q 440.3 147.3 446.4 146.5 Q 452.5 145.8 459.8 145.6 Q 467.1 145.3 475.1 145.6 Q 483.1 145.9 491.2 146.8 Q 499.3 147.7 506.9 149.2 Q 514.5 150.8 520.9 152.9 Q 527.4 155.0 532.1 157.6 Q 536.9 160.3 539.3 163.3 Q 541.8 166.4 541.5 169.8 Q 541.3 173.1 538.0 176.6 Q 534.6 180.2 528.1 183.6 Q 521.5 187.1 511.6 190.4 Q 501.8 193.6 488.7 196.5 Q 475.7 199.3 459.8 201.5 Q 443.9 203.8 425.7 205.2 Q 407.4 206.7 387.3 207.2 Q 367.3 207.8 346.2 207.3 Q 325.1 206.8 303.8 205.2 Q 282.6 203.6 262.0 200.9 Q 241.5 198.1 222.6 194.3 Q 203.8 190.4 187.6 185.5 Q 171.4 180.6 158.6 174.8 Q 145.9 169.0 137.5 162.4 Q 129.2 155.9 125.7 148.7 Q 122.3 141.6 124.4 134.2 Q 126.5 126.8 134.3 119.4 L 142.1 111.9"/>
        <animate attributeName="opacity" values="0;0.7;0.3;0" dur="12s" begin="14s" repeatCount="indefinite"/>
      </circle>
  
    <!-- 8. Tech dots + leader lines + labels -->
      <circle cx="394.7" cy="176.8" r="2.5" fill="#a78bfa" opacity="0.85">
        <animate attributeName="opacity" values="0.85;1;0.85" dur="5s" begin="0.0s" repeatCount="indefinite"/>
      </circle>
      <line x1="394.7" y1="176.8" x2="380.1" y2="187.3" stroke="#a78bfa" stroke-width="0.5" opacity="0.25" stroke-dasharray="2 2"/>
      <text x="380.1" y="190.3" text-anchor="end" fill="#a78bfa" font-size="9" font-family="monospace" opacity="0.2" filter="url(#label-glow)">Vue.js</text>
      <text x="380.1" y="190.3" text-anchor="end" fill="#a78bfa" font-size="9" font-family="monospace" opacity="0.85">Vue.js</text>
      <circle cx="284.2" cy="166.5" r="2.5" fill="#a78bfa" opacity="0.85">
        <animate attributeName="opacity" values="0.85;1;0.85" dur="5s" begin="0.7s" repeatCount="indefinite"/>
      </circle>
      <line x1="284.2" y1="166.5" x2="266.2" y2="167.9" stroke="#a78bfa" stroke-width="0.5" opacity="0.25" stroke-dasharray="2 2"/>
      <text x="266.2" y="170.9" text-anchor="end" fill="#a78bfa" font-size="9" font-family="monospace" opacity="0.2" filter="url(#label-glow)">HTML</text>
      <text x="266.2" y="170.9" text-anchor="end" fill="#a78bfa" font-size="9" font-family="monospace" opacity="0.85">HTML</text>
      <circle cx="257.1" cy="125.3" r="2.5" fill="#a78bfa" opacity="0.85">
        <animate attributeName="opacity" values="0.85;1;0.85" dur="5s" begin="1.4s" repeatCount="indefinite"/>
      </circle>
      <line x1="257.1" y1="125.3" x2="239.3" y2="122.2" stroke="#a78bfa" stroke-width="0.5" opacity="0.25" stroke-dasharray="2 2"/>
      <text x="239.3" y="125.2" text-anchor="end" fill="#a78bfa" font-size="9" font-family="monospace" opacity="0.2" filter="url(#label-glow)">CSS</text>
      <text x="239.3" y="125.2" text-anchor="end" fill="#a78bfa" font-size="9" font-family="monospace" opacity="0.85">CSS</text>
      <circle cx="414.4" cy="88.8" r="2.5" fill="#a78bfa" opacity="0.85">
        <animate attributeName="opacity" values="0.85;1;0.85" dur="5s" begin="2.0999999999999996s" repeatCount="indefinite"/>
      </circle>
      <line x1="414.4" y1="88.8" x2="411.6" y2="71.0" stroke="#a78bfa" stroke-width="0.5" opacity="0.25" stroke-dasharray="2 2"/>
      <text x="411.6" y="74.0" text-anchor="middle" fill="#a78bfa" font-size="9" font-family="monospace" opacity="0.2" filter="url(#label-glow)">Javascript</text>
      <text x="411.6" y="74.0" text-anchor="middle" fill="#a78bfa" font-size="9" font-family="monospace" opacity="0.85">Javascript</text>
      <circle cx="372.0" cy="136.2" r="2.5" fill="#00d4ff" opacity="0.85">
        <animate attributeName="opacity" values="0.85;1;0.85" dur="5s" begin="0.0s" repeatCount="indefinite"/>
      </circle>
      <line x1="372.0" y1="136.2" x2="355.1" y2="130.2" stroke="#00d4ff" stroke-width="0.5" opacity="0.25" stroke-dasharray="2 2"/>
      <text x="355.1" y="133.2" text-anchor="end" fill="#00d4ff" font-size="9" font-family="monospace" opacity="0.2" filter="url(#label-glow)">C#</text>
      <text x="355.1" y="133.2" text-anchor="end" fill="#00d4ff" font-size="9" font-family="monospace" opacity="0.85">C#</text>
      <circle cx="468.7" cy="119.2" r="2.5" fill="#00d4ff" opacity="0.85">
        <animate attributeName="opacity" values="0.85;1;0.85" dur="5s" begin="0.7s" repeatCount="indefinite"/>
      </circle>
      <line x1="468.7" y1="119.2" x2="482.6" y2="107.8" stroke="#00d4ff" stroke-width="0.5" opacity="0.25" stroke-dasharray="2 2"/>
      <text x="482.6" y="110.8" text-anchor="start" fill="#00d4ff" font-size="9" font-family="monospace" opacity="0.2" filter="url(#label-glow)">.NET 9</text>
      <text x="482.6" y="110.8" text-anchor="start" fill="#00d4ff" font-size="9" font-family="monospace" opacity="0.85">.NET 9</text>
      <circle cx="617.4" cy="137.2" r="2.5" fill="#00d4ff" opacity="0.85">
        <animate attributeName="opacity" values="0.85;1;0.85" dur="5s" begin="1.4s" repeatCount="indefinite"/>
      </circle>
      <line x1="617.4" y1="137.2" x2="635.3" y2="135.5" stroke="#00d4ff" stroke-width="0.5" opacity="0.25" stroke-dasharray="2 2"/>
      <text x="635.3" y="138.5" text-anchor="start" fill="#00d4ff" font-size="9" font-family="monospace" opacity="0.2" filter="url(#label-glow)">PostgreSQL</text>
      <text x="635.3" y="138.5" text-anchor="start" fill="#00d4ff" font-size="9" font-family="monospace" opacity="0.85">PostgreSQL</text>
      <circle cx="645.3" cy="190.8" r="2.5" fill="#00d4ff" opacity="0.85">
        <animate attributeName="opacity" values="0.85;1;0.85" dur="5s" begin="2.0999999999999996s" repeatCount="indefinite"/>
      </circle>
      <line x1="645.3" y1="190.8" x2="663.0" y2="193.7" stroke="#00d4ff" stroke-width="0.5" opacity="0.25" stroke-dasharray="2 2"/>
      <text x="663.0" y="196.7" text-anchor="start" fill="#00d4ff" font-size="9" font-family="monospace" opacity="0.2" filter="url(#label-glow)">SqlServer</text>
      <text x="663.0" y="196.7" text-anchor="start" fill="#00d4ff" font-size="9" font-family="monospace" opacity="0.85">SqlServer</text>
      <circle cx="514.5" cy="150.8" r="2.5" fill="#ffb020" opacity="0.85">
        <animate attributeName="opacity" values="0.85;1;0.85" dur="5s" begin="0.0s" repeatCount="indefinite"/>
      </circle>
      <line x1="514.5" y1="150.8" x2="532.5" y2="149.9" stroke="#ffb020" stroke-width="0.5" opacity="0.25" stroke-dasharray="2 2"/>
      <text x="532.5" y="152.9" text-anchor="start" fill="#ffb020" font-size="9" font-family="monospace" opacity="0.2" filter="url(#label-glow)">Docker</text>
      <text x="532.5" y="152.9" text-anchor="start" fill="#ffb020" font-size="9" font-family="monospace" opacity="0.85">Docker</text>
      <circle cx="534.6" cy="180.2" r="2.5" fill="#ffb020" opacity="0.85">
        <animate attributeName="opacity" values="0.85;1;0.85" dur="5s" begin="0.7s" repeatCount="indefinite"/>
      </circle>
      <line x1="534.6" y1="180.2" x2="552.2" y2="184.2" stroke="#ffb020" stroke-width="0.5" opacity="0.25" stroke-dasharray="2 2"/>
      <text x="552.2" y="187.2" text-anchor="start" fill="#ffb020" font-size="9" font-family="monospace" opacity="0.2" filter="url(#label-glow)">GitHub Actions</text>
      <text x="552.2" y="187.2" text-anchor="start" fill="#ffb020" font-size="9" font-family="monospace" opacity="0.85">GitHub Actions</text>
      <circle cx="407.4" cy="206.7" r="2.5" fill="#ffb020" opacity="0.85">
        <animate attributeName="opacity" values="0.85;1;0.85" dur="5s" begin="1.4s" repeatCount="indefinite"/>
      </circle>
      <line x1="407.4" y1="206.7" x2="401.6" y2="223.7" stroke="#ffb020" stroke-width="0.5" opacity="0.25" stroke-dasharray="2 2"/>
      <text x="401.6" y="226.7" text-anchor="middle" fill="#ffb020" font-size="9" font-family="monospace" opacity="0.2" filter="url(#label-glow)">Kubernetes</text>
      <text x="401.6" y="226.7" text-anchor="middle" fill="#ffb020" font-size="9" font-family="monospace" opacity="0.85">Kubernetes</text>
      <circle cx="203.8" cy="190.4" r="2.5" fill="#ffb020" opacity="0.85">
        <animate attributeName="opacity" values="0.85;1;0.85" dur="5s" begin="2.0999999999999996s" repeatCount="indefinite"/>
      </circle>
      <line x1="203.8" y1="190.4" x2="186.0" y2="193.3" stroke="#ffb020" stroke-width="0.5" opacity="0.25" stroke-dasharray="2 2"/>
      <text x="186.0" y="196.3" text-anchor="end" fill="#ffb020" font-size="9" font-family="monospace" opacity="0.2" filter="url(#label-glow)">CI/CD</text>
      <text x="186.0" y="196.3" text-anchor="end" fill="#ffb020" font-size="9" font-family="monospace" opacity="0.85">CI/CD</text>
  
    <!-- 9. Project stars -->
      <circle cx="623.9" cy="202.4" r="4" fill="#00d4ff" filter="url(#star-glow-1)">
        <animate attributeName="opacity" values="0.6;1;0.6" dur="4s" begin="0.8s" repeatCount="indefinite"/>
      </circle>
      <circle cx="623.9" cy="202.4" r="4" fill="#00d4ff" filter="url(#star-glow-1)">
        <animate attributeName="opacity" values="0.6;1;0.6" dur="4s" begin="0.8s" repeatCount="indefinite"/>
      </circle>
  
    <!-- 10. Orbital rings -->
      <ellipse cx="425" cy="155" rx="55" ry="18" fill="none" stroke="#00d4ff" stroke-width="0.6" opacity="0.15" stroke-dasharray="4 6">
        <animateTransform attributeName="transform" type="rotate" from="0 425 155" to="360 425 155" dur="20s" repeatCount="indefinite"/>
      </ellipse>
      <ellipse cx="425" cy="155" rx="75" ry="24" fill="none" stroke="#a78bfa" stroke-width="0.5" opacity="0.1" stroke-dasharray="3 8">
        <animateTransform attributeName="transform" type="rotate" from="360 425 155" to="0 425 155" dur="30s" repeatCount="indefinite"/>
      </ellipse>
  
    <!-- 11. Galaxy core -->
      <!-- Outer haze -->
      <circle cx="425" cy="155" r="40" fill="url(#core-haze-gradient)" opacity="0.4"/>
      <!-- Inner glow -->
      <circle cx="425" cy="155" r="24" fill="url(#core-inner-gradient)" opacity="0.6"/>
      <!-- Outer ring -->
      <ellipse cx="425" cy="155" rx="20" ry="18" fill="none" stroke="#00d4ff" stroke-width="1.2" opacity="0.55" stroke-dasharray="5 3" class="core-ring"/>
      <!-- Inner ring -->
      <circle cx="425" cy="155" r="14" fill="none" stroke="#a78bfa" stroke-width="0.8" opacity="0.4" class="core-ring-inner"/>
      <!-- Solid core -->
      <circle cx="425" cy="155" r="11" fill="#0f1623" stroke="#1a2332" stroke-width="0.5"/>
      <!-- Bright center dot -->
      <circle cx="425" cy="155" r="3" fill="#00d4ff" filter="url(#core-bright-glow)" opacity="0.9"/>
      <!-- Initial -->
      <text x="425" y="160" text-anchor="middle" fill="#00d4ff" font-size="14" font-weight="bold" font-family="monospace">W</text>
  
    <!-- 12. Profile text -->
    <text x="425" y="26" text-anchor="middle" fill="#f1f5f9" font-size="20" font-weight="bold" font-family="sans-serif">Willian Brito</text>
    <text x="425" y="44" text-anchor="middle" fill="#94a3b8" font-size="12" font-family="sans-serif">Engenheiro de Software</text>
    <text x="425" y="268" text-anchor="middle" fill="#64748b" font-size="11" font-family="monospace" font-style="italic">&quot;Escalabilidade não é acidente, é decisão de arquitetura.&quot;</text>
  </svg>

  <!--  stats card -->
  <svg xmlns="http://www.w3.org/2000/svg" width="850" height="180" viewBox="0 0 850 180">
  <defs>
    <style>
      .metric-icon {
        animation: count-glow 4s ease-in-out infinite;
      }
      @keyframes count-glow {
        0%, 100% { fill-opacity: 0.7; }
        50% { fill-opacity: 1; }
      }
    </style>
    <filter id="num-glow" x="-30%" y="-30%" width="160%" height="160%">
      <feGaussianBlur stdDeviation="3"/>
    </filter>
  </defs>

  <!-- Card background -->
  <rect x="0.5" y="0.5" width="849" height="179" rx="12" ry="12"
        fill="#0f1623" stroke="#1a2332" stroke-width="1"/>

  <!-- Section title -->
  <text x="30" y="38" fill="#64748b" font-size="11" font-family="monospace" letter-spacing="3">MISSION TELEMETRY</text>

  <!-- Dividers -->
    <line x1="170.0" y1="55" x2="170.0" y2="155" stroke="#1a2332" stroke-width="1" opacity="0.5"/>
    <line x1="340.0" y1="55" x2="340.0" y2="155" stroke="#1a2332" stroke-width="1" opacity="0.5"/>
    <line x1="510.0" y1="55" x2="510.0" y2="155" stroke="#1a2332" stroke-width="1" opacity="0.5"/>
    <line x1="680.0" y1="55" x2="680.0" y2="155" stroke="#1a2332" stroke-width="1" opacity="0.5"/>

  <!-- Metric cells -->
    <g class="metric-cell" transform="translate(85.0, 95)">
      <g transform="translate(-8, -30) scale(1)">
        <svg viewBox="0 0 16 16" width="16" height="16" fill="#00d4ff" class="metric-icon" style="animation-delay: 0.0s">
          <path d="M8 1a7 7 0 1 0 0 14A7 7 0 0 0 8 1zm0 2.5a4.5 4.5 0 0 1 4.473 4H14.5a.5.5 0 0 1 0 1h-2.027A4.5 4.5 0 0 1 8 12.5a4.5 4.5 0 0 1-4.473-4H1.5a.5.5 0 0 1 0-1h2.027A4.5 4.5 0 0 1 8 3.5zm0 1.5a3 3 0 1 0 0 6 3 3 0 0 0 0-6z"/>
        </svg>
      </g>
      <text x="0" y="2" text-anchor="middle" fill="#00d4ff" font-size="28" font-weight="bold" font-family="sans-serif" opacity="0.35" filter="url(#num-glow)">394</text>
      <text x="0" y="2" text-anchor="middle" fill="#f1f5f9" font-size="28" font-weight="bold" font-family="sans-serif">394</text>
      <text x="0" y="20" text-anchor="middle" fill="#64748b" font-size="11" font-family="monospace" letter-spacing="1">Commits</text>
    </g>
    <g class="metric-cell" transform="translate(255.0, 95)">
      <g transform="translate(-8, -30) scale(1)">
        <svg viewBox="0 0 16 16" width="16" height="16" fill="#ffb020" class="metric-icon" style="animation-delay: 0.3s">
          <path d="M8 .25a.75.75 0 0 1 .673.418l1.882 3.815 4.21.612a.75.75 0 0 1 .416 1.279l-3.046 2.97.719 4.192a.75.75 0 0 1-1.088.791L8 12.347l-3.766 1.98a.75.75 0 0 1-1.088-.79l.72-4.194L.818 6.374a.75.75 0 0 1 .416-1.28l4.21-.611L7.327.668A.75.75 0 0 1 8 .25z"/>
        </svg>
      </g>
      <text x="0" y="2" text-anchor="middle" fill="#ffb020" font-size="28" font-weight="bold" font-family="sans-serif" opacity="0.35" filter="url(#num-glow)">27</text>
      <text x="0" y="2" text-anchor="middle" fill="#f1f5f9" font-size="28" font-weight="bold" font-family="sans-serif">27</text>
      <text x="0" y="20" text-anchor="middle" fill="#64748b" font-size="11" font-family="monospace" letter-spacing="1">Stars</text>
    </g>
    <g class="metric-cell" transform="translate(425.0, 95)">
      <g transform="translate(-8, -30) scale(1)">
        <svg viewBox="0 0 16 16" width="16" height="16" fill="#a78bfa" class="metric-icon" style="animation-delay: 0.6s">
          <path d="M5 3.254V3.25v.005a.75.75 0 1 1 0-.005zm6.5 8a.75.75 0 1 1 0 1.5.75.75 0 0 1 0-1.5zM5 12.75a.75.75 0 1 1 0 1.5.75.75 0 0 1 0-1.5zm-1.5.75a1.5 1.5 0 1 0 1.5 1.5v-8.5a1.5 1.5 0 1 0-1.5-1.5v8.5a1.5 1.5 0 0 0 0 0zm8.5-2.5a1.5 1.5 0 0 0-1.5 1.5 1.5 1.5 0 1 0 3 0v-3.133l.025-.05A3.252 3.252 0 0 0 11 5.25V3.5h1.25a.75.75 0 0 0 .53-1.28l-2-2a.75.75 0 0 0-1.06 0l-2 2A.75.75 0 0 0 8.25 3.5H9.5v1.75a1.75 1.75 0 0 0 1.75 1.75h.244a1.75 1.75 0 0 1 1.006.319V11a1.5 1.5 0 0 0-1.5-1.5z"/>
        </svg>
      </g>
      <text x="0" y="2" text-anchor="middle" fill="#a78bfa" font-size="28" font-weight="bold" font-family="sans-serif" opacity="0.35" filter="url(#num-glow)">20</text>
      <text x="0" y="2" text-anchor="middle" fill="#f1f5f9" font-size="28" font-weight="bold" font-family="sans-serif">20</text>
      <text x="0" y="20" text-anchor="middle" fill="#64748b" font-size="11" font-family="monospace" letter-spacing="1">PRs</text>
    </g>
    <g class="metric-cell" transform="translate(595.0, 95)">
      <g transform="translate(-8, -30) scale(1)">
        <svg viewBox="0 0 16 16" width="16" height="16" fill="#00d4ff" class="metric-icon" style="animation-delay: 0.8999999999999999s">
          <path d="M8 9.5a1.5 1.5 0 1 0 0-3 1.5 1.5 0 0 0 0 3z"/><path d="M8 0a8 8 0 1 1 0 16A8 8 0 0 1 8 0zm0 1.5a6.5 6.5 0 1 0 0 13 6.5 6.5 0 0 0 0-13z"/>
        </svg>
      </g>
      <text x="0" y="2" text-anchor="middle" fill="#00d4ff" font-size="28" font-weight="bold" font-family="sans-serif" opacity="0.35" filter="url(#num-glow)">8</text>
      <text x="0" y="2" text-anchor="middle" fill="#f1f5f9" font-size="28" font-weight="bold" font-family="sans-serif">8</text>
      <text x="0" y="20" text-anchor="middle" fill="#64748b" font-size="11" font-family="monospace" letter-spacing="1">Issues</text>
    </g>
    <g class="metric-cell" transform="translate(765.0, 95)">
      <g transform="translate(-8, -30) scale(1)">
        <svg viewBox="0 0 16 16" width="16" height="16" fill="#a78bfa" class="metric-icon" style="animation-delay: 1.2s">
          <path d="M2 2.5A2.5 2.5 0 0 1 4.5 0h8.75a.75.75 0 0 1 .75.75v12.5a.75.75 0 0 1-.75.75h-2.5a.75.75 0 0 1 0-1.5h1.75v-2h-8a1 1 0 0 0-.714 1.7.75.75 0 0 1-1.072 1.05A2.495 2.495 0 0 1 2 11.5zm10.5-1h-8a1 1 0 0 0-1 1v6.708A2.486 2.486 0 0 1 4.5 9h8zM5 12.25a.25.25 0 0 1 .25-.25h3.5a.25.25 0 0 1 .25.25v3.25a.25.25 0 0 1-.4.2l-1.45-1.087a.25.25 0 0 0-.3 0L5.4 15.7a.25.25 0 0 1-.4-.2z"/>
        </svg>
      </g>
      <text x="0" y="2" text-anchor="middle" fill="#a78bfa" font-size="28" font-weight="bold" font-family="sans-serif" opacity="0.35" filter="url(#num-glow)">41</text>
      <text x="0" y="2" text-anchor="middle" fill="#f1f5f9" font-size="28" font-weight="bold" font-family="sans-serif">41</text>
      <text x="0" y="20" text-anchor="middle" fill="#64748b" font-size="11" font-family="monospace" letter-spacing="1">Repos</text>
    </g>
</svg>

<!-- tech stack -->
<svg xmlns="http://www.w3.org/2000/svg" width="850" height="261" viewBox="0 0 850 261">
  <defs/>

  <!-- Card background -->
  <rect x="0.5" y="0.5" width="849" height="260" rx="12" ry="12"
        fill="#0f1623" stroke="#1a2332" stroke-width="1"/>

  <!-- Left: Language Telemetry -->
  <text x="30" y="38" fill="#64748b" font-size="11" font-family="monospace" letter-spacing="3">LANGUAGE TELEMETRY</text>

  <!-- Vertical divider -->
  <line x1="425" y1="25" x2="425" y2="236" stroke="#1a2332" stroke-width="1" opacity="0.4"/>

  <!-- Right: Focus Sectors -->
  <text x="460" y="38" fill="#64748b" font-size="11" font-family="monospace" letter-spacing="3">FOCUS SECTORS</text>

    <g transform="translate(30, 65)">
      <text x="0" y="0" fill="#94a3b8" font-size="11" font-family="sans-serif" dominant-baseline="middle">C#</text>
      <rect x="110" y="-6" width="125.0" height="12" rx="3" fill="#178600" opacity="0.85">
        <animate attributeName="width" from="0" to="125.0" dur="0.8s" begin="0.0s" fill="freeze"/>
      </rect>
      <text x="320" y="0" fill="#64748b" font-size="10" font-family="monospace" dominant-baseline="middle">62.5%</text>
    </g>
    <g transform="translate(30, 87)">
      <text x="0" y="0" fill="#94a3b8" font-size="11" font-family="sans-serif" dominant-baseline="middle">PHP</text>
      <rect x="110" y="-6" width="18.6" height="12" rx="3" fill="#4F5D95" opacity="0.85">
        <animate attributeName="width" from="0" to="18.6" dur="0.8s" begin="0.1s" fill="freeze"/>
      </rect>
      <text x="320" y="0" fill="#64748b" font-size="10" font-family="monospace" dominant-baseline="middle">9.3%</text>
    </g>
    <g transform="translate(30, 109)">
      <text x="0" y="0" fill="#94a3b8" font-size="11" font-family="sans-serif" dominant-baseline="middle">Vue</text>
      <rect x="110" y="-6" width="15.4" height="12" rx="3" fill="#41b883" opacity="0.85">
        <animate attributeName="width" from="0" to="15.4" dur="0.8s" begin="0.2s" fill="freeze"/>
      </rect>
      <text x="320" y="0" fill="#64748b" font-size="10" font-family="monospace" dominant-baseline="middle">7.7%</text>
    </g>
    <g transform="translate(30, 131)">
      <text x="0" y="0" fill="#94a3b8" font-size="11" font-family="sans-serif" dominant-baseline="middle">Bicep</text>
      <rect x="110" y="-6" width="8.6" height="12" rx="3" fill="#8b949e" opacity="0.85">
        <animate attributeName="width" from="0" to="8.6" dur="0.8s" begin="0.30000000000000004s" fill="freeze"/>
      </rect>
      <text x="320" y="0" fill="#64748b" font-size="10" font-family="monospace" dominant-baseline="middle">4.3%</text>
    </g>
    <g transform="translate(30, 153)">
      <text x="0" y="0" fill="#94a3b8" font-size="11" font-family="sans-serif" dominant-baseline="middle">JavaScript</text>
      <rect x="110" y="-6" width="8.2" height="12" rx="3" fill="#f1e05a" opacity="0.85">
        <animate attributeName="width" from="0" to="8.2" dur="0.8s" begin="0.4s" fill="freeze"/>
      </rect>
      <text x="320" y="0" fill="#64748b" font-size="10" font-family="monospace" dominant-baseline="middle">4.1%</text>
    </g>
    <g transform="translate(30, 175)">
      <text x="0" y="0" fill="#94a3b8" font-size="11" font-family="sans-serif" dominant-baseline="middle">Pascal</text>
      <rect x="110" y="-6" width="6.0" height="12" rx="3" fill="#8b949e" opacity="0.85">
        <animate attributeName="width" from="0" to="6.0" dur="0.8s" begin="0.5s" fill="freeze"/>
      </rect>
      <text x="320" y="0" fill="#64748b" font-size="10" font-family="monospace" dominant-baseline="middle">3.0%</text>
    </g>
    <g transform="translate(30, 197)">
      <text x="0" y="0" fill="#94a3b8" font-size="11" font-family="sans-serif" dominant-baseline="middle">TypeScript</text>
      <rect x="110" y="-6" width="5.8" height="12" rx="3" fill="#3178c6" opacity="0.85">
        <animate attributeName="width" from="0" to="5.8" dur="0.8s" begin="0.6000000000000001s" fill="freeze"/>
      </rect>
      <text x="320" y="0" fill="#64748b" font-size="10" font-family="monospace" dominant-baseline="middle">2.9%</text>
    </g>
    <g transform="translate(30, 219)">
      <text x="0" y="0" fill="#94a3b8" font-size="11" font-family="sans-serif" dominant-baseline="middle">Java</text>
      <rect x="110" y="-6" width="4.4" height="12" rx="3" fill="#b07219" opacity="0.85">
        <animate attributeName="width" from="0" to="4.4" dur="0.8s" begin="0.7000000000000001s" fill="freeze"/>
      </rect>
      <text x="320" y="0" fill="#64748b" font-size="10" font-family="monospace" dominant-baseline="middle">2.2%</text>
    </g>

    <circle cx="637" cy="140" r="22" fill="none" stroke="#64748b" stroke-width="0.5" stroke-dasharray="3,3" opacity="0.25"/>
    <circle cx="637" cy="140" r="44" fill="none" stroke="#64748b" stroke-width="0.5" stroke-dasharray="3,3" opacity="0.25"/>
    <circle cx="637" cy="140" r="65" fill="none" stroke="#64748b" stroke-width="0.5" stroke-dasharray="3,3" opacity="0.25"/>
    <path d="M 637 140 L 638.1 75.0 A 65 65 0 0 1 693.9 171.5 Z" fill="#a78bfa" fill-opacity="0.10" stroke="#a78bfa" stroke-opacity="0.3" stroke-width="0.5"/>
    <path d="M 637 140 L 692.7 173.5 A 65 65 0 0 1 581.3 173.5 Z" fill="#00d4ff" fill-opacity="0.10" stroke="#00d4ff" stroke-opacity="0.3" stroke-width="0.5"/>
    <path d="M 637 140 L 580.1 171.5 A 65 65 0 0 1 635.9 75.0 Z" fill="#ffb020" fill-opacity="0.10" stroke="#ffb020" stroke-opacity="0.3" stroke-width="0.5"/>
    <line x1="637" y1="140" x2="637.0" y2="75.0" stroke="#64748b" stroke-width="0.5" opacity="0.3"/>
    <line x1="637" y1="140" x2="693.3" y2="172.5" stroke="#64748b" stroke-width="0.5" opacity="0.3"/>
    <line x1="637" y1="140" x2="580.7" y2="172.5" stroke="#64748b" stroke-width="0.5" opacity="0.3"/>
    <g>
      <!-- Sweep trail -->
      <path d="M 637 140 L 604.5 83.7 A 65 65 0 0 1 637.0 75.0 Z" fill="#00d4ff" fill-opacity="0.07"/>
      <!-- Outer wedge -->
      <polygon points="634.5,140 637,75 639.5,140" fill="#00d4ff" opacity="0.25"/>
      <!-- Inner bright core -->
      <polygon points="636.2,140 637,75 637.8,140" fill="#00d4ff" opacity="0.5"/>
      <!-- Tip glow -->
      <circle cx="637" cy="75" r="2" fill="#00d4ff" opacity="0.6">
        <animate attributeName="opacity" values="0.4;0.8;0.4" dur="2s" repeatCount="indefinite"/>
      </circle>
      <animateTransform attributeName="transform" type="rotate" from="0 637 140" to="360 637 140" dur="8s" repeatCount="indefinite"/>
    </g>
    <text x="708.9" y="98.5" fill="#a78bfa" font-size="9" font-family="monospace" text-anchor="start" dominant-baseline="middle">Frontend</text>
    <text x="708.9" y="110.5" fill="#64748b" font-size="8" font-family="monospace" text-anchor="start" dominant-baseline="middle">(4)</text>
    <text x="637.0" y="223.0" fill="#00d4ff" font-size="9" font-family="monospace" text-anchor="middle" dominant-baseline="middle">Backend</text>
    <text x="637.0" y="235.0" fill="#64748b" font-size="8" font-family="monospace" text-anchor="middle" dominant-baseline="middle">(4)</text>
    <text x="565.1" y="98.5" fill="#ffb020" font-size="9" font-family="monospace" text-anchor="end" dominant-baseline="middle">DevOps</text>
    <text x="565.1" y="110.5" fill="#64748b" font-size="8" font-family="monospace" text-anchor="end" dominant-baseline="middle">(4)</text>
    <circle cx="641.6" cy="116.4" r="3" fill="#a78bfa" opacity="0.35">
      <animate attributeName="opacity" values="0.35;0.35;1.0;0.35;0.35" keyTimes="0;0.04;0.06;0.10;1" dur="8s" begin="7.94s" repeatCount="indefinite"/>
    </circle>
    <circle cx="664.6" cy="111.1" r="3" fill="#a78bfa" opacity="0.35">
      <animate attributeName="opacity" values="0.35;0.35;1.0;0.35;0.35" keyTimes="0;0.04;0.06;0.10;1" dur="8s" begin="0.67s" repeatCount="indefinite"/>
    </circle>
    <circle cx="691.4" cy="126.8" r="3" fill="#a78bfa" opacity="0.35">
      <animate attributeName="opacity" values="0.35;0.35;1.0;0.35;0.35" keyTimes="0;0.04;0.06;0.10;1" dur="8s" begin="1.40s" repeatCount="indefinite"/>
    </circle>
    <circle cx="659.7" cy="147.8" r="3" fill="#a78bfa" opacity="0.35">
      <animate attributeName="opacity" values="0.35;0.35;1.0;0.35;0.35" keyTimes="0;0.04;0.06;0.10;1" dur="8s" begin="2.12s" repeatCount="indefinite"/>
    </circle>
    <circle cx="655.1" cy="155.7" r="3" fill="#00d4ff" opacity="0.35">
      <animate attributeName="opacity" values="0.35;0.35;1.0;0.35;0.35" keyTimes="0;0.04;0.06;0.10;1" dur="8s" begin="2.61s" repeatCount="indefinite"/>
    </circle>
    <circle cx="648.2" cy="178.4" r="3" fill="#00d4ff" opacity="0.35">
      <animate attributeName="opacity" values="0.35;0.35;1.0;0.35;0.35" keyTimes="0;0.04;0.06;0.10;1" dur="8s" begin="3.34s" repeatCount="indefinite"/>
    </circle>
    <circle cx="621.3" cy="193.7" r="3" fill="#00d4ff" opacity="0.35">
      <animate attributeName="opacity" values="0.35;0.35;1.0;0.35;0.35" keyTimes="0;0.04;0.06;0.10;1" dur="8s" begin="4.06s" repeatCount="indefinite"/>
    </circle>
    <circle cx="618.9" cy="155.7" r="3" fill="#00d4ff" opacity="0.35">
      <animate attributeName="opacity" values="0.35;0.35;1.0;0.35;0.35" keyTimes="0;0.04;0.06;0.10;1" dur="8s" begin="4.79s" repeatCount="indefinite"/>
    </circle>
    <circle cx="614.3" cy="147.8" r="3" fill="#ffb020" opacity="0.35">
      <animate attributeName="opacity" values="0.35;0.35;1.0;0.35;0.35" keyTimes="0;0.04;0.06;0.10;1" dur="8s" begin="5.28s" repeatCount="indefinite"/>
    </circle>
    <circle cx="598.1" cy="130.5" r="3" fill="#ffb020" opacity="0.35">
      <animate attributeName="opacity" values="0.35;0.35;1.0;0.35;0.35" keyTimes="0;0.04;0.06;0.10;1" dur="8s" begin="6.00s" repeatCount="indefinite"/>
    </circle>
    <circle cx="598.3" cy="99.5" r="3" fill="#ffb020" opacity="0.35">
      <animate attributeName="opacity" values="0.35;0.35;1.0;0.35;0.35" keyTimes="0;0.04;0.06;0.10;1" dur="8s" begin="6.73s" repeatCount="indefinite"/>
    </circle>
    <circle cx="632.4" cy="116.4" r="3" fill="#ffb020" opacity="0.35">
      <animate attributeName="opacity" values="0.35;0.35;1.0;0.35;0.35" keyTimes="0;0.04;0.06;0.10;1" dur="8s" begin="7.46s" repeatCount="indefinite"/>
    </circle>
</svg>

<!-- projects -->
  <svg xmlns="http://www.w3.org/2000/svg" width="850" height="220" viewBox="0 0 850 220">
  <defs>
    <filter id="proj-glow-0" x="-80%" y="-80%" width="260%" height="260%">
      <feGaussianBlur stdDeviation="4" in="SourceGraphic" result="blur"/>
      <feFlood flood-color="#00d4ff" flood-opacity="0.6" result="color"/>
      <feComposite in="color" in2="blur" operator="in" result="glow"/>
      <feMerge>
        <feMergeNode in="glow"/>
        <feMergeNode in="SourceGraphic"/>
      </feMerge>
    </filter>
    <filter id="proj-glow-1" x="-80%" y="-80%" width="260%" height="260%">
      <feGaussianBlur stdDeviation="4" in="SourceGraphic" result="blur"/>
      <feFlood flood-color="#00d4ff" flood-opacity="0.6" result="color"/>
      <feComposite in="color" in2="blur" operator="in" result="glow"/>
      <feMerge>
        <feMergeNode in="glow"/>
        <feMergeNode in="SourceGraphic"/>
      </feMerge>
    </filter>
    <filter id="card-nebula" x="-50%" y="-50%" width="200%" height="200%">
      <feGaussianBlur stdDeviation="15"/>
    </filter>
    <linearGradient id="card-bg-0" x1="0" y1="0" x2="0" y2="1">
      <stop offset="0%" stop-color="#1a2332" stop-opacity="0.6"/>
      <stop offset="100%" stop-color="#0f1623" stop-opacity="0.9"/>
    </linearGradient>
    <linearGradient id="card-bg-1" x1="0" y1="0" x2="0" y2="1">
      <stop offset="0%" stop-color="#1a2332" stop-opacity="0.6"/>
      <stop offset="100%" stop-color="#0f1623" stop-opacity="0.9"/>
    </linearGradient>
    <linearGradient id="conn-grad" x1="0" y1="0" x2="1" y2="0">
      <stop offset="0%" stop-color="#00d4ff" stop-opacity="0.4"/>
      <stop offset="100%" stop-color="#00d4ff" stop-opacity="0.4"/>
    </linearGradient>
    <clipPath id="card-clip-0">
      <rect x="56.666666666666664" y="55" width="340" height="140" rx="8" ry="8"/>
    </clipPath>
    <clipPath id="card-clip-1">
      <rect x="453.33333333333337" y="55" width="340" height="140" rx="8" ry="8"/>
    </clipPath>
    <style>
      @keyframes twinkle {
        0%, 100% { opacity: 0.1; }
        50% { opacity: 0.6; }
      }
      @keyframes orbit {
        from { transform: rotate(0deg); }
        to { transform: rotate(360deg); }
      }
      @keyframes card-appear {
        from { opacity: 0; transform: translateY(8px); }
        to { opacity: 1; transform: translateY(0); }
      }
      @keyframes scan-sweep {
        0% { transform: translateY(0); }
        100% { transform: translateY(160px); }
      }
    </style>
  </defs>

  <!-- Background -->
  <rect x="0.5" y="0.5" width="849" height="219" rx="12" ry="12" fill="#0f1623" stroke="#1a2332" stroke-width="1"/>

  <!-- Star field -->
  <circle cx="416.1" cy="72.5" r="0.9" fill="#00d4ff" opacity="0.09"><animate attributeName="opacity" values="0.09;0.26;0.09" dur="5.3s" repeatCount="indefinite"/></circle>
  <circle cx="692.3" cy="171.6" r="0.4" fill="#94a3b8" opacity="0.12"><animate attributeName="opacity" values="0.12;0.36;0.12" dur="7.4s" repeatCount="indefinite"/></circle>
  <circle cx="63.4" cy="16.1" r="0.7" fill="#94a3b8" opacity="0.25"><animate attributeName="opacity" values="0.25;0.60;0.25" dur="7.0s" repeatCount="indefinite"/></circle>
  <circle cx="548.4" cy="129.6" r="0.5" fill="#94a3b8" opacity="0.22"><animate attributeName="opacity" values="0.22;0.60;0.22" dur="7.5s" repeatCount="indefinite"/></circle>
  <circle cx="180.0" cy="103.4" r="0.6" fill="#00d4ff" opacity="0.07"><animate attributeName="opacity" values="0.07;0.22;0.07" dur="7.5s" repeatCount="indefinite"/></circle>
  <circle cx="438.0" cy="16.3" r="0.5" fill="#94a3b8" opacity="0.20"><animate attributeName="opacity" values="0.20;0.59;0.20" dur="6.4s" repeatCount="indefinite"/></circle>
  <circle cx="450.1" cy="60.9" r="0.9" fill="#94a3b8" opacity="0.22"><animate attributeName="opacity" values="0.22;0.60;0.22" dur="6.8s" repeatCount="indefinite"/></circle>
  <circle cx="170.7" cy="110.1" r="0.4" fill="#94a3b8" opacity="0.06"><animate attributeName="opacity" values="0.06;0.19;0.06" dur="7.9s" repeatCount="indefinite"/></circle>
  <circle cx="613.4" cy="38.1" r="0.7" fill="#00d4ff" opacity="0.13"><animate attributeName="opacity" values="0.13;0.39;0.13" dur="6.8s" repeatCount="indefinite"/></circle>
  <circle cx="480.8" cy="157.8" r="0.5" fill="#94a3b8" opacity="0.18"><animate attributeName="opacity" values="0.18;0.55;0.18" dur="7.8s" repeatCount="indefinite"/></circle>
  <circle cx="726.5" cy="194.1" r="0.7" fill="#94a3b8" opacity="0.22"><animate attributeName="opacity" values="0.22;0.60;0.22" dur="6.2s" repeatCount="indefinite"/></circle>
  <circle cx="658.8" cy="95.2" r="0.7" fill="#94a3b8" opacity="0.20"><animate attributeName="opacity" values="0.20;0.60;0.20" dur="7.6s" repeatCount="indefinite"/></circle>
  <circle cx="167.0" cy="54.0" r="0.9" fill="#00d4ff" opacity="0.24"><animate attributeName="opacity" values="0.24;0.60;0.24" dur="7.0s" repeatCount="indefinite"/></circle>
  <circle cx="691.5" cy="70.4" r="0.8" fill="#94a3b8" opacity="0.07"><animate attributeName="opacity" values="0.07;0.22;0.07" dur="5.4s" repeatCount="indefinite"/></circle>
  <circle cx="222.0" cy="150.3" r="0.6" fill="#94a3b8" opacity="0.15"><animate attributeName="opacity" values="0.15;0.45;0.15" dur="7.0s" repeatCount="indefinite"/></circle>
  <circle cx="199.6" cy="139.8" r="0.8" fill="#00d4ff" opacity="0.20"><animate attributeName="opacity" values="0.20;0.50;0.20" dur="4.4s" repeatCount="indefinite"/></circle>
  <circle cx="732.7" cy="192.0" r="1.2" fill="#94a3b8" opacity="0.21"><animate attributeName="opacity" values="0.21;0.52;0.21" dur="3.8s" repeatCount="indefinite"/></circle>
  <circle cx="433.7" cy="146.1" r="1.2" fill="#94a3b8" opacity="0.18"><animate attributeName="opacity" values="0.18;0.45;0.18" dur="4.7s" repeatCount="indefinite"/></circle>
  <circle cx="137.5" cy="81.6" r="1.0" fill="#94a3b8" opacity="0.34"><animate attributeName="opacity" values="0.34;0.80;0.34" dur="5.7s" repeatCount="indefinite"/></circle>
  <circle cx="573.7" cy="178.0" r="1.1" fill="#00d4ff" opacity="0.14"><animate attributeName="opacity" values="0.14;0.36;0.14" dur="3.5s" repeatCount="indefinite"/></circle>
  <circle cx="411.1" cy="172.0" r="1.1" fill="#94a3b8" opacity="0.13"><animate attributeName="opacity" values="0.13;0.32;0.13" dur="4.5s" repeatCount="indefinite"/></circle>
  <circle cx="462.3" cy="81.1" r="1.1" fill="#94a3b8" opacity="0.19"><animate attributeName="opacity" values="0.19;0.48;0.19" dur="4.9s" repeatCount="indefinite"/></circle>
  <circle cx="141.0" cy="77.7" r="1.1" fill="#94a3b8" opacity="0.19"><animate attributeName="opacity" values="0.19;0.48;0.19" dur="5.9s" repeatCount="indefinite"/></circle>
  <circle cx="410.0" cy="92.0" r="0.9" fill="#00d4ff" opacity="0.22"><animate attributeName="opacity" values="0.22;0.56;0.22" dur="5.8s" repeatCount="indefinite"/></circle>
  <circle cx="141.4" cy="87.2" r="0.7" fill="#94a3b8" opacity="0.20"><animate attributeName="opacity" values="0.20;0.49;0.20" dur="3.7s" repeatCount="indefinite"/></circle>

  <!-- Grid overlay -->
  <line x1="12" y1="40" x2="838" y2="40" stroke="#64748b" stroke-width="0.5" stroke-dasharray="4,8" opacity="0.12"/>
  <line x1="12" y1="80" x2="838" y2="80" stroke="#64748b" stroke-width="0.5" stroke-dasharray="4,8" opacity="0.12"/>
  <line x1="12" y1="120" x2="838" y2="120" stroke="#64748b" stroke-width="0.5" stroke-dasharray="4,8" opacity="0.12"/>
  <line x1="12" y1="160" x2="838" y2="160" stroke="#64748b" stroke-width="0.5" stroke-dasharray="4,8" opacity="0.12"/>
  <line x1="12" y1="200" x2="838" y2="200" stroke="#64748b" stroke-width="0.5" stroke-dasharray="4,8" opacity="0.12"/>
  <line x1="80" y1="12" x2="80" y2="208" stroke="#64748b" stroke-width="0.5" stroke-dasharray="4,8" opacity="0.08"/>
  <line x1="160" y1="12" x2="160" y2="208" stroke="#64748b" stroke-width="0.5" stroke-dasharray="4,8" opacity="0.08"/>
  <line x1="240" y1="12" x2="240" y2="208" stroke="#64748b" stroke-width="0.5" stroke-dasharray="4,8" opacity="0.08"/>
  <line x1="320" y1="12" x2="320" y2="208" stroke="#64748b" stroke-width="0.5" stroke-dasharray="4,8" opacity="0.08"/>
  <line x1="400" y1="12" x2="400" y2="208" stroke="#64748b" stroke-width="0.5" stroke-dasharray="4,8" opacity="0.08"/>
  <line x1="480" y1="12" x2="480" y2="208" stroke="#64748b" stroke-width="0.5" stroke-dasharray="4,8" opacity="0.08"/>
  <line x1="560" y1="12" x2="560" y2="208" stroke="#64748b" stroke-width="0.5" stroke-dasharray="4,8" opacity="0.08"/>
  <line x1="640" y1="12" x2="640" y2="208" stroke="#64748b" stroke-width="0.5" stroke-dasharray="4,8" opacity="0.08"/>
  <line x1="720" y1="12" x2="720" y2="208" stroke="#64748b" stroke-width="0.5" stroke-dasharray="4,8" opacity="0.08"/>
  <line x1="800" y1="12" x2="800" y2="208" stroke="#64748b" stroke-width="0.5" stroke-dasharray="4,8" opacity="0.08"/>

  <!-- Connection lines -->
  <line x1="226.7" y1="85" x2="623.3" y2="85" stroke="url(#conn-grad)" stroke-width="1" stroke-dasharray="6,4" opacity="0.5"/>

  <!-- Title area -->
  <g opacity="0.4">
    <polyline points="5,21 5,5 21,5" fill="none" stroke="#64748b" stroke-width="1.5"/>
    <polyline points="829,5 845,5 845,21" fill="none" stroke="#64748b" stroke-width="1.5"/>
    <polyline points="5,199 5,215 21,215" fill="none" stroke="#64748b" stroke-width="1.5"/>
    <polyline points="829,215 845,215 845,199" fill="none" stroke="#64748b" stroke-width="1.5"/>
  </g>
  <text x="30" y="38" fill="#64748b" font-size="11" font-family="monospace" letter-spacing="3">FEATURED SYSTEMS</text>
  <circle cx="218" cy="34" r="3" fill="#00d4ff" opacity="0.8"><animate attributeName="opacity" values="0.4;1;0.4" dur="2s" repeatCount="indefinite"/></circle>
  <text x="820" y="38" fill="#64748b" font-size="10" font-family="monospace" text-anchor="end" opacity="0.5">SYS 2/2 ONLINE</text>

  <!-- Project cards -->
  <g opacity="0" style="animation: card-appear 0.6s ease 0.0s forwards">
    <rect x="56.666666666666664" y="55" width="340" height="140" rx="8" ry="8" fill="url(#card-bg-0)" stroke="#1a2332" stroke-width="1"/>
    <g clip-path="url(#card-clip-0)">
      <circle cx="158.66666666666666" cy="90" r="50" fill="#00d4ff" opacity="0.025" filter="url(#card-nebula)"/>
      <circle cx="294.66666666666663" cy="150" r="40" fill="#00d4ff" opacity="0.03" filter="url(#card-nebula)"/>
      <rect x="56.666666666666664" y="55" width="340" height="2" fill="#00d4ff" opacity="0.1"><animateTransform attributeName="transform" type="translate" from="0 0" to="0 140" dur="6s" repeatCount="indefinite"/></rect>
    </g>
    <circle cx="226.66666666666666" cy="85" r="14" fill="none" stroke="#00d4ff" stroke-width="0.8" stroke-dasharray="4,3" opacity="0.5"><animateTransform attributeName="transform" type="rotate" from="0 226.66666666666666 85" to="360 226.66666666666666 85" dur="12s" repeatCount="indefinite"/></circle>
    <circle cx="226.66666666666666" cy="85" r="8" fill="#00d4ff" opacity="0.15" filter="url(#proj-glow-0)"/>
    <circle cx="226.66666666666666" cy="85" r="5" fill="#00d4ff" opacity="0.7"><animate attributeName="opacity" values="0.5;0.9;0.5" dur="3s" begin="0.0s" repeatCount="indefinite"/><animate attributeName="r" values="4.5;5.5;4.5" dur="3s" begin="0.0s" repeatCount="indefinite"/></circle>
    <circle cx="226.66666666666666" cy="85" r="2" fill="#ffffff" opacity="0.9"/>
    <text x="226.66666666666666" y="111" fill="#f1f5f9" font-size="14" font-weight="bold" font-family="sans-serif" text-anchor="middle">nerd-store-enterprise</text>
    <text x="226.66666666666666" y="129" fill="#94a3b8" font-size="11" font-family="sans-serif" text-anchor="middle">Projeto voltado a estudo e práticas de</text>
    <text x="226.66666666666666" y="144" fill="#94a3b8" font-size="11" font-family="sans-serif" text-anchor="middle">padrões de arquitetura de microsserviços.</text>
    <rect x="194.16666666666666" y="163" width="65" height="18" rx="9" ry="9" fill="#00d4ff" opacity="0.12"/>
    <text x="226.66666666666666" y="175" fill="#00d4ff" font-size="9" font-family="monospace" text-anchor="middle" opacity="0.85">Backend</text>
  </g>
  <g opacity="0" style="animation: card-appear 0.6s ease 0.3s forwards">
    <rect x="453.33333333333337" y="55" width="340" height="140" rx="8" ry="8" fill="url(#card-bg-1)" stroke="#1a2332" stroke-width="1"/>
    <g clip-path="url(#card-clip-1)">
      <circle cx="555.3333333333334" cy="90" r="50" fill="#00d4ff" opacity="0.025" filter="url(#card-nebula)"/>
      <circle cx="691.3333333333334" cy="150" r="40" fill="#00d4ff" opacity="0.03" filter="url(#card-nebula)"/>
      <rect x="453.33333333333337" y="55" width="340" height="2" fill="#00d4ff" opacity="0.1"><animateTransform attributeName="transform" type="translate" from="0 0" to="0 140" dur="6s" repeatCount="indefinite"/></rect>
    </g>
    <circle cx="623.3333333333334" cy="85" r="14" fill="none" stroke="#00d4ff" stroke-width="0.8" stroke-dasharray="4,3" opacity="0.5"><animateTransform attributeName="transform" type="rotate" from="0 623.3333333333334 85" to="360 623.3333333333334 85" dur="12s" repeatCount="indefinite"/></circle>
    <circle cx="623.3333333333334" cy="85" r="8" fill="#00d4ff" opacity="0.15" filter="url(#proj-glow-1)"/>
    <circle cx="623.3333333333334" cy="85" r="5" fill="#00d4ff" opacity="0.7"><animate attributeName="opacity" values="0.5;0.9;0.5" dur="3s" begin="0.3s" repeatCount="indefinite"/><animate attributeName="r" values="4.5;5.5;4.5" dur="3s" begin="0.3s" repeatCount="indefinite"/></circle>
    <circle cx="623.3333333333334" cy="85" r="2" fill="#ffffff" opacity="0.9"/>
    <text x="623.3333333333334" y="111" fill="#f1f5f9" font-size="14" font-weight="bold" font-family="sans-serif" text-anchor="middle">articly</text>
    <text x="623.3333333333334" y="129" fill="#94a3b8" font-size="11" font-family="sans-serif" text-anchor="middle">O Articly é um SaaS para gestão de artigos,</text>
    <text x="623.3333333333334" y="144" fill="#94a3b8" font-size="11" font-family="sans-serif" text-anchor="middle">desenvolvido para facilitar a criação,</text>
    <rect x="590.8333333333334" y="163" width="65" height="18" rx="9" ry="9" fill="#00d4ff" opacity="0.12"/>
    <text x="623.3333333333334" y="175" fill="#00d4ff" font-size="9" font-family="monospace" text-anchor="middle" opacity="0.85">Backend</text>
  </g>

  <!-- Global scan line -->
  <rect x="12" y="50" width="826" height="1.5" fill="#00d4ff" opacity="0.08"><animateTransform attributeName="transform" type="translate" from="0 0" to="0 160" dur="6s" repeatCount="indefinite"/></rect>
</svg>

</div>
  
<h3 align="center">Linguagens e Ferramentas que já utilizei</h3>
 <p align="center">
  <img align="center" height="40" width="40" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/csharp/csharp-original.svg">
  <img align="center" height="40" width="40" src="https://raw.githubusercontent.com/devicons/devicon/refs/heads/master/icons/dotnetcore/dotnetcore-original.svg">

  <img align="center" height="40" width="40" src="https://raw.githubusercontent.com/devicons/devicon/refs/heads/master/icons/dbeaver/dbeaver-original.svg">
  <img align="center" height="40" width="40" src="https://raw.githubusercontent.com/devicons/devicon/refs/heads/master/icons/postgresql/postgresql-original.svg">
  <img align="center" width="40" height="40" src="https://raw.githubusercontent.com/devicons/devicon/refs/heads/master/icons/microsoftsqlserver/microsoftsqlserver-original.svg" /> 
  <img align="center" width="40" height="40" src="https://raw.githubusercontent.com/devicons/devicon/refs/heads/master/icons/mongodb/mongodb-original.svg" /> 

  <img align="center" height="40" width="40" src="https://raw.githubusercontent.com/devicons/devicon/refs/heads/master/icons/docker/docker-original.svg">
  <img align="center" height="40" width="40" src="https://raw.githubusercontent.com/devicons/devicon/refs/heads/master/icons/kubernetes/kubernetes-original.svg">
  
  <img align="center" height="40" width="40" src="https://raw.githubusercontent.com/devicons/devicon/refs/heads/master/icons/grafana/grafana-original.svg">
  <img align="center" height="40" width="40" src="https://raw.githubusercontent.com/devicons/devicon/refs/heads/master/icons/prometheus/prometheus-original.svg">
  
  <img align="center" height="40" width="40" src="https://raw.githubusercontent.com/devicons/devicon/refs/heads/master/icons/vscode/vscode-original.svg">
  <img align="center" height="40" width="40" src="https://raw.githubusercontent.com/devicons/devicon/refs/heads/master/icons/rider/rider-original.svg">
  <img align="center" height="40" width="40" src="https://raw.githubusercontent.com/devicons/devicon/refs/heads/master/icons/visualstudio/visualstudio-original.svg">

  
  <img align="center" height="40" width="40" src="https://raw.githubusercontent.com/devicons/devicon/refs/heads/master/icons/selenium/selenium-original.svg">
  <img align="center" height="40" width="40" src="https://raw.githubusercontent.com/devicons/devicon/refs/heads/master/icons/postman/postman-original.svg">

  <img align="center" height="40" width="40" src="https://raw.githubusercontent.com/devicons/devicon/refs/heads/master/icons/rabbitmq/rabbitmq-original.svg">
  <img align="center" height="40" width="40" src="https://raw.githubusercontent.com/devicons/devicon/refs/heads/master/icons/apachekafka/apachekafka-original.svg">  

  <img align="center" height="40" width="40" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/javascript/javascript-plain.svg">
  <img align="center" height="40" width="40" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/typescript/typescript-plain.svg">
  <img align="center" height="40" width="40" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/html5/html5-original.svg">
  <img align="center" height="40" width="40" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/css3/css3-original.svg">
  <img align="center" height="40" width="40" src="https://raw.githubusercontent.com/devicons/devicon/refs/heads/master/icons/vuejs/vuejs-original.svg">

  <img align="center" height="40" width="40" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/linux/linux-original.svg">
  <img align="center" width="40" height="40" src="https://raw.githubusercontent.com/devicons/devicon/refs/heads/master/icons/git/git-original.svg" />
  <img align="center" width="40" height="40" src="https://raw.githubusercontent.com/devicons/devicon/refs/heads/master/icons/github/github-original.svg" />
  <img align="center" width="40" height="40" src="https://raw.githubusercontent.com/devicons/devicon/refs/heads/master/icons/githubactions/githubactions-original.svg" />
  
  <img align="center" height="40" width="40" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg">
</p>
  
  ##
  
<div align="center">
  <a href = "mailto:willianbrito05@gmail.com"><img src="https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white" target="_blank"></a>
  <a href="https://www.linkedin.com/in/willian-ferreira-brito" target="_blank"><img src="https://img.shields.io/badge/-LinkedIn-%230077B5?style=for-the-badge&logo=linkedin&logoColor=white" target="_blank"></a> 
  <a href = "mailto:willian_brito00@gmail.com"><img src="https://img.shields.io/badge/-Hotmail-D3D3D3?style=for-the-badge&logo=microsoft-outlook&logoColor=0078d4" target="_blank"></a>
  
![Snake animation](https://github.com/Willian-Brito/Willian-Brito/blob/output/github-contribution-grid-snake.svg)

</div>
