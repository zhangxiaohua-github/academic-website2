---
# Display name
title: 张鹏

# Name pronunciation (optional)
name_pronunciation: Jung Peng

# Full name (for SEO)
first_name: Peng
last_name: Zhang

# Status emoji
status:
  icon: ☕️

# Is this the primary user of the site?
superuser: true

# Highlight the author in author lists? (true/false)
highlight_name: true

# Role/position/tagline
role: Ph.D student 

# Organizations/Affiliations to display in Biography blox
organizations:
  - name: Marine and Coastal Geodesy Group at UH, University of Houston
    url: https://xie.cive.uh.edu/

# Social network links
# Need to use another icon? Simply download the SVG icon to your `assets/media/icons/` folder.
profiles:
  - icon: at-symbol
    url: 'mailto:zhang_peng_uestc@163.com'
    label: E-mail Me
  # - icon: brands/x
  #   url: https://twitter.com/GetResearchDev
  # - icon: brands/instagram
  #   url: https://www.instagram.com/
  # - icon: brands/github
  #   url: https://github.com/gcushen
  # - icon: brands/linkedin
  #   url: https://www.linkedin.com/
  # - icon: academicons/google-scholar
  #   url: https://scholar.google.com/
  # - icon: academicons/orcid
  #   url: https://orcid.org/

interests:
  - SAR Imaging
  - InSAR
  - GNSS-IR
  - Remote Sensing
  - GeoAI

