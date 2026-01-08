<html lang="es">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Currículum | José Miguel</title>

<style>
*{
    margin:0;
    padding:0;
    box-sizing:border-box;
    font-family: Arial, Helvetica, sans-serif;
}

body{
    background:#f4f6f9;
    color:#333;
}

.container{
    max-width:1100px;
    margin:40px auto;
    background:#fff;
    border-radius:12px;
    overflow:hidden;
    box-shadow:0 10px 25px rgba(0,0,0,.1);
}

.header{
    background:linear-gradient(135deg,#1e3c72,#2a5298);
    color:#fff;
    text-align:center;
    padding:40px 20px;
}

.header img{
    width:180px;
    height:180px;
    border-radius:50%;
    border:5px solid #fff;
    object-fit:cover;
    margin-bottom:15px;
}

.header h1{
    font-size:32px;
}

.header h3{
    font-weight:normal;
    margin-top:5px;
}

.content{
    display:grid;
    grid-template-columns: 1fr 2fr;
}

.sidebar{
    background:#f0f2f5;
    padding:30px;
}

.section{
    margin-bottom:25px;
}

.section h2{
    font-size:18px;
    margin-bottom:10px;
    color:#1e3c72;
    border-bottom:2px solid #1e3c72;
    padding-bottom:5px;
}

.info li{
    list-style:none;
    margin-bottom:8px;
    font-size:14px;
}

.main{
    padding:30px;
}

.experience{
    margin-bottom:20px;
}

.experience h4{
    color:#2a5298;
}

.experience span{
    font-size:13px;
    color:#666;
}

.experience p{
    margin-top:5px;
    font-size:14px;
    line-height:1.5;
}

button{
    margin-top:15px;
    padding:10px 18px;
    background:#2a5298;
    color:#fff;
    border:none;
    border-radius:20px;
    cursor:pointer;
}

button:hover{
    background:#1e3c72;
}

@media(max-width:768px){
    .content{
        grid-template-columns:1fr;
    }
}
</style>
</head>

<body>

<div class="container">

    <!-- ENCABEZADO -->
    <div class="header">
        <img src="fotomiguel.jpg" width="250" height="250">
        <h1>José Miguel Romero Ávila</h1>
        <h3>CEO / Director · Ciber Human</h3>
        <button onclick="window.print()">Imprimir CV</button>
    </div>

    <!-- CONTENIDO -->
    <div class="content">

        <!-- COLUMNA IZQUIERDA -->
        <aside class="sidebar">

            <div class="section">
                <h2>¿Quién soy?</h2>
                <p style="font-size:14px; line-height:1.5;">
                    Soy CEO y Director de la empresa Ciber Human. Me encargo de tomar decisiones estratégicas,
                    definir la dirección de la empresa, supervisar áreas, administrar recursos y representar
                    a la empresa ante socios e inversionistas.
                </p>
            </div>

            <div class="section">
                <h2>Información Personal</h2>
                <ul class="info">
                    <li><strong>Fecha:</strong> 02/02/2007</li>
                    <li><strong>Email:</strong> josemiguelromeroavila@gmail.com</li>
                    <li><strong>Teléfono:</strong> 729 550 4363</li>
                    <li><strong>Instagram:</strong> _.j.miguel17</li>
                    <li><strong>Dirección:</strong> Otzolotepec, Estado de México</li>
                </ul>
            </div>

        </aside>

        <!-- COLUMNA DERECHA -->
        <main class="main">

            <div class="section">
                <h2>Experiencia Profesional</h2>

                <div class="experience">
                    <h4>Motriz – Especialista en Ciberseguridad</h4>
                    <span>2016 – 2019</span>
                    <p>
                        Empresa dedicada a cursos de ciberseguridad y programación.
                        Aportación: Aprendió procesos técnicos, adaptación a clientes
                        y trato con estudiantes.
                    </p>
                </div>

                <div class="experience">
                    <h4>OrtoFlex Solutions – Coordinador de Taller</h4>
                    <span>2019 – 2022</span>
                    <p>
                        Taller especializado en dispositivos digitales.
                        Aportación: Supervisó producción, optimizó tiempos
                        y lideró un equipo multidisciplinario.
                    </p>
                </div>

                <div class="experience">
                    <h4>Advance Rehab Group – Gerente de Operaciones</h4>
                    <span>2022 – 2024</span>
                    <p>
                        Cadena de servicios y atención de cursos.
                        Aportación: Expansión de la empresa, implementación
                        de estrategias de servicio y mejora en atención al cliente.
                    </p>
                </div>

            </div>

        </main>

    </div>

</div>

</body>
</html>
