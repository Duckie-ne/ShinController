<script>
  // Có thể thêm logic JS ở đây nếu cần
</script>

<!-- Header -->
<header class="bg-white shadow sticky top-0 z-50">
  <nav class="container mx-auto flex items-center justify-between px-4 py-3">
    <div class="font-bold text-xl text-blue-700">Nguyễn Minh Trí</div>
    <ul class="flex space-x-6">
      <li><a href="#about" class="hover:text-blue-600">Về Mình</a></li>
      <li><a href="#projects" class="hover:text-blue-600">Dự Án</a></li>
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
      Xin chào! Mình là Trí, một Backend Developer level Fresher, đam mê xây dựng hệ thống web hiệu quả, an toàn và dễ mở rộng. Mình yêu thích học hỏi công nghệ mới và luôn sẵn sàng tham gia các dự án thực tế.
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
    <div>
      <h3 class="font-semibold text-blue-600 mb-2">Kỹ năng</h3>
      <ul class="text-gray-700 list-disc list-inside text-left inline-block">
        <li>Node.js / Express</li>
        <li>RESTful API</li>
        <li>MySQL, MongoDB</li>
        <li>Git, CI/CD cơ bản</li>
        <li>Docker (cơ bản)</li>
      </ul>
    </div>
    <div>
      <h3 class="font-semibold text-blue-600 mb-2">Học vấn</h3>
      <p class="text-gray-700">Cử nhân Công nghệ thông tin, Đại học ABC</p>
    </div>
    <div>
      <h3 class="font-semibold text-blue-600 mb-2">Mục tiêu</h3>
      <ul class="text-gray-700 list-disc list-inside text-left inline-block">
        <li>Trở thành Backend Developer chuyên nghiệp</li>
        <li>Tham gia các dự án thực tế</li>
        <li>Không ngừng học hỏi công nghệ mới</li>
      </ul>
    </div>
  </div>
</section>

<!-- Dự án -->
<section id="projects" class="py-10 bg-blue-50">
  <div class="container mx-auto">
    <h3 class="text-2xl font-bold text-blue-700 mb-6 text-center">Dự Án Đã Làm</h3>
    <div class="grid md:grid-cols-2 gap-6">
      <div class="bg-white p-6 rounded-lg shadow hover:shadow-xl transition-shadow duration-500">
        <h4 class="font-semibold text-blue-700 mb-2">Quản lý sinh viên</h4>
        <p class="text-gray-700 text-sm mb-2">Xây dựng RESTful API quản lý sinh viên, phân quyền, xác thực JWT, CRUD dữ liệu.</p>
        <a href="#" class="text-blue-600 hover:underline" target="_blank">Xem trên GitHub</a>
      </div>
      <div class="bg-white p-6 rounded-lg shadow hover:shadow-xl transition-shadow duration-500">
        <h4 class="font-semibold text-blue-700 mb-2">Blog API</h4>
        <p class="text-gray-700 text-sm mb-2">API cho ứng dụng blog, hỗ trợ đăng nhập, đăng ký, tạo bài viết, bình luận.</p>
        <a href="#" class="text-blue-600 hover:underline" target="_blank">Xem trên GitHub</a>
      </div>
      <!-- Thêm các dự án khác tại đây -->
    </div>
  </div>
</section>

<!-- Liên hệ -->
<section id="contact" class="py-10 bg-white">
  <div class="container mx-auto max-w-md">
    <h3 class="text-2xl font-bold text-blue-700 mb-4 text-center">Liên Hệ</h3>
    <form class="space-y-4">
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
