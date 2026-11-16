---
title: HydroImpact
description: HydroImpact is building a cloud-based platform that makes hydrological climate impact assessments accessible to water managers, engineers and planners.

hero:
  heading: Robust climate impact assessments for rivers across Europe
  lede: >-
    Climate change is reshaping how much water mountain rivers carry, and when.
    HydroImpact is building a cloud-based platform that lets water managers,
    engineers and planners assess how rivers in their own catchments may change,
    together with the full range of uncertainty.
  status: The project starts in May 2027, funded by BRIDGE.

# Modelling chain figure below the introduction (layouts/_partials/chain.html).
chain:
  title: How a hydrological climate impact assessment is built
  stages:
    - name: Emission scenarios
      text: Possible pathways of future greenhouse gas emissions
    - name: Global climate
      text: Simulated for the whole planet on a coarse grid
    - name: Regional climate
      text: Simulated over Europe on a finer grid
    - name: Local climate
      text: Adjusted to the catchment using observations
    - name: River impacts
      text: Changes in flow, floods, droughts and seasonality
  # role: "assess" (dashed blue) or "run" (solid blue) marks where HydroImpact comes in.
  steps:
    - name: Global climate models
    - name: Regional climate models
      role: assess
      note: Suitability of outputs assessed
    - name: Downscaling and bias adjustment
      role: run
      note: Evaluated and run
    - name: Hydrological models
      role: run
      note: Evaluated and run
  ours: >-
    HydroImpact does not run climate models. It assesses which regional climate
    simulations suit a given application, then evaluates combinations of
    downscaling, bias adjustment and hydrological models and runs them for your
    catchment.
  caption: >-
    Each step involves a choice between models and methods, and every combination
    gives a somewhat different answer.

why:
  heading: Why it matters
  text: |-
    Climate change is altering streamflow in mountain regions and in the lowlands that depend on them. Summer water availability is decreasing, while floods and droughts are intensifying, driven by changes in snow accumulation and melt, evapotranspiration, and the amount and intensity of precipitation.

    Quantifying these changes takes a long modelling chain: adjusting and downscaling climate data, calibrating hydrological models, then simulating how rivers respond to future climate. Each step involves choices, and the right combination depends on the question being asked. Doing this properly is time-consuming and often beyond what practitioners can take on. As a result, most climate impact studies stay in academia, and practical assessments tend to rely on a small subset of climate scenarios and models, which underestimates uncertainty.

build:
  heading: What we will build
  intro: >-
    A platform developed together with the people who will use it: water resources
    managers, engineers and consultants, river basin authorities, hydropower
    operators, environmental agencies, risk managers and planners.
  items:
    - title: Workflows tested for real applications
      text: >-
        We will evaluate combinations of climate data processing and hydrological
        models for specific uses, such as changes in water availability or flood
        frequency, across different regions of Europe, and quantify uncertainty
        along the whole modelling chain.
    - title: A platform that runs the whole chain
      text: >-
        Users define their catchment. The platform retrieves the relevant data,
        selects, calibrates and runs the most suitable workflow, and reports
        projected changes in mean flow, floods, droughts and seasonality, with
        their uncertainty.
    - title: Results that are easier to interpret
      text: >-
        An AI-assisted analysis layer will highlight the main patterns of change
        and what they mean in practice. Advanced users keep access to the full
        time series and statistics.
---

Climate change has a profound impact on streamflow in mountain regions and their dependent lowland areas, with summer water availability decreasing and extreme events such as floods and droughts intensifying. The underlying changes in key hydrological processes, including snow accumulation and melt, evapotranspiration, and precipitation amount and intensity, have severe impacts on water supply and management.

Quantifying such changes requires a hydrological modeling workflow that involves multiple steps, including bias-adjustment and downscaling of climate data, calibration/training and evaluation of hydrological models, and modeling the streamflow response to future climate conditions. While the individual components of this workflow have been well studied, analyzing the effectiveness of different combinations of modeling decisions for targeted applications, such as assessing changes in flood frequency in a specific region, is time-consuming and often beyond practitioners' expertise and technical capabilities. Consequently, most climate impact studies remain confined to academic settings, and impact assessments conducted by practitioners typically rely on incomplete workflows that consider small subsets of climate ensembles and hydrological models, which results in an underestimation of uncertainty.

In this project, we will make targeted hydrological climate impact assessments widely accessible to practitioners and engineers in Europe. To this end, we will build a cloud-based platform to facilitate, standardize, and enhance climate impact assessments in hydrology by integrating state-of-the-art modeling tools and employing a stakeholder co-design process. The aim of the platform is twofold: (i) ensure that tools and data are targeted to specific applications and (ii) offer reproducible workflows. To achieve this, our efforts will be structured along the following main axes:

- **Identification of suitable hydrological modeling workflows for a wide range of potential applications.** At the heart of our project lies the development and an extensive evaluation of modeling workflows, i.e., combinations of different climate data processing techniques, including bias adjustment and downscaling, and hydrological models. We will test the suitability of these workflows for specific applications, e.g., assessing changes in water availability or flood frequency, and for different regions in Europe. Developing suitable workflows will require the development of (i) strategies to facilitate the transferability of climate data processing and modeling tools across diverse regions and climatic conditions; and (ii) uncertainty quantification techniques that can quantify different sources of uncertainty along the modeling chain.
- **Cloud-based platform development building on user needs.** The platform will provide a unified and streamlined access to climate and hydrological data, enabling users to define their catchments of interest while automatically retrieving all relevant datasets for the planned application. The system will then identify, calibrate/train, and execute the most suitable hydrological modeling workflow. The resulting climate impact assessment will quantify projected changes in key hydrological indicators under future climate scenarios, including streamflow (e.g., mean discharge), flood and drought frequency and intensity, seasonality shifts, and associated uncertainties. Results will be delivered as summary statistics (e.g., return periods, exceedance probabilities), graphs, and time series which can be further processed by advanced users.
- **AI-driven results interpretation.** To facilitate the interpretation of these results, we will develop an AI-powered analytics engine that will highlight key change patterns and provide actionable insights, making complex hydrological data and simulation results more accessible and intuitive to interpret for practitioners.

Our platform will revolutionize hydrological climate impact assessments by providing robust, reproducible, and user-friendly modeling pipelines and simulation analysis tools. It will empower diverse stakeholders (water resources managers, engineers and consultants, river basin authorities, hydropower operators, environmental agencies, risk managers and planners) to perform and interpret tailor-made hydrological climate impact assessments, therefore supporting adaptation to climate change. After project completion, the platform will be maintained and continuously enhanced by a startup to be founded during the project by the project partners, ensuring long-term impact and scalability.
