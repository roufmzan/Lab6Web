# Nama : RO'UF MMUHAMMAD FAUZAN
# NIM : 312410157
# Kelas : TI.24.A1

**Hasil Output**
<img width="1440" height="900" alt="Jepretan Layar 2025-10-28 pukul 00 25 59" src="https://github.com/user-attachments/assets/d0e629d0-afed-44fc-aa0b-112862cb884d" />


**Codingan**
**Home.html**
``` python
<!doctype html>
<html lang="id">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Layout Sederhana</title>

  <!-- Bootstrap CSS -->
  <link
    href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css"
    rel="stylesheet"
    integrity="sha384-QWTKZyjpPEjISv5WaRU9OFeRpok6YctnYmDr5pNlyT2bRjXh0JMhjY6hW+ALEwIH"
    crossorigin="anonymous"
  />

  <!-- Custom CSS -->
  <link rel="stylesheet" href="bootstrap.min.css" />
</head>
<body class="bg-page">

  <!-- Brand bar -->
  <header class="brandbar">
    <div class="container">
      <h1 class="brandtitle">Layout Sederhana</h1>
    </div>
  </header>

  <!-- Navbar -->
  <nav class="navbar navbar-expand-lg navbar-dark navblue shadow-sm">
    <div class="container">
      <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#mainNav">
        <span class="navbar-toggler-icon"></span>
      </button>
      <div id="mainNav" class="collapse navbar-collapse">
        <ul class="navbar-nav me-auto">
          <li class="nav-item"><a class="nav-link active" href="#">Home</a></li>
          <li class="nav-item"><a class="nav-link" href="#">Artikel</a></li>
          <li class="nav-item"><a class="nav-link" href="#">About</a></li>
          <li class="nav-item"><a class="nav-link" href="#">Kontak</a></li>
        </ul>
      </div>
    </div>
  </nav>

  <!-- Hero -->
  <section class="container mt-3">
    <div class="panel panel-hero">
      <h2 class="fw-bold mb-2">Hello World!</h2>
      <p class="lead text-secondary mb-3">
        Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vestibulum lorem elit, iaculis in nisl volutpat, malesuada
        tincidunt arcu. Proin in leo fringilla, vestibulum mi porta, faucibus felis. Integer pharetra est nunc, nec
        pretium nunc pretium ac.
      </p>
      <a class="btn btn-primary btn-lg" href="#">Learn more »</a>
    </div>
  </section>

  <!-- Main + Sidebar -->
  <main class="container">
    <div class="panel panel-content">
      <div class="row gx-4 gy-4">
        <!-- Main column -->
        <div class="col-lg-8">
          <!-- 3 icon circles -->
          <div class="row text-center g-4 mt-2">
            <div class="col-md-4">
              <div>
                <div class="circle bg-orange">120 × 120</div>
                <h5 class="mt-2 mb-1 fw-semibold">Heading</h5>
                <p class="small text-secondary mb-2">
                  Donec sed odio dui. Etiam porta sem malesuada magna mollis euismod.
                </p>
                <a class="btn btn-light btn-sm btn-ghost" href="#">View detail</a>
              </div>
            </div>
            <div class="col-md-4">
              <div>
                <div class="circle bg-blue">120 × 120</div>
                <h5 class="mt-2 mb-1 fw-semibold">Heading</h5>
                <p class="small text-secondary mb-2">
                  Donec sed odio dui. Etiam porta sem malesuada magna mollis euismod.
                </p>
                <a class="btn btn-light btn-sm btn-ghost" href="#">View detail</a>
              </div>
            </div>
            <div class="col-md-4">
              <div>
                <div class="circle bg-teal">120 × 120</div>
                <h5 class="mt-2 mb-1 fw-semibold">Heading</h5>
                <p class="small text-secondary mb-2">
                  Donec sed odio dui. Etiam porta sem malesuada magna mollis euismod.
                </p>
                <a class="btn btn-light btn-sm btn-ghost" href="#">View detail</a>
              </div>
            </div>
          </div>

          <hr class="soft my-4">

          <!-- Featurette 1 -->
          <article class="row align-items-start gy-3">
            <div class="col-4 col-sm-3">
              <div class="thumb">150 × 150</div>
            </div>
            <div class="col">
              <h3 class="h4 fw-bold text-dark mb-2">First featurette heading.</h3>
              <p class="mb-0 text-secondary">
                Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vestibulum lorem elit, iaculis in nisl volutpat,
                malesuada tincidunt arcu. Proin in leo fringilla, vestibulum mi porta, faucibus felis. Integer pharetra
                est nunc, nec pretium nunc pretium ac.
              </p>
            </div>
          </article>

          <hr class="soft my-4">

          <!-- Featurette 2 -->
          <article class="row align-items-start gy-3">
            <div class="col">
              <h3 class="h4 fw-bold text-dark mb-2">First featurette heading.</h3>
              <p class="mb-0 text-secondary">
                Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vestibulum lorem elit, iaculis in nisl volutpat,
                malesuada tincidunt arcu. Proin in leo fringilla, vestibulum mi porta, faucibus felis. Integer pharetra
                est nunc, nec pretium nunc pretium ac.
              </p>
            </div>
            <div class="col-4 col-sm-3">
              <div class="thumb float-md-end">150 × 150</div>
            </div>
          </article>
        </div>

        <!-- Sidebar -->
        <aside class="col-lg-4">
          <div class="widget mb-4">
            <div class="widget-header">Widget Header</div>
            <ul class="list-unstyled m-0">
              <li class="widget-item"><a href="#" class="widget-link">Widget Link</a></li>
              <li class="widget-item"><a href="#" class="widget-link">Widget Link</a></li>
              <li class="widget-item"><a href="#" class="widget-link">Widget Link</a></li>
              <li class="widget-item"><a href="#" class="widget-link">Widget Link</a></li>
              <li class="widget-item"><a href="#" class="widget-link">Widget Link</a></li>
            </ul>
          </div>

          <div class="widget">
            <div class="widget-header">Widget Text</div>
            <div class="p-3">
              <p class="mb-0 text-secondary">
                Vestibulum lorem elit, iaculis in nisl volutpat, malesuada tincidunt arcu. Proin in leo fringilla,
                vestibulum mi porta, faucibus felis. Integer pharetra est nunc, nec pretium nunc pretium ac.
              </p>
            </div>
          </div>
        </aside>
      </div>
    </div>
  </main>

  <!-- Footer -->
  <footer class="site-footer">
    <div class="container small text-white">
      © 2021 - Universitas Pelita Bangsa
    </div>
  </footer>

  <!-- jQuery -->
  <script src="https://code.jquery.com/jquery-3.7.1.min.js"
          integrity="sha256-/JqT3SQfawRcv/BIHPThkBvs0OEvtFFmqPF/lYI/Cxo="
          crossorigin="anonymous"></script>
  <!-- Bootstrap JS -->
  <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js"
          integrity="sha384-YvpcrYf0tY3lHB60NNkmXc5s9fDVZLESaAA55NDzOxhy9GkcIdslK1eN7N6jIeHz"
          crossorigin="anonymous"></script>
  <!-- Custom JS -->
  <script src="bootstrap.bundle.min.js"></script>
  ```
