# CV-RAFLIYANSYAH
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link href="https://fonts.googleapis.com/css2?family=Poppins:ital,wght@0,100;0,200;0,300;0,400;0,500;0,600;0,700;0,800;0,900;1,100;1,200;1,300;1,400;1,500;1,600;1,700;1,800;1,900&display=swap" rel="stylesheet">
    <script src='https://cdn.tailwindcss.com/3.2.0'></script>
    <title>Muhamad Rafliyansyah - Portfolio</title>
    <style>
        /* Base styles */
        a, button, input, select, h1, h2, h3, h4, h5, * {
            box-sizing: border-box;
            margin: 0;
            padding: 0;
            border: none;
            text-decoration: none;
            background: none;
            font-family: 'Poppins', sans-serif;
            -webkit-font-smoothing: antialiased;
        }
        
        menu, ol, ul {
            list-style-type: none;
            margin: 0;
            padding: 0;
        }

        /* Common styles from all files */
        .bg-gradient {
            background: linear-gradient(
                108.47deg,
                rgba(250, 243, 199, 1) 2.87%,
                rgba(246, 243, 243, 1) 44.76%,
                rgba(234, 234, 234, 1) 100%
            );
        }

        /* Combine all other styles from original files */
        .section {
            padding: 4rem 1.5rem;
        }

        /* Add smooth scroll behavior */
        html {
            scroll-behavior: smooth;
        }

        /* Navigation styles */
        .nav-fixed {
            position: fixed;
            top: 0;
            left: 0;
            right: 0;
            z-index: 1000;
            background: rgba(255, 255, 255, 0.9);
            backdrop-filter: blur(5px);
        }

        .nav-links {
            display: flex;
            justify-content: center;
            gap: 2rem;
            padding: 1rem;
        }

        .nav-link {
            color: #333;
            font-weight: 500;
            transition: color 0.3s;
        }

        .nav-link:hover {
            color: #288670;
        }

        /* Include all other necessary styles from original files */
        /* ... (copy other specific styles from each original file) ... */
    </style>
</head>
<body>
    <!-- Navigation -->
    <nav class="nav-fixed">
        <div class="nav-links">
            <a href="#home" class="nav-link">Home</a>
            <a href="#about" class="nav-link">About</a>
            <a href="#experience" class="nav-link">Experience</a>
            <a href="#work" class="nav-link">Work</a>
            <a href="#certificate" class="nav-link">Certificate</a>
        </div>
    </nav>

    <!-- Home Section -->
    <section id="home" class="section min-h-screen pt-20">
        <!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta http-equiv="X-UA-Compatible" content="IE=edge">
  <meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1.0, minimum-scale=1.0, user-scalable=no">
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Poppins:ital,wght@0,300;0,400;0,500;0,600;1,300;1,400&display=swap" rel="stylesheet">
  <link rel="stylesheet" href="./vars.css">
  <link rel="stylesheet" href="./style.css">
  <script src='https://cdn.tailwindcss.com/3.2.0' ></script>
  <script src="./tailwind.config.js"></script>
  <style>
   a,
   button,
   input,
   select,
   h1,
   h2,
   h3,
   h4,
   h5,
   * {
       box-sizing: border-box;
       margin: 0;
       padding: 0;
       border: none;
       text-decoration: none;
       background: none;
       font-family: 'Poppins', sans-serif;
       -webkit-font-smoothing: antialiased;
   }
   
   menu, ol, ul {
       list-style-type: none;
       margin: 0;
       padding: 0;
   }

   .container-wrapper {
      width: 100%;
      min-height: 100vh;
      padding: 1.5rem;
   }

   .content-container {
      max-width: 1675px;
      margin: 0 auto;
      position: relative;
   }

   .bg-gradient {
      background: linear-gradient(
        108.47deg,
        rgba(250, 243, 199, 1) 2.87%,
        rgba(246, 243, 243, 1) 44.76%,
        rgba(234, 234, 234, 1) 100%
      );
   }

   .contact-grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 1rem;
      margin-top: 2rem;
   }

   .contact-item {
      display: flex;
      align-items: center;
      padding: 0.5rem;
      transition: transform 0.2s;
   }

   .contact-item:hover {
      transform: scale(1.02);
   }

   @media (max-width: 1024px) {
      .container-wrapper {
         padding: 1rem;
      }
      .profile-section {
         flex-direction: column;
         align-items: center;
         text-align: center;
         max-width: 600px;
         margin: 0 auto;
      }
      .profile-image-container {
         width: 100%;
         display: flex;
         justify-content: center;
         margin-bottom: 1.5rem;
      }
      .profile-image {
         width: 200px;
         height: auto;
      }
   }

   @media (max-width: 768px) {
      .container-wrapper {
         padding: 0.75rem;
      }
      .content-container {
         padding: 0.5rem;
      }
      .contact-grid {
         grid-template-columns: 1fr;
         gap: 0.75rem;
         padding: 0 0.5rem;
      }
      .heading-text {
         font-size: 1.75rem;
         line-height: 1.3;
         margin-bottom: 0.75rem;
      }
      .subheading-text {
         font-size: 1.25rem;
         line-height: 1.4;
      }
      .contact-item {
         padding: 0.75rem;
         font-size: 0.9rem;
      }
      .contact-item img {
         width: 2rem;
         height: 2rem;
      }
      .profile-image {
         width: 150px;
      }
      .profile-image-container {
         margin-bottom: 1rem;
      }
   }

   @media (max-width: 480px) {
      .heading-text {
         font-size: 1.5rem;
         margin-bottom: 0.5rem;
      }
      .subheading-text {
         font-size: 1rem;
         margin-bottom: 0.5rem;
      }
      .profile-image {
         width: 120px;
         margin-bottom: 0.75rem;
      }
      .bg-gradient {
         padding: 1rem;
      }
   }
  </style>
  <title>Document</title>
