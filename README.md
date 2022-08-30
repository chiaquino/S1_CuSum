# Reliably Mapping Low-intensity Forest Disturbance Using Satellite Radar Data 

Aquino C., Mitchard E.T.A., McNicol I.M., Carstairs H., Burt A., Puma Vilca B. L., Obiang Ebanega M., Modinga Dikongo A., Dassi C., Mayta S., Tamayo M., Grijalba P., Miranda F., Disney M.

# Abstract
In the last decades tropical forests have experienced increased fragmentation due to a global growing demand for agricultural and forest commodities. Satellite remote sensing offers a valuable tool for monitoring forest loss, thanks to the global coverage and the temporal consistency of the acquisitions. In tropical regions, C-band Synthetic Aperture Radar (SAR) data from the Sentinel-1 mission provides  cloud-free and open imagery on a 6 or 12-day repeat cycle, offering the unique opportunity to monitor forest disturbances in a timely and continuous manner. Despite recent advances, mapping subtle forest losses, such as those due to small-scale and irregular selective logging, remains problematic. A Cumulative Sum (CuSum) approach has been recently proposed for forest monitoring applications, with preliminary studies showing promising results. Unfortunately, the lack of accurate in-situ measurements of tropical forest loss has prevented a full validation of this approach, especially in the case of low-intensity logging. In this study, we used high-quality field measurements from the tropical Forest Degradation Experiment (FODEX), combining UAV LiDAR, Terrestrial Laser Scanning (TLS) and field-inventoried data of forest structural change collected in two logging concessions in Gabon and Peru. The CuSum algorithm was applied to VV-polarised Sentinel-1 ground range detected (GRD) time series to monitor a range of canopy loss events, from individual tree extraction to forest clear cuts. We developed a single change metric using the maximum of the CuSum distribution, retrieving location, time and magnitude of the disturbance events. A comparison of the CuSum algorithm with the LiDAR reference map resulted in a 78% success rate for the test site in Gabon and 65% success rate for the test site in Peru, for disturbances as small as 0.01 ha in size and for canopy height losses as fine as 10 m.  A correlation between the
change metric and above ground biomass (AGB) change was found with R2 = 0.95, and R2 = 0.83 for canopy height loss. From the regression model we directly estimated local AGB loss maps for the year 2020, at 1 ha scale and in percentages of AGB loss. Comparison with the Global Forest Watch (GFW) Tree Cover Loss (TCL) product showed a 61% overlap between the two maps when considering only deforested pixels, with 504 ha of deforestation detected by CuSum versus 348 ha detected by GFW. Low intensity disturbances captured by the CuSum method were largely undetected by GFW and by the SAR-based RADD Alert System. The results of this study confirm this approach as a simple and reproducible change detection method for monitoring and quantifying fine-scale to high intensity forest disturbances, even in the case of multi-storied and high biomass forests

-------------------------------------------------------------
CuSum algorithm code in support of the paper for mapping tropical forest degradation

Shield: [![CC BY 4.0][cc-by-shield]][cc-by]

This work is licensed under a
[Creative Commons Attribution 4.0 International License][cc-by].

[![CC BY 4.0][cc-by-image]][cc-by]

[cc-by]: http://creativecommons.org/licenses/by/4.0/
[cc-by-image]: https://i.creativecommons.org/l/by/4.0/88x31.png
[cc-by-shield]: https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey.svg
