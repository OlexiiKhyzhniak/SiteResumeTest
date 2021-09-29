# SiteResumeTest
Check in Web Browser:

https://resumeolexiikhyzhniak.netlify.app

HTML:

<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>My resume</title>

    <link rel="preconnect" href="https://fonts.googleapis.com" />
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin />
    <link
      href="https://fonts.googleapis.com/css2?family=Montserrat:wght@400;700&display=swap"
      rel="stylesheet"
    />
    <link rel="stylesheet" href="css/style.css" />
  </head>

  <body>
    <!-- Main container-->
    <div class="main-container">
      <!-- Main contant section-->
      <div class="main-content-section">
        <!--About me section-->
        <div class="about-me-section">
          <h2 class="about-me-profession">Front-End Developer</h2>
          <h1 class="about-me-name">Olexii Khyzhniak</h1>
          <p class="about-me-description">
            Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do
            eiusmod tempor incididunt ut labore et dolore magna aliqua. Quis
            ipsum suspendisse ultrices gravida. Risus commodo viverra maecenas
            accumsan lacus vel facilisis.
          </p>
        </div>

        <!--My projects section-->
        <div class="my-projects-section">
          <h3 class="main-content-title">Projects</h3>

          <ol class="my-projects-list">
            <li class="my-projects-item">
              <span class="my-projects-text">
                  <a href="https://hellenglish.goit.global/" class="my-projects-link"
                    >https://hellenglish.goit.global/</a>
                  .....
              <span class="my-projects-br">[</span> HTML5, CSS3 <span class="my-projects-br">]</span>
              </span>
            </li>
            <li class="my-projects-item"><span class="my-projects-text">
                  <a href="https://cryptohub.goit.global/" class="my-projects-link">https://cryptohub.goit.global/</a>
                  .......
                  <span class="my-projects-br">[</span> JavaScript <span class="my-projects-br">]</span>
                </span>
            </li>
            <li class="my-projects-item"><span class="my-projects-text">
                  <a href="https://kidslike.goit.global/" class="my-projects-link">https://kidslike.goit.global/</a>
                  .............
                  <span class="my-projects-br">[</span> React.js, Node.js <span class="my-projects-br">]</span>
                </span>
            </li>
          </ol>
        </div>

        <!--My work experience-->
        <div class="my-work-experience-section">
          <h3 class="main-content-title">Work Experience</h3>

          <!--Company 1-->
          <div class="my-work-experience-company-block">
            <h4 class="my-work-experience-position">Front-End Developer <span class="my-work-experience-company">Freelance</span></h4>
            <p class="my-work-experience-period">September 2019 - up to now <span class="my-work-experience-divider">|</span> Country</p>

            <ul class="my-work-experience-duties">
              <li class="my-work-experience-duty">
                Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do
                eiusmod tempor incididunt ut labore et dolore magna aliqua.
              </li>
              <li class="my-work-experience-duty">Lorem ipsum dolor sit amet, consectetur adipiscing elit.</li>
              <li class="my-work-experience-duty">Risus commodo viverra maecenas.</li>
              <li class="my-work-experience-duty">
                Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do
                eiusmod.
              </li>
            </ul>
          </div>

          <!--Company 2-->
          <div class="my-work-experience-company-block"> 
            <h4 class="my-work-experience-position">Manager <span class="my-work-experience-company">Roga & Kopyta New</span></h4>
            <p class="my-work-experience-period">March 2015 - October 2018 <span class="my-work-experience-divider">|</span> Country</p>

            <ul class="my-work-experience-duties">
              <li class="my-work-experience-duty">
                Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do
                eiusmod labore et dolore magna aliqua.
              </li>
              <li class="my-work-experience-duty">Quis ipsum suspendisse ultrices gravida.</li>
              <li class="my-work-experience-duty">Risus commodo viverra maecenas.</li>
            </ul>
          </div>

          <!--Company 3-->
          <div class="my-work-experience-company-block">
            <h4 class="my-work-experience-position">Manager <span class="my-work-experience-company">Roga & Kopyta LLC</span></h4>
            <p class="my-work-experience-period">June 2014 - February 2015 <span class="my-work-experience-divider">|</span> Country</p>

            <ul class="my-work-experience-duties">
              <li class="my-work-experience-duty">Lorem ipsum dolor sit amet, consectetur adipiscing elit.</li>
              <li class="my-work-experience-duty">Quis ipsum suspendisse ultrices gravida.</li>
              <li class="my-work-experience-duty">Risus commodo viverra maecenas.</li>
            </ul>
          </div>
        </div>

        <!--My Education-->
        <div class="my-education-section">
          <h3 class="my-education-header">Education</h3>
          <h4 class="my-education-university">National Technical University of Ukraine
            “Igor Sikorsky Kyiv Polytechnic Institute”</h4>
          <h5 class="education">Telecommunications and radio engineering</h5>
          <p class="my-work-experience-period">September 2009 - June 2014 <span class="my-work-experience-divider">|</span> Country</p>
        </div>
      </div>

      <!--Sidebar section-->
      <aside class="sidebar-section">
        <img class="img" src="img/photo2.jpg" alt="my photo" />

        <!--Contacts section-->
        <div class="contacts-section">
          <h3 class="sidebar-title">Contacts</h3>
          <div>
            <span class="contacts-section-type">C:</span>
            <a class="contacts-section-link" href="tel:+77777777777"
              >+7 777 777 77 77</a
            >
          </div>
          <div>
            <span class="contacts-section-type">E:</span>
            <a
              class="contacts-section-link"
              href="mailto:olexii.khyzhniak@gmail.com">olexii.khyzhniak@gmail.com</a
            >
          </div>
        </div>

        <!--Tech skills section-->
        <div class="tech-skills-section">
          <!--Tech Skills-->
          <h3 class="sidebar-title">Tech Skils</h3>
          <ul class="tech-skills-list">
            <li class="tech-skills-item">
              <span class="item-text">HTML5</span>
            </li>
            <li class="tech-skills-item">
              <span class="item-text">CSS3</span>
            </li>
            <li class="tech-skills-item"><span class="item-text">GIT</span></li>
            <li class="tech-skills-item">
              <span class="item-text">WebPack</span>
            </li>
            <li class="tech-skills-item">
              <span class="item-text">JavaScript</span>
            </li>
            <li class="tech-skills-item">
              <span class="item-text">React.js</span>
            </li>
            <li class="tech-skills-item">
              <span class="item-text">Node.js</span>
            </li>
          </ul>
        </div>

        <!--Soft skills section-->
        <div class="soft-skills-section">
          <h3 class="sidebar-title">Soft Skills</h3>
          <ul class="tech-skills-list">
            <li class="tech-skills-item">
              <span class="item-text">Scrum</span>
            </li>
            <li class="tech-skills-item">
              <span class="item-text">Agile</span>
            </li>
            <li class="tech-skills-item"><span class="item-text">GTD</span></li>
            <li class="tech-skills-item">
              <span class="item-text">Teamwork</span>
            </li>
          </ul>
        </div>
      </aside>
    </div>
  </body>
