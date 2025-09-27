<!DOCTYPE html>
<html lang="pt-br">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Inbox Privada</title>
  <script src="https://cdn.tailwindcss.com"></script>
</head>
<body class="bg-gray-900 text-white font-sans">

  <!-- Barra lateral com abas -->
  <div class="flex h-screen">
    <aside class="w-64 bg-gray-800 p-4">
      <h2 class="text-xl font-bold mb-4">Mensagens</h2>
      <ul class="space-y-2">
        <li class="bg-gray-700 p-2 rounded hover:bg-gray-600 cursor-pointer">João - Projeto feira</li>
        <li class="bg-gray-700 p-2 rounded hover:bg-gray-600 cursor-pointer">Maria - Script Roblox</li>
        <li class="bg-gray-700 p-2 rounded hover:bg-gray-600 cursor-pointer">Lucas - Foto para Discord</li>
      </ul>
    </aside>

    <!-- Área de leitura e resposta -->
    <main class="flex-1 p-6">
      <h1 class="text-2xl font-semibold mb-4">Mensagem de João</h1>
      <div class="bg-gray-800 p-4 rounded mb-4">
        <p>Oi! Queria ajuda com o projeto da feira de ciências. Você pode me responder aqui?</p>
      </div>

      <form class="space-y-4">
        <textarea class="w-full p-3 rounded bg-gray-700 text-white" rows="5" placeholder="Digite sua resposta..."></textarea>
        <button type="submit" class="bg-blue-600 hover:bg-blue-700 px-4 py-2 rounded text-white">Responder</button>
      </form>
    </main>
  </div>
</body>
</html>