education:
  - area: PhD Geosensing
    institution: University of Houston
    date_start: 2025-09-01
    date_end: 2030-06-31
    summary: | 
      Supervised by Prof Surui Xie (https://www.cive.uh.edu/faculty/xie-surui). 
    # button:
    #   text: 'Read Thesis'
    #   url: 'https://example.com'
  - area: MSc Radar Sensing
    institution: University of Electronic Science and Technology of China
    date_start: 2020-09-01
    date_end: 2023-06-31
    summary: |
      GPA: 3.67/4.00

      Courses included:
      - Modern Testing Technology
      - Methods and Applications of Signal Processing
      - Surveying and Mapping
      - Microwave measurement

      My master thesis, titled 'A study on the mechanism of permafrost surface deformation based on multi-source remote sensing data', was authorized "Outstanding Master's Thesis".

  - area: BSc Measurement and Control Technology and Instrumentation
    institution: University of Electronic Science and Technology of China
    date_start: 2016-09-01
    date_end: 2020-06-31
    summary: |
      GPA: 3.80/4.00
      
      Courses included:
      - Signals and Systems
      - Microcomputer System Thoery and Embedded System Design
      - Electronic Measurement Theory and Test Systems
      - Microwave Technology and Radio-Frequency Circuit

work:
  - position: SAR Signals and InSAR Analysist
    company_name: Tianjin Yunyao Yuhang Technology Co., Ltd. 
    # company_url: ''
    # company_logo: ''
    date_start: 2023-07-01
    date_end: 2023-12-31
    summary: |2-
      Responsibilities include:
      - Simulating echo signals from both airborne and spaceborne SAR systems. This simulation aids in subsequent comparisons with actual echo signal metrics.
      - Deinterleaving, and decompressing echo data to calculate peak and integral sidelobe ratios, and to assess the quality of echo signals.
      - Utilizing the Range-Doppler (RD) algorithm to compress echo signals in both the range and azimuth directions, enabling focused SAR imaging.
  # - position: Backend Software Engineer
  #   company_name: X
  #   company_url: ''
  #   company_logo: ''
  #   date_start: 2016-01-01
  #   date_end: 2020-12-31
  #   summary: |
  #     Responsibilities include:
  #     - Migrated infrastructure to a new data center
  #     - lorem ipsum dolor sit amet, consectetur adipiscing elit
  #     - lorem ipsum dolor sit amet, consectetur adipiscing elit


# Skills
# Add your own SVG icons to `assets/media/icons/`
skills:
  - name: Programming Languages:
    items:
      - name: Python
        description: ''
        percent: 100
        icon: devicon/python
      - name: MATLAB
        description: ''
        percent: 60
        icon: devicon/matlab
      - name: PyTorch
        description: ''
        percent: 40
        icon: devicon/pytorch
      - name: C/C++
        description: ''
        percent: 40
        icon: devicon/cpp
  - name: Tools:
    # color: '#eeac02'
    # color_border: '#f0bf23'
    items:
      - name: Google Earth Engine (GEE)
        description: 'Familiar with GEE data processing process (proficient in employing GEE to process a variety of remote sensing data)'
      - name: GNSS-IR
        description: 'Familiar with GNSS-IR'
      - name: ENVI, ArcGIS, QGIS, SARscape, Apache Doris, StamPS
        description: 'Proficient in using these platforms to process optical or microwave remote sensing data.'
  - name: Models/Methods/Professional Skills:
    # color: '#eeac02'
    # color_border: '#f0bf23'
    items:
      - name: RS image processing
        description: 'Multi-source and remote sensing image processing: proficient in processing optical remote sensing images and SAR images.)'
      - name: InSAR technique
        description: 'PS-InSAR, SBAS-InSAR'
      - name: Permafrost models
        description: ' TTOP model, Stefan model, seasonal and interannual deformation decomposition model, late season settlement model, ALT estimation through InSAR.'
      - name: SAR Echo Signal Simulation and Imaging
        description: 'Proficiently simulate the echo signals of both airborne and satellite-borne SAR, and utilize RD/CS/BP algorithms for focusing the echo data and imaging..'   

# Awards.
#   Add/remove as many awards below as you like.
#   Only `title`, `awarder`, and `date` are required.
#   Begin multi-line `summary` with YAML's `|` or `|2-` multi-line prefix and indent 2 spaces below.
awards:
  - title: Outstanding Graduate Student
    date: '2022'
    awarder: UESTC

  - title: Outstanding Master's Thesis
    date: '2023'
    awarder: UESTC

  - title: 'Huiding Technology Scholarship'
    date: '2022'
    awarder: UESTC

  - title: 'Academic Youth'
    date: '2022'
    awarder: UESTC

  - title: 'First-class Scholarship'
    date: '2022'
    awarder: UESTC

  - title: 'Outstanding Student Scholarship'
    date: '2017 & 2018 & 2019'
    awarder: UESTC

# research experience:
#   - name: Monitoring and Analysis of Surface Deformation in the Norilsk Region Based on SBAS-InSAR Technology
#     description: '1.Applied the Small Baseline Subset Interferometric Synthetic Aperture Radar (SBAS-InSAR) to obtain its permafrost surface deformation rate, then utilized a sine model to decompose its interannual deformation and seasonal deformation, and finally compared the relationship between topographic slope and deformation rate; 2.Revealed that when the annual average temperature continuously increases at a rate of 2◦c/year for 2∼3 consecutive years, permafrost areas with relatively large topographic slopes (>15◦) are more prone to severe surface deformation during the summer thaw period; 3.Analyzed the permafrost deformation mechanisms and determined early surface deformation signals with the case of the oil tank collapse accident in the Norilsk region.'
#   - name: Analyzing Integration of Satellite Data Processing and Applied Common Technologies
#     description: '1.Participated in the design, debugging, and integration of SAR image filtering and segmentation algorithms, as well as software module integration work; 2.For filtering algorithm: decomposed the target based on non-local Lee filter, combining with the scattering model for polarimetric SAR to deal with the over-blurring problem caused by non-local filter and the difficulty of maintaining energy features; 3.For filtering algorithm: improved the similarity measurement method for the non-local means algorithm, and obtained the adaptive weight parameter of the non-local spatial information by combining the information entropy within neighborhood gray-level histograms, as well as gained the segmentation algorithm through introducing the interclass dispersion effect term.'
#   - name: Calculation and Analysis of Flood-Affected Areas in the Poyang Lake Region
#     description: '1.Processed Sentinel-1B data applying filtering, registration, threshold segmentation, and geocoding techniques based on SARscape; 2.Conducted change detection to derive flood-affected area, contributing to flood disaster assessment efforts.'  

---

## About Me

I am currently a Ph.D Student at Marine and Coastal Geodesy Group, University of Houston, where I am contributing to GNSS-IR, InSAR, Remote Sensing and GeoAI.
