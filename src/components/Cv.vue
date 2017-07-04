<template>
  <div class="row">
    <div class="col s9 m9 l9 info">
      <h3>Estudiante de la Carrera de Ingeneria en Sistemas Computacionales-UNITEC</h3>
      <p>Alta capacidad de trabajo en equipo, responsable, leal, respetuoso de las normas eticas y morales, con una muy destacable formacion en valores humanos. Motivado por proyectos y retos que impliquen superacion tanto humana como profesional.</p>
      <hr>
      <h3>Educacion Universitaria</h3>
      <p>Enero 2013
        <blockquote>Estudiante en la Facultad de Ingeniería en la Carreara Ingeniería en Sistemas Computacionales.</blockquote>
      </p>
      <p>
        Centro de Estudios
        <blockquote> Universidad Tecnológica Centroamericana (UNITEC).</blockquote>
      </p>
      <div class="row">
        <div class="col s6 m6 l6">

          <h3>Educacion Secundaria</h3>
          <p>Noviembre 2012
            <blockquote>Bachillerato en Ciencias Y Letras </blockquote>
          </p>
          <p>
            Centro de Estudios
            <blockquote>Centro Escolar Aldebarán</blockquote>
          </p>
        </div>
        <div class="col s6 m6 l6">

          <h3>Educacion Primaria</h3>
          <p>Noviembre 2008
            <blockquote>6to grado</blockquote>
          </p>
          <p>
            Centro de Estudios
            <blockquote>Centro Escolar Aldebarán</blockquote>
          </p>
        </div>
      </div>

      <div class="row">
        <div class="col s6 m6 l6">

          <h3>Idiomas</h3>
          <li>Español-Lengua Madre</li>
          <li>Inglés-Nivel Avanzado</li>
          <li>Mandarín- Básico</li>
        </div>
        <div class="col s6 m6 l6">

          <h3>Cursos de Interes</h3>
          <p>Abril 2013
            <blockquote>Curso sobre Creación de Videojuegos en UNITY (UNITEC).</blockquote>
          </p>
          <p>Marzo 2013
            <blockquote>Curso sobre Armado de Computadoras (UNITEC).</blockquote>
          </p>
          <p>Septiembre 2014
            <blockquote>Taller sobre GIT y GITHUB (UNITEC).</blockquote>
          </p>
          <p>Noviembre 2015
            <blockquote>Primer HackTegus Ideas para mi Capital.</blockquote>
          </p>
          <p>Marzo 2016
            <blockquote>Introducción al Adobe Ilustrator(UNITEC).</blockquote>
          </p>
        </div>
      </div>
      <div class="row">
        <div class="col s6 m6 l6">

          <h3>Conocimientos</h3>
          <li>Microsoft Word</li>
          <li>Excel</li>
          <li>Power Point</li>
          <li>Access</li>
          <li>JAVA</li>
          <li>C/C++</li>
          <li>SQL Server</li>
          <li>MYSQL</li>
          <li>HTML</li>
          <li>CSS</li>
          <li>JavaScript</li>
          <li>Node.js</li>
          <li>Vue.js</li>
          <li>Android Studio.</li>
        </div>
        <div class="col s6 m6 l6">

          <h3>Actividades Extracurriculares</h3>
          <li>Instructor de niños (8-12 años) y jóvenes (13-16 años) Centro de Educación Complementaria Espavel.</li>
          <li>Visitas de solidaridad a centros de cuidado de adulto mayor. (Espavel).</li>
          <li>Equipo de voleibol en Aldebarán.</li>
          <li>Trabajo Educativo Social (Escuela Villa Olímpica).</li>
          <li>Conservatorio Amadeus.</li>
          <li>Natación en Agua Segura.</li>
          <li>Tutorías personales.</li>
          <li>Horas de vinculación en (UNITEC).</li>
          <li>Miembro IEEE (Agosto 2016).</li>
          <li>Presidente PES (Power & Energy Society) rama estudiantil UNITEC (septiembre 2016).</li>
        </div>
      </div>

    </div>
    <div class="col s3 m3 l3 nav">
      <div class="colNav">
        <div class="sideNav">
          <div class="brand">
            Curriculum Vitae
          </div>
          <ul>
            <li><img src="./image/miguel_ardon.jpg" alt="miguel_ardon"></li>
            <li><p>Miguel Angel Ardon Enriquez</p></li>
            <li>ID:<p>0801-1995-08131</p></li>
            <li>Fecha de Nacimiento:<p>16 de abril de 1995</p></li>
            <li>Edad:<p>22 años</p></li>
            <li>Estado Civil:<p>Soltero</p></li>
            <li>Nacionalidad:<p>hondureña</p></li>
            <li>Direccion:<p>Altos de Miraflores Sur bloque W casa 3A</p></li>
            <li>Telefono/Celular:<p>+504 2271-1072/+504 9523-6806</p></li>
            <li>Correo electronico:<p id="correo"><a href="mailto:miguel.ardonenriquez@gmail.com">miguel.ardonenriquez@gmail.com</a></p></li>
          </ul>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
}
</script>

<style scoped>

template{
  font-family: 'Roboto', sans-serif;
}

.info{
  margin-right: 0%;
}
.nav{
  padding-right: 0;
}

.colNav{
  right: 0px;
  padding-left: 0;
  padding-right: 0;
  position: static;
  top:0;
}

.brand{
  font-size: 30px;
  padding-left: 15%;
}

.sideNav{
  font-size: 150%;
  background-color: #ffa54c;
  top: 0px;
  height: 1700px;
  color: rgb(0, 0, 0);
}

.sideNave ,ul ,li{
  padding-left: 10%;
}

.sideNave, p{
  font-weight: bold;
}

a{
  font-size: 75%;
  padding-left: 0%;
  color: black;
}

#correo{
  padding-left: 0%;
}

h3{
  color: #ffa54c;
}

hr{
  background-color: #fff;
	border-top: 2px dashed #8c8b8b;
}
</style>
