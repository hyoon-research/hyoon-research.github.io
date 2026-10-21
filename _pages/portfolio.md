---
layout: page
title: Portfolio
permalink: /portfolio/
description: Selected first-author and co-first-author research.
nav: true
nav_order: 3
---

<style>
  #research-portfolio {
    --portfolio-line: var(--global-divider-color, rgba(128, 128, 128, 0.28));
    line-height: 1.65;
  }

  #research-portfolio .portfolio-intro {
    margin: 0 0 2.5rem;
  }

  #research-portfolio .portfolio-section + .portfolio-section {
    margin-top: 3.5rem;
  }

  #research-portfolio .section-heading {
    margin: 0 0 1.5rem;
    padding-bottom: 0.8rem;
    border-bottom: 2px solid currentColor;
    font-size: 1.5rem;
    line-height: 1.3;
    font-weight: 700;
    letter-spacing: -0.02em;
  }

  #research-portfolio .paper {
    padding: 0.5rem 0 1.75rem;
  }

  #research-portfolio .paper + .paper {
    padding-top: 1.75rem;
    border-top: 1px solid var(--portfolio-line);
  }

  #research-portfolio .paper-title {
    margin: 0 0 0.6rem;
    font-size: 1.05rem;
    font-weight: 600;
    line-height: 1.55;
  }

  #research-portfolio .paper-link {
    display: inline-block;
    margin-left: 0.35rem;
    font-size: 0.85rem;
    font-weight: 500;
    white-space: nowrap;
    color: var(--global-theme-color, #176b68);
    text-decoration: none;
  }

  #research-portfolio .paper-link:hover,
  #research-portfolio .paper-link:focus-visible {
    text-decoration: underline;
    text-underline-offset: 3px;
  }

  #research-portfolio .paper-venue {
    margin: 0 0 0.3rem;
    font-size: 0.92rem;
    line-height: 1.55;
  }

  #research-portfolio .paper-role {
    margin: 0;
    font-size: 0.85rem;
    line-height: 1.55;
  }

  #research-portfolio .paper-figure {
    margin: 1.25rem 0 0;
  }

  #research-portfolio .paper-figure img {
    display: block;
    width: 100%;
    max-width: 680px;
    height: auto;
    margin: 0 auto;
  }

  #research-portfolio .portfolio-footer {
    margin: 2rem 0 0;
    padding-top: 1rem;
    border-top: 1px solid var(--portfolio-line);
    font-size: 0.95rem;
  }

  @media (max-width: 600px) {
    #research-portfolio .section-heading {
      font-size: 1.3rem;
    }

    #research-portfolio .paper-title {
      font-size: 1rem;
    }

    #research-portfolio .portfolio-section + .portfolio-section {
      margin-top: 2.5rem;
    }
  }
</style>

