
<div class="alert alert-block alert-success" style="font-family:Times New Roman;color:#FFFFFF;background-color: #E7E7E7">
<h1 align="center"><span style="font-family:Times New Roman;color:#046D0B"><b>Big Data y Análisis de Datos usando Python con Inteligencia Artificial</b></span></h1>
</div>
<style>
table tr:last-child td:last-child {
  border-bottom-right-radius: 0.5rem;
}
</style>


<table align="center" style="font-size: 13px;">
<tr>
    <th align="left"><span style="font-family:Monospace;font-size: 12px;">Autor</span></th>
    <th align="left"><span style="font-family:Monospace;font-size: 12px;">:VR ROJAS</span></th>
</tr>
<tr>
    <th align="left"><span style="font-family:Monospace;font-size: 12px;">Email</span></th>
    <th align="left"><span style="font-family:Monospace;font-size: 12px;">:sacha.analytics@gmail.com</span></th>
</tr>
<tr>
    <th align="left"><span style="font-family:Monospace;font-size: 12px;">Web</span></th>
    <th align="left">:<a href="https://sacha-analytics.github.io/" style="font-family:Monospace;font-size: 13px;">sacha-analytics</a></th>
</tr>
</table>
<br>

%## Contenido
%- [Introducción a Big Data](#s0)
%- [Preámbulo](#pre)
%- [Origenes: informática y programación](#s1)
%- [Top 10 lenguajes de programación](#s2)
%- [Ecosistema de Python](#s2)
%- [Aplicaciones con Python](#s4)

# **1. Fundamentos de Big Data y Computación en la Nube**
<a name="s0"></a>
%---------------------------------------------------------------------------------------------------

## **I. Big Data**

### **1.1. Que es Big Data?**
<a name="pre"></a>
%---------------------------------------------------------------------------------------------------
Es el conjunto de estrategias, tecnologías y sistemas para el almacenamiento, procesamiento, análisis y visualización de conjunto de datos complejos.

<div class="languages-slideshow-container">
  <img class="languages-slides active" src="https://github.com/vrrp/sachabook_bigdata/blob/main/docs/images/preambulo/rev0.png?raw=true" alt="Imagen 0: Evolución 0">
  <img class="languages-slides" src="https://github.com/vrrp/sachabook_bigdata/blob/main/docs/images/preambulo/rev1.png?raw=true" alt="Imagen 1: Evolución 1">
  <img class="languages-slides" src="https://github.com/vrrp/sachabook_bigdata/blob/main/docs/images/preambulo/rev2.png?raw=true" alt="Imagen 2: Evolución 2">
  <img class="languages-slides" src="https://github.com/vrrp/sachabook_bigdata/blob/main/docs/images/preambulo/rev3.png?raw=true" alt="Imagen 3: Evolución 3">
  <img class="languages-slides" src="https://github.com/vrrp/sachabook_bigdata/blob/main/docs/images/preambulo/rev4.png?raw=true" alt="Imagen 4: Evolución 4">
  <img class="languages-slides" src="https://github.com/vrrp/sachabook_bigdata/blob/main/docs/images/preambulo/rev5.png?raw=true" alt="Imagen 5: Evolución 4">
  <img class="languages-slides" src="https://github.com/vrrp/sachabook_bigdata/blob/main/docs/images/preambulo/rev6.png?raw=true" alt="Imagen 6: Evolución 4">
  <img class="languages-slides" src="https://github.com/vrrp/sachabook_bigdata/blob/main/docs/images/preambulo/rev7.png?raw=true" alt="Imagen 7: Evolución 4">
  <img class="languages-slides" src="https://github.com/vrrp/sachabook_bigdata/blob/main/docs/images/preambulo/rev8.png?raw=true" alt="Imagen 8: Evolución 4">
  <img class="languages-slides" src="https://github.com/vrrp/sachabook_bigdata/blob/main/docs/images/preambulo/rev9.png?raw=true" alt="Imagen 9: Evolución 4">
  <img class="languages-slides" src="https://github.com/vrrp/sachabook_bigdata/blob/main/docs/images/preambulo/rev10.png?raw=true" alt="Imagen 10: Evolución 4">
  <img class="languages-slides" src="https://github.com/vrrp/sachabook_bigdata/blob/main/docs/images/preambulo/rev11.png?raw=true" alt="Imagen 11: Evolución 4">
  <img class="languages-slides" src="https://github.com/vrrp/sachabook_bigdata/blob/main/docs/images/preambulo/rev12.png?raw=true" alt="Imagen 12: Evolución 4">
  <img class="languages-slides" src="https://github.com/vrrp/sachabook_bigdata/blob/main/docs/images/preambulo/rev13.png?raw=true" alt="Imagen 13: Evolución 4">
  <img class="languages-slides" src="https://github.com/vrrp/sachabook_bigdata/blob/main/docs/images/preambulo/rev14.png?raw=true" alt="Imagen 14: Evolución 4">
  <img class="languages-slides" src="https://github.com/vrrp/sachabook_bigdata/blob/main/docs/images/preambulo/rev15.png?raw=true" alt="Imagen 15: Evolución 4">
  <img class="languages-slides" src="https://github.com/vrrp/sachabook_bigdata/blob/main/docs/images/preambulo/rev16.png?raw=true" alt="Imagen 16: Evolución 4">
  <div class="languages-controls"><button onclick="languagesChangeSlide(-1)">Anterior</button><button onclick="languagesToggleAutoPlay()" id="languages-play-btn">Play</button><button onclick="languagesChangeSlide(1)">Siguiente</button><button onclick="languagesToggleFullscreen()" id="languages-fullscreen-btn">Pantalla completa</button></div>
</div>

<style>
.languages-slideshow-container {
  max-width: 800px;
  margin: auto;
  position: relative;
  border: 2px solid #ddd;
  border-radius: 8px;
  overflow: hidden;
  box-shadow: 0 4px 8px rgba(0,0,0,0.1);
}
.languages-slides {
  display: none;
  width: 100%;
  height: auto;
}
.languages-slides.active {
  display: block;
}
.languages-controls {
  text-align: center;
  margin-top: 10px;
  padding: 10px;
  display: flex;
  flex-wrap: wrap;
  justify-content: center;
  gap: 8px;
}
.languages-controls button {
  margin: 0 5px;
  padding: 8px 15px;
  cursor: pointer;
  background: #007bff;
  color: white;
  border: none;
  border-radius: 5px;
  font-size: 14px;
  transition: background-color 0.3s;
}
.languages-controls button:hover {
  background: #0056b3;
  transform: translateY(-2px);
}
.languages-slideshow-container.fullscreen {
  position: fixed;
  top: 0;
  left: 0;
  width: 100vw;
  height: 100vh;
  max-width: 100vw;
  z-index: 9999;
  background: #000;
  border: none;
  border-radius: 0;
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
}
.languages-slideshow-container.fullscreen .languages-slides {
  max-height: calc(100vh - 80px);
  width: auto;
  max-width: 100%;
  object-fit: contain;
}
.languages-slideshow-container.fullscreen .languages-controls {
  position: absolute;
  bottom: 10px;
  width: 100%;
  background: rgba(0,0,0,0.5);
  padding: 15px;
}
</style>

<script>
(function() {
  let languagesSlideIndex = 0;
  let languagesAutoPlayInterval = null;
  const languagesSlides = document.getElementsByClassName("languages-slides");
  const languagesPlayBtn = document.getElementById("languages-play-btn");

  function languagesShowSlide(index) {
    if (index >= languagesSlides.length) languagesSlideIndex = 0;
    if (index < 0) languagesSlideIndex = languagesSlides.length - 1;
    for (let i = 0; i < languagesSlides.length; i++) {
      languagesSlides[i].classList.remove("active");
    }
    languagesSlides[languagesSlideIndex].classList.add("active");
  }

  window.languagesChangeSlide = function(n) {
    languagesSlideIndex += n;
    languagesShowSlide(languagesSlideIndex);
  };

  window.languagesToggleAutoPlay = function() {
    if (languagesAutoPlayInterval) {
      clearInterval(languagesAutoPlayInterval);
      languagesAutoPlayInterval = null;
      languagesPlayBtn.textContent = "Play";
    } else {
      languagesAutoPlayInterval = setInterval(() => {
        languagesSlideIndex++;
        languagesShowSlide(languagesSlideIndex);
      }, 3000); // Cambia cada 3 segundos
      languagesPlayBtn.textContent = "Pause";
    }
  };

  window.languagesToggleFullscreen = function() {
    const container = document.querySelector('.languages-slideshow-container');
    const fullscreenBtn = document.getElementById('languages-fullscreen-btn');
    
    if (!document.fullscreenElement) {
      container.requestFullscreen().then(() => {
        container.classList.add('fullscreen');
        fullscreenBtn.textContent = 'Salir';
      }).catch(err => {
        container.classList.add('fullscreen');
        fullscreenBtn.textContent = 'Salir';
      });
    } else {
      document.exitFullscreen().then(() => {
        container.classList.remove('fullscreen');
        fullscreenBtn.textContent = 'Pantalla completa';
      });
    }
  };

  document.addEventListener('fullscreenchange', function() {
    const container = document.querySelector('.languages-slideshow-container');
    const fullscreenBtn = document.getElementById('languages-fullscreen-btn');
    if (!document.fullscreenElement) {
      container.classList.remove('fullscreen');
      fullscreenBtn.textContent = 'Pantalla completa';
    }
  });

  languagesShowSlide(languagesSlideIndex);
})();
</script>
