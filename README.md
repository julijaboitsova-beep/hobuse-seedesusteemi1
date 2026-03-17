# hobuse-seedesusteemi1
<!DOCTYPE html>
<html lang="et">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Hobuse seedesüsteemi haigused</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css" rel="stylesheet">
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Inter:wght@300;400;600;700&display=swap');
        
        body {
            font-family: 'Inter', sans-serif;
            scroll-behavior: smooth;
        }

        .gradient-bg {
            background: linear-gradient(135deg, #1e3a8a 0%, #1e40af 100%);
        }

        .card-hover:hover {
            transform: translateY(-5px);
            transition: all 0.3s ease;
        }

        .correct {
            background-color: #dcfce7 !important;
            border-color: #22c55e !important;
        }

        .incorrect {
            background-color: #fee2e2 !important;
            border-color: #ef4444 !important;
        }

        .hidden-section {
            display: none;
        }
    </style>
</head>
<body class="bg-gray-50 text-gray-900">

    <!-- Header -->
    <header class="gradient-bg text-white py-12 px-4 text-center">
        <div class="max-w-4xl mx-auto">
            <h1 class="text-4xl md:text-5xl font-bold mb-4">Hobuse seedesüsteemi haigused</h1>
            <p class="text-xl opacity-90">Järvamaa Kutsehariduskeskus | Julija Boitsova PH-24</p>
        </div>
    </header>

    <!-- Navigation -->
    <nav class="sticky top-0 bg-white shadow-md z-50">
        <div class="max-w-4xl mx-auto flex justify-around p-4">
            <a href="#info" class="font-semibold text-blue-800 hover:text-blue-600">Loe teooriat</a>
            <a href="#quiz" class="font-semibold text-blue-800 hover:text-blue-600">Teadmiste kontroll</a>
        </div>
    </nav>

    <!-- Main Content -->
    <main class="max-w-5xl mx-auto px-4 py-12">
        
        <!-- Section 1: Theory -->
        <section id="info" class="mb-20">
            <div class="flex items-center mb-8">
                <div class="bg-blue-600 p-3 rounded-lg text-white mr-4">
                    <i class="fas fa-book-open text-2xl"></i>
                </div>
                <h2 class="text-3xl font-bold text-gray-800">Sissejuhatus ja eripärad</h2>
            </div>

            <div class="grid md:grid-cols-2 gap-8 mb-12">
                <div class="bg-white p-8 rounded-2xl shadow-sm border border-gray-100">
                    <h3 class="text-xl font-bold mb-4 text-blue-700">Miks on see oluline?</h3>
                    <p class="text-gray-600 leading-relaxed mb-4">
                        Hobuse seedesüsteem on väga tundlik ja eriline. Erinevalt paljudest teistest loomadest <strong>ei suuda hobune oksendada</strong>.
                    </p>
                    <p class="text-gray-600 leading-relaxed">
                        Tema jämesool ja umbsool mängivad suurt rolli toidu seedimisel, mistõttu haigused võivad olla eluohtlikud ja vajavad kiiret tegutsemist.
                    </p>
                </div>
                <div class="bg-white p-8 rounded-2xl shadow-sm border border-gray-100">
                    <h3 class="text-xl font-bold mb-4 text-blue-700">Peamised eripärad</h3>
                    <ul class="space-y-3">
                        <li class="flex items-start"><i class="fas fa-check-circle text-green-500 mt-1 mr-2"></i> Väike magu, suur jäme- ja umbsool.</li>
                        <li class="flex items-start"><i class="fas fa-check-circle text-green-500 mt-1 mr-2"></i> Seedimine toimub mikroorganismide abil.</li>
                        <li class="flex items-start"><i class="fas fa-check-circle text-green-500 mt-1 mr-2"></i> Vajalik on pidev ligipääs heinale ja veele.</li>
                        <li class="flex items-start"><i class="fas fa-check-circle text-green-500 mt-1 mr-2"></i> Järsud söödamuutused on ohtlikud.</li>
                    </ul>
                </div>
            </div>

            <h2 class="text-3xl font-bold text-gray-800 mb-8 flex items-center">
                <i class="fas fa-exclamation-triangle text-orange-500 mr-4"></i>
                Levinumad haigused
            </h2>

            <div class="grid md:grid-cols-2 gap-6">
                <!-- Koolikud -->
                <div class="bg-white p-6 rounded-xl shadow-sm border-l-4 border-orange-500 card-hover">
                    <h3 class="font-bold text-xl mb-3">3.1 Koolikud</h3>
                    <p class="text-sm text-gray-500 mb-3">Kõige sagedasem probleem.</p>
                    <p class="mb-2"><strong>Põhjused:</strong> Halb sööt, kiire söömine, vähene liikumine.</p>
                    <p><strong>Sümptomid:</strong> Kraapimine, kõhu vaatamine, rullimine, isutus.</p>
                </div>

                <!-- Umbsoole gaasid -->
                <div class="bg-white p-6 rounded-xl shadow-sm border-l-4 border-blue-400 card-hover">
                    <h3 class="font-bold text-xl mb-3">3.2 Umbsoole gaasid</h3>
                    <p class="mb-2"><strong>Põhjus:</strong> Liigne teravili või suur kogus värsket rohtu.</p>
                    <p><strong>Oht:</strong> Tekitab tugevat survet ja koolikuid.</p>
                </div>

                <!-- Sooleummistus -->
                <div class="bg-white p-6 rounded-xl shadow-sm border-l-4 border-red-400 card-hover">
                    <h3 class="font-bold text-xl mb-3">3.3 Sooleummistus</h3>
                    <p class="mb-2"><strong>Põhjus:</strong> Kuiv sööt, veepuudus või liiva allaneelamine.</p>
                    <p><strong>Sümptom:</strong> Toit ei liigu seedekulglas edasi.</p>
                </div>

                <!-- Kõhulahtisus -->
                <div class="bg-white p-6 rounded-xl shadow-sm border-l-4 border-yellow-400 card-hover">
                    <h3 class="font-bold text-xl mb-3">3.4 Kõhulahtisus</h3>
                    <p class="mb-2"><strong>Põhjus:</strong> Infektsioonid, stress, antibiootikumid.</p>
                    <p><strong>Oht:</strong> Kriitiline vedelikukaotus.</p>
                </div>
            </div>

            <div class="mt-12 bg-green-50 p-8 rounded-2xl border border-green-200">
                <h2 class="text-2xl font-bold text-green-800 mb-6 text-center">Ennetamine ja Ravi</h2>
                <div class="grid md:grid-cols-2 gap-8">
                    <div>
                        <h4 class="font-bold mb-4 underline">Ennetamine:</h4>
                        <ul class="space-y-2 text-green-900">
                            <li><i class="fas fa-tint mr-2"></i> Pidev puhas vesi</li>
                            <li><i class="fas fa-leaf mr-2"></i> Tolmuvaba kvaliteetne sööt</li>
                            <li><i class="fas fa-walking mr-2"></i> Regulaarne liikumine</li>
                            <li><i class="fas fa-bug mr-2"></i> Parasiitide tõrje</li>
                        </ul>
                    </div>
                    <div>
                        <h4 class="font-bold mb-4 underline">Ravi:</h4>
                        <p class="text-gray-700 italic">"Kiire tegutsemine on eluliselt tähtis!"</p>
                        <p class="mt-2">Raskel juhul: <strong>Veterinaararst</strong>.</p>
                        <p>Kerge juhul: Söötmise korrigeerimine.</p>
                    </div>
                </div>
            </div>
        </section>

        <hr class="mb-20">

        <!-- Section 2: Quiz -->
        <section id="quiz">
            <div class="text-center mb-12">
                <h2 class="text-4xl font-bold text-gray-800 mb-4">Teadmiste kontroll</h2>
                <p class="text-gray-500 text-lg">Vasta 20 küsimusele ja kontrolli oma teadmisi!</p>
            </div>

            <div id="quiz-container" class="space-y-8">
                <!-- Questions will be injected here via JS -->
            </div>

            <div class="mt-12 text-center p-8 bg-white rounded-xl shadow-lg">
                <button onclick="checkResults()" class="bg-blue-700 text-white px-10 py-4 rounded-full font-bold text-lg hover:bg-blue-800 transition shadow-lg">
                    Kontrolli vastuseid
                </button>
                <div id="final-score" class="mt-6 text-2xl font-bold text-blue-800 hidden"></div>
            </div>
        </section>
    </main>

    <footer class="bg-gray-800 text-white py-12 px-4 mt-20 text-center">
        <p>© 2024 Hobuse Tervis. Õppematerjal.</p>
        <p class="text-gray-400 text-sm mt-2">Allikad: Merck Vet Manual, Blue Cross, Extension UMN, RSPCA</p>
    </footer>

    <script>
        const questions = [
            { q: "Miks on hobuse seedesüsteem väga tundlik?", a: ["Ta on kohastunud pidevaks söömiseks väikestes kogustes", "Ta sööb ainult liha", "Tal puudub magu"], c: 0 },
            { q: "Miks ei saa hobune oksendada?", a: ["Tal puuduvad vastavad lihased", "Tema maolävis töötab ühesuunalise ventiilina", "Ta lihtsalt ei taha"], c: 1 },
            { q: "Milline sooleosa on hobusel eriti suur?", a: ["Peensool", "Umb- ja jämesool", "Magu"], c: 1 },
            { q: "Mis on koolikud?", a: ["Üldnimetus kõhuvalule", "Teatud tüüpi parasiit", "Söödalisand"], c: 0 },
            { q: "Nimeta koolikute põhjus:", a: ["Liigne liikumine", "Hallitanud või halb sööt", "Pidev ligipääs heinale"], c: 1 },
            { q: "Nimeta koolikute sümptom:", a: ["Saba liputamine", "Kraapimine ja kõhu vaatamine", "Kiire jooksmine"], c: 1 },
            { q: "Miks on järsk söödamuutus ohtlik?", a: ["Hobune keeldub söömast", "See hävitab seedimiseks vajalikud mikroorganismid", "See muudab hobuse uniseks"], c: 1 },
            { q: "Mis põhjustab umbsooles gaaside teket?", a: ["Värske õhk", "Mikroobide tegevus (eriti liigse suhkru/tärklise puhul)", "Liigne vee joomine"], c: 1 },
            { q: "Miks on teravilja liigne söömine ohtlik?", a: ["See on liiga kallis", "Põhjustab liigset käärimist ja gaase", "Muudab karva liiga läikivaks"], c: 1 },
            { q: "Mis on sooleummistus?", a: ["Olukord, kus toit ei liigu seedekulglas edasi", "Soolte liigne liikumine", "Tühi kõht"], c: 0 },
            { q: "Millest võib tekkida sooleummistus?", a: ["Liigsest veest", "Kuivast ja kiudainetevaesest söödast", "Värskest rohust"], c: 1 },
            { q: "Miks on vesi hobusele väga oluline?", a: ["Ujumiseks", "Aitab toidul seedekulglas liikuda ja ennetab ummistusi", "Hobune ei joogi vett"], c: 1 },
            { q: "Mis võib põhjustada kõhulahtisust?", a: ["Bakteriaalsed infektsioonid või stress", "Liigne magamine", "Kvaliteetne hein"], c: 0 },
            { q: "Miks on kõhulahtisus ohtlik?", a: ["See on kole", "Võib põhjustada ränka vedelikukaotust", "Hobune hakkab oksendama"], c: 1 },
            { q: "Kuidas saab seedesüsteemi haigusi ennetada?", a: ["Sööta ainult kord päevas", "Tagada puhas vesi ja kvaliteetne sööt", "Hoida hobust ainult tallis"], c: 1 },
            { q: "Miks on liikumine hobusele oluline?", a: ["Et hobune ei igatseks", "Soodustab soolte normaalset tööd", "Liikumine polegi oluline"], c: 1 },
            { q: "Millal tuleb kindlasti kutsuda veterinaararst?", a: ["Kui hobune magab", "Kui ilmnevad rasked koolikute tunnused", "Kui hobune sööb heina"], c: 1 },
            { q: "Kuidas mõjutab stress hobuse seedimist?", a: ["See ei mõjuta", "Võib põhjustada kõhulahtisust ja haavandeid", "Parandab seedimist"], c: 1 },
            { q: "Miks on parasiitide tõrje vajalik?", a: ["See on seadusega nõutud", "Parasiidid võivad kahjustada sooli ja põhjustada koolikuid", "Et hobune oleks kiirem"], c: 1 },
            { q: "Mida teha, kui hobusel tekivad koolikute tunnused?", a: ["Oodata hommikuni", "Eemaldada sööt ja kutsuda veterinaar", "Anda hobusele palju süüa"], c: 1 }
        ];

        function initQuiz() {
            const container = document.getElementById('quiz-container');
            questions.forEach((item, index) => {
                const qDiv = document.createElement('div');
                qDiv.className = "bg-white p-6 rounded-xl shadow-sm border border-gray-100";
                qDiv.innerHTML = `
                    <p class="font-bold text-lg mb-4 text-gray-800">${index + 1}. ${item.q}</p>
                    <div class="space-y-2" id="q-${index}">
                        ${item.a.map((ans, i) => `
                            <label class="flex items-center p-3 rounded-lg border border-gray-200 cursor-pointer hover:bg-gray-50 transition">
                                <input type="radio" name="q${index}" value="${i}" class="mr-3 w-4 h-4">
                                <span>${ans}</span>
                            </label>
                        `).join('')}
                    </div>
                `;
                container.appendChild(qDiv);
            });
        }

        function checkResults() {
            let score = 0;
            questions.forEach((item, index) => {
                const selected = document.querySelector(`input[name="q${index}"]:checked`);
                const options = document.getElementById(`q-${index}`).children;
                
                // Reset styles
                for(let opt of options) {
                    opt.classList.remove('correct', 'incorrect');
                }

                if (selected) {
                    const val = parseInt(selected.value);
                    if (val === item.c) {
                        score++;
                        options[val].classList.add('correct');
                    } else {
                        options[val].classList.add('incorrect');
                        options[item.c].classList.add('correct');
                    }
                } else {
                    options[item.c].classList.add('correct');
                }
            });

            const resultDisplay = document.getElementById('final-score');
            resultDisplay.innerHTML = `Sinu tulemus: ${score} / ${questions.length}`;
            resultDisplay.classList.remove('hidden');
            resultDisplay.scrollIntoView({ behavior: 'smooth' });
        }

        window.onload = initQuiz;
    </script>
</body>
</html>
