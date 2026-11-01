<!DOCTYPE html>
<html lang="th" class="scroll-smooth">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Home &amp; Cafe Preview - L'Académie &amp; Salon des Arts</title>
  
  <!-- Fonts: Playfair Display & Sarabun -->
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Playfair+Display:ital,wght@0,400;0,600;0,700;0,900;1,400;1,600&family=Sarabun:wght@300;400;500;600;700&display=swap" rel="stylesheet">
  
  <!-- Tailwind CSS CDN -->
  <script src="https://cdn.tailwindcss.com"></script>
  <script>
    tailwind.config = {
      theme: {
        extend: {
          colors: {
            burgundy: {
              DEFAULT: '#5c1d24',
              deep: '#3f1116',
              light: '#7e2a33',
              soft: '#8b323c'
            },
            parchment: {
              DEFAULT: '#fdf8f6',
              dim: '#ddd9d7',
              low: '#f7f3f0',
              container: '#f3ece8'
            },
            gold: {
              DEFAULT: '#9e782f',
              light: '#c59d4d',
              accent: '#d4af37'
            }
          },
          fontFamily: {
            serif: ['"Playfair Display"', 'Georgia', 'serif'],
            sans: ['"Sarabun"', 'sans-serif']
          }
        }
      }
    }
  </script>
  <style>
    /* Custom classical scrollbar & styling */
    ::-webkit-scrollbar { width: 8px; }
    ::-webkit-scrollbar-track { background: #fdf8f6; }
    ::-webkit-scrollbar-thumb { background: #5c1d2440; border-radius: 4px; }
    ::-webkit-scrollbar-thumb:hover { background: #5c1d2480; }
  </style>
</head>
<body class="bg-parchment text-[#2c2421] font-sans antialiased selection:bg-burgundy selection:text-white">

  <!-- TOP HEADER / MODERN CLASSICAL NAVBAR -->
  <header class="sticky top-0 z-50 bg-[#fdf8f6]/95 backdrop-blur-md border-b border-burgundy/10 transition-all">
    <div class="max-w-7xl mx-auto px-6 h-20 flex items-center justify-between">
      
      <!-- Logo & Emblem -->
      <a href="#" class="flex items-center gap-3 group">
        <div class="w-10 h-10 rounded-full border border-gold/40 flex items-center justify-center bg-burgundy text-parchment shadow-sm group-hover:scale-105 transition-transform">
          <svg class="w-5 h-5 fill-current text-gold-light" viewBox="0 0 24 24">
            <path d="M12 3v10.55c-.59-.34-1.27-.55-2-.55-2.21 0-4 1.79-4 4s1.79 4 4 4 4-1.79 4-4V7h4V3h-6z"/>
          </svg>
        </div>
        <div>
          <div class="flex items-center gap-2">
            <h1 class="font-serif text-lg font-bold tracking-wider text-burgundy">L'Académie &amp; Salon des Arts</h1>
            <span class="text-[9px] uppercase tracking-widest px-1.5 py-0.5 rounded bg-gold/15 text-gold-DEFAULT font-semibold">EST. 1894</span>
          </div>
          <p class="text-[10px] uppercase tracking-widest text-gold">Athénée · Grand Café · Beaux-Arts</p>
        </div>
      </a>

      <!-- Navigation Pills -->
      <nav class="hidden md:flex items-center gap-1 bg-parchment-low p-1.5 rounded-full border border-burgundy/10 text-xs shadow-inner">
        <a href="#cafe" class="px-5 py-2 rounded-full font-semibold transition-all bg-burgundy text-white shadow-sm">พรีวิวคาเฟ่ (Home &amp; Cafe)</a>
        <a href="#gallery" class="px-5 py-2 rounded-full font-medium text-burgundy hover:bg-burgundy/10 transition-all">แกลเลอรี &amp; ประมูล (Gallery)</a>
        <a href="#workshop" class="px-5 py-2 rounded-full font-medium text-burgundy hover:bg-burgundy/10 transition-all">จองเวิร์กช็อป (Workshops)</a>
        <a href="#salon" class="px-5 py-2 rounded-full font-medium text-burgundy hover:bg-burgundy/10 transition-all">สอบถาม &amp; ซาลอนส่วนตัว (Concierge)</a>
      </nav>

      <!-- Search & VIP Profile -->
      <div class="flex items-center gap-3">
        <div class="relative hidden lg:block">
          <input type="text" placeholder="ค้นหาวิจิตรศิลป์หรือสำรองที่นั่ง..." class="w-64 pl-9 pr-4 py-1.5 text-xs rounded-full bg-white border border-burgundy/15 focus:outline-none focus:border-gold transition-all" />
          <svg class="w-4 h-4 absolute left-3 top-2 text-gold" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M21 21l-6-6m2-5a7 7 0 11-14 0 7 7 0 0114 0z"/></svg>
        </div>
        <button class="px-3 py-1.5 text-xs font-semibold rounded-full bg-burgundy/5 border border-burgundy/15 text-burgundy hover:bg-burgundy/10 transition-all">THB (฿)</button>
        <div class="flex items-center gap-2 pl-2 border-l border-burgundy/15">
          <div class="w-8 h-8 rounded-full bg-burgundy text-white flex items-center justify-center font-serif text-xs font-semibold shadow">VIP</div>
          <span class="hidden sm:inline text-xs font-medium text-[#2c2421]">Curateur d'Art</span>
        </div>
      </div>
    </div>
  </header>

  <!-- HERO SECTION -->
  <section class="relative bg-gradient-to-b from-[#3f1116] via-[#5c1d24] to-[#2c0e12] text-white pt-24 pb-20 px-6 overflow-hidden">
    <div class="absolute inset-0 opacity-10 bg-[radial-gradient(#d4af37_1px,transparent_1px)] [background-size:20px_20px]"></div>
    
    <div class="max-w-4xl mx-auto text-center relative z-10">
      <div class="inline-flex items-center gap-2 px-4 py-1.5 rounded-full border border-gold/40 bg-white/5 backdrop-blur text-gold-light text-xs font-medium mb-6 uppercase tracking-widest">
        <span>❖</span> Athénée · Salon Gastronomique · Beaux-Arts <span>❖</span>
      </div>
      
      <h1 class="font-serif text-4xl sm:text-5xl md:text-6xl font-bold leading-tight mb-6 tracking-wide drop-shadow-sm">
        สุนทรียรสแห่งปรัชญา<br>และความวิจิตรยุควิกตอเรียน
      </h1>
      
      <p class="text-sm sm:text-base text-parchment/90 max-w-2xl mx-auto leading-relaxed mb-10 font-light">
        สัมผัสประสบการณ์ดื่มด่ำเหนือกาลเวลา การเสพสุนทรียวิจิตรศิลป์ชิ้นเอก สเปเชียลตี้คอฟฟี่สกัดเย็นในแก้วคริสตัลเจียระไน และประเพณีจิบน้ำชาชั้นสูง ท่ามกลางเสาหินอ่อนคอรินเธียนและบทสนทนาแห่งปัญญา
      </p>

      <div class="flex flex-wrap items-center justify-center gap-4 mb-16">
        <a href="#atmosphere" class="px-8 py-3.5 rounded bg-gold hover:bg-gold-light text-burgundy-deep font-semibold text-xs tracking-wider uppercase transition-all shadow-lg shadow-gold/20 flex items-center gap-2">
          สัมผัสบรรยากาศร้าน <span>▾</span>
        </a>
        <a href="#gallery" class="px-8 py-3.5 rounded border border-white/30 hover:border-gold hover:text-gold text-parchment font-medium text-xs tracking-wider uppercase transition-all backdrop-blur-sm">
          ชมคอลเลกชันศิลปะ &amp; ประมูลสด
        </a>
      </div>

      <!-- Feature Highlight Badges -->
      <div class="grid grid-cols-1 sm:grid-cols-3 gap-4 pt-6 border-t border-white/15 max-w-3xl mx-auto">
        <div class="p-4 rounded-xl bg-white/5 border border-white/10 backdrop-blur-sm text-center">
          <div class="text-xl mb-1 text-gold-light">☕</div>
          <h2 class="font-serif text-sm font-semibold text-parchment mb-1">กาแฟสกัดมือชั้นเลิศ</h2>
          <p class="text-[11px] text-parchment/70">คัดสรรเมล็ดพันธุ์อาราบิกาเกรดสะสม บ่มในถังไม้โอ๊ค</p>
        </div>
        <div class="p-4 rounded-xl bg-white/5 border border-white/10 backdrop-blur-sm text-center">
          <div class="text-xl mb-1 text-gold-light">🏛️</div>
          <h2 class="font-serif text-sm font-semibold text-parchment mb-1">พิพิธภัณฑ์มีชีวิต</h2>
          <p class="text-[11px] text-parchment/70">จิตรกรรมสีน้ำมันศตวรรษที่ 19 และงานบรอนซ์ตั้งเดิม</p>
        </div>
        <div class="p-4 rounded-xl bg-white/5 border border-white/10 backdrop-blur-sm text-center">
          <div class="text-xl mb-1 text-gold-light">🛎️</div>
          <h2 class="font-serif text-sm font-semibold text-parchment mb-1">ซาลอนส่วนตัวแบบเอ็กซ์คลูซีฟ</h2>
          <p class="text-[11px] text-parchment/70">มุมอ่านบทกวี โต๊ะหมากรุกไม้โรสวูด และดนตรีแชมเบอร์</p>
        </div>
      </div>
    </div>
  </section>

  <!-- LIVE TICKER BANNER -->
  <div class="bg-[#e9ba55] text-burgundy-deep py-2.5 px-6 text-xs font-medium border-y border-[#d4a843] flex items-center justify-between overflow-hidden">
    <div class="max-w-7xl mx-auto w-full flex items-center justify-between">
      <div class="flex items-center gap-2">
        <span class="w-2 h-2 rounded-full bg-red-600 animate-ping"></span>
        <span class="font-bold">LIVE LOT 42:</span>
        <span class="truncate">"Le Triomphe d'Apollon" จิตรกรรมสีน้ำมันปี 1888 — เคาราคาสูงสุด ณ ขณะนี้ ฿480,000</span>
      </div>
      <a href="#gallery" class="hidden sm:inline-flex items-center gap-1 font-semibold hover:underline">
        เข้าร่วมห้องประมูลแบบเรียลไทม์ <span>→</span>
      </a>
    </div>
  </div>

  <!-- ATMOSPHERE & ZONES SHOWCASE -->
  <section id="atmosphere" class="py-24 px-6 max-w-7xl mx-auto">
    <div class="text-center mb-16">
      <span class="text-xs uppercase tracking-widest text-gold font-semibold">ESPACES &amp; SALONS</span>
      <h2 class="font-serif text-3xl sm:text-4xl font-bold text-burgundy mt-2 mb-3">บรรยากาศและโซนวิจิตรศิลป์</h2>
      <div class="w-16 h-0.5 bg-gold mx-auto mb-4"></div>
      <p class="text-sm text-[#5c5450] max-w-xl mx-auto">แต่ละมุมจำลองความสง่างามแห่งสถาปัตยกรรมคลาสสิก พร้อมต้อนรับนักคิด นักสะสม และผู้แสวงหาสุนทรียะ</p>
    </div>

    <div class="grid grid-cols-1 md:grid-cols-3 gap-8">
      <!-- Zone 1: Colonnade -->
      <div class="bg-white rounded-2xl border border-burgundy/10 overflow-hidden shadow-sm hover:shadow-xl transition-all duration-300 group flex flex-col">
        <div class="h-64 overflow-hidden relative">
          <img src="https://images.unsplash.com/photo-1544816155-12df9643f363?auto=format&fit=crop&w=800&q=80" alt="The Corinthian Colonnade" class="w-full h-full object-cover group-hover:scale-105 transition-transform duration-500 rounded-t-2xl">
          <div class="absolute inset-0 bg-gradient-to-t from-black/80 via-black/20 to-transparent flex flex-col justify-end p-6">
            <span class="text-[10px] tracking-widest text-gold uppercase font-semibold">COLONNADE I</span>
            <h3 class="font-serif text-xl font-bold text-white">The Corinthian Colonnade</h3>
          </div>
        </div>
        <div class="p-6 flex-1 flex flex-col justify-between">
          <p class="text-xs text-[#5c5450] leading-relaxed mb-6">
            โถงจิบกาแฟสเปเชียลตี้ใต้ระเบียงเสาหินอ่อนกรีก เพดานโค้งสลักลายปูนปั้นนูนต่ำ ดื่มด่ำรสชาติกาแฟฟิกเนเจอร์พร้อมไอแดดอ่อนยามบ่าย
          </p>
          <div>
            <div class="flex flex-wrap gap-2 text-[10px] mb-4 text-burgundy font-medium">
              <span class="px-2.5 py-1 rounded bg-parchment-low">Specialty Coffee</span>
              <span class="px-2.5 py-1 rounded bg-parchment-low">Single Origin</span>
              <span class="px-2.5 py-1 rounded bg-parchment-low">Open Seating</span>
            </div>
            <div class="flex items-center justify-between text-xs pt-4 border-t border-burgundy/10">
              <span class="text-[#7d7571]">ความจุ 36 ที่นั่ง</span>
              <a href="#reserve" class="text-gold font-semibold hover:underline">สำรองที่นั่ง &rarr;</a>
            </div>
          </div>
        </div>
      </div>

      <!-- Zone 2: Victorian Tea Salon -->
      <div class="bg-white rounded-2xl border border-burgundy/10 overflow-hidden shadow-sm hover:shadow-xl transition-all duration-300 group flex flex-col">
        <div class="h-64 overflow-hidden relative">
          <img src="https://images.unsplash.com/photo-1517248135467-4c7edcad34c4?auto=format&fit=crop&w=800&q=80" alt="The Victorian Tea Salon" class="w-full h-full object-cover group-hover:scale-105 transition-transform duration-500 rounded-t-2xl">
          <div class="absolute inset-0 bg-gradient-to-t from-black/80 via-black/20 to-transparent flex flex-col justify-end p-6">
            <span class="text-[10px] tracking-widest text-gold uppercase font-semibold">SALON II</span>
            <h3 class="font-serif text-xl font-bold text-white">The Victorian Tea Salon</h3>
          </div>
        </div>
        <div class="p-6 flex-1 flex flex-col justify-between">
          <p class="text-xs text-[#5c5450] leading-relaxed mb-6">
            ห้องน้ำชาเบญจรงค์สไตล์อังกฤษและเบเกอรี่ชั้นสูง ปูพรมทอเปอร์เซีย ประดับกระจกเจียระไนจากเวนิส เหมาะสำหรับการรวมกลุ่มเพื่อสนทนาเชิงวรรณกรรม
          </p>
          <div>
            <div class="flex flex-wrap gap-2 text-[10px] mb-4 text-burgundy font-medium">
              <span class="px-2.5 py-1 rounded bg-parchment-low">English High Tea</span>
              <span class="px-2.5 py-1 rounded bg-parchment-low">Rare Teas</span>
              <span class="px-2.5 py-1 rounded bg-parchment-low">Private Alcove</span>
            </div>
            <div class="flex items-center justify-between text-xs pt-4 border-t border-burgundy/10">
              <span class="text-[#7d7571]">ความจุ 24 ที่นั่ง</span>
              <a href="#reserve" class="text-gold font-semibold hover:underline">สำรองที่นั่ง &rarr;</a>
            </div>
          </div>
        </div>
      </div>

      <!-- Zone 3: Atrium Gallery -->
      <div class="bg-white rounded-2xl border border-burgundy/10 overflow-hidden shadow-sm hover:shadow-xl transition-all duration-300 group flex flex-col">
        <div class="h-64 overflow-hidden relative">
          <img src="https://images.unsplash.com/photo-1582555172866-f73bb12a2ab3?auto=format&fit=crop&w=800&q=80" alt="The Atrium Gallery" class="w-full h-full object-cover group-hover:scale-105 transition-transform duration-500 rounded-t-2xl">
          <div class="absolute inset-0 bg-gradient-to-t from-black/80 via-black/20 to-transparent flex flex-col justify-end p-6">
            <span class="text-[10px] tracking-widest text-gold uppercase font-semibold">GALERIE III</span>
            <h3 class="font-serif text-xl font-bold text-white">The Atrium Gallery</h3>
          </div>
        </div>
        <div class="p-6 flex-1 flex flex-col justify-between">
          <p class="text-xs text-[#5c5450] leading-relaxed mb-6">
            ลานแสดงภาพวาดและประติมากรรมหินอ่อนยุคเรเนซองส์ถึงวิกตอเรียน จัดแสดงผลงานหมุนเวียนพร้อมพื้นที่เคาะประมูลสดระดับนานาชาติ
          </p>
          <div>
            <div class="flex flex-wrap gap-2 text-[10px] mb-4 text-burgundy font-medium">
              <span class="px-2.5 py-1 rounded bg-parchment-low">Live Auctions</span>
              <span class="px-2.5 py-1 rounded bg-parchment-low">Sculptures</span>
              <span class="px-2.5 py-1 rounded bg-parchment-low">Exhibits</span>
            </div>
            <div class="flex items-center justify-between text-xs pt-4 border-t border-burgundy/10">
              <span class="text-[#7d7571]">จัดแสดง 58 ชิ้นงาน</span>
              <a href="#gallery" class="text-gold font-semibold hover:underline">ชมสูจิบัตร &rarr;</a>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>

  <!-- GASTRONOMY & PATISSERIE MENU -->
  <section class="py-20 bg-parchment-low border-y border-burgundy/10 px-6">
    <div class="max-w-7xl mx-auto">
      <div class="flex flex-col sm:flex-row sm:items-end justify-between mb-12 gap-4">
        <div>
          <span class="text-xs uppercase tracking-widest text-gold font-semibold">HAUTE GASTRONOMIE &amp; PÂTISSERIE</span>
          <h2 class="font-serif text-3xl font-bold text-burgundy mt-1">เมนูซิกเนเจอร์ประจำชาลอน</h2>
          <p class="text-xs text-[#5c5450] mt-1">ผลงานรังสรรค์แห่งรสชาติที่ผสานศิลปะการอบขนมแบบฝรั่งเศสดั้งเดิมและกาแฟคัดเกรดพิเศษ</p>
        </div>
        <div class="flex items-center gap-2">
          <button class="px-4 py-1.5 rounded-full text-xs font-semibold bg-burgundy text-white shadow-sm">ทั้งหมด</button>
          <button class="px-4 py-1.5 rounded-full text-xs font-medium bg-white text-burgundy hover:bg-parchment border border-burgundy/15 transition-all">เครื่องดื่มซิกเนเจอร์</button>
          <button class="px-4 py-1.5 rounded-full text-xs font-medium bg-white text-burgundy hover:bg-parchment border border-burgundy/15 transition-all">ขนมอบ &amp; ชุดน้ำชา</button>
        </div>
      </div>

      <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-4 gap-6">
        <!-- Item 1 -->
        <div class="bg-white rounded-xl border border-burgundy/10 p-4 shadow-sm hover:shadow-md transition-shadow">
          <div class="relative h-48 rounded-lg overflow-hidden mb-4">
            <span class="absolute top-2 left-2 px-2 py-0.5 rounded text-[10px] font-bold bg-burgundy text-white uppercase tracking-wider z-10">SIGNATURE</span>
            <span class="absolute top-2 right-2 px-2 py-0.5 rounded text-[11px] font-bold bg-black/60 backdrop-blur text-white z-10">฿380</span>
            <img src="https://images.unsplash.com/photo-1514432324607-a09d9b4aefdd?auto=format&fit=crop&w=600&q=80" alt="Ambrosia Cold Drip" class="w-full h-full object-cover">
          </div>
          <h3 class="font-serif text-base font-bold text-burgundy">Ambrosia Cold Drip</h3>
          <p class="text-[11px] text-[#5c5450] mt-1 mb-3 line-clamp-2">กาแฟโคลด์ดริปสกัดเย็น 18 ชม. เสิร์ฟในแก้วคริสตัลโบราณ พร้อมกลิ่นสัมผัสเบอร์รีป่า อัลมอนด์และน้ำผึ้งป่า</p>
          <div class="flex items-center justify-between pt-3 border-t border-burgundy/10 text-[10px]">
            <span class="text-gold font-medium">Single Origin Panama Geisha</span>
            <button class="text-burgundy hover:text-gold"><svg class="w-4 h-4" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M5 5a2 2 0 012-2h10a2 2 0 012 2v16l-7-3.5L5 21V5z"/></svg></button>
          </div>
        </div>

        <!-- Item 2 -->
        <div class="bg-white rounded-xl border border-burgundy/10 p-4 shadow-sm hover:shadow-md transition-shadow">
          <div class="relative h-48 rounded-lg overflow-hidden mb-4">
            <span class="absolute top-2 left-2 px-2 py-0.5 rounded text-[10px] font-bold bg-gold text-burgundy-deep uppercase tracking-wider z-10">SET FOR TWO</span>
            <span class="absolute top-2 right-2 px-2 py-0.5 rounded text-[11px] font-bold bg-black/60 backdrop-blur text-white z-10">฿1,450</span>
            <img src="https://images.unsplash.com/photo-1587314168485-3236d6710814?auto=format&fit=crop&w=600&q=80" alt="Victorian Empress High Tea" class="w-full h-full object-cover">
          </div>
          <h3 class="font-serif text-base font-bold text-burgundy">Victorian Empress High Tea</h3>
          <p class="text-[11px] text-[#5c5450] mt-1 mb-3 line-clamp-2">ชุดน้ำชาและสโคนเนยแควนน็อกพรีเมียม เสิร์ฟพร้อมแยมเบอร์รีป่า คลอตเต็ดครีมแท้ และคานาเป้คาวิอาร์</p>
          <div class="flex items-center justify-between pt-3 border-t border-burgundy/10 text-[10px]">
            <span class="text-gold font-medium">ชาแบลนด์พิเศษ 2 กา</span>
            <button class="text-burgundy hover:text-gold"><svg class="w-4 h-4" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M5 5a2 2 0 012-2h10a2 2 0 012 2v16l-7-3.5L5 21V5z"/></svg></button>
          </div>
        </div>

        <!-- Item 3 -->
        <div class="bg-white rounded-xl border border-burgundy/10 p-4 shadow-sm hover:shadow-md transition-shadow">
          <div class="relative h-48 rounded-lg overflow-hidden mb-4">
            <span class="absolute top-2 right-2 px-2 py-0.5 rounded text-[11px] font-bold bg-black/60 backdrop-blur text-white z-10">฿340</span>
            <img src="https://images.unsplash.com/photo-1509440159596-0249088772ff?auto=format&fit=crop&w=600&q=80" alt="Apollo's Golden Choux" class="w-full h-full object-cover">
          </div>
          <h3 class="font-serif text-base font-bold text-burgundy">Apollo's Golden Choux</h3>
          <p class="text-[11px] text-[#5c5450] mt-1 mb-3 line-clamp-2">ชูครีมคาราเมลหุ้มทองคำเปลว 24K สอดไส้วานิลลาตาฮิติหอมละมุนและพราลีนถั่วฮาเซลนัทคั่ว</p>
          <div class="flex items-center justify-between pt-3 border-t border-burgundy/10 text-[10px]">
            <span class="text-gold font-medium">Edible 24K Gold Leaf</span>
            <button class="text-burgundy hover:text-gold"><svg class="w-4 h-4" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M5 5a2 2 0 012-2h10a2 2 0 012 2v16l-7-3.5L5 21V5z"/></svg></button>
          </div>
        </div>

        <!-- Item 4 -->
        <div class="bg-white rounded-xl border border-burgundy/10 p-4 shadow-sm hover:shadow-md transition-shadow">
          <div class="relative h-48 rounded-lg overflow-hidden mb-4">
            <span class="absolute top-2 right-2 px-2 py-0.5 rounded text-[11px] font-bold bg-black/60 backdrop-blur text-white z-10">฿290</span>
            <img src="https://images.unsplash.com/photo-1569864358642-9d1684040f43?auto=format&fit=crop&w=600&q=80" alt="Aphrodite Rose Velvet" class="w-full h-full object-cover">
          </div>
          <h3 class="font-serif text-base font-bold text-burgundy">Aphrodite Rose Velvet</h3>
          <p class="text-[11px] text-[#5c5450] mt-1 mb-3 line-clamp-2">มาการองกุหลาบดามาสก์ ผสานกานาชลิ้นจี่และราสเบอร์รีสด ให้สัมผัสหวานอมเปรี้ยวอันประณีต</p>
          <div class="flex items-center justify-between pt-3 border-t border-burgundy/10 text-[10px]">
            <span class="text-gold font-medium">Damask Rose Essence</span>
            <button class="text-burgundy hover:text-gold"><svg class="w-4 h-4" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M5 5a2 2 0 012-2h10a2 2 0 012 2v16l-7-3.5L5 21V5z"/></svg></button>
          </div>
        </div>
      </div>
    </div>
  </section>

  <!-- ART PREVIEW & TABLE RESERVATION SPLIT -->
  <section class="py-24 px-6 max-w-7xl mx-auto">
    <div class="grid grid-cols-1 lg:grid-cols-12 gap-12 items-start">
      
      <!-- Left: Featured Artwork Lot Teaser (7 cols) -->
      <div class="lg:col-span-7">
        <div class="flex items-center gap-2 text-xs uppercase tracking-widest text-gold font-semibold mb-2">
          <span>❖</span> EXPOSITION &amp; VENTE AUX ENCHÈRES
        </div>
        <h2 class="font-serif text-3xl font-bold text-burgundy mb-4">
          นิทรรศการมาสเตอร์พีซ<br>และศิลปกรรมประมูลประจำสัปดาห์
        </h2>
        <p class="text-xs text-[#5c5450] leading-relaxed mb-8">
          ชมจิตรกรรมดั้งเดิมที่ผ่านการอนุรักษ์โดยนักวิชาการศิลปะยุโรป ดื่มด่ำรสชาติกาแฟขณะพิจารณาฝีแปรงของศิลปินเอก ยุคคลาสสิกถึงอิมเพรสชันนิสม์
        </p>

        <!-- Artwork Feature Card -->
        <div class="bg-white rounded-2xl border border-burgundy/15 p-6 shadow-sm flex flex-col sm:flex-row gap-6 items-center">
          <div class="w-full sm:w-48 h-56 rounded-lg overflow-hidden border border-gold/40 shadow-inner flex-shrink-0">
            <img src="https://images.unsplash.com/photo-1579783900882-c0d3dad7b119?auto=format&fit=crop&w=600&q=80" alt="Portrait d'une Muse" class="w-full h-full object-cover">
          </div>
          <div class="flex-1 w-full">
            <div class="flex items-center justify-between text-xs text-gold font-semibold mb-1">
              <span>LOT # 89</span>
              <span class="text-red-700 bg-red-50 px-2 py-0.5 rounded">⏱ ปิดประมูลใน 02:44:18</span>
            </div>
            <h3 class="font-serif text-lg font-bold text-burgundy">"Portrait d'une Muse à la Bibliothèque" (1892)</h3>
            <p class="text-xs text-[#7d7571] mb-4">ศิลปิน: François-Édouard Picot (สตูดิโอ)</p>
            
            <div class="flex items-baseline justify-between mb-4 pt-3 border-t border-burgundy/10">
              <div>
                <span class="text-[10px] text-[#7d7571] block">ราคาเสนอปัจจุบัน</span>
                <span class="font-serif text-xl font-bold text-burgundy">฿320,000</span>
              </div>
              <a href="#gallery" class="px-5 py-2 rounded bg-burgundy hover:bg-burgundy-light text-white text-xs font-semibold shadow transition-all">
                เสนอราคาด่วน
              </a>
            </div>
          </div>
        </div>

        <!-- Next Workshop Teaser -->
        <div class="mt-6 p-4 rounded-xl bg-parchment-low border border-burgundy/10 flex items-center justify-between text-xs">
          <div class="flex items-center gap-3">
            <span class="p-2 rounded bg-burgundy/10 text-burgundy text-base">🎨</span>
            <div>
              <p class="font-semibold text-burgundy">เวิร์กช็อปจิตรกรรมสีน้ำมัน &amp; ชิมชาสมุนไพร</p>
              <p class="text-[11px] text-[#7d7571]">เสาร์นี้ 14:00 - 17:00 น. | เหลือเพียง 4 ที่นั่งสุดท้าย</p>
            </div>
          </div>
          <a href="#workshop" class="text-gold font-semibold hover:underline">ลงทะเบียน &rarr;</a>
        </div>
      </div>

      <!-- Right: Quick Table Reservation (5 cols) -->
      <div id="reserve" class="lg:col-span-5 bg-white rounded-2xl border border-burgundy/15 p-8 shadow-md">
        <div class="flex items-center justify-between border-b border-burgundy/10 pb-4 mb-6">
          <div>
            <h3 class="font-serif text-xl font-bold text-burgundy">จองโต๊ะ &amp; ห้องชาลอน</h3>
            <p class="text-[11px] text-[#7d7571]">โปรดระบุช่วงเวลาและโซนที่ต้องการเพื่อสัมผัสบริการระดับเอ็กซ์คลูซีฟ</p>
          </div>
          <span class="text-[10px] font-bold text-gold uppercase tracking-widest px-2 py-1 rounded bg-gold/10">VIP RESERVATION</span>
        </div>

        <form class="space-y-4 text-xs">
          <div>
            <label class="block font-medium text-burgundy mb-1">เลือกโซนห้อง</label>
            <select class="w-full px-3 py-2.5 rounded border border-burgundy/15 bg-parchment-low focus:outline-none focus:border-gold">
              <option>The Corinthian Colonnade (กาแฟสเปเชียลตี้)</option>
              <option>The Victorian Tea Salon (ห้องจิบชาอังกฤษ)</option>
              <option>The Atrium Gallery (โต๊ะริมแกลเลอรีประมูล)</option>
              <option>The Grand Victorian Chamber (ห้องรับรองส่วนตัว)</option>
            </select>
          </div>

          <div class="grid grid-cols-2 gap-4">
            <div>
              <label class="block font-medium text-burgundy mb-1">วันที่</label>
              <input type="date" value="2025-05-18" class="w-full px-3 py-2.5 rounded border border-burgundy/15 bg-parchment-low focus:outline-none focus:border-gold">
            </div>
            <div>
              <label class="block font-medium text-burgundy mb-1">จำนวนแขก</label>
              <select class="w-full px-3 py-2.5 rounded border border-burgundy/15 bg-parchment-low focus:outline-none focus:border-gold">
                <option>2 ท่าน</option>
                <option>4 ท่าน</option>
                <option>6-8 ท่าน</option>
                <option>10 ท่านขึ้นไป (ห้องส่วนตัว)</option>
              </select>
            </div>
          </div>

          <div>
            <label class="block font-medium text-burgundy mb-1">ชื่อผู้สำรอง &amp; นามสกุล</label>
            <input type="text" placeholder="ระบุชื่อของท่าน..." class="w-full px-3 py-2.5 rounded border border-burgundy/15 bg-parchment-low focus:outline-none focus:border-gold">
          </div>

          <div>
            <label class="block font-medium text-burgundy mb-1">เบอร์โทรศัพท์ติดต่อ</label>
            <input type="tel" placeholder="+66 8X XXX XXXX" class="w-full px-3 py-2.5 rounded border border-burgundy/15 bg-parchment-low focus:outline-none focus:border-gold">
          </div>

          <button type="button" class="w-full mt-2 py-3 rounded bg-burgundy hover:bg-burgundy-light text-white font-semibold transition-all shadow-md flex items-center justify-center gap-2">
            <span>ยืนยันการสำรองที่นั่ง</span>
          </button>
          
          <p class="text-[10px] text-center text-[#7d7571] mt-2">
            * สมาชิก VIP ได้รับสิทธิ์ยกเว้นค่ามัดจำห้องชาลอนส่วนตัว
          </p>
        </form>
      </div>

    </div>
  </section>

  <!-- TESTIMONIALS & CRITIQUE -->
  <section class="py-20 bg-parchment-low border-t border-burgundy/10 px-6">
    <div class="max-w-5xl mx-auto text-center">
      <span class="text-xs uppercase tracking-widest text-gold font-semibold">TÉMOIGNAGES &amp; PRESSE</span>
      <h2 class="font-serif text-3xl font-bold text-burgundy mt-2 mb-12">เสียงชื่นชมจากเหล่านักวิจารณ์</h2>
      
      <div class="grid grid-cols-1 md:grid-cols-3 gap-8 text-left">
        <div class="bg-white p-6 rounded-xl border border-burgundy/10 shadow-sm relative">
          <span class="text-4xl text-gold/30 font-serif absolute top-3 left-4">“</span>
          <p class="text-xs text-[#5c5450] leading-relaxed pt-4 mb-6">
            การผสมผสานบรรยากาศพิพิธภัณฑ์ยุโรปเข้ากับสุนทรียรสแห่งกาแฟได้อย่างไร้ที่ติ ที่นี่คือวิหารสำหรับผู้ที่ต้องการหลีกหนีความเร่งรีบของโลกสมัยใหม่
          </p>
          <div class="border-t border-burgundy/10 pt-3">
            <h4 class="font-serif text-xs font-bold text-burgundy">นิตยสาร L'Art &amp; Gastronomie</h4>
            <span class="text-[10px] text-[#7d7571]">คอลัมน์วิจารณ์ศิลปะและคาเฟ่ระดับโลก</span>
          </div>
        </div>

        <div class="bg-white p-6 rounded-xl border border-burgundy/10 shadow-sm relative">
          <span class="text-4xl text-gold/30 font-serif absolute top-3 left-4">“</span>
          <p class="text-xs text-[#5c5450] leading-relaxed pt-4 mb-6">
            ชุดน้ำชา Victorian Empress และสโคนเนยฝรั่งเศสทำให้หวนนึกถึงบ่ายวันหนึ่งในลอนดอนยุคเอ็ดเวิร์ด รสชาติละเอียดอ่อนและเครื่องกระเบื้องที่ใช้ล้ำค่า
          </p>
          <div class="border-t border-burgundy/10 pt-3">
            <h4 class="font-serif text-xs font-bold text-burgundy">ม.ล. วริรักษ์ ชุมสาย</h4>
            <span class="text-[10px] text-[#7d7571]">นักสะสมเครื่องเงินและเครื่องกระเบื้องยุโรป</span>
          </div>
        </div>

        <div class="bg-white p-6 rounded-xl border border-burgundy/10 shadow-sm relative">
          <span class="text-4xl text-gold/30 font-serif absolute top-3 left-4">“</span>
          <p class="text-xs text-[#5c5450] leading-relaxed pt-4 mb-6">
            เวทีประมูลศิลปะที่อบอุ่นและมีระดับที่สุดในเอเชียตะวันออกเฉียงใต้ การจิบกาแฟโคลด์ดริปพลางชมภาพวาดศตวรรษที่ 19 คือความอภิรมย์อย่างแท้จริง
          </p>
          <div class="border-t border-burgundy/10 pt-3">
            <h4 class="font-serif text-xs font-bold text-burgundy">The Bangkok Heritage Review</h4>
            <span class="text-[10px] text-[#7d7571]">ฉบับประจำฤดูใบไม้ผลิ 2025</span>
          </div>
        </div>
      </div>
    </div>
  </section>

  <!-- SHARED FOOTER -->
  <footer class="bg-[#2c0e12] text-parchment-low py-16 border-t border-gold/30 px-6">
    <div class="max-w-7xl mx-auto grid grid-cols-1 md:grid-cols-4 gap-10">
      <div>
        <h3 class="font-serif text-2xl font-bold text-parchment mb-2">L'Académie · 1894</h3>
        <p class="text-xs text-parchment-dim leading-relaxed mb-4">
          สถาบันศิลปะและชาลอนวิจิตรประณีต แหล่งรวบรวมชิ้นงานมาสเตอร์พีซ ศิลปะยุควิกตอเรียน-นีโอคลาสสิก พร้อมบริการเสิร์ฟกาแฟระดับโอเปร่าเฮาส์
        </p>
        <span class="text-[10px] text-gold uppercase tracking-wider block">❖ Acquisition · Salon · Conservation</span>
      </div>

      <div>
        <h4 class="text-xs font-semibold text-gold uppercase tracking-wider mb-4 flex items-center gap-1.5">
          <span>🕒</span> เวลาทำการชาลอน
        </h4>
        <div class="text-xs text-parchment-dim leading-relaxed space-y-2">
          <p><strong class="text-parchment">จันทร์ – พฤหัสบดี:</strong> 09:30 – 20:00 น.</p>
          <p><strong class="text-parchment">ศุกร์ – เสาร์:</strong> 09:30 – 23:00 น. (ค่ำคืนดนตรีแชมเบอร์)</p>
          <p><strong class="text-parchment">อาทิตย์:</strong> 10:00 – 19:30 น. (การประมูลรายสัปดาห์)</p>
          <p class="text-[10px] text-gold/80 pt-1">* กรุณาสำรองโต๊ะและห้องจัดแสดงส่วนตัวล่วงหน้า</p>
        </div>
      </div>

      <div>
        <h4 class="text-xs font-semibold text-gold uppercase tracking-wider mb-4 flex items-center gap-1.5">
          <span>📍</span> สถานที่ตั้ง &amp; การติดต่อ
        </h4>
        <div class="text-xs text-parchment-dim leading-relaxed space-y-2">
          <p>ตึกศิลาขาว เลขที่ 48 ถนนพาหุรัด-มรดกสยาม แขวงวังบูรพาภิรมย์ เขตพระนคร กรุงเทพมหานคร 10200</p>
          <p><strong class="text-parchment">โทร:</strong> +66 (0) 2 189 4455</p>
          <p><strong class="text-parchment">อีเมล:</strong> concierge@lacademie-artsalon.com</p>
        </div>
      </div>

      <div>
        <h4 class="text-xs font-semibold text-gold uppercase tracking-wider mb-4 flex items-center gap-1.5">
          <span>✉️</span> จดหมายข่าววิจิตรศิลป์
        </h4>
        <p class="text-xs text-parchment-dim leading-relaxed mb-4">
          รับสูจิบัตรประมูลและสิทธิ์สำรองรอบพรีวิวคอลเลกชันใหม่ก่อนใคร
        </p>
        <form class="space-y-2">
          <input type="email" placeholder="ระบุอีเมลของท่าน..." class="w-full px-3 py-2 text-xs rounded bg-white/10 text-white placeholder-white/50 border border-white/20 focus:outline-none focus:border-gold">
          <button type="button" class="w-full py-2.5 text-xs rounded bg-burgundy text-white font-medium hover:bg-burgundy-light transition-colors border border-gold/40 shadow">
            ลงนามรับสูจิบัตร
          </button>
        </form>
      </div>
    </div>

    <div class="max-w-7xl mx-auto mt-12 pt-6 border-t border-white/10 flex flex-col sm:flex-row items-center justify-between text-[11px] text-parchment-dim gap-4">
      <p class="font-serif italic">"Ars longa, vita brevis — ศิลปะยืนยาว ชีวิตสั้นนัก"</p>
      <p>© 1894–2025 L'Académie &amp; Salon des Arts. สงวนลิขสิทธิ์ทุกประการ.</p>
      <div class="flex gap-4">
        <a href="#" class="hover:text-gold transition-colors">ระเบียบการประมูล</a>
        <a href="#" class="hover:text-gold transition-colors">นโยบายความเป็นส่วนตัว</a>
        <a href="#" class="hover:text-gold transition-colors">หอจดหมายเหตุ</a>
      </div>
    </div>
  </footer>

</body>
</html>
