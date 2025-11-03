# Curriculo-Alife
Currículo desenvolvido por HTML5, CSS3 e TailwindCSS


<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Currículo</title>
    <link rel="stylesheet" href="style.css"></link>
    <script src="https://cdn.tailwindcss.com"></script>
</head>
<body class="bg-gradient-to-r from-stone-300 to-amber-200">
    <header class="bg-indigo-500 p-1 rounded-lg shadow-xl">
        <h1 class="text-3xl font-bold text-center mb-2 text-white">Álife Roberto Soares Nunes</h1>
        <p class="text-2xl font-bold text-center mb-2 text-white">Desenvolvedor front-end</p>
        <button id="theme-toggle" class="bg-white dark:bg-stone-900 text-indigo-700 dark:text-stone-200 transition all duration-500 rounded-lg">🌞</button>
    </header>
    <div class="flex flex-wrap justify-center gap-6 mt-8">
        <div class="bg-white shadow-lg rounded-lg p-6 mt-6 max-w-lg mx-5 w-full">
            <h1 class="font-extrabold text-stone-800 text-xl text-center mb-5">Informações pessoais</h1>
            <p class="mb-1 text-lg">Email: aliferobertodev2024@gmail.com</p>
            <p class="mb-1 text-lg">Telefone: +55(86) 99530-6995</p>
            <p class="mb-1 text-lg">Endereço: Rua Tabajara, 1685 - Parnaíba, Piauí</p>
            <a href="https://www.linkedin.com/in/%C3%A1life-roberto-soares-nunes-583639327/" class="mb-1 text-lg underline text-blue-600 font-semibold">Clique aqui (Linkedln)</a>
        </div>
        <div class="bg-white shadow-lg rounded-lg p-6 mt-6 max-w-lg mx-10 md:w-1/2 lg:w-1/3 text-lg text-stone-800">
            <h1 class="font-extrabold text-center mb-5">Objetivo Profissional</h1>
            <p class="text-justify">Desenvolvedor Front-End focado em criar interfaces modernas e responsivas.
            Experiência com HTML, CSS, JavaScript e TailwindCSS.
            Busco oportunidades para aplicar habilidades técnicas e contribuir em projetos desafiadores.</p>
        </div>
        <div class="bg-white shadow-lg rounded-lg p-6 mt-6 max-w-lg mx-5 md:w-1/2 lg:w-1/3 text-stone-800">
            <h1 class="font-extrabold text-xl text-center mb-5">Habilidades</h1>
            <ul class="text-lg mb-1">
                <li class="">HTML / CSS / JS</li>
                <li class="">Tailwind CSS</li>
                <li class="">Git / GitHub</li>
                <li class="">UI/UX e Design Responsivo</li>
            </ul>
            <h1 class="font-extrabold text-xl text-center mt-4">Habilidades Pessoais</h1>
            <ul class="text-lg mt-2">
                <li class="">Inglês - Básico</li>
                <li class="">Comunicação clara</li>
                <li class="">Aprendizado contínuo</li>
                <li class="">Atenção aos detalhes</li>
                <li class="">Trabalho em equipe</li>
            </ul>
        </div>
        <div class="bg-white shadow-lg rounded-lg p-6 mt-6 w-full max-w-lg mx-10 md:w-1/2 lg:w-1/3">
            <h1 class="font-extrabold text-stone-800 text-xl text-center mb-4">Projetos</h1>
            <h3 class="font-semibold text-stone-800 text-lg text-center">Confira todos os meus projetos do GitHub:</h3>
            <div class="text-center mt-2">
                <a href="https://github.com/devlifinho?tab=repositories" class="font-semibold text-blue-600 underline">Clique aqui</a>
            </div>
        </div>
        <div class="bg-white shadow-lg rounded-lg p-6 mt-6 w-full max-w-lg mx-5 md:w-1/2 lg:w-1/3 text-stone-800">
            <h1 class="font-extrabold text-xl text-center mb-4">Educação</h1>
            <h3 class="font-semibold text-lg text-center">Ensino Médio</h3>
            <p class="mt-4 text-lg">Centro Educacional Contexto - Parnaíba</p>
            <p class="text-lg">Concluído em Dezembro/2022</p>
            <p class="font-semibold text-lg text-center mt-4">Ensino Superior</p>
            <p class="mt-2 text-lg">Análise e desenvolvimento de sistemas - Instituto Federal do Piauí - Campus Parnaíba</p>
            <p class="text-lg">Cursando (2024-Atual)</p>
        </div>
    </div>
    <footer class="text-center text-lg text-stone-900 mt-10 mb-4 font-semibold">© 2025 - Desenvolvido por Álife Roberto Soares Nunes com TailwindCSS</footer>
</body>
</html>
