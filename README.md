<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Portofolio - Sudirman</title>
    <!-- Memuat Tailwind CSS untuk styling -->
    <script src="https://cdn.tailwindcss.com"></script>
    <!-- Memuat Google Fonts (Inter) -->
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700;800;900&display=swap" rel="stylesheet">
    <style>
        /* Menggunakan font Inter sebagai default */
        body {
            font-family: 'Inter', sans-serif;
        }
    </style>
</head>
<body class="bg-gray-50 text-gray-800">

    <div class="min-h-screen p-6 md:p-12">
      <!-- Header Section -->
      <header class="max-w-5xl mx-auto flex flex-col md:flex-row items-center gap-6 md:gap-8">
        <!-- Profile Initial with Accent Color -->
        <div class="w-32 h-32 md:w-40 md:h-40 rounded-full bg-blue-600 text-white shadow-lg flex items-center justify-center text-5xl md:text-6xl font-bold border-4 border-white">
          S
        </div>
        <div class="text-center md:text-left">
          <h1 class="text-3xl md:text-4xl font-extrabold text-slate-900">Sudirman</h1>
          <p class="text-base md:text-lg text-slate-600 mt-1">Administration & Data Integration</p>
          <!-- Contact Info with Icons -->
          <div class="mt-4 flex flex-wrap justify-center md:justify-start gap-x-4 gap-y-2 items-center">
            <a href="mailto:markomini4@gmail.com" class="flex items-center gap-1.5 text-sm text-slate-700 hover:text-blue-600 transition-colors">
                <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="text-slate-500"><rect x="2" y="4" width="20" height="16" rx="2"></rect><path d="m22 7-8.97 5.7a1.94 1.94 0 0 1-2.06 0L2 7"></path></svg>
                <span>markomini4@gmail.com</span>
            </a>
            <span class="text-sm text-slate-400 hidden md:inline">•</span>
            <a href="tel:+6282293612818" class="flex items-center gap-1.5 text-sm text-slate-700 hover:text-blue-600 transition-colors">
                <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="text-slate-500"><path d="M22 16.92v3a2 2 0 0 1-2.18 2 19.79 19.79 0 0 1-8.63-3.07 19.5 19.5 0 0 1-6-6 19.79 19.79 0 0 1-3.07-8.67A2 2 0 0 1 4.11 2h3a2 2 0 0 1 2 1.72 12.84 12.84 0 0 0 .7 2.81 2 2 0 0 1-.45 2.11L8.09 9.91a16 16 0 0 0 6 6l1.27-1.27a2 2 0 0 1 2.11-.45 12.84 12.84 0 0 0 2.81.7A2 2 0 0 1 22 16.92z"></path></svg>
                <span>+62 822 9361 2818</span>
            </a>
          </div>
        </div>
      </header>

      <!-- Main Content -->
      <main class="max-w-5xl mx-auto mt-10 grid grid-cols-1 md:grid-cols-3 gap-8">
        <!-- Kolom Kiri: Tentang, Pengalaman, Proyek -->
        <section class="md:col-span-2 space-y-8">
          <!-- About Me Section -->
          <div class="bg-white p-6 md:p-8 rounded-2xl shadow-sm">
            <h2 class="text-xl font-semibold border-b pb-3 text-slate-800">Tentang Saya</h2>
            <p class="text-sm text-slate-700 leading-relaxed mt-4">
              Membuat web cepat dengan AI dan integrasi data: Mahir memanfaatkan AI generatif dan mengintegrasikan Google Sheets/Spreadsheet, membuat function pada Apps Scrip pada Google Sheets/Spreadsheet. Terampil membuat otomatisasi aplikasi web dan aset konten digital sederhana menggunakan Canva.
            </p>
          </div>

          <!-- Work Experience Section -->
          <div class="bg-white p-6 md:p-8 rounded-2xl shadow-sm">
            <h3 class="text-xl font-semibold text-slate-800 border-b pb-3">Pengalaman Kerja</h3>
            <div class="mt-4 space-y-5">
              <!-- Pengalaman 1 -->
              <article class="p-4 border border-gray-200 rounded-lg transition-shadow hover:shadow-md">
                <div class="flex justify-between items-start">
                  <div>
                    <h4 class="font-semibold text-slate-900">Operator Komputer / Administrasi</h4>
                    <p class="text-sm text-slate-600">CV. Rangga Bante Consultant</p>
                  </div>
                  <p class="text-xs text-slate-500 bg-slate-100 px-2 py-1 rounded-full">2022 - 2024</p>
                </div>
                <ul class="mt-3 text-sm text-slate-700 list-disc list-inside space-y-1.5">
                  <li>Membuat laporan harian, mingguan, dan bulanan</li>
                  <li>Menyusun invoice, pengolahan data, dan membuat jadwal pelaksanaan</li>
                  <li>Menyusun, mereview, dan mengelola kontrak kerja</li>
                </ul>
              </article>
              <!-- Pengalaman 2 (Date Corrected) -->
              <article class="p-4 border border-gray-200 rounded-lg transition-shadow hover:shadow-md">
                <div class="flex justify-between items-start">
                  <div>
                    <h4 class="font-semibold text-slate-900">Pramuniaga (Dept. Store)</h4>
                    <p class="text-sm text-slate-600">PT. Matahari</p>
                  </div>
                  <p class="text-xs text-slate-500 bg-slate-100 px-2 py-1 rounded-full">Agustus 2024 – Januari 2025</p>
                </div>
                <ul class="mt-3 text-sm text-slate-700 list-disc list-inside space-y-1.5">
                  <li>Melayani customer</li>
                  <li>Merapikan area pajangan</li>
                  <li>Mendata barang keluar & masuk</li>
                </ul>
              </article>
              <!-- Pengalaman 3 (Date Corrected) -->
              <article class="p-4 border border-gray-200 rounded-lg transition-shadow hover:shadow-md">
                <div class="flex justify-between items-start">
                  <div>
                    <h4 class="font-semibold text-slate-900">CPC (Cash Processing Center)</h4>
                    <p class="text-sm text-slate-600">PT. Bringin Gigantara</p>
                  </div>
                   <p class="text-xs text-slate-500 bg-slate-100 px-2 py-1 rounded-full">Februari 2025 – Mei 2025</p>
                </div>
                <ul class="mt-3 text-sm text-slate-700 list-disc list-inside space-y-1.5">
                  <li>Menyiapkan perlengkapan & dokumen penambahan kas</li>
                  <li>Menghitung & menyortir uang</li>
                  <li>Melakukan packing uang untuk mesin ATM dan membuat laporan temuan uang rusak/palsu</li>
                </ul>
              </article>
            </div>
          </div>
          
          <!-- NEW: Projects Section -->
           <div class="bg-white p-6 md:p-8 rounded-2xl shadow-sm">
            <h3 class="text-xl font-semibold text-slate-800 border-b pb-3">Proyek</h3>
            <div class="mt-4 space-y-5">
              <!-- Project 1 -->
              <article class="p-4 border border-gray-200 rounded-lg transition-shadow hover:shadow-md">
                <div class="flex justify-between items-start">
                  <div>
                    <h4 class="font-semibold text-slate-900">Web Otomatisasi Laporan</h4>
                    <p class="text-sm text-slate-600">Integrasi Google Sheets & Web App</p>
                  </div>
                  <p class="text-xs text-slate-500 bg-slate-100 px-2 py-1 rounded-full">2023</p>
                </div>
                <p class="mt-3 text-sm text-slate-700">
                  Membangun sebuah aplikasi web sederhana yang terhubung langsung dengan Google Sheets. Aplikasi ini memungkinkan tim untuk memasukkan data harian melalui form web, dan data tersebut secara otomatis diolah dan divisualisasikan menggunakan Google Apps Script, mengurangi pekerjaan manual hingga 80%.
                </p>
                <div class="mt-3 flex flex-wrap gap-2">
                  <span class="text-xs text-blue-800 bg-blue-100 rounded-full px-2.5 py-1 font-medium">Google Sheets</span>
                  <span class="text-xs text-green-800 bg-green-100 rounded-full px-2.5 py-1 font-medium">Apps Script</span>
                  <span class="text-xs text-indigo-800 bg-indigo-100 rounded-full px-2.5 py-1 font-medium">HTML/CSS</span>
                </div>
              </article>
              <!-- Project 2 -->
              <article class="p-4 border border-gray-200 rounded-lg transition-shadow hover:shadow-md">
                 <div class="flex justify-between items-start">
                  <div>
                    <h4 class="font-semibold text-slate-900">Desain Aset Digital untuk Media Sosial</h4>
                    <p class="text-sm text-slate-600">Canva Design</p>
                  </div>
                  <p class="text-xs text-slate-500 bg-slate-100 px-2 py-1 rounded-full">2024</p>
                </div>
                <p class="mt-3 text-sm text-slate-700">
                  Membuat serangkaian template konten untuk media sosial (Instagram Posts & Stories) menggunakan Canva. Desain ini membantu meningkatkan engagement audiens dan menjaga konsistensi brand secara visual.
                </p>
                 <div class="mt-3 flex flex-wrap gap-2">
                  <span class="text-xs text-purple-800 bg-purple-100 rounded-full px-2.5 py-1 font-medium">Canva</span>
                  <span class="text-xs text-pink-800 bg-pink-100 rounded-full px-2.5 py-1 font-medium">Branding</span>
                  <span class="text-xs text-yellow-800 bg-yellow-100 rounded-full px-2.5 py-1 font-medium">Social Media</span>
                </div>
              </article>
            </div>
          </div>
        </section>

        <!-- Kolom Kanan: Skills, Info Kontak, dll. -->
        <aside class="space-y-8">
            <div class="bg-white p-6 rounded-2xl shadow-sm">
                <h3 class="font-semibold text-slate-800 border-b pb-2">Keahlian</h3>
                <ul class="mt-4 flex flex-wrap gap-2">
                    <li class="text-xs text-slate-700 bg-slate-100 rounded-full px-3 py-1.5">Web cepat & integrasi data</li>
                    <li class="text-xs text-slate-700 bg-slate-100 rounded-full px-3 py-1.5">Google Sheets ↔ Web</li>
                    <li class="text-xs text-slate-700 bg-slate-100 rounded-full px-3 py-1.5">Automasi aplikasi & kalkulasi</li>
                    <li class="text-xs text-slate-700 bg-slate-100 rounded-full px-3 py-1.5">AI generatif (Gemini)</li>
                    <li class="text-xs text-slate-700 bg-slate-100 rounded-full px-3 py-1.5">Desain dasar dengan Canva</li>
                    <li class="text-xs text-slate-700 bg-slate-100 rounded-full px-3 py-1.5">Administrasi & laporan</li>
                </ul>
            </div>

            <div class="bg-white p-6 rounded-2xl shadow-sm">
                <h3 class="font-semibold text-slate-800 border-b pb-2">Info & Pendidikan</h3>
                <ul class="text-sm text-slate-600 mt-4 space-y-2">
                    <li><strong>Tempat Lahir:</strong> Palu</li>
                    <li><strong>Tanggal Lahir:</strong> 03 Juni 2000</li>
                    <li><strong>Lokasi:</strong> Indonesia</li>
                    <li class="pt-2"><strong>Pendidikan:</strong> Univ. Haluoleo — Budidaya Perairan (2018 - 2023)</li>
                </ul>
            </div>
            
            <div class="bg-white p-6 rounded-2xl shadow-sm">
                 <h3 class="font-semibold text-slate-800 border-b pb-2">Ekstra</h3>
                 <p class="text-sm text-slate-600 mt-3">
                 <button id="downloadBtn" class="mt-4 w-full py-2.5 rounded-lg bg-slate-800 text-white text-sm font-semibold hover:bg-slate-700 transition-colors">
                   Download Resume (PDF)
                 </button>
            </div>
        </aside>
      </main>

      <!-- Footer -->
      <footer class="max-w-5xl mx-auto mt-12 mb-6 text-center text-sm text-slate-500">
        © <span id="current-year"></span> Sudirman
      </footer>
    </div>
    
    <!-- NEW: Modal for Download Button -->
    <div id="alertModal" class="fixed inset-0 bg-black bg-opacity-50 flex items-center justify-center p-4 hidden z-50">
      <div class="bg-white rounded-xl shadow-lg p-6 md:p-8 max-w-sm w-full text-center">
        <h3 class="text-lg font-semibold text-slate-800">Segera Hadir</h3>
        <p class="text-sm text-slate-600 mt-2">
          Fitur untuk mengunduh resume dalam format PDF saat ini sedang dalam pengembangan. Terima kasih atas pengertian Anda!
        </p>
        <button id="closeModalBtn" class="mt-6 w-full py-2 px-4 bg-blue-600 text-white rounded-lg hover:bg-blue-700 transition-colors text-sm font-semibold">
          Mengerti
        </button>
      </div>
    </div>

    <script>
        // Menampilkan tahun saat ini di footer secara dinamis
        document.getElementById('current-year').textContent = new Date().getFullYear();

        // --- NEW: Modal Logic ---
        const downloadBtn = document.getElementById('downloadBtn');
        const alertModal = document.getElementById('alertModal');
        const closeModalBtn = document.getElementById('closeModalBtn');

        // Show modal when download button is clicked
        downloadBtn.addEventListener('click', () => {
            alertModal.classList.remove('hidden');
        });

        // Hide modal when close button is clicked
        closeModalBtn.addEventListener('click', () => {
            alertModal.classList.add('hidden');
        });

        // Hide modal when clicking on the background overlay
        alertModal.addEventListener('click', (event) => {
            if (event.target === alertModal) {
                alertModal.classList.add('hidden');
            }
        });
    </script>

</body>
</html>
