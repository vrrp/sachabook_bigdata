
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

# **1. Introducción**
<a name="s0"></a>
%---------------------------------------------------------------------------------------------------
En los últimos años las empresas se han embarcado en un proceso de transformación
digital de profundo calado dentro del marco de lo que se conoce como la cuarta
revolución industrial, que esta dando paso a una nueva manera de organizar los medios
de producción.

<a style="color:blue">El resultado de esta tormenta perfecta en la que se halla todas las organizaciones es una
explosión del dato en volumen, velocidad y variedad. Y de modo natural ha crecido la
complejidad para capturar, procesar, almacenar, analizar y visualizar datos.</a>

Como resultado, han aparecido múltiples métodos, técnicas y tecnologías que buscan ayudar a las 
organizaciones a tomar mejores decisiones a partir de los datos y a extraer valor de estos. Estos métodos, técnicas
y tecnologías para la captura, el procesamiento, el almacenamiento, la gestión y el análisis se han
ido progresivamente estructurando en diferentes estrategias que conocemos como bíg data.

Aunque este concepto  ya lleva años en el mercado y existen múltiples casos de uso conocido,
las organizaciones siguen teniendo problemas para conocer el impacto y el valor de big data, y sobre todo para 
poner en marcha estos sistemas de información. Existen todavía múltiples preguntas:

1. Nuevo contexto

- Naturaleza del dato 1.2.1

* Que es big data?
* Qué significa para mi organizació?
* Cuándo es relevante?
* Está preparada mi organización?
* Como desplegar con éxito este tipo de iniciativas?
* Qué barreras presenta este tipo de proyectos?
* Que tecnologías existen dentro de big data?
* Cómo empiezo un proyecto?

**Data warehouse -o almacén de datos**

Se entiende por **data Warehouse** el repositorio de datos que
proporciona una visión global, común e integrada de los datos de la organización,
independiente de cómo se vayan a utilizar posteriormente por los consumidores o 
usuarios, con las propiedades siguientes: estable, coherente,fiable y con información
histórica

**Business inteligence -o inteligencia de negocio (BI)**

Se entiende por **business intelligence** el conjunto de metodologías, aplicaciones
prácticas y capacidades enfocadas a la creación y administración de información
que permite tomar mejores decisiones a los usuarios de una organización.

<a style="color:purple">Es fácil deducir que el **data werehouse** ha sido el componente principal para el
almacenamiento de datos y el **BI** lo ha sido para su explotación.</a>

Aparición de más fuentes que producen y consumen datos; de una mayor incorporación de usuairios
a internet; del despliegue de una mayor cantidad de dispositivos inteligentes, y del continuo
desarrollo de soluciones y servicios digitales.

<a style="color:purple">Esta explosión de datos está caracterizada por un crecimiento en las magnitudes físicas
del dato: **volumen, variedad y velocidad** (las 3 V del big data). Se crea un mayor volumen de datos, provenientes de una mayor variedad
de fuentes, representados en múltiples formatos y que se deben capturar y consumir a una mayor velocidad.
Este nuevo paradigma de los datos se conoce frecuentemente como Big Data.</a>

<a style="color:red"> Tecnologías de Big Data: Almacenamiento, procesamiento, análisis y visualización</a>

**Algunas herramientas para big data:** Apache Hadoop, Scikit-learn, Pandas o Caffe

**Dos disciplinas para la visualización de información:** Visualización de datos (data visualization) y data storytelling 
(historias fundadas en datos)



## **I. Big Data**
Es el conjunto de estrategias, tecnologías y sistemas para el almacenamiento, procesamiento, análisis y visualización de conjunto de datos complejos.

### **1.1. Que es Big Data?**
<a name="pre"></a>
%---------------------------------------------------------------------------------------------------
La sociedad ha experimentado una evolución significativa a lo largo del tiempo, marcada por avances tecnológicos y cambios en las necesidades y capacidades humanas.

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


<br><br>
## **II. Introducción a la Computación en la Nube**
<a name="s1"></a>
%---------------------------------------------------------------------------------------------------
Los origenes de la informática y la programación, y cómo evolucionaron para dar forma al mundo digital que conocemos hoy.

