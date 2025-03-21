<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Plataforma Circular</title>
    <script src="https://cdn.tailwindcss.com"></script>
</head>
<body class="bg-gray-100">
    <!-- Navbar -->
    <nav class="bg-green-600 p-4 text-white text-center text-xl font-bold">
        Plataforma de Economia Circular
    </nav>
    
    <!-- Seção Principal -->
    <header class="text-center py-16 bg-green-100">
        <h1 class="text-4xl font-bold text-green-700">Conectando Empresas e Consumidores para um Mundo Sustentável</h1>
        <p class="text-gray-600 mt-4">Transforme resíduos em oportunidades! Encontre ou venda materiais reutilizados.</p>
    </header>
    
    <!-- Seção para Empresas -->
    <section class="max-w-4xl mx-auto py-10">
        <h2 class="text-3xl text-center font-bold text-green-700">Para Empresas</h2>
        <p class="text-center text-gray-600">Cadastre seus materiais e participe da economia circular.</p>
        <form class="bg-white p-6 shadow-lg rounded-lg mt-6">
            <label class="block text-gray-700">Nome da Empresa:</label>
            <input type="text" class="w-full p-2 border rounded mt-2" placeholder="Digite o nome da sua empresa">
            
            <label class="block text-gray-700 mt-4">E-mail:</label>
            <input type="email" class="w-full p-2 border rounded mt-2" placeholder="Digite seu e-mail">
            
            <label class="block text-gray-700 mt-4">Materiais Disponíveis:</label>
            <textarea class="w-full p-2 border rounded mt-2" placeholder="Descreva os materiais que deseja cadastrar"></textarea>
            
            <button class="mt-6 bg-green-600 text-white p-2 rounded w-full">Cadastrar</button>
        </form>
    </section>
    
    <!-- Seção para Clientes -->
    <section class="max-w-4xl mx-auto py-10">
        <h2 class="text-3xl text-center font-bold text-green-700">Para Clientes</h2>
        <p class="text-center text-gray-600">Encontre materiais sustentáveis para seus projetos.</p>
        <div class="grid grid-cols-1 md:grid-cols-3 gap-6 mt-6">
            <div class="bg-white p-6 shadow-lg rounded-lg">
                <h3 class="font-bold text-xl">Madeira Reutilizada</h3>
                <p class="text-gray-600">Tábua de madeira de demolição - ótima para pisos e móveis.</p>
                <button class="mt-4 bg-green-600 text-white p-2 rounded w-full">Comprar</button>
            </div>
            <div class="bg-white p-6 shadow-lg rounded-lg">
                <h3 class="font-bold text-xl">Janelas de Alumínio</h3>
                <p class="text-gray-600">Janelas usadas em bom estado para reutilização.</p>
                <button class="mt-4 bg-green-600 text-white p-2 rounded w-full">Comprar</button>
            </div>
            <div class="bg-white p-6 shadow-lg rounded-lg">
                <h3 class="font-bold text-xl">Sobras de Tinta</h3>
                <p class="text-gray-600">Tintas de diversas cores disponíveis para reutilização.</p>
                <button class="mt-4 bg-green-600 text-white p-2 rounded w-full">Comprar</button>
            </div>
        </div>
    </section>
    
    <!-- Rodapé -->
    <footer class="bg-green-600 p-4 text-white text-center mt-10">
        © 2025 Plataforma Circular - Todos os direitos reservados
    </footer>
</body>
</html>
