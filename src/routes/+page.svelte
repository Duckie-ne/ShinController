<script>
  // Có thể thêm logic JS ở đây nếu cần

  // Thay link ảnh/logo thực tế cho đúng profile của bạn
  const equipment = [
    { img: "https://i.imgur.com/your-macbook.jpg", label: "MacBook" },
    { img: "https://i.imgur.com/your-headphone.jpg", label: "Tai nghe (Nghe trước)" },
    { img: "https://i.imgur.com/your-soundcard.jpg", label: "Sound Card" }
  ];

  const brands = [
    { img: "https://i.imgur.com/lego.png", label: "LEGO" },
    { img: "https://i.imgur.com/suntory.png", label: "SUNTORY PEPSICO" },
    { img: "https://i.imgur.com/victoria.png", label: "VICTORIA'S SECRET" },
    { img: "https://i.imgur.com/vib.png", label: "VIB" },
    // ... thêm các logo khác
  ];

  const realPics = [
    "https://i.imgur.com/pic1.jpg",
    "https://i.imgur.com/pic2.jpg",
    "https://i.imgur.com/pic3.jpg",
    "https://i.imgur.com/pic4.jpg",
    "https://i.imgur.com/pic5.jpg",
    "https://i.imgur.com/pic6.jpg",
    "https://i.imgur.com/pic7.jpg",
    "https://i.imgur.com/pic8.jpg"
  ];

  const agencies = [
    { img: "https://i.imgur.com/imex.png", label: "IMEX" },
    { img: "https://i.imgur.com/ignition.png", label: "Ignition Group" },
    // ... thêm các logo khác
  ];

  const mcs = [
    { img: "https://i.imgur.com/mc1.jpg", label: "MC SAN HÍ" },
    { img: "https://i.imgur.com/mc2.jpg", label: "MC TRƯỜNG LƯU" }
  ];
</script>

