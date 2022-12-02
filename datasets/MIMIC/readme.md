# MIMIC IV

MIMIC is an electronic health record database that is widely used around the world in research and education. 
The authors cited below carried out work to convert the latest version of MIMIC - MIMIC-IV - into the Observational Medical Outcomes Partnership (OMOP) model.

This repo contains a demo version of the dataset, based on a 100 patient subset of the full MIMIC-IV dataset for use in the Eunomia package. 
The following three modules of the MIMIC-IV dataset were included:

core: patient stay information (i.e. admissions and transfers)
hosp: hospital level data for patients: labs, micro, and electronic medication administration
icu: Event tables from the ICU, similar to those in MIMIC-III [6,7]

The csv files were downloaded on Dec 1, 2022 from https://physionet.org/content/mimic-iv-demo-omop/0.9/

**Citations**

Kallfelz, M., Tsvetkova, A., Pollard, T., Kwong, M., Lipori, G., Huser, V., Osborn, J., Hao, S., & Williams, A. (2021). MIMIC-IV demo data in the OMOP Common Data Model (version 0.9). PhysioNet. https://doi.org/10.13026/p1f5-7x35.


Goldberger, A., Amaral, L., Glass, L., Hausdorff, J., Ivanov, P. C., Mark, R., ... & Stanley, H. E. (2000). PhysioBank, PhysioToolkit, and PhysioNet: Components of a new research resource for complex physiologic signals. Circulation [Online]. 101 (23), pp. e215–e220.