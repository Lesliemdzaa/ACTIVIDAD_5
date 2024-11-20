<!DOCTYPE html>
<html lang="es">
<head>
     <meta name="viewport"content="wwidth=device-width,initial-scal=1.0">
     <meta charset=!UTF-8">
     <title>MENU DESPLEGABLES</title>

    <style>
        /* Estilos del menú */
        body {
            font-family: Arial, sans-serif;
        }

        .menu {
            background-color: #884ea0 ;
            padding: 12px;
        }

        .menu ul {
            list-style-type: none;
            margin: 0;
            padding: 0;
            display: flex;
        }

        .menu li {
            position: relative;
        }

        .menu li a {
            color: white;
            padding: 15px 20px;
            text-decoration: none;
            display: block;
        }

        .menu li a:hover {
            background-color: #e4cfed;
        }

        /* Submenú */
        .menu li ul {
            display: none;
            position: absolute;
            top: 100%;
            left: 0;
            background-color: #d5c5dc;
            min-width: 180px;
            box-shadow: 0px 8px 16px rgba(0, 0, 0, 0.2);
        }

        .menu li:hover ul {
            display: block;
        }

        .menu li ul li a {
            padding: 10px 20px;
        }

        .menu li ul li a:hover {
            background-color:  #884ea0 ;
        }

    </style>
</head>
<body>

    <nav class="menu">
        <ul>
            <li><a href="SOMBRAS.html">Inicio</a></li>
        
            <li>
                <a href="#">Servicios</a>
                <ul>
                    <li><a href="ARTICULO.html">Diseño</a></li>
                    <li><a href="CAJAS.html">Desarrollo</a></li>
                    <li><a href="LISTAS.html">Consultoría</a></li>
                </ul>
            </li>
            <li><a href="BARRADENAVEGACION_FIJA.html">Portafolio</a></li>
            <li><a href="TARJETA_DE_PERFIL.html">Contacto</a></li>
        </ul>
    </nav>

</body>
</html>
