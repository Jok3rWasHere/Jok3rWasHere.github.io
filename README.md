<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.1.2/css/all.min.css" integrity="sha512-1sCRPdkRXhBV2PBLUdRb4tMg1w2YPf37qatUFeS7zlBy7jJI8Lf4VHwWfZZfpXtYSLy85pkm9GaYVYMfw5BC1A==" crossorigin="anonymous" referrerpolicy="no-referrer" />
    <title>DJ JOINER</title>
    <link rel="stylesheet" href="brr.css">
</head>
<body>
    <!-- MENU ENCABEZADO -->
    <div class="contenedor-header">
        <header>
            <div class="logo">
                <a href="#"></a>
            </div>
            <nav id="nav">
                <ul>
                    <li><a href="#inicio" onclick="seleccionar()">INICIO</a></li>
                    <li><a href="#sobremi" onclick="seleccionar()">SOBRE MI</a></li>
                    <li><a href="#curriculum" onclick="seleccionar()">CURRICULUM</a></li>
                    <li><a href="#contacto" onclick="seleccionar()">CONTACTO</a></li>
                </ul>
            </nav>
            <div class="nav-responsive" onclick="mostrarOcultarMenu()">
                <i class="fa-solid fa-bars"></i>
            </div>
        </header>
    </div>

    <!-- SECCION INICIO -->
    <section id="inicio" class="inicio">
        <div class="contenido-banner">
            <div class="contenedor-img">
                <img src="img/joiner.png" alt="">
            </div>
            <h1>DJ JOINER</h1>
            <h2>Dj profesional - Crossover</h2>
            <div class="redes">
                <a href="https://www.facebook.com/joiner.montalvo.9" target="_blank"><i class="fa-brands fa-facebook-f"></i></a>
                <a href="https://www.youtube.com/@djjoiner5987" target="_blank"><i class="fa-brands fa-youtube"></i></a>
                <a href="https://www.instagram.com/djjoiner_oficial/" target="_blank"><i class="fa-brands fa-instagram"></i></a>
                <a href="https://www.tiktok.com/@djjoiner_19" target="_blank"><i class="fa-brands fa-tiktok"></i></a>

            </div>
        </div>
    </section>
    <!-- SECCION SOBRE MI -->
    <section id="sobremi" class="sobremi">
        <div class="contenido-seccion">
            <h2>Sobre Mí</h2>
            <p><span>Hola, soy Nick Perez.</span> Lorem ipsum dolor sit amet consectetur adipisicing elit. Quisquam unde soluta minima necessitatibus, voluptas consectetur vero officiis quas, explicabo deleniti repellendus aliquid debitis maiores numquam voluptate reprehenderit in delectus dolores.</p>

            <div class="fila">
                <!-- datos personales -->
                <div class="col">
                    <h3>Datos Personales</h3>
                    <ul>
                        <li>
                            <strong>Cumpleaños</strong>
                            6-11-2002
                        </li>
                        <li>
                            <strong>Teléfono</strong>
                            315-217-5447
                        </li>
                        <li>
                            <strong>Email</strong>
                            cw@example.com
                        </li>
                        <li>
                            <strong>Dirección</strong>
                            Cartagena , Colombia
                        </li>
                        </li>
                    </ul>
                </div>

                <!-- intereses -->
                <div class="col">
                    <h3>Intereses</h3>
                    <div class="contenedor-intereses">
                        <div class="interes">
                            <i class="fa-solid fa-gamepad"></i>
                            <span>JUEGOS</span>
                        </div>
                        <div class="interes">
                            <i class="fa-solid fa-headphones"></i>
                            <span>MUSICA</span>
                        </div>
                        <div class="interes">
                            <i class="fa-solid fa-plane"></i>
                            <span>VIAJAR</span>
                        </div>
                        <div class="interes">
                            <i class="fa-brands fa-apple"></i>
                            <span>MAC OS</span>
                        </div>
                        <div class="interes">
                            <i class="fa-solid fa-person-hiking"></i>
                            <span>DEPORTE</span>
                        </div>
                        <div class="interes">
                            <i class="fa-solid fa-book"></i>
                            <span>LIBROS</span>
                        </div>
                        <div class="interes">
                            <i class="fa-solid fa-car"></i>
                            <span>AUTOS</span>
                        </div>
                        <div class="interes">
                            <i class="fa-solid fa-camera"></i>
                            <span>FOTOS</span>
                        </div>
                        
                    </div>
                </div>
            </div>
            <button>
                Descargar CV <i class="fa-solid fa-download"></i>
                <span class="overlay"></span>
            </button>
        </div>
    </section>

    <!-- SECCION CURRICULUM -->
    <section id="curriculum" class="curriculum">
        <div class="contenido-seccion">
            <h2>Curriculum</h2>
            <div class="fila">
                <div class="col izquierda">
                    <h3>Educación</h3>
                    <div class="item izq">
                        <h4>Arte y Multimedia</h4>
                        <span class="casa">Universidad de Oxford</span>
                        <span class="fecha">2005 - 2008</span>
                        <p>Lorem ipsum dolor sit amet consectetur, adipisicing elit. Quis, cumque repellat, tempora recusandae aliquam nemo esse natus impedit, nostrum temporibus veritatis eaque soluta aperiam id repudiandae fugiat deserunt! Explicabo, veritatis?</p>
                        <div class="conectori">
                            <div class="circuloi"></div>
                        </div>
                    </div>
                    <div class="item izq">
                        <h4>Arte y Multimedia</h4>
                        <span class="casa">Universidad de Oxford</span>
                        <span class="fecha">2005 - 2008</span>
                        <p>Lorem ipsum dolor sit amet consectetur, adipisicing elit. Quis, cumque repellat, tempora recusandae aliquam nemo esse natus impedit, nostrum temporibus veritatis eaque soluta aperiam id repudiandae fugiat deserunt! Explicabo, veritatis?</p>
                        <div class="conectori">
                            <div class="circuloi"></div>
                        </div>
                    </div>
                    <div class="item izq">
                        <h4>Arte y Multimedia</h4>
                        <span class="casa">Universidad de Oxford</span>
                        <span class="fecha">2005 - 2008</span>
                        <p>Lorem ipsum dolor sit amet consectetur, adipisicing elit. Quis, cumque repellat, tempora recusandae aliquam nemo esse natus impedit, nostrum temporibus veritatis eaque soluta aperiam id repudiandae fugiat deserunt! Explicabo, veritatis?</p>
                        <div class="conectori">
                            <div class="circuloi"></div>
                        </div>
                    </div>
                </div>

                <div class="col derecha">
                    <h3>Experiencia de trabajo</h3>
                    <div class="item der">
                        <h4>Front Developer</h4>
                        <span class="casa">Nombre de Compañía</span>
                        <span class="fecha">2005 - 2008</span>
                        <p>Lorem ipsum dolor sit amet consectetur, adipisicing elit. Quis, cumque repellat, tempora recusandae aliquam nemo esse natus impedit, nostrum temporibus veritatis eaque soluta aperiam id repudiandae fugiat deserunt! Explicabo, veritatis?</p>
                        <div class="conectord">
                            <div class="circulod"></div>
                        </div>
                    </div>
                    <div class="item der">
                        <h4>Front Developer</h4>
                        <span class="casa">Nombre de Compañía</span>
                        <span class="fecha">2005 - 2008</span>
                        <p>Lorem ipsum dolor sit amet consectetur, adipisicing elit. Quis, cumque repellat, tempora recusandae aliquam nemo esse natus impedit, nostrum temporibus veritatis eaque soluta aperiam id repudiandae fugiat deserunt! Explicabo, veritatis?</p>
                        <div class="conectord">
                            <div class="circulod"></div>
                        </div>
                    </div>
                    <div class="item der">
                        <h4>Front Developer</h4>
                        <span class="casa">Nombre de Compañía</span>
                        <span class="fecha">2005 - 2008</span>
                        <p>Lorem ipsum dolor sit amet consectetur, adipisicing elit. Quis, cumque repellat, tempora recusandae aliquam nemo esse natus impedit, nostrum temporibus veritatis eaque soluta aperiam id repudiandae fugiat deserunt! Explicabo, veritatis?</p>
                        <div class="conectord">
                            <div class="circulod"></div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- SECCION CONTACTO -->
    <section id="contacto" class="contacto">
        <div class="contenido-seccion">
            <h2>CONTACTO</h2>
            <div class="fila">
                <!-- Formulario -->
                <div class="col">
                    <input type="text" placeholder="Tú Nombre">
                    <input type="text" placeholder="Número telefónico">
                    <input type="text" placeholder="Dirección de correo">
                    <input type="text" placeholder="Tema">
                    <textarea name="" id="" cols="30" rows="10" placeholder="Mensaje"></textarea>
                    <button>
                        Enviar Mensaje<i class="fa-solid fa-paper-plane"></i>
                        <span class="overlay"></span>
                    </button>
                </div>
                <!-- Mapa -->
                <div class="col">
                    <img src="img/ubicacion.png" alt="">
                    <div class="info">
                        <ul>
                            <li>
                                <i class="fa-solid fa-location-dot"></i>
                                Cartagena , Colombia
                            </li>
                            <li>
                                <i class="fa-solid fa-mobile-screen"></i>
                                Llamanos: 312-271-2615 
                            </li>
                            <li>
                                <i class="fa-solid fa-envelope"></i>
                                Email: cw@example.com
                            </li>
                        </ul>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- footer -->
    <footer>
        <a href="#inicio" class="arriba">
            <i class="fa-solid fa-angles-up"></i>
        </a>
        <div class="redes">
            <a href="https://www.facebook.com/joiner.montalvo.9" target="_blank"><i class="fa-brands fa-facebook-f"></i></a>
            <a href="https://www.youtube.com/@djjoiner5987" target="_blank"><i class="fa-brands fa-youtube"></i></a>
            <a href="https://www.instagram.com/djjoiner_oficial/" target="_blank"><i class="fa-brands fa-instagram"></i></a>
            <a href="https://www.tiktok.com/@djjoiner_19" target="_blank"><i class="fa-brands fa-tiktok"></i></a>
        </div>
    </footer>

    <script src="script.js"></script>
</body>
</html>
