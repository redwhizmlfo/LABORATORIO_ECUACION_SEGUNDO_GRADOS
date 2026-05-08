# Laboratorio: Ecuación de Segundo Grado con Git y GitHub

## Objetivo
Aplicar técnicas de versionamiento de código con Git y GitHub en un programa Java que resuelve la ecuación de segundo grado.

## Herramientas utilizadas
- Java
- Visual Studio Code
- Git
- GitHub

## Escenarios de trabajo
1. Trabajo solo en main
2. Trabajo con main y rama adicional

## Estructura general
- 01_documentacion
- 02_evidencias
- 03_escenario_main
- 04_escenario_ramas

## Ejecución
Compilar y ejecutar el archivo Main.java desde la terminal de VS Code.



-------------------------------------------------------------------------------------------------------------------------------------------------------------------
PROMPT — LANDING PAGE “BOUTIQUE PREMIUM” ULTRA MODERNA
Diseña una landing page cinematográfica, ultra premium, minimalista y futurista para una boutique de moda exclusiva.
La estética debe combinar el nivel visual de Apple, Jacquemus, Balenciaga y tiendas luxury fashion editoriales.
El diseño debe sentirse extremadamente elegante, aspiracional y moderno, con composición visual impecable, microinteracciones suaves y experiencia inmersiva.
DIRECCIÓN VISUAL GLOBAL


Estilo: luxury minimal + fashion editorial + high-end ecommerce


Apariencia ultra limpia, sofisticada y premium


Mucho espacio negativo


Tipografía gigante y elegante


Animaciones fluidas tipo Apple


Scroll cinematográfico


Transiciones suaves y modernas


Iluminación premium


Efectos glassmorphism sutiles


Blur elegante


Sombras suaves


UI extremadamente refinada


Responsive perfecto


Diseño pensado para convertir visitantes en clientes



1. PORTADA HERO (ESTILO APPLE)
Crear una portada impactante tipo Apple keynote.
ELEMENTOS


Imagen o video fullscreen ultra premium de modelo fashion


Fondo negro profundo o blanco minimal


Texto enorme centrado


Tipografía bold editorial


Animación fade-in elegante


Efecto parallax suave


CTA brillante y minimal


CONTENIDO
Título:

“Elegancia que impone presencia”

Subtítulo:

“Moda exclusiva para quienes nacieron para destacar”

Botones:


Explorar colección


Ver novedades


EFECTOS


Scroll reveal cinematográfico


Hover premium


Glow sutil


Transiciones buttery smooth


Movimiento de cámara ultra suave


Sensación tecnológica y fashion luxury



2. SECCIÓN MARCAS RESPALDAN (GRID + SLIDER INFINITO)
Crear una sección visualmente poderosa mostrando marcas premium que respaldan la boutique.
DISEÑO


Grid moderna con logos de marcas


Slider horizontal infinito automático


Movimiento continuo ultra suave


Logos en monocromo elegante


Hover que ilumina cada marca


Background minimal oscuro con blur


EFECTOS


Infinite marquee animation


Motion ultra fluido


Escala suave al hover


Glow elegante


Separaciones minimalistas


ESTILO
Inspirado en:


Apple


Nike


Zara Studio


Fear of God


Luxury fashion websites



3. SECCIÓN PRODUCTOS (GRID + CARRUSEL PREMIUM)
Crear una sección brutal de productos premium.
ESTRUCTURA


Carrusel horizontal


Productos pegados entre sí


Diferentes tamaños de grids


Layout dinámico editorial


Algunas cards grandes


Algunas cards pequeñas


Diseño asimétrico moderno


CADA PRODUCTO DEBE TENER


Imagen ultra HD


Hover cinematic zoom


Cambio de imagen al hover


Nombre elegante


Precio minimalista


Botón “Agregar”


Quick view moderno


Efectos premium


EFECTOS VISUALES


Scroll horizontal suave


Snap scrolling


Hover con profundidad


Glow sutil


Glass effect


Animaciones premium


Sombras realistas


ESTILO VISUAL
Inspirado en:


Apple Store


SSENSE


Farfetch


Balenciaga


Saint Laurent



4. FOOTER “SUPER BRUTAL” DE BOUTIQUE
Crear un footer gigantesco, elegante y memorable.
DISEÑO


Fondo negro premium


Tipografía enorme


Diseño editorial fashion


Varias columnas minimalistas


Elementos flotantes


