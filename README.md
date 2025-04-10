<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Finance Dashboard</title>
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;600;700&display=swap" rel="stylesheet">
  <script src="https://cdn.tailwindcss.com"></script>
  <style>
    body {
      font-family: 'Inter', sans-serif;
      background-color: #0a1e2c;
      color: white;
    }
  </style>
</head>
<body class="min-h-screen px-4 py-6">
  <div class="max-w-sm mx-auto bg-[#122b3a] p-4 rounded-2xl shadow-lg">
    <div class="flex justify-between items-center">
      <div>
        <h2 class="text-lg">Olá, <span class="font-semibold">Gustavo</span></h2>
        <p class="text-sm text-gray-300 mt-1">Saldo total</p>
        <p class="text-2xl font-bold text-green-400 mt-1">R$2,340.62</p>
        <p class="text-xs text-green-400 mt-1">+ R$102.3 (1.3%)</p>
      </div>
      <div>
        <img src="https://img.icons8.com/ios-filled/50/ffffff/visible.png" class="w-6 h-6 mb-2"/>
        <img src="https://img.icons8.com/ios-filled/50/ffffff/appointment-reminders.png" class="w-6 h-6"/>
      </div>
    </div>

    <div class="mt-4 flex gap-2">
      <button class="flex-1 bg-green-500 text-white py-2 rounded-lg font-semibold">Adicionar fundos</button>
      <button class="flex-1 bg-gray-700 text-white py-2 rounded-lg font-semibold">Criar Plano</button>
    </div>

    <div class="bg-[#1e3b4c] p-4 rounded-lg mt-4">
      <div class="flex items-center gap-4">
        <div class="w-16 h-16 rounded-full bg-blue-200 flex items-center justify-center text-black font-bold">75%</div>
        <div class="text-sm">
          <p class="font-semibold">Concluir a configuração da sua conta</p>
          <p class="text-gray-300 text-xs">O Rise exige que você conclua a configuração de sua conta e preencha as informações ausentes</p>
          <a href="#" class="text-blue-400 text-xs underline">Atualizar informações da conta</a>
        </div>
      </div>
    </div>

    <div class="bg-[#1e3b4c] p-4 rounded-lg mt-4">
      <h3 class="text-sm font-semibold">2 Planos Ativos</h3>
      <div class="text-xs text-gray-300 mt-2">40% Ações | 48% Imobiliário | 12% Renda Fixa</div>
      <div class="h-32 bg-gradient-to-t from-[#0a1e2c] to-[#2bc4a6] mt-2 rounded-lg"></div>
      <div class="flex justify-between text-sm mt-2">
        <div>
          <p class="font-semibold">R$340.62</p>
          <p class="text-xs text-gray-300">Ganhos totais</p>
        </div>
        <div>
          <p class="font-semibold">$1,307.62</p>
          <p class="text-xs text-gray-300">Depósito total</p>
        </div>
      </div>
      <p class="text-xs text-green-400 mt-1">+13% retorna do ano de início até a data</p>
    </div>

    <div class="mt-6 border-t border-gray-700 pt-3 flex justify-around text-sm text-gray-400">
      <span class="text-white font-semibold">inicio</span>
      <span>Planos</span>
      <span>Status</span>
      <span>Conta</span>
    </div>
  </div>
</body>
</html>