**bootstrap.min.css**
```
/* Latar halaman dan tipografi */
.bg-page { background: #f2f2f2; }
body { color: #333; }

/* Brand area */
.brandbar { background: #ffffff; border-bottom: 1px solid #e5e5e5; }
.brandtitle {
  font-size: 28px; font-weight: 700; margin: 16px 0;
  color: #b7b7b7; letter-spacing: .2px;
}

/* Navbar biru seperti contoh */
.navblue { background: #1e66b2; }
.navblue .nav-link { padding: .55rem .9rem; }
.navblue .nav-link.active,
.navblue .nav-link:hover { background: #155a9a; }

/* Panel umum (kotak putih dengan border halus) */
.panel {
  background: #ffffff;
  border: 1px solid #e3e3e3;
  border-radius: 3px;
  box-shadow: 0 1px 0 rgba(0,0,0,.02);
}
.panel-hero { padding: 26px; background: #eee; border-color: #dcdcdc; }
.panel-content { padding: 22px; margin-top: 16px; }

/* Divider tipis */
.soft { border: 0; border-top: 1px solid #ececec; }

/* Circle 120x120 dengan teks tengah */
.circle {
  width: 120px; height: 120px; border-radius: 999px;
  display: inline-flex; align-items: center; justify-content: center;
  font-weight: 600; color: #fff; margin-bottom: .5rem;
}
.bg-orange { background:#de7d2a; }
.bg-blue   { background:#3d6fe3; }
.bg-teal   { background:#66dbcf; color:#fff; }

/* Tombol abu-abu kecil seperti contoh */
.btn-ghost {
  border: 1px solid #cfcfcf !important;
  color: #555 !important;
  background: #f2f2f2 !important;
  padding: .35rem .7rem !important;
}

/* Thumbnail 150x150 hijau-abu */
.thumb{
  width:150px; height:150px; background:#7b8a70; color:#fff;
  display:flex; align-items:center; justify-content:center;
  border-radius:6px; font-weight:600;
}

/* Sidebar Widget */
.widget { border:1px solid #e3e3e3; border-radius:3px; background:#fff; }
.widget-header{
  background:#1e66b2; color:#fff; font-weight:600; padding:.6rem .9rem;
  border-bottom:1px solid #1b5da4;
}
.widget-item{
  padding:.55rem .9rem; border-bottom:1px solid #efefef; background:#fff;
}
.widget-item:last-child{ border-bottom:0; }
.widget-link{ text-decoration:none; color:#3b3b3b; }
.widget-link:hover{ text-decoration:underline; }

/* Footer */
.site-footer{
  background:#0f0f0f; padding:14px 0; margin-top:20px; border-top:1px solid #080808;
}

/* Responsif halus */
@media (max-width: 575.98px){
  .thumb{ width:120px; height:120px; }
}
```
**bootstrap.bundle.min.js**
bootstrap.bundle.min.js
```
// jQuery untuk interaksi ringan sesuai kebutuhan mockup

$(function () {
  // Set nav item aktif (jaga-jaga bila dipakai di banyak halaman)
  const file = location.pathname.split("/").pop() || "home.html";
  $(".navbar .nav-link").each(function () {
    if ($(this).attr("href") === "#" || $(this).attr("href") === file) {
      $(this).addClass("active");
    }
  });

  // Demo klik "View detail" → alert ala contoh (ringan)
  $(".btn-ghost").on("click", function (e) {
    e.preventDefault();
    alert("Detail item: " + $(this).closest("div").find("h5").text());
  });
});
```

