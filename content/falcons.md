---
title: 'Falcons'
date: 2023-10-24
type: landing

design:
  spacing: '5rem'

# Page sections
sections:
#   - block: resume-experience
#     content:
#       username: admin
#     design:
#       # Hugo date format
#       date_format: 'January 2006'
#       # Education or Experience section first?
#       is_education_first: false
# # gallery
  - block: markdown
    content:
      text: |-
        <div class="container">
          <div class="slideshow-main">
          <div class="slideshow-image">
          <!-- Full-width images with number text -->
          <div class="mySlides">
            <div class="numbertext">1 / 5</div>
              <img id="img1" src="https://raw.githubusercontent.com/ivk1231/portfolio/main/static/uploads/falcons/img1.jpg" style="width:100%">
          </div>

          <div class="mySlides">
            <div class="numbertext">2 / 5</div>
              <img src="https://raw.githubusercontent.com/ivk1231/portfolio/main/static/uploads/falcons/img2.jpg" style="width:100%">
          </div>

          <div class="mySlides">
            <div class="numbertext">3 / 5</div>
              <img src="https://raw.githubusercontent.com/ivk1231/portfolio/main/static/uploads/falcons/img3.jpg" style="width:100%">
          </div>

          <div class="mySlides">
            <div class="numbertext">4 / 5</div>
              <img src="https://raw.githubusercontent.com/ivk1231/portfolio/main/static/uploads/falcons/img4.jpg" style="width:100%">
          </div>

          <div class="mySlides">
            <div class="numbertext">5 / 5</div>
              <img src="https://raw.githubusercontent.com/ivk1231/portfolio/main/static/uploads/falcons/img5.jpg" style="width:100%">
          </div>
          </div>
          <div class="slideshow-arrows">
            <a class="prev" onclick="plusSlides(-1)">&#10094;</a>
            <a class="next" onclick="plusSlides(1)">&#10095;</a>
          </div>
          </div>
          <!-- Image text -->
          <div class="caption-container">
            <p id="caption"></p>
          </div>

          <!-- Thumbnail images -->
          <div class="row">
            <div class="column">
              <img class="demo cursor" src="https://raw.githubusercontent.com/ivk1231/portfolio/main/static/uploads/falcons/img1.jpg" style="width:100%" onclick="currentSlide(1)" alt="The Woods">
            </div>
            <div class="column">
              <img class="demo cursor" src="https://raw.githubusercontent.com/ivk1231/portfolio/main/static/uploads/falcons/img2.jpg" style="width:100%" onclick="currentSlide(2)" alt="Cinque Terre">
            </div>
            <div class="column">
              <img class="demo cursor" src="https://raw.githubusercontent.com/ivk1231/portfolio/main/static/uploads/falcons/img3.jpg" style="width:100%" onclick="currentSlide(3)" alt="Mountains and fjords">
            </div>
            <div class="column">
              <img class="demo cursor" src="https://raw.githubusercontent.com/ivk1231/portfolio/main/static/uploads/falcons/img4.jpg" style="width:100%" onclick="currentSlide(4)" alt="Northern Lights">
            </div>
            <div class="column">
              <img class="demo cursor" src="https://raw.githubusercontent.com/ivk1231/portfolio/main/static/uploads/falcons/img5.jpg" style="width:100%" onclick="currentSlide(5)" alt="Nature and sunrise">
            </div>
          </div>
        </div>
        <script>
        console.log("hello from the other side")
        </script>
    design:
      columns: '1'

---
