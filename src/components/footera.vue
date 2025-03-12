<template>
    <footer class="bg-gray-900 text-white py-10">
        <div class="container mx-auto px-6">
            <div class="grid grid-cols-1 md:grid-cols-3 gap-8">
                <!-- Section 1 : À propos -->
                <div>
                    <h2 class="text-xl font-bold mb-3">SkyLet Library</h2>
                    <p class="text-gray-400">
                        Découvrez des milliers de livres en ligne. Lisez partout, à tout moment.
                    </p>
                </div>
    
                <!-- Section 2 : Liens rapides -->
                <div>
                    <h3 class="text-lg font-semibold mb-3">Liens utiles</h3>
                    <ul class="space-y-2">
                        <li><a href="#" class="text-gray-400 hover:text-white">Accueil</a></li>
                        <li><a href="#" class="text-gray-400 hover:text-white">Catalogue</a></li>
                        <li><a href="#" class="text-gray-400 hover:text-white" onclick="showModal('aboutModal')">About</a></li>
                        <li><a href="#" class="text-gray-400 hover:text-white" onclick="showModal('contactModal')">Contact</a></li>
                    </ul>
                </div>
    
                <!-- Section 3 : Réseaux sociaux
                <div>
                    <h3 class="text-lg font-semibold mb-3">Suivez-nous</h3>
                    <div class="flex space-x-4">
                        <a href="#" class="text-gray-400 hover:text-white text-2xl">
                            <i class="fa-brands fa-facebook"></i>
                        </a>
                        <a href="#" class="text-gray-400 hover:text-white text-2xl">
                            <i class="fa-brands fa-x-twitter"></i>
                        </a>
                        <a href="#" class="text-gray-400 hover:text-white text-2xl">
                            <i class="fa-brands fa-instagram"></i>
                        </a>
                        <a href="#" class="text-gray-400 hover:text-white text-2xl">
                            <i class="fa-brands fa-linkedin"></i>
                        </a>
                    </div>
                </div> -->
            </div>
    
            <!-- Ligne de séparation -->
            <hr class="my-6 border-gray-700">
    
            <!-- Copyright -->
            <p class="text-center text-gray-500">&copy; 2025 SkyLet Library. Tous droits réservés.</p>
        </div>
    </footer>
</template>