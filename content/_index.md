---
# Leave the homepage title empty to use the site title
title: ''
date: 2022-10-24
type: landing

design:
  # Default section spacing
  spacing: '6rem'

sections:
  - block: resume-biography-3
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
      text: ''
      # Show a call-to-action button under your biography? (optional)
      button:
        text: Download CV
        url: uploads/Resume_Rex_Leung2.pdf
      headings:
        about: ''
        education: ''
        interests: ''
    design:
      # Apply a gradient background
      css_class: hbx-bg-gradient
      # Avatar customization
      avatar:
        size: medium # Options: small (150px), medium (200px, default), large (320px), xl (400px), xxl (500px)
        shape: circle # Options: circle (default), square, rounded
  - block: markdown
    content:
#      title: '📚 My Research'
      title: 'My Reflections'
      subtitle: ''
      text: |-
        ### Reflection 1:
        #### Description
        During my internship working on a group project, we worked together to design and implement an end-tidal co2 measuring device. The task involved integrating hardware (pump, MOSFET, power supply) with software (PWM signal generation and control logic). We divided tasks according to strengths. I handled circuit design, wiring, coding and debugging. Others handled the cannula connection and casing of the device. Along the way, I also had to address practical issues, such as power delivery from USB-C to both the ESP32 and the pump, and the use of pull-down resistors for reliable MOSFET control.
        #### Feelings
        Initially, I felt excited about the hands-on project because it aligned with my interest in embedded systems. However, I also experienced frustration when the pump would not respond correctly to the PWM signal due to glitching microcontroller. The group discussions and troubleshooting sessions sometimes became tense when multiple theories were proposed, but solving problems together was satisfying and motivating.
        #### Personal Beliefs
        I always believe that technical projects are mainly about getting the design correct from the start. Through this experience, I learned that flexibility and adaptability are just as important because real hardware rarely works perfectly on the first try. I also reaffirmed my belief that clear communication is essential. When each member explained their approach before acting, we avoided confusion and redundant work.
        #### Difficulties
        One major difficulty was ensuring the pump received a stable power supply without overloading the ESP32’s 5V rail. Another was properly selecting and connecting pull-down resistors so that the MOSFET didn’t switch erratically when the ESP32 booted. Debugging these issues required both patience and careful measurement with a multimeter. We also faced time management issues, as some tasks took longer than expected due to unexpected component behaviour.
        #### Perspective: Research
        From a broader perspective, I realised our technical challenges were not unique as similar issues are frequently discussed in embedded systems forums. This reinforced the importance of researching standard practices, such as decoupling capacitors across Vcc and GND for noise suppression, and diode flyback protection for inductive loads. In an industrial context, these “small” design details could be crucial for long-term reliability.
        #### Lessons Learned and Future Intentions
        From this project, I learned that hardware design requires both theoretical and practical knowledge. I gained new insights into the role of supporting components like pull-down resistors, capacitors, and diodes in the way of ensuring circuit stability. Moving forward, I intend to plan more detailed schematics before starting physical assembly, and to allocate extra time for testing and debugging.
        ### Reflection 2:
        #### Description
        When I was doing control studio, our group collaborated to design, calibrate, and test a magnetic levitation control system, including sensor calibration, voltage scaling, and closed-loop performance analysis. Each member contributed to modelling, coding, and hardware integration.
        #### Feelings
        Initially, I felt excited about applying theory to a physical system but also concerned about hardware limitations and signal scaling errors. There were moments of frustration when test results didn’t match simulations.
        #### Personal Beliefs
        I believe in solving problems through careful measurement and verification. This project reinforced my assumption that clear communication is as important as technical skill in engineering teamwork.
        #### Difficulties
        We encountered difficulties with mismatched voltage ranges, amplifier scaling, and the correct interpretation of position sensor readings. These highlighted the gap between theoretical models and real-world behaviour.
        #### Perspective
        From a systems engineering perspective, the calibration challenge resembled industrial control problems where sensor accuracy and signal conditioning critically affect performance. Observing others’ approaches broadened my understanding of practical control implementation.
        #### Lessons Learned
        I learned the importance of validating hardware assumptions early and documenting all calibration steps. In future projects, I intend to apply more structured testing, improve group task coordination, and integrate hardware-in-the-loop simulations earlier in the design process. 😃
    design:
      columns: '1'
  - block: markdown
    content:
      title: 'Cover Letter'
      subtitle: ''
      text: |-
        Dear Graduate Recruitment Team,
        ##### I am excited to apply for the Industrus Engineering Graduate Program. As I prepare to graduate with a degree of Bachelor of Engineering (electrical) at the end of this year, I am eager to begin my career in an organisation recognised for its innovation, technical excellence, and meaningful impact on communities across Australia. Industrus Engineering’s work on projects such as renewable energy storage, resilient transport infrastructure, and sustainable building design reflects a culture of creativity and purpose that I aspire to contribute to.
        ##### I am strongly committed to ethical conduct and professional accountability, values I have demonstrated through my internship and project work. Whether working on engineering design challenges, such as a magnetic levitation control system and energy-harvesting solutions, or collaborating with peers in multidisciplinary teams, I have always prioritised safety, transparency, and responsibility in delivering quality outcomes.
        ##### Through my internship and project experience, I have developed strong communication skills, effectively engaging with both engineering peers and stakeholders from diverse disciplines. By presenting technical concepts in clear, accessible terms, I have helped bridge gaps between theory and practice while ensuring all team members are aligned. I thrive in creative and proactive environments, where innovation is encouraged, and I enjoy contributing ideas to solve complex engineering challenges.
        ##### I am also confident in my ability to use and manage information effectively, from interpreting technical specifications to documenting results and using digital tools for project planning. I take pride in managing my own performance by setting high standards, seeking feedback, and continuously improving my technical and interpersonal skills.
        ##### I have demonstrated the ability to work effectively in teams while stepping into leadership roles when needed, such as coordinating project milestones or guiding technical investigations. These experiences have equipped me to contribute to Industrus Engineering’s dynamic, project-driven teams.
        ##### Thank you for considering my application. I would welcome the opportunity to bring my enthusiasm, adaptability, and problem-solving mindset to Industrus Engineering and contribute to your mission of reimagining engineering in Australia.
        ##### Kind regards,
        ##### Chi Hang Leung
        
