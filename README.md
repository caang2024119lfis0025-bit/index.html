<!DOCTYPE html>
<html lang="pt-BR">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <title>Café Sereno</title>

    <script src="https://cdn.jsdelivr.net/npm/@tailwindcss/browser@4"></script>
</head>

<body class="bg-[rgba(245,250,255,1)] text-slate-800">

<!-- ================================================= -->
<!-- HEADER -->
<!-- ================================================= -->

<header class="fixed top-0 left-0 w-full z-50
bg-[rgba(240,248,255,0.95)]
backdrop-blur-md
shadow-lg">

    <div class="max-w-7xl mx-auto
    flex
    justify-between
    items-center
    px-8
    py-5">

        <!-- Logo -->

        <div
        class="text-3xl
        font-bold
        text-sky-900
        tracking-wide">

            Café Sereno

        </div>

        <!-- Menu -->

        <nav>

            <ul class="
            hidden
            lg:flex
            gap-8
            text-lg
            font-medium">

                <li>
                    <a href="#inicio"
                    class="hover:text-sky-600
                    duration-300">
                    Início
                    </a>
                </li>

                <li>
                    <a href="#sobre"
                    class="hover:text-sky-600
                    duration-300">
                    Sobre Nós
                    </a>
                </li>

                <li>
                    <a href="#metodos"
                    class="hover:text-sky-600
                    duration-300">
                    Métodos
                    </a>
                </li>

                <li>
                    <a href="#menu"
                    class="hover:text-sky-600
                    duration-300">
                    Cardápio
                    </a>
                </li>

                <li>
                    <a href="#galeria"
                    class="hover:text-sky-600
                    duration-300">
                    Espaço
                    </a>
                </li>

                <li>
                    <a href="#avaliacoes"
                    class="hover:text-sky-600
                    duration-300">
                    Avaliações
                    </a>
                </li>

                <li>
                    <a href="#contato"
                    class="hover:text-sky-600
                    duration-300">
                    Contato
                    </a>
                </li>

            </ul>

        </nav>

    </div>

</header>

<!-- ================================================= -->
<!-- HERO -->
<!-- ================================================= -->

<section
id="inicio"
class="

min-h-screen

flex

items-center

justify-center

px-8

pt-40

bg-gradient-to-br

from-[rgba(224,242,254,1)]

via-[rgba(240,249,255,1)]

to-[rgba(186,230,253,0.45)]

">

<div
class="

max-w-7xl

grid

lg:grid-cols-2

gap-20

items-center

">

<!-- Texto -->

<div>

<h1 class="

text-5xl

md:text-6xl

font-extrabold

leading-tight

text-sky-900

">

Sabor artesanal,

<br>

momento sereno.

</h1>

<p class="

mt-8

text-xl

leading-9

text-slate-700

">

Encontre a paz na sua rotina com nossos grãos
selecionados, preparados artesanalmente e servidos
em um ambiente acolhedor pensado para proporcionar
tranquilidade em cada visita.

</p>

<div class="mt-12 flex flex-wrap gap-6">

<a href="#menu"

class="

bg-sky-600

text-white

px-8

py-4

rounded-full

font-semibold

hover:bg-sky-700

duration-300

shadow-xl

">

Ver Cardápio

</a>

<a href="#sobre"

class="

border-2

border-sky-500

px-8

py-4

rounded-full

font-semibold

hover:bg-sky-100

duration-300

">

Conheça Nossa História

</a>

</div>

</div>

<!-- Imagem -->

<div
class="flex justify-center">

<img

src="https://images.unsplash.com/photo-1495474472287-4d71bcdd2085?w=900"

alt="Café"

class="

rounded-[40px]

shadow-2xl

hover:scale-105

duration-500

w-full

max-w-xl

">

</div>

</div>

</section>

<!-- ================================================= -->
<!-- FIM DA HERO -->
<!-- ================================================= -->

<!-- ================================================= -->
<!-- PRÓXIMA PARTE -->
<!-- Sobre Nós -->
<!-- Cards de Estatísticas -->
<!-- Responsividade -->
<!-- ================================================= -->
<!-- ================================================= -->
<!-- FAVORITOS -->
<!-- ================================================= -->

