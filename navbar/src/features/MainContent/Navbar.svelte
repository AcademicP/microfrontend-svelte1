<script>
    import "bootstrap/dist/css/bootstrap.min.css";
</script>

<nav class="navbar navbar-expand-lg navbar-light bg-light">
    <div class="container-fluid">
        <a class="navbar-brand" href="/">FIIS UNAS </a>
    
        <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
            <span class="navbar-toggler-icon">
            
            </span>
        </button>
        <div class="collapse navbar-collapse" id="navbarSupportedContent">
            <ul class="navbar-nav me-auto mb-2 mb-lg-0">
                <li class="nav-item">
                    <a class="nav-link active" aria-current="page" href="/">Home</a>
                </li>
                <li class="nav-item">
                    <a class="nav-link" href="/about">About FIIS</a>
                </li>
                <li class="nav-item dropdown">
                    <a class="nav-link dropdown-toggle" href="#" id="navbarDropdown" role="button" data-bs-toggle="dropdown" aria-expanded="false">
                        Proyectos
                    </a>
                    <ul class="dropdown-menu" aria-labelledby="navbarDropdown">
                        <li><a class="dropdown-item" href="/react">React Projects</a></li>
                        <li><a class="dropdown-item" href="/vue">Vue Projects</a></li>
                        <li><a class="dropdown-item" href="/angular">Angular Projects</a></li>
                    </ul>
                </li>
                <li class="nav-item">
                    <a class="nav-link" href="/submit" tabindex="-1">Subir Proyecto</a>
                </li>
                SVELTE
            </ul>
          
            <form class="d-flex">
                <input class="form-control me-2" type="search" placeholder="Buscar proyectos" aria-label="Search">
                <button class="btn btn-outline-success" type="submit">Buscar</button>
            </form>
        </div>
    </div>
</nav>
