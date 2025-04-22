# Desafio_Olivia_Ros
Desafío_Olivia_Ros
style="background-color: #373A3C;"

/*reset de css a html*/
* {
    box-sizing: border-box;
    margin: 0;
    padding: 0;
}

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <!--links bootstrap-->
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.5/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-SgOJa3DmI69IUzQ2PVdRZhwQ+dy64/BUtbMJw1MZ8t5HZApcHrRKUc4W0kG879m7" crossorigin="anonymous">
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.5/dist/js/bootstrap.bundle.min.js" integrity="sha384-k6d4wzSIapyDyv1kpU366/PK5hCdSbCRGRCMv+eplOQJWyd1fbcAu9OCUj5zNLiq" crossorigin="anonymous"></script>
    <!--link css-->
    <link rel="stylesheet" href="assets/css/styles.css">
    <!--link font awesome-->
    <link rel="stylesheet" href="https://use.fontawesome.com/releases/v5.6.3/css/all.css"
    integrity="sha384-UHRtZLI+pbxtHCWp1t77Bi1L4ZtiqrqD80Kn4Z8NTSRyMA2Fd33n5dQ8lWUE00s/" crossorigin="anonymous">
    <title>Desafío Olivia Ros</title>


</head>
<body>
    <nav class="navbar navbar-dark navbar-expand-lg bg-dark">
        <div class="container-fluid">
          <a class="navbar-brand" href="#"><img src="assets/img/logo.png" alt=""></a>
          <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
            <span class="navbar-toggler-icon"></span>
          </button>
          <div class="collapse navbar-collapse" id="navbarSupportedContent"
          ></div>
        </div>
    </nav>

    <header class="text-light text-end">
        <div class="card text-bg-dark">
            <img src="assets/img/bg-hero.jpg" class="card-img" alt="...">
            <div class="card-img-overlay">
              <h5 class="card-title">Card title</h5>
              <p class="card-text">This is a wider card with supporting text below as a natural lead-in to additional content. This content is a little bit longer.</p>
              <p class="card-text"><small>Last updated 3 mins ago</small></p>
              <div>
                <button type="button" class="btn btn-primary">Primary</button>
                <button type="button" class="btn btn-outline-primary">Primary</button>
            </div>
            </div>
        </div>
            

        </div>

    </header>

    <section>
        <div class="card-group justify-content-center aling-item-center text-center">
            <h2 class="diplay-3 text-center">Acerca de mi</h2>
            <div class="card">
                <div class="card-body">
                    <div class="d-flex justify-content-center aling-item-center">
                        <i class="bi bi-camera2 fs-4"></i>
                    </div>
                    <h5 class="card-title">Fotógrafa de Comida</h5>
                </div>
            </div>
            <div class="card">
              
            <div class="card-body">
                <div class="d-flex justify-content-center aling-item-center">
                    <div class="d-flex justify-content-center aling-item-center">
                        <i class="bi bi-airplane-engines-fill fs-4"></i>
                    </div>
                </div>
                
                <h5 class="card-title">Crítica Culinaria</h5>
                
              </div>
            </div>
            <div class="card">
              
              <div class="card-body">
                
                <h5 class="card-title">Bloguera de viajes</h5>
                
              </div>
            </div>
        </div>
    </section>

    <section id="trabajos">
        <div class="row row-cols-1 row-cols-md-2 g-4 py-4">
            <div class="col">
              <div class="card">
                <img src="..." class="card-img-top" alt="...">
                <div class="card-body">
                  <h5 class="card-title">Card title</h5>
                  <p class="card-text">This is a longer card with supporting text below as a natural lead-in to additional content. This content is a little bit longer.</p>
                </div>
              </div>
            </div>
            <div class="col">
              <div class="card">
                <img src="..." class="card-img-top" alt="...">
                <div class="card-body">
                  <h5 class="card-title">Card title</h5>
                  <p class="card-text">This is a longer card with supporting text below as a natural lead-in to additional content. This content is a little bit longer.</p>
                </div>
              </div>
            </div>
            <div class="col">
              <div class="card">
                <img src="..." class="card-img-top" alt="...">
                <div class="card-body">
                  <h5 class="card-title">Card title</h5>
                  <p class="card-text">This is a longer card with supporting text below as a natural lead-in to additional content.</p>
                </div>
              </div>
            </div>
            </div>
          </div>
    </section>

    <section>
        <div class="mb-3 row">
            <label for="staticEmail" class="col-sm-2 col-form-label">Email</label>
            <div class="col-sm-10">
              <input type="text" readonly class="form-control-plaintext" id="staticEmail" value="email@example.com">
            </div>
          </div>
          <div class="mb-3 row">
            <label for="inputPassword" class="col-sm-2 col-form-label">Password</label>
            <div class="col-sm-10">
              <input type="password" class="form-control" id="inputPassword">
            </div>
            <div class="mb-3 row">
                <label for="inputPassword" class="col-sm-2 col-form-label">Mensaje</label>
                <div class="col-sm-10">
                    <input class="form-control" list="datalistOptions" id="exampleDataList" placeholder="Type to search...">
                </div>
          </div>

          <footer class="bg-dark text-center text-light">
            <p>Olivia Ros 2019. Todos los derechos reservados.</p>

          </footer>
    </section>
</body>
</html>