<section
id="menu"
class="py-24 px-6 bg-[rgba(248,252,255,1)]">

<div class="max-w-7xl mx-auto">

<div class="text-center mb-16">

<h2 class="text-4xl md:text-5xl font-bold text-sky-900">
Nossos Favoritos
</h2>

<p class="mt-5 text-lg text-slate-600 max-w-3xl mx-auto">
Conheça algumas das bebidas preferidas dos nossos clientes.
Preparadas artesanalmente e com ingredientes selecionados.
</p>

</div>

<div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-10">

<!-- CARD 1 -->

<div class="bg-white rounded-3xl overflow-hidden shadow-lg hover:shadow-2xl transition duration-500 hover:-translate-y-3">

<img
src="https://images.unsplash.com/photo-1517705008128-361805f42e86?w=800"
class="w-full h-72 object-cover">

<div class="p-8">

<h3 class="text-2xl font-bold text-sky-900">
Espresso Sereno
</h3>

<p class="mt-4 text-slate-600 leading-8">
Torra média com notas de chocolate,
avelã e um aroma marcante.
Ideal para quem aprecia cafés intensos.
</p>

<div class="flex justify-between items-center mt-8">

<span class="text-2xl font-bold text-sky-700">
R$ 10,90
</span>

<button class="bg-sky-600 text-white px-6 py-3 rounded-full hover:bg-sky-700 duration-300">
Comprar
</button>

</div>

</div>

</div>

<!-- CARD 2 -->

<div class="bg-white rounded-3xl overflow-hidden shadow-lg hover:shadow-2xl transition duration-500 hover:-translate-y-3">

<img
src="https://images.unsplash.com/photo-1495474472287-4d71bcdd2085?w=800"
class="w-full h-72 object-cover">

<div class="p-8">

<h3 class="text-2xl font-bold text-sky-900">
Aeropress
</h3>

<p class="mt-4 text-slate-600 leading-8">
Extração suave utilizando pressão do ar,
realçando sabores delicados e reduzindo
a acidez.
</p>

<div class="flex justify-between items-center mt-8">

<span class="text-2xl font-bold text-sky-700">
R$ 14,90
</span>

<button class="bg-sky-600 text-white px-6 py-3 rounded-full hover:bg-sky-700 duration-300">
Comprar
</button>

</div>

</div>

</div>

<!-- CARD 3 -->

<div class="bg-white rounded-3xl overflow-hidden shadow-lg hover:shadow-2xl transition duration-500 hover:-translate-y-3">

<img
src="https://images.unsplash.com/photo-1509042239860-f550ce710b93?w=800"
class="w-full h-72 object-cover">

<div class="p-8">

<h3 class="text-2xl font-bold text-sky-900">
Cappuccino Aveludado
</h3>

<p class="mt-4 text-slate-600 leading-8">
Leite vaporizado perfeitamente,
cacau especial e café premium,
criando uma bebida cremosa.
</p>

<div class="flex justify-between items-center mt-8">

<span class="text-2xl font-bold text-sky-700">
R$ 16,90
</span>

<button class="bg-sky-600 text-white px-6 py-3 rounded-full hover:bg-sky-700 duration-300">
Comprar
</button>

</div>

</div>

</div>

</div>

</div>

</section>

<!-- ================================================= -->
<!-- MÉTODOS -->
<!-- ================================================= -->

<section
id="metodos"
class="py-24 px-6 bg-[rgba(230,245,255,.7)]">

<div class="max-w-7xl mx-auto">

<div class="text-center">

<h2 class="text-4xl font-bold text-sky-900">
Métodos de Preparo
</h2>

<p class="mt-6 text-lg text-slate-600">
Cada método proporciona uma experiência diferente.
</p>

</div>

<div class="grid md:grid-cols-2 lg:grid-cols-4 gap-8 mt-16">

<div class="bg-white rounded-3xl p-8 shadow-lg hover:shadow-xl hover:scale-105 transition">
<h3 class="text-2xl font-bold text-sky-900">☕ V60</h3>
<p class="mt-4 text-slate-600 leading-7">
Extração lenta que destaca notas doces e aroma delicado.
</p>
</div>