% A figure of a photograph of some mountains, followed by a caption
:::{figure} https://github.com/vrrp/sachabook_modulo1/blob/main/docs/images/preambulo/lenguajes_pro.webp?raw=true
:name: fig:historiaLenguajes

:::

### 2.1. Qué es la Computación en la Nube?

<br><br>
## Top 10 lenguajes de programación
<a name="s2"></a>
%---------------------------------------------------------------------------------------------------
Existen índices ([TIOBE](https://www.tiobe.com/tiobe-index/), [PYPL](https://pypl.github.io/ODE.html)) que miden la popularidad de los lenguajes de programación. Su principal utilidad es funcionar como 
un indicador de las tendencias actuales en el mundo de la programación, ayudando a desarrolladores y empresas
a tomar decisiones informadas sobre qué lenguajes aprender, enseñar o utilizar en nuevos proyectos.

:::{figure} https://github.com/vrrp/sachabook_modulo1/blob/main/docs/images/preambulo/pypl.jpg?raw=true
:name: fig:pyplRanking

:::
<br><br>
## Ecosistema Python
<a name="s3"></a>
%---------------------------------------------------------------------------------------------------
El ecosistema Python es el conjunto de herramientas, bibliotecas, marcos de trabajo (frameworks) y la comunidad de desarrolladores que rodean al lenguaje de programación Python. Este ecosistema se caracteriza por su vastedad y la gran cantidad de recursos de código abierto, lo que permite a Python ser utilizado en una amplia variedad de campos, como el desarrollo web, la ciencia de datos, el aprendizaje automático y la informática científica. 

% A figure of a photograph of some mountains, followed by a caption
:::{figure} https://github.com/vrrp/sachabook_modulo1/blob/main/docs/images/preambulo/ecosistema.png?raw=true
:name: fig:mountains
:align: center

:::
<br><br>
## Aplicaciones con Python
<a name="s4"></a>
%---------------------------------------------------------------------------------------------------
Python se utiliza para una gran variedad de aplicaciones debido a su versatilidad y a su extenso ecosistema. A continuación, se detallan algunas de las más importantes.
% A figure of a photograph of some mountains, followed by a caption
:::{figure} https://github.com/vrrp/sachabook_modulo1/blob/main/docs/images/preambulo/python_app.png?raw=true
:name: fig:pythonEcosistema
:align: center

:::



## Automatización de procesos
%<a name="s4"></a>
%---------------------------------------------------------------------------------------------------
%fabrica automatizada de tesla
<div class="responsive-video-container">
    <iframe src="https://www.youtube.com/embed/WYnOGAvQEgk?si=Ii5Hib0Wqff3t_15" title="YouTube video player - Fábrica automatizada de Tesla" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
</div>

% Data center automatizado
<div class="responsive-video-container">
    <iframe src="https://www.youtube.com/embed/YkctZlQgU0g?si=RgrtJYMFfJqO0s2K" title="YouTube video player - Data center automatizado" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
</div>

<style>
/* CSS para videos responsivos */
.responsive-video-container {
    position: relative;
    width: 100%;
    height: 0;
    padding-bottom: 56.25%; /* Aspect ratio 16:9 */
    margin: 20px 0;
    border-radius: 8px;
    overflow: hidden;
    box-shadow: 0 4px 8px rgba(0,0,0,0.2);
}

.responsive-video-container iframe {
    position: absolute;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
    border: none;
}

/* Media queries para diferentes dispositivos */
/* Celulares pequeños */
@media screen and (max-width: 480px) {
    .responsive-video-container {
        margin: 15px 0;
        border-radius: 6px;
    }
}

/* Tablets */
@media screen and (min-width: 481px) and (max-width: 768px) {
    .responsive-video-container {
        max-width: 90%;
        margin: 20px auto;
    }
}

/* Laptops */
@media screen and (min-width: 769px) and (max-width: 1024px) {
    .responsive-video-container {
        max-width: 80%;
        margin: 25px auto;
    }
}

/* PCs y pantallas grandes */
@media screen and (min-width: 1025px) {
    .responsive-video-container {
        max-width: 70%;
        margin: 30px auto;
    }
}

/* Pantallas ultra grandes */
@media screen and (min-width: 1440px) {
    .responsive-video-container {
        max-width: 60%;
        margin: 35px auto;
    }
}
</style>