Blur effects


Líneas finas elegantes


CONTENIDO
Columnas:


Navegación


Colecciones


Redes sociales


Contacto


Newsletter premium


ELEMENTOS EXTRA


Texto gigante de fondo


Efecto glow elegante


Redes sociales minimalistas


Newsletter ultra moderna


Input glassmorphism


Hover animations premium


FRASE FINAL

“Luxury is an attitude.”


MICROINTERACCIONES Y UX
Agregar:


Smooth scrolling


Scroll reveal animations


Motion blur transitions


Magnetic buttons


Hover cinematic


Cursor personalizado premium


Animaciones suaves tipo Apple


Parallax moderno


Carga elegante


Lazy loading premium



PALETA DE COLORES
Usar combinación luxury:


Negro profundo


Blanco puro


Gris carbón


Beige premium


Plateado sutil


Toques dorados minimalistas



TIPOGRAFÍA
Usar tipografías tipo:


SF Pro Display


Neue Haas Grotesk


Helvetica Now


Editorial New


Modern luxury serif



OBJETIVO FINAL
La web debe:


Atrapar clientes instantáneamente


Verse absurdamente premium


Sentirse como una marca de lujo global


Tener estética Apple + Fashion Luxury


Generar deseo de compra inmediato


Parecer diseñada por una agencia creativa de élite mundial















--------------------------------------html-----------------
<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Boutique Premium | Elegancia que impone presencia</title>
    <meta name="description" content="Moda exclusiva para quienes nacieron para destacar. Descubre nuestra colección ultra premium.">
    
    <!-- Google Fonts -->
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;500;600;800&family=Playfair+Display:ital,wght@0,400;0,600;1,400&display=swap" rel="stylesheet">
    
    <link rel="stylesheet" href="styles.css">
