<!doctype html>
<html lang="id">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>SPA Industri — Solusi Perlengkapan & Layanan</title>
  <meta name="description" content="Penyedia alat & perlengkapan SPA industri: peralatan spa profesional, meja terapi, steam bath, mesin hidroterapi, dan layanan instalasi & pemeliharaan." />
  <link href="https://cdn.jsdelivr.net/npm/tailwindcss@2.2.19/dist/tailwind.min.css" rel="stylesheet">
  <style>
    /* Simple hero background gradient */
    .hero-bg{ background: linear-gradient(135deg,#0f172a 0%, #0ea5a4 100%); }
    .card-shadow{ box-shadow: 0 6px 18px rgba(2,6,23,0.16); }
  </style>
</head>
<body class="antialiased text-gray-800">
  <!-- NAV -->
  <nav class="bg-white shadow-sm">
    <div class="max-w-7xl mx-auto px-6 py-4 flex items-center justify-between">
      <div class="flex items-center space-x-3">
        <div class="w-10 h-10 rounded-md bg-gradient-to-br from-teal-400 to-cyan-600 flex items-center justify-center text-white font-bold">SP</div>
        <div>
          <a href="#" class="font-semibold text-lg">SPA Industri</a>
          <div class="text-xs text-gray-500">Perlengkapan & Solusi Profesional</div>
        </div>
      </div>
      <div class="hidden md:flex items-center space-x-6 text-sm">
        <a href="#services" class="hover:text-teal-600">Layanan</a>
        <a href="#equipment" class="hover:text-teal-600">Peralatan</a>
        <a href="#about" class="hover:text-teal-600">Tentang</a>
        <a href="#contact" class="text-white bg-teal-600 px-4 py-2 rounded-md">Hubungi</a>
      </div>
      <div class="md:hidden">
        <button id="menuBtn" class="p-2">☰</button>
      </div>
    </div>
  </nav>

  <!-- HERO -->
  <header class="hero-bg text-white">
    <div class="max-w-7xl mx-auto px-6 py-20 lg:py-28 flex flex-col lg:flex-row items-center gap-12">
      <div class="w-full lg:w-1/2">
        <h1 class="text-4xl lg:text-5xl font-extrabold leading-tight">Solusi Perlengkapan SPA Industri — <span class="text-teal-200">Meningkatkan efisiensi & kenyamanan</span></h1>
        <p class="mt-6 text-gray-100">Kami menyediakan alat spa skala industri: meja perawatan, bath hidroterapi, steam room, sistem filtrasi, dan layanan instalasi & maintenance. Cocok untuk hotel, klinik, pusat rehabilitasi, dan fasilitas kebugaran besar.</p>
        <div class="mt-8 flex space-x-4">
          <a href="#equipment" class="bg-white text-teal-700 px-5 py-3 rounded-md font-semibold">Lihat Peralatan</a>
          <a href="#contact" class="border border-white px-5 py-3 rounded-md">Minta Penawaran</a>
        </div>
        <ul class="mt-8 grid grid-cols-1 sm:grid-cols-2 gap-3 text-sm text-teal-50">
          <li>✅ Garansi & dukungan teknis</li>
          <li>✅ Pengiriman & instalasi</li>
          <li>✅ Training operator</li>
          <li>✅ Suku cadang tersedia</li>
        </ul>
      </div>
      <div class="w-full lg:w-1/2">
        <img src="https://images.unsplash.com/photo-1542736667-069246bdbc75?q=80&w=1200&auto=format&fit=crop&ixlib=rb-4.0.3&s=placeholder" alt="Perlengkapan SPA Industri" class="rounded-2xl shadow-2xl w-full object-cover" />
      </div>
    </div>
  </header>

  <!-- SERVICES -->
  <section id="services" class="max-w-7xl mx-auto px-6 py-16">
    <h2 class="text-2xl font-bold">Layanan Kami</h2>
    <p class="text-gray-600 mt-2 max-w-2xl">Dari perencanaan ruang SPA berskala besar sampai pemasangan dan pemeliharaan harian — layanan lengkap untuk kebutuhan industri Anda.</p>
    <div class="mt-8 grid grid-cols-1 md:grid-cols-3 gap-6">
      <div class="p-6 bg-white rounded-lg card-shadow">
        <h3 class="font-semibold">Rancang & Konsultasi</h3>
        <p class="text-sm text-gray-600 mt-2">Analisa tata letak, pemilihan alat, dan perencanaan alur kerja untuk efisiensi operasional.</p>
      </div>
      <div class="p-6 bg-white rounded-lg card-shadow">
        <h3 class="font-semibold">Supply & Instalasi</h3>
        <p class="text-sm text-gray-600 mt-2">Pengadaan peralatan bersertifikat dan instalasi oleh teknisi berpengalaman.</p>
      </div>
      <div class="p-6 bg-white rounded-lg card-shadow">
        <h3 class="font-semibold">Maintenance & Spareparts</h3>
        <p class="text-sm text-gray-600 mt-2">Kontrak pemeliharaan berkala, pelatihan operator, dan suku cadang asli.</p>
      </div>
    </div>
  </section>

  <!-- EQUIPMENT CATALOG -->
  <section id="equipment" class="bg-gray-50 py-16">
    <div class="max-w-7xl mx-auto px-6">
      <div class="flex items-center justify-between">
        <div>
          <h2 class="text-2xl font-bold">Peralatan & Perlengkapan</h2>
          <p class="text-gray-600 mt-1">Katalog singkat produk unggulan kami. Klik "Minta Penawaran" pada item untuk konsultasi harga & ketersediaan.</p>
        </div>
        <div class="flex space-x-2">
          <button class="px-4 py-2 border rounded-md text-sm">Filter: Semua</button>
          <button class="px-4 py-2 border rounded-md text-sm">Filter: Meja & Kursi</button>
        </div>
      </div>

      <div class="mt-8 grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-3 gap-6">
        <!-- Card template repeated -->
        <article class="bg-white rounded-lg p-5 card-shadow">
          <img src="https://images.unsplash.com/photo-1542314831-068cd1dbfeeb?q=80&w=1200&auto=format&fit=crop&ixlib=rb-4.0.3&s=placeholder" alt="Meja Terapi Stainless" class="w-full h-48 object-cover rounded-md" />
          <h3 class="mt-4 font-semibold">Meja Terapi Industrial - Stainless</h3>
          <p class="text-sm text-gray-600 mt-2">Meja kuat untuk operasi 24/7, kerangka stainless steel, lapisan anti-korosi, beban hingga 250 kg.</p>
          <ul class="text-xs text-gray-500 mt-3">
            <li>Dimensi: 200 x 75 x 80 cm</li>
            <li>Material: SUS 304</li>
            <li>Garansi: 2 tahun</li>
          </ul>
          <div class="mt-4 flex items-center justify-between">
            <div class="text-sm font-semibold">Mulai dari: Rp 12.500.000</div>
            <a href="#contact" class="text-sm bg-teal-600 text-white px-3 py-2 rounded-md">Minta Penawaran</a>
          </div>
        </article>

        <article class="bg-white rounded-lg p-5 card-shadow">
          <img src="https://images.unsplash.com/photo-1505691723518-36a9c3b0b8a6?q=80&w=1200&auto=format&fit=crop&ixlib=rb-4.0.3&s=placeholder" alt="Steam Room" class="w-full h-48 object-cover rounded-md" />
          <h3 class="mt-4 font-semibold">Kabinet Steam Room Industri</h3>
          <p class="text-sm text-gray-600 mt-2">Sistem steam terintegrasi untuk ruangan berskala besar, kontrol kelembaban & suhu otomatis.</p>
          <ul class="text-xs text-gray-500 mt-3">
            <li>Kapasitas: sampai 20 orang</li>
            <li>Control panel digital</li>
            <li>Material: Fiberglass / Stainless</li>
          </ul>
          <div class="mt-4 flex items-center justify-between">
            <div class="text-sm font-semibold">Mulai dari: Rp 65.000.000</div>
            <a href="#contact" class="text-sm bg-teal-600 text-white px-3 py-2 rounded-md">Minta Penawaran</a>
          </div>
        </article>

        <article class="bg-white rounded-lg p-5 card-shadow">
          <img src="https://images.unsplash.com/photo-1515378791036-0648a3ef77b2?q=80&w=1200&auto=format&fit=crop&ixlib=rb-4.0.3&s=placeholder" alt="Hydrotherapy" class="w-full h-48 object-cover rounded-md" />
          <h3 class="mt-4 font-semibold">Bath Hidroterapi Industrial</h3>
          <p class="text-sm text-gray-600 mt-2">Unit bathtub berkapasitas besar dengan jet terkontrol, sistem filtrasi 3-lapis, dan pemanas efisien.</p>
          <ul class="text-xs text-gray-500 mt-3">
            <li>Volume: 800 - 1500 L</li>
            <li>Material: Acrylic reinforced</li>
            <li>Opsional: Ozone / UV sanitasi</li>
          </ul>
          <div class="mt-4 flex items-center justify-between">
            <div class="text-sm font-semibold">Mulai dari: Rp 45.000.000</div>
            <a href="#contact" class="text-sm bg-teal-600 text-white px-3 py-2 rounded-md">Minta Penawaran</a>
          </div>
        </article>

        <!-- add more product cards as needed -->

      </div>
    </div>
  </section>

  <!-- ABOUT -->
  <section id="about" class="max-w-7xl mx-auto px-6 py-16">
    <h2 class="text-2xl font-bold">Tentang Kami</h2>
    <p class="text-gray-600 mt-2 max-w-3xl">Dengan pengalaman bertahun-tahun melayani hotel & pusat kebugaran berskala besar, kami memahami kebutuhan operasional industri SPA: keandalan, keamanan, dan dukungan purna jual. Tim kami terdiri dari insinyur mekanikal, teknisi HVAC, dan spesialis sanitasi.</p>
    <div class="mt-8 grid grid-cols-1 md:grid-cols-3 gap-6">
      <div class="p-6 bg-white rounded-lg card-shadow">
        <h3 class="font-semibold">Sertifikasi</h3>
        <p class="text-sm text-gray-600 mt-2">Produk bersertifikat internasional dan standar keselamatan.</p>
      </div>
      <div class="p-6 bg-white rounded-lg card-shadow">
        <h3 class="font-semibold">Tim Teknis</h3>
        <p class="text-sm text-gray-600 mt-2">Teknisi terlatih untuk instalasi & service 24/7.</p>
      </div>
      <div class="p-6 bg-white rounded-lg card-shadow">
        <h3 class="font-semibold">Logistik</h3>
        <p class="text-sm text-gray-600 mt-2">Distribusi ke seluruh Indonesia dengan partner logistik terpercaya.</p>
      </div>
    </div>
  </section>

  <!-- CONTACT -->
  <section id="contact" class="bg-white py-16">
    <div class="max-w-7xl mx-auto px-6 grid grid-cols-1 lg:grid-cols-2 gap-10">
      <div>
        <h2 class="text-2xl font-bold">Minta Penawaran / Kontak</h2>
        <p class="text-gray-600 mt-2">Isi form di bawah atau hubungi kami langsung via email / telepon untuk konsultasi gratis.</p>
        <div class="mt-6 space-y-4">
          <p class="text-sm"><strong>Email:</strong> sales@spaindustri.co.id</p>
          <p class="text-sm"><strong>Telepon:</strong> +62 812-3456-7890</p>
          <p class="text-sm"><strong>Alamat:</strong> Kawasan Industri, Jakarta</p>
        </div>
      </div>
      <div>
        <form action="#" onsubmit="alert('Form terkirim (demo). Kami akan hubungi Anda segera.'); return false;" class="bg-gray-50 p-6 rounded-lg">
          <div class="grid grid-cols-1 gap-3">
            <input required type="text" placeholder="Nama Perusahaan / Anda" class="p-3 rounded border" />
            <input required type="email" placeholder="Email" class="p-3 rounded border" />
            <input required type="tel" placeholder="Telepon" class="p-3 rounded border" />
            <select class="p-3 rounded border">
              <option>Butuh: (pilih)</option>
              <option>Pengadaan & Instalasi</option>
              <option>Maintenance</option>
              <option>Konsultasi Tata Ruang</option>
            </select>
            <textarea placeholder="Pesan / Spesifikasi singkat" class="p-3 rounded border" rows="4"></textarea>
            <button type="submit" class="bg-teal-600 text-white px-4 py-3 rounded font-semibold">Kirim Permintaan</button>
          </div>
        </form>
      </div>
    </div>
  </section>

  <!-- FAQ -->
  <section class="max-w-7xl mx-auto px-6 py-12">
    <h2 class="text-2xl font-bold">FAQ singkat</h2>
    <div class="mt-6 grid grid-cols-1 md:grid-cols-2 gap-6">
      <div class="bg-white p-4 rounded-lg card-shadow">
        <h4 class="font-semibold">Apakah kalian menyediakan instalasi?</h4>
        <p class="text-sm text-gray-600 mt-2">Ya, kami menyediakan paket instalasi lengkap dan pelatihan operator untuk setiap unit yang dipasok.</p>
      </div>
      <div class="bg-white p-4 rounded-lg card-shadow">
        <h4 class="font-semibold">Apakah suku cadang tersedia?</h4>
        <p class="text-sm text-gray-600 mt-2">Kami menyimpan suku cadang utama dan juga menyediakan kontrak pemeliharaan berkala.</p>
      </div>
    </div>
  </section>

  <!-- FOOTER -->
  <footer class="bg-gray-900 text-gray-200 py-8">
    <div class="max-w-7xl mx-auto px-6 flex flex-col md:flex-row justify-between items-center">
      <div>
        <div class="font-semibold">SPA Industri</div>
        <div class="text-sm text-gray-400">© 2025 SPA Industri. Semua hak dilindungi.</div>
      </div>
      <div class="mt-4 md:mt-0 text-sm text-gray-400">Follow kami: Instagram • LinkedIn • Facebook</div>
    </div>
  </footer>

  <script>
    // simple mobile menu toggle
    document.getElementById('menuBtn')?.addEventListener('click', function(){
      alert('Menu (demo) — untuk navigasi mobile tambahkan JS / CSS sesuai kebutuhan.');
    });
  </script>
</body>
</html>
