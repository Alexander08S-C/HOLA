<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Carne de Cuy - Alimento Nutritivo y Saludable</title>
    <link rel="stylesheet" href="plantilla.css">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta3/css/all.min.css">
    <script src="script.js"></script>
    <header>
        <div class="container header-container">
            <a href="#" class="logo">Valle del <span>Mantaro</span></a>
            <div class="mobile-menu">
                <i class="fas fa-bars"></i>
            </div>
            <nav>
                <ul>
                    <li><a href="#inicio">Inicio</a></li>
                    <li><a href="#beneficios">Beneficios</a></li>
                    <li><a href="#nutricion">Nutrición</a></li>
                    <li><a href="#testimonios">Testimonios</a></li>
                    <li><a href="#contacto">Contacto</a></li>
                </ul>
            </nav>
        </div>
    </header>

    <!-- Hero Section -->
    <section class="hero" id="inicio">
        <div class="container">
            <h1>Descubre los beneficios de la carne de cuy</h1>
            <p>Un superalimento andino rico en proteínas, hierro y ácidos grasos esenciales para tu salud</p>
            <a href="#nutricion" class="btn">Conoce sus propiedades</a>
        </div>
    </section>

    <!-- Features Section -->
    <section class="features" id="beneficios">
        <div class="container">
            <div class="section-title">
                <h2>Beneficios de la carne de cuy</h2>
                <p>La carne de cuy es reconocida por sus múltiples beneficios para la salud y su alto valor nutricional</p>
            </div>
            <div class="features-grid">
                <div class="feature-card">
                    <div class="feature-icon">
                        <i class="fas fa-heartbeat"></i>
                    </div>
                    <h3>Salud cardiovascular</h3>
                    <p>Bajo contenido de colesterol y triglicéridos, ideal para mantener un corazón saludable</p>
                </div>
                <div class="feature-card">
                    <div class="feature-icon">
                        <i class="fas fa-brain"></i>
                    </div>
                    <h3>Desarrollo neuronal</h3>
                    <p>Rica en ácidos grasos esenciales para el desarrollo del cerebro y sistema nervioso</p>
                </div>
                <div class="feature-card">
                    <div class="feature-icon">
                        <i class="fas fa-bone"></i>
                    </div>
                    <h3>Fortaleza ósea</h3>
                    <p>Alto contenido de calcio y fósforo para huesos y dientes fuertes</p>
                </div>
                <div class="feature-card">
                    <div class="feature-icon">
                        <i class="fas fa-utensils"></i>
                    </div>
                    <h3>Fácil digestión</h3>
                    <p>Carne de alta digestibilidad, recomendada para personas con problemas gastrointestinales</p>
                </div>
                <div class="feature-card">
                    <div class="feature-icon">
                        <i class="fas fa-shield-virus"></i>
                    </div>
                    <h3>Sistema inmunológico</h3>
                    <p>Fortalece las defensas del organismo gracias a su composición nutricional</p>
                </div>
                <div class="feature-card">
                    <div class="feature-icon">
                        <i class="fas fa-child"></i>
                    </div>
                    <h3>Combate la anemia</h3>
                    <p>Alto contenido de hierro y proteínas, esencial para combatir la anemia</p>
                </div>
            </div>
        </div>
    </section>

    <!-- About Section -->
    <section class="about">
        <div class="container">
            <div class="about-content">
                <div class="about-text">
                    <h2>Un alimento milenario</h2>
                    <p>La carne de cuy ha sido consumida en los Andes desde tiempos precolombinos, reconocida por sus propiedades nutricionales y beneficios para la salud.</p>
                    <p>Según el Ministerio de Agricultura (Minagri), la carne de cuy tiene alta digestibilidad, bajas trazas de colesterol y triglicéridos, y alta presencia de ácidos grasos linoleico y linolénico, esenciales para el ser humano.</p>
                    <p>Estos ácidos grasos son precursores de la conformación del ácido graso araquidónico (AA) y ácido graso docosahexaenoico (DHA), sustancias vitales para el desarrollo de las neuronas y las membranas celulares.</p>
                    <a href="#" class="btn">Más información</a>
                </div>
                <div class="about-image">
                    <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQ4zsMiH9R_WigvUFOl-LvNwlzsWToHVSvB8ES0kcIfbo6URFuHd15jjvZgw0jaRlt0sgc&usqp=CAU" alt="Cuy preparado">
                </div>
            </div>
        </div>
    </section>
    

    </div>
    <section class="nutrition" id="nutricion">
        <div class="container">
            <div class="section-title">
                <h2>Valor nutricional</h2>
            </div>
            <div class="nutrition-table">
                <table>
                    <thead>
                        <div class="nutrition-container">
                            <div class="nutrition-header">
                                <h2>VALOR NUTRICIONAL - CARNE DE CUY</h2>
                            </div>
                            <div class="nutrition-subheader">
                                Por 100 gramos de porción comestible
                            </div>
                            <table class="nutrition-table">
                                <tbody id="nutrition-data">
                                    <!-- Los datos nutricionales se insertarán aquí -->
                                </tbody>
                            </table>
                            <div class="nutrition-footer">
                                Fuente: Ministerio de Agricultura (Minagri) - Perú
                            </div>
                        </div>
                    </thead>
                </table>
                <script>
                    // Datos nutricionales (puedes editar estos valores)
                    const nutritionData = [
                        { nutrient: 'Energía (kcal)', value: '120-150' },
                        { nutrient: 'Proteínas (g)', value: '19-21' },
                        { nutrient: 'Grasas totales (g)', value: '6-8' },
                        { nutrient: 'Grasas saturadas (g)', value: '2-3' },
                        { nutrient: 'Hierro (mg)', value: '1.5-2.0' },
                        { nutrient: 'Calcio (mg)', value: '20-25' },
                        { nutrient: 'Colesterol (mg)', value: '60-70' },
                        { nutrient: 'Ácidos grasos omega-3 (g)', value: '0.7-0.9' },
                        { nutrient: 'Ácidos grasos omega-6 (g)', value: '1.1-1.3' }
                    ];
        
                    // Insertar datos en la tabla
                    const tableBody = document.getElementById('nutrition-data');
                    
                    nutritionData.forEach(item => {
                        const row = document.createElement('tr');
                        
                        row.innerHTML = `
                            <td>${item.nutrient}</td>
                            <td><strong>${item.value}</strong></td>
                        `;
                        
                        tableBody.appendChild(row);
                    });
                </script>
        </div>
    </section>

    <!-- Testimonials -->
    <section class="testimonials" id="testimonios">
        <div class="container">
            <div class="section-title">
                <h2>Lo que dicen nuestros clientes</h2>
                <p>Testimonios de personas que han incorporado la carne de cuy en su alimentación</p>
            </div>
            <div class="testimonials-grid">
                <div class="testimonial-card">
                    <div class="testimonial-text">
                        "Desde que comencé a consumir carne de cuy regularmente, mis niveles de hierro han mejorado notablemente. Mi médico quedó impresionado con los resultados."
                    </div>
                    <div class="testimonial-author">
                        <img src="https://randomuser.me/api/portraits/women/32.jpg" alt="María López">
                        <div class="author-info">
                            <h4>María López</h4>
                            <p>Paciente con anemia</p>
                        </div>
                    </div>
                </div>
                <div class="testimonial-card">
                    <div class="testimonial-text">
                        "Como nutricionista, recomiendo la carne de cuy por su perfil lipídico excepcional. Es una excelente alternativa proteica para mis pacientes."
                    </div>
                    <div class="testimonial-author">
                        <img src="https://randomuser.me/api/portraits/men/45.jpg" alt="Carlos Méndez">
                        <div class="author-info">
                            <h4>Carlos Méndez</h4>
                            <p>Nutricionista deportivo</p>
                        </div>
                    </div>
                </div>
                <div class="testimonial-card">
                    <div class="testimonial-text">
                        "Incorporamos carne de cuy en la dieta de nuestros hijos y hemos notado mejoras en su concentración y rendimiento escolar. ¡Los ácidos grasos funcionan!"
                    </div>
                    <div class="testimonial-author">
                        <img src="https://randomuser.me/api/portraits/women/68.jpg" alt="Familia Rojas">
                        <div class="author-info">
                            <h4>Familia Rojas</h4>
                            <p>Padres preocupados por la nutrición</p>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- CTA Section -->
    <section class="cta">
        <div class="container">
            <h2>¿Listo para mejorar tu alimentación?</h2>
            <p>Descubre cómo incorporar la carne de cuy en tu dieta puede beneficiar tu salud y la de tu familia</p>
            <a href="https://wa.me/51942224849" target="_blank">
                <button class="btn">Contáctanos</button>
            </a>
            
              
        </div>
    </section>

    <!-- Footer -->
    <footer id="contacto">
        <div class="container">
            <div class="footer-content">
                <div class="footer-column">
                    <h3>Valle del Mantaro</h3>
                    <p>Promoviendo el consumo de carne de cuy por sus excelentes propiedades nutricionales y beneficios para la salud.</p>
                    <div class="social-links">
                    </div>
                </div>
                <div class="footer-column">
                    <h3>Enlaces</h3>
                    <ul>
                        <li><a href="#inicio">Inicio</a></li>
                        <li><a href="#beneficios">Beneficios</a></li>
                        <li><a href="#nutricion">Valor nutricional</a></li>
                        <li><a href="#testimonios">Testimonios</a></li>
                        <li><a href="#contacto">Contacto</a></li>
                    </ul>
                </div>
                <div class="footer-column">
                    <h3>Contacto</h3>
                    <ul>
                        <li><i class="fas fa-map-marker-alt"></i> , Lima</li>
                        <li><i class="fas fa-phone"></i> (51) #numero de telefono</li>
                        <li><i class="fas fa-envelope"></i> valledelmantaro.com</li>
                        <li><i class="fas fa-clock"></i> Lunes a Sábado: 9am - 6pm</li>
                        <li><i class="fas fa-clock"></i> Domingo: 9am - 1pm</li>
                    </ul>
                </div>
            </div>
            <div class="copyright">
                <p>&copy; 2025 Valle del Mantaro. Todos los derechos reservados.</p>
            </div>
        </div>
    </footer>