<div class="min-h-screen bg-black text-white font-sans px-4 py-8">
  <!-- Header -->
  <div class="flex flex-col md:flex-row items-center md:items-start gap-8">
    <!-- Avatar -->
    <div class="flex-shrink-0 w-40 h-40 rounded-xl border-2 border-yellow-400 overflow-hidden shadow-lg bg-black">
      <img src="/ShinController/images/IMG_2991.JPG" alt="KuShyn" class="w-full h-full object-cover" />
    </div>
    <!-- Name & Title -->
    <div>
      <div class="text-5xl font-extrabold tracking-widest">
        <span class="text-white">KU</span>
        <span class="text-yellow-400">SHYN</span>
      </div>
      <div class="mt-2 text-lg font-semibold tracking-widest text-yellow-400">MUSIC CONTROLLER</div>
      <div class="mt-4 max-w-xl text-gray-200">
        Người sẽ chỉnh nhạc theo yêu cầu của chương trình từ phía các Agency hoặc có thể linh hoạt tuỳ tình hình thực tế, song song đó phối hợp với các đơn vị để giúp cho chương trình mạch lạc và có nhiều cung bậc cảm xúc nhất có thể. Công việc này khác hoàn với người chịu trách nhiệm MỞ hoặc TẮT NHẠC. Có thể ví von như một MasterChef nêm "GIA VỊ" cho các món ăn để buổi tiệc thêm phần đậm đà.
      </div>
    </div>
  </div>

  <!-- Experience & Skill -->
  <div class="mt-10 grid md:grid-cols-2 gap-8 items-stretch">
    <!-- Skill block -->
    <div class="flex flex-col h-full">
      <div class="text-xl font-bold text-yellow-400 mb-2">// EXPERIENCE </div>
      <div class="bg-gray-900 rounded-lg p-4 flex flex-col justify-between h-full">
        <div>
          <div class="font-semibold text-white">SKILL <span class="text-sm text-gray-400">(2020–2022)</span></div>
          <ul class="list-disc ml-5 text-gray-200 mt-2">
            <li>Có kỹ năng và sự hiểu biết về âm thanh</li>
            <li>Biết và thông thạo 1 loại nhạc cụ (Guitar)</li>
            <li>Thông thạo các phần mềm chỉnh nhạc: VirtualDJ, Serato, Rekordbox</li>
          </ul>
        </div>
        <div class="flex gap-2 mt-4">
          <span>🎧</span>
          <span>🎹</span>
          <span>🎵</span>
        </div>
      </div>
    </div>
  
    <!-- Experience block -->
    <div class="flex flex-col h-full">
      <div class="text-xl font-bold text-yellow-400 mb-2">// SKILL</div>
      <div class="bg-gray-900 rounded-lg p-4 flex flex-col justify-between h-full">
        <div>
          <div class="font-semibold text-white">EXPERIENCE <span class="text-sm text-gray-400">(2021–2024)</span></div>
          <ul class="list-disc ml-5 text-gray-200 mt-2">
            <li>Thiết kế và tư vấn nhạc trong chương trình cho khách.</li>
            <li>Có khả năng biến tấu theo các thể loại chương trình.</li>
            <li>Nguồn nhạc đa dạng, bắt trending nhanh.</li>
            <li>Từng làm sự kiện cho chương trình 1000 Pax.</li>
          </ul>
        </div>
      </div>
    </div>
  </div>
  

  <!-- Education & Type -->
  <div class="mt-10 grid md:grid-cols-2 gap-8">
    <div>
      <div class="text-xl font-bold text-yellow-400 mb-2">// EDUCATION</div>
      <div class="bg-gray-900 rounded-lg p-4">
        <div class="font-semibold">Cao Đẳng FPT Polytechnic (2019–2021)</div>
        <div class="text-gray-200">Khóa chính ngành Sự kiện Billy (MCT) (2022–2023)</div>
      </div>
    </div>
    <div>
      <div class="text-xl font-bold text-yellow-400 mb-2">// TYPE</div>
      <div class="bg-gray-900 rounded-lg p-4 flex flex-wrap gap-4">
        <div class="flex flex-col items-center">
          <span>🎤</span>
          <span class="text-sm mt-1">Gala</span>
        </div>
        <div class="flex flex-col items-center">
          <span>🎭</span>
          <span class="text-sm mt-1">Drama stage</span>
        </div>
        <div class="flex flex-col items-center">
          <span>📚</span>
          <span class="text-sm mt-1">Training</span>
        </div>
        <div class="flex flex-col items-center">
          <span>💍</span>
          <span class="text-sm mt-1">Wedding</span>
        </div>
        <div class="flex flex-col items-center">
          <span>🤝</span>
          <span class="text-sm mt-1">Teambuilding</span>
        </div>
      </div>
    </div>
  </div>

  <!-- EQUIPMENT USED -->
  <div class="mt-12">
    <div class="text-xl font-bold text-yellow-400 mb-4">// EQUIPMENT USED</div>
    <div class="flex flex-wrap gap-8 justify-center">
      {#each equipment as eq}
        <div class="flex flex-col items-center">
          <img src={eq.img} alt={eq.label} class="w-32 h-32 object-cover rounded-full border-4 border-gray-700 shadow-lg" />
          <span class="mt-2 text-sm">{eq.label}</span>
        </div>
      {/each}
    </div>
  </div>

  <!-- BRANDS I HAVE WORKED WITH -->
  <div class="mt-12">
    <div class="text-xl font-bold text-yellow-400 mb-4">// BRANDS I HAVE WORKED WITH</div>
    <div class="grid grid-cols-2 md:grid-cols-4 gap-6 justify-items-center">
      {#each brands as brand}
        <div class="flex flex-col items-center">
          <div class="rounded-full border-4 border-yellow-400 p-2 bg-black shadow-lg">
            <img src={brand.img} alt={brand.label} class="w-16 h-16 object-contain" />
          </div>
          <span class="mt-2 text-xs text-center">{brand.label}</span>
        </div>
      {/each}
    </div>
  </div>

  <!-- SOME REAL PICTURES -->
  <div class="mt-12">
    <div class="text-xl font-bold text-yellow-400 mb-4">// SOME REAL PICTURES</div>
    <div class="grid grid-cols-1 md:grid-cols-2 gap-6">
      {#each realPics as pic}
        <img src={pic} alt="Real event" class="rounded-lg shadow-lg object-cover w-full h-56" />
      {/each}
    </div>
  </div>

  <!-- AGENCY CONNECT -->
  <div class="mt-12">
    <div class="text-xl font-bold text-yellow-400 mb-4">// AGENCY CONNECT</div>
    <div class="flex flex-wrap gap-8 justify-center">
      {#each agencies as ag}
        <div class="flex flex-col items-center">
          <div class="rounded-full border-4 border-yellow-400 p-2 bg-black shadow-lg">
            <img src={ag.img} alt={ag.label} class="w-16 h-16 object-contain" />
          </div>
          <span class="mt-2 text-xs text-center">{ag.label}</span>
        </div>
      {/each}
    </div>
  </div>

  <!-- BEST WORK WITH MC -->
  <div class="mt-12">
    <div class="text-xl font-bold text-yellow-400 mb-4">// BEST WORK WITH MC</div>
    <div class="flex flex-wrap gap-8 justify-center">
      {#each mcs as mc}
        <div class="flex flex-col items-center">
          <img src={mc.img} alt={mc.label} class="w-32 h-32 object-cover rounded-lg border-4 border-gray-700 shadow-lg" />
          <span class="mt-2 text-sm">{mc.label}</span>
        </div>
      {/each}
    </div>
  </div>

  <!-- THANK YOU -->
  <div class="mt-12 flex flex-col items-center">
    <div class="text-5xl font-extrabold text-yellow-400 drop-shadow-lg mb-4">Thank You</div>
    <div class="flex gap-4">
      <img src="https://i.imgur.com/dj1.png" alt="DJ" class="w-20 h-20 object-contain" />
      <img src="https://i.imgur.com/dj2.png" alt="MC" class="w-20 h-20 object-contain" />
      <!-- ... thêm các ảnh sticker khác nếu muốn ... -->
    </div>
    <div class="mt-2 text-yellow-400 italic">MusicController! [Cụm từ]: Người "chơi" nhạc!</div>
  </div>
</div>

<!-- Footer -->
<footer class="bg-gray-800 text-white py-6 text-center">
  <div>© 2024 Nguyễn Minh Trí. All rights reserved.</div>
</footer>

<style>
  @keyframes fade-in-up {
    0% { opacity: 0; transform: translateY(40px); }
    100% { opacity: 1; transform: translateY(0); }
  }
  .animate-fade-in-up {
    animation: fade-in-up 1s cubic-bezier(0.23, 1, 0.32, 1);
  }
  @keyframes fade-in {
    0% { opacity: 0; }
    100% { opacity: 1; }
  }
  .animate-fade-in {
    animation: fade-in 1s cubic-bezier(0.23, 1, 0.32, 1);
  }
  .delay-200 { animation-delay: 0.2s; }
  .delay-300 { animation-delay: 0.3s; }
  .delay-500 { animation-delay: 0.5s; }
</style>
