<template>
  <div class="home">

    <nav class="navbar-main"> 
        <ul class="nav-menu">
            <li>
                <a href="#hero">
                    <i class="fas fa-home fa-lg"></i>
                </a>
            </li>
            <li>
                <a href="#profile">
                    <i class="far fa-user fa-lg"></i>
                </a>
            </li>
            <li>
                <a href="#exps">
                    <i class="fa fa-address-card fa-lg"></i>
                </a>
            </li>
            <li>
                <a href="#education">
                    <i class="fas fa-graduation-cap fa-lg"></i>
                </a>
            </li>
            <li>
                <a href="#skills">
                    <i class="fas fa-cogs fa-lg"></i>
                </a>
            </li>
        </ul>
        <div class="nav-background"></div>
    </nav>

    <section class="hero-container" id="hero">
      <!--  https://vignette.wikia.nocookie.net/leagueoflegends/images/6/6a/Ionia_LoR_Background.jpg/revision/latest/scale-to-width-down/340?cb=20191022172319  -->
      <h1 class="hero-header">{{name}}</h1>
      <!--       <div class="hero-divider shadow-lg"></div> -->
      <p class="hero-subheader">Personal Website</p>

    </section>

    <section class="profile-section" id="profile">
      <h1 class="display-4 heading">About Me</h1>
      <hr>
      <div class="row">
        <div class="col align-items-center">
          <img class="profile-image rounded-circle row justify-content-center mt-3"
            src="https://media-exp1.licdn.com/dms/image/C5603AQGmxlH1TOYVyw/profile-displayphoto-shrink_800_800/0?e=1597881600&v=beta&t=RB-rROT7SHMHCiGWztPUKlGledc1D-aa_PP8CngvA6M" />
          <p class="mt-4"> I'm a sophomore student specialising in Computer Science at the University of Toronto with a
            GPA of 3.96. I am interested in game development and the impact of computer programs on education and
            health. I have experience coding in Python, C++, and vue.js and I am currently seeking an internship role as
            a Software Engineer for summer 2021.</p>
          <div class="contact-links-container row">
            <a class="col" href="mailto:arthur.soenarto@mail.utoronto.ca" target="_blank">
              <i class="contact-link-icon fa fa-envelope"></i>
            </a>
            <a class="col" href="https://github.com/arthursoenarto">
              <i class="contact-link-icon fab fa-github"></i>
            </a>
            <a class="col" href="https://www.linkedin.com/in/arthursoenarto/" target="_blank">
              <i class="contact-link-icon fab fa-linkedin"></i>
            </a>
            <a class="col" href="https://codepen.io/arthursoenarto" target="_blank">
              <i class="contact-link-icon fab fa-codepen"></i>
            </a>
             <a class="col" href="/arthursoenartoresume.pdf" download>
               <!-- href="/resume.pdf" download -->
              <i class="contact-link-icon fas fa-download"></i>
            </a>
          </div>
        </div>
      </div>

    </section>

    <section class="profile-section experiences" id="exps">
      <h1 class="display-4 heading">Experiences</h1>
      <hr>
      <div class="experiences-main row">
        <div class="col-md-4">
          <h4> Code In Place | Stanford University </h4>
          <p> Apr 2020 - May 2020 </p>
          <location loc="Online"></location>
        </div>
        <div class="col-md-8">
          <p><strong>Section Leader</strong></p>
          <p>- Part of a teaching team for Code in Place, offered by Stanford during COVID-19 pandemic, with 10,000
            global students and 900 volunteer teachers participating from around the world.<br />
            - Prepared and taught a weekly discussion section of 10-12 students to supplement professors’ lectures in an
            introductory online Python programming course based on material from the first half of Stanford’s
            introductory programming course, CS106A.<br />
            - Trained by Professor Chris Piech, Professor Mehran Sahami, and head section leaders and attended section
            leader workshops to be able to successfully and effectively teach an online programming class.
          </p>
        </div>
      </div>
      <div class="experiences-main row">
        <div class="col-md-4">
          <h4> Keramik Diamond Industries </h4>
          <p> May 2018 - Jul 2018 </p>
          <location loc="Gresik, Indonesia"></location>
        </div>
        <div class="col-md-8">
          <p><strong>Information Technology Intern</strong></p>
          <p>- Part of the front-end development team to help create the company's new website: <a
              href="keramik-diamond.com" target="_blank">keramik-diamond.com</a><br />
            - Used HTML, CSS and Javascript </p>
        </div>
      </div>
      <div class="experiences-main row">
        <div class="col-md-4">
          <h4> Singapore National Academy </h4>
          <p> Jul 2017 - Apr 2019 </p>
          <location loc="Surabaya, Indonesia"></location>
        </div>
        <div class="col-md-8">
          <p><strong>Volunteer Teaching Assistant</strong></p>
          <p>- Helped primary and middle-school science and math teachers arrange lab sessions, set assignments, and
            mark tests. </p>
        </div>
      </div>
      <div class="experiences-main row">
        <div class="col-md-4">
          <h4> Habitat for Humanity</h4>
          <p> Apr 2016- May 2018</p>
          <location loc="Indonesia"></location>
        </div>
        <div class="col-md-8">
          <p><strong>Community Volunteer</strong></p>
          <p>- Raised money to go on mission trips to build houses for the rural communities of Indonesia</p>
        </div>
      </div>

    </section>

    <section class="profile-section" id="education">
      <h1 class="display-4 heading">Educations</h1>
      <hr>
      <div class="uoft">
        <h4>University of Toronto</h4>
        <p>Sep 2019 - present</p>
        <p><strong>Computer Science Specialist - 2nd Year</strong></p>
        <p>cGPA = 3.96</p>
        <p>Relevant Coursework Completed: </p>
        <ul>
          <li> Introduction to Computer Programming </li>
          <li> Introduction to Computer Science </li>
          <li> Introduction to Management Functions </li>
          <li> Linear Algebra 1 </li>
          <li> Introduction to Probability and Modelling </li>
          <li> Introduction to Sociology </li>
          <!-- calc1, calc2, mat102, soc100           -->
        </ul>
        <location loc="Toronto, Canada"></location>
      </div>
      <hr>
      <div class="highschool">
        <h4>Singapore National Academy</h4>
        <p>Jul 2004 - May 2019
        <p>
        <p><strong> High School (British-Patterned Education) </strong></p>
        <p> A-Levels </p>
        <ul>
          <li> Mathematics</li>
          <li> Chemistry </li>
          <li> Physics </li>
          <li> Information Technology</li>
          <li> English Language (AS Level) </li>
        </ul>
        <p> SATs </p>
        <ul>
          <li> SAT1: 1530/1600
            <ul>
              <li> Reading & Writing: 750/800</li>
              <li> Maths: 780/800 </li>
              <li> Essay: 21/24 </li>
            </ul>
          </li>
          <li> SAT2 Math Level 2: 800/800 </li>
        </ul>
        <p> 9 IGCSE Subjects and got distinction for Cambridge International Certificate of Education (ICE)</p>
        <p> Cambridge ICE is awarded to students who pass in at least seven Cambridge IGCSE subjects, including two from
          Group 1 and one from each of Groups 2 to 5. (Group 1 - Languages, Group 2 - Humanities, Group 3 - Sciences,
          Group 4 - Mathematics, Group 5 - Creative and Vocational) The seventh subject may be chosen from any of the
          syllabus groups. Distinction - Grade A or better in five subjects and grade C or better in two subjects. </p>
        <location loc="Surabaya, Indonesia"></location>
      </div>
    </section>

    <div class="skills-container">
      <section class="profile-section skills" id="skills">
        <h1 class="display-4 heading">Skills</h1>
        <hr>
        <h4> Coding </h4>
        <ul class="no-bullets">
          <li>
            <skill-stars skill="Python" stars="4"></skill-stars>
          </li>
          <li>
            <skill-stars skill="C++" stars="3"></skill-stars>
          </li>
          <li>
            <skill-stars skill="HTML" stars="3"></skill-stars>
          </li>
          <li>
            <skill-stars skill="CSS" stars="3"></skill-stars>
          </li>
          <li>
            <skill-stars skill="Javascript" stars="3"></skill-stars>
          </li>
          <li>
            <skill-stars skill="Vue.js" stars="3"></skill-stars>
          </li>
          <li>
            <skill-stars skill="Data Structures" stars="3"></skill-stars>
          </li>
          <li>
            <skill-stars skill="Algorithms" stars="3"></skill-stars>
          </li>
        </ul>
        <hr>
        <h4> Languages </h4>
        <ul class="no-bullets">
          <li>
            <skill-stars skill="English" stars="5"></skill-stars>
          </li>
          <li>
            <skill-stars skill="Indonesian" stars="5"></skill-stars>
          </li>
          <li>
            <skill-stars skill="Chinese" stars="3"></skill-stars>
          </li>
          <li>
            <skill-stars skill="Javanese" stars="5"></skill-stars>
          </li>
        </ul>

      </section>
    </div>

    <section class="profile-section">
      <h1 class="display-4 heading">Projects</h1>
      <hr>
      <p>This website is inspired by <a href="http://www.pascalvangemert.nl/" target="_blank">Pascal Van Gemert</a></p>
    </section>

    <section class="profile-section">
      <h1 class="display-4 heading">Hobbies</h1>
      <hr>
    </section>

  </div>
