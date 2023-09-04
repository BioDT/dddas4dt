# Designing Dynamic Data-Driven Digital Twin Systems in Ecology

**Workshop @ European Conference on Ecological Modelling 2023**

**Name and affiliation:** _Taimur Khan ([taimur.khan@ufz.de](mailto:taimur.khan@ufz.de)), Helmholtz-UFZ (Community Ecology)_

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.8313875.svg)](https://doi.org/10.5281/zenodo.8313875)

> **What system design is not: an absolute truth. Design methods change, as use cases and technologies change.**

Today's ecological modelling and simulation code typically only support static workflows. Users can only interact with the running code to terminate a run when input data and parameter files have been produced in advance and are read by the code at startup. If data re-integration is necessary, it is typically done manually using static, sanitised input files produced from data sources to interact with observation systems, data archives, and experiments. This presents a challenge in using legacy ecological models and simulations in Digital Twins.

Dynamic Data Driven Application Systems (or DDDAS, http://1dddas.org) is a conceptual framework that synergistically combines models and data in order to facilitate the analysis and prediction of physical phenomena. DDDAS is an emerging systems design approach that enables to measure physical processes more effectively and consequently update models and simulations. DDDAS and Digital Twins are a natural pairing that improve the combined capabilities of sensors, data, models, and choices. DDDAS incorporates additional data into an executing Digital Twin, and in reverse, enhance a Digital Twin to dynamically steer the decision on its physical asset.

In this workshop, participants will get the chance to dive into what DDDAS is and what possibilities it allows for designing Digital Twin systems in Ecology. Furthermore, examples of DDDAS in Digital Twin design will be presented.

![approach](/approach.png)

## Workshop Resources

- [slides.pdf](slides.pdf): Presentation at ECEM@2023
- [template.drawio](template.drawio) : Digital Twin Schema template for exercise (download and open on [draw.io](https://app.diagrams.net/))
- [DT Schema Gallery](https://drive.google.com/drive/folders/1_sx5-JHGgJZUw4GJjew5ngCf_DG671GD?usp=sharing):  Google Drive folder for DT Schema submissions of workshop participants (Google sign-in required for upload)

## Exercise

Design a plant self-watering system using a DT using the DT Schema template above. System is described in the slides.

- System: Soil Watering DT
- 8 soil beds with sensor network
- Observational Data (from sensors):
  - Soil moisture (%)
  - Soil temperature (F)
- Control inputs:
  - WiFi controlled water pumps with on/off states.
- Model: ? (e.g. linear regression, rates-of-change)
- Use the DT schema template on draw.io to create a schema for a DDDAS-based DT of the given Soil Watering system that automates soil watering based on soil moisture and soil temperature data.

> **HINT:** Think about what other data sources can be added, what is the state space, what type of model, is needed and what components would be required.

**Soil beds**
![soilbeds](/soilbeds.png)

**Pl@ntNet Species Observations**

| Bed # | Species                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                 |
| ----- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| 1     | 1x[Lavandula angustifolia Mill.. ](https://identify.plantnet.org/k-world-flora/observations/1019806178)(English lavender)<br />1x [Verbena bonariensis L.](https://identify.plantnet.org/k-world-flora/observations/1019806181) (Purpletop vervain)                                                                                                                                                                                                                                                           |
| 2     | 1x[Capsicum](https://identify.plantnet.org/k-world-flora/observations/1019806183) [chinense](https://identify.plantnet.org/k-world-flora/observations/1019806183)[ Jacq.](https://identify.plantnet.org/k-world-flora/observations/1019806183) (Habanero)<br />1x [Fuchsia](https://identify.plantnet.org/k-world-flora/observations/1019806185) [magellanica](https://identify.plantnet.org/k-world-flora/observations/1019806185)[ Lam.](https://identify.plantnet.org/k-world-flora/observations/1019806185) (Fuchsia) |
| 3     | 1x[Capsicum frutescens L.](https://identify.plantnet.org/k-world-flora/observations/1019806186) (Capsicum)<br />1x [Borago officinalis L.](https://identify.plantnet.org/k-world-flora/observations/1019806187) (Borage)                                                                                                                                                                                                                                                                                      |
| 4     | 2x[Mentha spicata L.](https://identify.plantnet.org/k-world-flora/observations/1019806175) (Spearmint)<br />1x [Aloysia citrodora](https://identify.plantnet.org/k-world-flora/observations/1019806167) (Lemon verben)                                                                                                                                                                                                                                                                                        |
| 5     | 2x[Salvia officinalis L.](https://identify.plantnet.org/k-world-flora/observations/1019805839)(Sage)                                                                                                                                                                                                                                                                                                                                                                                                       |
| 6     | 1x[Capsicum annuum L.](https://identify.plantnet.org/k-world-flora/observations/1019806189) (Chilli Pepppers)<br />1x [Rheum rhaponticum L. ](https://identify.plantnet.org/k-world-flora/observations/1019806191)(Rhubarb)<br />1x [Solanum](https://identify.plantnet.org/k-world-flora/observations/1019806193) [pimpinellifolium](https://identify.plantnet.org/k-world-flora/observations/1019806193)[ L.](https://identify.plantnet.org/k-world-flora/observations/1019806193) (Currant tomato)                  |
| 7     | 2x[Capsicum frutescens L. ](https://identify.plantnet.org/k-world-flora/observations/1019806203)(Capsicum)                                                                                                                                                                                                                                                                                                                                                                                                 |

## Sample Datasets

- [real-time.csv](real-time.csv) : Real-time Soil Moisture and Soil Temperature for Taimur's balcony soilbeds @60s resolution for ~ 3 days+2 nights w/ watering events (waterpump)
- [historical.csv](historic.csv) : Historical Soil Moisture and Soil Temperature for Taimur's balcony soilbeds @4hr resolution for 1 month w/ watering events (rain + waterpump)

## Survey results

- [Pre-workshop survey](pre-survey.pdf)
- [Post-workshop survey]()

## Literature

- Blasch, Erik P., Frederica Darema, Sai Ravela, and Alex J. Aved, eds. Handbook of Dynamic Data Driven Applications Systems: Volume 1. Springer Nature, 2022.
- Darema, Frederica. "Dynamic data driven applications systems: A new paradigm for application simulations and measurements." In International conference on computational science, pp. 662-669. Berlin, Heidelberg: Springer Berlin Heidelberg, 2004.
- Ravela, Sai, and Adrian Sandu, eds. Dynamic Data-Driven Environmental Systems Science: First International Conference, DyDESS 2014, Cambridge, MA, USA, November 5-7, 2014, Revised Selected Papers. Vol. 8964. Springer, 2015.
- Segovia, Mariana, and Joaquin Garcia-Alfaro. "Design, modeling and implementation of digital twins." Sensors 22, no. 14 (2022): 5396.

## Videos

- Soil-Plant System DT: [https://www.youtube.com/watch?v=4tiinfz-0Tg](https://www.youtube.com/watch?v=4tiinfz-0Tg)

[![Soil-Plant System DT](https://img.youtube.com/vi/4tiinfz-0Tg/0.jpg)](https://www.youtube.com/watch?v=4tiinfz-0Tg)
