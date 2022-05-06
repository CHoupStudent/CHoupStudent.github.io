<style>
    .accordion {
      max-width: 500px;
      border: 1px solid #⁠000;
    }

    .accordion-header {
      display: flex;
      padding: 16px;
      cursor: pointer;
      background-color: #3D3D3D;
      color: #FFFFFF;
      font-weight: bold;
    }

    .accordion-title {
      flex: 1;
    }

    .accordion-icon {
      width: 24px;
    }

    .accordion-content {
      padding: 16px;
    }

    .accordion-content {
      display: none;
    }
</style>

<h2>Chris Houp | About</h2>

  <h3>Headshot</h3>

![Christopher Houp's Headshot](assets/images/ChrisHeadshot.jpg)

  <h3>Desired Job</h3>
  I am looking for a web development job, preferrably on the backend. I believe my experience with databases and languages such as Python, Java, and MySQL will be particularly useful. I can also optimize my code for front-end development with my knowledge of html, css, and JavaScript.

  <h3>Education</h3>
  - Central High School (2014-2017)
  - Mount Aloysius College (2020-2023)
    - B.S. Information Technology
  <h3>Courses Taken</h3>
  - Introduction to Web Design
  - Database Applications
  - Database Management Systems (MySQL)
  - Ethical Hacking
  - Client/Server Operating Systems
  - Intro to Networking
  - Current Microcomputing Systems
  - PC Operating Systems
  - JavaScript Programming
  - Java Programming
  - Programming for Beginners (Python)
  - Other Useful Courses
    - Professional Communications
  <h3>Honors and Awards</h3>
  - Member of The National Society of Leadership and Success
    - Mount Aloysius College Chapter

#
  * * *


  <h3>Previous Work</h3>
  <section id="skillsAccordion" style="padding: 0px 0px 0px 0px; margin: 0px 0px 20px 0px">
      <h3>Languages</h3>

      <div class="accordion">

        <div class="accordion-header">
          <div class="accordion-title">Java</div>
          <span class="accordion-icon">+</span>
        </div>
        <div class="accordion-content">
            I have taken one semester in a Java class focused on object-oriented programming.
        </div>
        <div class="accordion-header">
          <div class="accordion-title">Python</div>
          <span class="accordion-icon">+</span>
        </div>
        <div class="accordion-content">
            I have taken one semester on Python where I made a working Alien Invasion clone game.
        </div>
        <div class="accordion-header">
          <div class="accordion-title">JavaScript</div>
          <span class="accordion-icon">+</span>
        </div>
        <div class="accordion-content">
            I have taken one semester in a JavaScript class where I created this portfolio site.
        </div>
        <div class="accordion-header">
          <div class="accordion-title">MySQL</div>
          <span class="accordion-icon">+</span>
        </div>
        <div class="accordion-content">
            I have taken one semester of MySQL and another semester on general relational database principles.
        </div>

      </div>


  </section>
  <script>

      const accordionHeaders = document.getElementsByClassName('accordion-header');
      const accordionContents = document.getElementsByClassName('accordion-content');
      const accordionIcons = document.getElementsByClassName('accordion-icon');

      for (let i = 0; i < accordionHeaders.length; i++) {
        accordionHeaders[i].addEventListener('click', () => {
          accordionContents[i].style.display = accordionContents[i].style.display == 'block' ? 'none' : 'block';
          accordionIcons[i].innerHTML = accordionContents[i].style.display == 'block' ? '-' : '+';
        })
      }
    </script>

  <h3>Internships</h3>

<h2>My Work / Projects</h2>

<h2>Contact Me</h2>