</head>
<body class="loading">
    <!-- Custom Cursor -->
    <div class="cursor"></div>
    <div class="cursor-follower"></div>

    <!-- Preloader -->
    <div class="preloader">
        <div class="preloader-text">BOUTIQUE PREMIUM</div>
    </div>

    <!-- Header -->
    <header class="header">
        <div class="logo">BOUTIQUE PREMIUM</div>
        <nav class="nav">
            <a href="#hero" class="nav-link">Inicio</a>
            <a href="#brands" class="nav-link">Marcas</a>
            <a href="#products" class="nav-link">Colección</a>
        </nav>
        <button class="menu-btn magnetic-btn">Menú</button>
    </header>

    <main>
        <!-- Section 1: Hero -->
        <section id="hero" class="hero section">
            <div class="hero-bg">
                <!-- Using Unsplash high-end fashion placeholder -->
                <img src="https://images.unsplash.com/photo-1539109136881-3be0616acf4b?q=80&w=2787&auto=format&fit=crop" alt="Fashion Model" class="hero-img">
                <div class="hero-overlay"></div>
            </div>
            <div class="hero-content">
                <h1 class="hero-title reveal-text">
                    <span>ELEGANCIA QUE</span><br>
                    <span>IMPONE PRESENCIA</span>
                </h1>
                <p class="hero-subtitle reveal-text delay-1">Moda exclusiva para quienes nacieron para destacar</p>
                <div class="hero-cta reveal-text delay-2">
                    <a href="#products" class="btn btn-primary magnetic-btn">Explorar Colección</a>
                    <a href="#brands" class="btn btn-secondary magnetic-btn">Ver Novedades</a>
                </div>
            </div>
        </section>

        <!-- Section 2: Marcas Respaldan -->
        <section id="brands" class="brands section">
            <div class="marquee-container">
                <div class="marquee">
                    <div class="marquee-content">
                        <!-- Brand Logos (Text as placeholders for high-end look) -->
                        <span class="brand-item">BALENCIAGA</span>
                        <span class="brand-item">JACQUEMUS</span>
                        <span class="brand-item">SAINT LAURENT</span>
                        <span class="brand-item">PRADA</span>
                        <span class="brand-item">CELINE</span>
                        <span class="brand-item">BOTTEGA VENETA</span>
                    </div>
                    <!-- Duplicate for infinite loop -->
                    <div class="marquee-content" aria-hidden="true">
                        <span class="brand-item">BALENCIAGA</span>
                        <span class="brand-item">JACQUEMUS</span>
                        <span class="brand-item">SAINT LAURENT</span>
                        <span class="brand-item">PRADA</span>
                        <span class="brand-item">CELINE</span>
                        <span class="brand-item">BOTTEGA VENETA</span>
                    </div>
                </div>
            </div>
        </section>

        <!-- Section 3: Productos (Grid + Carrusel) -->
        <section id="products" class="products section">
            <div class="container">
                <h2 class="section-title reveal-text">Productos Destacados</h2>
                <div class="products-carousel">
                    
                    <!-- Product 1: Large Card -->
                    <div class="product-card large">
                        <div class="product-img-wrapper">
                            <img src="https://images.unsplash.com/photo-1584916201218-f4242ceb4809?q=80&w=2000&auto=format&fit=crop" alt="Bolso Premium" class="product-img">
                            <img src="https://images.unsplash.com/photo-1590874103328-eac38a683ce7?q=80&w=2000&auto=format&fit=crop" alt="Bolso Premium Alt" class="product-img-hover">
                        </div>
                        <div class="product-info">
                            <div class="product-details">
                                <h3 class="product-name">Bolso Icono "Aura"</h3>
                                <p class="product-price">$2,450</p>
                            </div>
                            <div class="product-actions">
                                <button class="btn-action">Agregar</button>
                                <button class="btn-action">Quick View</button>
                            </div>
                        </div>
                    </div>

                    <!-- Product 2: Small Card -->
                    <div class="product-card small">
                        <div class="product-img-wrapper">
                            <img src="https://images.unsplash.com/photo-1543163521-1bf539c55dd2?q=80&w=1760&auto=format&fit=crop" alt="Zapatos Elegantes" class="product-img">
                            <img src="https://images.unsplash.com/photo-1508296695146-257a814070b4?q=80&w=1760&auto=format&fit=crop" alt="Zapatos Elegantes Alt" class="product-img-hover">
                        </div>
                        <div class="product-info">
                            <div class="product-details">
                                <h3 class="product-name">Derby Noir Obsidian</h3>
                                <p class="product-price">$980</p>
                            </div>
                            <div class="product-actions">
                                <button class="btn-action">Agregar</button>
                                <button class="btn-action">Quick View</button>
                            </div>
                        </div>
                    </div>

                    <!-- Product 3: Medium Card -->
                    <div class="product-card medium">
                        <div class="product-img-wrapper">
                            <img src="https://images.unsplash.com/photo-1618244972963-dbee1a7edc95?q=80&w=1760&auto=format&fit=crop" alt="Chaqueta Luxury" class="product-img">
                            <img src="https://images.unsplash.com/photo-1551028719-00167b16eac5?q=80&w=1760&auto=format&fit=crop" alt="Chaqueta Luxury Alt" class="product-img-hover">
                        </div>
                        <div class="product-info">
                            <div class="product-details">
                                <h3 class="product-name">Blazer Asimétrico Vantablack</h3>
                                <p class="product-price">$3,100</p>
                            </div>
                            <div class="product-actions">
                                <button class="btn-action">Agregar</button>
                                <button class="btn-action">Quick View</button>
                            </div>
                        </div>
                    </div>
                    
                    <!-- Product 4: Small Card -->
                    <div class="product-card small">
                        <div class="product-img-wrapper">
                            <img src="https://images.unsplash.com/photo-1591557306404-f58c70f03223?q=80&w=1760&auto=format&fit=crop" alt="Gafas de Sol" class="product-img">
                            <img src="https://images.unsplash.com/photo-1511499767150-a48a237f0083?q=80&w=1760&auto=format&fit=crop" alt="Gafas de Sol Alt" class="product-img-hover">
                        </div>
                        <div class="product-info">
                            <div class="product-details">
                                <h3 class="product-name">Gafas Eclipse "00"</h3>
                                <p class="product-price">$450</p>
                            </div>
                            <div class="product-actions">
                                <button class="btn-action">Agregar</button>
                                <button class="btn-action">Quick View</button>
                            </div>
                        </div>
                    </div>

                </div>
            </div>
        </section>
    </main>

    <!-- Footer "Super Brutal" -->
    <footer class="footer">
        <div class="footer-bg-text">BOUTIQUE PREMIUM</div>
        <div class="container footer-content">
            <div class="footer-grid">
                <div class="footer-col">
                    <h4>Navegación</h4>
                    <ul>
                        <li><a href="#hero">Inicio</a></li>
                        <li><a href="#brands">Marcas</a></li>
                        <li><a href="#products">Colecciones</a></li>
                        <li><a href="#">Editorial</a></li>
                    </ul>
                </div>
                <div class="footer-col">
                    <h4>Colecciones</h4>
                    <ul>
                        <li><a href="#">SS26</a></li>
                        <li><a href="#">FW25</a></li>
                        <li><a href="#">Accesorios</a></li>
                        <li><a href="#">Essentials</a></li>
                    </ul>
                </div>
                <div class="footer-col">
                    <h4>Social</h4>
                    <ul>
                        <li><a href="#">Instagram</a></li>
                        <li><a href="#">TikTok</a></li>
                        <li><a href="#">Pinterest</a></li>
                    </ul>
                </div>
                <div class="footer-col">
                    <h4>Newsletter Premium</h4>
                    <form class="newsletter-form">
                        <div class="input-glass">
                            <input type="email" placeholder="Tu email editorial..." required>
                            <button type="submit" class="btn-submit magnetic-btn">Suscribir</button>
                        </div>
                    </form>
                </div>
            </div>
            <div class="footer-bottom">
                <p class="final-phrase">"Luxury is an attitude."</p>
                <div class="footer-legal">
                    <span>© 2026 Boutique Premium. Todos los derechos reservados.</span>
                </div>
            </div>
        </div>
    </footer>

    <script src="script.js"></script>
