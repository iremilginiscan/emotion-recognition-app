<!DOCTYPE html>
<html lang="tr">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Duygu Tanıma Projesi</title>
  <style>
    * {
      box-sizing: border-box;
      margin: 0;
      padding: 0;
    }

    body {
      font-family: 'Segoe UI', sans-serif;
      background: linear-gradient(to bottom right, #1b1f3a, #502c7d);
      color: #ffffff;
      line-height: 1.7;
    }

    .container {
      max-width: 1200px;
      margin: 4rem auto;
      padding: 2rem;
    }

    header {
      text-align: center;
      margin-bottom: 3rem;
    }

    header h1 {
      font-size: 3.5rem;
      background: linear-gradient(to right, #8e2de2, #4a00e0);
      -webkit-background-clip: text;
      -webkit-text-fill-color: transparent;
      font-weight: bold;
    }

    header h3 {
      font-weight: 300;
      font-size: 1.2rem;
      margin-top: 1rem;
      color: #d1c4e9;
    }

    .glass-box {
      background: rgba(255, 255, 255, 0.07);
      border: 1px solid rgba(255, 255, 255, 0.1);
      border-radius: 20px;
      padding: 2rem;
      margin-bottom: 2rem;
      backdrop-filter: blur(10px);
      box-shadow: 0 8px 30px rgba(0, 0, 0, 0.3);
    }

    h2 {
      color: #b39ddb;
      margin-bottom: 1rem;
      border-left: 5px solid #7e57c2;
      padding-left: 12px;
      font-size: 1.5rem;
    }

    ul {
      margin-left: 1.5rem;
    }

    .badges {
      margin-top: 1rem;
    }

    .badge {
      display: inline-block;
      background-color: #7c4dff;
      color: white;
      font-weight: 500;
      padding: 0.5rem 1.2rem;
      border-radius: 30px;
      margin: 0.3rem;
      font-size: 0.9rem;
    }

    .buttons {
      text-align: center;
      margin-top: 3rem;
    }

    .buttons button {
      background: linear-gradient(to right, #8e2de2, #4a00e0);
      color: white;
      padding: 0.9rem 1.8rem;
      border: none;
      border-radius: 50px;
      font-size: 1rem;
      font-weight: bold;
      margin: 0.5rem;
      cursor: pointer;
      transition: all 0.3s ease-in-out;
    }

    .buttons button:hover {
      transform: scale(1.05);
      box-shadow: 0 0 15px #9575cd;
    }

    @media (max-width: 768px) {
      header h1 {
        font-size: 2.2rem;
      }
      .glass-box {
        padding: 1.2rem;
      }
    }
  </style>
</head>
<body>
  <div class="container">
    <header>
      <h1>Emotion Recognition App</h1>
      <h3>İrem Ilgın İşcan | Bilgisayar Mühendisliği 4. Sınıf Öğrencisi</h3>
    </header>

    <div class="glass-box">
      <h2>Hakkımda</h2>
      <p>Ben <strong>İrem Ilgın İşcan</strong>. Antalya Bilim Üniversitesi'nde Bilgisayar Mühendisliği 4. sınıf öğrencisiyim. Bu projeyi yapay zekâ, görsel işleme ve modern web teknolojileri alanlarına olan ilgim doğrultusunda geliştirdim.</p>
    </div>

    <div class="glass-box">
      <h2>Proje Özeti</h2>
      <p>Yüz ifadelerinden temel duyguları (mutlu, üzgün, kızgın, şaşkın, korkmuş, tiksinmiş, nötr) analiz eden bir sistem geliştirdim. Sistem, görselleri işleyip anlık duygu sınıflandırması yapar ve gerektiğinde API’lerle genişletilebilir. Hem bireysel hem kurumsal projelere entegre edilebilir yapıdadır.</p>
    </div>

    <div class="glass-box">
      <h2>Kullanım Alanları</h2>
      <ul>
        <li>Güvenlik sistemleri</li>
        <li>Müşteri deneyimi analizi</li>
        <li>Eğitimde öğrenci katılım izleme</li>
        <li>Sürücü yorgunluk tespiti</li>
        <li>Sağlık ve psikolojik analiz</li>
      </ul>
    </div>

    <div class="glass-box">
      <h2>Kullanılan Teknolojiler</h2>
      <div class="badges">
        <span class="badge">Node.js</span>
        <span class="badge">JavaScript</span>
        <span class="badge">face-api.js</span>
        <span class="badge">TensorFlow.js</span>
        <span class="badge">OpenAI GPT</span>
        <span class="badge">React.js</span>
        <span class="badge">HTML/CSS</span>
      </div>
    </div>

    <div class="glass-box">
      <h2>API ve Model Entegrasyonları</h2>
      <ul>
        <li><strong>face-api.js:</strong> Açık kaynak yüz tanıma ve duygu modeli</li>
        <li><strong>Azure Face API:</strong> Kurumsal servis, 5000 çağrı ücretsiz</li>
        <li><strong>OpenAI Whisper:</strong> Sesli duygu analizi (isteğe bağlı)</li>
        <li><strong>HuggingFace Modelleri:</strong> Multimodal analiz imkânı</li>
      </ul>
    </div>

    <div class="glass-box">
      <h2>Proje Aşamaları </h2>
      <ul>
        <li>Analiz ve Tasarım</li>
        <li>MVP Geliştirme </li>
        <li>API Entegrasyonu </li>
        <li>Test ve Yayınlama </li>
      </ul>
    </div>

    <div class="buttons">
      <button onclick="window.open('https://github.com/iremilginiscan/emotion-recognition-app')">GitHub Repo</button>
      <button onclick="alert('Demo henüz eklenmedi.')">Canlı Demo</button>
    </div>
  </div>
</body>
</html>