**Penjelasan**
**Layout Sederhana (Bootstrap 5)**

Proyek ini adalah template halaman web sederhana berbasis **Bootstrap 5** dengan sedikit gaya kustom dan interaksi ringan menggunakan jQuery.

---

**1. Prasyarat**

Tidak ada instalasi khusus. Kamu cukup memakai browser modern. (Opsional) Editor seperti **VS Code** dengan ekstensi *Live Server* akan memudahkan pengembangan lokal.

---

**2. Struktur Proyek**

- **Home.html** — halaman utama yang memuat Bootstrap dari CDN, jQuery dari CDN, serta file CSS/JS kustom proyek. :contentReference[oaicite:0]{index=0}  
- **bootstrap.min.css** — stylesheet kustom untuk tema (warna navbar, panel, widget, tombol, dll). :contentReference[oaicite:1]{index=1}  
- **bootstrap.bundle.min.js** — skrip kustom (jQuery) untuk interaksi ringan; bisa menandai item navbar aktif dan demo tombol “View detail”. :contentReference[oaicite:2]{index=2}

---

**3. Cara Menjalankan Secara Lokal (Paling Cepat)**

1. **Download** atau **clone** repo ini.
2. Buka file **`Home.html`** langsung di browser (double-click).
3. Kamu sudah bisa melihat tampilan layout, termasuk:
   - *Brand bar* dan **navbar** berwarna biru. :contentReference[oaicite:3]{index=3}
   - *Hero section*, *panel content*, ikon lingkaran, *featurette*, dan *sidebar widget*. :contentReference[oaicite:4]{index=4}
   - Interaksi klik tombol **“View detail”** yang memunculkan *alert*. :contentReference[oaicite:5]{index=5}