</body>
</html>



----------------------------------------------------css--------------------
/* =========================================
   VARIABLES & DESIGN TOKENS
   ========================================= */
:root {
    /* Colors */
    --color-black: #050505;
    --color-white: #fafafa;
    --color-gray: #1a1a1a;
    --color-gray-light: #333333;
    --color-beige: #f5f0e6;
    --color-gold: #d4af37;
    --color-silver: #c0c0c0;

    /* Typography */
    --font-sans: 'Inter', -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, Helvetica, Arial, sans-serif;
    --font-serif: 'Playfair Display', serif;
    
    /* Easing for buttery smooth animations */
    --ease-out-expo: cubic-bezier(0.19, 1, 0.22, 1);
    --ease-in-out-circ: cubic-bezier(0.85, 0, 0.15, 1);
    --transition-fast: 0.3s var(--ease-out-expo);
    --transition-slow: 0.8s var(--ease-out-expo);
    
    /* Z-index */
    --z-cursor: 9999;
    --z-preloader: 9000;
    --z-header: 1000;
}

/* =========================================
   RESET & GLOBAL
   ========================================= */
*, *::before, *::after {
    box-sizing: border-box;
    margin: 0;
    padding: 0;
}

html {
    scroll-behavior: smooth; /* Native smooth scroll fallback */
    font-size: 16px;
}

body {
    background-color: var(--color-black);
    color: var(--color-white);
    font-family: var(--font-sans);
    line-height: 1.5;
    overflow-x: hidden;
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale;
}

body.loading {
    overflow: hidden;
}

ul { list-style: none; }
a { text-decoration: none; color: inherit; }
img { max-width: 100%; display: block; }
button { cursor: pointer; border: none; background: none; font-family: inherit; }

.container {
    width: 100%;
    max-width: 1600px;
    margin: 0 auto;
    padding: 0 4vw;
}

/* =========================================
   CUSTOM CURSOR
   ========================================= */
body { cursor: none; }

.cursor, .cursor-follower {
    position: fixed;
    top: 0;
    left: 0;
    pointer-events: none;
    border-radius: 50%;
    z-index: var(--z-cursor);
    transform: translate(-50%, -50%);
}

.cursor {
    width: 8px;
    height: 8px;
    background-color: var(--color-white);
    transition: width 0.3s, height 0.3s, background-color 0.3s;
}

.cursor-follower {
    width: 40px;
    height: 40px;
    border: 1px solid rgba(255,255,255,0.3);
    transition: transform 0.1s linear, width 0.3s, height 0.3s, border-color 0.3s, background-color 0.3s;
    display: flex;
    align-items: center;
    justify-content: center;
    color: var(--color-black);
    font-size: 10px;
    font-weight: 600;
    text-transform: uppercase;
    letter-spacing: 1px;
    opacity: 0;
}

.cursor-follower.active {
    width: 80px;
    height: 80px;
    background-color: var(--color-white);
    border-color: var(--color-white);
    mix-blend-mode: difference;
    opacity: 1;
}

/* =========================================
   PRELOADER
   ========================================= */
