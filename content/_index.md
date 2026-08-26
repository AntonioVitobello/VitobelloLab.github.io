---
title: "VITOBELLO LAB"
summary: "Human Genetics · Gene Regulation · RNA Biology"
date: 2026-08-20
type: landing

sections:

  # ============================================================
  # 1. HERO
  # ============================================================

  - block: hero
    id: hero
    content:
      title: "Deciphering gene regulation<br>in human development<br>and disease"
      text: >
        We investigate how regulatory proteins shape gene expression,
        RNA regulation and cellular identity, and how disruption of
        these mechanisms leads to human disease.
      primary_action:
        text: "Explore our research"
        url: "#research"
      secondary_action:
        text: "Publications"
        url: "/publication/"
    design:
      css_class: "lab-hero"
      size: "viewport"
      alignment: "left"
      background:
        image:
          filename: hero-rna.jpg
          size: cover
          position: center
          filters:
            brightness: 0.85
            contrast: 1.05
            saturate: 1.05
          
    
  # ============================================================
  # 2. SCIENTIFIC VISION
  # ============================================================

  - block: markdown
    content:
      title: "VITOBELLO LAB"
      subtitle: "Human Genetics · Gene Regulation · RNA Biology"
      text: |-

        **Our laboratory uses human genetic variation as a window into
        fundamental mechanisms of gene regulation**, connecting genomic
        discovery with molecular mechanisms, cellular function and
        developmental phenotypes.

        **We investigate how regulatory proteins, including RNA-binding
        proteins, transcription factors and chromatin regulators, shape
        gene expression, RNA regulation, cellular identity and
        developmental processes, with a particular interest in how
        their spatial and temporal organization influences cell fate.**

    design:
      columns: "1"
      css_class: "scientific-vision"


  # ============================================================
  # 3. RESEARCH FRAMEWORK
  # ============================================================

  - block: markdown
    id: research
    content:
      title: "Research framework"
      text: |-

        ### From human genetic variation to biological mechanisms

        Human genetic variation provides a window into the molecular
        mechanisms that govern gene regulation, RNA regulation and
        organization, cellular function and human development and disease.

        ![Research framework](framework.jpg)

    design:
      columns: "1"
      css_class: "research-framework-section"


  # ============================================================
  # 4. RESEARCH PROGRAM
  # ============================================================

  - block: markdown
    id: research-program
    content:
      title: "Research program"
      text: |-

        ### 01 · Regulatory proteins in human development

        We investigate how **transcription factors, chromatin regulators
        and RNA-binding proteins** control gene expression and cellular
        identity during human development, and how genetic variation
        disrupts these regulatory mechanisms.

        ### 02 · Spatial and post-transcriptional regulation of RNA

        We investigate how RNA regulation extends beyond transcription,
        with a particular focus on **RNA-binding proteins, RNA localization,
        cytoplasmic RNA regulation and RNA-protein condensates**.

        ### 03 · From regulatory mechanisms to phenotypes

        We connect molecular perturbations to cellular and developmental
        phenotypes using **CRISPR/Cas9 genome editing, functional genomics,
        single-cell and spatial approaches, and human cellular and
        organoid models**.

    design:
      columns: "1"


  # ============================================================
  # 5. DISCOVERY & FUNCTIONAL GENOMICS
  # ============================================================

  - block: markdown
    id: discovery
    content:
      title: "Discovery & Functional Genomics"
      text: |-

        We integrate **genomics, transcriptomics, epigenomics and
        multi-omics approaches** to identify disease-associated genetic
        variation and uncover molecular mechanisms in unresolved rare
        disorders.

        These discoveries provide the starting point for functional studies
        of **gene regulation, RNA biology and cellular mechanisms**.

        **Discovery**  
        Genomics · Transcriptomics · Epigenomics · Multi-omics

        **Definition**  
        Gene regulation · RNA biology · Cellular mechanisms

        **Functional modeling**  
        CRISPR/Cas9 · Cellular models · Organoids · Single-cell · Spatial approaches

        ### European networks & consortia

        **Solve-RD · ERDERA**

    design:
      columns: "1"


  # ============================================================
  # 6. SELECTED PUBLICATIONS
  # ============================================================

  - block: markdown
    id: selected-publications
    content:
      title: "Selected publications"
      text: |-

        ### 01 · Genetic discovery

        From genomic variation to the identification of genes and
        molecular mechanisms underlying rare human disorders.

        ### 02 · Gene regulation & developmental mechanisms

        Discovering how regulatory proteins shape gene expression,
        cellular identity and human development.

        ### 03 · RNA biology & spatial regulation

        Understanding how RNA-binding proteins and RNA localization
        contribute to cellular function and disease.

        ### 04 · From mechanism to phenotype

        Connecting molecular mechanisms to cellular and developmental
        phenotypes through functional genomics and experimental models.

    design:
      columns: "1"


  # ============================================================
  # 7. RESEARCH PROJECTS
  # ============================================================

  - block: collection
    id: projects
    content:
      title: "Research Projects"
      text: "Selected projects supporting our research program."
      filters:
        folders:
          - projects
        exclude_featured: false
    design:
      view: card
      columns: 3


  # ============================================================
  # 8. ALL PUBLICATIONS
  # ============================================================

  - block: collection
    id: publications
    content:
      title: "Publications"
      text: "Our complete list of publications."
      filters:
        folders:
          - publications
    design:
      view: article-grid
      columns: 3


  # ============================================================
  # 9. LATEST NEWS
  # ============================================================

  - block: collection
    id: news
    content:
      title: "Latest News"
      page_type: blog
      count: 6
      filters:
        exclude_future: false
        exclude_past: false
      order: desc
    design:
      view: card
      spacing:
        padding: [0, 0, 0, 0]


  # ============================================================
  # 10. JOIN THE LAB
  # ============================================================

  - block: cta-card
    content:
      title: "Join the Vitobello Lab"
      text: "We are interested in motivated researchers, clinicians and students working at the interface of human genetics, gene regulation and functional biology."
      button:
        text: "Join us"
        url: "/join-us/"
    design:
      card:
        css_class: "bg-gradient-to-br from-primary-500 via-primary-600 to-secondary-600 text-white shadow-2xl"
        css_style: ""
---
