<main>
  <div class="logo-container">
    <img src="/logo.png" alt="logo"/>
  </div>
  <nav class="text-style-1">
    <span class="active">El estudio</span>
    <span>Socios</span>
    <span>Misión, visión, valores</span>
    <span>Areas de práctica</span>
    <span>Clientes</span>
    <span>Contacto</span>
  </nav>
  <section class="presentation">
    <h1 class="text-style-1">Qué hacemos</h1>
    <p class="text-style-2">
      Somos una firma legal dedicada exclusivamente al asesoramiento y al litigio tributario. Estamos enfocados en brindar nuestro servicio profesional personalizado, con exigentes estándares de calidad, lo que nos permite alcanzar excelentes resultados y altos niveles de satisfacción de nuestros clientes. La tributación nacional, provincial y municipal, en sus diversas expresiones, nos ocupan cotidianamente, laboral y académicamente. 
    </p>
    <img src="/pic01.jpg" alt="pic01"/>
  </section>
  <section class="socios">
    <h1 class="text-style-1">Socios</h1>
    <div class="divider">
      <div class="text-style-2">
        <h2 class="text-style-1">Enrique Bulit Goñi</h2>
        <img src="/Bulit.jpg" alt="Bulit"/>
        <a href="/socios#enrique-bulit-goni">Más información</a>
      </div>
      <div class="text-style-2">
        <h2 class="text-style-1">Rodrigo Lema</h2>
        <img src="/Lema.jpg" alt="Lema"/>
        <a href="/socios#rodrigo-lema">Más información</a>
      </div>
    </div>
  </section>
</main>

<style>
  main {
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: flex-start;
    height: 100vh;
    /* margin: 6rem; */
    max-width: 72rem;
    margin: auto;
    box-sizing: border-box;
  }
  nav {
    display: flex;
    flex-direction: row;
    align-items: center;
    justify-content: center;
    width: 100%;
    font-size: 0.8rem;
  }

  nav > span {
    padding: 1.5rem;
    background-color: rgba(255, 255, 255, 0.175);
    flex-grow: 1;
    text-align: center;
    color: white;
    transition: background-color 0.2s ease-in-out, color 0.2s ease-in-out;
  }

  nav > span.active {
    background-color: white;
    color: #212931;
  }

  nav > span:hover {
    background-color: rgba(255, 255, 255, 0.3);
  }

  img {
        width: 100%;
        height: auto;
  }

  h1 {
    font-size: 4rem;
  }
  
  section.presentation {
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
    flex-grow: 1;
    width: 100%;
    background-color: white;
    padding: 6rem 8rem;
    box-sizing: border-box;
    & p {
      font-style: italic;
      text-align: center;
    };
  }

  section.socios {
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
    flex-grow: 1;
    width: 100%;
    background-color: white;
  }

  section.socios > div.divider {
    display: flex;
    flex-direction: row;
    align-items: center;
    justify-content: center;
    width: 100%;
    box-sizing: border-box;
    background-color: white;
    & div {
      display: flex;
      flex-direction: column;
      align-items: center;
      justify-content: center;
      width: 50%;
      box-sizing: border-box;
      padding: 4rem;
      border: 1px solid rgb(200, 200, 200);
      & h2 {
        text-align: center;
        text-transform: uppercase;
      };
      & a {
        color: #212931;
        text-decoration: none;
        border-bottom: 1px dashed #212931;
      }
    }
  }
  div.logo-container {
    padding: 4rem;
    margin-bottom: 6rem;
  }
</style>