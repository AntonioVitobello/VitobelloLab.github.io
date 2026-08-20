---
title: "VITOBELLO LAB"
summary: "Rare diseases · RNA Biology · Cellular Mechanisms"
date: 2026-08-20
type: landing

sections:

  # ============================================================
  # 1. SCIENTIFIC VISION
  # ============================================================

  - block: markdown
    content:
      title: "VITOBELLO LAB"
      subtitle: "Rare diseases · RNA Biology · Cellular Mechanisms"
      text: |-
        We investigate how RNA-binding proteins control RNA function across cellular compartments, and how disruption of these mechanisms leads to human disease.

        Our laboratory uses **human genetic variation as a window into fundamental RNA biology**, connecting genomic discovery with molecular mechanisms, cellular function and developmental phenotypes.

        **From human genetic variation to disease mechanism:  
        Genome → RNA → Cell → Tissue → Phenotype.**

    design:
      columns: "1"


  # ============================================================
  # 2. RESEARCH FRAMEWORK
  # ============================================================

  - block: markdown
    id: research
    content:
      title: "Our research"
      text: |-

        ### A unified research program

        Rare genetic disorders provide a unique opportunity to discover
        fundamental mechanisms of gene regulation.

        We focus on **RNA-binding proteins (RBPs)** and investigate how
        genetic variation alters RNA regulation, subcellular localization
        and cellular identity.

        Our research moves across biological scales:

        **Patient → Genome → RNA → Cell → Organoid → Phenotype**

    design:
      columns: "1"


  # ============================================================
  # 3. THREE RESEARCH DIRECTIONS
  # ============================================================

  - block: markdown
    id: research-directions
    content:
      title: "Research directions"
      text: |-

        ### 01 · RNA-binding proteins in human disease

        We use human genetic variation to identify RNA-binding proteins
        and RNA regulatory mechanisms involved in rare developmental
        disorders.

        ### 02 · Spatial regulation of RNA

        We investigate how RNA-binding proteins regulate RNA function
        beyond their classical nuclear roles, with a particular focus
        on **subcellular RNA localization, cytoplasmic regulation and
        RNA-protein condensates**.

        ### 03 · From molecular mechanisms to phenotypes

        We connect molecular perturbations to cellular and developmental
        phenotypes using **CRISPR/Cas9 genome editing, functional
        genomics, single-cell and spatial approaches, and human
        cellular and organoid models**.

    design:
      columns: "1"


  # ============================================================
  # 4. RESEARCH PROJECTS
  # ============================================================

  - block: collection
    id: projects
    content:
      title: "Research Projects"
      text: "Selected projects illustrating our research program."
      filters:
        folders:
          - projects
        exclude_featured: false
    design:
      view: card
      columns: 3


  # ============================================================
  # 5. SELECTED PUBLICATIONS
  # ============================================================

  - block: collection
    id: papers
    content:
      title: "Selected Publications"
      filters:
        folders:
          - publications
        featured_only: true
    design:
      view: article-grid
      columns: 3


  # ============================================================
  # 6. LATEST NEWS
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
  # 7. JOIN THE LAB
  # ============================================================

  - block: cta-card
    content:
      title: "Join the Vitobello Lab"
      text: "We are interested in motivated researchers, clinicians and students working at the interface of human genetics, RNA biology and functional genomics."
      button:
        text: "Join us"
        url: "/join-us/"
    design:
      card:
        css_class: "bg-gradient-to-br from-primary-500 via-primary-600 to-secondary-600 text-white shadow-2xl"
        css_style: ""
---
