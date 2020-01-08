# portfolio2
 </div>
	  
	  
<!-- PCTO-->
    <div id="bar" class="bg slideup">
      <h1>PCTO</h1>
		
   	<!-- carosello-->
		<div id="carouselExampleCaptions" class="carousel slide" data-ride="carousel">
  <ol class="carousel-indicators">
    <li data-target="#carouselExampleCaptions" data-slide-to="0" class="active"></li>
    <li data-target="#carouselExampleCaptions" data-slide-to="1"></li>
    <li data-target="#carouselExampleCaptions" data-slide-to="2"></li>
  </ol>
  <div class="carousel-inner">
    <div class="carousel-item active">
      <img src="https://placekitten.com/1201/800" class="d-block w-100" alt="...">
      <div class="carousel-caption d-none d-md-block">
        <h5>progetto 1</h5>
        <p>Nulla vitae elit libero, a pharetra augue mollis interdum.</p>
      </div>
    </div>
    <div class="carousel-item">
      <img src="https://placekitten.com/1201/800" class="d-block w-100" alt="...">
      <div class="carousel-caption d-none d-md-block">
        <h5>progetto 2</h5>
        <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit.</p>
      </div>
    </div>
    <div class="carousel-item">
      <img src="https://placekitten.com/1201/800" class="d-block w-100" alt="...">
      <div class="carousel-caption d-none d-md-block">
        <h5>progetto 3</h5>
        <p>Praesent commodo cursus magna, vel scelerisque nisl consectetur.</p>
      </div>
    </div>
  </div>
  <a class="carousel-control-prev" href="#carouselExampleCaptions" role="button" data-slide="prev">
    <span class="carousel-control-prev-icon" aria-hidden="true"></span>
    <span class="sr-only">Previous</span>
  </a>
  <a class="carousel-control-next" href="#carouselExampleCaptions" role="button" data-slide="next">
    <span class="carousel-control-next-icon" aria-hidden="true"></span>
    <span class="sr-only">Next</span>
  </a>
</div>
		
    </div>
<!-- 5B-->
    <div id="baz" class="bg slideleft">
      <h1 class="5B">quintaB</h1>
     <!-- metti lo sfondo bianco-->	
    </div>
	  
<!-- 3B-->
    <div id="qux" class="bg slideright">
      <h1>terzaB</h1>
      <img src="https://placekitten.com/1201/800" alt="">
    </div>
	  
<!-- 4B-->
    <div id="quux" class="bg slidedown">
      <h1>quartaB</h1>
      <img src="https://placekitten.com/1203/800" alt="">
    </div>

  </div>
  <script>
    const slideup = document.querySelector("#slideup");
    const bar = document.querySelector("#bar");
    slideup.onclick = function () {
      const active = bar.classList.toggle("active");
      slideup.innerHTML = active ? "Slide down" : "Slide up";
    };

    const slideleft = document.querySelector("#slideleft");
    const baz = document.querySelector("#baz");
    slideleft.onclick = function () {
      const active = baz.classList.toggle("active");
      slideleft.innerHTML = active ? "Slide right" : "Slide left";
    };

    const slideright = document.querySelector("#slideright");
    const qux = document.querySelector("#qux");
    slideright.onclick = function () {
      const active = qux.classList.toggle("active");
      slideright.innerHTML = active ? "Slide left" : "Slide right";
    };

    const slidedown = document.querySelector("#slidedown");
    const quux = document.querySelector("#quux");
    slidedown.onclick = function () {
      const active = quux.classList.toggle("active");
      slidedown.innerHTML = active ? "Slide up" : "Slide down";
    };

  </script>


</body></html>
