<template>
	<div>
		<Header />
		
		<b-container class="mt-5 mb-5">
			<h1 class="display-4">Mejora tus fotos</h1>
			<p>Mejora tu técnica fotográfica, tu capacidad de visualización y tu manejo de la luz, los colores y las poses con los cursos de fotografía que tengo para ofrecerte. Si ya eres fotógrafo, conoce las herramientas de productividad que he desarrollado para facilitar el flujo de tu trabajo fotográfico.</p>
		</b-container>

		<b-container>
			<b-card-group deck class="text-center">
				<b-card style="max-width: 33%" bg-variant="dark" header-tag="header" footer-tag="footer" img-src="/images/presencial-punta-arenas.jpg">
					<p><span class="price">$78.800</span> / por alumno</p>
					<template #header>
						<h6 class="mb-0 lead">Curso Básico PRESENCIAL</h6>
					</template>
					<b-card-text>
						4 clases de 2 horas cada una<br>
						Incluye salida fotográfica al Cementerio de Punta Arenas<br>
						Acceso a material<br>
						8 cupos por curso<br>
						Próxima fecha: POR DEFINIR<br>
					</b-card-text>
					<b-button size="lg" class="w-100" target="_blank" href="" variant="primary">Inscribirme</b-button><br>
					<b-button href="/galeria/express" class="btn-outline-secondary mt-1 w-100" variant="dark">Ver Programa del Curso</b-button>
				</b-card>

				<b-card style="max-width: 33%" bg-variant="dark" header-tag="header" footer-tag="footer" img-src="/images/basico-online.jpg">
					<p class="small mb-4" style="line-height: 1rem"><span class="price">$36.800</span><br>con acceso a consultas y revisiones</p>
					<p class="small mb-5" style="line-height: 1rem"><span class="price">$12.800</span><br>sólo asistencia a clases virtuales</p>
					<template #header>
						<h6 class="mb-0 lead">Curso Básico ONLINE</h6>
					</template>
					<b-card-text>
						4 clases de 2 horas cada una<br>
						8 cupos con derecho a consultas y revisión de ejercicios fotográficos<br>
						40 cupos sólo con derecho a asistir a clases online (sin preguntas ni revisión de ejercicios)<br>
						Incluye salida fotográfica VIRTUAL al Cementerio de Punta Arenas<br>
						Acceso a material<br>
						Próxima fecha: POR DEFINIR<br>
					</b-card-text>
					<b-button size="lg" class="w-100" target="_blank" href="" variant="primary">Inscribirme</b-button><br>
					<b-button href="/galeria/express" class="btn-outline-secondary mt-1 w-100" variant="dark">Ver Programa del Curso</b-button>
				</b-card>

				<b-card style="max-width: 33%" bg-variant="dark" header-tag="header" footer-tag="footer" img-src="/images/retratos-grabado.jpg">
					<p class="lead prelaunch">PRE-LANZAMIENTO</p>
					<p><span class="price"><strike style="font-size:2rem; opacity: 0.6;">$38.800</strike><br>$12.800</span></p>
					<template #header>
						<h6 class="mb-0 lead">Curso de Retratos GRABADO</h6>
					</template>
					<b-card-text>
						12 clases de 1 hora, cada una<br>
						Derecho de revisión y análisis de 1 sesión fotográfica<br>
						Fecha de lanzamiento: Miércoles 6 de julio
					</b-card-text>
					<b-button size="lg" class="w-100" target="_blank" href="" variant="primary">Inscribirme</b-button><br>
					<b-button href="/galeria/express" class="btn-outline-secondary mt-1 w-100" variant="dark">Ver Programa del Curso</b-button>
				</b-card>
			</b-card-group>

			<b-card-group deck class="text-center mt-5">
				<b-card style="max-width: 33%" bg-variant="dark" header-tag="header" footer-tag="footer" img-src="/images/composicion-grabado.jpg">
					<p class="lead prelaunch">PRE-LANZAMIENTO</p>
					<p><span class="price"><strike style="font-size:2rem; opacity: 0.6;">$16.800</strike><br>$6.800</span></p>
					<template #header>
						<h6 class="mb-0 lead">Curso de Composición GRABADO</h6>
					</template>
					<b-card-text>
						4 clases de 1 hora, cada una<br>
						Derecho de revisión y análisis de 1 sesión fotográfica<br>
						Fecha de lanzamiento: Miércoles 6 de julio
					</b-card-text>
					<b-button size="lg" class="w-100" target="_blank" href="" variant="primary">Inscribirme</b-button><br>
					<b-button href="/galeria/express" class="btn-outline-secondary mt-1 w-100" variant="dark">Ver Programa del Curso</b-button>
				</b-card>

				<b-card style="max-width: 33%" bg-variant="dark" header-tag="header" footer-tag="footer" img-src="/images/presets.jpg">
					<p class="lead prelaunch">PRE-LANZAMIENTO</p>
					<p><span class="price"><strike style="font-size:2rem; opacity: 0.6;">$24.800</strike><br>$12.800</span></p>
					<template #header>
						<h6 class="mb-0 lead">Timeless (presets para Lightroom)</h6>
					</template>
					<b-card-text>
						Descarga este conjunto de presets creado para mis propios retratos <em>timeless</em><br>
						Son en total 24 presets, en color y blanco y negro, además de utilidades para generar atractivos efectos con viñetas, grano de película y máxima definición para redes sociales.<br>
						Fecha de lanzamiento: Miércoles 6 de julio
					</b-card-text>
					<b-button target="_blank" href="" variant="primary" class="w-100">Comprar</b-button><br>
					<b-button href="/galeria/express" class="btn-outline-secondary mt-1 w-100" variant="dark">Ver detalle de los Presets</b-button>
				</b-card>

				<b-card style="max-width: 33%" bg-variant="dark" header-tag="header" footer-tag="footer" img-src="/images/edicion-veloz.jpg">
					<p class="lead prelaunch">PRE-LANZAMIENTO</p>
					<p><span class="price"><strike style="font-size:2rem; opacity: 0.6;">$24.800</strike><br>$12.800</span></p>
					<template #header>
						<h6 class="mb-0 lead">Curso de Edición Veloz</h6>
					</template>
					<b-card-text>
						¿Cuántas fotos eres capaz de editar en 1 hora? Duplica ese número con este curso, en el que te enseñaré todos mis trucos para editar más fotos en menos tiempo.
						Fecha de lanzamiento: Miércoles 6 de julio
					</b-card-text>
					<b-button target="_blank" href="" variant="primary" class="w-100">Comprar</b-button><br>
					<b-button href="/galeria/express" class="btn-outline-secondary mt-1 w-100" variant="dark">Ver Programa del Curso</b-button>
				</b-card>
			</b-card-group>
		</b-container>

		<Footer />
	</div>
</template>

<script>
export default {
  name: 'IndexPage',

  head() {
    return {
      title: 'Danny Perich Fotografía - Cursos presenciales, online y grabados de fotografía'
    }
  },
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

	.prelaunch {
		width: 100%;
		background-color: rgb(0, 0, 0);
	}
</style>