---
layout: default
title: Kadir Bedir
---

<!-- HERO BÖLÜMÜ -->
<section id="hero">
  <div class="container text-center">
    <img src="/assets/img/profile.jpg" alt="Kadir Bedir" class="profile-img mb-4">
    <h1 class="display-3 fw-bold">Kadir Bedir</h1>
   <p class="lead">Elektrik-Elektronik Mühendisi • Embedded Systems • C/C#/Python •Linux •.NET core •Frontend-Backend •Raspberry Pi </p>
    <p class="fs-5 opacity-90 mb-4"> Linux, Gömülü sistemler, PCB tasarım, 3d yazıcılar</p>
    <div>
      <a href="#tecrube" class="btn btn-light btn-lg me-3">Projelerim</a>
      <a href="#iletisim" class="btn btn-outline-light btn-lg">İletişime Geç</a>
    </div>
  </div>
</section>

<!-- HAKKIMDA -->
<section id="hakkimda" class="bg-white">
  <div class="container">
    <h2 class="text-center mb-5">Hakkımda</h2>
    <div class="row justify-content-center">
      <div class="col-lg-8">
        <p class="lead text-center">
          Merhaba! Elektrik elektronik Mühendisiyim
        </p>
      </div>
    </div>
  </div>
</section>

<!-- TECRÜBE & PROJELER -->
<section id="tecrube" class="bg-light">
  <div class="container">
    <h2 class="text-center mb-5">Projeler & Tecrübe</h2>
    <div class="timeline">
      <div class="timeline-item">
        <div class="timeline-year">2025</div>
        <h4>Raspberry Pi 5 – Speed detection and Collision Avoidance Lidar System Design </h4>
        <p>Gürültü filtreleme, sensör optimizasyonu ve gerçek zamanlı takip sistemi. Python + OpenCV.</p>
      </div>
      <div class="timeline-item">
        <div class="timeline-year">2024-2025</div>
        <h4>Matematik & Algoritma Geliştirme</h4>
        <p>Uygun substitüsyon teknikleriyle integral çözümleri ve optimizasyon çalışmaları.</p>
      </div>
      <div class="timeline-item">
        <div class="timeline-year">2023-Devam</div>
        <h4>Rusça Dil Eğitimi</h4>
        <p>A1 → A2 seviyesine geçiş, Поехали! serisi ve günlük pratik.</p>
      </div>
    </div>
  </div>
</section>

<!-- İLGİ ALANLARI -->
<section id="ilgi">
  <div class="container">
    <h2 class="text-center mb-5">İlgi Alanlarım</h2>
    <div class="row g-4">
      <div class="col-md-4">
        <div class="text-center p-4 bg-white rounded shadow-sm h-100">
          <h5>🇷🇺 Rusça</h5>
          <p>A2 seviyesindeyim, Поехали! kitabı ve günlük konuşma pratiği.</p>
        </div>
      </div>
      <div class="col-md-4">
        <div class="text-center p-4 bg-white rounded shadow-sm h-100">
          <h5>🔬 Görüntü İşleme</h5>
          <p>Raspberry Pi + OpenCV ile gerçek zamanlı nesne takibi.</p>
        </div>
      </div>
      <div class="col-md-4">
        <div class="text-center p-4 bg-white rounded shadow-sm h-100">
          <h5>🧾 Fusion </h5>
          <p> 3D yazıcı ve Fusion.</p>
        </div>
      </div>
    </div>
  </div>
</section>

<!-- BLOG -->
<section id="blog" class="bg-light">
  <div class="container">
    <h2 class="text-center mb-5">Son Yazılar</h2>
    <div class="row">
      {% for post in site.posts limit:3 %}
      <div class="col-md-4 mb-4">
        <div class="card h-100 shadow-sm">
          <div class="card-body">
            <h5 class="card-title"><a href="{{ post.url }}">{{ post.title }}</a></h5>
            <p class="card-text text-muted small">{{ post.date | date: "%d %B %Y" }}</p>
            <p>{{ post.excerpt | strip_html | truncate: 120 }}</p>
          </div>
        </div>
      </div>
      {% endfor %}
    </div>
    <div class="text-center mt-4">
      <a href="/blog" class="btn btn-primary">Tüm Yazılar →</a>
    </div>
  </div>
</section>

<!-- İLETİŞİM -->
<section id="iletisim">
  <div class="container text-center">
    <h2 class="mb-5">İletişim</h2>
    <p class="lead mb-4">:</p>
    <div class="fs-3">
      <a href="mailto:eem.kadirbedir@gmail.com" class="mx-3 text-decoration-none">✉️ E-posta</a>
      <a href="https://github.com/kadirbedir" class="mx-3 text-decoration-none">🐙 GitHub</a>
      <a href="https://www.linkedin.com/in/kadir-bedir-tr196018/" class="mx-3 text-decoration-none">💼 LinkedIn</a>
    </div>
  </div>
</section>