.preloader {
    position: fixed;
    inset: 0;
    background-color: var(--color-black);
    z-index: var(--z-preloader);
    display: flex;
    justify-content: center;
    align-items: center;
    transition: opacity 1s var(--ease-out-expo), visibility 1s;
}

.preloader.hidden {
    opacity: 0;
    visibility: hidden;
}

.preloader-text {
    font-family: var(--font-sans);
    font-size: 2rem;
    font-weight: 800;
    letter-spacing: 4px;
    color: var(--color-white);
    overflow: hidden;
    position: relative;
}

.preloader-text::after {
    content: '';
    position: absolute;
    top: 0;
    right: 0;
    width: 100%;
    height: 100%;
    background-color: var(--color-black);
    animation: revealText 1.5s var(--ease-in-out-circ) forwards;
}

@keyframes revealText {
    0% { transform: translateX(0); }
    100% { transform: translateX(100%); }
}

/* =========================================
   HEADER
   ========================================= */
.header {
    position: fixed;
    top: 0;
    left: 0;
    width: 100%;
    padding: 2rem 4vw;
    display: flex;
    justify-content: space-between;
    align-items: center;
    z-index: var(--z-header);
    transition: background-color 0.4s ease, padding 0.4s ease;
    mix-blend-mode: difference; /* Ensures visibility on light and dark backgrounds */
}

.header.scrolled {
    padding: 1rem 4vw;
    background-color: rgba(5, 5, 5, 0.8);
    backdrop-filter: blur(10px);
    -webkit-backdrop-filter: blur(10px);
    mix-blend-mode: normal;
    border-bottom: 1px solid rgba(255,255,255,0.05);
}

.logo {
    font-weight: 800;
    font-size: 1.2rem;
    letter-spacing: 2px;
}

.nav {
    display: none; /* Hide on mobile */
}

@media (min-width: 768px) {
    .nav {
        display: flex;
        gap: 2rem;
    }
    
    .nav-link {
        font-size: 0.9rem;
        text-transform: uppercase;
        letter-spacing: 1px;
        position: relative;
    }
    
    .nav-link::after {
        content: '';
        position: absolute;
        bottom: -4px;
        left: 0;
        width: 0%;
        height: 1px;
        background-color: var(--color-white);
        transition: width var(--transition-fast);
    }
    
    .nav-link:hover::after {
        width: 100%;
    }
}

.menu-btn {
    color: var(--color-white);
    font-size: 0.9rem;
    text-transform: uppercase;
    letter-spacing: 1px;
}

/* =========================================
   HERO SECTION
   ========================================= */
.hero {
    position: relative;
    height: 100vh;
    display: flex;
    align-items: center;
    justify-content: center;
    overflow: hidden;
}

.hero-bg {
    position: absolute;
    inset: 0;
    z-index: -1;
}

.hero-img {
    width: 100%;
    height: 100%;
    object-fit: cover;
    transform: scale(1.1);
    transition: transform 2s var(--ease-out-expo);
}

.hero.loaded .hero-img {
    transform: scale(1);
}

.hero-overlay {
    position: absolute;
    inset: 0;
    background: linear-gradient(to bottom, rgba(5,5,5,0.2) 0%, rgba(5,5,5,0.8) 100%);
}

.hero-content {
    text-align: center;
    z-index: 1;
    display: flex;
    flex-direction: column;
    align-items: center;
    width: 100%;
    padding: 0 4vw;
}

.hero-title {
    font-family: var(--font-sans);
    font-size: clamp(3rem, 8vw, 8rem);
    font-weight: 800;
    line-height: 1;
    letter-spacing: -2px;
    margin-bottom: 1.5rem;
    text-transform: uppercase;
}

.hero-title span {
    display: inline-block;
}

.hero-subtitle {
    font-family: var(--font-serif);
    font-size: clamp(1.2rem, 2vw, 1.8rem);
    font-style: italic;
    color: var(--color-beige);
    margin-bottom: 3rem;
    max-width: 600px;
}

.hero-cta {
    display: flex;
    gap: 1.5rem;
    flex-wrap: wrap;
    justify-content: center;
}

.btn {
    padding: 1rem 2.5rem;
    border-radius: 100px;
    font-size: 0.9rem;
    font-weight: 600;
    text-transform: uppercase;
    letter-spacing: 1px;
    transition: all var(--transition-fast);
    position: relative;
    overflow: hidden;
}

