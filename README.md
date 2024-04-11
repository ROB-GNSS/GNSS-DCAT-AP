# GNSS-DCAT-AP

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.10955559.svg)](https://doi.org/10.5281/zenodo.10955559)

Draft of a DCAT-AP extension for GNSS observation data (GNSS-DCAT-AP) to facilitate GNSS data exchange. This proposal aims at facilitating the exchange of GNSS RINEX observation data in order to increase their Findability, Accessibility, Interoperability, and Re-usability (FAIR).

GNSS-DCAT-AP adds additional support for the following entities:
* GNSS observation data file (RINEX) and its header
* GNSS station
* GNSS antenna and receiver
* GNSS observation data generating software
* GNSS data repository

GNSS-DCAT-AP is currently used for the metadata attached to daily RINEX files accessible via [https://gnss.be/opendataportal/](https://gnss.be/opendataportal/) the and its RESTfulAPI.

 *A Simplified UML Class Diagram of the GNSS-DCAT-AP model. It extends DCAT-AP 2.1.0 introducing additional classes (**in blue**) and relationships*
 ![Simplified GNSS-DCAT-AP class diagram](Draft/gnss-dcat-ap_v0.3.png)
