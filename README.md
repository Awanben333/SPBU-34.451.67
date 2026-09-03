# SPBU-34.451.67
<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>SPBU 34.451.67 Kondangsari - Layanan BBM 24 Jam</title>
    <!-- Bootstrap 5 CSS -->
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css" rel="stylesheet">
    <!-- Font Awesome Icons -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <style>
        :root {
            --primary-red: #ed1c24;
            --primary-blue: #005baa;
            --primary-green: #23b14d;
            --dark-color: #212529;
            --light-bg: #f8f9fa;
        }

        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            color: var(--dark-color);
        }

        .navbar {
            box-shadow: 0 2px 10px rgba(0,0,0,0.1);
        }

        .navbar-brand span {
            font-weight: bold;
        }

        .text-red { color: var(--primary-red); }
        .text-blue { color: var(--primary-blue); }
        .text-green { color: var(--primary-green); }

        .hero-section {
            background: linear-gradient(rgba(0,0,0,0.6), rgba(0,0,0,0.6)), url('1788397131630.jpg') center/cover no-repeat;
            color: white;
            padding: 100px 0;
        }

        .card-img-top {
            height: 220px;
            object-fit: cover;
        }

        .feature-card {
            transition: transform 0.3s ease, box-shadow 0.3s ease;
            border: none;
            border-radius: 10px;
            overflow: hidden;
        }

        .feature-card:hover {
            transform: translateY(-5px);
            box-shadow: 0 10px 20px rgba(0,0,0,0.15) !important;
        }

        .badge-product {
            font-size: 0.9rem;
            padding: 8px 12px;
            border-radius: 20px;
        }

        .footer {
            background-color: #1a1a1a;
            color: #ccc;
        }
    </style>
