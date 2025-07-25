<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Profil GitHub Gaming</title>
    <!-- Tailwind CSS CDN -->
    <script src="https://cdn.tailwindcss.com"></script>
    <!-- Google Fonts - Inter -->
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;600;700&display=swap" rel="stylesheet">
    <style>
        body {
            font-family: 'Inter', sans-serif;
            background-color: #1a202c; /* Dark background for gaming theme */
            color: #e2e8f0; /* Light text color */
        }
        .container {
            max-width: 960px;
            margin: 0 auto;
            padding: 2rem;
        }
        .readme-content h1 {
            font-size: 2.5rem;
            font-weight: bold;
            color: #4299e1; /* Blue for headings */
            margin-bottom: 1.5rem;
            border-bottom: 3px solid #4299e1;
            padding-bottom: 0.5rem;
        }
        .readme-content h2 {
            font-size: 2rem;
            font-weight: bold;
            color: #63b3ed; /* Lighter blue for subheadings */
            margin-top: 2rem;
            margin-bottom: 1rem;
            border-bottom: 2px solid #63b3ed;
            padding-bottom: 0.3rem;
        }
        .readme-content h3 {
            font-size: 1.5rem;
            font-weight: bold;
            color: #90cdf4; /* Even lighter blue */
            margin-top: 1.5rem;
            margin-bottom: 0.75rem;
        }
        .readme-content p {
            margin-bottom: 1rem;
            line-height: 1.6;
        }
        .readme-content ul {
            list-style-type: disc;
            margin-left: 1.5rem;
            margin-bottom: 1rem;
        }
        .readme-content ul li {
            margin-bottom: 0.5rem;
        }
        .readme-content strong {
            color: #a78bfa; /* Purple for emphasis */
        }
        .badge-container {
            display: flex;
            flex-wrap: wrap;
            gap: 0.75rem;
            margin-top: 1rem;
            margin-bottom: 1.5rem;
        }
        .badge-container img {
            border-radius: 0.375rem; /* rounded-md */
        }
        .section-divider {
            border-top: 1px dashed #4a5568; /* Gray dashed line */
            margin-top: 2.5rem;
            margin-bottom: 2.5rem;
        }
        a {
            color: #81e6d9; /* Teal for links */
            text-decoration: none;
            transition: color 0.3s ease;
        }
        a:hover {
            color: #4fd1c5; /* Lighter teal on hover */
        }
    </style>
