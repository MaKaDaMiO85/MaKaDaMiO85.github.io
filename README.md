
<!DOCTYPE html>
<html lang="es">
  <head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Tarjeta de Negocio Virtual</title>
<script src="https://cdn.tailwindcss.com"></script>
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta3/css/all.min.css">
<link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;600;700&display=swap" rel="stylesheet">
<style>
body {
font-family: 'Inter', sans-serif;
background-color: #f0f2f5; /* Un gris claro para el fondo general /
display: flex;
justify-content: center;
align-items: center;
min-height: 100vh;
padding: 1rem; / Espaciado general para móviles /
}
/ Estilos personalizados para el botón de copiar /
.copy-button {
transition: background-color 0.3s ease, transform 0.1s ease;
}
        .copy-button:active {
            transform: scale(0.98);
        }
        .copy-button.copied {
            background-color: #28a745; /* Verde para indicar copiado */
        }
        /* Estilos para que los botones sobresalgan */
        .animated-link {
            transition: transform 0.2s ease, box-shadow 0.2s ease;
        }
        .animated-link:hover, .animated-link:focus {
            transform: scale(1.05);
            z-index: 10; /* Asegura que el botón se superponga a otros elementos */
            box-shadow: 0 10px 15px -3px rgba(0, 0, 0, 0.1), 0 4px 6px -2px rgba(0, 0, 0, 0.05);
        }
    </style>
</head>
<body class="antialiased">

    <div class="max-w-md w-full bg-white rounded-xl shadow-2xl overflow-hidden md:max-w-xl">
        <div class="md:flex">
            <div class="w-full p-6">
                <div class="flex flex-col items-center">
                
 <img style="    width: 290px;" src="https://www.geasesores.com/assets/admin/media/logos/logo.png" alt="GEA" width="200" data-retina="https://www.geasesores.com/assets/admin/media/logos/logo.png" data-width="290" data-height="48">                  
                         

                    <h1 class="text-2xl font-bold text-gray-500 mb-1 text- center">GEA ASESORES</h1>
                    <p class="text-xl text-indigo-600 font-semibold mb-3 text-center">Agencia de Consultoria Tecnica Especializada</p>

                    <p class="text-lg text-gray-700 mb-4 text-center">
                        <i class="fas fa-building text-gray-500 mr-2"></i>Tu Empresa es nuestra Prioridad
                    </p>
                    <p class="text-md text-gray-600 italic mb-6 text-center">
                        "Conoce nuestro Catalogo de Servicios, dale click"
                        
                        </p>
                </div>
                 <div class="grid grid-cols-2 gap-4 mb-6 relative">
                    <a href="#" class="animated-link flex items-center justify-center p-3 bg-red-500 text-white rounded-lg shadow-md hover:bg-red-600 transition-colors duration-300">
                        <i class="fas fa-link mr-5"></i> Consultoria
                    </a>
                    <a href="#" class="animated-link flex items-center justify-center p-3 bg-indigo-500 text-white rounded-lg shadow-md hover:bg-indigo-600 transition-colors duration-300">
                        <i class="fas fa-link mr-2"></i> Gestion Ambiental
                    </a>
                    <a href="#" class="animated-link flex items-center justify-center p-3 bg-gray-500 text-white rounded-lg shadow-md hover:bg-gray-600 transition-colors duration-300">
                        <i class="fas fa-link mr-2"></i> Proteccion Civil
                    </a>
                    <a href="#" class="animated-link flex items-center justify-center p-3 bg-pink-500 text-white rounded-lg shadow-md hover:bg-pink-600 transition-colors duration-300">
                        <i class="fas fa-link mr-2"></i> Higiene Ocupacional
                    </a>
                    <a href="#" class="animated-link flex items-center justify-center p-3 bg-orange-500 text-white rounded-lg shadow-md hover:bg-orange-600 transition-colors duration-300">
                        <i class="fas fa-link mr-2"></i>
                        Sector 
                        Hidrocarburos
                    </a>
                    <a href="#" class="animated-link flex items-center justify-center p-3 bg-teal-500 text-white rounded-lg shadow-md hover:bg-teal-600 transition-colors duration-300">
                        <i class="fas fa-link mr-2"></i> Juridico
                    </a>
                    <a href="#" class="animated-link flex items-center justify-center p-3 bg-lime-500 text-white rounded-lg shadow-md hover:bg-lime-600 transition-colors duration-300">
                        <i class="fas fa-link mr-2"></i> Estudios Ambientales
                    </a>
                    <a href="#" class="animated-link flex items-center justify-center p-3 bg-cyan-500 text-white rounded-lg shadow-md hover:bg-cyan-600 transition-colors duration-300">
                        <i class="fas fa-link mr-2"></i> Capacitacion de Personal
                    </a>
                    <a href="#" class="animated-link flex items-center justify-center p-3 bg-fuchsia-500 text-white rounded-lg shadow-md hover:bg-fuchsia-600 transition-colors duration-300">
                        <i class="fas fa-link mr-2"></i> Sociedad y Medio Ambiente
                    </a>
                    <a href="#" class="animated-link flex items-center justify-center p-3 bg-rose-500 text-white rounded-lg shadow-md hover:bg-rose-600 transition-colors duration-300">
                        <i class="fas fa-link mr-2"></i> Enlace 10
                    </a>
                </div>
                 <div class="grid grid-cols-0 gap-4 mb-6">
                   <a href="enlace.gea@gmail.com"
                       class="animated-link flex items-center justify-center p-3 bg-blue-500 text-white rounded-lg shadow-md hover:bg-blue-600 transition-colors duration-300">
                        <i class="fas fa-envelope mr-2"></i> Email
                    </a>
                    <a href="tel:+523331908298"
                       class="animated-link flex items-center justify-center p-3 bg-green-500 text-white rounded-lg shadow-md hover:bg-green-600 transition-colors duration-300">
