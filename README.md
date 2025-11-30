<!DOCTYPE html>
<html lang="fr">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Chats du Pic - Accueil</title>
  <script src="https://cdn.tailwindcss.com"></script>
</head>

<body class="bg-yellow-50 text-gray-800 font-sans">

  <!-- HEADER -->
  <header class="bg-yellow-400 py-6 shadow-lg rounded-b-3xl">
    <div class="max-w-6xl mx-auto flex justify-between items-center px-6">
      <h1 class="text-2xl font-extrabold text-gray-900">Chats du Pic</h1>
      <nav class="space-x-6">
        <a href="#services" class="font-medium hover:text-gray-900">Services</a>
        <a href="#galerie" class="font-medium hover:text-gray-900">Galerie</a>
        <a href="#apropos" class="font-medium hover:text-gray-900">À propos</a>
        <a href="#contact" class="font-medium hover:text-gray-900">Contact</a>
      </nav>
    </div>
  </header>

  <!-- HERO -->
  <section class="bg-yellow-100 rounded-b-3xl shadow-inner">
    <div class="max-w-6xl mx-auto text-center py-28 px-6">
      <h2 class="text-5xl font-extrabold text-gray-900 mb-4">Chats du Pic</h2>
      <p class="text-xl text-gray-700 mb-10">Confort, sécurité et amour — comme à la maison pour votre chat.</p>
      <a href="#contact" class="bg-yellow-400 hover:bg-yellow-500 text-gray-900 font-semibold px-10 py-4 rounded-3xl shadow-lg transition duration-300">
        Réserver un séjour
      </a>
    </div>
  </section>

  <!-- SERVICES -->
  <section id="services" class="py-24 bg-yellow-50">
    <div class="max-w-6xl mx-auto px-6">
      <h3 class="text-4xl font-bold text-gray-900 text-center mb-16">Nos Services</h3>
      <div class="grid md:grid-cols-3 gap-12">

        <div class="p-8 bg-yellow-200 rounded-3xl shadow-lg text-center transition hover:scale-105 duration-300">
          <h4 class="text-2xl font-bold mb-4">Séjour court</h4>
          <p>Idéal pour un week-end ou quelques jours. Confort garanti.</p>
        </div>

        <div class="p-8 bg-yellow-200 rounded-3xl shadow-lg text-center transition hover:scale-105 duration-300">
          <h4 class="text-2xl font-bold mb-4">Séjour long</h4>
          <p>Une prise en charge complète pour les vacances ou déplacements prolongés.</p>
        </div>

        <div class="p-8 bg-yellow-200 rounded-3xl shadow-lg text-center transition hover:scale-105 duration-300">
          <h4 class="text-2xl font-bold mb-4">Soins & alimentation</h4>
          <p>Repas adaptés, suivi quotidien, administration de soins si besoin.</p>
        </div>

      </div>
    </div>
  </section>

  <!-- GALERIE -->
  <section id="galerie" class="py-24 bg-yellow-100">
    <div class="max-w-6xl mx-auto px-6">
      <h3 class="text-4xl font-bold text-gray-900 text-center mb-12">Galerie</h3>
      <div class="grid md:grid-cols-3 gap-8">

        <img src="https://placekitten.com/400/300" class="rounded-3xl shadow-lg">
        <img src="https://placekitten.com/401/300" class="rounded-3xl shadow-lg">
        <img src="https://placekitten.com/402/300" class="rounded-3xl shadow-lg">
      
      </div>
    </div>
  </section>

  <!-- A PROPOS -->
  <section id="apropos" class="py-24 bg-yellow-50">
    <div class="max-w-4xl mx-auto px-6 text-center">
      <h3 class="text-4xl font-bold text-gray-900 mb-8">À propos</h3>
      <p class="text-lg text-gray-700 leading-relaxed">
        Passionnée par les animaux depuis l’enfance, je me suis spécialisée dans l’accueil et le bien-être des chats.  
        Votre compagnon est accueilli dans un environnement calme, sécurisé et chaleureux.
      </p>
    </div>
  </section>

  <!-- CONTACT -->
  <section id="contact" class="py-24 bg-yellow-200">
    <div class="max-w-4xl mx-auto px-6">
      <h3 class="text-4xl font-bold text-gray-900 text-center mb-12">Contact & Réservations</h3>

      <form class="bg-white p-10 rounded-3xl shadow-lg grid gap-6">

        <input type="text" placeholder="Nom" class="border p-4 rounded-2xl">
        <input type="email" placeholder="Email" class="border p-4 rounded-2xl">
        <textarea placeholder="Message" rows="5" class="border p-4 rounded-2xl"></textarea>

        <button class="bg-yellow-400 hover:bg-yellow-500 text-gray-900 font-semibold py-4 rounded-3xl transition duration-300">
          Envoyer
        </button>
      </form>
    </div>
  </section>

  <!-- FOOTER -->
  <footer class="bg-gray-900 text-white text-center py-6 rounded-t-3xl">
    <p>Chats du Pic © 2025 — Tous droits réservés.</p>
  </footer>

</body>
</html>