</head>
<body>

    <!-- Header / Navbar -->
    <nav class="navbar navbar-expand-lg navbar-dark bg-dark sticky-top">
        <div class="container">
            <a class="navbar-brand d-flex align-items-center" href="#">
                <i class="fa-solid fa-gas-pump me-2 text-red fs-3"></i>
                <span>SPBU <span class="text-red">34.</span><span class="text-blue">451.</span><span class="text-green">67</span></span>
            </a>
            <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav">
                <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse" id="navbarNav">
                <ul class="navbar-nav ms-auto">
                    <li class="nav-item"><a class="nav-link active" href="#beranda">Beranda</a></li>
                    <li class="nav-item"><a class="nav-link" href="#produk">Produk BBM</a></li>
                    <li class="nav-item"><a class="nav-link" href="#galeri">Fasilitas & Galeri</a></li>
                    <li class="nav-item"><a class="nav-link" href="#lokasi">Lokasi & Kontak</a></li>
                </ul>
            </div>
        </div>
    </nav>

    <!-- Hero Section -->
    <header id="beranda" class="hero-section text-center">
        <div class="container">
            <h1 class="display-4 fw-bold mb-3">Selamat Datang di SPBU 34.451.67</h1>
            <p class="lead mb-4">Kondangsari, Beber, Cirebon — Melayani Anda 24 Jam dengan Bahan Bakar Berkualitas & Fasilitas Lengkap</p>
            <a href="#galeri" class="btn btn-danger btn-lg me-2"><i class="fa-solid fa-images me-2"></i>Lihat Galeri</a>
            <a href="#lokasi" class="btn btn-outline-light btn-lg"><i class="fa-solid fa-location-dot me-2"></i>Petunjuk Arah</a>
        </div>
    </header>

    <!-- Section Produk BBM -->
    <section id="produk" class="py-5">
        <div class="container">
            <div class="text-center mb-5">
                <h2 class="fw-bold">Produk Bahan Bakar</h2>
                <p class="text-muted">Pilihan BBM berkualitas tinggi untuk performa mesin kendaraan Anda</p>
            </div>
            <div class="row g-4 text-center">
                <div class="col-6 col-md-3">
                    <div class="p-3 border rounded shadow-sm bg-white">
                        <i class="fa-solid fa-droplet fs-1 text-primary mb-2"></i>
                        <h5 class="fw-bold">Pertalite</h5>
                        <span class="badge bg-primary badge-product">RON 90</span>
                    </div>
                </div>
                <div class="col-6 col-md-3">
                    <div class="p-3 border rounded shadow-sm bg-white">
                        <i class="fa-solid fa-droplet fs-1 text-blue mb-2"></i>
                        <h5 class="fw-bold">Pertamax</h5>
                        <span class="badge bg-info text-dark badge-product">RON 92</span>
                    </div>
                </div>
                <div class="col-6 col-md-3">
                    <div class="p-3 border rounded shadow-sm bg-white">
                        <i class="fa-solid fa-bolt fs-1 text-red mb-2"></i>
                        <h5 class="fw-bold">Pertamax Turbo</h5>
                        <span class="badge bg-danger badge-product">RON 98 / Top Tier</span>
                    </div>
                </div>
                <div class="col-6 col-md-3">
                    <div class="p-3 border rounded shadow-sm bg-white">
                        <i class="fa-solid fa-truck-monster fs-1 text-green mb-2"></i>
                        <h5 class="fw-bold">Pertamina Dex</h5>
                        <span class="badge bg-success badge-product">CN 53 / Top Tier</span>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Section Galeri & Fasilitas -->
    <section id="galeri" class="py-5 bg-light">
        <div class="container">
            <div class="text-center mb-5">
                <h2 class="fw-bold">Galeri & Fasilitas SPBU</h2>
                <p class="text-muted">Kenyamanan dan keamanan pengisian serta istirahat pelanggan adalah prioritas kami</p>
            </div>
            
            <div class="row g-4">
                <!-- Foto 1: Jalur Antrean BBM -->
                <div class="col-md-4">
                    <div class="card h-100 shadow-sm feature-card">
                        <img src="1788397521237.jpg" class="card-img-top" alt="Antrean Pengisian BBM Motor">
                        <div class="card-body">
                            <h5 class="card-title fw-bold"><i class="fa-solid fa-motorcycle text-blue me-2"></i>Pelayanan Jalur BBM</h5>
                            <p class="card-text text-muted">Jalur pengisian BBM teratur dan tertata rapi untuk kemudahan akses kendaraan roda dua maupun roda empat.</p>
                        </div>
                    </div>
                </div>

                <!-- Foto 2: Operator Bertugas -->
                <div class="col-md-4">
                    <div class="card h-100 shadow-sm feature-card">
                        <img src="1788397403397.jpg" class="card-img-top" alt="Operator SPBU Melayani Pengisian">
                        <div class="card-body">
                            <h5 class="card-title fw-bold"><i class="fa-solid fa-user-check text-red me-2"></i>Operator Sigap & Ramah</h5>
                            <p class="card-text text-muted">Petugas operator yang sigap, jujur, dan ramah siap memberikan pelayanan terbaik untuk Anda.</p>
                        </div>
                    </div>
                </div>

                <!-- Foto 3: Masjid Tampak Senja -->
                <div class="col-md-4">
                    <div class="card h-100 shadow-sm feature-card">
                        <img src="1788397487479.jpg" class="card-img-top" alt="Masjid Besar SPBU Tampak Senja">
                        <div class="card-body">
                            <h5 class="card-title fw-bold"><i class="fa-solid fa-mosque text-green me-2"></i>Masjid Besar & Nyaman</h5>
                            <p class="card-text text-muted">Tempat ibadah yang bersih, megah, dan sejuk untuk menunjang ibadah serta istirahat selama perjalanan.</p>
                        </div>
                    </div>
                </div>

                <!-- Foto 4: Kantin / Rest Area -->
                <div class="col-md-4">
                    <div class="card h-100 shadow-sm feature-card">
                        <img src="1788397320239.jpg" class="card-img-top" alt="Kantin dan Area Istirahat Outdoor">
                        <div class="card-body">
                            <h5 class="card-title fw-bold"><i class="fa-solid fa-utensils text-warning me-2"></i>Kantin & Rest Area</h5>
                            <p class="card-text text-muted">Area santai luar ruangan dilengkapi meja, kursi, serta aneka jajanan dan minuman untuk melepas lelah.</p>
                        </div>
                    </div>
                </div>

                <!-- Foto 5: Galeri ATM -->
                <div class="col-md-4">
                    <div class="card h-100 shadow-sm feature-card">
                        <img src="1788397349700.jpg" class="card-img-top" alt="Galeri ATM Center">
                        <div class="card-body">
                            <h5 class="card-title fw-bold"><i class="fa-solid fa-credit-card text-primary me-2"></i>Galeri ATM Center</h5>
                            <p class="card-text text-muted">Kemudahan penarikan uang tunai dan transaksi perbankan langsung di lingkungan area SPBU.</p>
                        </div>
                    </div>
                </div>

                <!-- Foto 6: Minimarket & Parkir Motor -->
                <div class="col-md-4">
                    <div class="card h-100 shadow-sm feature-card">
                        <img src="1788397266517.jpg" class="card-img-top" alt="Toko dan Area Parkir Motor">
                        <div class="card-body">
                            <h5 class="card-title fw-bold"><i class="fa-solid fa-store text-danger me-2"></i>Toko & Parkir Teratur</h5>
                            <p class="card-text text-muted">Tersedia toko kebutuhan berkendara/pelumas serta area parkir motor yang bersih dan tertata.</p>
                        </div>
                    </div>
                </div>

                <!-- Foto 7: Banner Malam Hari Full Width -->
                <div class="col-12">
                    <div class="card shadow-sm feature-card">
                        <img src="1788397131630.jpg" class="card-img-top" alt="Suasana SPBU Malam Hari" style="height: 380px;">
                        <div class="card-body text-center p-4">
                            <h4 class="card-title fw-bold"><i class="fa-solid fa-moon text-warning me-2"></i>Area Kuat Penerangan & Keamanan 24 Jam</h4>
                            <p class="card-text text-muted max-w-75 mx-auto">Halaman luas dengan sistem pencahayaan yang terang benderang serta dipantau CCTV demi memastikan kenyamanan, keselamatan, dan keamanan pengunjung di malam hari.</p>
                        </div>
                    </div>
                </div>

            </div>
        </div>
    </section>

    <!-- Section Lokasi & Footer -->
    <footer id="lokasi" class="footer pt-5 pb-3">
        <div class="container">
            <div class="row g-4 mb-4">
                <div class="col-md-6">
                    <h4 class="text-white mb-3">SPBU 34.451.67 Kondangsari</h4>
                    <p><i class="fa-solid fa-location-dot me-2 text-red"></i>Jl. Raya Beber - Kuningan, Kondangsari, Kec. Beber, Kabupaten Cirebon, Jawa Barat</p>
                    <p><i class="fa-solid fa-clock me-2 text-blue"></i>Jam Operasional: <strong>24 Jam Nonstop</strong></p>
                    <p><i class="fa-solid fa-shield-halved me-2 text-green"></i>Fasilitas Pendukung: CCTV 24 Jam, Toilet Clean & Good, Masjid Besar, Kantin, Galeri ATM, Parkir Luas.</p>
                </div>
                <div class="col-md-6">
                    <h5 class="text-white mb-3">Peta Lokasi</h5>
                    <div class="ratio ratio-16x9 rounded overflow-hidden">
                        <iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d15848.472718116513!2d108.5471!3d-6.7905!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x2e6f1d24a9a08e1f%3A0x401e8f1fc28c890!2sKondangsari%2C%20Beber%2C%20Cirebon!5e0!3m2!1sid!2sid!4v1700000000000!5m2!1sid!2sid" allowfullscreen="" loading="lazy"></iframe>
                    </div>
                </div>
            </div>
            <hr class="bg-secondary">
            <div class="text-center text-muted">
                <small>&copy; 2026 SPBU 34.451.67 Kondangsari, Beber, Cirebon. All Rights Reserved.</small>
            </div>
        </div>
    </footer>

    <!-- Bootstrap 5 JS Bundle -->
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/bootstrap.bundle.min.js"></script>
</body>
</html>
