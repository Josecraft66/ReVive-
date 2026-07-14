<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>ReVive+ - Intercambia, Dona, Vende</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.1/css/all.min.css">
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Poppins:wght@400;500;600;700&display=swap');
        body { font-family: 'Poppins', sans-serif; }
        .hero-bg {
            background: linear-gradient(135deg, #10b981 0%, #047857 100%);
        }
        .product-card {
            transition: all 0.3s cubic-bezier(0.4, 0, 0.2, 1);
        }
        .product-card:hover {
            transform: translateY(-8px);
            box-shadow: 0 20px 25px -5px rgb(0 0 0 / 0.1), 0 8px 10px -6px rgb(0 0 0 / 0.1);
        }
        .nav-link {
            position: relative;
        }
        .nav-link:after {
            content: '';
            position: absolute;
            width: 0;
            height: 2px;
            bottom: -2px;
            left: 0;
            background-color: #10b981;
            transition: width 0.3s;
        }
        .nav-link:hover:after {
            width: 100%;
        }
        .feed-item {
            scroll-snap-align: start;
        }
    </style>
</head>
<body class="bg-gray-50 text-gray-900">
    <!-- Navbar -->
    <nav class="bg-white shadow-md sticky top-0 z-50">
        <div class="max-w-7xl mx-auto px-4">
            <div class="flex items-center justify-between h-16">
                <!-- Logo -->
                <div class="flex items-center space-x-3">
                    <div class="w-10 h-10 bg-emerald-600 rounded-2xl flex items-center justify-center text-white font-bold text-2xl">R+</div>
                    <div>
                        <span class="text-3xl font-bold tracking-tight">
                            <span class="text-emerald-600">Re</span><span class="text-gray-800">Vive</span><span class="text-emerald-500">+</span>
                        </span>
                    </div>
                </div>

                <!-- Search -->
                <div class="flex-1 max-w-xl mx-8">
                    <div class="relative">
                        <input id="searchInput" 
                               type="text" 
                               placeholder="Buscar bicicletas, celulares, muebles..." 
                               class="w-full bg-gray-100 border border-gray-200 focus:border-emerald-500 focus:bg-white pl-12 py-3 rounded-3xl text-sm outline-none transition-all">
                        <i class="fas fa-search absolute left-5 top-3.5 text-gray-400"></i>
                    </div>
                </div>

                <!-- Nav Links -->
                <div class="flex items-center space-x-8 text-sm font-medium">
                    <a href="#" onclick="showSection('feed')" class="nav-link text-gray-700 hover:text-emerald-600 flex items-center gap-1">
                        <i class="fas fa-home"></i> Inicio
                    </a>
                    <a href="#" onclick="showSection('market')" class="nav-link text-gray-700 hover:text-emerald-600 flex items-center gap-1">
                        <i class="fas fa-exchange-alt"></i> Mercado
                    </a>
                    <a href="#" onclick="showSection('donate')" class="nav-link text-gray-700 hover:text-emerald-600 flex items-center gap-1">
                        <i class="fas fa-heart"></i> Dona
                    </a>
                    <a href="#" onclick="showSection('profile')" class="nav-link text-gray-700 hover:text-emerald-600 flex items-center gap-1">
                        <i class="fas fa-user"></i> Perfil
                    </a>
                </div>

                <div class="flex items-center gap-4">
                    <button onclick="toggleLoginModal()" 
                            class="px-5 py-2 text-sm font-semibold text-emerald-700 hover:bg-emerald-50 rounded-3xl transition-colors flex items-center gap-2">
                        <i class="fas fa-sign-in-alt"></i>
                        Iniciar Sesión
                    </button>
                    <button onclick="uploadItem()" 
                            class="bg-emerald-600 hover:bg-emerald-700 text-white px-6 py-2.5 rounded-3xl text-sm font-semibold flex items-center gap-2 shadow-lg shadow-emerald-200 transition-all active:scale-95">
                        <i class="fas fa-plus"></i> Publicar
                    </button>
                </div>
            </div>
        </div>

        <!-- Category Bar -->
        <div class="bg-white border-t">
            <div class="max-w-7xl mx-auto px-4 py-3 flex gap-8 text-sm overflow-x-auto whitespace-nowrap">
                <a href="#" onclick="filterCategory('all')" class="category-tab active font-medium text-emerald-600">Todos</a>
                <a href="#" onclick="filterCategory('electronics')" class="category-tab hover:text-emerald-600">Electrónicos</a>
                <a href="#" onclick="filterCategory('clothing')" class="category-tab hover:text-emerald-600">Ropa</a>
                <a href="#" onclick="filterCategory('furniture')" class="category-tab hover:text-emerald-600">Muebles</a>
                <a href="#" onclick="filterCategory('vehicles')" class="category-tab hover:text-emerald-600">Vehículos</a>
                <a href="#" onclick="filterCategory('books')" class="category-tab hover:text-emerald-600">Libros</a>
                <a href="#" onclick="filterCategory('tools')" class="category-tab hover:text-emerald-600">Herramientas</a>
            </div>
        </div>
    </nav>

    <!-- HERO -->
    <header id="hero" class="hero-bg text-white py-20">
        <div class="max-w-6xl mx-auto px-6 grid md:grid-cols-2 gap-12 items-center">
            <div>
                <div class="inline-flex items-center gap-2 bg-white/20 backdrop-blur-md px-5 py-2 rounded-3xl mb-6">
                    <span class="text-xs tracking-widest font-mono">ECONOMÍA CIRCULAR</span>
                </div>
                <h1 class="text-6xl md:text-7xl font-bold leading-none mb-6">
                    Lo que ya no necesitas<br>
                    <span class="text-emerald-200">puede cambiar</span> la vida<br>de alguien más.
                </h1>
                <p class="text-xl text-emerald-100 max-w-md mb-10">Intercambia, dona o vende con diferencia. Reutilizamos juntos.</p>
                
                <div class="flex items-center gap-4">
                    <button onclick="showSection('market')" 
                            class="bg-white text-emerald-700 hover:bg-emerald-50 px-8 py-4 rounded-3xl font-semibold text-lg shadow-xl shadow-emerald-900/30 flex items-center gap-3">
                        Explorar ahora <i class="fas fa-arrow-right"></i>
                    </button>
                    <button onclick="uploadItem()" 
                            class="border-2 border-white/80 hover:bg-white/10 px-8 py-4 rounded-3xl font-semibold text-lg transition-all">
                        Publicar artículo
                    </button>
                </div>
            </div>
            
            <div class="hidden md:flex justify-center">
                <img id="logo-preview" src="/home/workdir/attachments/image.png" alt="ReVive+ Logo" class="w-96 drop-shadow-2xl">
            </div>
        </div>
    </header>

    <!-- Main Content Container -->
    <main class="max-w-7xl mx-auto px-6 py-8">
        
        <!-- FEED SECTION -->
        <section id="feed-section" class="mb-16">
            <div class="flex justify-between items-end mb-8">
                <h2 class="text-3xl font-semibold">Lo más reciente para ti</h2>
                <div class="flex items-center text-sm text-gray-500">
                    Basado en tus preferencias <span class="ml-2 px-3 py-1 bg-emerald-100 text-emerald-700 rounded-full text-xs font-medium">IA Recomendaciones</span>
                </div>
            </div>
            
            <div id="feed-grid" class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 xl:grid-cols-4 gap-6">
                <!-- Populated by JS -->
            </div>
        </section>

        <!-- MARKETPLACE SECTION -->
        <section id="market-section" class="hidden">
            <div class="flex justify-between items-center mb-6">
                <h2 class="text-3xl font-semibold flex items-center gap-3">
                    <i class="fas fa-store"></i> Mercado ReVive+
                </h2>
                <div class="flex gap-3">
                    <select id="sortSelect" onchange="sortProducts()" class="bg-white border border-gray-200 rounded-2xl px-5 py-2.5 text-sm">
                        <option value="new">Más recientes</option>
                        <option value="price-low">Precio: bajo a alto</option>
                        <option value="price-high">Precio: alto a bajo</option>
                    </select>
                </div>
            </div>
            
            <div id="market-grid" class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 xl:grid-cols-4 gap-6">
                <!-- Populated by JS -->
            </div>
        </section>

        <!-- PROFILE SECTION -->
        <section id="profile-section" class="hidden">
            <div class="max-w-4xl mx-auto bg-white rounded-3xl shadow p-8">
                <div class="flex flex-col md:flex-row gap-10">
                    <!-- Avatar -->
                    <div class="flex-shrink-0 text-center">
                        <div id="user-avatar" class="w-32 h-32 mx-auto rounded-3xl bg-gradient-to-br from-emerald-400 to-teal-600 flex items-center justify-center text-6xl text-white shadow-inner overflow-hidden">
                            👤
                        </div>
                        <button onclick="editProfile()" class="mt-4 text-xs text-emerald-600 hover:underline">Editar foto</button>
                    </div>
                    
                    <div class="flex-1">
                        <h1 id="profile-name" class="text-4xl font-semibold mb-1">Juan Pérez</h1>
                        <p id="profile-email" class="text-emerald-600 mb-6">juan@email.com</p>
                        
                        <div class="grid grid-cols-3 gap-4 mb-10">
                            <div class="bg-gray-50 rounded-2xl p-5 text-center">
                                <div class="text-3xl font-semibold text-emerald-600">24</div>
                                <div class="text-xs tracking-widest text-gray-500 mt-1">INTERCAMBIOS</div>
                            </div>
                            <div class="bg-gray-50 rounded-2xl p-5 text-center">
                                <div class="text-3xl font-semibold text-emerald-600">4.9</div>
                                <div class="text-xs tracking-widest text-gray-500 mt-1">CALIFICACIÓN</div>
                            </div>
                            <div class="bg-gray-50 rounded-2xl p-5 text-center">
                                <div class="text-3xl font-semibold text-emerald-600">12</div>
                                <div class="text-xs tracking-widest text-gray-500 mt-1">DONACIONES</div>
                            </div>
                        </div>
                        
                        <div class="border-t pt-8">
                            <h3 class="font-medium mb-5 flex items-center gap-2"><i class="fas fa-history"></i> Historial reciente</h3>
                            <div class="space-y-4 text-sm" id="history-list">
                                <!-- JS populated -->
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </section>

    </main>

    <!-- PRODUCT MODAL -->
    <div id="product-modal" class="hidden fixed inset-0 bg-black/70 flex items-center justify-center z-[100]">
        <div class="bg-white rounded-3xl max-w-2xl w-full max-h-[90vh] overflow-hidden">
            <div class="p-6 border-b flex justify-between items-center">
                <h3 id="modal-title" class="font-semibold text-2xl"></h3>
                <button onclick="closeModal()" class="text-3xl text-gray-400 hover:text-gray-600">×</button>
            </div>
            
            <div class="p-6 overflow-auto" style="max-height: calc(90vh - 120px)">
                <img id="modal-image" class="w-full h-80 object-cover rounded-2xl mb-6" alt="">
                
                <div class="flex gap-6">
                    <div class="flex-1">
                        <div class="flex items-center justify-between">
                            <div id="modal-price" class="text-4xl font-bold text-emerald-600"></div>
                            <div id="modal-type" class="px-5 py-1 bg-emerald-100 text-emerald-700 rounded-3xl text-xs font-semibold"></div>
                        </div>
                        
                        <p id="modal-description" class="mt-6 text-gray-600 leading-relaxed"></p>
                    </div>
                    
                    <div class="w-64 border-l pl-6">
                        <div onclick="startTransaction()" class="cursor-pointer bg-emerald-600 text-white rounded-3xl py-4 px-6 text-center font-semibold hover:bg-emerald-700 transition-all mb-4">
                            <span id="action-btn-text">Intercambiar / Comprar</span>
                        </div>
                        
                        <div class="text-xs text-gray-500 space-y-4">
                            <div class="flex justify-between"><span>Estado</span><span class="font-medium text-emerald-600">Nuevo / Como nuevo</span></div>
                            <div class="flex justify-between"><span>Publicada hace</span><span>2 días</span></div>
                            <div class="flex justify-between"><span>Ubicación</span><span>CDMX</span></div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </div>

    <!-- LOGIN MODAL -->
    <div id="login-modal" class="hidden fixed inset-0 bg-black/60 flex items-center justify-center z-[200]">
        <div class="bg-white rounded-3xl w-full max-w-md p-8">
            <div class="text-center mb-8">
                <div class="inline-flex w-16 h-16 bg-emerald-100 rounded-2xl items-center justify-center text-4xl mb-4">🌱</div>
                <h2 class="text-3xl font-semibold">Bienvenido a ReVive+</h2>
                <p class="text-gray-500 mt-2">Inicia sesión para continuar</p>
            </div>
            
            <div class="space-y-6">
                <div>
                    <label class="block text-xs font-medium mb-2 text-gray-500">CORREO ELECTRÓNICO</label>
                    <input id="login-email" type="email" value="juan@email.com" 
                           class="w-full px-5 py-4 bg-gray-50 border border-transparent focus:border-emerald-400 rounded-3xl outline-none">
                </div>
                <div>
                    <label class="block text-xs font-medium mb-2 text-gray-500">CONTRASEÑA</label>
                    <input id="login-pass" type="password" value="demo123" 
                           class="w-full px-5 py-4 bg-gray-50 border border-transparent focus:border-emerald-400 rounded-3xl outline-none">
                </div>
                
                <button onclick="performLogin()" 
                        class="w-full py-4 bg-emerald-600 hover:bg-emerald-700 text-white font-semibold rounded-3xl text-lg transition-all">
                    Iniciar Sesión
                </button>
                
                <div class="text-center text-sm">
                    <a href="#" class="text-emerald-600 hover:underline">¿Olvidaste tu contraseña?</a>
                </div>
                
                <div onclick="registerDemo()" class="text-center text-sm text-gray-500 hover:text-gray-700 cursor-pointer">
                    ¿No tienes cuenta? <span class="text-emerald-600 font-medium">Regístrate gratis</span>
                </div>
            </div>
            
            <button onclick="toggleLoginModal()" class="absolute top-6 right-6 text-gray-400">✕</button>
        </div>
    </div>

    <!-- UPLOAD ITEM MODAL -->
    <div id="upload-modal" class="hidden fixed inset-0 bg-black/70 flex items-center justify-center z-[150]">
        <div class="bg-white rounded-3xl w-full max-w-lg p-8">
            <h2 class="text-2xl font-semibold mb-6">Publica tu artículo</h2>
            
            <form id="uploadForm" onsubmit="submitUpload(event)">
                <div class="space-y-5">
                    <div>
                        <label class="block text-sm mb-2">Título</label>
                        <input id="upload-title" type="text" required class="w-full px-4 py-3 border border-gray-200 rounded-2xl" placeholder="Bicicleta Trek">
                    </div>
                    
                    <div class="grid grid-cols-2 gap-5">
                        <div>
                            <label class="block text-sm mb-2">Tipo de publicación</label>
                            <select id="upload-type" class="w-full px-4 py-3 border border-gray-200 rounded-2xl">
                                <option value="exchange">Intercambio</option>
                                <option value="sell">Venta</option>
                                <option value="donate">Donación</option>
                            </select>
                        </div>
                        <div>
                            <label class="block text-sm mb-2">Precio / Diferencia</label>
                            <input id="upload-price" type="number" class="w-full px-4 py-3 border border-gray-200 rounded-2xl" placeholder="800">
                        </div>
                    </div>
                    
                    <div>
                        <label class="block text-sm mb-2">Descripción</label>
                        <textarea id="upload-desc" rows="3" class="w-full px-4 py-3 border border-gray-200 rounded-2xl" placeholder="Excelente estado..."></textarea>
                    </div>
                    
                    <div>
                        <label class="block text-sm mb-2">Categoría</label>
                        <select id="upload-category" class="w-full px-4 py-3 border border-gray-200 rounded-2xl">
                            <option value="vehicles">Vehículos</option>
                            <option value="electronics">Electrónicos</option>
                            <option value="clothing">Ropa</option>
                        </select>
                    </div>
                    
                    <!-- Mock image upload -->
                    <div class="border-2 border-dashed border-gray-300 rounded-3xl p-8 text-center">
                        <i class="fas fa-cloud-upload-alt text-4xl text-gray-300 mb-3"></i>
                        <p class="text-sm text-gray-500">Haz clic para subir foto</p>
                        <input type="file" id="upload-image" accept="image/*" class="hidden">
                    </div>
                </div>
                
                <div class="flex gap-4 mt-8">
                    <button type="button" onclick="closeUploadModal()" 
                            class="flex-1 py-4 border border-gray-300 font-medium rounded-3xl">Cancelar</button>
                    <button type="submit" 
                            class="flex-1 py-4 bg-emerald-600 text-white font-semibold rounded-3xl">Publicar</button>
                </div>
            </form>
        </div>
    </div>

    <footer class="bg-gray-900 text-white py-16 mt-20">
        <div class="max-w-7xl mx-auto px-6 grid grid-cols-2 md:grid-cols-4 gap-12">
            <div>
                <div class="flex items-center gap-3 text-white mb-6">
                    <div class="w-8 h-8 bg-emerald-500 rounded-2xl flex items-center justify-center">R+</div>
                    <span class="text-2xl font-bold">ReVive+</span>
                </div>
                <p class="text-gray-400 text-sm">Reutilizamos el presente para un futuro mejor.</p>
            </div>
            <div>
                <div class="font-medium mb-4">Plataforma</div>
                <ul class="space-y-2 text-sm text-gray-400">
                    <li><a href="#" class="hover:text-white">Cómo funciona</a></li>
                    <li><a href="#" class="hover:text-white">Seguridad</a></li>
                    <li><a href="#" class="hover:text-white">Centro de ayuda</a></li>
                </ul>
            </div>
            <div>
                <div class="font-medium mb-4">Comunidad</div>
                <ul class="space-y-2 text-sm text-gray-400">
                    <li><a href="#" class="hover:text-white">Blog</a></li>
                    <li><a href="#" class="hover:text-white">Historias de impacto</a></li>
                </ul>
            </div>
            <div>
                <div class="font-medium mb-4">Empresa</div>
                <ul class="space-y-2 text-sm text-gray-400">
                    <li><a href="#" class="hover:text-white">Sobre nosotros</a></li>
                    <li><a href="#" class="hover:text-white">Carreras</a></li>
                    <li><a href="#" class="hover:text-white">Contacto</a></li>
                </ul>
            </div>
        </div>
        <div class="text-center text-xs text-gray-500 mt-16">© 2026 ReVive+. Todos los derechos reservados. Hecho con ❤️ para el planeta.</div>
    </footer>

    <script>
        // Mock data
        let products = [
            {
                id: 1,
                title: "Bicicleta de montaña Trek",
                price: 1200,
                type: "exchange",
                category: "vehicles",
                image: "https://picsum.photos/id/1015/600/400",
                desc: "Excelente estado, solo 3 meses de uso. Ideal para ciudad y montaña.",
                location: "CDMX"
            },
            {
                id: 2,
                title: "iPhone 13 Mini 128GB",
                price: 4500,
                type: "sell",
                category: "electronics",
                image: "https://picsum.photos/id/201/600/400",
                desc: "Como nuevo, batería al 95%. Incluye cargador original.",
                location: "Guadalajara"
            },
            {
                id: 3,
                title: "Sofá 3 plazas azul",
                price: 0,
                type: "donate",
                category: "furniture",
                image: "https://picsum.photos/id/251/600/400",
                desc: "En muy buen estado. Lo entrego a quien lo necesite cerca.",
                location: "Monterrey"
            },
            {
                id: 4,
                title: "Libro 'El Poder del Ahora'",
                price: 180,
                type: "exchange",
                category: "books",
                image: "https://picsum.photos/id/24/600/400",
                desc: "Edición de tapa dura. Perfecto estado.",
                location: "CDMX"
            },
            {
                id: 5,
                title: "Camiseta Nike nueva",
                price: 350,
                type: "sell",
                category: "clothing",
                image: "https://picsum.photos/id/64/600/400",
                desc: "Talla M, sin uso.",
                location: "CDMX"
            },
            {
                id: 6,
                title: "Martillo y caja de herramientas",
                price: 0,
                type: "donate",
                category: "tools",
                image: "https://picsum.photos/id/201/600/400",
                desc: "Set completo en buen estado.",
                location: "Monterrey"
            }
        ];

        let currentUser = null;
        let myPublishedProducts = []; // IDs of products published by current user

        function populateFeed() {
            filterCategory('all');  // Use the filtered version
        }

        function populateMarket() {
            const grid = document.getElementById('market-grid');
            grid.innerHTML = '';
            // Reuse feed logic but for market view
            products.forEach(product => {
                const card = document.createElement('div');
                card.className = `product-card bg-white rounded-3xl overflow-hidden shadow-sm cursor-pointer`;
                card.innerHTML = `
                    <div class="relative">
                        <img src="${product.image}" class="w-full h-56 object-cover">
                        <div class="absolute top-4 right-4 px-3 py-1 text-xs font-semibold rounded-3xl ${product.type === 'donate' ? 'bg-green-500 text-white' : product.type === 'sell' ? 'bg-amber-500 text-white' : 'bg-teal-500 text-white'}">
                            ${product.type === 'donate' ? 'DONACIÓN' : product.type === 'sell' ? 'VENTA' : 'TRUEQUE'}
                        </div>
                    </div>
                    <div class="p-5">
                        <div class="font-semibold text-lg leading-tight mb-1">${product.title}</div>
                        <div class="flex justify-between items-end">
                            <div>
                                ${product.price > 0 ? `<span class="text-2xl font-bold text-emerald-600">$${product.price}</span>` : '<span class="text-emerald-600 font-medium">GRATIS</span>'}
                            </div>
                            <div onclick="event.stopImmediatePropagation(); viewProduct(${product.id})" class="text-xs bg-gray-100 hover:bg-emerald-100 px-5 py-2 rounded-3xl transition-colors">Ver</div>
                        </div>
                    </div>
                `;
                card.onclick = () => viewProduct(product.id);
                grid.appendChild(card);
            });
        }

        function viewProduct(id) {
            const product = products.find(p => p.id === id);
            if (!product) return;
            
            document.getElementById('modal-title').textContent = product.title;
            document.getElementById('modal-image').src = product.image;
            document.getElementById('modal-price').innerHTML = product.price > 0 ? `$${product.price}` : 'GRATIS';
            document.getElementById('modal-description').textContent = product.desc;
            document.getElementById('modal-type').textContent = product.type === 'donate' ? 'DONACIÓN' : product.type === 'sell' ? 'VENTA' : 'INTERCAMBIO';
            
            document.getElementById('product-modal').classList.remove('hidden');
            document.getElementById('product-modal').classList.add('flex');
        }

        function closeModal() {
            const modal = document.getElementById('product-modal');
            modal.classList.add('hidden');
            modal.classList.remove('flex');
        }

        function startTransaction() {
            closeModal();
            if (!currentUser) {
                const proceed = confirm("Para completar la transacción es necesario iniciar sesión.\n\n¿Quieres iniciar sesión ahora? (Presiona Cancelar para seguir navegando)");
                if (proceed) {
                    toggleLoginModal();
                }
                return;
            }
            
            alert("✅ Transacción iniciada.\n\nSe ha enviado un correo de confirmación a tu cuenta.\n\nA continuación se abrirá la cámara para subir identificación.");
            // Simulate ID upload and signature
            setTimeout(() => {
                alert("📸 Cámara abierta (simulada). Sube tu credencial.");
                setTimeout(() => {
                    alert("✍️ Por favor firma digitalmente para confirmar.");
                    alert("🎉 ¡Intercambio confirmado! Revisa tu historial.");
                }, 1200);
            }, 800);
        }

        function toggleLoginModal() {
            const modal = document.getElementById('login-modal');
            modal.classList.toggle('hidden');
        }

        function performLogin() {
            currentUser = {
                name: "Juan Pérez",
                email: document.getElementById('login-email').value || "juan@email.com",
                avatar: "👤"
            };
            document.getElementById('profile-name').textContent = currentUser.name;
            document.getElementById('profile-email').textContent = currentUser.email;
            toggleLoginModal();
            alert("Sesión iniciada correctamente ✅");
            showSection('profile');
        }

        function registerDemo() {
            alert("Registro simulado completado. ¡Bienvenido a ReVive+!");
            toggleLoginModal();
        }

        function uploadItem() {
            if (!currentUser) {
                const proceed = confirm("Para publicar artículos necesitas iniciar sesión.\n\n¿Quieres iniciar sesión ahora? (Presiona Cancelar para seguir navegando)");
                if (proceed) {
                    toggleLoginModal();
                }
                return;
            }
            document.getElementById('upload-modal').classList.remove('hidden');
            document.getElementById('upload-modal').classList.add('flex');
        }

        function closeUploadModal() {
            document.getElementById('upload-modal').classList.add('hidden');
            document.getElementById('upload-modal').classList.remove('flex');
        }

        function submitUpload(e) {
            e.preventDefault();
            const title = document.getElementById('upload-title').value;
            if (title) {
                alert(`✅ Artículo "${title}" publicado con éxito!`);
                closeUploadModal();
                // Add to products
                products.unshift({
                    id: Date.now(),
                    title: title,
                    price: parseInt(document.getElementById('upload-price').value) || 0,
                    type: document.getElementById('upload-type').value,
                    category: document.getElementById('upload-category').value,
                    image: "https://picsum.photos/id/870/600/400",
                    desc: document.getElementById('upload-desc').value || "Nuevo artículo en ReVive+",
                    location: "CDMX"
                });
                populateFeed();
            }
        }

        function showSection(section) {
            // Hide all
            document.getElementById('feed-section').classList.add('hidden');
            document.getElementById('market-section').classList.add('hidden');
            document.getElementById('profile-section').classList.add('hidden');
            
            if (section === 'feed') {
                document.getElementById('feed-section').classList.remove('hidden');
            } else if (section === 'market') {
                document.getElementById('market-section').classList.remove('hidden');
                populateMarket();
            } else if (section === 'profile') {
                document.getElementById('profile-section').classList.remove('hidden');
            } else if (section === 'donate') {
                alert("Sección de donaciones. Filtrando publicaciones gratuitas...");
                showSection('market');
            }
        }

        function filterCategory(cat) {
            document.querySelectorAll('.category-tab').forEach(tab => {
                tab.classList.remove('active', 'text-emerald-600', 'font-medium');
                if ((cat === 'all' && tab.textContent === 'Todos') || tab.getAttribute('onclick').includes(cat)) {
                    tab.classList.add('active', 'text-emerald-600', 'font-medium');
                }
            });
            
            const grid = document.getElementById('feed-grid');
            grid.innerHTML = '';
            
            const filtered = cat === 'all' ? products : products.filter(p => p.category === cat);
            
            if (filtered.length === 0) {
                grid.innerHTML = `<div class="col-span-full text-center py-12 text-gray-500">No hay productos en esta categoría aún. ¡Sé el primero en publicar!</div>`;
                return;
            }
            
            filtered.forEach(product => {
                const card = document.createElement('div');
                card.className = `product-card bg-white rounded-3xl overflow-hidden shadow-sm cursor-pointer`;
                card.innerHTML = `
                    <div class="relative">
                        <img src="${product.image}" class="w-full h-56 object-cover">
                        <div class="absolute top-4 right-4 px-3 py-1 text-xs font-semibold rounded-3xl ${product.type === 'donate' ? 'bg-green-500 text-white' : product.type === 'sell' ? 'bg-amber-500 text-white' : 'bg-teal-500 text-white'}">
                            ${product.type === 'donate' ? 'DONACIÓN' : product.type === 'sell' ? 'VENTA' : 'TRUEQUE'}
                        </div>
                    </div>
                    <div class="p-5">
                        <div class="font-semibold text-lg leading-tight mb-1">${product.title}</div>
                        <div class="flex justify-between items-end">
                            <div>
                                ${product.price > 0 ? `<span class="text-2xl font-bold text-emerald-600">$${product.price}</span>` : '<span class="text-emerald-600 font-medium">GRATIS</span>'}
                            </div>
                            <div onclick="event.stopImmediatePropagation(); viewProduct(${product.id})" class="text-xs bg-gray-100 hover:bg-emerald-100 px-5 py-2 rounded-3xl transition-colors">Ver</div>
                        </div>
                    </div>
                `;
                card.onclick = () => viewProduct(product.id);
                grid.appendChild(card);
            });
        }

        function sortProducts() {
            // Demo
            populateFeed();
        }

        function editProfile() {
            alert("📸 Sube una nueva foto de perfil (simulado)");
        }

        // Keyboard shortcuts & init
        function init() {
            populateFeed();
            showSection('feed');
            
            // Tailwind script already loaded
            console.log('%cReVive+ Prototype listo 🚀', 'color:#10b981; font-size:13px; font-family:monospace');
            
            // Fake preferences notification
            setTimeout(() => {
                if (Math.random() > 0.7) {
                    console.log("IA: Recomendando bicicletas cerca de ti");
                }
            }, 4500);
        }

        window.onload = init;
    </script>
</body>
</html>
