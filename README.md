# Designing Dynamic Data-Driven Digital Twin Systems in Ecology

**Workshop @ European Conference on Ecological Modelling 2023**

**Name and affiliation:** _Taimur Khan ([taimur.khan@ufz.de](mailto:taimur.khan@ufz.de)), Helmholtz-UFZ (Community Ecology)_

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.8313064.svg)](https://doi.org/10.5281/zenodo.8313064)


> What systems design is not: an absolute truth. Design methods changes as use cases and technologies change.

Today's ecological modelling and simulation code typically only support static workflows. Users can only interact with the running code to terminate a run when input data and parameter files have been produced in advance and are read by the code at startup. If data re-integration is necessary, it is typically done manually using static, sanitised input files produced from data sources to interact with observation systems, data archives, and experiments. This presents a challenge in using legacy ecological models and simulations in Digital Twins.

Dynamic Data Driven Application Systems (or DDDAS, http://1dddas.org) is a conceptual framework that synergistically combines models and data in order to facilitate the analysis and prediction of physical phenomena. DDDAS is an emerging systems design approach that enables to measure physical processes more effectively and consequently update models and simulations. DDDAS and Digital Twins are a natural pairing that improve the combined capabilities of sensors, data, models, and choices. DDDAS incorporates additional data into an executing Digital Twin, and in reverse, enhance a Digital Twin to dynamically steer the decision on its physical asset.

In this workshop, participants will get the chance to dive into what DDDAS is and what possibilities it allows for designing Digital Twin systems in Ecology. Furthermore, examples of DDDAS in Digital Twin design will be presented.

![approach](/approach.png)

## Workshop Resources

- [slides.pdf](slides.pdf): Presentation at ECEM@2023
- [template.drawio](template.drawio) : Digital Twin Schema template for exercise (download and open on [draw.io](https://app.diagrams.net/))
- [DT Schema Gallery](https://drive.google.com/drive/folders/1_sx5-JHGgJZUw4GJjew5ngCf_DG671GD?usp=sharing):  Google Drive folder for DT Schema submissions of workshop participants

## Datasets
- [real-time.csv](real-time.csv) : Real-time Soil Moisture and Soil Temperature for Taimur's balcony soilbeds @60s resolution for ~ 3 days w/ watering events (waterpump)
- [historical.csv](historic.csv) : Historical Soil Moisture and Soil Temperature for Taimur's balcony soilbeds @4hr resolution for 1 month w/ watering events (rain + waterpump)

## Literature

- Blasch, Erik P., Frederica Darema, Sai Ravela, and Alex J. Aved, eds. Handbook of Dynamic Data Driven Applications Systems: Volume 1. Springer Nature, 2022.
- Darema, Frederica. "Dynamic data driven applications systems: A new paradigm for application simulations and measurements." In International conference on computational science, pp. 662-669. Berlin, Heidelberg: Springer Berlin Heidelberg, 2004.
- Ravela, Sai, and Adrian Sandu, eds. Dynamic Data-Driven Environmental Systems Science: First International Conference, DyDESS 2014, Cambridge, MA, USA, November 5-7, 2014, Revised Selected Papers. Vol. 8964. Springer, 2015.
- Segovia, Mariana, and Joaquin Garcia-Alfaro. "Design, modeling and implementation of digital twins." Sensors 22, no. 14 (2022): 5396.

## Videos

- Soil-Plant System DT: [https://www.youtube.com/watch?v=4tiinfz-0Tg](https://www.youtube.com/watch?v=4tiinfz-0Tg)

[![Soil-Plant System DT](https://img.youtube.com/vi/4tiinfz-0Tg/0.jpg)](https://www.youtube.com/watch?v=4tiinfz-0Tg)