</head>
<body class="bg-gray-900 text-gray-200 p-4 sm:p-6 md:p-8">
    <div class="container bg-gray-800 rounded-lg shadow-xl p-6 sm:p-8 md:p-10 border border-blue-700">
        <div id="readme-output" class="readme-content">
            <!-- Markdown content will be rendered here -->
        </div>
    </div>

    <!-- Marked.js CDN for Markdown parsing -->
    <script src="https://cdn.jsdelivr.net/npm/marked/marked.min.js"></script>
    <script>
        // The Markdown content for your README.md
        const markdownContent = `
# 🚀 Arena Koding [Nama Anda/Nickname Anda]! 🎮

Selamat datang, *player*! Anda telah memasuki zona pribadi saya di GitHub, tempat di mana setiap baris kode adalah *spell* baru dan setiap proyek adalah *boss battle* yang menantang. Saya [Nama Anda/Nickname Anda], seorang *developer* yang selalu siap untuk *level up* dan menaklukkan tantangan digital.

Di sini, Anda akan menemukan jejak petualangan koding saya, mulai dari *side quests* kecil hingga *epic sagas*. Mari kita mulai petualangan ini bersama!

---

## 🎯 Misi Utama & *Side Quests*

Inilah beberapa misi yang sedang saya kerjakan atau yang baru saja saya selesaikan:

* **[Nama Proyek 1]** (Status: 🟢 *In Progress*): *[Deskripsi singkat proyek, contoh: "Membangun platform turnamen e-sports mini dengan Next.js dan Firebase."]*
* **[Nama Proyek 2]** (Status: 🟡 *On Hold/Refactoring*): *[Deskripsi singkat proyek, contoh: "Meningkatkan performa aplikasi manajemen inventaris game indie."]*
* **[Nama Proyek 3]** (Status: 🏆 *Completed*): *[Deskripsi singkat proyek, contoh: "Membuat bot Discord untuk notifikasi game favorit."]*

---

## 🎒 Inventaris Senjata (Tech Stack)

Ini adalah *arsenal* teknologi yang saya gunakan untuk menghadapi berbagai *bug* dan membangun solusi keren:

**Bahasa Pemrograman:**
<div class="badge-container">
    <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python">
    <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" alt="JavaScript">
    <img src="https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white" alt="TypeScript">
    <!-- Tambahkan badge bahasa lain yang Anda kuasai di sini -->
</div>

**Framework & Library:**
<div class="badge-container">
    <img src="https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=black" alt="React">
    <img src="https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=node.js&logoColor=white" alt="Node.js">
    <img src="https://img.shields.io/badge/Express.js-000000?style=for-the-badge&logo=express&logoColor=white" alt="Express.js">
    <img src="https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white" alt="Tailwind CSS">
    <!-- Tambahkan badge framework/library lain yang Anda kuasai di sini -->
</div>

**Database & Tools:**
<div class="badge-container">
    <img src="https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white" alt="PostgreSQL">
    <img src="https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white" alt="MongoDB">
    <img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white" alt="Git">
    <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" alt="Docker">
    <img src="https://img.shields.io/badge/VS%20Code-007ACC?style=for-the-badge&logo=visual-studio-code&logoColor=white" alt="VS Code">
    <!-- Tambahkan badge database/tools lain yang Anda kuasai di sini -->
</div>

---

## 🏆 Ruang Trofi (Achievements)

Beberapa *trofi* yang telah saya raih dalam perjalanan koding:

* **[Nama Pencapaian 1]:** *[Deskripsi singkat, contoh: "Berhasil menyelesaikan 100 hari streak koding di GitHub."]*
* **[Nama Proyek Terbaik/Pencapaian 2]:** *[Deskripsi singkat, contoh: "Membangun game web sederhana yang dimainkan oleh >100 user."]*
* **[Sertifikasi/Course Penting]:** *[Contoh: "Mendapatkan sertifikasi Game Development dari Coursera."]*

---

## 🤝 Bergabung dalam *Party* (Connect with Me!)

Ingin berkolaborasi, berdiskusi tentang game, atau sekadar menyapa? Jangan ragu untuk menghubungi saya!

<div class="badge-container">
    <a href="https://www.linkedin.com/in/[username_linkedin_anda]" target="_blank">
        <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn">
    </a>
    <a href="https://twitter.com/[username_twitter_anda]" target="_blank">
        <img src="https://img.shields.io/badge/Twitter-1DA1F2?style=for-the-badge&logo=twitter&logoColor=white" alt="Twitter">
    </a>
    <a href="mailto:[email_anda]">
        <img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email">
    </a>
    <a href="https://[link_portfolio_anda]" target="_blank">
        <img src="https://img.shields.io/badge/Portfolio-FF5722?style=for-the-badge&logo=google-chrome&logoColor=white" alt="Portfolio">
    </a>
</div>

---

## 📊 Statistik Pertempuran (GitHub Stats)

<div class="flex flex-col sm:flex-row justify-center items-center gap-4 mt-4">
    <img src="https://github-readme-stats.vercel.app/api?username=YOUR_GITHUB_USERNAME&show_icons=true&theme=dark&hide_title=true&hide_border=true&count_private=true&line_height=25" alt="GitHub Stats" class="rounded-lg shadow-lg">
    <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=YOUR_GITHUB_USERNAME&layout=compact&theme=dark&hide_title=true&hide_border=true" alt="Top Languages" class="rounded-lg shadow-lg">
</div>

*Ganti \`YOUR_GITHUB_USERNAME\` dengan username GitHub Anda agar statistik muncul.*

---

Terima kasih sudah mampir ke markas saya! Semoga hari Anda penuh dengan *loot* dan *XP*!
        `;

        // Function to render markdown
        function renderMarkdown() {
            const readmeOutput = document.getElementById('readme-output');
            // Use marked.js to convert markdown to HTML
            readmeOutput.innerHTML = marked.parse(markdownContent);

            // Add Tailwind classes to specific elements after rendering
            readmeOutput.querySelectorAll('h1').forEach(el => {
                el.classList.add('text-4xl', 'font-extrabold', 'text-blue-400', 'mb-6', 'pb-2', 'border-b-4', 'border-blue-600');
            });
            readmeOutput.querySelectorAll('h2').forEach(el => {
                el.classList.add('text-3xl', 'font-bold', 'text-blue-300', 'mt-8', 'mb-4', 'pb-1', 'border-b-2', 'border-blue-500');
            });
            readmeOutput.querySelectorAll('h3').forEach(el => {
                el.classList.add('text-2xl', 'font-semibold', 'text-blue-200', 'mt-6', 'mb-3');
            });
            readmeOutput.querySelectorAll('p').forEach(el => {
                el.classList.add('text-lg', 'leading-relaxed', 'mb-4');
            });
            readmeOutput.querySelectorAll('ul').forEach(el => {
                el.classList.add('list-disc', 'ml-6', 'mb-4');
            });
            readmeOutput.querySelectorAll('ul li').forEach(el => {
                el.classList.add('mb-2');
            });
            readmeOutput.querySelectorAll('strong').forEach(el => {
                el.classList.add('text-purple-400');
            });
            readmeOutput.querySelectorAll('a').forEach(el => {
                el.classList.add('text-teal-400', 'hover:text-teal-300', 'transition-colors', 'duration-300');
            });
            readmeOutput.querySelectorAll('hr').forEach(el => {
                el.classList.add('border-t-2', 'border-dashed', 'border-gray-600', 'my-10');
            });

            // Handle image rendering, specifically for the badge containers
            // We need to re-insert the badge containers as marked.js will parse them as plain text
            const badgeContainers = readmeOutput.querySelectorAll('.badge-container');
            if (badgeContainers.length > 0) {
                // Manually re-insert the badge HTML as marked.js might escape it
                const techStackSection = readmeOutput.querySelector('h2#inventaris-senjata-tech-stack'); // Find the tech stack heading
                if (techStackSection) {
                    let currentElement = techStackSection.nextElementSibling;
                    let badgeIndex = 0;
                    while(currentElement && badgeIndex < badgeContainers.length) {
                        if (currentElement.textContent.includes('Bahasa Pemrograman:')) {
                            currentElement.insertAdjacentHTML('afterend', `
                                <div class="badge-container flex flex-wrap gap-3 mt-4 mb-6">
                                    <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python">
                                    <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" alt="JavaScript">
                                    <img src="https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white" alt="TypeScript">
                                    <!-- Tambahkan badge bahasa lain yang Anda kuasai di sini -->
                                </div>
                            `);
                            currentElement = currentElement.nextElementSibling; // Move past the newly inserted div
                        } else if (currentElement.textContent.includes('Framework & Library:')) {
                            currentElement.insertAdjacentHTML('afterend', `
                                <div class="badge-container flex flex-wrap gap-3 mt-4 mb-6">
                                    <img src="https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=black" alt="React">
                                    <img src="https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=node.js&logoColor=white" alt="Node.js">
                                    <img src="https://img.shields.io/badge/Express.js-000000?style=for-the-badge&logo=express&logoColor=white" alt="Express.js">
                                    <img src="https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white" alt="Tailwind CSS">
                                    <!-- Tambahkan badge framework/library lain yang Anda kuasai di sini -->
                                </div>
                            `);
                            currentElement = currentElement.nextElementSibling;
                        } else if (currentElement.textContent.includes('Database & Tools:')) {
                            currentElement.insertAdjacentHTML('afterend', `
                                <div class="badge-container flex flex-wrap gap-3 mt-4 mb-6">
                                    <img src="https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white" alt="PostgreSQL">
                                    <img src="https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white" alt="MongoDB">
                                    <img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white" alt="Git">
                                    <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" alt="Docker">
                                    <img src="https://img.shields.io/badge/VS%20Code-007ACC?style=for-the-badge&logo=visual-studio-code&logoColor=white" alt="VS Code">
                                    <!-- Tambahkan badge database/tools lain yang Anda kuasai di sini -->
                                </div>
                            `);
                            currentElement = currentElement.nextElementSibling;
                        } else if (currentElement.textContent.includes('Ingin berkolaborasi, berdiskusi tentang game, atau sekadar menyapa?')) {
                            currentElement.insertAdjacentHTML('afterend', `
                                <div class="badge-container flex flex-wrap gap-3 mt-4 mb-6">
                                    <a href="https://www.linkedin.com/in/[username_linkedin_anda]" target="_blank">
                                        <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn">
                                    </a>
                                    <a href="https://twitter.com/[username_twitter_anda]" target="_blank">
                                        <img src="https://img.shields.io/badge/Twitter-1DA1F2?style=for-the-badge&logo=twitter&logoColor=white" alt="Twitter">
                                    </a>
                                    <a href="mailto:[email_anda]">
                                        <img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email">
                                    </a>
                                    <a href="https://[link_portfolio_anda]" target="_blank">
                                        <img src="https://img.shields.io/badge/Portfolio-FF5722?style=for-the-badge&logo=google-chrome&logoColor=white" alt="Portfolio">
                                    </a>
                                </div>
                            `);
                            currentElement = currentElement.nextElementSibling;
                        } else if (currentElement.textContent.includes('Ganti `YOUR_GITHUB_USERNAME` dengan username GitHub Anda agar statistik muncul.')) {
                            currentElement.insertAdjacentHTML('beforebegin', `
                                <div class="flex flex-col sm:flex-row justify-center items-center gap-4 mt-4 mb-6">
                                    <img src="https://github-readme-stats.vercel.app/api?username=YOUR_GITHUB_USERNAME&show_icons=true&theme=dark&hide_title=true&hide_border=true&count_private=true&line_height=25" alt="GitHub Stats" class="rounded-lg shadow-lg">
                                    <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=YOUR_GITHUB_USERNAME&layout=compact&theme=dark&hide_title=true&hide_border=true" alt="Top Languages" class="rounded-lg shadow-lg">
                                </div>
                            `);
                            currentElement = currentElement.previousElementSibling; // Stay on the newly inserted div
                        }
                        currentElement = currentElement.nextElementSibling;
                    }
                }
            }
        }

        // Call the render function when the DOM is fully loaded
        document.addEventListener('DOMContentLoaded', renderMarkdown);
    </script>
</body>
</html>
