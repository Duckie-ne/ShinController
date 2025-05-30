<script>
  // Có thể thêm logic JS ở đây nếu cần
</script>

<!-- Header -->
<header class="bg-white shadow sticky top-0 z-50">
  <nav class="container mx-auto flex items-center justify-between px-4 py-3">
    <div class="font-bold text-xl text-blue-700">Nguyễn Minh Trí</div>
    <ul class="flex space-x-6">
      <li><a href="#" class="hover:text-blue-600">Home</a></li>
      <li><a href="#about" class="hover:text-blue-600">Về Mình</a></li>
      <li><a href="#posts" class="hover:text-blue-600">Bài Viết</a></li>
      <li><a href="#quotes" class="hover:text-blue-600">Châm Ngôn</a></li>
      <li><a href="#contact" class="hover:text-blue-600">Liên Hệ</a></li>
    </ul>
  </nav>
</header>

<!-- Hero & Giới thiệu -->
<section class="bg-gradient-to-r from-blue-100 to-purple-100 py-12 text-center">
  <div class="flex flex-col items-center animate-fade-in-up">
    <img src="https://ui-avatars.com/api/?name=Nguyen+Minh+Tri&background=3B82F6&color=fff&size=128" alt="Nguyễn Minh Trí" class="w-32 h-32 rounded-full mx-auto mb-4 shadow-lg border-4 border-white animate-bounce">
    <h1 class="text-3xl font-bold text-blue-700 mb-2 animate-fade-in">Nguyễn Minh Trí</h1>
    <h2 class="text-xl text-purple-600 mb-4 animate-fade-in delay-200">Backend Developer (Fresher)</h2>
    <p class="max-w-xl mx-auto text-gray-700 animate-fade-in delay-300">
      Xin chào! Mình là Trí, một Backend Developer yêu thích công nghệ, thích khám phá và chia sẻ kiến thức lập trình. Mình mong muốn xây dựng các hệ thống web hiệu quả, an toàn và dễ mở rộng.
    </p>
    <div class="flex justify-center gap-4 mt-6 animate-fade-in delay-500">
      <img src="https://images.unsplash.com/photo-1461749280684-dccba630e2f6?auto=format&fit=crop&w=400&q=80" alt="Coding" class="w-32 h-20 object-cover rounded-lg shadow-md border-2 border-blue-200">
      <img src="https://images.unsplash.com/photo-1519389950473-47ba0277781c?auto=format&fit=crop&w=400&q=80" alt="Teamwork" class="w-32 h-20 object-cover rounded-lg shadow-md border-2 border-purple-200">
    </div>
  </div>
</section>

<!-- Thông tin cá nhân -->
<section id="about" class="py-10 bg-white">
  <div class="container mx-auto grid md:grid-cols-3 gap-8 text-center">
    <div class="transition-transform duration-500 hover:scale-105">
      <img src="https://images.unsplash.com/photo-1513258496099-48168024aec0?auto=format&fit=crop&w=400&q=80" alt="Study" class="w-20 h-20 mx-auto rounded-full mb-2 object-cover shadow">
      <h3 class="font-semibold text-blue-600 mb-2">Ngành học</h3>
      <p class="text-gray-700">Cử nhân Công nghệ thông tin, Đại học ABC</p>
    </div>
    <div class="transition-transform duration-500 hover:scale-105">
      <img src="https://images.unsplash.com/photo-1519125323398-675f0ddb6308?auto=format&fit=crop&w=400&q=80" alt="Work" class="w-20 h-20 mx-auto rounded-full mb-2 object-cover shadow">
      <h3 class="font-semibold text-blue-600 mb-2">Công việc</h3>
      <p class="text-gray-700">Backend Developer (Fresher)</p>
    </div>
    <div class="transition-transform duration-500 hover:scale-105">
      <img src="https://images.unsplash.com/photo-1506744038136-46273834b3fb?auto=format&fit=crop&w=400&q=80" alt="Passion" class="w-20 h-20 mx-auto rounded-full mb-2 object-cover shadow">
      <h3 class="font-semibold text-blue-600 mb-2">Đam mê</h3>
      <p class="text-gray-700">Lập trình, đọc sách, du lịch, chia sẻ kiến thức</p>
    </div>
  </div>
