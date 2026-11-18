---
title: HydroImpact
description: HydroImpact makes robust hydrological climate impact assessments accessible to those who need them, with an application-driven climate impact platform for rivers across Europe.

hero:
  heading: Robust climate impact assessments for rivers across Europe
  lede: >-
    Climate change is reshaping our rivers, with longer droughts and more intense
    floods. HydroImpact will make robust hydrological climate impact assessments
    accessible to water professionals, with a platform that quantifies these
    changes for their own catchment and application.
  status: The project starts in May 2027, funded by BRIDGE.

# Modelling chain figure below the introduction (layouts/_partials/chain.html).
chain:
  title: 
  stages:
    - name: Emission scenarios
      text: Possible pathways of future greenhouse gas emissions
    - name: Global climate
      text: Simulated for the whole planet on a coarse grid
    - name: Regional climate
      text: Simulated over Europe on a finer grid
    - name: Local climate
      text: Brought down to the catchment scale
    - name: River impacts
      text: Changes in streamflow, floods, low flows and seasonality
  # role: "assess" (dashed) or "run" (solid) marks where HydroImpact comes in.
  steps:
    - name: Global climate models
    - name: Regional climate models
      role: assess
      note: 
    - name: Bias adjustment and downscaling
      role: run
      note: 
    - name: Hydrological models
      role: run
      note: 
  ours: >-
    HydroImpact tests which chains suit each application and region, from the
    regional climate simulations onwards, and turns them into automated
    workflows.

why:
  heading: The challenge
  text: |-
    Many decisions taken today depend on how rivers will change over the coming decades. Yet turning climate projections into actionable hydrological information remains difficult:

    - **The modelling chain is complex.** It involves huge climate datasets, and models that take time and expertise to set up.
    - **Uncertainty accumulates along the chain.** Leaving it out gives false precision, with protection that is too weak or needlessly costly.
    - **The right workflow depends on the application.** What works for droughts is not what a 100-year flood estimate needs.

# Sections shown after "The challenge", in this order. A section with "steps"
# shows them as numbered columns, followed by the optional "closing" line.
sections:
  - heading: Our approach
    text: |-
      HydroImpact combines research and software. A systematic benchmark will first identify which modelling chains can be trusted for which application and region. An application-driven cloud platform will then run these validated workflows automatically and add AI-powered insights, so practitioners get robust, uncertainty-aware answers without building the chain themselves.
  - heading: How the platform will work
    text: |-
      The platform will offer the validated workflows as a guided, code-free service. Everything runs in the cloud, so no climate data need to be downloaded and no models set up locally. An assessment takes three steps.
    steps:
      - title: Select
        text: >-
          You will choose the catchment on a map, the application (flood
          frequency, low flows, water availability, seasonality or reservoir
          inflows) and the time horizon.
      - title: Compute
        text: >-
          HydroImpact will run the workflow validated for that application and
          region in the cloud, and quantify the uncertainty.
      - title: Understand
        text: >-
          Results will come decision-ready: time series and indicators
          with their likely range, plain-language explanations
          of what changes and why, and reports or an API for your own tools.
  - heading: Open and co-designed
    text: |-
      Models and methods will be mostly open source, and results published in open-access, peer-reviewed articles.

      Partners from engineering firms, hydropower companies, public authorities and insurance companies co-design and test the platform, which will cover Switzerland first, then Europe.
---

Climate change has a profound impact on streamflow in mountain regions and their dependent lowland areas, with summer water availability decreasing and extreme events such as floods and droughts intensifying. The underlying changes in key hydrological processes, including snow accumulation and melt, evapotranspiration, and precipitation amount and intensity, have severe impacts on water supply and management.

Quantifying such changes requires a hydrological modeling workflow that involves multiple steps, including bias-adjustment and downscaling of climate data, calibration/training and evaluation of hydrological models, and modeling the streamflow response to future climate conditions. While the individual components of this workflow have been well studied, analyzing the effectiveness of different combinations of modeling decisions for targeted applications, such as assessing changes in flood frequency in a specific region, is time-consuming and often beyond practitioners' expertise and technical capabilities. Consequently, most climate impact studies remain confined to academic settings, and impact assessments conducted by practitioners typically rely on incomplete workflows that consider small subsets of climate ensembles and hydrological models, which results in an underestimation of uncertainty.

In this project, we will make targeted hydrological climate impact assessments widely accessible to practitioners and engineers in Europe. To this end, we will build a cloud-based platform to facilitate, standardize, and enhance climate impact assessments in hydrology by integrating state-of-the-art modeling tools and employing a stakeholder co-design process. The aim of the platform is twofold: (i) ensure that tools and data are targeted to specific applications and (ii) offer reproducible workflows. To achieve this, our efforts will be structured along the following main axes:

- **Identification of suitable hydrological modeling workflows for a wide range of potential applications.** At the heart of our project lies the development and an extensive evaluation of modeling workflows, i.e., combinations of different climate data processing techniques, including bias adjustment and downscaling, and hydrological models. We will test the suitability of these workflows for specific applications, e.g., assessing changes in water availability or flood frequency, and for different regions in Europe. Developing suitable workflows will require the development of (i) strategies to facilitate the transferability of climate data processing and modeling tools across diverse regions and climatic conditions; and (ii) uncertainty quantification techniques that can quantify different sources of uncertainty along the modeling chain.
- **Cloud-based platform development building on user needs.** The platform will provide a unified and streamlined access to climate and hydrological data, enabling users to define their catchments of interest while automatically retrieving all relevant datasets for the planned application. The system will then identify, calibrate/train, and execute the most suitable hydrological modeling workflow. The resulting climate impact assessment will quantify projected changes in key hydrological indicators under future climate scenarios, including streamflow (e.g., mean discharge), flood and drought frequency and intensity, seasonality shifts, and associated uncertainties. Results will be delivered as summary statistics (e.g., return periods, exceedance probabilities), graphs, and time series which can be further processed by advanced users.
- **AI-driven results interpretation.** To facilitate the interpretation of these results, we will develop an AI-powered analytics engine that will highlight key change patterns and provide actionable insights, making complex hydrological data and simulation results more accessible and intuitive to interpret for practitioners.

Our platform will revolutionize hydrological climate impact assessments by providing robust, reproducible, and user-friendly modeling pipelines and simulation analysis tools. It will empower diverse stakeholders (water resources managers, engineers and consultants, river basin authorities, hydropower operators, environmental agencies, risk managers and planners) to perform and interpret tailor-made hydrological climate impact assessments, therefore supporting adaptation to climate change. After project completion, the platform will be maintained and continuously enhanced by a startup to be founded during the project by the project partners, ensuring long-term impact and scalability.
