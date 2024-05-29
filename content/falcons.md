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

        <img src="https://fastly.picsum.photos/id/919/200/300.jpg?hmac=jkU3iBD7FmgjpBy_oLT-Au05XW2UsFassE3X44PO_iQ">
          <div class="container">

          <!-- Full-width images with number text -->
          <div class="mySlides">
            <div class="numbertext">1 / 6</div>
              <img id="img1" src="assets/icon.png" style="width:100%">
          </div>

          <div class="mySlides">
            <div class="numbertext">2 / 6</div>
              <img src="assets/icon.png" style="width:100%">
          </div>

          <div class="mySlides">
            <div class="numbertext">3 / 6</div>
              <img src="assets/icon.png" style="width:100%">
          </div>

          <div class="mySlides">
            <div class="numbertext">4 / 6</div>
              <img src="assets/icon.png" style="width:100%">
          </div>

          <div class="mySlides">
            <div class="numbertext">5 / 6</div>
              <img src="assets/icon.png" style="width:100%">
          </div>

          <div class="mySlides">
            <div class="numbertext">6 / 6</div>
              <img src="assets/icon.png" style="width:100%">
          </div>

          <!-- Next and previous buttons -->
          <a class="prev" onclick="plusSlides(-1)">&#10094;</a>
          <a class="next" onclick="plusSlides(1)">&#10095;</a>

          <!-- Image text -->
          <div class="caption-container">
            <p id="caption"></p>
          </div>

          <!-- Thumbnail images -->
          <div class="row">
            <div class="column">
              <img class="demo cursor" src="uploads/smart-bio-cover.png" style="width:100%" onclick="currentSlide(1)" alt="The Woods">
            </div>
            <div class="column">
              <img class="demo cursor" src="img_5terre.jpg" style="width:100%" onclick="currentSlide(2)" alt="Cinque Terre">
            </div>
            <div class="column">
              <img class="demo cursor" src="img_mountains.jpg" style="width:100%" onclick="currentSlide(3)" alt="Mountains and fjords">
            </div>
            <div class="column">
              <img class="demo cursor" src="img_lights.jpg" style="width:100%" onclick="currentSlide(4)" alt="Northern Lights">
            </div>
            <div class="column">
              <img class="demo cursor" src="img_nature.jpg" style="width:100%" onclick="currentSlide(5)" alt="Nature and sunrise">
            </div>
            <div class="column">
              <img class="demo cursor" src="img_snow.jpg" style="width:100%" onclick="currentSlide(6)" alt="Snowy Mountains">
            </div>
          </div>
        </div>
        <script>
        console.log("hello from the other side")
        </script>
    design:
      columns: '1'

---
