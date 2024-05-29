---
# Leave the homepage title empty to use the site title
title: ""
date: 2022-10-24
type: landing

design:
  # Default section spacing
  spacing: "6rem"

sections:
  - block: resume-biography-3
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: Immanuel
      text: ""
      # Show a call-to-action button under your biography? (optional)
      button:
        text: Download CV
        url: uploads/ImmanuelvKoshy_Resume.pdf
    design:
      css_class: dark
      background:
        color: black
        image:
          # Add your image background to `assets/media/`.
          filename: stacked-peaks.svg
          filters:
            brightness: 1.0
          size: cover
          position: center
          parallax: false
  # - block: markdown
  #   content:
  #     title: '📚 My Goals'
  #     subtitle: ''
  #     text: |-
  #       Use this area to speak to your mission. I'm a research scientist in the Moonshot team at DeepMind. I blog about machine learning, deep learning, and moonshots.

  #       I apply a range of qualitative and quantitative methods to comprehensively investigate the role of science and technology in the economy.
        
  #       Please reach out to collaborate 😃
  #   design:
  #     columns: '1'
  # - block: collection
  #   id: papers
  #   content:
  #     title: Featured Publications
  #     filters:
  #       folders:
  #         - publication
  #       featured_only: true
    # design:
    #   view: article-grid
    #   columns: 2
  - block: experience
    id: experience-section
    content:
      username: Immanuel
    design:
      # Hugo date format
      date_format: 'January 2006'
      # Education or Experience section first?
      is_education_first: false

  # - block: collection
  #   content:
  #     title: Publications
  #     text: ""
  #     filters:
  #       folders:
  #         - publication
  #       exclude_featured: false
  #   design:
  #     view: citation
  #create a 2 column layout for publications
  # each publication will be displayed in a card
  # the card will have a title, authors, publication date, and a link to the publication
  - block: markdown
    id: publications-section
    content:
      text: |-
        <h3 class="mb-6 text-3xl font-bold text-gray-900 dark:text-white" id="pubs-title">Publications</h3>
        <div class="my-publications">
        <a href="https://arxiv.org/pdf/1909.05330">
        <div class="card">
          <img src="uploads/smart-bio-cover.png">
          <div class="card-body">
            <h5 class="card-title hover-underline-animation">Smart-Door Bio sentry</h5>
            <p style="color:grey; font-size:0.8em;">Sustainable Innovation in Engineering and Technology, 2023</p>
            <p class="card-text">Published under the IoT domain of SIET 2023 conference and made a working prototype of a smart doorbell which doubles as a anti Covid/Viral protection system via inbuilt health sensors and a disinfectant dispersal system. Works on a YOLOV3 model running off a RPI.</p>
          </div>
          <a href="https://arxiv.org/pdf/1909.05330" class="btn btn-primary">Read More</a>
        </a>
        </div>
        <a href="https://arxiv.org/pdf/1909.05330">
        <div class="card">
          <img src="uploads/warehouse-cover.png">
          <div class="card-body">
            <h5 class="card-title hover-underline-animation">Intelligent Warehouse Optimization System</h5>
            <p style="color:grey; font-size:0.8em;">IEEE CONECCT, 2024</p>
            <p class="card-text"> It is linear regression based System designed to optimize warehouse management by seamlessly combining machine learning, IoT technology and predictive maintenance. The primary goal of IWOS is to enhance the overall efficiency, accuracy and reliability of warehouse operations, ultimately leading to reduced costs.</p>
            <a href="https://arxiv.org/pdf/1909.05330" class="btn btn-primary">Read More</a>
          </div>
        </div>
        </a>
        </div>
    design:
      columns: '1'
  - block: markdown
    content:
      text: |-
        <div style="text-align: left; display:flex; width:100vh">
          <h3 class="mb-6 text-3xl font-bold text-gray-900 dark:text-white" style="margin:0px;">Awards</h3>
        </div>
    design:
      columns: '1'
      css_class: title-text
  - block: resume-awards
    id: awards
    content:
      username: Immanuel
  - block: markdown
    id: certifications-section
    content:
      text: |-
        <div style="text-align: left; display:flex; width:100vh">
          <h3 class="mb-6 text-3xl font-bold text-gray-900 dark:text-white" style="margin:0px;">Certifications</h3>
        </div>
        <table style="margin-top: 0;">
          <tr>
            <th style="border-bottom: 1px solid transparent;">Certification</th>
            <th style="border-bottom: 1px solid transparent;">Issuing Authority</th>
            <th style="border-bottom: 1px solid transparent;">Year</th>
            <th style="border-bottom: 1px solid transparent;">Certificate</th>
          </tr>
          <tr>
            <td style="border-bottom: 1px solid transparent;">IoT with Smartworks</td>
            <td style="border-bottom: 1px solid transparent;">Altair</td>
            <td style="border-bottom: 1px solid transparent; color:grey;">2023</td>
            <td style="border-bottom: 1px solid transparent;"><a class="hover:underline inline-flex items-center text-primary-600 dark:text-primary-300" style="text-decoration:none;"href="uploads/iot_cert.pdf">
            See Certificate
              <svg class="w-3 h-3 ms-2.5 rtl:rotate-[270deg]" aria-hidden="true" xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 18 18">
              <path stroke="currentColor" stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M15 11v4.833A1.166 1.166 0 0 1 13.833 17H2.167A1.167 1.167 0 0 1 1 15.833V4.167A1.166 1.166 0 0 1 2.167 3h4.618m4.447-2H17v5.768M9.111 8.889l7.778-7.778"></path>
            </svg>
            </a></td>
          </tr>
          <tr>
            <td style="border-bottom: 1px solid transparent;">Security Fundamentals</td>
            <td style="border-bottom: 1px solid transparent;">MTA</td>
            <td style="border-bottom: 1px solid transparent; color:grey;">2021</td>
            <td style="border-bottom: 1px solid transparent;"><a class="hover:underline inline-flex items-center text-primary-600 dark:text-primary-300" style="text-decoration:none;"href="https://www.credly.com/badges/87c1357f-a6e1-4b1d-9429-26a97bcfb4ad?source=linked_in_profile">
            See Certificate
              <svg class="w-3 h-3 ms-2.5 rtl:rotate-[270deg]" aria-hidden="true" xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 18 18">
              <path stroke="currentColor" stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M15 11v4.833A1.166 1.166 0 0 1 13.833 17H2.167A1.167 1.167 0 0 1 1 15.833V4.167A1.166 1.166 0 0 1 2.167 3h4.618m4.447-2H17v5.768M9.111 8.889l7.778-7.778"></path>
            </svg>
            </a></td>
          </tr>
          <tr>
            <td style="border-bottom: 1px solid transparent;">Music theory Grade 3</td>
            <td style="border-bottom: 1px solid transparent;">Trinity College, London</td>
            <td style="border-bottom: 1px solid transparent; color:grey;">2017</td>
            <td style="border-bottom: 1px solid transparent;"><a class="hover:underline inline-flex items-center text-primary-600 dark:text-primary-300" style="text-decoration:none;"href="certificate_url">
            See Certificate
              <svg class="w-3 h-3 ms-2.5 rtl:rotate-[270deg]" aria-hidden="true" xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 18 18">
              <path stroke="currentColor" stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M15 11v4.833A1.166 1.166 0 0 1 13.833 17H2.167A1.167 1.167 0 0 1 1 15.833V4.167A1.166 1.166 0 0 1 2.167 3h4.618m4.447-2H17v5.768M9.111 8.889l7.778-7.778"></path>
            </svg>
            </a></td>
          </tr>
          <tr>
            <td style="border-bottom: 1px solid transparent;">Foundations of Project Management</td>
            <td style="border-bottom: 1px solid transparent;">Google</td>
            <td style="border-bottom: 1px solid transparent; color:grey;">2022</td>
            <td style="border-bottom: 1px solid transparent;"><a class="hover:underline inline-flex items-center text-primary-600 dark:text-primary-300" style="text-decoration:none;" href="https://www.coursera.org/account/accomplishments/certificate/UD9K262DP7GH">
              See Certificate
              <svg class="w-3 h-3 ms-2.5 rtl:rotate-[270deg]" aria-hidden="true" xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 18 18">
          <path stroke="currentColor" stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M15 11v4.833A1.166 1.166 0 0 1 13.833 17H2.167A1.167 1.167 0 0 1 1 15.833V4.167A1.166 1.166 0 0 1 2.167 3h4.618m4.447-2H17v5.768M9.111 8.889l7.778-7.778"></path>
              </svg>
            </a></td>
          </tr>
          <tr>
            <td style="border-bottom: 1px solid transparent;">Project Initiation: Starting a Successful Project</td>
            <td style="border-bottom: 1px solid transparent;">Google</td>
            <td style="border-bottom: 1px solid transparent; color:grey;">2022</td>
            <td style="border-bottom: 1px solid transparent;"><a class="hover:underline inline-flex items-center text-primary-600 dark:text-primary-300" style="text-decoration:none;" href="https://www.coursera.org/account/accomplishments/certificate/JLPDRGVSBR6A">
              See Certificate
              <svg class="w-3 h-3 ms-2.5 rtl:rotate-[270deg]" aria-hidden="true" xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 18 18">
                <path stroke="currentColor" stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M15 11v4.833A1.166 1.166 0 0 1 13.833 17H2.167A1.167 1.167 0 0 1 1 15.833V4.167A1.166 1.166 0 0 1 2.167 3h4.618m4.447-2H17v5.768M9.111 8.889l7.778-7.778"></path>
              </svg>
            </a></td>
          </tr>
        </table>
    design:
      columns: '1'
      css_class: title-text
