# BOOTSTRAP TEST

This is to learn how to structure our bootstrap code for future use

## Navbar

- Ensure to use a container class
- Use the navbar class 

<nav class="navbar navbar-expand-lg navbar-dark">
        <div class="container">
          <a href="#" class="navbar-brand text-uppercase text-black">Property</a>
          <button
            class="navbar-toggler"
            type="button"
            data-bs-toggle="collapse"
            data-bs-target="#navbarNavAltMarkup"
            aria-controls="navbarNavAltMarkup"
            aria-expanded="false"
            aria-label="Toggle navigation"
          >
            <span class="navbar-toggler-icon"></span>
          </button>

          <div
            class="collaspe navbar-collapse justify-content-end"
            id="navbarNavAltMarkup"
          >
            <div class="navbar-nav">
              <a href="#home" class="navbar-link active" aria-current="page"
                >Home
              </a>

              
              <a href="#about" class="navbar-link"> About </a>
              <a href="#feature" class="navbar-link"> Feature </a>
              <a href="#contact" class="navbar-link"> Contact </a>
            </div>
          </div>
        </div>
      </nav>