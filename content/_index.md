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
      username: admin
      text: ""
      # Show a call-to-action button under your biography? (optional)
      button:
        text: Download CV
        url: uploads/resume.pdf
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
  - block: markdown
    content:
      title: '📚 My Interests'
      subtitle: ''
      text: |-
              I am a Colombian engineer and computer scientist. I believe in the potential of AI, thus I do research on AI architectures for prosocial, competitive, and cooperative environments. Additionally, I have done personal projects studying large language models' behavior, as well as using large language models for creating specific applications. This research helps me stay tuned with state-of-the-art AI methods, as well as gives me insight into AI's potential for complex tasks, and its possible future impact on society.

              On the other hand, I am passionate about finance, investment, and economics. In my free time, I enjoy attending international events targeted to people with long-term vision or people knowledgeable about global economics, such as the Berkshire Hathaway annual shareholders meeting. I believe globalization brings benefits outweighing possible weaknesses, thus I focus on learning about developed and developing markets and am continuously learning about different kinds of capital markets.

              Please reach out to me if your interests resonate with this 😃
      
    design:
      columns: '1'
  - block: collection
    id: papers
    content:
      title: Featured Research Work
      filters:
        folders:
          - publication
        featured_only: true
    design:
      view: article-grid
      columns: 2
 
  - block: collection
    id: talks
    content:
      title: Media Coverage 
      filters:
        folders:
          - event
    
    design:
      view: article-grid
      columns: 2
  - block: markdown
    id: news
    content:
      title: Timeline
      subtitle: ''
      text: |
        - **January 2023**. I became the Backoffice vice-president in AIESEC Cali, being in charge of Talent Acquisition management, and financial planning support.
        - **December 2022**. I started to work at Procedata Internacional as a Control M administrator in Data Crédito - Experian (development of new flows, business software development, and control shells programming).
        - **December 2022**. I finished the "Machine Learning" specialization at Coursera.
        - **December 2022**. I finished the "AI in Healthcare" specialization at Coursera.
        - **December 2022**. I finished the "Mathematics for Machine Learning" specialization at Coursera.
        - **November 2022**. I finished the "Data Analysis for Business Decision Making" professional certificate at EdX.
        - **November 2022**. I finished the "FinTech: Foundations and Applications of Financial Technology" specialization at Coursera.
        - **November 2022**. I finished the "MLOps1 (Azure): Deploying AI and ML Models using Microsoft Azure Machine Learning" course at EdX.
        - **November 2022**. I finished the "Object Oriented Programming in Java" course at Coursera.
        - **October 2022**. I enrolled in the "Online Diploma in Neural Networks and Deep Learning" course at UAO University.
        - **September 2022**. I finished the "Stock Market Self-Regulator Exam Preparation" course at BVC Online.
        - **September 2022**. I started the "Design's Architecture of a Decision Supporting Software for Buying/Holding/Selling Stocks" project.
        - **August 2022**. I finished the "Comparison of Machine Learning Methods Applied to Predicting Short-Term Movements of DJIA Stocks During Quarterly Financial Reporting Periods" project.
        - **June - July 2022**. I volunteered at CEFAMM, Quito.
        - **June 2022**. I finished the "Diploma in Stock Market" course at BVC Online.
        - **April 2022**. I finished the "Machine Learning with Python: A Practical Introduction" course at EdX.
        - **February 2022**. I started the "Comparison of Machine Learning Methods Applied to..." project.
        - **2017**. I won **1st place** in the **National Mathematics Competition** (ORM).
        - **2017**. I was awarded a **Half Tuition Scholarship** from **Javeriana University** (2017-2021).
        - **2017**. I was **selected for a 1-month National Math Boot Camp** by **OCM**.
        - **December 2021 - January 2022**. I volunteered at **SERART**, Guadalajara.
        - **April - August 2021**. I worked at **Bosch in Schwieberdingen, Germany**, as an intern in **Knowledge Management for Semi-Autonomous Driving**.
        - **October 2020 - March 2021**. I studied at **Otto-von-Guericke-Universität Magdeburg** as an exchange student as part of the **KOSPIE scholarship**.
  
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
        css_class: "bg-primary-700"
        css_style: ""
---
