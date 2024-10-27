# BOOTSTRAP TEST
This is to learn how to structure our bootstrap for future code
## Navbar
- Ensure to use a container class
- use the navbar class

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
            class="collapse navbar-collapse justify-content-end"
            id="navbarNavAltMarkup"
          >
            <div class="navbar-nav">
              <a href="#home" class="nav-link active text-black" arial-current="page"
                >Home</a
              >
              <a href="#About" class="nav-link text-black">About</a>
              <a href="#Feature" class="nav-link text-black">Feature</a>
              <a href="#Contact" class="nav-link text-black">Contact</a>
            </div>
          </div>
        </div>
        </nav>