<i class="fas fa-phone mr-2"></i> Llamar
                    </a>
                    <a href="https://wa.me/+523331908298"
                       class="animated-link flex items-center justify-center p-3 bg-teal-500 text-white rounded-lg shadow-md hover:bg-teal-600 transition-colors duration-300">
                        <i class="fab fa-whatsapp mr-2"></i> WhatsApp
                    </a>
                    <a href="https://www.linkedin.com/company/gea-gestion-tecnica-ambiental/" target="_blank" rel="noopener noreferrer"
                       class="animated-link flex items-center justify-center p-3 bg-blue-700 text-white rounded-lg shadow-md hover:bg-blue-800 transition-colors duration-300">
                        <i class="fab fa-linkedin mr-2"></i> LinkedIn
                    </a>
                </div>
                <button id="shareButton"
                        class="copy-button w-full flex items-center justify-center p-3 bg-gray-700 text-white font-bold rounded-lg shadow-md hover:bg-gray-800 transition-colors duration-300 focus:outline-none focus:ring-2 focus:ring-gray-500 focus:ring-opacity-50">
<i class="fas fa-share-alt mr-2"></i> Compartir Tarjeta
                </button>

                <div id="copyMessage" class="mt-4 text-center text-sm text-green-700 font-medium hidden">
                    ¡Enlace copiado al portapapeles!
                </div>
            </div>
        </div>
    </div>

    <script>
        document.addEventListener('DOMContentLoaded', () => {
            const shareButton = document.getElementById('shareButton');
            const copyMessage = document.getElementById('copyMessage');

            shareButton.addEventListener('click', () => {
                const cardUrl = window.location.href;
                const tempInput = document.createElement('textarea');
                tempInput.value = cardUrl;
                document.body.appendChild(tempInput);
                tempInput.select();
                try {
                    document.execCommand('copy');
                    copyMessage.textContent = '¡Enlace copiado al portapapeles!';
                    copyMessage.classList.remove('hidden');
                    shareButton.classList.add('copied');
                    setTimeout(() => {
                        copyMessage.classList.add('hidden');
                        shareButton.classList.remove('copied');
                    }, 3000);
                } catch (err) {
                    console.error('Error al copiar: ', err);
                    copyMessage.textContent = 'Error al copiar el enlace.';
                    copyMessage.classList.remove('hidden');
                    copyMessage.classList.remove('text-green-700');
                    copyMessage.classList.add('text-red-700');
                    setTimeout(() => {
                        copyMessage.classList.add('hidden');
                        copyMessage.classList.add('text-green-700');
                        copyMessage.classList.remove('text-red-700');
                    }, 3000);
                } finally {
                    document.body.removeChild(tempInput);
                }
            });
        });
    </script>
</body>
</html>
         
                        
                 
 
