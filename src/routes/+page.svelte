<main>
  <div class="logo-container">
    <img src="/logo.png" alt="logo" />
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
      Somos una firma legal dedicada exclusivamente al asesoramiento y al
      litigio tributario. Estamos enfocados en brindar nuestro servicio
      profesional personalizado, con exigentes estándares de calidad, lo que nos
      permite alcanzar excelentes resultados y altos niveles de satisfacción de
      nuestros clientes. La tributación nacional, provincial y municipal, en sus
      diversas expresiones, nos ocupan cotidianamente, laboral y académicamente.
    </p>
    <img src="/pic01.jpg" alt="pic01" />
  </section>
  <section class="socios">
    <h1 class="text-style-1">Socios</h1>
    <div class="divider">
      <div class="text-style-2">
        <h2 class="text-style-1">Enrique Bulit Goñi</h2>
        <img src="/Bulit.jpg" alt="Bulit" />
        <a href="/socios#enrique-bulit-goni">Más información</a>
      </div>
      <div class="text-style-2">
        <h2 class="text-style-1">Rodrigo Lema</h2>
        <img src="/Lema.jpg" alt="Lema" />
        <a href="/socios#rodrigo-lema">Más información</a>
      </div>
    </div>
  </section>
  <section class="contacto">
    <h1 class="text-style-1">Contacto</h1>
    <div class="divider">
      <div class="text-style-2">
        <form class="text-style-1">
          <label for="name">Nombre completo</label>
          <input type="text" id="name" />
          <label for="email">Correo electrónico</label>
          <input type="email" id="email" />
          <label for="message">Mensaje</label>
          <textarea id="message"/>
          <button type="submit">Enviar mensaje</button>
        </form>
      </div>
      <div class="text-style-1 contact-info">
        <div>Direccion</div>
        <div>Telefono</div>
        <div>Email</div>
      </div>
    </div>
  </section>
  <footer>
    <div class="text-style-1">
      <div>© 2024 BULIT GOÑI | LEMA abogados</div>
    </div>
  </footer>
</main>

<style>
  main {
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: flex-start;
    height: 100vh;
    max-width: 72em;
    width: calc(100% - 4rem);
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
    transition:
      background-color 0.2s ease-in-out,
      color 0.2s ease-in-out;
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

  h2 {
    text-align: center;
    font-size: 1.75rem;
    line-height: 1.3rem;
    margin-bottom: 1.5rem;
  }

  section {
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
    flex-grow: 1;
    width: 100%;
    background-color: white;
    box-sizing: border-box;
  }

  section.presentation > p {
    padding: 6rem 8rem;
    font-style: italic;
    text-align: center;
  }

  section.socios {
    & img {
      margin: 2.5rem 0;
    }
  }

  div.divider {
    display: flex;
    flex-direction: row;
    align-items: center;
    justify-content: center;
    width: 100%;
    box-sizing: border-box;
    height: max-content;
    border: 2px solid rgb(200, 200, 200);
    & > div {
      display: flex;
      flex-direction: column;
      align-items: center;
      justify-content: center;
      width: 50%;
      box-sizing: border-box;
      padding: 4rem;
      border: 1px solid rgb(200, 200, 200);

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

  section.contacto {
    background-color: #dddddd;
  }
  
  form {
    display: flex;
    flex-direction: column;
    text-align: left;
    justify-content: center;
    color: rgb(113, 121, 129);
    width: 100%;
    box-sizing: border-box;
    font-size: 0.8rem;
    & input {
      width: 100%;
      margin: 0.5rem 0;
      padding: 0.5rem;
      height: 2rem;
      border: 2px solid rgb(200, 200, 200);
      background-color: transparent;
    }
    & textarea {
      width: 100%;
      margin: 0.5rem 0;
      padding: 0.5rem;
      border: 2px solid rgb(200, 200, 200);
      background-color: transparent;
      resize: none;
      height: 8rem;
    }
    & button {
      width: max-content;
      margin-top: 2rem;
      padding: 1rem 2rem;
      border: 2px solid rgb(144, 148, 152);
      background-color: transparent;
    }
  }
  .contact-info {
    color: rgb(113, 121, 129);
    font-size: 0.8rem;
    width: 100%;
    height: 100%;
    padding: 0 !important;
    & > div {
      width: 100%;
      padding: 4rem;
      box-sizing: border-box;
      border: 1px solid rgb(200, 200, 200);
      flex-grow: 1;
    }
  }
  footer {
    display: flex;
    flex-direction: row;
    align-items: center;
    justify-content: center;
    width: 100%;
    padding: 2rem;
    box-sizing: border-box;
    font-size: 0.8rem;
    color: white;
    opacity: 0.5;
  }
</style>
