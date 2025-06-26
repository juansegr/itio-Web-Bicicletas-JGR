<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Bicicletas JGR</title>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet">
    <link rel="stylesheet" href="styles.css">
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap-icons@1.10.5/font/bootstrap-icons.css">
</head>
<body>
    <header class="bg-primary text-light text-center p-3 d-flex align-items-center justify-content-center">
        <img src="Imagenes/Screenshot 2024-11-14 110311.png" alt="Logo de Bicicletas JGR" class="me-3" style="height: 300px;">
        <div>
            
        </div>
    </header>

    <div class="container mt-4">
        <div class="row">
            <div class="col text-center">
                <h3>Nueva Colección de Bicicletas</h3>
                <p>Descubre nuestra nueva línea de bicicletas perfectas para cualquier aventura.</p>
                <img src="Imagenes/1.png" class="img-fluid" alt="Bicicleta nueva" />
            </div>
        </div>

        <form class="mt-4" action="#" method="post">
            <div class="mb-3">
                <label for="email" class="form-label">Suscríbete para recibir información</label>
                <input type="email" class="form-control" id="email" placeholder="Tu correo electrónico" required>
            </div>
            <button type="submit" class="btn btn-primary">Enviar</button>
        </form>

        <div class="row mt-4">
            <div class="col-md-4 text-center">
                <img src="Imagenes/Montana.png" class="img-fluid" alt="Bicicleta de montaña">
                <h4>Bicicleta de montaña</h4>
                <p>Precio: $1.990.000</p>
                <button class="btn btn-success">Comprar</button>
            </div>
            <div class="col-md-4 text-center">
                <img src="Imagenes/ruart.png" class="img-fluid" alt="Bicicleta de ruta">
                <h4>Bicicleta de ruta</h4>
                <p>Precio: $2.850.000</p>
                <button class="btn btn-success">Comprar</button>
            </div>
            <div class="col-md-4 text-center">
                <img src="Imagenes/urbaadan.png" class="img-fluid" alt="Bicicleta urbana">
                <h4>Bicicleta urbana</h4>
                <p>Precio: $1.450.000</p>
                <button class="btn btn-success">Comprar</button>
            </div>
        </div>

        <div class="mt-5">
            <h3>Testimonios de Nuestros Clientes</h3>
            <ul class="list-unstyled">
                <li>"Excelente servicio y productos de calidad." - Juan P.</li>
                <li>"Las bicicletas son increíbles, muy cómodas." - Ana M.</li>
                <li>"Compré una bici y estoy muy satisfecho." - Carlos R.</li>
                <li>"Excelente atención al cliente." - Laura G.</li>
                <li>"El mejor lugar para comprar bicicletas." - Pedro S.</li>
            </ul>
        </div>
    </div>

    <footer class="bg-dark text-light text-center p-3">
        <div>
            <a href="#" class="text-success mx-2"><i class="bi bi-facebook"></i></a>
            <a href="#" class="text-success mx-2"><i class="bi bi-instagram"></i></a>
            <a href="#" class="text-success mx-2"><i class="bi bi-twitter"></i></a>
        </div>
        <p>Juan Sebastian Giraldo Roldan</p>
    </footer>

    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js"></script>
</body>
