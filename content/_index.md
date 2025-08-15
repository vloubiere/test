---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: markdown
    content:
      title: 
      subtitle: 
      text: |
        <div class="subtitle-text">
          Epigenetic memory in development and cancer models
        </div>
    design:
      columns: '1'
      background:
        image: 
          filename: Cavalli_v2_landscape_cropped_tiny.png
          filters:
            brightness: 1
          parallax: false
          position: center
          size: contain
          text_color_light: true
      spacing:
        padding: ['20px', '0', '20px', '0']
      css_class: tiny-banner

  - block: markdown
    content:
      title: Research
      text: |
        We use <strong>multidisciplinary approaches</strong> — single-cell omics, confocal and super-resolution microscopy, CRISPR-based genome editing, genomics, computational analyses, and physical modeling — to study how <strong>the 3D epigenome establishes and maintains transcriptional programs during development and disease</strong>, both in vivo (using <em>Drosophila</em> genetics) and in vitro (mouse cell lines). Our research focuses on three main topics:

        <div class="research-flex">
          <div class="research-flex-item left">
            <img src="media/fly_TEI.png" alt="Epigenetic inheritance of alternative chromatin states">
            <div class="research-grid-caption">
              Epigenetic inheritance of alternative chromatin states
            </div>
          </div>
          <div class="research-flex-item center">
            <img src="/media/HiC_Micro.png" alt="3D organization and function of the genome">
            <div class="research-grid-caption">
              3D organization and function of the genome
            </div>
          </div>
          <div class="research-flex-item right">
            <img src="/media/cancer_ED.png" alt="Role of Polycomb Group Proteins in development and cancer">
            <div class="research-grid-caption">
              Polycomb Group Proteins in development and cancer
            </div>
          </div>
        </div>
    design:
      columns: '1'
      spacing:
        padding: ['40px', '0', '40px', '0']

  - block: collection
    content:
      title: Latest News
      count: 5
      filters:
        author: ''
        category: ''
        exclude_featured: false
        publication_type: ''
        tag: ''
      offset: 0
      order: desc
      page_type: post
    design:
      view: card
      columns: '5'   # Show 5 cards in a row
      spacing:
        padding: ['40px', '0', '40px', '0']
      
  - block: collection
    content:
      title: Publications
      count: 5
      filters:
        folders:
          - publication
    design:
      view: citation
      columns: '1'
      spacing:
        padding: ['40px', '0', '40px', '0']

  - block: markdown
    content:
      text: |
        {{% cta cta_link="./people/" cta_text="Meet the team →" %}}
    design:
      columns: '1'
---