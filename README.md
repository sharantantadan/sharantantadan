<svg xmlns="http://www.w3.org/2000/svg" width="900" height="220" viewBox="0 0 900 220">
  <defs>
    <style>
      @import url('https://fonts.googleapis.com/css2?family=Share+Tech+Mono&amp;display=swap');
      
      .matrix-char { 
        font-family: 'Share Tech Mono', 'Courier New', monospace;
        font-size: 14px;
        fill: #00aa00;
      }
      .matrix-char-bright { 
        font-family: 'Share Tech Mono', 'Courier New', monospace;
        font-size: 14px;
        fill: #39FF14;
      }
      .matrix-char-dim { 
        font-family: 'Share Tech Mono', 'Courier New', monospace;
        font-size: 14px;
        fill: #004400;
      }
      .name-text {
        font-family: 'Share Tech Mono', 'Courier New', monospace;
        font-size: 52px;
        font-weight: bold;
        fill: #000000;
        letter-spacing: 3px;
      }
      .name-glow {
        font-family: 'Share Tech Mono', 'Courier New', monospace;
        font-size: 52px;
        font-weight: bold;
        fill: #39FF14;
        letter-spacing: 3px;
      }

      /* Column animations - each column falls at different speed/delay */
      .col0 { animation: fall0 2.1s linear infinite; }
      .col1 { animation: fall1 1.8s linear infinite; }
      .col2 { animation: fall2 2.4s linear infinite; }
      .col3 { animation: fall3 1.6s linear infinite; }
      .col4 { animation: fall4 2.8s linear infinite; }
      .col5 { animation: fall5 2.0s linear infinite; }
      .col6 { animation: fall6 1.5s linear infinite; }
      .col7 { animation: fall7 2.2s linear infinite; }
      .col8 { animation: fall8 1.9s linear infinite; }
      .col9 { animation: fall9 2.6s linear infinite; }
      .col10 { animation: fall10 1.7s linear infinite; }
      .col11 { animation: fall11 2.3s linear infinite; }
      .col12 { animation: fall12 1.4s linear infinite; }
      .col13 { animation: fall13 2.5s linear infinite; }
      .col14 { animation: fall14 1.8s linear infinite; }
      .col15 { animation: fall15 2.1s linear infinite; }
      .col16 { animation: fall16 1.6s linear infinite; }
      .col17 { animation: fall17 2.7s linear infinite; }
      .col18 { animation: fall18 2.0s linear infinite; }
      .col19 { animation: fall19 1.5s linear infinite; }
      .col20 { animation: fall20 2.3s linear infinite; }
      .col21 { animation: fall21 1.9s linear infinite; }
      .col22 { animation: fall22 2.6s linear infinite; }
      .col23 { animation: fall23 1.7s linear infinite; }
      .col24 { animation: fall24 2.4s linear infinite; }
      .col25 { animation: fall25 1.3s linear infinite; }
      .col26 { animation: fall26 2.8s linear infinite; }
      .col27 { animation: fall27 2.0s linear infinite; }
      .col28 { animation: fall28 1.6s linear infinite; }
      .col29 { animation: fall29 2.2s linear infinite; }
      .col30 { animation: fall30 1.8s linear infinite; }
      .col31 { animation: fall31 2.5s linear infinite; }
      .col32 { animation: fall32 1.4s linear infinite; }
      .col33 { animation: fall33 2.1s linear infinite; }
      .col34 { animation: fall34 1.9s linear infinite; }
      .col35 { animation: fall35 2.7s linear infinite; }
      .col36 { animation: fall36 1.5s linear infinite; }
      .col37 { animation: fall37 2.3s linear infinite; }
      .col38 { animation: fall38 1.7s linear infinite; }
      .col39 { animation: fall39 2.0s linear infinite; }
      .col40 { animation: fall40 2.4s linear infinite; }
      .col41 { animation: fall41 1.6s linear infinite; }
      .col42 { animation: fall42 2.8s linear infinite; }
      .col43 { animation: fall43 1.3s linear infinite; }
      .col44 { animation: fall44 2.1s linear infinite; }
      .col45 { animation: fall45 1.9s linear infinite; }
      .col46 { animation: fall46 2.5s linear infinite; }
      .col47 { animation: fall47 1.8s linear infinite; }
      .col48 { animation: fall48 2.2s linear infinite; }
      .col49 { animation: fall49 1.4s linear infinite; }
      .col50 { animation: fall50 2.6s linear infinite; }
      .col51 { animation: fall51 1.7s linear infinite; }
      .col52 { animation: fall52 2.0s linear infinite; }
      .col53 { animation: fall53 1.5s linear infinite; }
      .col54 { animation: fall54 2.3s linear infinite; }
      .col55 { animation: fall55 1.8s linear infinite; }
      .col56 { animation: fall56 2.7s linear infinite; }
      .col57 { animation: fall57 1.6s linear infinite; }
      .col58 { animation: fall58 2.4s linear infinite; }
      .col59 { animation: fall59 1.9s linear infinite; }

      @keyframes fall0  { 0%{transform:translateY(-220px)} 100%{transform:translateY(220px)} }
      @keyframes fall1  { 0%{transform:translateY(-220px)} 100%{transform:translateY(220px)} }
      @keyframes fall2  { 0%{transform:translateY(-220px)} 100%{transform:translateY(220px)} }
      @keyframes fall3  { 0%{transform:translateY(-220px)} 100%{transform:translateY(220px)} }
      @keyframes fall4  { 0%{transform:translateY(-220px)} 100%{transform:translateY(220px)} }
      @keyframes fall5  { 0%{transform:translateY(-220px)} 100%{transform:translateY(220px)} }
      @keyframes fall6  { 0%{transform:translateY(-220px)} 100%{transform:translateY(220px)} }
      @keyframes fall7  { 0%{transform:translateY(-220px)} 100%{transform:translateY(220px)} }
      @keyframes fall8  { 0%{transform:translateY(-220px)} 100%{transform:translateY(220px)} }
      @keyframes fall9  { 0%{transform:translateY(-220px)} 100%{transform:translateY(220px)} }
      @keyframes fall10 { 0%{transform:translateY(-220px)} 100%{transform:translateY(220px)} }
      @keyframes fall11 { 0%{transform:translateY(-220px)} 100%{transform:translateY(220px)} }
      @keyframes fall12 { 0%{transform:translateY(-220px)} 100%{transform:translateY(220px)} }
      @keyframes fall13 { 0%{transform:translateY(-220px)} 100%{transform:translateY(220px)} }
      @keyframes fall14 { 0%{transform:translateY(-220px)} 100%{transform:translateY(220px)} }
      @keyframes fall15 { 0%{transform:translateY(-220px)} 100%{transform:translateY(220px)} }
      @keyframes fall16 { 0%{transform:translateY(-220px)} 100%{transform:translateY(220px)} }
      @keyframes fall17 { 0%{transform:translateY(-220px)} 100%{transform:translateY(220px)} }
      @keyframes fall18 { 0%{transform:translateY(-220px)} 100%{transform:translateY(220px)} }
      @keyframes fall19 { 0%{transform:translateY(-220px)} 100%{transform:translateY(220px)} }
      @keyframes fall20 { 0%{transform:translateY(-220px)} 100%{transform:translateY(220px)} }
      @keyframes fall21 { 0%{transform:translateY(-220px)} 100%{transform:translateY(220px)} }
      @keyframes fall22 { 0%{transform:translateY(-220px)} 100%{transform:translateY(220px)} }
      @keyframes fall23 { 0%{transform:translateY(-220px)} 100%{transform:translateY(220px)} }
      @keyframes fall24 { 0%{transform:translateY(-220px)} 100%{transform:translateY(220px)} }
      @keyframes fall25 { 0%{transform:translateY(-220px)} 100%{transform:translateY(220px)} }
      @keyframes fall26 { 0%{transform:translateY(-220px)} 100%{transform:translateY(220px)} }
      @keyframes fall27 { 0%{transform:translateY(-220px)} 100%{transform:translateY(220px)} }
      @keyframes fall28 { 0%{transform:translateY(-220px)} 100%{transform:translateY(220px)} }
      @keyframes fall29 { 0%{transform:translateY(-220px)} 100%{transform:translateY(220px)} }
      @keyframes fall30 { 0%{transform:translateY(-220px)} 100%{transform:translateY(220px)} }
      @keyframes fall31 { 0%{transform:translateY(-220px)} 100%{transform:translateY(220px)} }
      @keyframes fall32 { 0%{transform:translateY(-220px)} 100%{transform:translateY(220px)} }
      @keyframes fall33 { 0%{transform:translateY(-220px)} 100%{transform:translateY(220px)} }
      @keyframes fall34 { 0%{transform:translateY(-220px)} 100%{transform:translateY(220px)} }
      @keyframes fall35 { 0%{transform:translateY(-220px)} 100%{transform:translateY(220px)} }
      @keyframes fall36 { 0%{transform:translateY(-220px)} 100%{transform:translateY(220px)} }
      @keyframes fall37 { 0%{transform:translateY(-220px)} 100%{transform:translateY(220px)} }
      @keyframes fall38 { 0%{transform:translateY(-220px)} 100%{transform:translateY(220px)} }
      @keyframes fall39 { 0%{transform:translateY(-220px)} 100%{transform:translateY(220px)} }
      @keyframes fall40 { 0%{transform:translateY(-220px)} 100%{transform:translateY(220px)} }
      @keyframes fall41 { 0%{transform:translateY(-220px)} 100%{transform:translateY(220px)} }
      @keyframes fall42 { 0%{transform:translateY(-220px)} 100%{transform:translateY(220px)} }
      @keyframes fall43 { 0%{transform:translateY(-220px)} 100%{transform:translateY(220px)} }
      @keyframes fall44 { 0%{transform:translateY(-220px)} 100%{transform:translateY(220px)} }
      @keyframes fall45 { 0%{transform:translateY(-220px)} 100%{transform:translateY(220px)} }
      @keyframes fall46 { 0%{transform:translateY(-220px)} 100%{transform:translateY(220px)} }
      @keyframes fall47 { 0%{transform:translateY(-220px)} 100%{transform:translateY(220px)} }
      @keyframes fall48 { 0%{transform:translateY(-220px)} 100%{transform:translateY(220px)} }
      @keyframes fall49 { 0%{transform:translateY(-220px)} 100%{transform:translateY(220px)} }
      @keyframes fall50 { 0%{transform:translateY(-220px)} 100%{transform:translateY(220px)} }
      @keyframes fall51 { 0%{transform:translateY(-220px)} 100%{transform:translateY(220px)} }
      @keyframes fall52 { 0%{transform:translateY(-220px)} 100%{transform:translateY(220px)} }
      @keyframes fall53 { 0%{transform:translateY(-220px)} 100%{transform:translateY(220px)} }
      @keyframes fall54 { 0%{transform:translateY(-220px)} 100%{transform:translateY(220px)} }
      @keyframes fall55 { 0%{transform:translateY(-220px)} 100%{transform:translateY(220px)} }
      @keyframes fall56 { 0%{transform:translateY(-220px)} 100%{transform:translateY(220px)} }
      @keyframes fall57 { 0%{transform:translateY(-220px)} 100%{transform:translateY(220px)} }
      @keyframes fall58 { 0%{transform:translateY(-220px)} 100%{transform:translateY(220px)} }
      @keyframes fall59 { 0%{transform:translateY(-220px)} 100%{transform:translateY(220px)} }

      .name-pulse {
        animation: namePulse 3s ease-in-out infinite;
      }
      @keyframes namePulse {
        0%, 100% { opacity: 1; filter: drop-shadow(0 0 8px #39FF14) drop-shadow(0 0 20px #39FF14); }
        50% { opacity: 0.85; filter: drop-shadow(0 0 20px #39FF14) drop-shadow(0 0 40px #00ff00) drop-shadow(0 0 60px #39FF14); }
      }
    </style>

    <filter id="glow">
      <feGaussianBlur stdDeviation="2" result="coloredBlur"/>
      <feMerge><feMergeNode in="coloredBlur"/><feMergeNode in="SourceGraphic"/></feMerge>
    </filter>
    <filter id="strongGlow">
      <feGaussianBlur stdDeviation="4" result="coloredBlur"/>
      <feMerge><feMergeNode in="coloredBlur"/><feMergeNode in="coloredBlur"/><feMergeNode in="SourceGraphic"/></feMerge>
    </filter>
    <filter id="nameGlow">
      <feGaussianBlur stdDeviation="6" result="coloredBlur"/>
      <feMerge><feMergeNode in="coloredBlur"/><feMergeNode in="coloredBlur"/><feMergeNode in="SourceGraphic"/></feMerge>
    </filter>

    <clipPath id="bannerClip">
      <rect width="900" height="220"/>
    </clipPath>
  </defs>

  <!-- Background -->
  <rect width="900" height="220" fill="#000000"/>

  <!-- Matrix rain columns clipped to banner -->
  <g clip-path="url(#bannerClip)">

    <!-- Col 0 x=5 -->
    <g class="col0" style="animation-delay:-0.3s">
      <text x="5"   y="20"  class="matrix-char-bright" filter="url(#glow)">ア</text>
      <text x="5"   y="36"  class="matrix-char">ナ</text>
      <text x="5"   y="52"  class="matrix-char">1</text>
      <text x="5"   y="68"  class="matrix-char-dim">カ</text>
      <text x="5"   y="84"  class="matrix-char-dim">0</text>
      <text x="5"   y="100" class="matrix-char">タ</text>
      <text x="5"   y="116" class="matrix-char">ラ</text>
      <text x="5"   y="132" class="matrix-char-dim">サ</text>
      <text x="5"   y="148" class="matrix-char">マ</text>
      <text x="5"   y="164" class="matrix-char-bright" filter="url(#glow)">ハ</text>
      <text x="5"   y="180" class="matrix-char">ヤ</text>
      <text x="5"   y="196" class="matrix-char-dim">ワ</text>
      <text x="5"   y="212" class="matrix-char">Z</text>
    </g>

    <!-- Col 1 x=20 -->
    <g class="col1" style="animation-delay:-1.1s">
      <text x="20"  y="20"  class="matrix-char">7</text>
      <text x="20"  y="36"  class="matrix-char-bright" filter="url(#glow)">イ</text>
      <text x="20"  y="52"  class="matrix-char">ウ</text>
      <text x="20"  y="68"  class="matrix-char-dim">エ</text>
      <text x="20"  y="84"  class="matrix-char">オ</text>
      <text x="20"  y="100" class="matrix-char-dim">3</text>
      <text x="20"  y="116" class="matrix-char">キ</text>
      <text x="20"  y="132" class="matrix-char">ク</text>
      <text x="20"  y="148" class="matrix-char-bright" filter="url(#glow)">ケ</text>
      <text x="20"  y="164" class="matrix-char-dim">コ</text>
      <text x="20"  y="180" class="matrix-char">9</text>
      <text x="20"  y="196" class="matrix-char">シ</text>
      <text x="20"  y="212" class="matrix-char-dim">ス</text>
    </g>

    <!-- Col 2 x=35 -->
    <g class="col2" style="animation-delay:-0.7s">
      <text x="35"  y="20"  class="matrix-char-dim">セ</text>
      <text x="35"  y="36"  class="matrix-char">ソ</text>
      <text x="35"  y="52"  class="matrix-char-bright" filter="url(#glow)">チ</text>
      <text x="35"  y="68"  class="matrix-char">ツ</text>
      <text x="35"  y="84"  class="matrix-char">テ</text>
      <text x="35"  y="100" class="matrix-char-dim">ト</text>
      <text x="35"  y="116" class="matrix-char">5</text>
      <text x="35"  y="132" class="matrix-char">ニ</text>
      <text x="35"  y="148" class="matrix-char-dim">ヌ</text>
      <text x="35"  y="164" class="matrix-char">ネ</text>
      <text x="35"  y="180" class="matrix-char-bright" filter="url(#glow)">ノ</text>
      <text x="35"  y="196" class="matrix-char">8</text>
      <text x="35"  y="212" class="matrix-char-dim">ヒ</text>
    </g>

    <!-- Col 3 x=50 -->
    <g class="col3" style="animation-delay:-1.5s">
      <text x="50"  y="20"  class="matrix-char">フ</text>
      <text x="50"  y="36"  class="matrix-char-dim">ヘ</text>
      <text x="50"  y="52"  class="matrix-char">ホ</text>
      <text x="50"  y="68"  class="matrix-char-bright" filter="url(#glow)">2</text>
      <text x="50"  y="84"  class="matrix-char">ミ</text>
      <text x="50"  y="100" class="matrix-char">ム</text>
      <text x="50"  y="116" class="matrix-char-dim">メ</text>
      <text x="50"  y="132" class="matrix-char">モ</text>
      <text x="50"  y="148" class="matrix-char">4</text>
      <text x="50"  y="164" class="matrix-char-dim">ユ</text>
      <text x="50"  y="180" class="matrix-char">ヨ</text>
      <text x="50"  y="196" class="matrix-char-bright" filter="url(#glow)">リ</text>
      <text x="50"  y="212" class="matrix-char">ル</text>
    </g>

    <!-- Col 4 x=65 -->
    <g class="col4" style="animation-delay:-0.5s">
      <text x="65"  y="20"  class="matrix-char-dim">レ</text>
      <text x="65"  y="36"  class="matrix-char">ロ</text>
      <text x="65"  y="52"  class="matrix-char">6</text>
      <text x="65"  y="68"  class="matrix-char-dim">ヲ</text>
      <text x="65"  y="84"  class="matrix-char-bright" filter="url(#glow)">ン</text>
      <text x="65"  y="100" class="matrix-char">ア</text>
      <text x="65"  y="116" class="matrix-char">0</text>
      <text x="65"  y="132" class="matrix-char-dim">イ</text>
      <text x="65"  y="148" class="matrix-char">ウ</text>
      <text x="65"  y="164" class="matrix-char">1</text>
      <text x="65"  y="180" class="matrix-char-dim">エ</text>
      <text x="65"  y="196" class="matrix-char">オ</text>
      <text x="65"  y="212" class="matrix-char-bright" filter="url(#glow)">カ</text>
    </g>

    <!-- Col 5 x=80 -->
    <g class="col5" style="animation-delay:-1.8s">
      <text x="80"  y="20"  class="matrix-char">キ</text>
      <text x="80"  y="36"  class="matrix-char-bright" filter="url(#glow)">ク</text>
      <text x="80"  y="52"  class="matrix-char-dim">ケ</text>
      <text x="80"  y="68"  class="matrix-char">コ</text>
      <text x="80"  y="84"  class="matrix-char">7</text>
      <text x="80"  y="100" class="matrix-char-dim">サ</text>
      <text x="80"  y="116" class="matrix-char">シ</text>
      <text x="80"  y="132" class="matrix-char-bright" filter="url(#glow)">ス</text>
      <text x="80"  y="148" class="matrix-char">セ</text>
      <text x="80"  y="164" class="matrix-char-dim">ソ</text>
      <text x="80"  y="180" class="matrix-char">3</text>
      <text x="80"  y="196" class="matrix-char">チ</text>
      <text x="80"  y="212" class="matrix-char-dim">ツ</text>
    </g>

    <!-- Col 6 x=95 -->
    <g class="col6" style="animation-delay:-0.2s">
      <text x="95"  y="20"  class="matrix-char-bright" filter="url(#glow)">テ</text>
      <text x="95"  y="36"  class="matrix-char-dim">ト</text>
      <text x="95"  y="52"  class="matrix-char">ナ</text>
      <text x="95"  y="68"  class="matrix-char">ニ</text>
      <text x="95"  y="84"  class="matrix-char-dim">ヌ</text>
      <text x="95"  y="100" class="matrix-char">9</text>
      <text x="95"  y="116" class="matrix-char">ネ</text>
      <text x="95"  y="132" class="matrix-char-dim">ノ</text>
      <text x="95"  y="148" class="matrix-char-bright" filter="url(#glow)">ハ</text>
      <text x="95"  y="164" class="matrix-char">ヒ</text>
      <text x="95"  y="180" class="matrix-char">5</text>
      <text x="95"  y="196" class="matrix-char-dim">フ</text>
      <text x="95"  y="212" class="matrix-char">ヘ</text>
    </g>

    <!-- Col 7 x=110 -->
    <g class="col7" style="animation-delay:-1.3s">
      <text x="110" y="20"  class="matrix-char-dim">ホ</text>
      <text x="110" y="36"  class="matrix-char">マ</text>
      <text x="110" y="52"  class="matrix-char-bright" filter="url(#glow)">ミ</text>
      <text x="110" y="68"  class="matrix-char">ム</text>
      <text x="110" y="84"  class="matrix-char-dim">メ</text>
      <text x="110" y="100" class="matrix-char">2</text>
      <text x="110" y="116" class="matrix-char">モ</text>
      <text x="110" y="132" class="matrix-char-dim">ヤ</text>
      <text x="110" y="148" class="matrix-char">ユ</text>
      <text x="110" y="164" class="matrix-char-bright" filter="url(#glow)">ヨ</text>
      <text x="110" y="180" class="matrix-char-dim">リ</text>
      <text x="110" y="196" class="matrix-char">8</text>
      <text x="110" y="212" class="matrix-char">ル</text>
    </g>

    <!-- Col 8 x=125 -->
    <g class="col8" style="animation-delay:-0.9s">
      <text x="125" y="20"  class="matrix-char">レ</text>
      <text x="125" y="36"  class="matrix-char-dim">ロ</text>
      <text x="125" y="52"  class="matrix-char">ワ</text>
      <text x="125" y="68"  class="matrix-char-bright" filter="url(#glow)">ヲ</text>
      <text x="125" y="84"  class="matrix-char">ン</text>
      <text x="125" y="100" class="matrix-char-dim">4</text>
      <text x="125" y="116" class="matrix-char">ア</text>
      <text x="125" y="132" class="matrix-char">イ</text>
      <text x="125" y="148" class="matrix-char-dim">ウ</text>
      <text x="125" y="164" class="matrix-char">エ</text>
      <text x="125" y="180" class="matrix-char-bright" filter="url(#glow)">1</text>
      <text x="125" y="196" class="matrix-char-dim">オ</text>
      <text x="125" y="212" class="matrix-char">カ</text>
    </g>

    <!-- Col 9 x=140 -->
    <g class="col9" style="animation-delay:-1.6s">
      <text x="140" y="20"  class="matrix-char-dim">キ</text>
      <text x="140" y="36"  class="matrix-char">6</text>
      <text x="140" y="52"  class="matrix-char-dim">ク</text>
      <text x="140" y="68"  class="matrix-char">ケ</text>
      <text x="140" y="84"  class="matrix-char-bright" filter="url(#glow)">コ</text>
      <text x="140" y="100" class="matrix-char">サ</text>
      <text x="140" y="116" class="matrix-char-dim">シ</text>
      <text x="140" y="132" class="matrix-char">0</text>
      <text x="140" y="148" class="matrix-char">ス</text>
      <text x="140" y="164" class="matrix-char-dim">セ</text>
      <text x="140" y="180" class="matrix-char">ソ</text>
      <text x="140" y="196" class="matrix-char-bright" filter="url(#glow)">チ</text>
      <text x="140" y="212" class="matrix-char-dim">ツ</text>
    </g>

    <!-- Col 10 x=155 -->
    <g class="col10" style="animation-delay:-0.4s">
      <text x="155" y="20"  class="matrix-char">テ</text>
      <text x="155" y="36"  class="matrix-char-bright" filter="url(#glow)">3</text>
      <text x="155" y="52"  class="matrix-char">ナ</text>
      <text x="155" y="68"  class="matrix-char-dim">ニ</text>
      <text x="155" y="84"  class="matrix-char">ヌ</text>
      <text x="155" y="100" class="matrix-char">ネ</text>
      <text x="155" y="116" class="matrix-char-dim">7</text>
      <text x="155" y="132" class="matrix-char-bright" filter="url(#glow)">ノ</text>
      <text x="155" y="148" class="matrix-char">ハ</text>
      <text x="155" y="164" class="matrix-char-dim">ヒ</text>
      <text x="155" y="180" class="matrix-char">フ</text>
      <text x="155" y="196" class="matrix-char">ヘ</text>
      <text x="155" y="212" class="matrix-char-dim">ホ</text>
    </g>

    <!-- Col 11 x=170 -->
    <g class="col11" style="animation-delay:-1.0s">
      <text x="170" y="20"  class="matrix-char-dim">マ</text>
      <text x="170" y="36"  class="matrix-char">ミ</text>
      <text x="170" y="52"  class="matrix-char-dim">5</text>
      <text x="170" y="68"  class="matrix-char-bright" filter="url(#glow)">ム</text>
      <text x="170" y="84"  class="matrix-char">メ</text>
      <text x="170" y="100" class="matrix-char">モ</text>
      <text x="170" y="116" class="matrix-char-dim">ヤ</text>
      <text x="170" y="132" class="matrix-char">ユ</text>
      <text x="170" y="148" class="matrix-char-bright" filter="url(#glow)">ヨ</text>
      <text x="170" y="164" class="matrix-char">9</text>
      <text x="170" y="180" class="matrix-char-dim">リ</text>
      <text x="170" y="196" class="matrix-char">ル</text>
      <text x="170" y="212" class="matrix-char">レ</text>
    </g>

    <!-- Col 12 x=185 -->
    <g class="col12" style="animation-delay:-1.7s">
      <text x="185" y="20"  class="matrix-char-bright" filter="url(#glow)">ロ</text>
      <text x="185" y="36"  class="matrix-char-dim">ワ</text>
      <text x="185" y="52"  class="matrix-char">ヲ</text>
      <text x="185" y="68"  class="matrix-char">2</text>
      <text x="185" y="84"  class="matrix-char-dim">ン</text>
      <text x="185" y="100" class="matrix-char">ア</text>
      <text x="185" y="116" class="matrix-char-bright" filter="url(#glow)">イ</text>
      <text x="185" y="132" class="matrix-char">ウ</text>
      <text x="185" y="148" class="matrix-char-dim">エ</text>
      <text x="185" y="164" class="matrix-char">8</text>
      <text x="185" y="180" class="matrix-char">オ</text>
      <text x="185" y="196" class="matrix-char-dim">カ</text>
      <text x="185" y="212" class="matrix-char-bright" filter="url(#glow)">キ</text>
    </g>

    <!-- Col 13 x=200 -->
    <g class="col13" style="animation-delay:-0.6s">
      <text x="200" y="20"  class="matrix-char">ク</text>
      <text x="200" y="36"  class="matrix-char">ケ</text>
      <text x="200" y="52"  class="matrix-char-dim">コ</text>
      <text x="200" y="68"  class="matrix-char-bright" filter="url(#glow)">1</text>
      <text x="200" y="84"  class="matrix-char">サ</text>
      <text x="200" y="100" class="matrix-char-dim">シ</text>
      <text x="200" y="116" class="matrix-char">ス</text>
      <text x="200" y="132" class="matrix-char">セ</text>
      <text x="200" y="148" class="matrix-char-dim">4</text>
      <text x="200" y="164" class="matrix-char-bright" filter="url(#glow)">ソ</text>
      <text x="200" y="180" class="matrix-char">チ</text>
      <text x="200" y="196" class="matrix-char">ツ</text>
      <text x="200" y="212" class="matrix-char-dim">テ</text>
    </g>

    <!-- Col 14 x=215 -->
    <g class="col14" style="animation-delay:-1.4s">
      <text x="215" y="20"  class="matrix-char-dim">ト</text>
      <text x="215" y="36"  class="matrix-char-bright" filter="url(#glow)">ナ</text>
      <text x="215" y="52"  class="matrix-char">ニ</text>
      <text x="215" y="68"  class="matrix-char-dim">6</text>
      <text x="215" y="84"  class="matrix-char">ヌ</text>
      <text x="215" y="100" class="matrix-char">ネ</text>
      <text x="215" y="116" class="matrix-char-bright" filter="url(#glow)">ノ</text>
      <text x="215" y="132" class="matrix-char-dim">ハ</text>
      <text x="215" y="148" class="matrix-char">ヒ</text>
      <text x="215" y="164" class="matrix-char">0</text>
      <text x="215" y="180" class="matrix-char-dim">フ</text>
      <text x="215" y="196" class="matrix-char-bright" filter="url(#glow)">ヘ</text>
      <text x="215" y="212" class="matrix-char">ホ</text>
    </g>

    <!-- Cols 15-59: abbreviated but still animated -->
    <g class="col15" style="animation-delay:-0.8s">
      <text x="230" y="20"  class="matrix-char-dim">マ</text><text x="230" y="36"  class="matrix-char">3</text><text x="230" y="52"  class="matrix-char-bright" filter="url(#glow)">ミ</text><text x="230" y="68"  class="matrix-char-dim">ム</text><text x="230" y="84"  class="matrix-char">メ</text><text x="230" y="100" class="matrix-char">モ</text><text x="230" y="116" class="matrix-char-dim">7</text><text x="230" y="132" class="matrix-char-bright" filter="url(#glow)">ヤ</text><text x="230" y="148" class="matrix-char">ユ</text><text x="230" y="164" class="matrix-char-dim">ヨ</text><text x="230" y="180" class="matrix-char">リ</text><text x="230" y="196" class="matrix-char">9</text><text x="230" y="212" class="matrix-char-dim">ル</text>
    </g>
    <g class="col16" style="animation-delay:-1.9s">
      <text x="245" y="20"  class="matrix-char-bright" filter="url(#glow)">レ</text><text x="245" y="36"  class="matrix-char-dim">ロ</text><text x="245" y="52"  class="matrix-char">ワ</text><text x="245" y="68"  class="matrix-char">5</text><text x="245" y="84"  class="matrix-char-dim">ヲ</text><text x="245" y="100" class="matrix-char">ン</text><text x="245" y="116" class="matrix-char-bright" filter="url(#glow)">ア</text><text x="245" y="132" class="matrix-char">イ</text><text x="245" y="148" class="matrix-char-dim">ウ</text><text x="245" y="164" class="matrix-char">2</text><text x="245" y="180" class="matrix-char">エ</text><text x="245" y="196" class="matrix-char-dim">オ</text><text x="245" y="212" class="matrix-char-bright" filter="url(#glow)">カ</text>
    </g>
    <g class="col17" style="animation-delay:-0.1s">
      <text x="260" y="20"  class="matrix-char">キ</text><text x="260" y="36"  class="matrix-char">ク</text><text x="260" y="52"  class="matrix-char-dim">ケ</text><text x="260" y="68"  class="matrix-char-bright" filter="url(#glow)">コ</text><text x="260" y="84"  class="matrix-char">8</text><text x="260" y="100" class="matrix-char-dim">サ</text><text x="260" y="116" class="matrix-char">シ</text><text x="260" y="132" class="matrix-char">ス</text><text x="260" y="148" class="matrix-char-bright" filter="url(#glow)">セ</text><text x="260" y="164" class="matrix-char-dim">ソ</text><text x="260" y="180" class="matrix-char">チ</text><text x="260" y="196" class="matrix-char">4</text><text x="260" y="212" class="matrix-char-dim">ツ</text>
    </g>
    <g class="col18" style="animation-delay:-1.2s">
      <text x="275" y="20"  class="matrix-char-dim">テ</text><text x="275" y="36"  class="matrix-char-bright" filter="url(#glow)">ト</text><text x="275" y="52"  class="matrix-char">ナ</text><text x="275" y="68"  class="matrix-char-dim">ニ</text><text x="275" y="84"  class="matrix-char">ヌ</text><text x="275" y="100" class="matrix-char">1</text><text x="275" y="116" class="matrix-char-dim">ネ</text><text x="275" y="132" class="matrix-char-bright" filter="url(#glow)">ノ</text><text x="275" y="148" class="matrix-char">ハ</text><text x="275" y="164" class="matrix-char-dim">ヒ</text><text x="275" y="180" class="matrix-char">フ</text><text x="275" y="196" class="matrix-char">6</text><text x="275" y="212" class="matrix-char-dim">ヘ</text>
    </g>
    <g class="col19" style="animation-delay:-0.55s">
      <text x="290" y="20"  class="matrix-char-bright" filter="url(#glow)">ホ</text><text x="290" y="36"  class="matrix-char-dim">マ</text><text x="290" y="52"  class="matrix-char">ミ</text><text x="290" y="68"  class="matrix-char">ム</text><text x="290" y="84"  class="matrix-char-dim">メ</text><text x="290" y="100" class="matrix-char">0</text><text x="290" y="116" class="matrix-char-bright" filter="url(#glow)">モ</text><text x="290" y="132" class="matrix-char">ヤ</text><text x="290" y="148" class="matrix-char-dim">ユ</text><text x="290" y="164" class="matrix-char">ヨ</text><text x="290" y="180" class="matrix-char">7</text><text x="290" y="196" class="matrix-char-dim">リ</text><text x="290" y="212" class="matrix-char-bright" filter="url(#glow)">ル</text>
    </g>

    <!-- Columns 20-59: dense fill across the rest of the banner -->
    <g class="col20" style="animation-delay:-1.35s"><text x="305" y="20" class="matrix-char-dim">レ</text><text x="305" y="36" class="matrix-char">3</text><text x="305" y="52" class="matrix-char-bright" filter="url(#glow)">ロ</text><text x="305" y="68" class="matrix-char">ワ</text><text x="305" y="84" class="matrix-char-dim">ヲ</text><text x="305" y="100" class="matrix-char">ン</text><text x="305" y="116" class="matrix-char">ア</text><text x="305" y="132" class="matrix-char-dim">イ</text><text x="305" y="148" class="matrix-char-bright" filter="url(#glow)">ウ</text><text x="305" y="164" class="matrix-char">9</text><text x="305" y="180" class="matrix-char-dim">エ</text><text x="305" y="196" class="matrix-char">オ</text><text x="305" y="212" class="matrix-char">カ</text></g>
    <g class="col21" style="animation-delay:-0.75s"><text x="320" y="20" class="matrix-char">キ</text><text x="320" y="36" class="matrix-char-bright" filter="url(#glow)">ク</text><text x="320" y="52" class="matrix-char-dim">5</text><text x="320" y="68" class="matrix-char">コ</text><text x="320" y="84" class="matrix-char">サ</text><text x="320" y="100" class="matrix-char-dim">シ</text><text x="320" y="116" class="matrix-char-bright" filter="url(#glow)">ス</text><text x="320" y="132" class="matrix-char">セ</text><text x="320" y="148" class="matrix-char-dim">ソ</text><text x="320" y="164" class="matrix-char">2</text><text x="320" y="180" class="matrix-char">チ</text><text x="320" y="196" class="matrix-char-dim">ツ</text><text x="320" y="212" class="matrix-char-bright" filter="url(#glow)">テ</text></g>
    <g class="col22" style="animation-delay:-1.65s"><text x="335" y="20" class="matrix-char-dim">ト</text><text x="335" y="36" class="matrix-char">ナ</text><text x="335" y="52" class="matrix-char-bright" filter="url(#glow)">ニ</text><text x="335" y="68" class="matrix-char-dim">8</text><text x="335" y="84" class="matrix-char">ネ</text><text x="335" y="100" class="matrix-char">ノ</text><text x="335" y="116" class="matrix-char-dim">ハ</text><text x="335" y="132" class="matrix-char-bright" filter="url(#glow)">ヒ</text><text x="335" y="148" class="matrix-char">フ</text><text x="335" y="164" class="matrix-char-dim">ヘ</text><text x="335" y="180" class="matrix-char">4</text><text x="335" y="196" class="matrix-char">ホ</text><text x="335" y="212" class="matrix-char-dim">マ</text></g>
    <g class="col23" style="animation-delay:-0.25s"><text x="350" y="20" class="matrix-char-bright" filter="url(#glow)">ミ</text><text x="350" y="36" class="matrix-char-dim">ム</text><text x="350" y="52" class="matrix-char">メ</text><text x="350" y="68" class="matrix-char">1</text><text x="350" y="84" class="matrix-char-dim">モ</text><text x="350" y="100" class="matrix-char-bright" filter="url(#glow)">ヤ</text><text x="350" y="116" class="matrix-char">ユ</text><text x="350" y="132" class="matrix-char-dim">ヨ</text><text x="350" y="148" class="matrix-char">リ</text><text x="350" y="164" class="matrix-char">6</text><text x="350" y="180" class="matrix-char-dim">ル</text><text x="350" y="196" class="matrix-char-bright" filter="url(#glow)">レ</text><text x="350" y="212" class="matrix-char">ロ</text></g>
    <g class="col24" style="animation-delay:-1.45s"><text x="365" y="20" class="matrix-char-dim">ワ</text><text x="365" y="36" class="matrix-char">ヲ</text><text x="365" y="52" class="matrix-char">0</text><text x="365" y="68" class="matrix-char-bright" filter="url(#glow)">ン</text><text x="365" y="84" class="matrix-char-dim">ア</text><text x="365" y="100" class="matrix-char">イ</text><text x="365" y="116" class="matrix-char">ウ</text><text x="365" y="132" class="matrix-char-dim">エ</text><text x="365" y="148" class="matrix-char-bright" filter="url(#glow)">7</text><text x="365" y="164" class="matrix-char">オ</text><text x="365" y="180" class="matrix-char-dim">カ</text><text x="365" y="196" class="matrix-char">キ</text><text x="365" y="212" class="matrix-char">ク</text></g>
    <g class="col25" style="animation-delay:-0.85s"><text x="380" y="20" class="matrix-char-bright" filter="url(#glow)">ケ</text><text x="380" y="36" class="matrix-char">コ</text><text x="380" y="52" class="matrix-char-dim">サ</text><text x="380" y="68" class="matrix-char">シ</text><text x="380" y="84" class="matrix-char">3</text><text x="380" y="100" class="matrix-char-dim">ス</text><text x="380" y="116" class="matrix-char-bright" filter="url(#glow)">セ</text><text x="380" y="132" class="matrix-char">ソ</text><text x="380" y="148" class="matrix-char-dim">チ</text><text x="380" y="164" class="matrix-char">ツ</text><text x="380" y="180" class="matrix-char">9</text><text x="380" y="196" class="matrix-char-dim">テ</text><text x="380" y="212" class="matrix-char-bright" filter="url(#glow)">ト</text></g>
    <g class="col26" style="animation-delay:-1.95s"><text x="395" y="20" class="matrix-char-dim">ナ</text><text x="395" y="36" class="matrix-char-bright" filter="url(#glow)">ニ</text><text x="395" y="52" class="matrix-char">ヌ</text><text x="395" y="68" class="matrix-char-dim">ネ</text><text x="395" y="84" class="matrix-char">5</text><text x="395" y="100" class="matrix-char">ノ</text><text x="395" y="116" class="matrix-char-dim">ハ</text><text x="395" y="132" class="matrix-char-bright" filter="url(#glow)">ヒ</text><text x="395" y="148" class="matrix-char">フ</text><text x="395" y="164" class="matrix-char-dim">ヘ</text><text x="395" y="180" class="matrix-char">ホ</text><text x="395" y="196" class="matrix-char">2</text><text x="395" y="212" class="matrix-char-dim">マ</text></g>
    <g class="col27" style="animation-delay:-0.45s"><text x="410" y="20" class="matrix-char-bright" filter="url(#glow)">ミ</text><text x="410" y="36" class="matrix-char-dim">ム</text><text x="410" y="52" class="matrix-char">メ</text><text x="410" y="68" class="matrix-char">8</text><text x="410" y="84" class="matrix-char-dim">モ</text><text x="410" y="100" class="matrix-char">ヤ</text><text x="410" y="116" class="matrix-char-bright" filter="url(#glow)">ユ</text><text x="410" y="132" class="matrix-char">ヨ</text><text x="410" y="148" class="matrix-char-dim">リ</text><text x="410" y="164" class="matrix-char">4</text><text x="410" y="180" class="matrix-char">ル</text><text x="410" y="196" class="matrix-char-dim">レ</text><text x="410" y="212" class="matrix-char-bright" filter="url(#glow)">ロ</text></g>
    <g class="col28" style="animation-delay:-1.55s"><text x="425" y="20" class="matrix-char">ワ</text><text x="425" y="36" class="matrix-char">1</text><text x="425" y="52" class="matrix-char-dim">ヲ</text><text x="425" y="68" class="matrix-char-bright" filter="url(#glow)">ン</text><text x="425" y="84" class="matrix-char">ア</text><text x="425" y="100" class="matrix-char-dim">イ</text><text x="425" y="116" class="matrix-char">ウ</text><text x="425" y="132" class="matrix-char">エ</text><text x="425" y="148" class="matrix-char-dim">0</text><text x="425" y="164" class="matrix-char-bright" filter="url(#glow)">オ</text><text x="425" y="180" class="matrix-char">カ</text><text x="425" y="196" class="matrix-char-dim">キ</text><text x="425" y="212" class="matrix-char">ク</text></g>
    <g class="col29" style="animation-delay:-0.15s"><text x="440" y="20" class="matrix-char-dim">ケ</text><text x="440" y="36" class="matrix-char-bright" filter="url(#glow)">コ</text><text x="440" y="52" class="matrix-char">6</text><text x="440" y="68" class="matrix-char-dim">サ</text><text x="440" y="84" class="matrix-char">シ</text><text x="440" y="100" class="matrix-char-bright" filter="url(#glow)">ス</text><text x="440" y="116" class="matrix-char-dim">セ</text><text x="440" y="132" class="matrix-char">ソ</text><text x="440" y="148" class="matrix-char">チ</text><text x="440" y="164" class="matrix-char-dim">7</text><text x="440" y="180" class="matrix-char-bright" filter="url(#glow)">ツ</text><text x="440" y="196" class="matrix-char">テ</text><text x="440" y="212" class="matrix-char-dim">ト</text></g>
    <g class="col30" style="animation-delay:-1.25s"><text x="455" y="20" class="matrix-char">ナ</text><text x="455" y="36" class="matrix-char-dim">ニ</text><text x="455" y="52" class="matrix-char-bright" filter="url(#glow)">ヌ</text><text x="455" y="68" class="matrix-char">ネ</text><text x="455" y="84" class="matrix-char-dim">ノ</text><text x="455" y="100" class="matrix-char">3</text><text x="455" y="116" class="matrix-char">ハ</text><text x="455" y="132" class="matrix-char-dim">ヒ</text><text x="455" y="148" class="matrix-char-bright" filter="url(#glow)">フ</text><text x="455" y="164" class="matrix-char">ヘ</text><text x="455" y="180" class="matrix-char-dim">ホ</text><text x="455" y="196" class="matrix-char">マ</text><text x="455" y="212" class="matrix-char">9</text></g>
    <g class="col31" style="animation-delay:-0.65s"><text x="470" y="20" class="matrix-char-bright" filter="url(#glow)">ミ</text><text x="470" y="36" class="matrix-char">ム</text><text x="470" y="52" class="matrix-char-dim">メ</text><text x="470" y="68" class="matrix-char">モ</text><text x="470" y="84" class="matrix-char-bright" filter="url(#glow)">5</text><text x="470" y="100" class="matrix-char-dim">ヤ</text><text x="470" y="116" class="matrix-char">ユ</text><text x="470" y="132" class="matrix-char">ヨ</text><text x="470" y="148" class="matrix-char-dim">リ</text><text x="470" y="164" class="matrix-char-bright" filter="url(#glow)">ル</text><text x="470" y="180" class="matrix-char">レ</text><text x="470" y="196" class="matrix-char-dim">2</text><text x="470" y="212" class="matrix-char">ロ</text></g>
    <g class="col32" style="animation-delay:-1.85s"><text x="485" y="20" class="matrix-char-dim">ワ</text><text x="485" y="36" class="matrix-char-bright" filter="url(#glow)">ヲ</text><text x="485" y="52" class="matrix-char">ン</text><text x="485" y="68" class="matrix-char-dim">ア</text><text x="485" y="84" class="matrix-char">イ</text><text x="485" y="100" class="matrix-char">8</text><text x="485" y="116" class="matrix-char-dim">ウ</text><text x="485" y="132" class="matrix-char-bright" filter="url(#glow)">エ</text><text x="485" y="148" class="matrix-char">オ</text><text x="485" y="164" class="matrix-char-dim">カ</text><text x="485" y="180" class="matrix-char">キ</text><text x="485" y="196" class="matrix-char">1</text><text x="485" y="212" class="matrix-char-dim">ク</text></g>
    <g class="col33" style="animation-delay:-0.35s"><text x="500" y="20" class="matrix-char-bright" filter="url(#glow)">ケ</text><text x="500" y="36" class="matrix-char-dim">コ</text><text x="500" y="52" class="matrix-char">サ</text><text x="500" y="68" class="matrix-char">シ</text><text x="500" y="84" class="matrix-char-dim">4</text><text x="500" y="100" class="matrix-char">ス</text><text x="500" y="116" class="matrix-char-bright" filter="url(#glow)">セ</text><text x="500" y="132" class="matrix-char">ソ</text><text x="500" y="148" class="matrix-char-dim">チ</text><text x="500" y="164" class="matrix-char">ツ</text><text x="500" y="180" class="matrix-char">0</text><text x="500" y="196" class="matrix-char-dim">テ</text><text x="500" y="212" class="matrix-char-bright" filter="url(#glow)">ト</text></g>
    <g class="col34" style="animation-delay:-1.15s"><text x="515" y="20" class="matrix-char-dim">ナ</text><text x="515" y="36" class="matrix-char">ニ</text><text x="515" y="52" class="matrix-char-bright" filter="url(#glow)">ヌ</text><text x="515" y="68" class="matrix-char-dim">ネ</text><text x="515" y="84" class="matrix-char">6</text><text x="515" y="100" class="matrix-char">ノ</text><text x="515" y="116" class="matrix-char-dim">ハ</text><text x="515" y="132" class="matrix-char-bright" filter="url(#glow)">ヒ</text><text x="515" y="148" class="matrix-char">フ</text><text x="515" y="164" class="matrix-char-dim">ヘ</text><text x="515" y="180" class="matrix-char">ホ</text><text x="515" y="196" class="matrix-char">7</text><text x="515" y="212" class="matrix-char-dim">マ</text></g>
    <g class="col35" style="animation-delay:-0.95s"><text x="530" y="20" class="matrix-char-bright" filter="url(#glow)">ミ</text><text x="530" y="36" class="matrix-char-dim">ム</text><text x="530" y="52" class="matrix-char">メ</text><text x="530" y="68" class="matrix-char">モ</text><text x="530" y="84" class="matrix-char-dim">ヤ</text><text x="530" y="100" class="matrix-char">3</text><text x="530" y="116" class="matrix-char-bright" filter="url(#glow)">ユ</text><text x="530" y="132" class="matrix-char">ヨ</text><text x="530" y="148" class="matrix-char-dim">リ</text><text x="530" y="164" class="matrix-char">ル</text><text x="530" y="180" class="matrix-char">9</text><text x="530" y="196" class="matrix-char-dim">レ</text><text x="530" y="212" class="matrix-char-bright" filter="url(#glow)">ロ</text></g>
    <g class="col36" style="animation-delay:-1.75s"><text x="545" y="20" class="matrix-char">ワ</text><text x="545" y="36" class="matrix-char">ヲ</text><text x="545" y="52" class="matrix-char-dim">5</text><text x="545" y="68" class="matrix-char-bright" filter="url(#glow)">ン</text><text x="545" y="84" class="matrix-char">ア</text><text x="545" y="100" class="matrix-char-dim">イ</text><text x="545" y="116" class="matrix-char">ウ</text><text x="545" y="132" class="matrix-char">2</text><text x="545" y="148" class="matrix-char-dim">エ</text><text x="545" y="164" class="matrix-char-bright" filter="url(#glow)">オ</text><text x="545" y="180" class="matrix-char-dim">カ</text><text x="545" y="196" class="matrix-char">キ</text><text x="545" y="212" class="matrix-char">ク</text></g>
    <g class="col37" style="animation-delay:-0.05s"><text x="560" y="20" class="matrix-char-dim">ケ</text><text x="560" y="36" class="matrix-char-bright" filter="url(#glow)">コ</text><text x="560" y="52" class="matrix-char">サ</text><text x="560" y="68" class="matrix-char-dim">8</text><text x="560" y="84" class="matrix-char">シ</text><text x="560" y="100" class="matrix-char">ス</text><text x="560" y="116" class="matrix-char-dim">セ</text><text x="560" y="132" class="matrix-char-bright" filter="url(#glow)">ソ</text><text x="560" y="148" class="matrix-char">チ</text><text x="560" y="164" class="matrix-char-dim">ツ</text><text x="560" y="180" class="matrix-char">テ</text><text x="560" y="196" class="matrix-char">4</text><text x="560" y="212" class="matrix-char-dim">ト</text></g>
    <g class="col38" style="animation-delay:-1.05s"><text x="575" y="20" class="matrix-char-bright" filter="url(#glow)">ナ</text><text x="575" y="36" class="matrix-char-dim">ニ</text><text x="575" y="52" class="matrix-char">ヌ</text><text x="575" y="68" class="matrix-char">ネ</text><text x="575" y="84" class="matrix-char-dim">1</text><text x="575" y="100" class="matrix-char">ノ</text><text x="575" y="116" class="matrix-char-bright" filter="url(#glow)">ハ</text><text x="575" y="132" class="matrix-char">ヒ</text><text x="575" y="148" class="matrix-char-dim">フ</text><text x="575" y="164" class="matrix-char">0</text><text x="575" y="180" class="matrix-char">ヘ</text><text x="575" y="196" class="matrix-char-dim">ホ</text><text x="575" y="212" class="matrix-char-bright" filter="url(#glow)">マ</text></g>
    <g class="col39" style="animation-delay:-1.55s"><text x="590" y="20" class="matrix-char">ミ</text><text x="590" y="36" class="matrix-char-bright" filter="url(#glow)">6</text><text x="590" y="52" class="matrix-char-dim">ム</text><text x="590" y="68" class="matrix-char">メ</text><text x="590" y="84" class="matrix-char">モ</text><text x="590" y="100" class="matrix-char-dim">ヤ</text><text x="590" y="116" class="matrix-char">ユ</text><text x="590" y="132" class="matrix-char">7</text><text x="590" y="148" class="matrix-char-dim">ヨ</text><text x="590" y="164" class="matrix-char-bright" filter="url(#glow)">リ</text><text x="590" y="180" class="matrix-char">ル</text><text x="590" y="196" class="matrix-char-dim">レ</text><text x="590" y="212" class="matrix-char">ロ</text></g>
    <g class="col40" style="animation-delay:-0.55s"><text x="605" y="20" class="matrix-char-dim">ワ</text><text x="605" y="36" class="matrix-char">ヲ</text><text x="605" y="52" class="matrix-char-bright" filter="url(#glow)">ン</text><text x="605" y="68" class="matrix-char-dim">ア</text><text x="605" y="84" class="matrix-char">3</text><text x="605" y="100" class="matrix-char">イ</text><text x="605" y="116" class="matrix-char-dim">ウ</text><text x="605" y="132" class="matrix-char-bright" filter="url(#glow)">エ</text><text x="605" y="148" class="matrix-char">オ</text><text x="605" y="164" class="matrix-char-dim">カ</text><text x="605" y="180" class="matrix-char">9</text><text x="605" y="196" class="matrix-char">キ</text><text x="605" y="212" class="matrix-char-dim">ク</text></g>
    <g class="col41" style="animation-delay:-1.35s"><text x="620" y="20" class="matrix-char-bright" filter="url(#glow)">ケ</text><text x="620" y="36" class="matrix-char-dim">コ</text><text x="620" y="52" class="matrix-char">サ</text><text x="620" y="68" class="matrix-char">シ</text><text x="620" y="84" class="matrix-char-dim">5</text><text x="620" y="100" class="matrix-char">ス</text><text x="620" y="116" class="matrix-char-bright" filter="url(#glow)">セ</text><text x="620" y="132" class="matrix-char">ソ</text><text x="620" y="148" class="matrix-char-dim">2</text><text x="620" y="164" class="matrix-char">チ</text><text x="620" y="180" class="matrix-char">ツ</text><text x="620" y="196" class="matrix-char-dim">テ</text><text x="620" y="212" class="matrix-char-bright" filter="url(#glow)">ト</text></g>
    <g class="col42" style="animation-delay:-0.85s"><text x="635" y="20" class="matrix-char-dim">ナ</text><text x="635" y="36" class="matrix-char-bright" filter="url(#glow)">ニ</text><text x="635" y="52" class="matrix-char">8</text><text x="635" y="68" class="matrix-char-dim">ヌ</text><text x="635" y="84" class="matrix-char">ネ</text><text x="635" y="100" class="matrix-char">ノ</text><text x="635" y="116" class="matrix-char-dim">ハ</text><text x="635" y="132" class="matrix-char-bright" filter="url(#glow)">ヒ</text><text x="635" y="148" class="matrix-char">フ</text><text x="635" y="164" class="matrix-char-dim">1</text><text x="635" y="180" class="matrix-char">ヘ</text><text x="635" y="196" class="matrix-char">ホ</text><text x="635" y="212" class="matrix-char-dim">マ</text></g>
    <g class="col43" style="animation-delay:-1.95s"><text x="650" y="20" class="matrix-char-bright" filter="url(#glow)">ミ</text><text x="650" y="36" class="matrix-char">ム</text><text x="650" y="52" class="matrix-char-dim">メ</text><text x="650" y="68" class="matrix-char">4</text><text x="650" y="84" class="matrix-char">モ</text><text x="650" y="100" class="matrix-char-dim">ヤ</text><text x="650" y="116" class="matrix-char">ユ</text><text x="650" y="132" class="matrix-char-bright" filter="url(#glow)">0</text><text x="650" y="148" class="matrix-char-dim">ヨ</text><text x="650" y="164" class="matrix-char">リ</text><text x="650" y="180" class="matrix-char">ル</text><text x="650" y="196" class="matrix-char-dim">6</text><text x="650" y="212" class="matrix-char-bright" filter="url(#glow)">レ</text></g>
    <g class="col44" style="animation-delay:-0.45s"><text x="665" y="20" class="matrix-char-dim">ロ</text><text x="665" y="36" class="matrix-char">ワ</text><text x="665" y="52" class="matrix-char-bright" filter="url(#glow)">ヲ</text><text x="665" y="68" class="matrix-char">ン</text><text x="665" y="84" class="matrix-char-dim">7</text><text x="665" y="100" class="matrix-char">ア</text><text x="665" y="116" class="matrix-char">イ</text><text x="665" y="132" class="matrix-char-dim">ウ</text><text x="665" y="148" class="matrix-char-bright" filter="url(#glow)">エ</text><text x="665" y="164" class="matrix-char">3</text><text x="665" y="180" class="matrix-char-dim">オ</text><text x="665" y="196" class="matrix-char">カ</text><text x="665" y="212" class="matrix-char">キ</text></g>
    <g class="col45" style="animation-delay:-1.65s"><text x="680" y="20" class="matrix-char">ク</text><text x="680" y="36" class="matrix-char-bright" filter="url(#glow)">ケ</text><text x="680" y="52" class="matrix-char-dim">コ</text><text x="680" y="68" class="matrix-char">サ</text><text x="680" y="84" class="matrix-char">9</text><text x="680" y="100" class="matrix-char-dim">シ</text><text x="680" y="116" class="matrix-char-bright" filter="url(#glow)">ス</text><text x="680" y="132" class="matrix-char">セ</text><text x="680" y="148" class="matrix-char-dim">ソ</text><text x="680" y="164" class="matrix-char">5</text><text x="680" y="180" class="matrix-char">チ</text><text x="680" y="196" class="matrix-char-dim">ツ</text><text x="680" y="212" class="matrix-char-bright" filter="url(#glow)">テ</text></g>
    <g class="col46" style="animation-delay:-0.25s"><text x="695" y="20" class="matrix-char-dim">ト</text><text x="695" y="36" class="matrix-char">ナ</text><text x="695" y="52" class="matrix-char-bright" filter="url(#glow)">2</text><text x="695" y="68" class="matrix-char">ニ</text><text x="695" y="84" class="matrix-char-dim">ヌ</text><text x="695" y="100" class="matrix-char">ネ</text><text x="695" y="116" class="matrix-char">ノ</text><text x="695" y="132" class="matrix-char-dim">ハ</text><text x="695" y="148" class="matrix-char-bright" filter="url(#glow)">ヒ</text><text x="695" y="164" class="matrix-char">8</text><text x="695" y="180" class="matrix-char-dim">フ</text><text x="695" y="196" class="matrix-char">ヘ</text><text x="695" y="212" class="matrix-char">ホ</text></g>
    <g class="col47" style="animation-delay:-1.45s"><text x="710" y="20" class="matrix-char-bright" filter="url(#glow)">マ</text><text x="710" y="36" class="matrix-char-dim">ミ</text><text x="710" y="52" class="matrix-char">ム</text><text x="710" y="68" class="matrix-char">メ</text><text x="710" y="84" class="matrix-char-dim">1</text><text x="710" y="100" class="matrix-char">モ</text><text x="710" y="116" class="matrix-char-bright" filter="url(#glow)">ヤ</text><text x="710" y="132" class="matrix-char">ユ</text><text x="710" y="148" class="matrix-char-dim">ヨ</text><text x="710" y="164" class="matrix-char">リ</text><text x="710" y="180" class="matrix-char">4</text><text x="710" y="196" class="matrix-char-dim">ル</text><text x="710" y="212" class="matrix-char-bright" filter="url(#glow)">レ</text></g>
    <g class="col48" style="animation-delay:-0.75s"><text x="725" y="20" class="matrix-char">ロ</text><text x="725" y="36" class="matrix-char-bright" filter="url(#glow)">ワ</text><text x="725" y="52" class="matrix-char-dim">6</text><text x="725" y="68" class="matrix-char">ヲ</text><text x="725" y="84" class="matrix-char">ン</text><text x="725" y="100" class="matrix-char-dim">ア</text><text x="725" y="116" class="matrix-char">イ</text><text x="725" y="132" class="matrix-char-bright" filter="url(#glow)">ウ</text><text x="725" y="148" class="matrix-char">エ</text><text x="725" y="164" class="matrix-char-dim">0</text><text x="725" y="180" class="matrix-char">オ</text><text x="725" y="196" class="matrix-char">カ</text><text x="725" y="212" class="matrix-char-dim">7</text></g>
    <g class="col49" style="animation-delay:-1.85s"><text x="740" y="20" class="matrix-char-bright" filter="url(#glow)">キ</text><text x="740" y="36" class="matrix-char-dim">ク</text><text x="740" y="52" class="matrix-char">ケ</text><text x="740" y="68" class="matrix-char">3</text><text x="740" y="84" class="matrix-char-dim">コ</text><text x="740" y="100" class="matrix-char">サ</text><text x="740" y="116" class="matrix-char-bright" filter="url(#glow)">シ</text><text x="740" y="132" class="matrix-char">ス</text><text x="740" y="148" class="matrix-char-dim">セ</text><text x="740" y="164" class="matrix-char">ソ</text><text x="740" y="180" class="matrix-char">9</text><text x="740" y="196" class="matrix-char-dim">チ</text><text x="740" y="212" class="matrix-char-bright" filter="url(#glow)">ツ</text></g>
    <g class="col50" style="animation-delay:-0.35s"><text x="755" y="20" class="matrix-char-dim">テ</text><text x="755" y="36" class="matrix-char">ト</text><text x="755" y="52" class="matrix-char-bright" filter="url(#glow)">ナ</text><text x="755" y="68" class="matrix-char-dim">5</text><text x="755" y="84" class="matrix-char">ニ</text><text x="755" y="100" class="matrix-char">ヌ</text><text x="755" y="116" class="matrix-char-dim">ネ</text><text x="755" y="132" class="matrix-char-bright" filter="url(#glow)">ノ</text><text x="755" y="148" class="matrix-char">ハ</text><text x="755" y="164" class="matrix-char-dim">ヒ</text><text x="755" y="180" class="matrix-char">フ</text><text x="755" y="196" class="matrix-char">2</text><text x="755" y="212" class="matrix-char-dim">ヘ</text></g>
    <g class="col51" style="animation-delay:-1.15s"><text x="770" y="20" class="matrix-char-bright" filter="url(#glow)">ホ</text><text x="770" y="36" class="matrix-char-dim">マ</text><text x="770" y="52" class="matrix-char">ミ</text><text x="770" y="68" class="matrix-char">8</text><text x="770" y="84" class="matrix-char-dim">ム</text><text x="770" y="100" class="matrix-char">メ</text><text x="770" y="116" class="matrix-char-bright" filter="url(#glow)">モ</text><text x="770" y="132" class="matrix-char">ヤ</text><text x="770" y="148" class="matrix-char-dim">ユ</text><text x="770" y="164" class="matrix-char">1</text><text x="770" y="180" class="matrix-char">ヨ</text><text x="770" y="196" class="matrix-char-dim">リ</text><text x="770" y="212" class="matrix-char-bright" filter="url(#glow)">ル</text></g>
    <g class="col52" style="animation-delay:-0.65s"><text x="785" y="20" class="matrix-char">レ</text><text x="785" y="36" class="matrix-char-bright" filter="url(#glow)">ロ</text><text x="785" y="52" class="matrix-char-dim">ワ</text><text x="785" y="68" class="matrix-char">ヲ</text><text x="785" y="84" class="matrix-char">4</text><text x="785" y="100" class="matrix-char-dim">ン</text><text x="785" y="116" class="matrix-char">ア</text><text x="785" y="132" class="matrix-char-bright" filter="url(#glow)">イ</text><text x="785" y="148" class="matrix-char">ウ</text><text x="785" y="164" class="matrix-char-dim">エ</text><text x="785" y="180" class="matrix-char">6</text><text x="785" y="196" class="matrix-char">オ</text><text x="785" y="212" class="matrix-char-dim">カ</text></g>
    <g class="col53" style="animation-delay:-1.75s"><text x="800" y="20" class="matrix-char-bright" filter="url(#glow)">キ</text><text x="800" y="36" class="matrix-char-dim">ク</text><text x="800" y="52" class="matrix-char">0</text><text x="800" y="68" class="matrix-char">ケ</text><text x="800" y="84" class="matrix-char-dim">コ</text><text x="800" y="100" class="matrix-char">サ</text><text x="800" y="116" class="matrix-char-bright" filter="url(#glow)">3</text><text x="800" y="132" class="matrix-char">ス</text><text x="800" y="148" class="matrix-char-dim">セ</text><text x="800" y="164" class="matrix-char">ソ</text><text x="800" y="180" class="matrix-char">チ</text><text x="800" y="196" class="matrix-char-dim">9</text><text x="800" y="212" class="matrix-char-bright" filter="url(#glow)">ツ</text></g>
    <g class="col54" style="animation-delay:-0.15s"><text x="815" y="20" class="matrix-char-dim">テ</text><text x="815" y="36" class="matrix-char">ト</text><text x="815" y="52" class="matrix-char-bright" filter="url(#glow)">ナ</text><text x="815" y="68" class="matrix-char">7</text><text x="815" y="84" class="matrix-char-dim">ニ</text><text x="815" y="100" class="matrix-char">ヌ</text><text x="815" y="116" class="matrix-char">ネ</text><text x="815" y="132" class="matrix-char-dim">ノ</text><text x="815" y="148" class="matrix-char-bright" filter="url(#glow)">ハ</text><text x="815" y="164" class="matrix-char">ヒ</text><text x="815" y="180" class="matrix-char-dim">5</text><text x="815" y="196" class="matrix-char">フ</text><text x="815" y="212" class="matrix-char">ヘ</text></g>
    <g class="col55" style="animation-delay:-1.05s"><text x="830" y="20" class="matrix-char-bright" filter="url(#glow)">ホ</text><text x="830" y="36" class="matrix-char-dim">マ</text><text x="830" y="52" class="matrix-char">ミ</text><text x="830" y="68" class="matrix-char">2</text><text x="830" y="84" class="matrix-char-dim">ム</text><text x="830" y="100" class="matrix-char">メ</text><text x="830" y="116" class="matrix-char-bright" filter="url(#glow)">モ</text><text x="830" y="132" class="matrix-char">8</text><text x="830" y="148" class="matrix-char-dim">ユ</text><text x="830" y="164" class="matrix-char">ヨ</text><text x="830" y="180" class="matrix-char">リ</text><text x="830" y="196" class="matrix-char-dim">ル</text><text x="830" y="212" class="matrix-char-bright" filter="url(#glow)">レ</text></g>
    <g class="col56" style="animation-delay:-1.55s"><text x="845" y="20" class="matrix-char">ロ</text><text x="845" y="36" class="matrix-char-bright" filter="url(#glow)">ワ</text><text x="845" y="52" class="matrix-char-dim">1</text><text x="845" y="68" class="matrix-char">ヲ</text><text x="845" y="84" class="matrix-char">ン</text><text x="845" y="100" class="matrix-char-dim">ア</text><text x="845" y="116" class="matrix-char">4</text><text x="845" y="132" class="matrix-char-bright" filter="url(#glow)">イ</text><text x="845" y="148" class="matrix-char">ウ</text><text x="845" y="164" class="matrix-char-dim">エ</text><text x="845" y="180" class="matrix-char">オ</text><text x="845" y="196" class="matrix-char">カ</text><text x="845" y="212" class="matrix-char-dim">0</text></g>
    <g class="col57" style="animation-delay:-0.55s"><text x="860" y="20" class="matrix-char-dim">キ</text><text x="860" y="36" class="matrix-char">ク</text><text x="860" y="52" class="matrix-char-bright" filter="url(#glow)">6</text><text x="860" y="68" class="matrix-char-dim">ケ</text><text x="860" y="84" class="matrix-char">コ</text><text x="860" y="100" class="matrix-char">サ</text><text x="860" y="116" class="matrix-char-dim">シ</text><text x="860" y="132" class="matrix-char-bright" filter="url(#glow)">ス</text><text x="860" y="148" class="matrix-char">3</text><text x="860" y="164" class="matrix-char-dim">セ</text><text x="860" y="180" class="matrix-char">ソ</text><text x="860" y="196" class="matrix-char">チ</text><text x="860" y="212" class="matrix-char-dim">ツ</text></g>
    <g class="col58" style="animation-delay:-1.25s"><text x="875" y="20" class="matrix-char-bright" filter="url(#glow)">テ</text><text x="875" y="36" class="matrix-char-dim">ト</text><text x="875" y="52" class="matrix-char">ナ</text><text x="875" y="68" class="matrix-char">9</text><text x="875" y="84" class="matrix-char-dim">ニ</text><text x="875" y="100" class="matrix-char">ヌ</text><text x="875" y="116" class="matrix-char-bright" filter="url(#glow)">ネ</text><text x="875" y="132" class="matrix-char">7</text><text x="875" y="148" class="matrix-char-dim">ハ</text><text x="875" y="164" class="matrix-char">ヒ</text><text x="875" y="180" class="matrix-char">フ</text><text x="875" y="196" class="matrix-char-dim">ヘ</text><text x="875" y="212" class="matrix-char-bright" filter="url(#glow)">ホ</text></g>
    <g class="col59" style="animation-delay:-0.95s"><text x="890" y="20" class="matrix-char">マ</text><text x="890" y="36" class="matrix-char-bright" filter="url(#glow)">ミ</text><text x="890" y="52" class="matrix-char-dim">5</text><text x="890" y="68" class="matrix-char">ム</text><text x="890" y="84" class="matrix-char">メ</text><text x="890" y="100" class="matrix-char-dim">モ</text><text x="890" y="116" class="matrix-char">ヤ</text><text x="890" y="132" class="matrix-char-bright" filter="url(#glow)">2</text><text x="890" y="148" class="matrix-char">ヨ</text><text x="890" y="164" class="matrix-char-dim">リ</text><text x="890" y="180" class="matrix-char">ル</text><text x="890" y="196" class="matrix-char">レ</text><text x="890" y="212" class="matrix-char-dim">ロ</text></g>

  </g>

  <!-- Dark overlay behind name for readability -->
  <rect x="80" y="68" width="740" height="84" rx="8" fill="rgba(0,0,0,0.65)"/>

  <!-- Name shadow/glow layer -->
  <text x="450" y="132" text-anchor="middle" class="name-text" filter="url(#nameGlow)" opacity="0.6">SHARAN NANDA KUMAR</text>

  <!-- Name main layer with pulse animation -->
  <text x="450" y="132" text-anchor="middle" class="name-glow name-pulse" filter="url(#nameGlow)">SHARAN NANDA KUMAR</text>

</svg>

<p align="center">
<img src="https://readme-typing-svg.herokuapp.com?font=Share+Tech+Mono&size=26&duration=3000&pause=900&color=39FF14&center=true&vCenter=true&width=750&lines=Hi+I'm+Sharan+Nanda+Kumar;Information+Science+Engineering+Student;AI+%26+Machine+Learning+Enthusiast;Building+Real+World+Projects;Always+Learning+Something+New"/>
</p>

<p align="center">
<img src="https://img.shields.io/badge/Timezone-IST%20(UTC%2B5%3A30)-39FF14?style=for-the-badge&logo=clockify&logoColor=39FF14&labelColor=0d1117"/>
&nbsp;
<img src="https://img.shields.io/badge/Location-Bangalore%2C%20India-39FF14?style=for-the-badge&logo=googlemaps&logoColor=39FF14&labelColor=0d1117"/>
</p>

---

# 👨‍💻 About Me

| | |
|---|---|
| 💻 **Degree** | B.E. Information Science |
| 🎓 **College** | Atria Institute of Technology |
| 📅 **Graduation** | 2027 |
| 🤖 **Focus** | AI, Machine Learning, Software Systems |

---

# 🌐 Connect With Me

<p align="center"><a href="https://www.linkedin.com/in/sharan-n-k-2k42k42k4/"><img src="https://upload.wikimedia.org/wikipedia/commons/c/ca/LinkedIn_logo_initials.png" width="55"/></a>&nbsp;&nbsp;&nbsp;&nbsp;<a href="https://www.instagram.com/sharan._x?igsh=MXQxdm12cWx6ZDh5MQ=="><img src="https://upload.wikimedia.org/wikipedia/commons/a/a5/Instagram_icon.png" width="55"/></a>&nbsp;&nbsp;&nbsp;&nbsp;<a href="mailto:sharannandakumar2k4@gmail.com"><img src="https://upload.wikimedia.org/wikipedia/commons/4/4e/Gmail_Icon.png" width="55"/></a></p>

---

# ⚙️ Tech Stack

<p align="center">
<img src="https://skillicons.dev/icons?i=python,java,html,css,js,mysql,mongodb,git,linux"/>
</p>

---

# 🚀 Featured Projects

<p align="center">
<a href="https://github.com/sharantantadan/LangAssist">
<img src="https://github-readme-stats.vercel.app/api/pin/?username=sharantantadan&repo=LangAssist&theme=tokyonight&border_color=39FF14&border_radius=12"/>
</a>
<a href="https://github.com/sharantantadan/ecommerce-website">
<img src="https://github-readme-stats.vercel.app/api/pin/?username=sharantantadan&repo=ecommerce-website&theme=tokyonight&border_color=39FF14&border_radius=12"/>
</a>
</p>

---

# 📊 GitHub Stats

<p align="center">
<img src="https://github-readme-stats.vercel.app/api?username=sharantantadan&show_icons=true&theme=tokyonight&border_color=39FF14&border_radius=12&icon_color=39FF14&title_color=39FF14"/>
</p>

---

# 🔥 GitHub Streak

<p align="center">
<img src="https://streak-stats.demolab.com/?user=sharantantadan&theme=tokyonight&border=39FF14&border_radius=12&ring=39FF14&fire=39FF14&currStreakLabel=39FF14"/>
</p>

---

# 🐍 Snake Eating My Contributions

<p align="center">
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/sharantantadan/sharantantadan/output/github-contribution-grid-snake-dark.svg"/>
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/sharantantadan/sharantantadan/output/github-contribution-grid-snake.svg"/>
  <img alt="github-snake" src="https://raw.githubusercontent.com/sharantantadan/sharantantadan/output/github-contribution-grid-snake-dark.svg"/>
</picture>
</p>

---

# 📈 Contribution Activity

<p align="center">
<img src="https://github-readme-activity-graph.vercel.app/graph?username=sharantantadan&theme=tokyo-night&radius=12&color=39FF14&line=39FF14&point=ffffff"/>
</p>

---

# 🧠 Currently Learning

- Machine Learning  
- Computer Vision  
- AI System Design  
- Backend Development  

---

# Profile Views

<p align="center">
<img src="https://komarev.com/ghpvc/?username=sharantantadan&label=Profile%20Views&color=39FF14&style=flat"/>
</p>

---

Always interested in building impactful projects and collaborating with other developers.
