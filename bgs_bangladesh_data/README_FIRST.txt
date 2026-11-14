bgs_bangladesh_data.zip  -  official BGS/DPHE files used by Environment_Thesis_Journal_Pipeline_v4.ipynb

Contents (unchanged copies of the downloaded files):
  NationalSurveyData.csv   DPHE/BGS National Hydrochemical Survey (3,534 records)
  NHSGeology.csv           surface geology and lithology matched to the national samples
  SpecialStudyData.csv     Special Study Areas (Chapai Nawabganj, Faridpur, Lakshmipur, multi-depth wells)
  MandariSurveyData.csv    Mandari village survey (236 private wells)
  BLatLong.csv             coastline and district boundary reference points (map background)

How to use with the notebook (set ONE of these, then run all cells):
  1. Host this zip at a direct-download URL (GitHub release asset or raw file, Zenodo, or a Google Drive
     share link) and paste the URL into cfg.dataset_url in Section 2. A URL ending in "/" is treated as a
     folder that holds the five CSV files individually.
  2. Or place this zip (or the five files) in the Colab working directory /content, in data/, or in a Google
     Drive folder named in cfg.drive_dir.
  3. On Kaggle, attach the files as a dataset input.

Terms and citation: check the BGS terms of use before redistributing these files. Cite as
Kinniburgh, D. G. and Smedley, P. L. (Eds.) (2001). Arsenic contamination of groundwater in Bangladesh,
British Geological Survey Technical Report WC/00/19. Official pages: https://www.bgs.ac.uk/groundwater/quality/
