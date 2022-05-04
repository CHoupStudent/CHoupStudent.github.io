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
  <h3>Desired Job</h3>

  <h3>Education</h3>
  <h3>Courses Taken</h3>
  <h3>Honors and Awards</h3>

  <h3>Previous Work</h3>

  <section id="skillsAccordion">
      <h3>Skills and Languages</h3>

      <div class="accordion">

        <div class="accordion-header">
          <div class="accordion-title">Skills</div>
          <span class="accordion-icon">+</span>
        </div>
        <div class="accordion-content">
            Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolor
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
