<svg width="1180" height="610" viewBox="0 0 1180 610" fill="none" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink">
  <defs>
    <!-- Gradients -->
    <linearGradient id="darkAccentGradient" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" stop-color="#7C3AED"/>
      <stop offset="50%" stop-color="#22D3EE"/>
      <stop offset="100%" stop-color="#10B981"/>
      <animate attributeName="x1" from="0%" to="100%" dur="8s" repeatCount="indefinite"/>
      <animate attributeName="x2" from="100%" to="200%" dur="8s" repeatCount="indefinite"/>
    </linearGradient>

    <linearGradient id="darkAsciiGradient" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" stop-color="#06B6D4"/>
      <stop offset="100%" stop-color="#7C3AED"/>
      <animate attributeName="x1" from="0%" to="100%" dur="6s" repeatCount="indefinite"/>
      <animate attributeName="x2" from="100%" to="200%" dur="6s" repeatCount="indefinite"/>
    </linearGradient>

    <radialGradient id="darkBackgroundGlow" cx="50%" cy="50%" r="50%">
      <stop offset="0%" stop-color="#0EA5E9" stop-opacity="0.2"/>
      <stop offset="100%" stop-color="#7C3AED" stop-opacity="0"/>
    </radialGradient>

    <filter id="glassmorphism" x="-50%" y="-50%" width="200%" height="200%">
      <feGaussianBlur in="SourceGraphic" stdDeviation="8" result="blur"/>
      <feOffset in="blur" dx="0" dy="4" result="offsetBlur"/>
      <feFlood flood-color="rgba(0,0,0,0.2)" result="offsetcolor"/>
      <feComposite in="offsetcolor" in2="offsetBlur" operator="in" result="offsetblur"/>
      <feFlood flood-color="rgba(255,255,255,0.05)" result="glowcolor"/>
      <feComposite in="glowcolor" in2="SourceAlpha" operator="in" result="glowblur"/>
      <feMerge>
        <feMergeNode in="offsetblur"/>
        <feMergeNode in="glowblur"/>
        <feMergeNode in="SourceGraphic"/>
      </feMerge>
    </filter>

    <pattern id="scanlines" x="0" y="0" width="100%" height="2" patternUnits="userSpaceOnUse">
      <line x1="0" y1="0" x2="100%" y2="0" stroke="rgba(255,255,255,0.03)" stroke-width="1"/>
    </pattern>
  </defs>

  <!-- Background -->
  <rect width="1180" height="610" rx="20" fill="#030712"/>
  
  <!-- Background Glow -->
  <circle cx="590" cy="305" r="400" fill="url(#darkBackgroundGlow)">
    <animate attributeName="r" from="350" to="450" dur="6s" repeatCount="indefinite"/>
  </circle>

  <!-- Scanlines Overlay -->
  <rect width="1180" height="610" rx="20" fill="url(#scanlines)" opacity="0.5">
    <animate attributeName="opacity" from="0.3" to="0.6" dur="3s" repeatCount="indefinite"/>
  </rect>

  <!-- Left Section (ASCII Art) -->
  <g>
    <rect x="20" y="20" width="448.4" height="570" rx="10" fill="#0F172A" stroke="rgba(255,255,255,.08)" stroke-width="1" filter="url(#glassmorphism)">
      <animate attributeName="stroke" from="rgba(255,255,255,.08)" to="rgba(124,58,237,.2)" dur="4s" repeatCount="indefinite"/>
    </rect>
    
    <g transform="translate(0, 0)">
      <text x="40" y="60" font-family="'Courier New', monospace" font-size="7" fill="url(#darkAsciiGradient)" style="white-space: pre; letter-spacing: 0.5px; line-height: 1.2;">
                    ::-+#+-::.                    
                  ... .+#*.  --.                  
                ..  ..:+*+-. ::--.                
               ..  ::.      .::. :.               
            .  . .:           .:. :.              
           .:....               .: .:             
           :=::.                  . ..            
           +-=:                    :. .           
          .-::         :.           -...          
          ..:         .::.          .. .          
         ...         .: .-.           ...         
         .-:         .. ..:           . ..        
          -.         :   .::          .  .        
          .          :    .:.         :-=-:       
       .: .         ..     ::         .::.:       
       .-           .      .:         .    .      
      :.:           .       ..        .  ...      
      .::.          .       .:        :   .       
     : .  .        ..        :        :   .       
     =..           .         ..       .    .      
    ...            .          .            ..:    
                   .          ..           -*=    
     .            ..          ..           :==.   
   ..             ..           :           . .:   
   ..             ..           ..          :  .   
   .             ..             .          .      
  ..   .         ..             .       .         
  .             ...             ..             .  
                .:.              .      .     ..  
                .-.              .     .    . :.  
 ..             .-               ..         = ::  
 .:             ::                .        .= .:  
  .             :                 .  .     --. .  
 .:  ..        .:                 :.      .=..    
 .   ..        .                  .       =-.:    
              .:                 ..    . :+:.:    
