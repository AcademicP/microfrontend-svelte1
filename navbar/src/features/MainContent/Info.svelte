<script>
  // No se necesita lógica específica para este ejemplo.
</script>

<div class="main-content">
  <div class="jumbotron bg-light p-4 rounded shadow-sm">
    <h1 class="display-6 text-center mb-3">Bienvenido al Portal FIIS</h1>
    <p class="lead text-center">
      Explora las diferentes aplicaciones y recursos disponibles para estudiantes y docentes.
      Este portal facilita la navegación y ofrece información relevante, apoyando el crecimiento
      académico y profesional.
    </p>
  </div>

  <div class="advantages mt-4">
    <h2 class="text-center mb-4">¿Por qué usar esta plataforma?</h2>
    <div class="row row-cols-1 row-cols-md-3 g-3">
      <div class="col">
        <div class="card h-100 shadow-sm text-center">
          <div class="card-body">
            <i class="bi bi-speedometer2 icon mb-2"></i>
            <h5 class="card-title">Navegación Rápida</h5>
            <p class="card-text">
              Las SPA ofrecen una experiencia de usuario fluida con actualizaciones en tiempo real,
              sin recargar toda la página.
            </p>
          </div>
        </div>
      </div>

      <div class="col">
        <div class="card h-100 shadow-sm text-center">
          <div class="card-body">
            <i class="bi bi-server icon mb-2"></i>
            <h5 class="card-title">Eficiencia en el Servidor</h5>
            <p class="card-text">
              La plataforma optimiza la carga, enviando solo los datos necesarios, reduciendo costos
              e impacto ambiental.
            </p>
          </div>
        </div>
      </div>

      <div class="col">
        <div class="card h-100 shadow-sm text-center">
          <div class="card-body">
            <i class="bi bi-arrows-angle-expand icon mb-2"></i>
            <h5 class="card-title">Escalabilidad</h5>
            <p class="card-text">
              La SPA permite a cada estudiante dejar un legado con sus proyectos, fortaleciendo la
              marca FIIS y promoviendo la innovación continua.
            </p>
          </div>
        </div>
      </div>
    </div>
  </div>
</div>

<style>
  .main-content {
    flex: 1;
    padding: 20px;
    background-color: #f5f5f5;
    overflow-y: auto;
  }

  .jumbotron {
    background-color: #ffffff;
    text-align: center;
    border-radius: 10px;
    padding: 30px;
  }

  .advantages h2 {
    color: #343a40;
  }

  .card {
    border-radius: 10px;
    transition: transform 0.2s;
  }

  .card:hover {
    transform: scale(1.05);
  }

  .icon {
    font-size: 2.5rem;
    color: #0d6efd;
  }

  .card-text {
    color: #6c757d;
  }
</style>
