<script setup>

</script>

<template>
  <header id="NavMenu" class="transform translate-y-1/2 flex flex-col md:flex-row justify-between items-center w-full h-auto p-4 bg-transparent border border-[#14ff72cb] border-[2px] rounded-lg backdrop-blur-md">
        <div class="flex items-center gap-2 mb-4 md:mb-0">
            <img src="/src/assets/img/logo.png" alt="Logo" class="w-[50px] h-[50px]">
            <p class="font-bold text-[20px]">SkyLet Library</p>
        </div>
        <div class="flex items-center justify-end w-full md:w-auto">
            <div class="relative">
                <button id="menu-toggle" class="md:hidden bg-gray-500 text-white p-2 rounded">
                    <i id="menu-icon" class="fas fa-bars"></i>
                </button>
                <nav id="nav-menu"class="hidden md:flex flex-col md:flex-row gap-4 absolute md:static bg-transparent md:bg-transparent shadow-md md:shadow-none right-0">
                    <a href="#"class="active">Home</a>
                    <a href="#" onclick="showModal('aboutModal')">About</a>
                    <a href="#" onclick="showModal('services')">Services</a>
                    <a href="#" onclick="showModal('contactModal')">Contact</a>
                </nav>
            </div>
            <div class="relative ml-4">
                <button id="search-toggle" class="bg-gray-500 text-white p-2 rounded">
                    <i class="fa-solid fa-magnifying-glass"></i>
                </button>
                <div id="search-bar" class="hidden absolute right-0 bg-gray-500 p-2 rounded-full">
                    <input 
                        type="text" 
                        class="border-none outline-none p-1 bg-transparent text-white text-base" 
                        placeholder="Rechercher..."
                    >
                </div>
            </div>
        </div>        
    </header>
    
    <div id="content" class="slider">
        <div class="list">
            <div class="item">
                <img src="/src/assets/img/img1.jpg" alt="">
                <div class="content">
                    <div class="title">Bibliothèque Virtuelle</div>
                    <div class="type">Littérature Classique</div>
                    <div class="description">
                        Plongez dans les chefs-d'œuvre intemporels de la littérature. Redécouvrez les romans qui ont marqué l’histoire et laissez-vous transporter par des récits fascinants.
                    </div>
                    <div class="button text-black">
                        <button><a href="#books-section">Voir Plus</a></button>
                    </div>
                </div>
            </div>

            <div class="item">
                <img src="/src/assets/img/img2.jpg" alt="">
                <div class="content">
                    <div class="title">Bibliothèque Virtuelle</div>
                    <div class="type">Science-Fiction & Fantasy</div>
                    <div class="description">
                        Partez à l’aventure dans des mondes extraordinaires où l'imaginaire devient réalité. Découvrez des histoires captivantes mêlant magie, technologies avancées et quêtes épiques.
                    </div>
                    <div class="button text-black">
                        <button><a href="#books-section">Voir Plus</a></button>
                    </div>
                </div>
            </div>

            <div class="item">
                <img src="/src/assets/img/img4.jpg" alt="">
                <div class="content">
                    <div class="title">Bibliothèque Virtuelle</div>
                    <div class="type">Développement Personnel</div>
                    <div class="description">
                        Découvrez des ouvrages inspirants qui vous aideront à évoluer, à acquérir de nouvelles compétences et à améliorer votre quotidien.
                    </div>
                    <div class="button text-black">
                        <button><a href="#books-section">Voir Plus</a></button>
                    </div>
                </div>
            </div>

            <div class="item">
                <img src="/src/assets/img/img3.jpg" alt="">
                <div class="content">
                    <div class="title">Bibliothèque Virtuelle</div>
                    <div class="type">Histoire & Biographies</div>
                    <div class="description">
                        Revivez les grands événements de l’histoire et plongez dans la vie de figures emblématiques à travers des récits captivants et inspirants.
                    </div>
                    <div class="button text-black">
                        <button><a href="#books-section">Voir Plus</a></button>
                    </div>
                </div>
            </div>
        </div>

        <div class="thumbnail">
            <div class="item">
                <img src="/src/assets/img/img1.jpg" alt="">
            </div>
            <div class="item">
                <img src="/src/assets/img/img2.jpg" alt="">
            </div>
            <div class="item">
                <img src="/src/assets/img/img4.jpg" alt="">
            </div>
            <div class="item">
                <img src="/src/assets/img/img3.jpg" alt="">
            </div>
        </div>

        <div class="nextPrevArrows">
            <button class="prev"> < </button>
            <button class="next"> > </button>
        </div>
    </div>

</template>


