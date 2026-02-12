<!DOCTYPE html>
<html lang="tr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Hüseyin Gülen - Software Architect</title>
    <style>
        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            line-height: 1.6;
            color: #333;
            max-width: 1200px;
            margin: 0 auto;
            padding: 20px;
            background-color: #f8f9fa;
        }
        .header-banner {
            background: linear-gradient(135deg, #0d1117 0%, #000000 100%);
            color: white;
            text-align: center;
            padding: 60px 20px;
            border-radius: 10px;
            margin-bottom: 30px;
        }
        .profile-views {
            text-align: center;
            margin: 20px 0;
        }
        .badge {
            background-color: #28a745;
            color: white;
            padding: 5px 15px;
            border-radius: 20px;
            font-weight: bold;
            display: inline-block;
        }
        h1, h2, h3 {
            color: #0d1117;
        }
        h1 {
            font-size: 2.5em;
            margin-bottom: 10px;
        }
        .subtitle {
            font-size: 1.2em;
            opacity: 0.9;
            margin-bottom: 20px;
        }
        .section {
            background: white;
            margin: 20px 0;
            padding: 25px;
            border-radius: 10px;
            box-shadow: 0 2px 10px rgba(0,0,0,0.1);
        }
        .tech-stack {
            display: flex;
            flex-wrap: wrap;
            gap: 10px;
            margin: 15px 0;
        }
        .tech-item {
            background: #e9ecef;
            padding: 5px 15px;
            border-radius: 20px;
            font-size: 0.9em;
        }
        .focus-areas {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 15px;
            margin: 20px 0;
        }
        .focus-item {
            background: #e9ecef;
            padding: 15px;
            border-radius: 8px;
        }
        .manifesto {
            background: #0d1117;
            color: white;
            padding: 30px;
            border-radius: 10px;
            text-align: center;
            font-size: 1.2em;
            font-weight: bold;
        }
        .contact {
            text-align: center;
            margin: 30px 0;
        }
        .contact a {
            color: #007bff;
            text-decoration: none;
            margin: 0 15px;
        }
        .contact a:hover {
            text-decoration: underline;
        }
        hr {
            margin: 30px 0;
            border: none;
            border-top: 1px solid #dee2e6;
        }
        pre {
            background: #f8f9fa;
            padding: 15px;
            border-radius: 5px;
            overflow-x: auto;
        }
        .mermaid {
            text-align: center;
            background: white;
            padding: 20px;
            border-radius: 10px;
            margin: 20px 0;
        }
        .quote {
            font-style: italic;
            text-align: center;
            font-size: 1.1em;
            color: #6c757d;
            margin: 30px 0;
        }
    </style>
</head>
<body>
    <!-- ULTRA BLACK BANNER -->
    <div class="header-banner">
        <h1>Hüseyin Gülen</h1>
        <p class="subtitle">Software Architect • AI Systems Builder • Cyber Security Engineer</p>
        <p>Production seviyesinde çalışan, ölçeklenebilir ve güvenli dijital sistemler tasarlıyorum.</p>
        <p>Kod yazmaktan çok <strong>mimari kurarım.</strong></p>
    </div>

    <!-- PROFILE VIEWS -->
    <div class="profile-views">
        <span class="badge">Profile Views: 5000+</span>
    </div>

    <hr>

    <!-- ARCHITECT MINDSET -->
    <div class="section">
        <h2>Architect Mindset</h2>
        <pre>
Architecture > Code
Security > Convenience
Scalability > Speed
Signal > Noise
        </pre>
        <p><strong>Büyük sistemler sessiz çalışır.</strong></p>
    </div>

    <hr>

    <!-- ODAK ALANLARI -->
    <div class="section">
        <h2>Şu Anda Odaklandığım Alanlar</h2>
        <div class="focus-areas">
            <div class="focus-item">AI tabanlı ticari platformlar</div>
            <div class="focus-item">Self-hosted cloud ekosistemleri</div>
            <div class="focus-item">Secure infrastructure design</div>
            <div class="focus-item">Mikroservis mimarileri</div>
            <div class="focus-item">LLM destekli otomasyonlar</div>
            <div class="focus-item">High-availability sistemler</div>
        </div>
    </div>

    <hr>

    <!-- SİSTEM TASARIM YAKLAŞIMI -->
    <div class="section">
        <h2>Sistem Tasarım Yaklaşımım</h2>
        <div class="mermaid">
            <p><strong>Flow Diagram:</strong></p>
            <p>Client → CDN → Gateway → Services → [AI, Database, Cache]</p>
            <p>Database → Backup</p>
            <p>AI → VectorDB</p>
        </div>
        <p><strong>Prensip:</strong> Tek noktadan hata vermeyen, yatay ölçeklenebilir sistemler.</p>
    </div>

    <hr>

    <!-- SEÇİLİ SİSTEMLER -->
    <div class="section">
        <h2>Selected Systems</h2>
        
        <h3>AI Skin Analysis Platform</h3>
        <p>Computer vision destekli ticari analiz sistemi.</p>
        <div class="tech-stack">
            <span class="tech-item">Python</span>
            <span class="tech-item">AI</span>
            <span class="tech-item">Cloud</span>
            <span class="tech-item">Vision Models</span>
        </div>

        <h3>Enterprise ERP</h3>
        <p>Finans, operasyon ve randevu orkestrasyonu yapan işletme platformu.</p>
        <div class="tech-stack">
            <span class="tech-item">Laravel</span>
            <span class="tech-item">Docker</span>
            <span class="tech-item">Microservices</span>
        </div>

        <h3>Secure Production Environments</h3>
        <p>Hardened Linux altyapıları ve güvenli CI/CD pipeline'ları.</p>
        <p><strong>Odak:</strong> Stability + Security</p>
    </div>

    <hr>

    <!-- KULLANIM ALANLARI -->
    <div class="section">
        <h2>Uses</h2>
        
        <h3>Editor</h3>
        <div class="tech-stack">
            <span class="tech-item">VS Code / Cursor</span>
            <span class="tech-item">JetBrains tools</span>
        </div>

        <h3>Backend</h3>
        <div class="tech-stack">
            <span class="tech-item">Laravel</span>
            <span class="tech-item">Node.js</span>
            <span class="tech-item">Python</span>
        </div>

        <h3>Frontend</h3>
        <div class="tech-stack">
            <span class="tech-item">React</span>
            <span class="tech-item">Next.js</span>
        </div>

        <h3>Infrastructure</h3>
        <div class="tech-stack">
            <span class="tech-item">Linux</span>
            <span class="tech-item">Docker</span>
            <span class="tech-item">Nginx</span>
            <span class="tech-item">Redis</span>
        </div>

        <h3>AI</h3>
        <div class="tech-stack">
            <span class="tech-item">OpenAI</span>
            <span class="tech-item">Local LLMs</span>
            <span class="tech-item">Vector Databases</span>
        </div>
    </div>

    <hr>

    <!-- AI-FIRST ENGINEERING -->
    <div class="section">
        <h2>AI-First Engineering</h2>
        <p>Yapay zekayı sadece entegre etmem. Ürünlerin merkezine konumlandırırım.</p>
        <p><strong>Odak noktalarım:</strong></p>
        <ul>
            <li>AI-native product design</li>
            <li>Prompt architecture</li>
            <li>Retrieval sistemleri</li>
            <li>Automation agents</li>
            <li>Computer vision</li>
        </ul>
    </div>

    <hr>

    <!-- MANİFESTO -->
    <div class="manifesto">
        Basit tasarla.<br>
        Güvenli kur.<br>
        Yatay ölçekle.<br>
        Sessiz çalıştır.<br><br>
        İyi yazılım görünmezdir.<br>
        Harika altyapı fark edilmez.
    </div>

    <hr>

    <!-- İLETİŞİM -->
    <div class="contact">
        <h2>Contact</h2>
        <p>
            <a href="https://huseyingulen.net" target="_blank">Website → https://huseyingulen.net</a>
            <a href="mailto:hello@huseyingulen.net">Mail → hello@huseyingulen.net</a>
        </p>
    </div>

    <hr>

    <!-- ALT BANNER -->
    <div class="header-banner" style="padding: 30px;">
        <p><strong>Designing systems that survive scale.</strong></p>
    </div>

    <script>
        // Basit profil görüntüleme sayacı (demo için)
        document.addEventListener('DOMContentLoaded', function() {
            const badge = document.querySelector('.badge');
            if (badge) {
                badge.textContent = 'Profile Views: 5000+';
            }
        });
    </script>
</body>
</html>