> Alternatif (disarankan untuk dev): pakai ekstensi **Live Server** (VS Code) agar *auto reload* saat kamu mengubah file.

---

**4. Dependensi & Pemuatan Aset**

File **`Home.html`** sudah memuat:
- **Bootstrap CSS** via CDN (5.3.3) dan **Bootstrap JS** via CDN,  
- **jQuery 3.7.1** via CDN,  
- CSS kustom `bootstrap.min.css` dan JS kustom `bootstrap.bundle.min.js` dari root proyek. :contentReference[oaicite:6]{index=6}

Tidak perlu build step atau package manager.

---

**5. Kustomisasi**

### 5.1. Gaya (CSS)
Semua penyesuaian tema ada di **`bootstrap.min.css`**:
- Kelas `navblue` untuk warna navbar, `panel`, `widget`, `btn-ghost`, `circle`, `thumb`, hingga *footer*.  
- Responsif halus untuk perangkat kecil. :contentReference[oaicite:7]{index=7}

Edit nilai warna/ukuran sesuai kebutuhanmu.

### 5.2. Interaksi (JS)
Interaksi ringan berada di **`bootstrap.bundle.min.js`**:
- Menandai link navbar aktif berdasarkan URL.
- Demo klik tombol “View detail” yang menampilkan judul item. :contentReference[oaicite:8]{index=8}

Tambah logika lain (mis. *modal*, *toast*, AJAX) di file yang sama atau pecah ke file baru.

### 5.3. Konten (HTML)
Ubah struktur, teks, atau komponen langsung di **`Home.html`**:
- *Hero section*, 3 ikon lingkaran, *featurette* kiri/kanan, dan *sidebar widget* siap diubah. :contentReference[oaicite:9]{index=9}

---

**6. Deploy ke GitHub Pages**

1. Push kode ke branch `main` (atau `master`).
2. Di GitHub repo → **Settings** → **Pages**.
3. **Source**: pilih `Deploy from a branch`.
4. **Branch**: pilih `main` dan folder `/root` (jika file di root).
5. Klik **Save** dan tunggu situs aktif di URL GitHub Pages yang disediakan.

---

**7. Troubleshooting**

- **Tampilan tidak sesuai / tanpa gaya**  
  Pastikan `bootstrap.min.css` dipanggil setelah CSS Bootstrap CDN di `<head>`. :contentReference[oaicite:10]{index=10}

- **Tombol “View detail” tidak bereaksi**  
  Pastikan urutan skrip: jQuery CDN → Bootstrap JS CDN → `bootstrap.bundle.min.js` (kustom). :contentReference[oaicite:11]{index=11}

- **Ikon lingkaran/warna tidak muncul**  
  Cek kelas `circle`, `bg-orange`, `bg-blue`, `bg-teal` di CSS kustom. :contentReference[oaicite:12]{index=12}

---

**8. Kontribusi**

1. Fork repo ini.
2. Buat branch fitur: `git checkout -b fitur-ku`.
3. Commit perubahan: `git commit -m "Tambah fitur X"`.
4. Push branch: `git push origin fitur-ku`.
5. Buka **Pull Request**.
