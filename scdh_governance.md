Data Access and Governance
================
Ben Matthews
2023-07-17

## The combined datasets

This Hackathon uses the sweeps of the [Scottish Crime and Justice Survey (SCJS)](https://www.gov.scot/collections/scottish-crime-and-justice-survey/)
from the [UK Data Service (UKDS)](https://beta.ukdataservice.ac.uk/datacatalogue/series/series?id=2000046).

We have provided a harmonized version of these datasets to help teams in
their analyses. Stuart from Scottish Government has done an amazing job
of pulling the individual datasets available from UKDS together - you
can see his hard work at
<https://github.com/DataScienceScotland/sccjr-hackathon-2023>.

The page linked above contains links to the individual sweeps of the
SCJS available through UKDS, and a series of `R` scripts used to
harmonize the datasets and combine them into a single analytical
dataset. As part of this process we have removed some variables from the
SCJS - if you are feeling intrepid you are welcome to spin up your own
harmonized dataset from the individual sweeps and include any variables you like, but we don’t recommend
this.

You can access the harmonized versions of the datasets [via this link](https://stir-my.sharepoint.com/:f:/r/personal/bm47_stir_ac_uk/Documents/research/scottish_crime_data_hackathon/hackathon_data?csf=1&web=1&e=nwmVcs)

This link is restricted and will only work with the email address that
you used to register for the UKDS, and will only be activated once you
have confirmed that you have registered for UKDS and Ben has added you
to the UKDS project.

## Responsible usage of the SCJS

Use of SCJS must be in line with the UKDS [End User License
Agreement](https://ukdataservice.ac.uk/app/uploads/cd137-enduserlicence.pdf).

Some key points to note for the Hackathon:

- Please **do not** share either the original data from UKDS or the
  harmonized datasets with anyone outwith the Hackathon. If you accidentally delete
  the data you’re working on, please download a new copy from the link
  above or from UKDS. 
- All the results of our research must be non-commercial. So if you were
  thinking of monetizing your analysis somehow please do not!
- It is not specifically included in the restrictions for using SCJS but
  we recommend that if you want to include frequency tables in your
  outputs that you do not include any cells with fewer than 10 cases.
  This abides by principles of [Statistical Disclosure
  Control](https://dam.ukdataservice.ac.uk/media/622521/thf_datareport_aw_web.pdf)
  used in secure research environments.
