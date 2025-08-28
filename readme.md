<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 400 120" width="100%" height="120">
  <rect width="400" height="120" fill="black" rx="10" />

  <!-- Glowing star -->
  <circle cx="200" cy="60" r="8" fill="pink">
    <animate attributeName="r" values="8;12;8" dur="2s" repeatCount="indefinite" />
    <animate attributeName="opacity" values="1;0.6;1" dur="2s" repeatCount="indefinite" />
  </circle>

  <!-- Floating petal -->
  <ellipse cx="100" cy="90" rx="10" ry="5" fill="lightpink">
    <animateTransform attributeName="transform"
      type="translate"
      values="0,0; 200,-40; 400,0"
      dur="6s"
      repeatCount="indefinite"/>
    <animateTransform attributeName="transform"
      additive="sum"
      type="rotate"
      values="0 100 90; 360 100 90"
      dur="6s"
      repeatCount="indefinite"/>
  </ellipse>

  <!-- Another floating petal -->
  <ellipse cx="300" cy="100" rx="12" ry="6" fill="pink">
    <animateTransform attributeName="transform"
      type="translate"
      values="0,0; -200,-60; -400,0"
      dur="7s"
      repeatCount="indefinite"/>
    <animateTransform attributeName="transform"
      additive="sum"
      type="rotate"
      values="0 300 100; -360 300 100"
      dur="7s"
      repeatCount="indefinite"/>
  </ellipse>
</svg>
