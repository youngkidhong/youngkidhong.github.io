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
        url: uploads/YH-CV.pdf
    design:
      css_class: light
      background:
        color: white
        image:
          # Add your image background to `assets/media/`.
          filename: Untitled.png
          filters:
            brightness: 1.0
          size: cover
          position: center
          parallax: false
  - block: markdown
    id: papers
    content:
      title: Publications
      text: |
        **Hong, Y.**, Auten, A. R., & Ratner, K. G. (in press). Group Bouba-Kiki effects: The interplay of social categorization, competition, and sound symbolism . *Journal of Experimental Psychology: General*.

        **Hong, Y.**, & Freeman, J. B. (2024). Shifts in facial impression structures across group boundaries. *Social Psychological and Personality Science, 15*(6), 619-629. [[pdf](uploads/spps.pdf)]

        **Hong, Y.**, Maitner, A. T., & Ratner, K. G. (2024). Psychological effects of anti-Arab politics on American and Arab peoples' views of each other. *PLoS ONE, 19*(5): e0301282.[[pdf](uploads/HongMaitnerRatner2024.pdf)]

        **Hong, Y.**, Chua, C-W., & Freeman, J. B. (2024). Reducing facial stereotype bias in consequential social judgments: Intervention success with White male faces. *Psychological Science, 35*(1), 21-33. [[pdf](uploads/HongChuaFreeman2023.pdf)]

        **Hong, Y.**, Reed, M., & Ratner, K. G. (2023). Facial stereotypes of competence (not trustworthiness and dominance) most resemble facial stereotypes of group membership. *Social Cognition, 41*(6), 562-578. [[pdf](uploads/hong_soccog2023.pdf)]

        **Hong, Y.**, Mayes, M. S., Munasinghe, A. P., & Ratner, K. G. (2022). Scrutinizing whether mere group membership influences the N170 response to faces: Results from two preregistered ERP studies. *Journal of Cognitive Neuroscience, 34*(11), 1999-2015. [[pdf](uploads/jocn.pdf)]

        **Hong, Y.**, & Ratner, K. G. (2021). Minimal but not meaningless: Seemingly arbitrary category labels can imply more than group membership. *Journal of Personality and Social Psychology, 120*(3), 576-600. [[pdf](uploads/Hong_JPSP2020.pdf)]

        Welborn, B. L., & **Hong, Y.**, & Ratner, K. G. (2020). Exposure to negative stereotypes influences the representations of monetary incentives in the nucleus accumbens. *Social Cognitive and Affective Neuroscience, 15*(3), 347-358. [[pdf](uploads/WelbornHong_SCAN2020.pdf)]

        Hu, C., Yin, J., Lindenberg, S., Dalgar, I., Weissgerber, S. S., Vergara, R. C., Cairo, A. H, Čolic, M. V., Dursun, P., Frankowska, N., Hadi, R., Hall, C. J., **Hong, Y.**, …, & IJzerman, H. (2019). Data from the Human Penguin Project: A cross-national dataset testing principles from social thermoregulation theory. *Scientific Data, 6*(1), 32. [[pdf](uploads/scientificdata.pdf)]

        Ratner, K. G., Kaczmarek, A. R., & **Hong, Y.** (2018). Can over-the-counter pain medications influence our thoughts and emotions? *Policy Insights from the Behavioral and Brain Sciences, 5*(1), 82-89. [[pdf](uploads/RatnerKaczmarekHong2018.pdf)]

        IJzerman, H., Dalgar, I., Weissgerber, S. S., Vergara, R. C., Cairo, A. H, Čolic, M. V., Dursun, P., Frankowska, N., Hadi, R., Hall, C. J., **Hong, Y.**, …, & Lindenberg, S. M. (2018). The human penguin project: Complex social integration buffers human core temperatures from cold climates. *Collabra: Psychology, 4*(1), 37. [[pdf](uploads/HPP.pdf)]

        IJzerman, H., Čolic, M. V., Hennecke, M., **Hong, Y.**, …, & Lindenberg, S. M. (2017). Does distance from the equator predict self-control? Lessons from the Human Penguin Project. *Behavioral and Brain Sciences, 40*. [[pdf](uploads/BBS.pdf)]
    design:
      css_class: light space-y-12
      background:
       color: WhiteSmoke
  - block: markdown
    id: news
    content:
      title: Recent news
      text: |
        **August 15, 2025**: Youngki starts his position as an assistant professor in the Department of Psychology and Neurscience at CU Boulder!

        **March 14, 2025**: The paper titled "Group Bouba-Kiki effects: The interplay of social categorization, competition, and sound symbolism " was accepted for publication at the Journal of Experimental Psychology: General!

        **March 14, 2024**: The paper titled "Psychological effects of anti-Arab politics on American and Arab people’s views of each other" was accepted for publication at PLOS ONE!

        **November 28, 2023**: The paper titled "Facial stereotypes of competence (not trustworthiness and dominance) most resemble facial stereotypes of group membership" was accepted for publication at Social Cognition!

    design:
      css_class: light
      background:
        color: White
      # Choose a layout view
      view: date-title-summary
      # Reduce spacing
      spacing:
        padding: [0, 0, 0, 0]
  - block: cta-card
    design:
      card:
        # Card background color (CSS class)
        css_class: "bg-primary-700"
        css_style: ""
---