<div class="bg-white rounded-3xl p-8 shadow-lg hover:shadow-xl hover:scale-105 transition">
<h3 class="text-2xl font-bold text-sky-900">☕ Aeropress</h3>
<p class="mt-4 text-slate-600 leading-7">
Método versátil com baixa acidez e sabor equilibrado.
</p>
</div>

<div class="bg-white rounded-3xl p-8 shadow-lg hover:shadow-xl hover:scale-105 transition">
<h3 class="text-2xl font-bold text-sky-900">☕ Prensa Francesa</h3>
<p class="mt-4 text-slate-600 leading-7">
Café encorpado preservando os óleos naturais dos grãos.
</p>
</div>

<div class="bg-white rounded-3xl p-8 shadow-lg hover:shadow-xl hover:scale-105 transition">
<h3 class="text-2xl font-bold text-sky-900">☕ Espresso</h3>
<p class="mt-4 text-slate-600 leading-7">
Preparado sob alta pressão, intenso e extremamente aromático.
</p>
</div>

</div>

</div>

</section>

<!-- ================================================= -->
<!-- FIM DA PARTE 3 -->
<!-- Na próxima parte: Galeria + Avaliações ⭐⭐⭐⭐⭐ -->
<!-- ================================================= -->

<!-- ================================================= -->
<!-- GALERIA -->
<!-- ================================================= -->

<section
id="galeria"
class="py-24 px-6 bg-[rgba(245,250,255,1)]">

<div class="max-w-7xl mx-auto">

<div class="text-center mb-16">

<h2 class="text-4xl md:text-5xl font-bold text-sky-900">
Nosso Refúgio
</h2>

<p class="mt-5 text-lg text-slate-600 max-w-3xl mx-auto">
Um ambiente pensado para quem deseja relaxar, estudar,
trabalhar ou simplesmente apreciar um excelente café.
</p>

</div>

<div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-8">

<div class="overflow-hidden rounded-3xl shadow-lg hover:shadow-2xl transition duration-500">

<img
src="https://images.unsplash.com/photo-1554118811-1e0d58224f24?w=900"
alt="Interior da cafeteria"
class="w-full h-80 object-cover hover:scale-110 transition duration-700">

</div>

<div class="overflow-hidden rounded-3xl shadow-lg hover:shadow-2xl transition duration-500">

<img
src="https://images.unsplash.com/photo-1495474472287-4d71bcdd2085?w=900"
alt="Barista preparando café"
class="w-full h-80 object-cover hover:scale-110 transition duration-700">

</div>

<div class="overflow-hidden rounded-3xl shadow-lg hover:shadow-2xl transition duration-500">

<img
src="https://images.unsplash.com/photo-1445116572660-236099ec97a0?w=900"
alt="Mesa de café"
class="w-full h-80 object-cover hover:scale-110 transition duration-700">

</div>

<div class="overflow-hidden rounded-3xl shadow-lg hover:shadow-2xl transition duration-500">

<img
src="https://images.unsplash.com/photo-1501339847302-ac426a4a7cbb?w=900"
class="w-full h-80 object-cover hover:scale-110 transition duration-700">

</div>

<div class="overflow-hidden rounded-3xl shadow-lg hover:shadow-2xl transition duration-500">

<img
src="https://images.unsplash.com/photo-1453614512568-c4024d13c247?w=900"
class="w-full h-80 object-cover hover:scale-110 transition duration-700">

</div>

<div class="overflow-hidden rounded-3xl shadow-lg hover:shadow-2xl transition duration-500">

<img
src="https://images.unsplash.com/photo-1511920170033-f8396924c348?w=900"
class="w-full h-80 object-cover hover:scale-110 transition duration-700">

</div>

</div>

</div>

</section>

<!-- ================================================= -->
<!-- AVALIAÇÕES -->
<!-- ================================================= -->

<section
id="avaliacoes"
class="py-24 px-6 bg-[rgba(224,242,254,.6)]">

<div class="max-w-7xl mx-auto">