<div id="research-portfolio">
  <p class="portfolio-intro">
    Research spanning contaminant biogeochemistry, environmental microbiology,
    and predictive modeling.
  </p>

  <section class="portfolio-section" aria-labelledby="manuscripts">
    <h2 class="section-heading" id="manuscripts">
      Manuscripts in Preparation
    </h2>

    <article class="paper">
      <h3 class="paper-title">
        Molecular structure and environmental context jointly predict PFAS
        biotransformation outcomes: a literature-derived machine learning analysis
            <a
      class="paper-link"
      href="{{ '/assets/pdf/poster_ml.pdf' | relative_url }}"
      target="_blank"
      rel="noopener noreferrer"
      aria-label="Open research poster in a new tab"
      title="Research poster"
    >[Poster Link]</a>
      </h3>
      <p class="paper-venue"><em>In preparation</em></p>
      <p class="paper-role">First author</p>

      {% assign highlight_image = site.static_files | where: "path", "/assets/img/pfas_ml_inprep.png" | first %}
      {% if highlight_image %}
      <figure class="paper-figure">
        <img
          src="{{ '/assets/img/pfas_ml_inprep.png' | relative_url }}"
          alt="PFAS biotransformation prediction"
          loading="lazy"
        >
      </figure>
      {% endif %}
    </article>

    <article class="paper">
      <h3 class="paper-title">
        Charge-dependent sorption controls the bioavailability and
        biotransformation of PFAS precursors in AFFF-impacted solids
                    <a
      class="paper-link"
      href="{{ '/assets/pdf/poster_bioavailability.pdf' | relative_url }}"
      target="_blank"
      rel="noopener noreferrer"
      aria-label="Open research poster in a new tab"
      title="Research poster"
    >[Poster Link]</a>
      </h3>
      <p class="paper-venue"><em>In preparation</em></p>
      <p class="paper-role">
        Co-first author with Anna-Ricarda Schittich
      </p>

      {% assign highlight_image = site.static_files | where: "path", "/assets/img/pfas_bioavailability_inprep.png" | first %}
      {% if highlight_image %}
      <figure class="paper-figure">
        <img
          src="{{ '/assets/img/pfas_bioavailability_inprep.png' | relative_url }}"
          alt="PFAS precursor bioavailability and biotransformation"
          loading="lazy"
        >
      </figure>
      {% endif %}
    </article>
  </section>

  <section class="portfolio-section" aria-labelledby="preprints">
    <h2 class="section-heading" id="preprints">Preprints</h2>

    <article class="paper">
      <h3 class="paper-title">
        Genome-resolved metatranscriptomic analysis of arsenic demethylation
        and detoxification in a methanogenic rice paddy soil
        <a
          class="paper-link"
          href="https://doi.org/10.64898/2026.08.27.747368"
          target="_blank"
          rel="noopener noreferrer"
          aria-label="Open arsenic demethylation preprint in a new tab"
        >[Link]</a>
      </h3>
      <p class="paper-venue"><em>bioRxiv · 2026</em></p>
      <p class="paper-role">Co-first author with Michael Vega</p>

      {% assign highlight_image = site.static_files | where: "path", "/assets/img/arsenic_demethylation_2026.png" | first %}
      {% if highlight_image %}
      <figure class="paper-figure">
        <img
          src="{{ '/assets/img/arsenic_demethylation_2026.png' | relative_url }}"
          alt="Arsenic demethylation in rice paddy soil"
          loading="lazy"
        >
      </figure>
      {% endif %}
    </article>
  </section>

  <section class="portfolio-section" aria-labelledby="publications">
    <h2 class="section-heading" id="publications">
      Peer-reviewed Publications
    </h2>

    <article class="paper">
      <h3 class="paper-title">
        Versatile TOP assay surrogates for evaluating oxidation efficiency
        in complex environmental samples
        <a
          class="paper-link"
          href="https://doi.org/10.1016/j.hazl.2026.100198"
          target="_blank"
          rel="noopener noreferrer"
          aria-label="Open TOP assay paper in a new tab"
        >[Link]</a>
      </h3>
      <p class="paper-venue">
        <em>Journal of Hazardous Materials Letters · 2026 · 7: 100198</em>
      </p>
      <p class="paper-role">Co-first author with Sarah Choyke</p>

      {% assign highlight_image = site.static_files | where: "path", "/assets/img/top_assay_2026.png" | first %}
      {% if highlight_image %}
      <figure class="paper-figure">
        <img
          src="{{ '/assets/img/top_assay_2026.png' | relative_url }}"
          alt="TOP assay performance in complex samples"
          loading="lazy"
        >
      </figure>
      {% endif %}
    </article>

    <article class="paper">
      <h3 class="paper-title">
        Effects of Organic Matter, Iron (Hydr)oxides, and Iron Reductive
        Dissolution on Per- and Polyfluoroalkyl Substances Sorption to
        Aqueous Film-Forming Foam-Impacted Solids
        <a
          class="paper-link"
          href="https://doi.org/10.1021/acs.estlett.5c01155"
          target="_blank"
          rel="noopener noreferrer"
          aria-label="Open PFAS sorption paper in a new tab"
        >[Link]</a>
      </h3>
      <p class="paper-venue">
        <em>Environmental Science &amp; Technology Letters · 2026 · 13(1): 130–136</em>
      </p>
      <p class="paper-role">First author</p>

      {% assign highlight_image = site.static_files | where: "path", "/assets/img/pfas_sorption_2026.png" | first %}
      {% if highlight_image %}
      <figure class="paper-figure">
        <img
          src="{{ '/assets/img/pfas_sorption_2026.png' | relative_url }}"
          alt="PFAS sorption in AFFF-impacted solids"
          loading="lazy"
        >
      </figure>
      {% endif %}
    </article>

    <article class="paper">
      <h3 class="paper-title">
        Repression of microbial arsenite uptake and methylation by dissolved
        organic carbon
        <a
          class="paper-link"
          href="https://doi.org/10.1021/acs.estlett.4c00400"
          target="_blank"
          rel="noopener noreferrer"
          aria-label="Open arsenite uptake and methylation paper in a new tab"
        >[Link]</a>
      </h3>
      <p class="paper-venue">
        <em>Environmental Science &amp; Technology Letters · 2024 · 11(8): 838–844</em>
      </p>
      <p class="paper-role">First author</p>

      {% assign highlight_image = site.static_files | where: "path", "/assets/img/arsenic_repression_2024.png" | first %}
      {% if highlight_image %}
      <figure class="paper-figure">
        <img
          src="{{ '/assets/img/arsenic_repression_2024.png' | relative_url }}"
          alt="Organic carbon and microbial arsenite uptake"
          loading="lazy"
        >
      </figure>
      {% endif %}
    </article>

    <article class="paper">
      <h3 class="paper-title">
        Effects of iron and dissolved organic matter on bioavailability
        of arsenite under anaerobic conditions
        <a
          class="paper-link"
          href="https://doi.org/10.1021/acsestwater.3c00432"
          target="_blank"
          rel="noopener noreferrer"
          aria-label="Open arsenite bioavailability paper in a new tab"
        >[Link]</a>
      </h3>
      <p class="paper-venue">
        <em>ACS ES&amp;T Water · 2023 · 3(11): 3676–3686</em>
      </p>
      <p class="paper-role">First author</p>

      {% assign highlight_image = site.static_files | where: "path", "/assets/img/arsenic_bioavailability_2023.png" | first %}
      {% if highlight_image %}
      <figure class="paper-figure">
        <img
          src="{{ '/assets/img/arsenic_bioavailability_2023.png' | relative_url }}"
          alt="Arsenite bioavailability under anaerobic conditions"
          loading="lazy"
        >
      </figure>
      {% endif %}
    </article>

    <article class="paper">
      <h3 class="paper-title">
        Time-dependent biosensor fluorescence as a measure of bacterial
        arsenic uptake kinetics and its inhibition by dissolved organic matter
        <a
          class="paper-link"
          href="https://doi.org/10.1128/aem.00891-22"
          target="_blank"
          rel="noopener noreferrer"
          aria-label="Open arsenic biosensor paper in a new tab"
        >[Link]</a>
      </h3>
      <p class="paper-venue">
        <em>Applied and Environmental Microbiology · 2022 · 88(16): e00891-22</em>
      </p>
      <p class="paper-role">First author</p>

      {% assign highlight_image = site.static_files | where: "path", "/assets/img/arsenic_biosensor_2022.png" | first %}
      {% if highlight_image %}
      <figure class="paper-figure">
        <img
          src="{{ '/assets/img/arsenic_biosensor_2022.png' | relative_url }}"
          alt="Biosensors for bacterial arsenic uptake kinetics"
          loading="lazy"
        >
      </figure>
      {% endif %}
    </article>

    <article class="paper">
      <h3 class="paper-title">
        A serial biofiltration system for effective removal of low-concentration
        nitrous oxide in oxic gas streams: mathematical modeling of reactor
        performance and experimental validation
        <a
          class="paper-link"
          href="https://doi.org/10.1021/acs.est.8b05924"
          target="_blank"
          rel="noopener noreferrer"
          aria-label="Open serial biofiltration paper in a new tab"
        >[Link]</a>
      </h3>
      <p class="paper-venue">
        <em>Environmental Science &amp; Technology · 2019 · 53(4): 2063–2074</em>
      </p>
      <p class="paper-role">First author</p>

      {% assign highlight_image = site.static_files | where: "path", "/assets/img/n2o_serial_biofilter_2019.png" | first %}
      {% if highlight_image %}
      <figure class="paper-figure">
        <img
          src="{{ '/assets/img/n2o_serial_biofilter_2019.png' | relative_url }}"
          alt="Serial biofiltration of nitrous oxide"
          loading="lazy"
        >
      </figure>
      {% endif %}
    </article>

    <article class="paper">
      <h3 class="paper-title">
        Design and feasibility analysis of a self-sustaining biofiltration
        system for removal of low concentration N2O emitted from wastewater
        treatment plants
        <a
          class="paper-link"
          href="https://doi.org/10.1021/acs.est.7b02750"
          target="_blank"
          rel="noopener noreferrer"
          aria-label="Open self-sustaining biofiltration paper in a new tab"
        >[Link]</a>
      </h3>
      <p class="paper-venue">
        <em>Environmental Science &amp; Technology · 2017 · 51(18): 10736–10745</em>
      </p>
      <p class="paper-role">First author</p>

      {% assign highlight_image = site.static_files | where: "path", "/assets/img/n2o_biofilter_2017.png" | first %}
      {% if highlight_image %}
      <figure class="paper-figure">
        <img
          src="{{ '/assets/img/n2o_biofilter_2017.png' | relative_url }}"
          alt="Self-sustaining biofiltration of nitrous oxide"
          loading="lazy"
        >
      </figure>
      {% endif %}
    </article>
  </section>

  <p class="portfolio-footer">
    <a href="{{ '/publications/' | relative_url }}">
      View all publications &rarr;
    </a>
  </p>
</div>