</head>
<body>
  <div class="container-wrapper">
    <div class="content-container">
      <div class="bg-gradient rounded-[25px] p-8">
        <div class="flex flex-col md:flex-row gap-8 profile-section">
          <div class="md:hidden profile-image-container">
            <img src="foto-rafli-x-10.png" 
                 alt="Profile" 
                 class="profile-image"
                 style="aspect-ratio: 382.59/495" />
          </div>
          
          <div class="flex-1">
            <h1 class="text-3xl md:text-5xl font-medium mb-4 md:mb-6 heading-text">
              MUHAMAD<br />RAFLIYANSYAH
            </h1>
            
            <h2 class="text-xl md:text-3xl font-light mb-3 md:mb-4 subheading-text">
              Designer Graphic | UI/UX | Front End Developer
            </h2>
            
            <p class="text-xl font-light italic mb-4">
              Bogor, Jawa Barat
            </p>
            
            <p class="text-xl font-light italic mb-8 max-w-[769px]">
              "Berpikir kreatif, mendesain dengan visi, dan mengkode dengan presisi. karena
              setiap detail membawa perbedaan"
            </p>

            <div class="flex justify-center md:justify-start">
              <a href="./assets/cv.pdf" download 
                 class="bg-[#288670] text-white px-8 py-2 rounded-[52px] text-xl font-light italic
                        hover:bg-[#1f6655] transition-colors shadow-md">
                UNDUH CV
              </a>
            </div>
          </div>
          
          <div class="hidden md:block md:w-[382.59px]">
            <img src="foto-rafli-x-10.png" 
                 alt="Profile" 
                 class="w-full h-auto profile-image"
                 style="aspect-ratio: 382.59/495" />
          </div>
        </div>

        <div class="contact-grid mt-16">
          <a href="https://wa.me/6295365575395" target="_blank" class="contact-item bg-white rounded-lg">
            <img src="whatsapp-10.png" alt="WhatsApp" class="w-10 h-10 mr-4" />
            <span class="text-xl">+6295-3655-75395</span>
          </a>

          <a href="mailto:mrafliyns212@gmail.com" target="_blank" class="contact-item bg-white rounded-lg">
            <img src="gmail-10.png" alt="Email" class="w-10 h-10 mr-4" />
            <span class="text-xl">mrafliyns212@gmail.com</span>
          </a>

          <a href="https://www.instagram.com/ilfarilfarr" target="_blank" class="contact-item bg-white rounded-lg">
            <img src="instagram-10.png" alt="Instagram" class="w-10 h-10 mr-4" />
            <span class="text-xl">ilfarilfarr</span>
          </a>

          <a href="https://www.behance.net/theilfart" target="_blank" class="contact-item bg-white rounded-lg">
            <img src="behance-10.png" alt="Behance" class="w-10 h-10 mr-4" />
            <span class="text-xl">the ilfart</span>
          </a>
        </div>
      </div>
    </div>
  </div>
</body>
</html>
    </section>
    <!-- About Section -->
    <section id="about" class="section">
      <!DOCTYPE html>
      <html lang="en">
      <head>
        <meta charset="UTF-8">
        <meta http-equiv="X-UA-Compatible" content="IE=edge">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <link rel="preconnect" href="https://fonts.googleapis.com">
        <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
        <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;500;600;700&display=swap" rel="stylesheet">
        <link rel="stylesheet" href="./vars.css">
        <link rel="stylesheet" href="./style.css">
        <script src='https://cdn.tailwindcss.com/3.2.0' ></script>
        <script src="./tailwind.config.js"></script>
        <style>
         a,
         button,
         input,
         select,
         h1,
         h2,
         h3,
         h4,
         h5,
         * {
             box-sizing: border-box;
             margin: 0;
             padding: 0;
             border: none;
             text-decoration: none;
             background: none;
             font-family: 'Poppins', sans-serif;
             -webkit-font-smoothing: antialiased;
         }
         
         menu, ol, ul {
             list-style-type: none;
             margin: 0;
             padding: 0;
         }
      
         .education-item {
            margin-bottom: 1.5rem;
         }
         .education-title {
            font-weight: 600;
            font-size: 1.1rem;
            margin-bottom: 0.25rem;
         }
         .education-year {
            color: #666;
            font-size: 0.9rem;
            margin-bottom: 0.25rem;
         }
         .education-address {
            color: #666;
            font-size: 0.9rem;
         }
         .skills-grid {
            display: grid;
            grid-template-columns: repeat(3, 110px);
            gap: 2rem;
            justify-content: center;
            padding: 1rem;
         }
         .skills-grid img {
            transition: transform 0.2s ease;
         }
         .skills-grid img:hover {
            transform: scale(1.05);
         }
         .layout-container {
            max-width: 1675px;
            margin: 0 auto;
            position: relative;
            padding: 1.5rem;
         }
         
         .bg-gradient {
            background: linear-gradient(
              108.47deg,
              rgba(250, 243, 199, 1) 2.87%,
              rgba(246, 243, 243, 1) 44.76%,
              rgba(234, 234, 234, 1) 100%
            );
         }
      
         @media (max-width: 768px) {
            .container {
              padding: 1rem;
            }
            .about-section, .education-section, .skills-section {
              width: 100%;
              margin: 1rem 0;
            }
            .skills-grid {
               display: grid;
               grid-template-rows: auto auto;  /* Two rows */
               grid-auto-flow: row;  /* Force row-based filling */
               gap: 2rem;
               justify-content: center;
               align-items: center;
            }
            
            /* First row - 3 items */
            .skills-grid > img:nth-child(-n+3) {
               grid-row: 1;
            }
            
            /* Second row - 4 items */
            .skills-grid > img:nth-child(n+4) {
               grid-row: 2;
            }
         }
         </style>
        <title>Document</title>
      </head>
      <body>
        <div class="layout-container">
          <!-- Main background -->
          <div class="bg-gradient rounded-[25px] absolute inset-0"></div>
      
          <!-- Content wrapper -->
          <div class="relative z-10">
            <!-- About section -->
            <div class="bg-gradient rounded-[25px] shadow-lg p-8 mb-8">
              <h1 class="text-4xl md:text-5xl font-medium mb-8">About Me</h1>
              <div class="text-lg md:text-xl leading-relaxed">
                <span>
                  Saya adalah individu yang berkomitmen tinggi terhadap pekerjaan,
                  menjunjung tinggi tanggung jawab, dan ketepatan waktu. Selain itu, saya
                  memiliki kemampuan untuk beradaptasi dan bekerja sama dengan berbagai
                  individu dalam lingkungan yang dinamis. Meskipun terkadang ada tantangan
                  dalam berinteraksi dengan orang baru, saya tetap mampu membangun
                  komunikasi yang efektif serta kolaborasi yang produktif.
                  <br />
                  <br />
                  Bepengalaman dalam Bidang Desain Grafis,
                  Berpikir kreatif, mendesain dengan visi, dan mengkode dengan presisi.
                  karena setiap detail membawa perbedaan.
                </span>
              </div>
            </div>
      
            <!-- Two column layout -->
            <div class="grid md:grid-cols-2 gap-8">
              <!-- Education section -->
              <div class="bg-gradient rounded-[25px] shadow-lg p-8">
                <h2 class="text-4xl md:text-5xl font-medium mb-8">Education</h2>
                <div class="space-y-6">
                  <div class="education-item">
                    <div class="education-title">SMKN 1 CIOMAS JURUSAN ANIMASI</div>
                    <div class="education-year">2018-2021</div>
                    <div class="education-address">Jl. Raya Laladon Ciomas, Kab. Bogor</div>
                  </div>
                  <div class="education-item">
                    <div class="education-title">MTS DARUL IHYA</div>
                    <div class="education-year">2015-2018</div>
                    <div class="education-address">Jl. Raya Ciomas 16610</div>
                  </div>
                  <div class="education-item">
                    <div class="education-title">MI DARUL IHYA</div>
                    <div class="education-year">2009-2015</div>
                    <div class="education-address">Jl. Raya Ciomas 16610</div>
                  </div>
                </div>
              </div>
      
              <!-- Skills section -->
              <div class="bg-gradient rounded-[25px] shadow-lg p-8">
                <h2 class="text-4xl md:text-5xl font-medium mb-8">Skills</h2>
                <div class="skills-grid">
                  <img src="photoshop-10.png" alt="Photoshop" class="w-[110px] h-[110px] object-cover" />
                  <img src="illustrator-10.png" alt="Illustrator" class="w-[110px] h-[110px] object-cover" />
                  <img src="draw-10.png" alt="Draw" class="w-[110px] h-[110px] object-cover" />
                  <img src="figma-10.png" alt="Figma" class="w-[110px] h-[110px] object-cover" />
                  <img src="excel-10.png" alt="Excel" class="w-[110px] h-[110px] object-cover" />
                  <img src="word-10.png" alt="Word" class="w-[110px] h-[110px] object-cover" />
                  <img src="visual-studio-10.png" alt="Visual Studio" class="w-[110px] h-[110px] object-cover" />
                </div>
              </div>
            </div>
          </div>
        </div>
      </body>
      </html>
    </section>
    <!-- Experience Section -->
    <section id="experience" class="section">
      <!DOCTYPE html>
      <html lang="en">
      <head>
        <meta charset="UTF-8">
        <meta http-equiv="X-UA-Compatible" content="IE=edge">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <link rel="stylesheet" href="./vars.css">
        <link rel="stylesheet" href="./style.css">
        <script src='https://cdn.tailwindcss.com/3.2.0' ></script>
        <script src="./tailwind.config.js"></script>
        <link rel="preconnect" href="https://fonts.googleapis.com">
        <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
        <link href="https://fonts.googleapis.com/css2?family=Poppins:ital,wght@0,100;0,200;0,300;0,400;0,500;0,600;0,700;0,800;0,900;1,100;1,200;1,300;1,400;1,500;1,600;1,700;1,800;1,900&display=swap" rel="stylesheet">
        <style>
         a,
         button,
         input,
         select,
         h1,
         h2,
         h3,
         h4,
         h5,
         * {
             box-sizing: border-box;
             margin: 0;
             padding: 0;
             border: none;
             text-decoration: none;
             background: none;
             font-family: 'Poppins', sans-serif;
             -webkit-font-smoothing: antialiased;
         }
         
         menu, ol, ul {
             list-style-type: none;
             margin: 0;
             padding: 0;
         }
         </style>
        <title>Document</title>
      </head>
      <body>
        <div class="min-h-screen bg-white p-4 md:p-6 lg:p-8">
          <div class="max-w-7xl mx-auto rounded-[25px] bg-gradient-to-br from-[#FAF3C7] via-[#F6F3F3] to-[#EAEAEA] shadow-lg p-6 md:p-8 lg:p-10">
            
            <h1 class="text-4xl md:text-5xl font-medium text-left mb-8 md:mb-12">
              Experience
            </h1>
      
            <div class="flex flex-col gap-8">
              <!-- 2019 Experiences -->
              <div class="space-y-6">
                <div class="flex flex-col md:flex-row gap-2 md:gap-4">
                  <span class="font-medium w-24">2019 :</span>
                  <div class="flex-1">
                    <p class="text-base md:text-lg hover:underline">
                      SEMINAR BEKRAF ANIMATION CONFERENCE (BEACON) 2019 DI HOTEL PULLMAN JAKARTA
                    </p>
                  </div>
                </div>
      
                <div class="flex flex-col md:flex-row gap-2 md:gap-4">
                  <span class="font-medium w-24">2019 :</span>
                  <div class="flex-1">
                    <p class="text-base md:text-lg hover:underline">
                      SEMINAR ANIMAKINI 2019 DI TEATER JAKARTA, TAMAN ISMAIL MARZUKI
                    </p>
                  </div>
                </div>
              </div>
      
              <!-- 2020 Experiences -->
              <div class="space-y-6">
                <div class="flex flex-col md:flex-row gap-2 md:gap-4">
                  <span class="font-medium w-24">Nov 2020 :</span>
                  <div class="flex-1">
                    <p class="text-base md:text-lg hover:underline">
                      DIKLAT SERTIFIKASI KOMPETENSI SUB SEKTOR ANIMASI DI TAMAN BUKIT PALEM RESORT BOGOR
                    </p>
                    <p class="text-sm md:text-base italic text-gray-600 mt-2">
                      Diklat Sertifikasi ini saya Mengerjakan 3D Motion Graphic Tentang Iklan Komersil.
                    </p>
                  </div>
                </div>
      
                <div class="flex flex-col md:flex-row gap-2 md:gap-4">
                  <span class="font-medium w-24">Des 2020 :</span>
                  <div class="flex-1">
                    <p class="text-base md:text-lg hover:underline">
                      PRAKTEK KERJA LAPANGAN (PKL) DI KAMPOONG MONSTER STUDIO SELAMA 5 BULAN.
                    </p>
                    <p class="text-sm md:text-base italic text-gray-600 mt-2">
                      Membantu dan Mengerjakan apa yang diperintahkan oleh Atasan.
                    </p>
                  </div>
                </div>
              </div>
      
              <!-- 2021 Experiences -->
              <div class="space-y-6">
                <div class="flex flex-col md:flex-row gap-2 md:gap-4">
                  <span class="font-medium w-24">April 2021 :</span>
                  <div class="flex-1">
                    <p class="text-base md:text-lg hover:underline">
                      UJI KOMPETENSI JURUSAN ANIMASI (MEMBUAT FILM ANIMASI BERDURASI PENDEK)
                    </p>
                    <p class="text-sm md:text-base italic text-gray-600 mt-2">
                      Disini saya Bersama 1 orang teman saya mengerjakan Project Akhir sekolah Berdurasi 6 menit. dan Oleh penguji dan guru, saya dinyatakan Kompeten.
                    </p>
                  </div>
                </div>
      
                <div class="flex flex-col md:flex-row gap-2 md:gap-4">
                  <span class="font-medium w-24">Sep 2021 :</span>
                  <div class="flex-1">
                    <p class="text-base md:text-lg hover:underline">
                      BIMBINGAN TEKNIS DAN BERBASIS STANDAR KOMPETENSI KERJA NASIONAL INDONESIA (SKKNI) BIDANG KOMINFO SKEMA MOTION GRAPHIC ARTIST DI HOTEL SAHIRA BOGOR
                    </p>
                    <p class="text-sm md:text-base italic text-gray-600 mt-2">
                      Membuat explainer, Lowerthird dan Motion Graphic sesuai dengan Naskah yang diberikan
                    </p>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>
      </body>
      </html>
    </section>

    <!-- Work Section -->
    <section id="work" class="section">
      <!DOCTYPE html>
      <html lang="en">
      <head>
        <meta charset="UTF-8">
        <meta http-equiv="X-UA-Compatible" content="IE=edge">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <link rel="stylesheet" href="./vars.css">
        <link rel="stylesheet" href="./style.css">
        <link href="https://fonts.googleapis.com/css2?family=Poppins:ital,wght@0,100;0,200;0,300;0,400;0,500;0,600;0,700;0,800;0,900;1,100;1,200;1,300;1,400;1,500;1,600;1,700;1,800;1,900&display=swap" rel="stylesheet">
        <script src='https://cdn.tailwindcss.com/3.2.0' ></script>
        <script src="./tailwind.config.js"></script>
        <style>
         a, button, input, select, h1, h2, h3, h4, h5, * {
             box-sizing: border-box;
             margin: 0;
             padding: 0;
             border: none;
             text-decoration: none;
             background: none;
             font-family: 'Poppins', sans-serif;
             -webkit-font-smoothing: antialiased;
         }
         
         menu, ol, ul {
             list-style-type: none;
             margin: 0;
             padding: 0;
         }
      
         .gradient-bg {
            background: linear-gradient(
              108.47deg,
              rgba(250, 243, 199, 1) 2.874845266342163%,
              rgba(246, 243, 243, 1) 44.76401209831238%,
              rgba(234, 234, 234, 1) 100%
            );
         }
         </style>
        <title>Document</title>
      </head>
      <body>
        <div class="min-h-screen bg-white p-4 md:p-6 lg:p-8">
          <div class="gradient-bg rounded-[25px] p-6 md:p-8 lg:p-10 max-w-7xl mx-auto shadow-lg">
            <h1 class="text-4xl md:text-5xl font-medium mb-8 md:mb-12">Work Experience</h1>
            
            <div class="space-y-8 md:space-y-12">
              <!-- Lawson -->
              <div class="experience-item">
                <div class="flex flex-col md:flex-row md:items-center gap-2 mb-3">
                  <span class="font-normal text-lg md:text-xl">Nov 2021 :</span>
                  <span class="font-normal text-lg md:text-xl">PT. LANCAR WIGUNA SEJAHTERA (LAWSON INDONESIA)</span>
                </div>
                <div class="ml-4 md:ml-6 text-base md:text-lg italic font-light">
                  <p class="mb-2">Pramuniaga/ Crew Store (Nov 2021 - Apr 2022)</p>
                  <p class="text-justify">Mendisplay barang dari gudang ke area Sales, Menggoreng goreng sesuai kebutuhan Toko Contohnya Menggoreng Enachike dan Membuat Bento, Membuat kopi Lawson, Melayani Konsumen dan menawarkan item oden odenan, juga menjadi kasir</p>
                </div>
              </div>
      
              <!-- Exleas -->
              <div class="experience-item">
                <div class="flex flex-col md:flex-row md:items-center gap-2 mb-3">
                  <span class="font-normal text-lg md:text-xl">Des 2022 :</span>
                  <span class="font-normal text-lg md:text-xl">EXLEAS GROUP</span>
                </div>
                <div class="ml-4 md:ml-6 text-base md:text-lg italic font-light space-y-3">
                  <div>
                    <p class="mb-2">Designer Grafis (Des 2022 - Jun 2022)</p>
                    <p class="text-justify">Membuat / Mendesain Mockup Jersey, Mendesain Flyer & Poster, Membuat Pola/Mendesain Sepatu</p>
                  </div>
                  <div>
                    <p class="mb-2">Operator Mesin</p>
                    <p class="text-justify">Selain Mendesain, Saya juga sebagai Operator Mesin Eco-solvent Printers.</p>
                  </div>
                </div>
              </div>
      
              <!-- Voosh -->
              <div class="experience-item">
                <div class="flex flex-col md:flex-row md:items-center gap-2 mb-3">
                  <span class="font-normal text-lg md:text-xl">Sep 2023 :</span>
                  <span class="font-normal text-lg md:text-xl">Voosh.id Printing</span>
                </div>
                <div class="ml-4 md:ml-6 text-base md:text-lg italic font-light space-y-3">
                  <div>
                    <p class="mb-2">Designer Grafis (Sep 2023 - Jan 2024)</p>
                    <p class="text-justify">Membuat kebutuhan Konten Instagram, Membuat Pola/Desain Sepatu anak Dll</p>
                  </div>
                  <div>
                    <p class="mb-2">Deskrip Print</p>
                    <p class="text-justify">Membuat kebutuhan Desain Konsumen, Seperti Banner, Stiker Dll.</p>
                  </div>
                </div>
              </div>
      
              <!-- Bawaslu -->
              <div class="experience-item">
                <div class="flex flex-col md:flex-row md:items-center gap-2 mb-3">
                  <span class="font-normal text-lg md:text-xl">Mei 2024 :</span>
                  <span class="font-normal text-lg md:text-xl">BAWASLU KECAMATAN CIOMAS</span>
                </div>
              </div>
            </div>
          </div>
        </div>
      </body>
      </html>
    </section>
    <!-- Certificate Section -->
    <section id="certificate" class="section">
      <!DOCTYPE html>
      <html lang="en">
      <head>
        <meta charset="UTF-8">
        <meta http-equiv="X-UA-Compatible" content="IE=edge">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <link rel="stylesheet" href="./vars.css">
        <link rel="stylesheet" href="./style.css">
        <link href="https://fonts.googleapis.com/css2?family=Poppins:ital,wght@0,100;0,200;0,300;0,400;0,500;0,600;0,700;0,800;0,900;1,100;1,200;1,300;1,400;1,500;1,600;1,700;1,800;1,900&display=swap" rel="stylesheet">
        <script src='https://cdn.tailwindcss.com/3.2.0' ></script>
        <script src="./tailwind.config.js"></script>
        <style>
         a,
         button,
         input,
         select,
         h1,
         h2,
         h3,
         h4,
         h5,
         * {
             box-sizing: border-box;
             margin: 0;
             padding: 0;
             border: none;
             text-decoration: none;
             background: none;
             font-family: 'Poppins', sans-serif;
             -webkit-font-smoothing: antialiased;
         }
         
         menu, ol, ul {
             list-style-type: none;
             margin: 0;
             padding: 0;
         }
      
         .certificate-container {
           max-width: 1440px;
           width: 100%;
           margin: 0 auto;
           padding: 2rem;
         }
      
         .certificate-grid {
           display: grid;
           grid-template-columns: repeat(auto-fit, minmax(320px, 1fr));
           gap: 2rem;
           padding: 1rem;
           max-width: 100%;
         }
      
         .certificate-card {
           background: #fff;
           border-radius: 25px;
           padding: 1.5rem;
           box-shadow: 0px 10px 17px rgba(0, 0, 0, 0.1);
           min-width: 300px;
           max-width: 100%;
           margin: 0 auto;
         }
      
         .certificate-card img {
           width: 100%;
           height: auto;
           object-fit: contain;
           max-height: 500px;
         }
      
         .img-container {
           display: flex;
           flex-direction: column;
           gap: 1rem;
           align-items: center;
         }
      
         @media (max-width: 768px) {
           .certificate-grid {
             grid-template-columns: 1fr;
             padding: 0.5rem;
           }
           
           .certificate-container {
             padding: 1rem;
           }
         }
      
         @media (min-width: 2000px) {
           .certificate-container {
             max-width: 1800px;
           }
         }
      
         /* Modal styles */
         .modal {
           display: none;
           position: fixed;
           top: 0;
           left: 0;
           width: 100%;
           height: 100%;
           background: rgba(0, 0, 0, 0.8);
           z-index: 1000;
           justify-content: center;
           align-items: center;
           opacity: 0;
           transition: opacity 0.3s ease;
         }
      
         .modal.show {
           display: flex;
           opacity: 1;
         }
      
         .modal-content {
           position: relative;
           max-width: 90%;
           max-height: 90vh;
           transform: scale(0.7);
           transition: transform 0.3s ease;
         }
      
         .modal.show .modal-content {
           transform: scale(1);
         }
      
         .modal-content img {
           max-width: 100%;
           max-height: 90vh;
           object-fit: contain;
         }
      
         .close-button {
           position: absolute;
           top: -40px;
           right: 0;
           color: white;
           font-size: 30px;
           cursor: pointer;
           padding: 5px;
           transition: transform 0.2s;
         }
      
         .close-button:hover {
           transform: scale(1.1);
         }
      
         .zoomable {
           cursor: pointer;
           transition: transform 0.2s;
         }
      
         .zoomable:hover {
           transform: scale(1.02);
         }
        </style>
        <title>Document</title>
      </head>
      <body>
        <main class="min-h-screen bg-gradient-to-br from-yellow-100 via-gray-50 to-gray-200">
          <div class="certificate-container">
            <h1 class="text-4xl md:text-5xl font-medium py-8 px-4 text-left">
              Certificate
            </h1>
            
            <div class="certificate-grid">
              <!-- Certificate 1 -->
              <div class="certificate-card">
                <div class="img-container">
                  <img src="sertifikat-animedia-10.png" alt="Animedia Certificate" class="zoomable" onclick="openModal(this.src)" />
                </div>
                <div class="mt-4">
                  <h2 class="text-sm font-normal">
                    Sertifikasi Bidang Graphic Designer (Animedia)
                  </h2>
                  <p class="text-xs italic mt-2">
                    Kompetensi Motion Graphic Artist
                    <br />
                    08 Februari 2021
                  </p>
                </div>
              </div>
      
              <!-- Certificate 2 -->
              <div class="certificate-card">
                <div class="img-container">
                  <img src="sertifikat-ainaki-10.png" alt="AINAKI Certificate" class="zoomable" onclick="openModal(this.src)" />
                </div>
                <div class="mt-4">
                  <h2 class="text-sm font-normal">
                    Sertifikasi Bidang Graphic Designer (AINAKI)
                  </h2>
                  <p class="text-xs italic mt-2">
                    Kompetensi Motion Graphic Artist
                    <br />
                    20 September 2021
                  </p>
                </div>
              </div>
      
              <!-- Certificate 3 -->
              <div class="certificate-card">
                <div class="img-container">
                  <img src="sertifikat-kompeten-10.png" alt="Kompetensi Certificate" class="zoomable" onclick="openModal(this.src)" />
                  <img src="nilai-sertifikat-10.png" alt="Nilai Certificate" class="zoomable" onclick="openModal(this.src)" />
                </div>
                <div class="mt-4">
                  <h2 class="text-sm font-normal">
                    Sertifikat Kompetensi Keahlian Animasi
                  </h2>
                  <p class="text-xs italic mt-2">
                    5 April 2021
                  </p>
                </div>
              </div>
            </div>
          </div>
      
          <!-- Modal -->
          <div class="modal" id="imageModal">
            <div class="modal-content">
              <span class="close-button" onclick="closeModal()">&times;</span>
              <img id="modalImage" src="" alt="Zoomed certificate">
            </div>
          </div>
      
          <footer class="py-6 bg-white mt-8">
            <div class="certificate-container">
              <p class="text-center text-base md:text-xl">
                © Copyright 2025 Muhamad Rafliyansyah All Right Reserved
              </p>
            </div>
          </footer>
        </main>
      
        <script>
          const modal = document.getElementById('imageModal');
          const modalImg = document.getElementById('modalImage');
      
          function openModal(imgSrc) {
            modal.classList.add('show');
            modalImg.src = imgSrc;
            document.body.style.overflow = 'hidden';
          }
      
          function closeModal() {
            modal.classList.remove('show');
            document.body.style.overflow = 'auto';
          }
      
          // Close modal when clicking outside the image
          modal.addEventListener('click', function(e) {
            if (e.target === modal) {
              closeModal();
            }
          });
      
          // Close modal with Escape key
          document.addEventListener('keydown', function(e) {
            if (e.key === 'Escape') {
              closeModal();
            }
          });
        </script>
      </body>
      </html>
    </section>

    <script>
        // Smooth scroll for navigation links
        document.querySelectorAll('a[href^="#"]').forEach(anchor => {
            anchor.addEventListener('click', function (e) {
                e.preventDefault();
                document.querySelector(this.getAttribute('href')).scrollIntoView({
                    behavior: 'smooth'
                });
            });
        });

        // Active link highlighting
        const sections = document.querySelectorAll('section');
        const navLinks = document.querySelectorAll('.nav-link');

        window.addEventListener('scroll', () => {
            let current = '';
            sections.forEach(section => {
                const sectionTop = section.offsetTop;
                const sectionHeight = section.clientHeight;
                if (pageYOffset >= sectionTop - 60) {
                    current = section.getAttribute('id');
                }
            });

            navLinks.forEach(link => {
                link.classList.remove('text-[#288670]');
                if (link.getAttribute('href').slice(1) === current) {
                    link.classList.add('text-[#288670]');
                }
            });
        });
    </script>
</body>
</html>