.btn-primary {
    background-color: var(--color-white);
    color: var(--color-black);
}

.btn-primary:hover {
    background-color: var(--color-beige);
    box-shadow: 0 0 30px rgba(255,255,255,0.3);
    transform: translateY(-2px);
}

.btn-secondary {
    background-color: transparent;
    color: var(--color-white);
    border: 1px solid rgba(255,255,255,0.3);
    backdrop-filter: blur(10px);
    -webkit-backdrop-filter: blur(10px);
}

.btn-secondary:hover {
    border-color: var(--color-white);
    background-color: rgba(255,255,255,0.1);
    transform: translateY(-2px);
}

/* =========================================
   BRANDS SECTION
   ========================================= */
.brands {
    padding: 6rem 0;
    background-color: var(--color-black);
    border-bottom: 1px solid var(--color-gray);
    overflow: hidden;
}

.marquee-container {
    width: 100%;
    position: relative;
    display: flex;
    overflow: hidden;
    mask-image: linear-gradient(to right, transparent, black 10%, black 90%, transparent);
    -webkit-mask-image: linear-gradient(to right, transparent, black 10%, black 90%, transparent);
}

.marquee {
    display: flex;
    width: max-content;
    animation: marquee 30s linear infinite;
}

.marquee:hover {
    animation-play-state: paused;
}

.marquee-content {
    display: flex;
    justify-content: space-around;
    min-width: 100%;
}

.brand-item {
    font-size: 2rem;
    font-weight: 800;
    color: var(--color-gray-light);
    margin: 0 4rem;
    transition: color var(--transition-fast), text-shadow var(--transition-fast), transform var(--transition-fast);
    cursor: default;
}

.brand-item:hover {
    color: var(--color-white);
    text-shadow: 0 0 20px rgba(255,255,255,0.5);
    transform: scale(1.05);
}

@keyframes marquee {
    0% { transform: translateX(0); }
    100% { transform: translateX(-50%); }
}

/* =========================================
   PRODUCTS SECTION (Horizontal Carousel)
   ========================================= */
.products {
    padding: 8rem 0;
    background-color: var(--color-gray);
    position: relative;
}

.section-title {
    font-size: clamp(2rem, 4vw, 3.5rem);
    margin-bottom: 4rem;
    font-weight: 800;
    letter-spacing: -1px;
    padding-left: 4vw;
}

.products-carousel {
    display: flex;
    gap: 2px; /* Brutalist tight gap */
    padding: 0 4vw;
    overflow-x: auto;
    scroll-snap-type: x mandatory;
    scrollbar-width: none; /* Firefox */
    -ms-overflow-style: none;  /* IE and Edge */
}

.products-carousel::-webkit-scrollbar {
    display: none;
}

.product-card {
    flex: 0 0 auto;
    scroll-snap-align: start;
    background-color: var(--color-black);
    position: relative;
    overflow: hidden;
    border-radius: 20px;
    margin-right: 20px;
}

.product-card.large { width: 500px; height: 700px; }
.product-card.medium { width: 400px; height: 600px; }
.product-card.small { width: 300px; height: 450px; }

@media (max-width: 768px) {
    .product-card.large, .product-card.medium { width: 85vw; height: 60vh; }
    .product-card.small { width: 70vw; height: 50vh; }
}

.product-img-wrapper {
    width: 100%;
    height: 100%;
    position: relative;
    overflow: hidden;
}

.product-img, .product-img-hover {
    width: 100%;
    height: 100%;
    object-fit: cover;
    transition: transform var(--transition-slow), opacity var(--transition-slow);
}

.product-img-hover {
    position: absolute;
    top: 0;
    left: 0;
    opacity: 0;
}

.product-card:hover .product-img {
    opacity: 0;
    transform: scale(1.05);
}

.product-card:hover .product-img-hover {
    opacity: 1;
    transform: scale(1.05);
}

.product-info {
    position: absolute;
    bottom: 0;
    left: 0;
    width: 100%;
    padding: 2rem;
    background: linear-gradient(to top, rgba(0,0,0,0.9), transparent);
    display: flex;
    justify-content: space-between;
    align-items: flex-end;
    transform: translateY(20px);
    opacity: 0.9;
    transition: transform var(--transition-fast), opacity var(--transition-fast);
}

.product-card:hover .product-info {
    transform: translateY(0);
    opacity: 1;
}