</html>

CSS: 

body {
    font-family: 'Montserrat', sans-serif;
    background-color: #E5E5E5;
}
.main-container {
    display: flex;
    flex-direction: row-reverse;
    width: 1200px;
    background: white;
    margin: 40px auto;
    box-shadow: 6px 6px 20px rgba(0, 0, 0, 0.1);
}

/* Main content section */
.main-content-section {
   padding: 100px 90px; 
}
.main-content-title {
    font-style: normal;
    font-weight: bold;
    font-size: 22px;
    line-height: 27px;
    color: black;
    margin-bottom: 10px;
}

/* About me section */
.about-me-section {
    margin: 0 0 40px 0;
}

.about-me-profession {
    font-style: normal;
    font-weight: bold;
    font-size: 14px;
    line-height: 17px;
    color: black;
    margin: 0 0 20px 0;
}
.about-me-name{
    font-style: normal;
    font-weight: bold;
    font-size: 45px;
    line-height: 55px;
    color: black;
    margin: 0 0 25px 0;
}
.about-me-description{
    color: #595959;
    font-style: normal;
    font-weight: normal;
    font-size: 14px;
    line-height: 24px;
    width: 400px;

}

/* My projects section */

.my-projects-section {
    margin: 0 0 50px 0;
}

.my-projects-list{
    padding: 0 0 0 18px;
}

.my-projects-item {
    color: black;
    font-weight: bold;

}
.my-projects-text {
    font-style: normal;
    font-weight: normal;
    font-size: 14px;
    line-height: 24px;
    color: #595959;
    margin-left: 5px;
}
.my-projects-link {
    font-style: normal;
    font-weight: normal;
    font-size: 14px;
    line-height: 24px;
    color: #595959;
}
.my-projects-br {
    color: black;
    font-style: normal;
    font-weight: bold;
    font-size: 14px;
    line-height: 24px;
}
/* My work experience */
.my-work-experience-section {
    margin-bottom: 45px;
}
.my-work-experience-position{
    font-style: normal;
    font-weight: bold;
    font-size: 16px;
    line-height: 20px;
    margin: 0 0 10px 0;
}
.my-work-experience-period{
    font-style: normal;
    font-weight: normal;
    font-size: 12px;
    line-height: 15px;
    color: #A8A8A8;
    margin: 0 0 10px 0;
}
.my-work-experience-divider {
    color: black;
}
.my-work-experience-company {
    color: #FB6D3A; 
}

.my-work-experience-duties {
    padding: 0 0 0 18px;
}

.my-work-experience-duty{
    color: #595959;
    font-style: normal;
    font-weight: normal;
    font-size: 14px;
    line-height: 24px;
}

.my-work-experience-company-block{
 margin: 0 15px 0 0;
}

.img{
    height: 354px;
    margin: 0 0 0 -40px;
}

/* Education section*/

.my-education-header {
    font-style: normal;
    font-weight: bold;
    font-size: 22px;
    line-height: 27px;
    color: black;
}
.my-education-university {
    font-style: normal;
    font-weight: bold;
    font-size: 16px;
    line-height: 20px;
    color: #FB6D3A;
    width: 380px;  
    margin-bottom: -10px;
}
.education {
    font-style: normal;
    font-weight: bold;
    font-size: 14px;
    line-height: 17px;
    margin-bottom: 10px;
}
/* Sidebar section */
.sidebar-section {
    background: #1E2939;
    width: 370px;
    padding: 40px 0 0 40px;
}
.contacts-section,
.tech-skills-section,
.soft-skills-section {
    margin: 50 0 0 40px;
}
.sidebar-title {
    font-style: normal;
    font-weight: bold;
    font-size: 22px;
    line-height: 27px;
    color: white;
    margin-bottom: 10px;
}
/* Contact section */

.contacts-section-type {
    font-weight: bold;
    font-size: 14px;
    line-height: 24px;
    color: white;
    margin-right: 7px;
}
.contacts-section-link {
    color: #565E6A;
    font-style: normal;
    font-weight: normal;
    font-size: 14px;
    line-height: 24px;
}
/* Tech skills section */

.tech-skills-list {
    padding: 0 0 0 17px;
}
.tech-skills-item {
    color: #FB6D3A;
}
.item-text {
    font-style: normal;
    font-weight: normal;
    font-size: 14px;
    line-height: 24px;
    color: white;
}

