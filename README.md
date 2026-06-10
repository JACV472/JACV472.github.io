
<html lang="es">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<title>Rem | Wiki Anime</title>

<style>

*{
    margin:0;
    padding:0;
    box-sizing:border-box;
}

body{
    font-family:Arial, Helvetica, sans-serif;
    background:#181a20;
    color:white;
    line-height:1.6;
}

header{
    background:#2b2f3a;
    padding:25px;
    text-align:center;
    box-shadow:0 2px 10px rgba(0,0,0,.4);
}

header h1{
    color:#7fb3ff;
    font-size:2.5rem;
}

.contenedor{
    max-width:1200px;
    margin:20px auto;
    display:flex;
    gap:20px;
    padding:10px;
}

.ficha{
    width:320px;
    background:#252934;
    border-radius:12px;
    overflow:hidden;
    box-shadow:0 4px 12px rgba(0,0,0,.4);
}

.ficha img{
    width:100%;
    display:block;
    transition:0.3s;
}

.ficha img:hover{
    transform:scale(1.05);
}

.datos{
    padding:15px;
}

.datos h2{
    color:#7fb3ff;
    margin-bottom:10px;
}

.datos p{
    margin:8px 0;
}

.contenido{
    flex:1;
    background:#252934;
    border-radius:12px;
    padding:25px;
    text-align:justify;
    box-shadow:0 4px 12px rgba(0,0,0,.4);
}

.seccion{
    margin-bottom:30px;
}

.seccion h2{
    color:#7fb3ff;
    border-bottom:2px solid #5c7cff;
    padding-bottom:5px;
    margin-bottom:15px;
}

ul{
    padding-left:20px;
}

li{
    margin-bottom:10px;
}

.galeria{
    display:flex;
    flex-wrap:wrap;
    gap:10px;
}

.galeria img{
    width:220px;
    border-radius:10px;
    transition:0.3s;
}

.galeria img:hover{
    transform:scale(1.05);
}

footer{
    background:#2b2f3a;
    text-align:center;
    padding:15px;
    margin-top:20px;
}

@media (max-width:768px){

    .contenedor{
        flex-direction:column;
    }

    .ficha{
        width:100%;
    }

    .galeria img{
        width:100%;
    }
}

</style>
</head>
<body>

<header>
    <h1>Rem</h1>
</header>

<div class="contenedor">

    <aside class="ficha">

        <img src="rem.jpg" alt="Rem">

        <div class="datos">

            <h2>Información</h2>

            <p><b>Anime:</b> Re:Zero − Starting Life in Another World</p>
            <p><b>Edad:</b> 17 años</p>
            <p><b>Altura:</b> 154 cm</p>
            <p><b>Cumpleaños:</b> 2 de febrero</p>
            <p><b>Raza:</b> Oni</p>
            <p><b>Ocupación:</b> Sirvienta</p>
            <p><b>Hermana:</b> Ram</p>

        </div>

    </aside>

    <main class="contenido">

        <section class="seccion">

            <h2>Historia</h2>

            <p>
                Rem es una de las gemelas oni que trabajan como
                sirvientas en la mansión de Roswaal junto a su
                hermana Ram.
            </p>

            <br>

            <p>
                Durante su infancia vivió en una aldea oni.
                Mientras Ram era considerada un prodigio,
                Rem creció sintiéndose inferior a ella.
                Tras el ataque que destruyó su aldea y dejó
                a Ram sin su cuerno, Rem desarrolló un fuerte
                sentimiento de culpa y dedicó gran parte de
                su vida a compensar la pérdida de su hermana.
            </p>

            <br>

            <p>
                Con el paso del tiempo comenzó a trabajar en
                la mansión de Roswaal. La llegada de Subaru
                Natsuki cambió profundamente su forma de ver
                la vida y la ayudó a ganar confianza en sí
                misma y encontrar un propósito propio.
            </p>

        </section>

        <section class="seccion">

            <h2>Personalidad</h2>

            <p>
                Rem suele ser reservada, trabajadora y muy
                dedicada a las personas que aprecia. Aunque
                inicialmente puede mostrarse desconfiada,
                demuestra una gran lealtad y amabilidad con
                quienes se ganan su confianza.
            </p>

            <br>

            <p>
                Le gusta ayudar a los demás, cumplir con sus
                responsabilidades y proteger a sus seres
                queridos. Su objetivo es superar sus
                inseguridades y convertirse en alguien de quien
                pueda sentirse orgullosa.
            </p>

        </section>

        <section class="seccion">

            <h2>Habilidades</h2>

            <ul>
                <li><b>Modo Oni:</b> aumenta enormemente su fuerza, velocidad y resistencia.</li>

                <li><b>Magia de agua:</b> puede utilizar hechizos de agua para combatir y apoyar aliados.</li>

                <li><b>Dominio del mayal:</b> maneja con gran habilidad su característica arma de cadena.</li>
            </ul>

        </section>

        <section class="seccion">

            <h2>Galería</h2>

            <div class="galeria">

                <img src="rem1.jpg" alt="Rem">
                <img src="rem2.jpg" alt="Rem">
                <img src="rem3.jpg" alt="Rem">

            </div>

        </section>

    </main>

</div>

<footer>
    REM ES VIDA
</footer>

</body>
</html>