#volunteering
# Designer at Helphen India (NGO) Jan 2023 - Present
# Editorial Head at VIT Stellar Jan 2022 - May 2023
  - block: markdown
    content:
      text: |-
        <div style="text-align: left; display:flex; width:100vh">
          <h3 class="mb-6 text-3xl font-bold text-gray-900 dark:text-white" style="margin:0px;">Volunteering</h3>
        </div>
        <table style="margin-top: 0;">
          <tr>
            <td style="border-bottom: 1px solid transparent;">Designer at Helphen India (NGO)</td>
            <td style="border-bottom: 1px solid transparent; color:grey;">Jan 2023 - Present</td>
          </tr>
          <tr>
            <td style="border-bottom: 1px solid transparent;">Editorial Head at VIT Stellar</td>
            <td style="border-bottom: 1px solid transparent; color:grey;">Jan 2022 - May 2023</td>
          </tr>
        </table>
    design:
      columns: '1'
      css_class: title-text
  # - block: collection
  #   id: talks
  #   content:
  #     title: Recent & Upcoming Talks
  #     filters:
  #       folders:
  #         - event
  #   design:
  #     view: article-grid
  #     columns: 1
  # - block: markdown
    # content:
  # - block: collection
  #   id: news
  #   content:
  #     title: Recent News
  #     subtitle: ''
  #     text: ''
  #     # Page type to display. E.g. post, talk, publication...
  #     page_type: post
  #     # Choose how many pages you would like to display (0 = all pages)
  #     count: 5
  #     # Filter on criteria
  #     filters:
  #       author: ""
  #       category: ""
  #       tag: ""
  #       exclude_featured: false
  #       exclude_future: false
  #       exclude_past: false
  #       publication_type: ""
  #     # Choose how many pages you would like to offset by
  #     offset: 0
  #     # Page order: descending (desc) or ascending (asc) date.
  #     order: desc
  #   design:
  #     # Choose a layout view
  #     view: date-title-summary
  #     # Reduce spacing
  #     spacing:
  #       padding: [0, 0, 0, 0]
  # - block: cta-card
  #   demo: true # Only display this section in the Hugo Blox Builder demo site
  #   content:
  #     title: 👉 Build your own academic website like this
  #     text: |-
  #       This site is generated by Hugo Blox Builder - the FREE, Hugo-based open source website builder trusted by 250,000+ academics like you.

  #       <a class="github-button" href="https://github.com/HugoBlox/hugo-blox-builder" data-color-scheme="no-preference: light; light: light; dark: dark;" data-icon="octicon-star" data-size="large" data-show-count="true" aria-label="Star HugoBlox/hugo-blox-builder on GitHub">Star</a>

  #       Easily build anything with blocks - no-code required!
        
  #       From landing pages, second brains, and courses to academic resumés, conferences, and tech blogs.
  #     button:
  #       text: Get Started
  #       url: https://hugoblox.com/templates/
  #   design:
  #     card:
  #       # Card background color (CSS class)
  #       css_class: "bg-primary-700"
  #       css_style: ""
---