#  - block: collection
#    id: papers
#    content:
#      title: Featured Publications
#      filters:
#        folders:
#          - publications
#        featured_only: true
#    design:
#      view: article-grid
#      columns: 2
#  - block: collection
#    content:
#      title: Recent Publications
#      text: ''
#      filters:
#        folders:
#          - publications
#        exclude_featured: false
#    design:
#      view: citation
#  - block: collection
#    id: talks
#    content:
#      title: Recent & Upcoming Talks
#      filters:
#        folders:
#          - events
#    design:
#      view: card
#  - block: collection
#    id: news
#    content:
#      title: Recent News
#      subtitle: ''
#      text: ''
      # Page type to display. E.g. post, talk, publication...
#      page_type: blog
      # Choose how many pages you would like to display (0 = all pages)
#      count: 5
      # Filter on criteria
#      filters:
#        author: ''
#        category: ''
#        tag: ''
#        exclude_featured: false
#        exclude_future: false
#        exclude_past: false
#        publication_type: ''
      # Choose how many pages you would like to offset by
      offset: 0
      # Page order: descending (desc) or ascending (asc) date.
      order: desc
    design:
      # Choose a layout view
      view: card
      # Reduce spacing
      spacing:
        padding: [0, 0, 0, 0]
  - block: cta-card
    demo: true # Only display this section in the Hugo Blox Builder demo site
    content:
      title: 👉 Build your own academic website like this
      text: |-
        This site is generated by Hugo Blox Builder - the FREE, Hugo-based open source website builder trusted by 250,000+ academics like you.

        <a class="github-button" href="https://github.com/HugoBlox/hugo-blox-builder" data-color-scheme="no-preference: light; light: light; dark: dark;" data-icon="octicon-star" data-size="large" data-show-count="true" aria-label="Star HugoBlox/hugo-blox-builder on GitHub">Star</a>

        Easily build anything with blocks - no-code required!

        From landing pages, second brains, and courses to academic resumés, conferences, and tech blogs.
      button:
        text: Get Started
        url: https://hugoblox.com/templates/
    design:
      card:
        # Card background color (CSS class)
        css_class: 'bg-primary-700'
        css_style: ''
---
