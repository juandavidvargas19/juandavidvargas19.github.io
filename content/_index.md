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
        - **March 2025**. The PPSP Lab increased its RGU allocation from 1 to 65 RGU years, which is closely equivalent to a market value of CAD $220,000 using the metrics of H100 80 GB GPUS of DRAC. This was in part the result of my work to compile and submit the resources grant during the summer of 2024. 
        - **March 2025**. I presented MAPS at the TOM4AI workshop in AAAI 2025.
        - **February 2025**. I was awarded a travel grant by UNIQUE to do a presentation in the AAAI 2025 conference.
        - **December 2024**. I was awarded a redaction scholarship by DIRO (Département d'informatique et de recherche opérationnelle).
        - **July 2024**. I was co-author of the neuromatch-neuro AI course 2024.
        - **June 2024**. I was research assistant during summer (in addition to my research work) leading the efforts to submit a computational resources grant to the Digital Research Alliance of Canada.
        - **June 2024**. I was awarded an entrepeneurship grant by Mila Quebec AI Institute for my development of a financial chatbot.
        - **May 2024**. I presented MAPS at the Canadian AI 2024 conference.
        - **May 2024**. I was awarded an travel grant by Mila Quebec AI Institute to present a poster in the Canadian AI 2024.
        - **April 2024**. I was awarded an international fellowship by DIRO (Département d'informatique et de recherche opérationnelle).
        - **February 2024**. I was awarded an AI Research scholarship by DIRO (Département d'informatique et de recherche opérationnelle).
        - **December 2023**. I was awarded an international fellowship by DIRO (Département d'informatique et de recherche opérationnelle).
        - **December 2023**. We presented MAPLE during NeurIPS 2023 – Meltingpot Challenge Workshop.
        - **October 2023**. We presented MAPLE during the Workshop of Advances in Neuro AI 2023.
        - **July 2023**. I was accepted into UdeM to the AI MSc with Mila Quebec Institute. I was awarded an exemption scholarship, and a monthly stipend for the duration of my studies by the PPSP Laboratory.
        - **January 2023**. I became the Backoffice vice-president in AIESEC Cali, being in charge of Talent Acquisition management, and financial planning support.
        - **December 2022**. I started to work at Procedata Internacional as a Control M administrator in Data Crédito - Experian (development of new flows, business software development, and control shells programming).
        - **December 2022**. I finished the "Machine Learning" specialization at Coursera.
        - **December 2022**. I finished the "AI in Healthcare" specialization at Coursera.
        - **December 2022**. I finished the "Mathematics for Machine Learning" specialization at Coursera.
        - **November 2022**. I finished the "Data Analysis for Business Decision Making" professional certificate at EdX.
        - **November 2022**. I finished the "FinTech: Foundations and Applications of Financial Technology" specialization at Coursera.
        - **November 2022**. I finished the "MLOps1 (Azure): Deploying AI and ML Models using Microsoft Azure Machine Learning" course at EdX.
        - **November 2022**. I finished the "Object Oriented Programming in Java" course at Coursera.
        - **September 2022**. I finished the "Stock Market Self-Regulator Exam Preparation" course at BVC Online.
        - **August 2022**. I finished my BSc project "Comparison of Machine Learning Methods Applied to Predicting Short-Term Movements of DJIA Stocks During Quarterly Financial Reporting Periods".
        - **July 2022**. I was awarded an honor mention in the OMUS 2022 (university level math olympiads of southwestern Colombia).
        - **June - July 2022**. I volunteered at CEFAMM, Quito.
        - **June 2022**. I finished the "Diploma in Stock Market" course at BVC Online.
        - **April 2022**. I finished the "Machine Learning with Python: A Practical Introduction" course at EdX.
        - **December 2021 - January 2022**. I volunteered at SERART, Guadalajara.
        - **April - August 2021**. I worked at Bosch in Schwieberdingen, Germany, as an intern in Knowledge Management for Semi-Autonomous Driving.
        - **October 2020 - March 2021**. I studied at Otto-von-Guericke-Universität Magdeburg as an exchange student as part of the **KOSPIE scholarship**.
        - **June 2020** . I was awarded the KOSPIE scholarship by the DAAD, targeted to have a 1 year experience in Germany for 50 engineering students in Colombia.
        - **November 2017**. I won **1st place** in the **National Mathematics Competition** (ORM).
        - **August 2017**. I started my BSc of electronics engineering and I was awarded a Half Tuition Scholarship from Javeriana University (2017-2021).
        - **June 2017**. I was selected for a 1-month National Math Boot Camp by OCM.

  
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
