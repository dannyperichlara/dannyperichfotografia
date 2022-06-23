<template>
  <div>
    <Header />
      
    <div class="">
      <div class="row p-4 pb-0 pe-lg-0 pt-0 align-items-center rounded-3 shadow-lg">
        <div class="col-lg-7 p-3 p-lg-5 pt-lg-3">
          <h1 class="price fw-bold lh-1">Retratos atemporales</h1>
          <p class="lead">&#8220;Mi trabajo está basado en la idea de que una fotografía no puede estar asociada sólo a una época. Las fotos deben ser capaces de traspasar la barrera del tiempo, al punto en que, cuando las personas vean tus fotos en el futuro, sean incapaces de distinguir cuándo fueron tomadas&#8221;. (Danny Perich L.)</p>
          <div class="d-grid gap-2 d-md-flex justify-content-md-start mb-4 mb-lg-3">
            <b-button target="_blank" href="https://wa.me/56992948450?text=Hola,%20Danny.%20Me%20gustar%C3%ADa%20agendar%20una%20sesi%C3%B3n%20de%20fotos." type="button" variant="primary" class="btn btn-primary btn-lg px-4 me-md-2 fw-bold">Agenda tu Sesión de Fotos</b-button>
            <b-button href="#cursos" type="button" variant="dark" class="btn btn-outline-secondary btn-lg px-4 ml-1">Aprende Fotografía</b-button>
          </div>
        </div>
        <div class="col-lg-4 offset-lg-1 p-0 overflow-hidden shadow-lg text-center">
            <img class="rounded-lg-3" src="/images/fotos/01.jpg" alt="" width="100%"><br>
            <span class="small">Modelo: Alexandra Vásquez (<a target="_blank" href="https://instagram.com/ohglitterboo">@ohglitterboo</a>)</span>
        </div>
      </div>
    </div>

    <span v-for="(image, index) in images" class="thumb-item" href="#" @click="visiblePhoto = index" :key="index">
      <img :src="image.thumbSrc" width="25%"/>
    </span>

    <div id="agendar"></div>
    <div class="row p-4 pb-0 pe-lg-0 pt-lg-5 align-items-center rounded-3 shadow-lg">
      <div class="col-lg-7 p-3 p-lg-5 pt-lg-3">
        <h1 class="price fw-bold lh-1">Agenda tu sesión</h1>
        <p class="lead">Contáctate diréctamente conmigo para agendar una sesión. Las sesiones pueden ser tanto en estudio como exterior, con iluminación de estudio o luz natural. Revisa los planes que tengo disponibles; si las condiciones te parecen bien, me escribes y agendamos.</p>
        <div class="d-grid gap-2 d-md-flex justify-content-md-start mb-4 mb-lg-3">
          <b-button variant="primary" target="_blank" href="https://wa.me/56992948450?text=Hola,%20Danny.%20Me%20gustar%C3%ADa%20agendar%20una%20sesi%C3%B3n%20de%20fotos." type="button" class="btn btn-primary btn-lg px-4 me-md-2 fw-bold">Agenda tu Sesión de Fotos</b-button>
          <!-- <button href="#tienda" type="button" class="btn btn-outline-secondary btn-lg px-4">Ver Tarifas</button> -->
        </div>
      </div>
      <div class="col-lg-4 offset-lg-1 p-0 overflow-hidden shadow-lg">
          <img class="rounded-lg-3" src="/images/fotos/14.jpg" alt="" width="100%"><br>
      </div>
      <b-container>
      <b-card-group deck class="text-center">
        <b-card bg-variant="dark" header-tag="header" footer-tag="footer">
          <p><span class="price">$48.800</span> / por sesión</p>
          <template #header>
            <h6 class="mb-0 lead">Sesión Express</h6>
          </template>
          <b-card-text>
            Sesión de <b>45</b> minutos<br>
            2 vestuarios<br>
            En estudio con luz artificial y natural<br>
            Entrega de <b>15 fotos</b><br>
            Foto extra <b>$2.800</b><br>
          </b-card-text>
          <b-button target="_blank" href="https://wa.me/56992948450?text=Hola,%20Danny.%20Me%20gustar%C3%ADa%20agendar%20una%20sesi%C3%B3n%20de%20fotos." class="w-100" variant="primary">Agendar sesión</b-button><br>
          <b-button href="/galeria/express" class="btn-outline-secondary mt-1 w-100" variant="dark">Ver ejemplos</b-button>
          <!-- <template #footer>
            <em>Ver ejemplos de sesiones en esta modalidad</em>
          </template> -->
        </b-card>

        <b-card bg-variant="dark" header-tag="header" footer-tag="footer">
          <p><span class="price">$85.000</span> / por sesión</p>
          <template #header>
            <h6 class="mb-0 lead">Sesión Normal</h6>
          </template>
          <b-card-text>
            Sesión de <b>90</b> minutos<br>
            Sin restricción de vestuarios<br>
            En estudio con luz artificial y natural<br>
            En los alrededores del estudio<br>
            Entrega de <b>25 fotos</b><br>
            Foto extra <b>$2.500</b><br>
          </b-card-text>
          <b-button target="_blank" href="https://wa.me/56992948450?text=Hola,%20Danny.%20Me%20gustar%C3%ADa%20agendar%20una%20sesi%C3%B3n%20de%20fotos." class="w-100" variant="primary">Agendar sesión</b-button><br>
          <b-button href="/galeria/normal" class="btn-outline-secondary mt-1 w-100" variant="dark">Ver ejemplos</b-button>
          <!-- <template #footer>
            <em>Ver ejemplos de sesiones en esta modalidad</em>
          </template> -->
        </b-card>

        <b-card bg-variant="dark" header-tag="header" footer-tag="footer">
          <div class="ribbon-corner ribbon-fold">Popular</div>
          <p><strike style="opacity: 0.6;">$110.000</strike><br><span class="price">$96.000</span> / por sesión</p>
          <template #header>
            <h6 class="mb-0 lead">Sesión Beauty</h6>
          </template>
          <b-card-text>
            <p class="list"><b>Incluye maquillaje</b></p>
            <p class="list">Sesión de <b>90</b> minutos, más el tiempo de preparación de maquillaje y vestuario</p>
            <p class="list">Sin restricción de vestuarios</p>
            <p class="list">En estudio con luz artificial y natural</p>
            <p class="list">En los alrededores del estudio</p>
            <p class="list">Incluye asistencia en vestuario, pose y cuidado previo a la sesión</p>
            <p class="list">Incluye telas y accesorios</p>
            <p class="list">Para sesión de embarazo, incluye vestidos</p>
            <p class="list">Entrega de <b>25 fotos</b></p>
            <p class="list">Foto extra <b>$2.500</b></p>
          </b-card-text>
          <b-button target="_blank" href="https://wa.me/56992948450?text=Hola,%20Danny.%20Me%20gustar%C3%ADa%20agendar%20una%20sesi%C3%B3n%20de%20fotos." class="w-100" variant="primary">Agendar sesión</b-button><br>
          <b-button href="/galeria/extendida" class="btn-outline-secondary mt-1 w-100" variant="dark">Ver ejemplos</b-button>
          <!-- <template #footer>
            <em>Ver ejemplos de sesiones en esta modalidad</em>
          </template> -->
        </b-card>
      </b-card-group>
      </b-container>
    </div>

    <div id="cursos"></div>
    <div class="row p-4 pb-0 pe-lg-0 pt-lg-5 align-items-center rounded-3 shadow-lg">
      <div class="col-lg-7 p-3 p-lg-5 pt-lg-3">
        <h1 class="price fw-bold lh-1">Aprende fotografía</h1>
        <p class="lead">Si te interesa la fotografía, aprende con mis cursos presenciales, online o grabados. A diferencia de otros cursos, los míos se enfocan en la composición e iluminación, y no tanto en la configuración de cámara o la edición. La idea es que tus fotos salgan perfectas de tu cámara (cualquier ésta sea) sin depender del gasto en tecnología y sin estar horas arreglando una foto deficiente.</p>
        <div class="d-grid gap-2 d-md-flex justify-content-md-start mb-4 mb-lg-3">
          <b-button href="/tienda" variant="primary" type="button" class="btn btn-primary btn-lg px-4 me-md-2 fw-bold">Ver Cursos disponibles</b-button>
          <!-- <button href="#tienda" type="button" class="btn btn-outline-secondary btn-lg px-4">Ver Tarifas</button> -->
        </div>
      </div>
      <div class="col-lg-4 offset-lg-1 p-0 overflow-hidden shadow-lg">
          <img class="rounded-lg-3" src="/images/curso-main-photo.jpg" alt="" width="100%"><br>
      </div>
    </div>
    <Footer />
  </div>
