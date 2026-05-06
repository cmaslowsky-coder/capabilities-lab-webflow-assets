<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>The Capabilities Lab — Human-Centered AI Enablement</title>
  <meta name="description" content="We help mission-driven organizations adopt AI without losing the trust, judgment, empathy, and human connection that make their work valuable.">

  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Cormorant+Garamond:ital,wght@0,300;0,400;0,500;0,600;1,300;1,400;1,500&family=Inter:wght@300;400;500;600&display=swap" rel="stylesheet">

  <link rel="stylesheet" href="css/styles.css">
</head>
<body>

<div class="jungle">

  <!-- ═══ SKY ═══ -->
  <div class="sky"></div>

  <!-- ═══ FAR PLANE — distant tropical horizon ═══ -->
  <div class="plane far" data-rate="0.15">
    <!-- Hero zone: distant hills with palms -->
    <div class="plant" style="top: 75vh; left: 0; transform: none; width: 100vw; height: 30vh;">
      <svg viewBox="0 0 1600 300" preserveAspectRatio="none">
        <path d="M0,300 L0,170 Q120,110 240,150 Q360,90 480,130 Q600,100 720,140 Q840,90 960,130 Q1080,100 1200,140 Q1320,90 1440,130 Q1520,110 1600,150 L1600,300 Z" fill="#7ecc66" opacity="0.5"/>
        <path d="M0,300 L0,220 Q140,170 280,200 Q420,160 560,190 Q700,170 840,200 Q980,160 1120,200 Q1260,180 1400,210 Q1500,200 1600,220 L1600,300 Z" fill="#5ab068" opacity="0.7"/>
      </svg>
    </div>

    <!-- Distant palm silhouettes -->
    <div class="plant" style="top: 65vh; left: 12%; width: 18vh; height: 35vh;">
      <svg viewBox="0 0 100 200">
        <path d="M48,200 L49,30 L51,30 L52,200 Z" fill="#3d9a62" opacity="0.6"/>
        <g stroke="#3d9a62" stroke-width="1.5" fill="#3d9a62" opacity="0.6">
          <path d="M50,30 Q30,20 5,15 Q25,28 50,32 Z"/>
          <path d="M50,30 Q70,20 95,15 Q75,28 50,32 Z"/>
          <path d="M50,30 Q35,5 15,-5 Q35,18 50,30 Z"/>
          <path d="M50,30 Q65,5 85,-5 Q65,18 50,30 Z"/>
        </g>
      </svg>
    </div>
    <div class="plant" style="top: 70vh; left: 78%; width: 20vh; height: 38vh;">
      <svg viewBox="0 0 100 200">
        <path d="M48,200 L49,30 L51,30 L52,200 Z" fill="#2c8458" opacity="0.55"/>
        <g stroke="#2c8458" stroke-width="1.5" fill="#2c8458" opacity="0.55">
          <path d="M50,30 Q30,18 5,12 Q25,28 50,32 Z"/>
          <path d="M50,30 Q70,18 95,12 Q75,28 50,32 Z"/>
          <path d="M50,30 Q35,3 15,-8 Q35,18 50,30 Z"/>
          <path d="M50,30 Q65,3 85,-8 Q65,18 50,30 Z"/>
        </g>
      </svg>
    </div>

    <!-- Far hazy canopy in deeper zones -->
    <div class="plant" style="top: 155vh; left: 0; transform: none; width: 100vw; height: 25vh;">
      <svg viewBox="0 0 1600 250" preserveAspectRatio="none">
        <ellipse cx="200" cy="120" rx="200" ry="60" fill="#5ab068" opacity="0.4"/>
        <ellipse cx="600" cy="100" rx="220" ry="55" fill="#3d9a62" opacity="0.4"/>
        <ellipse cx="1000" cy="130" rx="240" ry="65" fill="#5ab068" opacity="0.4"/>
        <ellipse cx="1400" cy="110" rx="200" ry="55" fill="#3d9a62" opacity="0.4"/>
      </svg>
    </div>
  </div>

  <!-- ═══ BACK PLANE — mid distance ═══ -->
  <div class="plane back" data-rate="0.35">

    <!-- Zone 1: distant banana clump -->
    <div class="plant" style="top: 85vh; left: 8%; width: 22vh; height: 30vh;">
      <svg viewBox="0 0 200 250">
        <path d="M95,250 L95,80 L105,80 L105,250 Z" fill="#1d6b4f"/>
        <g transform="translate(100,80)">
          <path d="M0,0 Q-30,-20 -70,-30 Q-100,-30 -110,-20 Q-80,-15 -40,-10 Q-15,-5 0,0 Z" fill="#4ea554"/>
          <path d="M0,0 Q30,-20 70,-30 Q100,-30 110,-20 Q80,-15 40,-10 Q15,-5 0,0 Z" fill="#5ab068"/>
          <path d="M0,0 Q-20,-50 -50,-80 Q-80,-95 -90,-85 Q-65,-65 -35,-40 Q-10,-15 0,0 Z" fill="#7ecc66"/>
          <path d="M0,0 Q20,-50 50,-80 Q80,-95 90,-85 Q65,-65 35,-40 Q10,-15 0,0 Z" fill="#88c468"/>
        </g>
      </svg>
    </div>

    <!-- Zone 2: bromeliad cluster -->
    <div class="plant" style="top: 120vh; left: 88%; width: 18vh; height: 22vh;">
      <svg viewBox="0 0 200 200">
        <g transform="translate(100,150)">
          <path d="M0,0 L-25,-50 L-15,-55 L-5,-15 Z" fill="#5ab068"/>
          <path d="M0,0 L25,-50 L15,-55 L5,-15 Z" fill="#5ab068"/>
          <path d="M0,0 L-40,-40 L-32,-46 L-12,-12 Z" fill="#7ecc66"/>
          <path d="M0,0 L40,-40 L32,-46 L12,-12 Z" fill="#7ecc66"/>
          <path d="M0,0 L-15,-70 L-5,-72 L-2,-20 Z" fill="#88c468"/>
          <path d="M0,0 L15,-70 L5,-72 L2,-20 Z" fill="#88c468"/>
          <ellipse cx="0" cy="-12" rx="6" ry="10" fill="#ff5078"/>
          <ellipse cx="0" cy="-15" rx="3" ry="6" fill="#ffd23f"/>
        </g>
      </svg>
    </div>

    <!-- Zone 3: fern cluster -->
    <div class="plant" style="top: 155vh; left: 5%; width: 28vh; height: 25vh;">
      <svg viewBox="0 0 250 200">
        <g fill="#5ab068" opacity="0.85">
          <path d="M30,200 Q60,140 90,180 Q120,130 150,180 Q180,140 210,200 Z"/>
        </g>
        <g fill="#7ecc66">
          <path d="M50,200 Q80,150 110,190 Q140,150 170,200 Z"/>
        </g>
      </svg>
    </div>

    <!-- Zone 4: heliconia stand -->
    <div class="plant" style="top: 190vh; left: 90%; width: 16vh; height: 32vh;">
      <svg viewBox="0 0 200 400">
        <path d="M100,400 L100,200" stroke="#3d9a62" stroke-width="3" fill="none"/>
        <g transform="translate(100,250)">
          <path d="M-2,0 Q-15,15 -8,28 Q5,32 8,18 Q5,10 -2,0 Z" fill="#ff5547"/>
          <path d="M-2,28 Q-15,43 -8,56 Q5,60 8,46 Q5,38 -2,28 Z" fill="#ff8a3a"/>
          <path d="M-2,56 Q-15,71 -8,84 Q5,88 8,74 Q5,66 -2,56 Z" fill="#ff5547"/>
          <path d="M-2,84 Q-15,99 -8,112 Q5,116 8,102 Q5,94 -2,84 Z" fill="#ff8a3a"/>
          <ellipse cx="0" cy="6" rx="3" ry="2" fill="#ffe066"/>
          <ellipse cx="0" cy="34" rx="3" ry="2" fill="#ffe066"/>
        </g>
        <g transform="translate(100,200) rotate(-30)">
          <path d="M0,0 Q15,-50 30,-100 Q35,-130 25,-140 Q15,-115 8,-70 Q3,-30 0,0 Z" fill="#4ea554"/>
        </g>
        <g transform="translate(100,200) rotate(30)">
          <path d="M0,0 Q-15,-50 -30,-100 Q-35,-130 -25,-140 Q-15,-115 -8,-70 Q-3,-30 0,0 Z" fill="#5ab068"/>
        </g>
      </svg>
    </div>

    <!-- Zone 5: small tropical tree -->
    <div class="plant" style="top: 225vh; left: 7%; width: 22vh; height: 38vh;">
      <svg viewBox="0 0 200 350">
        <path d="M95,350 L97,150 L103,150 L105,350 Z" fill="#2a5544"/>
        <ellipse cx="100" cy="140" rx="60" ry="35" fill="#4ea554"/>
        <ellipse cx="70" cy="155" rx="35" ry="22" fill="#3d9a62"/>
        <ellipse cx="130" cy="155" rx="35" ry="22" fill="#3d9a62"/>
        <ellipse cx="85" cy="120" rx="38" ry="25" fill="#5ab068"/>
        <ellipse cx="115" cy="120" rx="38" ry="25" fill="#5ab068"/>
        <ellipse cx="100" cy="100" rx="32" ry="22" fill="#7ecc66"/>
      </svg>
    </div>

    <!-- Zone 6: deeper trunks -->
    <div class="plant" style="top: 260vh; left: 25%; width: 6vh; height: 60vh;">
      <svg viewBox="0 0 30 400" preserveAspectRatio="none">
        <rect x="10" y="0" width="10" height="400" fill="#2a5544" opacity="0.7"/>
      </svg>
    </div>
    <div class="plant" style="top: 260vh; left: 75%; width: 7vh; height: 65vh;">
      <svg viewBox="0 0 30 400" preserveAspectRatio="none">
        <rect x="10" y="0" width="11" height="400" fill="#1d6b4f" opacity="0.7"/>
      </svg>
    </div>
  </div>

  <!-- ═══ MID PLANE — feature plants in margins ═══ -->
  <div class="plane mid" data-rate="0.65">

    <!-- Zone 1: Bird of paradise on left -->
    <div class="plant" style="top: 115vh; left: 12%; width: 25vh; height: 45vh;">
      <svg viewBox="0 0 200 380">
        <!-- stems -->
        <path d="M100,380 L100,180" stroke="#2a5544" stroke-width="4" fill="none"/>
        <path d="M100,380 L95,200" stroke="#2a5544" stroke-width="3" fill="none"/>
        <!-- big leaves -->
        <g transform="translate(100,200) rotate(-25)">
          <path d="M0,0 Q-20,-50 -40,-100 Q-50,-130 -45,-145 Q-30,-130 -18,-90 Q-8,-45 0,0 Z" fill="#4ea554"/>
          <path d="M0,0 Q-15,-60 -25,-130" stroke="#2a5544" stroke-width="1.5" fill="none"/>
        </g>
        <g transform="translate(100,200) rotate(20)">
          <path d="M0,0 Q20,-50 40,-100 Q50,-130 45,-145 Q30,-130 18,-90 Q8,-45 0,0 Z" fill="#5ab068"/>
          <path d="M0,0 Q15,-60 25,-130" stroke="#2a5544" stroke-width="1.5" fill="none"/>
        </g>
        <g transform="translate(100,200) rotate(0)">
          <path d="M0,0 Q-3,-50 -8,-110 Q-3,-130 0,-140 Q3,-130 8,-110 Q3,-50 0,0 Z" fill="#7ecc66"/>
        </g>
        <!-- bird of paradise flower -->
        <g transform="translate(100,180)">
          <!-- spathe (boat) -->
          <path d="M-5,0 Q-25,-15 -15,-25 Q5,-22 15,-30 Q35,-25 30,-10 Q5,-5 -5,0 Z" fill="#3d7e5c"/>
          <!-- orange bracts -->
          <path d="M0,-15 Q-8,-35 -3,-50 Q3,-45 8,-25 Q3,-18 0,-15 Z" fill="#ff8a3a"/>
          <path d="M5,-12 Q-2,-40 5,-58 Q12,-50 14,-30 Q10,-20 5,-12 Z" fill="#ff6e1f"/>
          <path d="M12,-10 Q8,-35 18,-48 Q22,-40 22,-25 Q18,-15 12,-10 Z" fill="#ff8a3a"/>
          <!-- blue accent -->
          <path d="M2,-25 Q5,-35 10,-32 Q8,-28 2,-25 Z" fill="#4477e0"/>
        </g>
      </svg>
    </div>

    <!-- Zone 1: Hibiscus on right -->
    <div class="plant" style="top: 115vh; left: 88%; width: 22vh; height: 30vh;">
      <svg viewBox="0 0 200 250">
        <!-- stem with leaves -->
        <path d="M100,250 Q95,180 100,120" stroke="#3d7e5c" stroke-width="3" fill="none"/>
        <g transform="translate(100,180)">
          <path d="M0,0 Q-25,-5 -35,-20 Q-25,-30 -10,-25 Q-3,-15 0,0 Z" fill="#5ab068"/>
        </g>
        <g transform="translate(95,150)">
          <path d="M0,0 Q25,-5 35,-20 Q25,-30 10,-25 Q3,-15 0,0 Z" fill="#7ecc66"/>
        </g>
        <!-- hibiscus flower -->
        <g transform="translate(100,100)">
          <!-- 5 petals -->
          <path d="M0,0 Q-30,-15 -45,-45 Q-50,-65 -30,-60 Q-15,-40 0,0 Z" fill="#ff5078"/>
          <path d="M0,0 Q15,-30 35,-50 Q55,-55 50,-30 Q40,-15 0,0 Z" fill="#ff5078"/>
          <path d="M0,0 Q35,-5 55,15 Q60,35 35,30 Q15,15 0,0 Z" fill="#ff7090"/>
          <path d="M0,0 Q15,30 5,55 Q-15,60 -10,35 Q-3,15 0,0 Z" fill="#ff5078"/>
          <path d="M0,0 Q-30,20 -55,15 Q-60,-5 -40,-10 Q-20,-5 0,0 Z" fill="#ff7090"/>
          <!-- yellow center -->
          <circle cx="0" cy="0" r="6" fill="#ffe066"/>
          <!-- stamen -->
          <line x1="0" y1="0" x2="3" y2="-12" stroke="#ff8a3a" stroke-width="1.5"/>
        </g>
      </svg>
    </div>

    <!-- Zone 2: Big monstera leaf left -->
    <div class="plant" style="top: 180vh; left: 8%; width: 32vh; height: 32vh;">
      <svg viewBox="0 0 280 280">
        <g transform="translate(140,40) rotate(-15)">
          <path d="M0,0 Q-2,40 -1,80" stroke="#3d7e5c" stroke-width="3" fill="none"/>
          <path d="M-1,80 Q-90,90 -125,125 Q-145,170 -125,215 Q-95,240 -50,245 Q0,250 50,245 Q95,240 125,215 Q145,170 125,125 Q90,90 1,80 Z" fill="#5ab068"/>
          <path d="M-50,245 Q-65,210 -55,170" stroke="#2a5544" stroke-width="2.5" fill="none" opacity="0.7"/>
          <path d="M50,245 Q65,210 55,170" stroke="#2a5544" stroke-width="2.5" fill="none" opacity="0.7"/>
          <path d="M-95,235 Q-110,200 -100,160" stroke="#2a5544" stroke-width="2" fill="none" opacity="0.6"/>
          <path d="M95,235 Q110,200 100,160" stroke="#2a5544" stroke-width="2" fill="none" opacity="0.6"/>
          <ellipse cx="-30" cy="155" rx="8" ry="5" fill="#2a8458"/>
          <ellipse cx="30" cy="155" rx="8" ry="5" fill="#2a8458"/>
          <ellipse cx="-70" cy="180" rx="6" ry="4" fill="#2a8458"/>
          <ellipse cx="70" cy="180" rx="6" ry="4" fill="#2a8458"/>
          <path d="M0,80 Q1,160 2,235" stroke="#3d7e5c" stroke-width="2" fill="none"/>
        </g>
      </svg>
    </div>

    <!-- Zone 2: Plumeria/frangipani right -->
    <div class="plant" style="top: 180vh; left: 92%; width: 20vh; height: 26vh;">
      <svg viewBox="0 0 200 250">
        <!-- stem -->
        <path d="M100,250 L100,150" stroke="#3d7e5c" stroke-width="3" fill="none"/>
        <!-- leaves -->
        <ellipse cx="80" cy="180" rx="22" ry="8" fill="#4ea554" transform="rotate(-25 80 180)"/>
        <ellipse cx="120" cy="170" rx="20" ry="7" fill="#5ab068" transform="rotate(20 120 170)"/>
        <!-- plumeria cluster -->
        <g transform="translate(100,120)">
          <!-- flower 1 -->
          <g transform="translate(-15,-15)">
            <ellipse cx="0" cy="-10" rx="10" ry="14" fill="#fffaf0"/>
            <ellipse cx="-10" cy="-3" rx="10" ry="14" fill="#fffaf0" transform="rotate(72 -10 -3)"/>
            <ellipse cx="-5" cy="11" rx="10" ry="14" fill="#fffaf0" transform="rotate(144 -5 11)"/>
            <ellipse cx="8" cy="8" rx="10" ry="14" fill="#fffaf0" transform="rotate(-144 8 8)"/>
            <ellipse cx="9" cy="-7" rx="10" ry="14" fill="#fffaf0" transform="rotate(-72 9 -7)"/>
            <circle cx="0" cy="0" r="4" fill="#ffd23f"/>
          </g>
          <!-- flower 2 -->
          <g transform="translate(20,5) scale(0.85)">
            <ellipse cx="0" cy="-10" rx="10" ry="14" fill="#fffaf0"/>
            <ellipse cx="-10" cy="-3" rx="10" ry="14" fill="#fffaf0" transform="rotate(72 -10 -3)"/>
            <ellipse cx="-5" cy="11" rx="10" ry="14" fill="#fffaf0" transform="rotate(144 -5 11)"/>
            <ellipse cx="8" cy="8" rx="10" ry="14" fill="#fffaf0" transform="rotate(-144 8 8)"/>
            <ellipse cx="9" cy="-7" rx="10" ry="14" fill="#fffaf0" transform="rotate(-72 9 -7)"/>
            <circle cx="0" cy="0" r="4" fill="#ffd23f"/>
          </g>
        </g>
      </svg>
    </div>

    <!-- Zone 3: Banana leaves arching -->
    <div class="plant" style="top: 245vh; left: 10%; width: 35vh; height: 40vh;">
      <svg viewBox="0 0 300 350">
        <path d="M150,350 L155,150 L165,150 L160,350 Z" fill="#2a5544"/>
        <g transform="translate(160,150) rotate(-30)">
          <path d="M0,0 Q-30,-40 -90,-75 Q-160,-100 -210,-105 Q-225,-90 -215,-75 Q-170,-50 -110,-30 Q-50,-12 0,0 Z" fill="#4ea554"/>
          <path d="M0,0 Q-90,-55 -210,-105" stroke="#2a5544" stroke-width="2" fill="none"/>
          <g stroke="#2a5544" stroke-width="0.8" fill="none" opacity="0.5">
            <path d="M-30,-15 Q-60,-30 -90,-45"/>
            <path d="M-70,-30 Q-100,-50 -130,-65"/>
            <path d="M-110,-50 Q-140,-65 -170,-80"/>
          </g>
        </g>
        <g transform="translate(160,150) rotate(20)">
          <path d="M0,0 Q30,-40 90,-75 Q160,-100 210,-105 Q225,-90 215,-75 Q170,-50 110,-30 Q50,-12 0,0 Z" fill="#5ab068"/>
          <path d="M0,0 Q90,-55 210,-105" stroke="#2a5544" stroke-width="2" fill="none"/>
        </g>
      </svg>
    </div>

    <!-- Zone 3: Anthurium right -->
    <div class="plant" style="top: 245vh; left: 90%; width: 18vh; height: 22vh;">
      <svg viewBox="0 0 200 200">
        <!-- leaves -->
        <ellipse cx="80" cy="160" rx="30" ry="18" fill="#4ea554" transform="rotate(-20 80 160)"/>
        <ellipse cx="120" cy="150" rx="32" ry="20" fill="#3d9a62" transform="rotate(15 120 150)"/>
        <!-- anthurium spathe -->
        <g transform="translate(100,90)">
          <path d="M0,0 Q-35,-15 -45,-40 Q-30,-55 0,-50 Q30,-55 45,-40 Q35,-15 0,0 Z" fill="#e8516e"/>
          <path d="M0,-30 Q5,-25 10,-10 Q5,-5 0,-8 Z" fill="#ffd23f"/>
        </g>
      </svg>
    </div>

    <!-- Zone 4: Heliconia (services area) -->
    <div class="plant" style="top: 310vh; left: 8%; width: 22vh; height: 45vh;">
      <svg viewBox="0 0 200 400">
        <path d="M100,400 L100,180" stroke="#3d7e5c" stroke-width="4" fill="none"/>
        <g transform="translate(100,250)">
          <path d="M-2,0 Q-18,18 -10,32 Q6,38 10,22 Q6,12 -2,0 Z" fill="#ff5547"/>
          <path d="M-2,32 Q-18,50 -10,64 Q6,70 10,54 Q6,44 -2,32 Z" fill="#ff8a3a"/>
          <path d="M-2,64 Q-18,82 -10,96 Q6,102 10,86 Q6,76 -2,64 Z" fill="#ff5547"/>
          <path d="M-2,96 Q-18,114 -10,128 Q6,134 10,118 Q6,108 -2,96 Z" fill="#ff8a3a"/>
          <path d="M-2,128 Q-18,146 -10,160 Q6,166 10,150 Q6,140 -2,128 Z" fill="#ff4030"/>
          <ellipse cx="0" cy="6" rx="3" ry="2" fill="#ffe066"/>
          <ellipse cx="0" cy="38" rx="3" ry="2" fill="#ffe066"/>
          <ellipse cx="0" cy="70" rx="3" ry="2" fill="#ffe066"/>
        </g>
        <g transform="translate(100,180) rotate(-25)">
          <path d="M0,0 Q20,-60 45,-130 Q55,-160 50,-180 Q35,-160 20,-100 Q8,-50 0,0 Z" fill="#4ea554"/>
        </g>
        <g transform="translate(100,180) rotate(30)">
          <path d="M0,0 Q-20,-60 -45,-130 Q-55,-160 -50,-180 Q-35,-160 -20,-100 Q-8,-50 0,0 Z" fill="#5ab068"/>
        </g>
      </svg>
    </div>

    <!-- Zone 4: Bromeliad cluster right -->
    <div class="plant" style="top: 310vh; left: 92%; width: 24vh; height: 28vh;">
      <svg viewBox="0 0 220 220">
        <g transform="translate(110,170)">
          <path d="M0,0 L-30,-60 L-18,-66 L-6,-18 Z" fill="#4ea554"/>
          <path d="M0,0 L30,-60 L18,-66 L6,-18 Z" fill="#4ea554"/>
          <path d="M0,0 L-50,-50 L-40,-58 L-15,-15 Z" fill="#5ab068"/>
          <path d="M0,0 L50,-50 L40,-58 L15,-15 Z" fill="#5ab068"/>
          <path d="M0,0 L-20,-85 L-8,-88 L-3,-25 Z" fill="#7ecc66"/>
          <path d="M0,0 L20,-85 L8,-88 L3,-25 Z" fill="#7ecc66"/>
          <path d="M0,0 L-8,-95 L0,-100 L3,-30 Z" fill="#88c468"/>
          <ellipse cx="0" cy="-15" rx="9" ry="14" fill="#ff4060"/>
          <ellipse cx="0" cy="-20" rx="5" ry="9" fill="#ffd544"/>
        </g>
        <g transform="translate(60,180) scale(0.6)">
          <path d="M0,0 L-30,-60 L-18,-66 L-6,-18 Z" fill="#5ab068"/>
          <path d="M0,0 L30,-60 L18,-66 L6,-18 Z" fill="#5ab068"/>
          <path d="M0,0 L-20,-85 L-8,-88 L-3,-25 Z" fill="#88c468"/>
          <path d="M0,0 L20,-85 L8,-88 L3,-25 Z" fill="#88c468"/>
          <ellipse cx="0" cy="-15" rx="9" ry="14" fill="#e8516e"/>
        </g>
      </svg>
    </div>

    <!-- Zone 5: Palm fronds (outcomes area) -->
    <div class="plant" style="top: 375vh; left: 6%; width: 28vh; height: 50vh;">
      <svg viewBox="0 0 250 450">
        <path d="M120,450 L122,150 L128,150 L130,450 Z" fill="#2a5544"/>
        <g transform="translate(125,150)">
          <g stroke="#3d7e5c" stroke-width="2" fill="none">
            <path d="M0,0 Q-40,-15 -90,-25 Q-110,-22 -120,-15"/>
            <path d="M0,0 Q40,-15 90,-25 Q110,-22 120,-15"/>
            <path d="M0,0 Q-30,-50 -70,-80 Q-90,-90 -100,-85"/>
            <path d="M0,0 Q30,-50 70,-80 Q90,-90 100,-85"/>
            <path d="M0,0 Q-15,-70 -30,-130 Q-40,-145 -50,-145"/>
            <path d="M0,0 Q15,-70 30,-130 Q40,-145 50,-145"/>
          </g>
          <g fill="#5ab068">
            <path d="M-3,-2 Q-40,-18 -90,-25 Q-50,-8 -3,-3 Z"/>
            <path d="M3,-2 Q40,-18 90,-25 Q50,-8 3,-3 Z"/>
            <path d="M-3,-12 Q-30,-50 -70,-80 Q-35,-35 -3,-12 Z"/>
            <path d="M3,-12 Q30,-50 70,-80 Q35,-35 3,-12 Z"/>
          </g>
          <g fill="#4ea554">
            <path d="M-3,-25 Q-15,-70 -30,-130 Q-15,-65 -3,-22 Z"/>
            <path d="M3,-25 Q15,-70 30,-130 Q15,-65 3,-22 Z"/>
          </g>
        </g>
      </svg>
    </div>

    <!-- Zone 5: Big monstera right -->
    <div class="plant" style="top: 375vh; left: 92%; width: 30vh; height: 32vh;">
      <svg viewBox="0 0 280 280">
        <g transform="translate(140,40) rotate(20) scale(1.05)">
          <path d="M0,0 Q2,40 1,80" stroke="#3d7e5c" stroke-width="3" fill="none"/>
          <path d="M-1,80 Q-90,90 -125,125 Q-145,170 -125,215 Q-95,240 -50,245 Q0,250 50,245 Q95,240 125,215 Q145,170 125,125 Q90,90 1,80 Z" fill="#3d9a62"/>
          <path d="M-50,245 Q-65,210 -55,170" stroke="#2a5544" stroke-width="2.5" fill="none" opacity="0.7"/>
          <path d="M50,245 Q65,210 55,170" stroke="#2a5544" stroke-width="2.5" fill="none" opacity="0.7"/>
          <ellipse cx="-30" cy="155" rx="9" ry="6" fill="#1d6b4f"/>
          <ellipse cx="30" cy="155" rx="9" ry="6" fill="#1d6b4f"/>
          <ellipse cx="-70" cy="180" rx="7" ry="5" fill="#1d6b4f"/>
          <ellipse cx="70" cy="180" rx="7" ry="5" fill="#1d6b4f"/>
        </g>
      </svg>
    </div>

    <!-- Zone 6: Buttress tree base (positioning area) -->
    <div class="plant" style="top: 440vh; left: 50%; width: 50vh; height: 55vh;">
      <svg viewBox="0 0 500 450">
        <!-- canopy crown above -->
        <ellipse cx="250" cy="80" rx="120" ry="60" fill="#5ab068"/>
        <ellipse cx="180" cy="100" rx="80" ry="45" fill="#4ea554"/>
        <ellipse cx="320" cy="100" rx="80" ry="45" fill="#4ea554"/>
        <ellipse cx="220" cy="50" rx="70" ry="40" fill="#7ecc66"/>
        <ellipse cx="280" cy="50" rx="70" ry="40" fill="#7ecc66"/>
        <!-- trunk -->
        <path d="M220,450 L228,250 Q232,180 235,140 L265,140 Q268,180 272,250 L280,450 Z" fill="#5a4030"/>
        <!-- buttress flares -->
        <path d="M235,250 Q200,310 130,400 Q90,440 70,450 L235,450 Z" fill="#5a4030"/>
        <path d="M265,250 Q300,310 370,400 Q410,440 430,450 L265,450 Z" fill="#5a4030"/>
        <path d="M240,260 Q220,330 190,400 Q175,430 165,450 L250,450 L250,260 Z" fill="#7a5840" opacity="0.8"/>
        <path d="M260,260 Q280,330 310,400 Q325,430 335,450 L250,450 L250,260 Z" fill="#7a5840" opacity="0.8"/>
        <!-- moss accents -->
        <ellipse cx="120" cy="430" rx="40" ry="8" fill="#4ea554" opacity="0.7"/>
        <ellipse cx="380" cy="430" rx="40" ry="8" fill="#4ea554" opacity="0.7"/>
        <ellipse cx="240" cy="280" rx="14" ry="5" fill="#7ecc66" opacity="0.8"/>
      </svg>
    </div>
  </div>

  <!-- ═══ LIGHTS PLANE — sun shafts ═══ -->
  <div class="plane lights" data-rate="0.5">
    <div class="plant" style="top: 100vh; left: 30%; width: 22vh; height: 110vh;">
      <svg viewBox="0 0 100 400" preserveAspectRatio="none">
        <defs>
          <linearGradient id="lg1" x1="0" y1="0" x2="0" y2="1">
            <stop offset="0%" stop-color="#fff5d8" stop-opacity="0.7"/>
            <stop offset="60%" stop-color="#ffe066" stop-opacity="0.2"/>
            <stop offset="100%" stop-color="#ffe066" stop-opacity="0"/>
          </linearGradient>
        </defs>
        <path d="M40,0 L60,0 L80,400 L20,400 Z" fill="url(#lg1)"/>
      </svg>
    </div>
    <div class="plant" style="top: 200vh; left: 65%; width: 18vh; height: 105vh;">
      <svg viewBox="0 0 100 400" preserveAspectRatio="none">
        <defs>
          <linearGradient id="lg2" x1="0" y1="0" x2="0" y2="1">
            <stop offset="0%" stop-color="#fff5d8" stop-opacity="0.55"/>
            <stop offset="60%" stop-color="#ffe066" stop-opacity="0.13"/>
            <stop offset="100%" stop-color="#ffe066" stop-opacity="0"/>
          </linearGradient>
        </defs>
        <path d="M40,0 L60,0 L78,400 L22,400 Z" fill="url(#lg2)"/>
      </svg>
    </div>
    <div class="plant" style="top: 300vh; left: 20%; width: 16vh; height: 100vh;">
      <svg viewBox="0 0 100 400" preserveAspectRatio="none">
        <defs>
          <linearGradient id="lg3" x1="0" y1="0" x2="0" y2="1">
            <stop offset="0%" stop-color="#fff5d8" stop-opacity="0.4"/>
            <stop offset="100%" stop-color="#ffe066" stop-opacity="0"/>
          </linearGradient>
        </defs>
        <path d="M40,0 L60,0 L75,400 L25,400 Z" fill="url(#lg3)"/>
      </svg>
    </div>
    <div class="plant" style="top: 400vh; left: 75%; width: 14vh; height: 95vh;">
      <svg viewBox="0 0 100 400" preserveAspectRatio="none">
        <defs>
          <linearGradient id="lg4" x1="0" y1="0" x2="0" y2="1">
            <stop offset="0%" stop-color="#fff5d8" stop-opacity="0.32"/>
            <stop offset="100%" stop-color="#ffe066" stop-opacity="0"/>
          </linearGradient>
        </defs>
        <path d="M40,0 L60,0 L72,400 L28,400 Z" fill="url(#lg4)"/>
      </svg>
    </div>
  </div>

  <!-- ═══ NEAR PLANE — foreground edges & bridging vine ═══ -->
  <div class="plane near" data-rate="0.92">

    <!-- Drooping leaves at hero corners -->
    <div class="plant" style="top: 70vh; left: 0; transform: translateY(-50%); width: 35vh; height: 35vh;">
      <svg viewBox="0 0 300 300">
        <g transform="translate(0,0) rotate(-15)">
          <path d="M0,0 Q60,40 120,80 Q180,140 200,220 Q190,280 160,310 Q100,300 50,250 Q-10,180 -20,100 Q-15,40 0,0 Z" fill="#5ab068"/>
          <path d="M0,0 Q80,80 160,180 Q190,250 170,300" stroke="#2a5544" stroke-width="2" fill="none" opacity="0.5"/>
        </g>
      </svg>
    </div>

    <div class="plant" style="top: 70vh; left: auto; right: 0; transform: translateY(-50%); width: 38vh; height: 38vh;">
      <svg viewBox="0 0 300 300">
        <g transform="translate(280, 30) rotate(120)">
          <path d="M0,0 Q60,40 120,80 Q180,140 200,220 Q190,280 160,310 Q100,300 50,250 Q-10,180 -20,100 Q-15,40 0,0 Z" fill="#4ea554"/>
        </g>
      </svg>
    </div>

    <!-- Bridging vine LEFT — spans zones 1-5 (pains through outcomes) -->
    <div class="plant" style="top: 326vh; left: 0; transform: translateY(-50%); width: 18vh; height: 380vh;">
      <svg viewBox="0 0 200 2400" preserveAspectRatio="xMidYMid meet">
        <!-- main vine -->
        <path d="M40,-50 Q110,300 60,700 Q120,1100 80,1500 Q140,1900 60,2400" stroke="#3d7e5c" stroke-width="14" fill="none"/>
        <path d="M40,-50 Q110,300 60,700 Q120,1100 80,1500 Q140,1900 60,2400" stroke="#5a4030" stroke-width="6" fill="none"/>
        <!-- secondary vine -->
        <path d="M60,-20 Q40,250 80,550 Q120,850 50,1200 Q90,1550 70,1900 Q100,2200 50,2400" stroke="#2a5544" stroke-width="4" fill="none" opacity="0.85"/>
        <!-- big heart leaves at intervals -->
        <g transform="translate(70, 200) rotate(-20)">
          <path d="M0,0 Q-30,20 -45,55 Q-50,90 -25,110 Q0,120 25,110 Q50,90 45,55 Q30,20 0,0 Z" fill="#5ab068"/>
          <path d="M0,0 Q1,55 2,110" stroke="#2a5544" stroke-width="1.5" fill="none"/>
        </g>
        <!-- pink hibiscus on vine -->
        <g transform="translate(85, 480)">
          <path d="M0,0 Q-22,-10 -32,-32 Q-36,-48 -22,-44 Q-10,-30 0,0 Z" fill="#ff5078"/>
          <path d="M0,0 Q12,-22 28,-38 Q40,-40 36,-22 Q28,-10 0,0 Z" fill="#ff5078"/>
          <path d="M0,0 Q26,0 40,12 Q44,28 26,22 Q12,10 0,0 Z" fill="#ff7090"/>
          <path d="M0,0 Q10,22 0,40 Q-12,44 -10,26 Q-3,12 0,0 Z" fill="#ff5078"/>
          <path d="M0,0 Q-22,15 -40,10 Q-44,-4 -28,-8 Q-15,-4 0,0 Z" fill="#ff7090"/>
          <circle cx="0" cy="0" r="5" fill="#ffe066"/>
        </g>
        <g transform="translate(75, 800) rotate(-30) scale(0.9)">
          <path d="M0,0 Q-30,20 -45,55 Q-50,90 -25,110 Q0,120 25,110 Q50,90 45,55 Q30,20 0,0 Z" fill="#4ea554"/>
        </g>
        <g transform="translate(110, 1100) rotate(-15)">
          <path d="M0,0 Q-30,20 -45,55 Q-50,90 -25,110 Q0,120 25,110 Q50,90 45,55 Q30,20 0,0 Z" fill="#5ab068"/>
        </g>
        <!-- another hibiscus -->
        <g transform="translate(85, 1380) scale(0.85)">
          <path d="M0,0 Q-22,-10 -32,-32 Q-36,-48 -22,-44 Q-10,-30 0,0 Z" fill="#ff5078"/>
          <path d="M0,0 Q12,-22 28,-38 Q40,-40 36,-22 Q28,-10 0,0 Z" fill="#ff5078"/>
          <path d="M0,0 Q26,0 40,12 Q44,28 26,22 Q12,10 0,0 Z" fill="#ff7090"/>
          <path d="M0,0 Q10,22 0,40 Q-12,44 -10,26 Q-3,12 0,0 Z" fill="#ff5078"/>
          <path d="M0,0 Q-22,15 -40,10 Q-44,-4 -28,-8 Q-15,-4 0,0 Z" fill="#ff7090"/>
          <circle cx="0" cy="0" r="5" fill="#ffe066"/>
        </g>
        <g transform="translate(75, 1700) rotate(-25) scale(0.85)">
          <path d="M0,0 Q-30,20 -45,55 Q-50,90 -25,110 Q0,120 25,110 Q50,90 45,55 Q30,20 0,0 Z" fill="#4ea554"/>
        </g>
        <g transform="translate(95, 2050) rotate(-10)">
          <path d="M0,0 Q-30,20 -45,55 Q-50,90 -25,110 Q0,120 25,110 Q50,90 45,55 Q30,20 0,0 Z" fill="#5ab068"/>
        </g>
      </svg>
    </div>

    <!-- Bridging vine RIGHT — spans zones 2-6 -->
    <div class="plant" style="top: 418vh; left: auto; right: 0; transform: translateY(-50%); width: 16vh; height: 360vh;">
      <svg viewBox="0 0 200 2200" preserveAspectRatio="xMidYMid meet">
        <path d="M150,-50 Q80,250 130,500 Q180,800 100,1100 Q160,1400 120,1700 Q140,1950 150,2200" stroke="#3d7e5c" stroke-width="12" fill="none"/>
        <path d="M150,-50 Q80,250 130,500 Q180,800 100,1100 Q160,1400 120,1700 Q140,1950 150,2200" stroke="#5a4030" stroke-width="5" fill="none"/>
        <g transform="translate(115, 280) rotate(20)">
          <path d="M0,0 Q-25,15 -38,45 Q-42,75 -20,92 Q0,100 20,92 Q42,75 38,45 Q25,15 0,0 Z" fill="#4ea554"/>
        </g>
        <!-- bromeliad on vine -->
        <g transform="translate(155, 580) rotate(15) scale(0.7)">
          <path d="M0,0 L-25,-50 L-15,-55 L-5,-15 Z" fill="#5ab068"/>
          <path d="M0,0 L25,-50 L15,-55 L5,-15 Z" fill="#5ab068"/>
          <path d="M0,0 L-15,-70 L-5,-72 L-2,-20 Z" fill="#7ecc66"/>
          <path d="M0,0 L15,-70 L5,-72 L2,-20 Z" fill="#7ecc66"/>
          <ellipse cx="0" cy="-15" rx="6" ry="10" fill="#ff4060"/>
        </g>
        <g transform="translate(125, 880) rotate(25) scale(0.85)">
          <path d="M0,0 Q-25,15 -38,45 Q-42,75 -20,92 Q0,100 20,92 Q42,75 38,45 Q25,15 0,0 Z" fill="#5ab068"/>
        </g>
        <!-- orchid -->
        <g transform="translate(140, 1200)">
          <ellipse cx="0" cy="-10" rx="11" ry="14" fill="#ec7eb5"/>
          <ellipse cx="-12" cy="-3" rx="10" ry="13" fill="#ec7eb5" transform="rotate(72 -12 -3)"/>
          <ellipse cx="-6" cy="13" rx="11" ry="14" fill="#ec7eb5" transform="rotate(144 -6 13)"/>
          <ellipse cx="10" cy="10" rx="11" ry="14" fill="#ec7eb5" transform="rotate(-144 10 10)"/>
          <ellipse cx="11" cy="-9" rx="11" ry="14" fill="#ec7eb5" transform="rotate(-72 11 -9)"/>
          <ellipse cx="0" cy="0" rx="5" ry="6" fill="#fffaf0"/>
          <circle cx="0" cy="0" r="2.5" fill="#b266d2"/>
        </g>
        <g transform="translate(130, 1500) rotate(20) scale(0.85)">
          <path d="M0,0 Q-25,15 -38,45 Q-42,75 -20,92 Q0,100 20,92 Q42,75 38,45 Q25,15 0,0 Z" fill="#4ea554"/>
        </g>
        <g transform="translate(140, 1850) rotate(15)">
          <path d="M0,0 Q-25,15 -38,45 Q-42,75 -20,92 Q0,100 20,92 Q42,75 38,45 Q25,15 0,0 Z" fill="#5ab068"/>
        </g>
      </svg>
    </div>

    <!-- Foreground palm at bottom (positioning zone) -->
    <div class="plant" style="top: 602vh; left: -8vw; transform: translateY(-50%); width: 50vh; height: 70vh;">
      <svg viewBox="0 0 400 600">
        <g transform="translate(50, 580) rotate(-30)">
          <path d="M0,0 L0,-500" stroke="#5a4030" stroke-width="4" fill="none"/>
          <g fill="#5ab068">
            <path d="M-3,-50 Q-30,-50 -80,-55 Q-50,-45 -3,-45 Z"/>
            <path d="M-3,-100 Q-30,-100 -85,-110 Q-55,-95 -3,-95 Z"/>
            <path d="M-3,-150 Q-35,-150 -90,-165 Q-60,-145 -3,-145 Z"/>
            <path d="M-3,-200 Q-35,-205 -95,-220 Q-60,-198 -3,-195 Z"/>
            <path d="M-3,-250 Q-35,-260 -90,-275 Q-60,-250 -3,-245 Z"/>
            <path d="M-3,-300 Q-30,-310 -80,-325 Q-50,-300 -3,-295 Z"/>
            <path d="M-3,-350 Q-25,-360 -65,-370 Q-40,-345 -3,-345 Z"/>
            <path d="M3,-50 Q30,-50 80,-55 Q50,-45 3,-45 Z" fill="#4ea554"/>
            <path d="M3,-100 Q30,-100 85,-110 Q55,-95 3,-95 Z" fill="#4ea554"/>
            <path d="M3,-150 Q35,-150 90,-165 Q60,-145 3,-145 Z" fill="#4ea554"/>
            <path d="M3,-200 Q35,-205 95,-220 Q60,-198 3,-195 Z" fill="#4ea554"/>
            <path d="M3,-250 Q35,-260 90,-275 Q60,-250 3,-245 Z" fill="#4ea554"/>
          </g>
        </g>
      </svg>
    </div>

    <!-- Foreground hibiscus bottom right -->
    <div class="plant" style="top: 602vh; left: auto; right: 0; transform: translateY(-50%); width: 32vh; height: 40vh;">
      <svg viewBox="0 0 280 350">
        <path d="M260,350 Q230,250 220,150" stroke="#3d7e5c" stroke-width="3" fill="none"/>
        <ellipse cx="190" cy="280" rx="32" ry="14" fill="#5ab068" transform="rotate(-30 190 280)"/>
        <ellipse cx="240" cy="220" rx="28" ry="12" fill="#7ecc66" transform="rotate(20 240 220)"/>
        <ellipse cx="200" cy="200" rx="30" ry="13" fill="#4ea554" transform="rotate(-15 200 200)"/>
        <g transform="translate(220, 130)">
          <path d="M0,0 Q-35,-18 -55,-50 Q-60,-75 -35,-72 Q-18,-50 0,0 Z" fill="#ff5078"/>
          <path d="M0,0 Q18,-35 45,-58 Q68,-65 60,-38 Q48,-18 0,0 Z" fill="#ff5078"/>
          <path d="M0,0 Q40,-5 65,18 Q70,42 42,38 Q18,18 0,0 Z" fill="#ff7090"/>
          <path d="M0,0 Q18,38 5,65 Q-20,72 -12,42 Q-3,18 0,0 Z" fill="#ff5078"/>
          <path d="M0,0 Q-38,25 -68,18 Q-72,-8 -50,-12 Q-25,-5 0,0 Z" fill="#ff7090"/>
          <circle cx="0" cy="0" r="7" fill="#ffe066"/>
          <line x1="0" y1="0" x2="4" y2="-15" stroke="#ff8a3a" stroke-width="2"/>
        </g>
      </svg>
    </div>
  </div>

  <!-- ═══ VIGNETTE ═══ -->
  <div class="vignette"></div>

  <!-- ═══ CONTENT ═══ -->
  <div class="content">

    <!-- ZONE 0: HERO -->
    <section class="zone hero">
      <div class="card">
        <span class="brand">The Capabilities Lab</span>
        <h1>Human-Centered<br><em>AI Enablement</em></h1>
        <p class="tagline">We help mission-driven organizations adopt AI without losing the trust, judgment, empathy, and human connection that make their work valuable.</p>
      </div>
      <div class="scroll-cue">↓ The Premise</div>
    </section>

    <!-- ZONE 1: THESIS -->
    <section class="zone">
      <div class="card">
        <span class="eyebrow">The Premise</span>
        <h2>Most AI consulting installs <em>tools</em>.<br>We do something different.</h2>
        <p class="body">We help organizations preserve trust, judgment, empathy, and human connection while redesigning work around AI. That isn't soft — it's a business performance issue. Poorly implemented AI creates employee anxiety, mistrust, inconsistent customer experience, brand risk, and adoption failure.</p>
        <div class="stat">
          <span class="num">~30%</span>
          <p class="text">of workers now use AI frequently. About half seldom or never use it — citing concerns about ethics, privacy, accuracy, and job loss.</p>
          <span class="source">— Gallup / Associated Press, 2026</span>
        </div>
        <p class="body">The market isn't just asking <em>"What AI tools should we buy?"</em> It's asking, <strong>"How do we get people to use this responsibly, confidently, and without damaging the culture?"</strong></p>
      </div>
    </section>

    <!-- ZONE 2: FIVE PAINS -->
    <section class="zone">
      <div class="card wide">
        <span class="eyebrow">What we hear</span>
        <h2>The five problems<br>we solve</h2>
        <ol class="pains">
          <li><span class="num">1</span><span class="text"><strong>Adoption is creating fear, resistance, or uneven use.</strong> Leaders need to communicate AI as augmentation, not just automation.</span></li>
          <li><span class="num">2</span><span class="text"><strong>Customer, student, and patient experience is becoming colder.</strong> Teams need clear rules for where AI supports human connection — and where humans must remain central.</span></li>
          <li><span class="num">3</span><span class="text"><strong>Managers don't know how to lead AI-enabled teams.</strong> They need new skills in delegation, human review, coaching, and responsible escalation.</span></li>
          <li><span class="num">4</span><span class="text"><strong>AI governance is too technical.</strong> Privacy, security, and compliance get attention. Tone, empathy, bias, escalation, and transparency do not.</span></li>
          <li><span class="num">5</span><span class="text"><strong>The organization lacks a change strategy.</strong> Empathy is essential to AI transformation. Most rollouts treat it as optional.</span></li>
        </ol>
      </div>
    </section>

    <!-- ZONE 3: WHO WE SERVE -->
    <section class="zone">
      <div class="card">
        <span class="eyebrow">Where we focus</span>
        <h2>Mission-driven<br>organizations</h2>
        <p class="body">These sectors are relationship-heavy, labor-constrained, budget-pressured, and culturally sensitive. They need AI — but they cannot afford to sound robotic, extractive, or impersonal.</p>
        <div class="sectors">
          <div class="sector">— Higher Education</div>
          <div class="sector">— Nonprofits</div>
          <div class="sector">— Healthcare Education</div>
          <div class="sector">— Mission-Driven Orgs</div>
        </div>
      </div>
    </section>

    <!-- ZONE 4: SERVICES -->
    <section class="zone">
      <div class="card wide">
        <span class="eyebrow">How we work</span>
        <h2>Six engagements</h2>
        <div class="services">
          <div class="service">
            <h3>AI Trust &amp; Readiness Assessment</h3>
            <p>Evaluate where AI is being adopted, where staff feel threatened, where experience could degrade, and where governance is weak.</p>
          </div>
          <div class="service">
            <h3>Emotionally Intelligent AI Enablement</h3>
            <p>Workshops that train leaders and teams to use AI while preserving voice, care, judgment, and accountability.</p>
          </div>
          <div class="service">
            <h3>Human-in-the-Loop Workflow Design</h3>
            <p>Map which decisions AI can support, which require human review, and which must remain human-led.</p>
          </div>
          <div class="service">
            <h3>AI Communication &amp; Change Narrative</h3>
            <p>Help executives explain AI in ways that reduce fear and increase adoption.</p>
          </div>
          <div class="service">
            <h3>Experience AI Guardrails</h3>
            <p>Standards for tone, escalation, transparency, empathy, personalization, and intervention.</p>
          </div>
          <div class="service">
            <h3>Manager Playbooks for AI-Enabled Teams</h3>
            <p>Coach managers through adoption, redesign roles, measure quality, and protect morale.</p>
          </div>
        </div>
      </div>
    </section>

    <!-- ZONE 5: OUTCOMES -->
    <section class="zone">
      <div class="card">
        <span class="eyebrow">What buyers pay for</span>
        <h2>What this work<br><em>delivers</em></h2>
        <p class="body">We don't sell &ldquo;emotional intelligence in AI&rdquo; as a phrase. We sell the operational outcomes it produces.</p>
        <div class="outcomes">
          <div class="outcome">— Better AI adoption</div>
          <div class="outcome">— Lower employee resistance</div>
          <div class="outcome">— More trusted AI workflows</div>
          <div class="outcome">— Better student &amp; customer experience</div>
          <div class="outcome">— Reduced reputational risk</div>
          <div class="outcome">— Improved manager readiness</div>
          <div class="outcome">— Human-centered governance</div>
          <div class="outcome">— Stronger implementation outcomes</div>
        </div>
      </div>
    </section>

    <!-- ZONE 6: POSITIONING / CTA -->
    <section class="zone coda">
      <div class="card">
        <span class="eyebrow">How we put it</span>
        <p class="quote">We help organizations turn AI adoption into trusted operational change &mdash; by aligning technology, people, workflows, governance, and emotionally intelligent leadership.</p>
        <a href="#contact" class="cta">Get in touch</a>
        <span class="colophon">The Capabilities Lab</span>
      </div>
    </section>

  </div>

</div>

  <script src="js/parallax.js"></script>
</body>
</html>
