<style>
  .main_container {
    display: flex;
    flex-direction: column;
    margin-top: 20px;
    font-family: sans-serif;
  }

  .first_section_container {
    display: flex;
    align-items: center;
    gap: 40px;
  }

  .main_text {
    font-weight: bold;
  }

  .main_photo {
    width: 300px;
    border-radius: 40px;
    border: 3px gray solid; 
  }

  .skills_container {
    display: flex;
    flex-direction: column;
    align-items: center;
  }

  .skills_title {
    font-size: 30px;
  }

  .skills_image_container {
    display: flex;
    gap: 15px;
    flex-wrap: wrap;
    justify-content: center;
  }

  .skill_container {
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: space-between;
    width: 95px;
    padding-bottom: 15px;
  }

  .skill_image {
    max-width: 70px;
    max-height: 70px;
  }

  .skill_span{
    font-weight:
    bold;margin-top: 5px;
  }

  .next_express_container{
    height: 70px;
    display: flex;
    align-items: center;
    background-color: black;
    width: 70px;
    justify-content: center;
    border-radius: 5px;
  }

  .next_express_img{
    max-width: 65px;
    max-height: 70px;
  }

  .css_frames_cont {
    height: 75px;
    display: flex;
    align-items: center;
  }

  .know_me_container{
    display: flex;
    flex-direction: column;
    align-items: center;
  }

  .know_me_title {
    font-size: 30px;
  }

  .know_me_buttons {
    display: flex;
    gap: 30px;
    flex-wrap: wrap;
    justify-content: center;
  }

  .know_me_button {
    background-color: white;
    border: 5px solid gray;
    border-radius: 20px;
    display: flex;
    align-items: center;
    gap: 15px;
    text-decoration: none;
    color: black;
    transform: scale(1);
    transition: transform 0.2s;
    width: 200px;
    justify-content: center;
  }

  .icon_portfolio {
    height: 40px;
  }

  .span_button{
    font-weight: bolder;
    font-size: 25px;
  }

  .icon_linkedin {
    height: 32px;
  }

  .email_button {
    background-color: white;
    border: 5px solid gray;
    border-radius: 20px;
    display: flex;
    align-items: center;
    gap: 15px;
    padding: 5px;
    text-decoration: none;
    color: black;
    width: 430px;
    justify-content: center;
    margin: 25px 0;
  }

  .email_icon {
    height: 27px;
  }

  .email_span {
    font-weight: bolder;
    font-size: 25px;
  }
</style>

<div class="main_container">
    <div class="first_section_container">
      <p class="main_text">
        Hola, soy Camilo Gil, un desarrollador web full stack e ingeniero mecánico de Bogotá, Colombia. Como ingeniero
        mecánico,
        tengo una alta capacidad de resolución de problemas, y como desarrollador web, puedo crear aplicaciones
        interactivas,
        versátiles y altamente escalables. Me encanta aprender y siempre busco expandir mis habilidades y conocimientos
        en
        el
        campo de la ingeniería y el desarrollo web. Trabajo en equipo y valoro la colaboración para lograr resultados
        excepcionales en cada proyecto que emprendo.
      </p>
      <img src="./foto.png" alt="foto" class="main_photo">
    </div>
    <div class="skills_container">
      <h2 class="skills_title">Habilidades Técnicas</h2>
      <div class="skills_image_container">
        <div class="skill_container">
          <img src="./JavaScript.png" alt="javascript" class="skill_image">
          <span class="skill_span">JavaScript</span>
        </div>
        <div class="skill_container">
          <img src="./html.png" alt="javascript" class="skill_image">
          <span class="skill_span">HTML</span>
        </div>
        <div class="skill_container">
          <img src="./CSS.png" alt="javascript" class="skill_image">
          <span class="skill_span">CSS</span>
        </div>
        <div
          class="skill_container">
          <img src="./react.png" alt="javascript" class="skill_image">
          <span class="skill_span">React</span>
        </div>
        <div
          class="skill_container">
          <img src="./reactNative.png" alt="javascript" class="skill_image">
          <span class="skill_span">React Native</span>
        </div>
        <div
          class="skill_container">
          <img src="./node.png" alt="javascript" class="skill_image">
          <span class="skill_span">Node Js</span>
        </div>
        <div
          class="skill_container">
          <img src="./Typescript.png" alt="javascript" class="skill_image">
          <span class="skill_span">TypeScript</span>
        </div>
        <div
          class="skill_container">
          <div class="next_express_container">
            <img src="./next.png" alt="javascript" class="next_express_img">
          </div>
          <span class="skill_span">Next Js</span>
        </div>
        <div
          class="skill_container">
          <div
            class="next_express_container">
            <img src="./express.png" alt="javascript" class="next_express_img">
          </div>
          <span class="skill_span">Express</span>
        </div>
        <div
          class="skill_container">
          <img src="./MongoDB1.png" alt="javascript" class="skill_image">
          <span class="skill_span">Mongo DB</span>
        </div>
        <div
          class="skill_container">
          <img src="./Postgresql.png" alt="javascript" class="skill_image">
          <span class="skill_span">PostgreSQL</span>
        </div>
        <div
          class="skill_container">
          <img src="./Prisma.png" alt="javascript" class="skill_image">
          <span class="skill_span">Prisma</span>
        </div>
        <div
          class="skill_container">
          <div class="css_frames_cont">
            <img src="./sass.png" alt="javascript" class="skill_image">
          </div>
          <span class="skill_span">Sass</span>
        </div>
        <div
          class="skill_container">
          <div class="css_frames_cont">
            <img src="./Tailwind.png" alt="javascript" class="skill_image">
          </div>
          <span class="skill_span">Tailwind</span>
        </div>
        <div
          class="skill_container">
          <div class="css_frames_cont">
            <img src="./Bootstrap.png" alt="javascript" class="skill_image">
          </div>
          <span class="skill_span">Bootstrap</span>
        </div>
        <div
          class="skill_container">
          <img src="./Git.png" alt="javascript" class="skill_image">
          <span class="skill_span">Git</span>
        </div>
      </div>
    </div>
    <div class="know_me_container">
      <h2 class="know_me_title">Conóceme un Poco Mas</h2>
      <div class="know_me_buttons">
        <a href="https://www.camilogilfranco.tech/" target="_blank" class="know_me_button"
          onmouseover="this.style.transform='scale(1.2)';" onmouseout="this.style.transform='scale(1)';">
          <img src="./portfolio.svg" alt="portafolio" class="icon_portfolio">
          <span class="span_button">Portafolio</span>
        </a>
        <a href="https://www.linkedin.com/in/adrian-camilo-gil-franco/" target="_blank"
          class="know_me_button"
          onmouseover="this.style.transform='scale(1.2)';" onmouseout="this.style.transform='scale(1)';">
          <img src="./linkedin_negro.png" alt="portafolio" class="icon_linkedin">
          <span class="span_button">LikedIn</span>
        </a>
      </div>
      <div href="https://www.linkedin.com/in/adrian-camilo-gil-franco/" target="_blank" class="email_button">
        <img src="./mail_negro.png" alt="portafolio" class="email_icon">
        <span class="email_span">camilogilfranco@gmail.com</span>
      </div>
    </div>
  </div>