</section>

<!-- Châm ngôn & lời nhắn nhủ -->
<section id="quotes" class="py-10 bg-blue-50">
  <div class="container mx-auto text-center">
    <h3 class="text-2xl font-bold text-purple-700 mb-4 animate-fade-in">Châm Ngôn</h3>
    <blockquote class="italic text-gray-600 mb-2 animate-fade-in delay-200">"Traveling – it leaves you speechless, then turns you into a storyteller." – Ibn Battuta</blockquote>
    <blockquote class="italic text-gray-600 animate-fade-in delay-300">"Knowledge of the past and of the places of the earth is the ornament and food of the mind of man." – Leonardo da Vinci</blockquote>
    <div class="flex justify-center gap-4 mt-6 animate-fade-in delay-500">
      <img src="https://images.unsplash.com/photo-1500534314209-a25ddb2bd429?auto=format&fit=crop&w=400&q=80" alt="Travel" class="w-32 h-20 object-cover rounded-lg shadow-md border-2 border-blue-200">
      <img src="https://images.unsplash.com/photo-1465101046530-73398c7f28ca?auto=format&fit=crop&w=400&q=80" alt="Book" class="w-32 h-20 object-cover rounded-lg shadow-md border-2 border-purple-200">
    </div>
  </div>
</section>

<!-- Bài viết nổi bật (mẫu) -->
<section id="posts" class="py-10 bg-white">
  <div class="container mx-auto">
    <h3 class="text-2xl font-bold text-blue-700 mb-6 text-center">Bài Viết Nổi Bật</h3>
    <div class="grid md:grid-cols-2 gap-6">
      <div class="bg-blue-100 p-4 rounded-lg shadow hover:shadow-xl transition-shadow duration-500 animate-fade-in-up">
        <img src="https://images.unsplash.com/photo-1465101178521-c1a9136a3fd9?auto=format&fit=crop&w=400&q=80" alt="Phú Quốc" class="w-full h-32 object-cover rounded mb-3">
        <h4 class="font-semibold text-blue-700 mb-2">DỊCH NHƯ VẦY CÓ NÊN ĐI PHÚ QUỐC?</h4>
        <p class="text-gray-700 text-sm">Hành trình đi Phú Quốc của mình được chốt kèo rất mông lung vì đặt vé máy bay xong vẫn không biết là có đi được hay không...</p>
      </div>
      <div class="bg-blue-100 p-4 rounded-lg shadow hover:shadow-xl transition-shadow duration-500 animate-fade-in-up delay-200">
        <img src="https://images.unsplash.com/photo-1519125323398-675f0ddb6308?auto=format&fit=crop&w=400&q=80" alt="Tiếng Anh" class="w-full h-32 object-cover rounded mb-3">
        <h4 class="font-semibold text-blue-700 mb-2">MẤT GỐC TIẾNG ANH PHẢI HỌC NHƯ THẾ NÀO?</h4>
        <p class="text-gray-700 text-sm">Đây là câu hỏi đi đâu mình cũng thấy. Nhân đây mình sẽ viết bài giải đáp giúp các bạn...</p>
      </div>
    </div>
  </div>
</section>

<!-- Form liên hệ -->
<section id="contact" class="py-10 bg-blue-50">
  <div class="container mx-auto max-w-md">
    <h3 class="text-2xl font-bold text-blue-700 mb-4 text-center">Liên Hệ</h3>
    <form class="space-y-4 animate-fade-in-up">
      <input type="text" placeholder="Họ tên" class="w-full p-2 rounded border border-gray-300 focus:border-blue-500" />
      <input type="email" placeholder="Email" class="w-full p-2 rounded border border-gray-300 focus:border-blue-500" />
      <textarea placeholder="Nội dung" class="w-full p-2 rounded border border-gray-300 focus:border-blue-500"></textarea>
      <button type="submit" class="w-full bg-blue-600 text-white py-2 rounded hover:bg-blue-700 transition">Gửi</button>
    </form>
  </div>
</section>

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
