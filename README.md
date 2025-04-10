# jv-gym-website
"Jv-Gym to platforma, która wspiera pasjonatów fitnessu. Oferujemy spersonalizowane plany treningowe, diety 1:1 oraz akcesoria sportowe, które pomagają w osiąganiu lepszych wyników i motywacji. Z nami rozwój w sporcie staje się prostszy i bardziej efektywny."
<head>
  ...
  <style>
    body {
      font-family: 'Montserrat', sans-serif;
    }
    .hero-section {
      background-image: linear-gradient(to right, rgba(0, 0, 0, 0.85), rgba(0, 0, 0, 0.4)), url('https://public.readdy.ai/ai/img_res/a727bed27773e1cad1bf73c609b4b8d7.jpg');
      background-size: cover;
      background-position: center;
    }
    .custom-checkbox {
      appearance: none;
      width: 20px;
      height: 20px;
      border: 2px solid #d32f2f;
      border-radius: 4px;
      position: relative;
      cursor: pointer;
    }
    .custom-checkbox:checked {
      background-color: #d32f2f;
    }
    .custom-checkbox:checked::after {
      content: "";
      position: absolute;
      top: 2px;
      left: 6px;
      width: 6px;
      height: 12px;
      border: solid white;
      border-width: 0 2px 2px 0;
      transform: rotate(45deg);
    }
    .text-logo {
      text-shadow: 0 0 0.7px #d32f2f, 0 0 0.7px #d32f2f;
    }
  </style>
</head>
<body class="bg-white text-gray-900">
  <!-- Navigation -->
  <nav class="fixed top-0 left-0 right-0 z-50 bg-white/95 shadow-md">
    <div class="container mx-auto px-6 py-4 flex justify-between items-center">
      <a href="#" class="text-4xl font-pacifico text-secondary font-semibold tracking-tighter text-logo">JV-GYM</a>
      <div class="hidden md:flex items-center space-x-8">
        <a href="#about" class="font-medium hover:text-secondary transition-colors">About</a>
        <a href="#programs" class="font-medium hover:text-secondary transition-colors">Programs</a>
        <a href="#shop" class="font-medium hover:text-secondary transition-colors">Shop</a>
        <a href="#community" class="font-medium hover:text-secondary transition-colors">Community</a>
        <a href="#contact" class="font-medium hover:text-secondary transition-colors">Contact</a>
      </div>
      <div class="flex items-center space-x-4">
        <button class="md:hidden w-10 h-10 flex items-center justify-center">
          <i class="ri-menu-line ri-lg"></i>
        </button>
      </div>
    </div>
  </nav>