<div class="text-center mb-16">

<h2 class="text-4xl md:text-5xl font-bold text-sky-900">
Quem nos Visita
</h2>

<p class="mt-5 text-lg text-slate-600">
Veja a opinião de alguns clientes.
</p>

</div>

<div class="grid md:grid-cols-2 lg:grid-cols-3 gap-10">

<!-- CARD 1 -->

<div class="bg-white rounded-3xl shadow-xl p-8 hover:-translate-y-2 hover:shadow-2xl transition">

<div class="flex items-center gap-5">

<img
src="https://i.pravatar.cc/100?img=5"
class="w-16 h-16 rounded-full">

<div>

<h3 class="font-bold text-xl text-sky-900">
Mariana de Souza
</h3>

<div class="text-yellow-400 text-xl">
★★★★★
</div>

</div>

</div>

<p class="mt-6 text-slate-600 leading-8 italic">
"O melhor lugar da cidade para ler um livro e tomar um café impecável. Voltarei muitas vezes."
</p>

</div>

<!-- CARD 2 -->

<div class="bg-white rounded-3xl shadow-xl p-8 hover:-translate-y-2 hover:shadow-2xl transition">

<div class="flex items-center gap-5">

<img
src="https://i.pravatar.cc/100?img=12"
class="w-16 h-16 rounded-full">

<div>

<h3 class="font-bold text-xl text-sky-900">
Carlos Pires
</h3>

<div class="text-yellow-400 text-xl">
★★★★★
</div>

</div>

</div>

<p class="mt-6 text-slate-600 leading-8 italic">
"O Espresso Sereno realmente faz jus ao nome. Atendimento excelente e ambiente extremamente agradável."
</p>

</div>

<!-- CARD 3 -->

<div class="bg-white rounded-3xl shadow-xl p-8 hover:-translate-y-2 hover:shadow-2xl transition">

<div class="flex items-center gap-5">

<img
src="https://i.pravatar.cc/100?img=20"
class="w-16 h-16 rounded-full">

<div>

<h3 class="font-bold text-xl text-sky-900">
Beatriz Moura
</h3>

<div class="text-yellow-400 text-xl">
★★★★★
</div>

</div>

</div>

<p class="mt-6 text-slate-600 leading-8 italic">
"Espaço perfeito para home office. Internet rápida, poltronas confortáveis e um cappuccino maravilhoso."
</p>

</div>

</div>

</div>

</section>

<!-- ================================================= -->
<!-- ESPAÇO PARA NOVAS SEÇÕES -->
<!-- Basta copiar uma SECTION e alterar o conteúdo -->
<!-- ================================================= -->

<!-- ================================================= -->
<!-- CONTATO -->
<!-- ================================================= -->

<section
id="contato"
class="py-24 px-6 bg-[rgba(240,249,255,1)]">

<div class="max-w-7xl mx-auto">

<div class="text-center mb-16">

<h2 class="text-4xl md:text-5xl font-bold text-sky-900">
Venha nos Visitar
</h2>

<p class="mt-5 text-lg text-slate-600">
Será um prazer receber você em nossa cafeteria.
</p>

</div>

<div class="grid lg:grid-cols-2 gap-12">

<!-- Informações -->

<div class="bg-white rounded-3xl shadow-xl p-10">

<h3 class="text-3xl font-bold text-sky-900">
Informações
</h3>

<div class="mt-8 space-y-6 text-lg">

<div>
<p class="font-semibold text-sky-800">📍 Endereço</p>
<p class="text-slate-600">
Rua Wattersons, 123 - Centro
</p>
</div>

<div>
<p class="font-semibold text-sky-800">📞 Telefone</p>
<p class="text-slate-600">
(86) 99999-9999
</p>
</div>

<div>
<p class="font-semibold text-sky-800">✉️ E-mail</p>
<p class="text-slate-600">
contato@cafesereno.com
</p>
</div>

<div>
<p class="font-semibold text-sky-800">🕒 Horário</p>
<p class="text-slate-600">
Segunda a Domingo
<br>
07:00 às 20:00
</p>
</div>

</div>

</div>