.product-name {
    font-size: 1.2rem;
    font-weight: 600;
    margin-bottom: 0.5rem;
}

.product-price {
    font-family: var(--font-serif);
    font-style: italic;
    color: var(--color-beige);
}

.product-actions {
    display: flex;
    gap: 0.5rem;
    opacity: 0;
    transform: translateY(10px);
    transition: all var(--transition-fast);
}

.product-card:hover .product-actions {
    opacity: 1;
    transform: translateY(0);
    transition-delay: 0.1s;
}

.btn-action {
    background-color: rgba(255,255,255,0.1);
    backdrop-filter: blur(5px);
    -webkit-backdrop-filter: blur(5px);
    color: var(--color-white);
    padding: 0.5rem 1rem;
    border-radius: 50px;
    font-size: 0.8rem;
    font-weight: 600;
    text-transform: uppercase;
    transition: background-color 0.2s;
}

.btn-action:hover {
    background-color: var(--color-white);
    color: var(--color-black);
}

/* =========================================
   FOOTER "SUPER BRUTAL"
   ========================================= */
.footer {
    position: relative;
    background-color: var(--color-black);
    padding: 8rem 0 2rem;
    overflow: hidden;
}

.footer-bg-text {
    position: absolute;
    top: 50%;
    left: 50%;
    transform: translate(-50%, -50%);
    font-size: 15vw;
    font-weight: 900;
    color: rgba(255,255,255,0.02);
    white-space: nowrap;
    pointer-events: none;
    z-index: 0;
    font-family: var(--font-sans);
}

.footer-content {
    position: relative;
    z-index: 1;
}

.footer-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
    gap: 4rem;
    margin-bottom: 8rem;
}

.footer-col h4 {
    font-size: 0.9rem;
    text-transform: uppercase;
    letter-spacing: 2px;
    color: var(--color-gray-light);
    margin-bottom: 1.5rem;
}

.footer-col ul {
    display: flex;
    flex-direction: column;
    gap: 1rem;
}

.footer-col a {
    font-size: 1.1rem;
    transition: color var(--transition-fast);
}

.footer-col a:hover {
    color: var(--color-beige);
}

.newsletter-form {
    margin-top: 1rem;
}

.input-glass {
    display: flex;
    background: rgba(255,255,255,0.05);
    backdrop-filter: blur(10px);
    -webkit-backdrop-filter: blur(10px);
    border: 1px solid rgba(255,255,255,0.1);
    border-radius: 100px;
    padding: 0.5rem;
    transition: border-color var(--transition-fast), box-shadow var(--transition-fast);
}

.input-glass:focus-within {
    border-color: var(--color-white);
    box-shadow: 0 0 20px rgba(255,255,255,0.1);
}

.input-glass input {
    background: transparent;
    border: none;
    color: var(--color-white);
    padding: 0.5rem 1rem;
    flex: 1;
    outline: none;
    font-family: inherit;
}

.input-glass input::placeholder {
    color: rgba(255,255,255,0.4);
}

.btn-submit {
    background-color: var(--color-white);
    color: var(--color-black);
    padding: 0.5rem 1.5rem;
    border-radius: 50px;
    font-weight: 600;
    text-transform: uppercase;
    font-size: 0.8rem;
}

.footer-bottom {
    display: flex;
    flex-direction: column;
    align-items: center;
    gap: 4rem;
    border-top: 1px solid rgba(255,255,255,0.1);
    padding-top: 4rem;
}

.final-phrase {
    font-family: var(--font-serif);
    font-size: clamp(2rem, 5vw, 4rem);
    font-style: italic;
    color: var(--color-white);
    text-align: center;
}

.footer-legal {
    font-size: 0.8rem;
    color: var(--color-gray-light);
}

/* =========================================
   ANIMATIONS & UTILS
   ========================================= */
.reveal-text {
    opacity: 0;
    transform: translateY(30px);
    transition: opacity 1s var(--ease-out-expo), transform 1s var(--ease-out-expo);
}

.reveal-text.visible {
    opacity: 1;
    transform: translateY(0);
}

.delay-1 { transition-delay: 0.2s; }
.delay-2 { transition-delay: 0.4s; }

