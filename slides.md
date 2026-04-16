---
theme: black
css: style.css
transition: convex
---

# Fish Industry Aquaculture

<!-- .slide: data-background="img/background-title.jpg" data-background-opacity="0.3" -->

The aquaculture industry is one of the fastest-growing sectors in the world, driven by increasing demand for sustainable seafood.

Note: Welcome the audience and introduce the topic of aquaculture growth.

---

## Overview

This presentation summarizes the computer vision technologies used in the industry, providing an overview of key challenges and potential solutions.

Note: Mention that computer vision is a key enabler for modernizing this sector.

---

## My Background: The FishScan Project

<div style="display: flex; align-items: center; justify-content: space-around;">
  <img src="https://web.archive.org/web/20141217042105im_/http://fishscanproject.com/var/ezwebin_site/storage/images/media/eu-prosjektweb/fishscan3/final-meeting/120514-1-eng-GB/Final-meeting_large.jpg" alt="FishScan Project Team" width="300">
  <img src="img/rigsetup.png" alt="Underwater Rig Setup" width="180">
</div>

- **Innovation:** Transitioned from manual sampling to **Automated 3D Biomass Estimation**.
- **Sensor Fusion:** Combined **Time-of-Flight (TOF) depth data** with **2D CCD intensity** to solve depth-invariance.
- **Challenges:** Engineered solutions for articulated deformations, viewpoint variations, and underwater occlusions.
- **Impact:** Focused on the critical industry need for precise pre-harvest size distribution (essential for **80% of sales**).

Note: My work involved building a multi-stage pipeline: Fish Detection → Contour Extraction → Volume-Biomass Estimation, utilizing Deformable Part Models (DPM) for aquatic species.

---

## Current State of the Sector

- Crucial component for sustainable seafood.
- Minimizes environmental impact.
- Faces challenges: disease outbreaks, feed costs, environmental concerns.

Note: Highlight the critical role of aquaculture as an alternative to wild-caught fish.

---

## Companies and Technologies

Summary of leading companies and technologies in the space:

- **Tidal**: AI-driven feed optimization and underwater robotics.
- **Stingray**: AI-guided laser sea lice removal and monitoring.
- **OptoScale**: Real-time biomass and welfare monitoring via the Bioscope.
- **Aquabyte**: AI-powered underwater monitoring and analytics.

Note: These companies represent the forefront of digital transformation in aquaculture.

---

## Stingray

<video data-autoplay loop muted width="100%" height="400px">
  <source src="https://stingrayonline.no/assets/bg-large-DDQn_ZKe.mp4" type="video/mp4">
</video>

<a href="https://www.stingray.no/en/technology/" target="_blank">Discover Stingray Technology</a>

- **Laser Sea Lice Removal:** Identifying parasites in real-time and firing laser pulses to kill them without harming the fish.
- **Real-time AI:** Stereo camera vision identifies parasites in milliseconds.
- **24/7 Monitoring:** Tracks biomass and welfare via Stingray Online.

Note: Stingray takes a direct, active approach to pest control using robotics and lasers, shifting from passive monitoring to active intervention.

---

## Tidal (Alphabet's X)

<video data-autoplay loop muted width="100%" height="auto">
  <source src="https://cdn.prod.website-files.com/66268f7920153766c84384ba/662c17d5b7209e4591a5b1b3_color-fish-trim3-transcode.mp4" type="video/mp4">
</video>

<iframe data-src="https://cdn.prod.website-files.com/66268f7920153766c84384ba/662dceab74811b48b7482b9e_fish-detection-without-fish-bg.svg" width="100%" height="200px"></iframe>

- **Autonomous Feeding:** AI-driven optimization to reduce waste.
- **Biomass Estimation:** Continuous, real-time growth monitoring.
- **Sea Lice Detection:** Automated health tracking.

Note: Tidal was incubated at Alphabet's X and focuses on using advanced robotics and AI to reduce the environmental impact of fish farming through optimized feeding.

---

## Aquabyte

![AI Detection Interface](img/lice-detection-ui.jpg)

- **Product:** Hammerhead Camera & AI Platform
- **Technology:** Captures 1M+ images daily, self-cleaning hardware.
- **Key Features:** Automatic sea lice counting, continuous biomass estimation, welfare monitoring.

Note: Aquabyte uses hardware-software integration. Their Hammerhead camera connects to cloud ML to provide actionable insights without manual handling.

---

## Aquabyte: Hammerhead Hardware

<iframe data-src="https://www.aquabyte.ai/categories/our-solution/hardware" width="100%" height="500px"></iframe>

- **The Hammerhead Camera:** Specialized underwater unit.
- **The Cabinet:** Pen-side unit for cloud connectivity.
- **The Winch:** Remote repositioning system.

Note: The hardware is designed for extreme underwater conditions, featuring self-cleaning technology to ensure consistent data quality.

---

## OptoScale

<img src="https://optoscale.no/wp-content/uploads/2021/08/BioScope-Transparent-800px-ref.png" alt="BioScope Hardware" width="300">

<a href="https://optoscale.no/wp-content/uploads/2021/08/optoscale_banner_web_v01_1_2.mp4" target="_blank">Watch Bioscope in Action</a>

- **Biomass Estimation:** Automating weight and growth tracking.
- **Sea Lice Counting:** Accurately measuring infestation levels.
- **Welfare Assessments:** Monitoring respiration and swimming behavior.

Note: The Bioscope hardware is designed to capture tens of thousands of images daily for comprehensive health tracking without manual handling.

---

## Technologies and Options for Growth

<iframe src="https://ourworldindata.org/grapher/aquaculture-farmed-fish-production?tab=map" loading="lazy" style="width: 80%; height: 500px; border: 0px none;" allow="web-share; clipboard-write"></iframe>

<small>Source: <a href="https://ourworldindata.org/fish-and-overfishing" target="_blank">Our World in Data</a></small>

- **Role of computer vision:** Addressing challenges of scale and sustainability.
- **Innovative solutions:** Driving continued, efficient growth.
- **Long-term impact:** Ensuring the viability of the industry.

Note: Emphasize that innovation is not just for efficiency but for long-term survival.

---

## Conclusion

The fish industry aquaculture sector is at a crossroads where technology like computer vision will be the key to sustainable growth.

Note: Summarize the main points and call for continued innovation.
