# Industrial ML Datasets

The following is a curated list of datasets, publically available for machine learning research in the area of manufacturing.

:heavy_check_mark: indicates a preset split between training and testing data.

:globe_with_meridians: indicates, that the test set labels are hidden behind an evaluation server.

## Predictive Maintenance and Condition Monitoring

 Name | Year | Feature Type | Feature Count | Target Variable | Instances | Official Train/Test Split | Data Source | Format | License |  |
 ---- | ---- | ---- | ---- | ---- | ---- | ---- | ---- | ---- | ---- | ----
 **Diesel Engine Faults Features** <br> Fault detection based on pressure curves and vibration. | 2020 | Signal | 84 | C (4) | 3.500 |  | Synthetic | MAT | CC BY 4.0 | [Link](https://data.mendeley.com/datasets/k22zxz29kr/1)
 **Degradation of a Cutting Blade** <br> Wrapping machine process data over 12 months with a degrading cutting tool. | 2019 | Signal | 9 | C (8) / R | 1.062.912 |  | Real | CSV | CC BY-SA 3.0 | [Link](https://www.kaggle.com/inIT-OWL/one-year-industrial-component-degradation)
 **CNC Mill Tool Wear** <br> CNC process data of wax milling with worn/unworn tools. | 2018 | Signal | 48 | C (3*2) | 25.286 |  | Real | CSV | CC0: Public Domain | [Link](https://www.kaggle.com/shasun/tool-wear-detection-in-cnc-mill)
 **Condition Monitoring of Hydraulic Systems** <br> Test rig process data of multiple load cycles with various fault types and severity levels. | 2018 | Signal | 17 | C (5*(24)) | 2.205 |  | Real | Non-Standard | ? | [Link](https://archive.ics.uci.edu/ml/datasets/Condition+monitoring+of+hydraulic+systems)
 **Production Plant Data for Condition Monitoring** <br> nonymized process data of component run-to-failure experiments. | 2018 | Signal | 26 | - | 228.414 |  | Real | CSV | CC BY-SA 3.0 | [Link](https://www.kaggle.com/inIT-OWL/production-plant-data-for-condition-monitoring)
 **Versatile Production** <br> Popcorn production process data with multiple process steps. | 2018 | Signal | 5-85 | - | 80.000 |  | Real | CSV | CC BY-NC-SA 4.0 | [Link](https://www.kaggle.com/inIT-OWL/versatileproductionsystem)
 **Degradation Measurement of Robot Arm Position Accuracy** <br> Target- and actual values of robotic arm tool position, velocity and current for health assessment. | 2017 | Signal | 73 | - | 155.000 |  | Real | CSV | ? | [Link](https://www.nist.gov/el/intelligent-systems-division-73500/degradation-measurement-robot-arm-position-accuracy)
 **APS Failure at Scania Trucks** <br> Anonymized counters and histograms for air pressure system fault detection. | 2016 | Signal | 170 | C (2) | 76.000 | :heavy_check_mark: | Real | CSV | GNU General Public License | [Link](https://archive.ics.uci.edu/ml/datasets/APS+Failure+at+Scania+Trucks)
 **Maintenance of Naval Propulsion Plants** <br> Gas turbine process data for component decay state prediction.| 2016 | Signal | 16 | R | 11.934 |  | Synthetic | Non-Standard | <details><summary> More Information </summary>Use of this dataset in publications must be acknowledged by referencing the following publication: <br> A. Coraddu, L. Oneto, A. Ghio, S. Savio, D. Anguita, M. Figari, Machine Learning Approaches for Improving Condition?Based Maintenance of Naval Propulsion Plants, Journal of Engineering for the Maritime Environment, 2014, DOI: 10.1177/1475090214540874, (In Press)</details> | [Link](http://archive.ics.uci.edu/ml/datasets/Condition+Based+Maintenance+of+Naval+Propulsion+Plants)
 **Plant Fault Detection** <br> Anonymized process data for plant fault detection. | 2015 | Signal | 10 | C (6) | 8.938.370 |  | Real | CSV | ? | [Link](https://github.com/robot007/PHM15)
 **Asset Failure and Replacement** <br> Anonymized data for asset fault detection. | 2014 | Signal | 1 | C (2) | 447.341 | :heavy_check_mark: :globe_with_meridians: | Real | CSV | ? | [Link](https://phmsociety.org/conference/annual-conference-of-the-phm-society/annual-conference-of-the-prognostics-and-health-management-society-2014/phm-data-challenge-2)
 **Maintenance Action Recommendation** <br> Anonymized process and maintenance data of an industrial asset for maintenance action recommendation.| 2013 | Signal | 32 | C (14) | 2.097.152 | :heavy_check_mark: :globe_with_meridians: | Real | CSV | ? | [Link](https://phmsociety.org/conference/annual-conference-of-the-phm-society/annual-conference-of-the-prognostics-and-health-management-society-2013/phm-data-challenge/)
 **Anemometer Fault Detection** <br> Anemometer measurements for fault detection. | 2011 | Signal | 16 <br> 16-20 | - | 345.700 <br> 208.800 | :heavy_check_mark: :globe_with_meridians: | Real | Non-Standard | ? | [Link](https://phmsociety.org/phm_competition/2011-phm-society-conference-data-challenge/)
 **Gearbox Fault Detection** <br> Test rig accelerometer data for fault detection.| 2009 | Signal | 3 | - | > 10 Mio. |  | Real | CSV | ? | [Link](https://c3.nasa.gov/dashlink/resources/997/)
 **Li-Ion Battery Aging** <br> Battery test rig data during charge and discharge cycles for degradation detection.| 2008 | Signal | 12 | - | 2.167 |  | Real | MAT | N/A | [Link](https://c3.nasa.gov/dashlink/resources/133/)
 **Turbofan Engine Degradation Simulation** <br> C-MAPSS simulation sensor data of various conditions and fault modes.| 2008 | Signal | 26 | - | 262.256 | :heavy_check_mark: | Synthetic | Non-Standard | ? | [Link](https://c3.nasa.gov/dashlink/resources/139/)
 **Bearing** <br> Bearing test rig accelerometer data of run-to-failure experiments.| 2007 | Signal | 4-8 | - | 61.440 |  | Real | CSV | ? | [Link](https://ti.arc.nasa.gov/tech/dash/groups/pcoe/prognostic-data-repository/)
 **Milling** <br> Milling process- and external sensor data for tool wear detection. | 2007 | Signal | 13 | R | 1.503.000 |  | Real | MAT | ? | [Link](https://ti.arc.nasa.gov/tech/dash/groups/pcoe/prognostic-data-repository/)
 **CWRU Bearing Data** <br> Bearing test rig accelerometer data for fault detection.| n.A. | Signal | 5 | C (2) | > 10 Mio. |  | Real | MAT | ? | [Link](https://csegroups.case.edu/bearingdatacenter)
 

## Process Monitoring

Name | Year | Feature Type | Feature Count | Target Variable | Instances | Official Train/Test Split | Data Source | Format | License | |
 ---- | ---- | ---- | ---- | ---- | ---- | ---- | ---- | ---- | ---- | ----
**High Storage System Anomaly Detection** <br> Storage test rig process data for anomaly detection.| 2018 | Signal | 20 | C (2) | 91.000 |  | Synthetic | CSV | CC-BY-NC-SA 4.0 | [Link](https://www.kaggle.com/inIT-OWL/high-storage-system-data-for-energy-optimization)
**Genesis Pick-and-Place Demonstrator** <br> Material sorting test rig process data for anomaly detection.| 2018 | Signal | 23 | C (3) | 32.440 |  | Real | CSV | CC-BY-NC-SA 4.0 | [Link](https://www.kaggle.com/inIT-OWL/genesis-demonstrator-data-for-machine-learning/home)
**Tennessee Eastman Process Simulation Dataset** <br> Simulated chemical process data for anomaly detection with different fault types.| 2017 | Signal | 51 | C (21) / R | > 10 Mio. | :heavy_check_mark: | Synthetic | RData | <details><summary> More Information </summary> The person who owns, created, or contributed a work to the data or work provided here dedicated the work to the public domain and has waived his or her rights    to the work worldwide under copyright law. You can copy, modify, distribute, and perform the work, for any lawful purpose, without asking permission.</details> | [Link](https://dataverse.harvard.edu/dataset.xhtml?persistentId=doi:10.7910/DVN/6C3JR1)
**Robot Execution Failures** <br> Force and torque measurements of an industrial robot with different erroneous operating conditions.| 1999 | Signal | 89 | C (13) | 463 |  | Real | Non-Standard | ? | [Link](http://archive.ics.uci.edu/ml/datasets/Robot+Execution+Failures)
**Mechanical Analysis** <br> Vibration measurements of electromechanical devices with different erroneous operating conditions.| 1990 | Signal | 7 | C (6) | 209 | :heavy_check_mark: | Real | MAT | ? | [Link](http://archive.ics.uci.edu/ml/datasets/Mechanical+Analysis)
**CWRU Bearing Data** Bearing test rig accelerometer data for anomaly detection.| n.A. | Signal | 5 | C (2) | > 10 Mio. |  | Real | MAT | ? | [Link](https://csegroups.case.edu/bearingdatacenter)


## Predictive Quality and Quality Inspection

Name | Year | Feature Type | Feature Count | Target Variable | Instances | Official Train/Test Split | Data Source | Format | License | |
 ---- | ---- | ---- | ---- | ---- | ---- | ---- | ---- | ---- | ---- | ----
**Casting Product Quality Inspection** <br> Grayscale images of pump impeller castings with and without defects.| 2020 | Image | 300x300 <br> 512x512 | C (2) | 7.348 | :heavy_check_mark: | Real | JPG | CC-BY-NC-ND 4.0 | [Link](https://www.kaggle.com/ravirajsinh45/real-life-industrial-dataset-of-casting-product)
**GC10-DET Defect Location for Metal Surface** <br> Grayscale images of metal surfaces with various defect types and corresponding bounding box annotations. | 2020 | Image | Varying | C (10) | 3.570 |  | Real | JPG, XML | ? | [Link](https://www.kaggle.com/zhangyunsheng/defects-class-and-location) 
**Mechanic Component Images** <br> Grayscale images of air conditioner pistons with various defect types. | 2020 | Image | 86x90 | C (3) | 285 |  | Real | PNG | ? | [Link](https://www.kaggle.com/satishpaladi11/mechanic-component-images-normal-defected)
**Multi-Stage Continuous Flow Process** <br> Anonymized process data of a production line with quality measurements of part dimensions. | 2020 | Signal | 116 | - | 14.088 |  | Real | CSV | ? | [Link](https://www.kaggle.com/supergus/multistage-continuousflow-manufacturing-process/metadata)
**Plastic Extrusion Defects** <br> Process data of a plastic extrusion process.| 2020 | Signal | 470 | - | 226.536 |  | Real | CSV | CC BY-NC-ND 4.0 | [Link](https://www.kaggle.com/podsyp/find-a-defect-in-the-production-extrusion-line/metadata)
**AITEX** <br> Grayscale images of textile fabrics with various defect types and corresponding segmentation masks. | 2019 | Image | 4096x256 | C (13) | 245 |  | Real | PNG, Mask | ? | [Link](https://www.aitex.es/afid)
**Deep PCB** <br> Grayscale images of circuit boards with various defect types and corresponding bounding box annotations. | 2019 | Image | 640x640 | C (7) | 1.500 | :heavy_check_mark: | Real | JPG, Mask | only for research purpose | [Link](https://github.com/Charmve/Surface-Defect-Detection/tree/master/DeepPCB)
**Severstal Steel Defect Detection** <br> Grayscale images of steel surfaces with various defect types and corresponding segmentation polygons. | 2019 | Image | 1600x256 | C (5) | 18.074 | :heavy_check_mark: :globe_with_meridians: | Real | JPG, CSV | ? | [Link](https://www.kaggle.com/c/severstal-steel-defect-detection/overview)
**Turning Dataset for Chatter Diagnosis** <br> Sensory data of a turning test rig and varying strengths of chatter. | 2019 | Signal | 8 | C (4) | > 10 Mio. |  | Real | MAT | CC BY 4.0 | [Link](http://dx.doi.org/10.17632/hvm4wh3jzx.1)
**Magnetic Tile Defect** <br> Grayscale images of magnetic tile surfaces with various defect types and corresponding segmentation masks. | 2018 | Image | 248x373 | C (6) | 1.344 |  | Real | JPG, PNG | ? | [Link](https://github.com/abin24/Magnetic-tile-defect-datasets.)
**TIG Welding** <br> Grayscale images of a welding process with various defect types. | 2018 | Image | 800x974 | C (6) | 33.254 | :heavy_check_mark: | Real | PNG, JSON | CC BY-SA 4.0 | [Link](https://www.kaggle.com/danielbacioiu/tig-aluminium-5083)
**Mining Process** <br> Process data of a mining process for impurity prediction in ore concentrate. | 2017 | Signal | 24 | R | 737.454 |  | Real | CSV | CC0: Public Domain | [Link](https://www.kaggle.com/edumagalhaes/quality-prediction-in-a-mining-process)
**Bosch Production Line Performance** <br> Anonymized process data of production lines with and without defects. | 2016 | Signal | 4264 | C (2) | 2.368.435 | :heavy_check_mark: :globe_with_meridians: | Real | CSV | ? | [Link](https://www.kaggle.com/c/bosch-production-line-performance/overview)
**WM811K Wafer Maps** <br> Defect matrices of semiconductor wafers with various defect types. | 2014 | 2D Defect Matrix | Varying | C (9) | 811.457 |  | Real | MAT | ? | [Link](http://mirlab.org/dataSet/public)
**NEU Surface Defect Database** <br> Grayscale images of metal surfaces with various defect types and corresponding bounding box annotations. | 2013 | Image | 200x200 | C (6) | 1.800 |  | Real | BMP, XML | ? | [Link](http://faculty.neu.edu.cn/yunhyan/NEU_surface_defect_database.html)
**Steel Plate Faults** <br> Geometric measurements of steel plates with various defect types. | 2010 | Signal | 27 | C (7) | 1.941 |  | Real | CSV | ? | [Link](https://www.kaggle.com/uciml/faulty-steel-plates)
**HCI Industrial Optical Inspection** <br> Synthetic grayscale images of textured surfaces with corresponding defect ellipses. | 2007 | Image | 512x512 | C (2) | 16.100 | :heavy_check_mark: | Synthetic | PNG, Non-Standard | ? | [Link](https://hci.iwr.uni-heidelberg.de/content/weakly-supervised-learning-industrial-optical-inspection)

## Process Parameter Optimization

 Name | Year | Feature Type | Feature Count | Instances | Official Train/Test Split | Data Source | Format | License | |
 ---- | ---- | ---- | ---- | ---- | ---- | ---- | ---- | ---- | ----
 **Laser Welding** <br> Process parameter recordings for correlation with weld quality indicators such as weld depth and geometrical dimensions. | 2020 | Signal | 13 | 361 |  | Real | XLS | CC BY 4.0 | [Link](http://dx.doi.org/10.17632/2s5m3crbkd.2)
 **3D Printer** <br> Process parameters of a 3D printer for correlation with print quality indicators such as roughness, tension and elongation. | 2018 | Signal | 12 | 50 |  | Real | CSV | ? | [Link](https://www.kaggle.com/afumetto/3dprinter)
 **Tool Path Generation** <br> Shape deviation measurements and corresponding simulated cutting conditions. | 2018 | Signal | 9 | 4.968 |  | Real | CSV | CC BY 4.0 | [Link](https://data.mendeley.com/datasets/smyg6cfwpk/1)
 **Mercedes-Benz Greener Manufacturing** <br> Car feature configurations to be correlated with the required test time of the configurations. | 2017 | Signal | 378 | 8.420 | :heavy_check_mark: :globe_with_meridians: | Real | CSV | ? | [Link](https://www.kaggle.com/c/mercedes-benz-greener-manufacturing/data)
 **SECOM** <br> Semiconductor process measurements and corresponding yields for determination of key factors to yield.| 2008 | Signal | 591 | 1.567 |  | Real | Non-Standard | ?| [Link](http://archive.ics.uci.edu/ml/datasets/SECOM)

 