------------------------------js-------------------------------------
document.addEventListener("DOMContentLoaded", () => {
    // 1. Preloader
    const preloader = document.querySelector('.preloader');
    const hero = document.querySelector('.hero');
    
    // Simulate loading time for visual impact
    setTimeout(() => {
        preloader.classList.add('hidden');
        document.body.classList.remove('loading');
        hero.classList.add('loaded');
        
        // Trigger initial reveal animations
        setTimeout(() => {
            const initialReveals = document.querySelectorAll('#hero .reveal-text');
            initialReveals.forEach(el => el.classList.add('visible'));
        }, 300);
    }, 2000);

    // 2. Custom Cursor
    const cursor = document.querySelector('.cursor');
    const cursorFollower = document.querySelector('.cursor-follower');
    
    let mouseX = 0;
    let mouseY = 0;
    let cursorX = 0;
    let cursorY = 0;

    document.addEventListener('mousemove', (e) => {
        mouseX = e.clientX;
        mouseY = e.clientY;
        
        // Immediate update for dot
        cursor.style.transform = `translate3d(${mouseX}px, ${mouseY}px, 0) translate(-50%, -50%)`;
    });

    // Smooth follower animation loop
    function animateCursor() {
        // Ease function for smooth follow
        cursorX += (mouseX - cursorX) * 0.15;
        cursorY += (mouseY - cursorY) * 0.15;
        
        cursorFollower.style.transform = `translate3d(${cursorX}px, ${cursorY}px, 0) translate(-50%, -50%)`;
        requestAnimationFrame(animateCursor);
    }
    animateCursor();

    // Hover effects for cursor
    const interactiveElements = document.querySelectorAll('a, button, .product-card');
    
    interactiveElements.forEach(el => {
        el.addEventListener('mouseenter', () => {
            cursorFollower.classList.add('active');
            
            // Si es un producto, cambiar el texto del cursor
            if(el.classList.contains('product-card')) {
                cursorFollower.textContent = 'View';
            }
        });
        
        el.addEventListener('mouseleave', () => {
            cursorFollower.classList.remove('active');
            cursorFollower.textContent = '';
        });
    });

    // 3. Header Scroll Effect
    const header = document.querySelector('.header');
    
    window.addEventListener('scroll', () => {
        if (window.scrollY > 50) {
            header.classList.add('scrolled');
        } else {
            header.classList.add('scrolled'); // Keep it scrolled style for better contrast or toggle it
            if(window.scrollY < 10) {
                header.classList.remove('scrolled');
            }
        }
    });

    // 4. Scroll Reveal Animations (Intersection Observer)
    const revealElements = document.querySelectorAll('.reveal-text:not(#hero .reveal-text)');
    
    const revealOptions = {
        threshold: 0.1,
        rootMargin: "0px 0px -50px 0px"
    };

    const revealOnScroll = new IntersectionObserver(function(entries, observer) {
        entries.forEach(entry => {
            if (!entry.isIntersecting) {
                return;
            }
            entry.target.classList.add('visible');
            observer.unobserve(entry.target);
        });
    }, revealOptions);

    revealElements.forEach(el => {
        revealOnScroll.observe(el);
    });

    // 5. Magnetic Buttons Effect
    const magneticButtons = document.querySelectorAll('.magnetic-btn');

    magneticButtons.forEach(btn => {
        btn.addEventListener('mousemove', function(e) {
            const position = btn.getBoundingClientRect();
            const x = e.pageX - position.left - position.width / 2;
            const y = e.pageY - position.top - position.height / 2;
            
            // Adjust the multiplier (0.3) for more or less magnetic pull
            btn.style.transform = `translate(${x * 0.3}px, ${y * 0.3}px)`;
        });

        btn.addEventListener('mouseout', function() {
            btn.style.transform = 'translate(0px, 0px)';
        });
    });

    // 6. Smooth Scroll for Anchor Links (Vanilla JS)
    document.querySelectorAll('a[href^="#"]').forEach(anchor => {
        anchor.addEventListener('click', function (e) {
            e.preventDefault();
            
            const targetId = this.getAttribute('href');
            if (targetId === '#') return;
            
            const targetElement = document.querySelector(targetId);
            if (targetElement) {
                window.scrollTo({
                    top: targetElement.offsetTop,
                    behavior: 'smooth'
                });
            }
        });
    });
    
    // 7. Parallax Effect for Hero Image
    const heroImg = document.querySelector('.hero-img');
    window.addEventListener('scroll', () => {
        const scrolled = window.scrollY;
        if(scrolled < window.innerHeight) {
            heroImg.style.transform = `translateY(${scrolled * 0.3}px) scale(1)`;
        }
    });
});

