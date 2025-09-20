<!DOCTYPE html>
<html lang="tr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Enes Er | Elektrik-Elektronik Mühendisliği Öğrencisi</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
        }
        
        body {
            background-color: #f5f5f5;
            color: #333;
            line-height: 1.6;
        }
        
        .container {
            max-width: 1100px;
            margin: 0 auto;
            padding: 20px;
        }
        
        header {
            text-align: center;
            padding: 40px 20px;
            background: linear-gradient(135deg, #2c3e50 0%, #4a6491 100%);
            color: white;
            border-radius: 10px;
            margin-bottom: 30px;
            box-shadow: 0 4px 15px rgba(0, 0, 0, 0.1);
        }
        
        h1 {
            font-size: 2.5rem;
            margin-bottom: 10px;
        }
        
        h2 {
            font-size: 1.8rem;
            margin: 20px 0 15px;
            color: #2c3e50;
            border-bottom: 2px solid #4a6491;
            padding-bottom: 5px;
        }
        
        h3 {
            font-size: 1.4rem;
            margin: 15px 0;
            color: #4a6491;
        }
        
        .subtitle {
            font-size: 1.2rem;
            color: #ecf0f1;
            margin-bottom: 20px;
        }
        
        .content {
            display: flex;
            flex-wrap: wrap;
            gap: 30px;
            margin-bottom: 30px;
        }
        
        .main-content {
            flex: 2;
            min-width: 300px;
        }
        
        .sidebar {
            flex: 1;
            min-width: 250px;
        }
        
        .card {
            background: white;
            border-radius: 10px;
            padding: 25px;
            margin-bottom: 25px;
            box-shadow: 0 4px 10px rgba(0, 0, 0, 0.08);
            transition: transform 0.3s ease;
        }
        
        .card:hover {
            transform: translateY(-5px);
        }
        
        .about {
            display: flex;
            flex-direction: column;
            gap: 15px;
        }
        
        .interests {
            display: grid;
            grid-template-columns: repeat(auto-fill, minmax(250px, 1fr));
            gap: 15px;
        }
        
        .interest-item {
            background: #f8f9fa;
            padding: 15px;
            border-radius: 8px;
            border-left: 4px solid #4a6491;
        }
        
        .tools {
            display: flex;
            flex-wrap: wrap;
            gap: 15px;
            justify-content: center;
            padding: 15px 0;
        }
        
        .tool-item {
            display: flex;
            flex-direction: column;
            align-items: center;
            width: 80px;
        }
        
        .tool-icon {
            font-size: 2.5rem;
            margin-bottom: 8px;
            color: #2c3e50;
        }
        
        .contact-links {
            display: flex;
            justify-content: center;
            gap: 25px;
            margin-top: 20px;
        }
        
        .contact-links a {
            color: white;
            font-size: 2.5rem;
            transition: transform 0.3s ease;
        }
        
        .contact-links a:hover {
            transform: scale(1.1);
        }
        
        .language-switcher {
            text-align: center;
            margin: 20px 0;
        }
        
        .language-btn {
            background: #4a6491;
            color: white;
            border: none;
            padding: 10px 20px;
            border-radius: 5px;
            cursor: pointer;
            margin: 0 5px;
            transition: background 0.3s;
        }
        
        .language-btn:hover {
            background: #2c3e50;
        }
        
        .language-content {
            display: none;
        }
        
        .active {
            display: block;
        }
        
        footer {
            text-align: center;
            padding: 20px;
            margin-top: 30px;
            background: #2c3e50;
            color: white;
            border-radius: 10px;
        }
        
        @media (max-width: 768px) {
            .content {
                flex-direction: column;
            }
            
            h1 {
                font-size: 2rem;
            }
            
            .contact-links {
                flex-wrap: wrap;
            }
        }
    </style>
</head>
<body>
    <div class="container">
        <header>
            <h1>Enes Er</h1>
            <p class="subtitle">Elektrik-Elektronik Mühendisliği Öğrencisi</p>
            <p class="subtitle">Balıkesir Üniversitesi | GPA: 3.2</p>
            
            <div class="language-switcher">
                <button class="language-btn" onclick="showLanguage('tr')">Türkçe</button>
                <button class="language-btn" onclick="showLanguage('en')">English</button>
            </div>
            
            <div class="contact-links">
                <a href="mailto:eneserr07@gmail.com"><i class="fas fa-envelope"></i></a>
                <a href="https://www.linkedin.com/in/enes-er-425661297/" target="_blank"><i class="fab fa-linkedin"></i></a>
                <a href="https://github.com/yourprofile" target="_blank"><i class="fab fa-github"></i></a>
            </div>
        </header>
        
        <div class="content">
            <div class="main-content">
                <div class="card">
                    <div id="about-tr" class="language-content active">
                        <h2>Hakkımda</h2>
                        <div class="about">
                            <p>Merhaba! Ben Balıkesir Üniversitesi Elektrik-Elektronik Mühendisliği öğrencisiyim (GPA: 3.2).</p>
                            <p>Gömülü sistemler ve elektronik alanına özel bir ilgi duyuyorum ve kendimi bu yönde geliştirmekteyim.</p>
                            <p>TEKNOFEST Roket Yarışması'nda finalist olarak takım çalışması, mühendislik tasarımı ve problem çözme konularında önemli deneyimler kazandım.</p>
                            <p>Henüz staj yapmadım, ancak yakın zamanda yapacağım staj ile endüstriyel projelerde aktif rol almayı hedefliyorum.</p>
                            <p>Şu anda öğrenmeye ve kendimi geliştirmeye odaklı bir junior mühendis adayıyım.</p>
                        </div>
                    </div>
                    
                    <div id="about-en" class="language-content">
                        <h2>About Me</h2>
                        <div class="about">
                            <p>Hello! I am an Electrical & Electronics Engineering student at Balıkesir University (GPA: 3.2).</p>
                            <p>I have a strong interest in embedded systems and electronics, and I am continuously improving myself in this field.</p>
                            <p>As a finalist at the TEKNOFEST Rocket Competition, I gained valuable experience in teamwork, engineering design, and problem solving.</p>
                            <p>I have not completed an internship yet, but I aim to take part in industrial projects through upcoming internships.</p>
                            <p>Currently, I am focused on learning and developing my skills as a junior engineer.</p>
                        </div>
                    </div>
                </div>
                
                <div class="card">
                    <div id="interests-tr" class="language-content active">
                        <h2>İlgi Alanlarım</h2>
                        <div class="interests">
                            <div class="interest-item">
                                <h3>Gömülü Sistemler</h3>
                                <p>MCU, sensörler, haberleşme protokolleri</p>
                            </div>
                            <div class="interest-item">
                                <h3>Robotik ve Otomasyon</h3>
                                <p>Endüstriyel otomasyon sistemleri</p>
                            </div>
                            <div class="interest-item">
                                <h3>Elektronik Devre & PCB Tasarımı</h3>
                                <p>Devre tasarımı ve baskı devre kartları</p>
                            </div>
                            <div class="interest-item">
                                <h3>Düşük Seviye Programlama</h3>
                                <p>C / C++ ile gömülü sistem programlama</p>
                            </div>
                        </div>
                    </div>
                    
                    <div id="interests-en" class="language-content">
                        <h2>My Interests</h2>
                        <div class="interests">
                            <div class="interest-item">
                                <h3>Embedded Systems</h3>
                                <p>MCU, sensors, communication protocols</p>
                            </div>
                            <div class="interest-item">
                                <h3>Robotics & Automation</h3>
                                <p>Industrial automation systems</p>
                            </div>
                            <div class="interest-item">
                                <h3>Electronic Circuit & PCB Design</h3>
                                <p>Circuit design and printed circuit boards</p>
                            </div>
                            <div class="interest-item">
                                <h3>Low-level Programming</h3>
                                <p>Embedded systems programming with C/C++</p>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
            
            <div class="sidebar">
                <div class="card">
                    <h2>Yetenekler & Araçlar</h2>
                    <div class="tools">
                        <div class="tool-item">
                            <i class="fab fa-cuttlefish tool-icon"></i>
                            <span>C</span>
                        </div>
                        <div class="tool-item">
                            <i class="fab fa-c-plus-plus tool-icon"></i>
                            <span>C++</span>
                        </div>
                        <div class="tool-item">
                            <i class="fas fa-microchip tool-icon"></i>
                            <span>Arduino</span>
                        </div>
                        <div class="tool-item">
                            <img src="https://upload.wikimedia.org/wikipedia/commons/6/6a/Altium_Designer_Logo.png" alt="Altium" style="width: 40px; height: 40px; margin-bottom: 8px;">
                            <span>Altium</span>
                        </div>
                        <div class="tool-item">
                            <img src="https://upload.wikimedia.org/wikipedia/commons/6/6b/SolidWorks_Logo.png" alt="SolidWorks" style="width: 40px; height: 40px; margin-bottom: 8px;">
                            <span>SolidWorks</span>
                        </div>
                        <div class="tool-item">
                            <img src="https://www.labcenter.com/images/logo.svg" alt="Proteus" style="width: 40px; height: 40px; margin-bottom: 8px;">
                            <span>Proteus</span>
                        </div>
                        <div class="tool-item">
                            <img src="https://upload.wikimedia.org/wikipedia/commons/2/29/Autodesk_EAGLE_logo.png" alt="Eagle" style="width: 40px; height: 40px; margin-bottom: 8px;">
                            <span>Eagle</span>
                        </div>
                        <div class="tool-item">
                            <i class="fab fa-github tool-icon"></i>
                            <span>GitHub</span>
                        </div>
                    </div>
                </div>
                
                <div class="card">
                    <h2>Eğitim</h2>
                    <div class="education">
                        <h3>Balıkesir Üniversitesi</h3>
                        <p>Elektrik-Elektronik Mühendisliği</p>
                        <p>GPA: 3.2/4.0</p>
                    </div>
                </div>
                
                <div class="card">
                    <h2>Başarılar</h2>
                    <div class="achievement">
                        <h3>TEKNOFEST Roket Yarışması</h3>
                        <p>Finalist</p>
                        <p>2023</p>
                    </div>
                </div>
            </div>
        </div>
        
        <footer>
            <p>© 2023 Enes Er. Tüm Hakları Saklıdır.</p>
            <p>İletişim: eneserr07@gmail.com</p>
        </footer>
    </div>

    <script>
        function showLanguage(lang) {
            // Tüm içerikleri gizle
            document.querySelectorAll('.language-content').forEach(content => {
                content.classList.remove('active');
            });
            
            // Seçilen dile ait içerikleri göster
            document.getElementById('about-' + lang).classList.add('active');
            document.getElementById('interests-' + lang).classList.add('active');
        }
    </script>
</body>
</html>
