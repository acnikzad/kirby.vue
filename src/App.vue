<template>
  <div id="app">
<!-- Navigation-->
    <nav class="navbar navbar-expand-lg navbar-light fixed-top py-3" id="mainNav">
        <div class="container">
            <a class="navbar-brand js-scroll-trigger" href="#page-top">4x4 Teardrop Trailers</a>
            <button class="navbar-toggler navbar-toggler-right" type="button" data-toggle="collapse" data-target="#navbarResponsive" aria-controls="navbarResponsive" aria-expanded="false" aria-label="Toggle navigation"><span class="navbar-toggler-icon"></span></button>
            <div class="collapse navbar-collapse" id="navbarResponsive">
                <ul class="navbar-nav ml-auto my-2 my-lg-0">
                    <li class="nav-item"><a class="nav-link js-scroll-trigger" href="#home">Home</a></li>
                    <li class="nav-item"><a class="nav-link js-scroll-trigger" href="#services">About</a></li>
                    <li class="nav-item"><a class="nav-link js-scroll-trigger" href="#portfolio">Trailers</a></li>
                    <li class="nav-item"><a class="nav-link js-scroll-trigger" href="/contact">Contact</a></li>
                </ul>
            </div>
        </div>
    </nav>
<!-- Masthead-->
    <header class="masthead">
        <div class="container h-100">
            <div class="row h-100 align-items-center justify-content-center text-center">
                <div class="col-lg-10 align-self-end">
                    <h1 class="text-uppercase text-white font-weight-bold">Vintage Trailer Works</h1>
                    <hr class="divider my-4" />
                </div>
                <div class="col-lg-8 align-self-baseline">
                    <p class="text-white-75 font-weight-light mb-5">Build your own custom offroad travel trailer!</p>
                    <a class="btn btn-primary btn-xl js-scroll-trigger" href="#about">Find Out More</a>
                </div>
            </div>
        </div>
    </header>
    <router-view/>
    <footer class="bg-light py-5">
      <div class="row">
        <div class="col span-1-of-2">
          <div class="container"><div class="small text-center text-muted">Contact Us: (415) 333-3333</div></div>
        </div>
        <div class="col span-1-of-2">
          <div class="container"><div class="small text-center text-muted">Petaluma, CA</div></div>
        </div>
      </div>
    </footer>
  </div>
</template>

<style>

</style>