.. .     :    ..                 .:.    :.--    . 
..    . .:    ..                ..:.     .--    : 
 .      :.   ..:.               ::..      ::    ..
..     . .   . .:               :-..      ..    ..
.   .:..      .-:                .:.     :- .   ..
.   ...   ....::                  .:     :. ..  ..
:    .      ..:                    ..      .-:  .:
-           .-.                     .     . .:. ..
-     ..    .:       =       -       .    .  .. ..
-      .:.  :.      -=       +-      .     .... .-
-      . ...:       +-       -=      ....   :-: .-
-         .:.      .=:       :=.      ...   .:   .
:         .:       :::       -::      .:.  ::.   .
.         ..       -.- :=+=. -.:      .:.  :-.    
.         .        - --=. :+.- -       :. ...     
.         .       .- :*:   :*: ::      ....       
.         .       --  -.   := .--      ..-.       
:        .        --. :.   .. .--      .:-       .
:        .        ---.=     = --:       :.       :
:        .        :-++:     -*=-:       ..       :
.                 .-=        .=-.       :.       .
.                 .:=.   .   .=:        -.      . 
..                 :.:       :.-        :.      . 
..                 :-.=: . :=:-:        ..        
..                  - .+=.=+. =         ..       .
..                  -  .. .. .:         .       .-
..                  .-- .. .:-.                .==
..                   -:.. .::-                  .:
..                   : -: ::.:                   .
 .                   :.:---.:.                 ...
 ..                   =:-=-:=                  .: 
 ..                   .-...-.                   . 
 ..  .                 =-:--                    . 
 .. ..                 -. ::                    . 
  . ..                 .- -                    .. 
  . ..                  -+:                    :  
  ....                                        .-  
  ....                                        .:  
    .:                                         .  
   ..-                                            
   :.:.                                       .   
   . ..                                      ..   
      .                                     ...   
    . .    .                             ...:.    
    . .   ..                            :-:...    
     . :  :                               . .     
     :::-=-                               : .     
      -+#=.                       .       :.      
      .-- ..                      .       :.      
          :.                      .      ...      
       .  :.                             ..       
          ..                           ....       
        .  .                           :..        
         . ..                         .=..        
         . :.                         =-:         
          .::                        .-=          
           ==  .                    ..:.          
           .::  .          .       ....           
             ..  .                .  .            
                  ..            ..  .             
                   .:.        .:.                 
                     .:-=-:::.--.                 
                   ... .+-   :=:                  
                     .:=*+:::.                    
      </text>
      <animateTransform attributeName="transform" type="translate" from="0 0" to="0 3" dur="4s" repeatCount="indefinite"/>
    </g>
  </g>

  <!-- Right Section (Terminal Window) -->
  <g>
    <rect x="488.4" y="20" width="671.6" height="570" rx="10" fill="#0F172A" stroke="rgba(255,255,255,.08)" stroke-width="1" filter="url(#glassmorphism)">
      <animate attributeName="stroke" from="rgba(255,255,255,.08)" to="rgba(34,211,238,.2)" dur="4s" repeatCount="indefinite"/>
    </rect>

    <!-- Terminal Header -->
    <rect x="488.4" y="20" width="671.6" height="40" rx="10" fill="rgba(255,255,255,0.02)" stroke="rgba(255,255,255,.05)" stroke-width="1"/>
    
    <!-- Terminal Dots -->
    <circle cx="510" cy="40" r="3" fill="#FF6B6B" opacity="0.8"/>
    <circle cx="530" cy="40" r="3" fill="#FFD93D" opacity="0.8"/>
    <circle cx="550" cy="40" r="3" fill="#6BCF7F" opacity="0.8"/>

    <!-- Greeting with typing animation -->
    <text x="520" y="90" font-family="'Segoe UI', sans-serif" font-size="28" font-weight="700" fill="url(#darkAccentGradient)">
      <tspan>Hi 👋</tspan>
      <animate attributeName="opacity" from="0" to="1" dur="0.6s" begin="0s" fill="freeze"/>
    </text>
    
    <text x="520" y="130" font-family="'Segoe UI', sans-serif" font-size="24" font-weight="600" fill="#F8FAFC">
      I'm MrSyntax
      <animate attributeName="opacity" from="0" to="1" dur="0.8s" begin="0.5s" fill="freeze"/>
    </text>

    <!-- Roles with typing animation -->
    <g>
      <!-- Role 1 -->
      <text x="520" y="180" font-family="'Courier New', monospace" font-size="16" fill="#94A3B8">
        <tspan id="role1">Backend Engineer</tspan>
        <animate attributeName="opacity" from="0" to="1" dur="0.6s" begin="1.2s" fill="freeze"/>
      </text>

      <!-- Role 2 -->
      <text x="520" y="205" font-family="'Courier New', monospace" font-size="16" fill="#94A3B8">
        <tspan id="role2">Full Stack Developer</tspan>
        <animate attributeName="opacity" from="0" to="1" dur="0.6s" begin="2s" fill="freeze"/>
      </text>

      <!-- Role 3 -->
      <text x="520" y="230" font-family="'Courier New', monospace" font-size="16" fill="#94A3B8">
        <tspan id="role3">Open Source Contributor</tspan>
        <animate attributeName="opacity" from="0" to="1" dur="0.6s" begin="3s" fill="freeze"/>
      </text>
    </g>

    <!-- Cursor Blink -->
    <rect x="520" y="245" width="2" height="16" fill="#22D3EE">
      <animate attributeName="opacity" from="1" to="0" dur="1s" repeatCount="indefinite" begin="4.15s"/>
    </rect>

    <!-- Info Section -->
    <text x="520" y="310" font-family="'Segoe UI', sans-serif" font-size="13" fill="#F8FAFC">
      <tspan font-weight="600">Location:</tspan>
      <tspan fill="#94A3B8"> Lisboa, Portugal</tspan>
    </text>
    
    <text x="520" y="340" font-family="'Segoe UI', sans-serif" font-size="13" fill="#F8FAFC">
      <tspan font-weight="600">GitHub:</tspan>
      <tspan fill="#22D3EE"> @mrsyntaxdev</tspan>
    </text>

    <!-- Skills Pills -->
    <g>
      <!-- Skill 1 Pill -->
      <rect x="520" y="370" width="70" height="28" rx="14" fill="rgba(34,211,238,0.1)" stroke="rgba(34,211,238,0.3)" stroke-width="1">
        <animate attributeName="stroke" from="rgba(34,211,238,0.3)" to="rgba(34,211,238,0.8)" dur="2s" repeatCount="indefinite"/>
      </rect>
      <text x="555" y="390" font-family="'Segoe UI', sans-serif" font-size="12" fill="#22D3EE" text-anchor="middle" font-weight="600">React</text>

      <!-- Skill 2 Pill -->
      <rect x="600" y="370" width="90" height="28" rx="14" fill="rgba(124,58,237,0.1)" stroke="rgba(124,58,237,0.3)" stroke-width="1">
        <animate attributeName="stroke" from="rgba(124,58,237,0.3)" to="rgba(124,58,237,0.8)" dur="2s" begin="0.3s" repeatCount="indefinite"/>
      </rect>
      <text x="645" y="390" font-family="'Segoe UI', sans-serif" font-size="12" fill="#7C3AED" text-anchor="middle" font-weight="600">TypeScript</text>

      <!-- Skill 3 Pill -->
      <rect x="700" y="370" width="85" height="28" rx="14" fill="rgba(16,185,129,0.1)" stroke="rgba(16,185,129,0.25)" stroke-width="1">
        <animate attributeName="stroke" from="rgba(16,185,129,0.25)" to="rgba(16,185,129,0.6)" dur="2s" begin="0.6s" repeatCount="indefinite"/>
      </rect>
      <text x="742.5" y="390" font-family="'Segoe UI', sans-serif" font-size="12" fill="#10B981" text-anchor="middle" font-weight="600">Node.js</text>
    </g>

    <!-- Social Links -->
    <text x="520" y="460" font-family="'Segoe UI', sans-serif" font-size="13" fill="#94A3B8">
      <tspan font-weight="600">Connect:</tspan>
    </text>
    
    <g>
      <!-- GitHub Link -->
      <text x="520" y="490" font-family="'Segoe UI', sans-serif" font-size="12" fill="#22D3EE" text-decoration="underline">
        github.com/mrsyntaxdev
      </text>
      
      <!-- Portfolio Link -->
      <text x="520" y="520" font-family="'Segoe UI', sans-serif" font-size="12" fill="#22D3EE" text-decoration="underline">
        Portfolio: https://mrsyntax.vercel.app/
      </text>
    </g>

    <!-- Floating Glow Effect -->
    <circle cx="800" cy="200" r="100" fill="url(#darkBackgroundGlow)" opacity="0.3">
      <animate attributeName="r" from="80" to="120" dur="5s" repeatCount="indefinite"/>
      <animate attributeName="opacity" from="0.2" to="0.5" dur="5s" repeatCount="indefinite"/>
    </circle>
  </g>

  <!-- Border Shimmer Animation -->
  <rect x="20" y="20" width="1140" height="570" rx="20" fill="none" stroke="url(#darkAccentGradient)" stroke-width="2" opacity="0.3">
    <animate attributeName="opacity" from="0.1" to="0.4" dur="3s" repeatCount="indefinite"/>
  </rect>

</svg>
