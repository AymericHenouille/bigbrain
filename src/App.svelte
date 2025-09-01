<script lang="ts">
  // Si besoin d'interactivité plus tard
</script>

<div class="min-h-screen bg-gradient-to-b from-gray-50 to-gray-100 text-gray-900">
  <!-- Header -->
  <header class="container mx-auto flex justify-between items-center py-6 px-2">
    <h1 class="text-2xl font-bold tracking-tight">🧠 BIG BRAIN</h1>
    <nav class="space-x-2">
      <a href="#features" class="hover:text-indigo-600">Fonctionnalités</a>
      <a href="#pricing" class="hover:text-indigo-600">Tarifs</a>
      <a href="#contact" class="hover:text-indigo-600">Contact</a>
    </nav>
  </header>

  <!-- Hero Section -->
  <section class="container mx-auto flex flex-col items-center text-center py-20 px-4">
    <h2 class="text-5xl font-extrabold tracking-tight mb-6">
      Louez un cerveau,<br /> boostez vos idées
    </h2>
    <p class="max-w-2xl text-lg text-gray-600 mb-8">
      BIG BRAIN est le premier service de location de cerveaux à la demande, imaginé par 
      <span class="font-semibold">Tess Deparme</span>.  
      Obtenez un coup de génie quand vous en avez besoin !
    </p>
    <a href="#pricing" 
       class="px-8 py-4 bg-indigo-600 text-white font-semibold rounded-2xl shadow-lg hover:bg-indigo-700 transition">
      Commencer dès maintenant
    </a>
  </section>

  <!-- Features -->
  <section id="features" class="container mx-auto py-20 px-4 grid md:grid-cols-3 gap-12 text-center">
    <div class="p-6 bg-white rounded-2xl shadow-md hover:shadow-lg transition">
      <h3 class="text-xl font-bold mb-3">⚡ Idées instantanées</h3>
      <p class="text-gray-600">Connectez-vous à un cerveau et générez des solutions créatives en quelques secondes.</p>
    </div>
    <div class="p-6 bg-white rounded-2xl shadow-md hover:shadow-lg transition">
      <h3 class="text-xl font-bold mb-3">🤝 Collaboration fluide</h3>
      <p class="text-gray-600">Travaillez avec un cerveau comme si c'était un collègue, sans paperasse inutile.</p>
    </div>
    <div class="p-6 bg-white rounded-2xl shadow-md hover:shadow-lg transition">
      <h3 class="text-xl font-bold mb-3">🔒 Sécurité totale</h3>
      <p class="text-gray-600">Vos idées restent protégées, nos cerveaux loués respectent la confidentialité.</p>
    </div>
  </section>

  <!-- Pricing -->
  <section id="pricing" class="bg-indigo-50 py-20 px-4">
    <div class="container mx-auto text-center">
      <h2 class="text-3xl font-extrabold mb-8">Nos offres</h2>
      <div class="grid md:grid-cols-3 gap-8">
        <div class="p-6 bg-white rounded-2xl shadow-md">
          <h3 class="text-xl font-bold mb-4">Starter 🥉</h3>
          <p class="text-4xl font-extrabold mb-4">29€</p>
          <p class="mb-6 text-gray-600">1h de cerveau / semaine</p>
          <a href="#" class="px-6 py-3 bg-indigo-600 text-white rounded-xl hover:bg-indigo-700 transition">Choisir</a>
        </div>
        <div class="p-6 bg-white rounded-2xl shadow-md border-2 border-indigo-600">
          <h3 class="text-xl font-bold mb-4">Pro 🥈</h3>
          <p class="text-4xl font-extrabold mb-4">99€</p>
          <p class="mb-6 text-gray-600">5h de cerveau / semaine</p>
          <a href="#" class="px-6 py-3 bg-indigo-600 text-white rounded-xl hover:bg-indigo-700 transition">Choisir</a>
        </div>
        <div class="p-6 bg-white rounded-2xl shadow-md">
          <h3 class="text-xl font-bold mb-4">Ultimate 🥇</h3>
          <p class="text-4xl font-extrabold mb-4">199€</p>
          <p class="mb-6 text-gray-600">Cerveau illimité 24/7</p>
          <a href="#" class="px-6 py-3 bg-indigo-600 text-white rounded-xl hover:bg-indigo-700 transition">Choisir</a>
        </div>
      </div>
    </div>
  </section>

  <!-- Contact -->
  <section id="contact" class="container mx-auto py-20 px-4 text-center">
    <h2 class="text-3xl font-extrabold mb-6">Restons en contact</h2>
    <p class="text-gray-600 mb-8">Envie d’un cerveau pour votre prochain projet ?</p>
    <form class="max-w-lg mx-auto space-y-4">
      <input type="email" placeholder="Votre email"
             class="w-full p-3 border rounded-xl focus:outline-none focus:ring-2 focus:ring-indigo-600"/>
      <textarea placeholder="Votre message"
                class="w-full p-3 border rounded-xl focus:outline-none focus:ring-2 focus:ring-indigo-600"></textarea>
      <button type="submit"
              class="w-full px-6 py-3 bg-indigo-600 text-white font-semibold rounded-xl hover:bg-indigo-700 transition">
        Envoyer
      </button>
    </form>
  </section>

  <!-- Footer -->
  <footer class="bg-gray-900 text-gray-400 py-6 text-center">
    <p>&copy; {new Date().getFullYear()} BIG BRAIN - Une idée de Tess Deparme</p>
  </footer>
</div>