</template>

<script>
// @ is an alias to /src

import SkillStars from "../components/SkillStars"

import Location from "../components/Location"


export default {
  data() {
    return {
      name: 'Arthur Soenarto'
    }
  },
  components: {
    SkillStars,
    Location,
  }
}
</script>

<style>

*{
  text-align: left;
}

section {
  padding: 48px;
}

.hero-container {
  background: url(https://wallpaperset.com/w/full/2/3/7/534900.jpg) no-repeat center fixed;
  background-size: cover;
  opacity: 0.48;
  height: 100vh;
  display: flex;
  align-items: center;
  justify-content: center;
  flex-direction: column;
}
  
.hero-header {
  color: white;
  padding-bottom: 12px;
  border-bottom: 1px solid #FFFFFF;
}

.hero-subheader {
  color: white;
}

.hero-divider {
  height: 3px;
  width: 25%;
  background: #ffffff;
  text-align: center;
}

.experiences{
  background: #f1f1da;
}

.profile-image {
  height: 236px;
}

.contact-link-icon {
  color: #3498db;
  font-size: 42px;
  transition: color 0.2s ease-out;
}

.contact-link-icon:hover {
  color: #2ecc71;
}

.col {
  display: flex;
  flex-direction: column;
}

.uoft{
  padding:12px 0;
}

.highschool{
  margin-right: 30px;
}

.location{
  display: flex;
  flex-direction: row;
}

.no-bullets{
  list-style-type: none;
  margin: 0px;
  padding: 0px;
}

.heading{
  text-align: center;
}

.skills{
  margin-left: 25%;
  margin-right: 25%;
}

.skills-container{
  background-color: #f1f1da;
}

.experiences-main{
  padding-top: 12px;
  padding-bottom: 12px;
  margin-right: 10px;
}

.navbar-main{
  border-radius: 100px;
  z-index: 999;
  padding-top: 5px;
  padding-bottom: 5px;
  right: 2%;
  position: fixed;
  top: 50%;
  transform: translateY(-50%);
}

.nav-menu{
  margin: 0;
  padding-left: 0;
  list-style: none;
}

.nav-menu li a{
  text-align: center;
  display: block;
  padding: 20px;
  color: white;
  border-radius: 100px;
}

.nav-menu li a:hover{
  background:rgba(244,244,244,.3); 
}

.nav-background{
  background-image: linear-gradient(to bottom,#1C5E91 0,#167699 100%);
  position: absolute;
  width: 100%;
  height: 100%;
  border-radius: 100px;
  z-index: -1;
  top: 0;
  transition: 0.1s;
}

</style>