<!-- Formulário -->

<div class="bg-white rounded-3xl shadow-xl p-10">

<h3 class="text-3xl font-bold text-sky-900">
Envie uma mensagem
</h3>

<form class="mt-8 space-y-6">

<input
type="text"
placeholder="Seu nome"
class="w-full border border-sky-200 rounded-xl p-4 focus:outline-none focus:ring-2 focus:ring-sky-400">

<input
type="email"
placeholder="Seu e-mail"
class="w-full border border-sky-200 rounded-xl p-4 focus:outline-none focus:ring-2 focus:ring-sky-400">

<textarea
rows="6"
placeholder="Digite sua mensagem..."
class="w-full border border-sky-200 rounded-xl p-4 focus:outline-none focus:ring-2 focus:ring-sky-400"></textarea>

<button
class="w-full bg-sky-600 text-white py-4 rounded-xl hover:bg-sky-700 transition duration-300 font-semibold">

Enviar Mensagem

</button>

</form>

</div>

</div>

</div>

</section>

<!-- ================================================= -->
<!-- NEWSLETTER -->
<!-- ================================================= -->

<section
class="py-20 px-6 bg-sky-700 text-white">

<div class="max-w-5xl mx-auto text-center">

<h2 class="text-4xl font-bold">

Receba nossas novidades

</h2>

<p class="mt-6 text-lg">

Cadastre seu e-mail e fique por dentro de novos cafés,
promoções e eventos.

</p>

<div class="mt-10 flex flex-col md:flex-row gap-5 justify-center">

<input
type="email"
placeholder="Digite seu e-mail"
class="bg-white text-slate-700 rounded-xl px-5 py-4 w-full md:w-96">

<button
class="bg-sky-900 px-8 py-4 rounded-xl hover:bg-sky-950 transition">

Cadastrar

</button>

</div>

</div>

</section>

<!-- ================================================= -->
<!-- RODAPÉ -->
<!-- ================================================= -->

<footer
class="bg-slate-900 text-white py-16 px-6">

<div class="max-w-7xl mx-auto">

<div class="grid md:grid-cols-3 gap-10">

<div>

<h2 class="text-3xl font-bold">
Café Sereno
</h2>

<p class="mt-6 leading-8 text-slate-300">

Muito mais do que uma cafeteria.
Um ambiente criado para transformar
cada pausa em um momento especial.

</p>

</div>

<div>

<h3 class="text-2xl font-semibold">

Links

</h3>

<ul class="mt-6 space-y-4">

<li><a href="#inicio" class="hover:text-sky-300">Início</a></li>

<li><a href="#sobre" class="hover:text-sky-300">Sobre</a></li>

<li><a href="#menu" class="hover:text-sky-300">Cardápio</a></li>

<li><a href="#galeria" class="hover:text-sky-300">Galeria</a></li>

<li><a href="#contato" class="hover:text-sky-300">Contato</a></li>

</ul>

</div>

<div>

<h3 class="text-2xl font-semibold">

Redes Sociais

</h3>

<div class="mt-6 flex gap-5">

<a
href="#"
class="bg-sky-700 px-5 py-3 rounded-xl hover:bg-sky-600 transition">

Instagram

</a>

<a
href="#"
class="bg-sky-700 px-5 py-3 rounded-xl hover:bg-sky-600 transition">

Facebook

</a>

<a
href="#"
class="bg-sky-700 px-5 py-3 rounded-xl hover:bg-sky-600 transition">

TikTok

</a>

</div>

</div>

</div>

<hr class="my-10 border-slate-700">

<div class="text-center text-slate-400">

© 2026 Café Sereno. Todos os direitos reservados.

</div>

</div>

</footer>

<!-- ================================================= -->
<!-- ÁREA RESERVADA PARA NOVAS SEÇÕES -->
<!--

Você pode copiar este modelo para adicionar:

- FAQ
- Equipe
- Blog
- Eventos
- Promoções
- Localização (Google Maps)
- Parceiros
- Produtos
- História
- Loja Online

Todas seguirão o mesmo padrão de responsividade.

===================================================== -->

</body>
</html>