</template>

<script>
export default {
  name: 'IndexPage',

  head() {
    return {
      title: 'Danny Perich Fotografía - Retratos atemporales'
    }
  },

  components: {
    // PhotoGallery
  },

  data() {
    return {
      images: [
        {
          src: "/images/fotos/01.jpg",
          thumbSrc: "/images/thumbs/01.jpg",
          w: 1512,
          h: 2000
        },
        {
          src: "/images/fotos/02.jpg",
          thumbSrc: "/images/thumbs/02.jpg",
          w: 3654,
          h: 5473
        },
        {
          src: "/images/fotos/04.jpg",
          thumbSrc: "/images/thumbs/04.jpg",
          w: 3262,
          h: 4920
        },
        {
          src: "/images/fotos/03.jpg",
          thumbSrc: "/images/thumbs/03.jpg",
          w: 3262,
          h: 4920
        },
        {
          src: "/images/fotos/05.jpg",
          thumbSrc: "/images/thumbs/05.jpg",
          w: 3262,
          h: 4920
        },
        {
          src: "/images/fotos/12.jpg",
          thumbSrc: "/images/thumbs/12.jpg",
          w: 2316,
          h: 2316
        },
        {
          src: "/images/fotos/06.jpg",
          thumbSrc: "/images/thumbs/06.jpg",
          w: 3262,
          h: 4920
        },
        {
          src: "/images/fotos/07.jpg",
          thumbSrc: "/images/thumbs/07.jpg",
          w: 3262,
          h: 4920
        },
        {
          src: "/images/fotos/08.jpg",
          thumbSrc: "/images/thumbs/08.jpg",
          w: 3593,
          h: 4920
        },
        {
          src: "/images/fotos/09.jpg",
          thumbSrc: "/images/thumbs/09.jpg",
          w: 1431,
          h: 2000
        },
        {
          src: "/images/fotos/10.jpg",
          thumbSrc: "/images/thumbs/10.jpg",
          w: 1335,
          h: 2000
        },
        {
          src: "/images/fotos/11.jpg",
          thumbSrc: "/images/thumbs/11.jpg",
          w: 1367,
          h: 2048
        }
      ],
      visiblePhoto: null
    };
  }
}
</script>

<style>
  body {
    background-color: black;

    color: #EEE;
  }

  .price {
    font-size: 2.5rem;
  }

  .ribbon-corner {background-color: #1f44ff;
    display: flex;
    text-align: center;
    align-items: center;
    justify-content: center;
    color: #fff;
    position: absolute;
    box-sizing: border-box;
    top: 0;
    right: 0;
    -webkit-clip-path: var(--tor-ribbon-polygon);
    clip-path: var(--tor-ribbon-polygon);
    transform: rotate(var(--tor-ribbon-rotate)) translateY(var(--tor-ribbon-translateY)) translateX(var(--tor-ribbon-translateX)) !important;
    transform-origin: var(--tor-ribbon-origin) !important;
    width: calc( (var(--tor-ribbon-size) + 1em) * 2);
    height: 2em;

    --tor-ribbon-size: 3em;
    --tor-ribbon-rotate: 45deg;
    --tor-ribbon-translateX: 50%;
    --tor-ribbon-translateY: calc((var(--tor-ribbon-size) + 1em) - 100%);
    --tor-ribbon-origin: 100% 0%;
    --tor-ribbon-polygon: polygon(0% 100%, 50% calc(100% - (var(--tor-ribbon-size) + 1em)), 100% 100%);
  }

  .ribbon-corner.ribbon-fold {
    --tor-ribbon-polygon: polygon(0% 100%, 50% calc(100% - (var(--tor-ribbon-size) + 1em)), 100% 100%, 100% calc(100% + 0.5em), 0% calc(100% + 0.5em));
    margin: -0.34em;
}

.list {
  margin-bottom: 12px;
  line-height: 1.2rem;
}
</style>