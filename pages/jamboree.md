---
layout: page-fullwidth
title: "Data Jamboree"
header: no
permalink: /jamboree/
---

Data jamboree is a party of different computing tools solving the same data
science problems. The [NYC Open Data of 311 Service
Requests](https://data.cityofnewyork.us/Social-Services/311-Service-Requests-from-2010-to-Present/erm2-nwe9)
contains all 311 requests of NYC from 2010 to present. We consider a subset,
requests created between 00:00:00 01/15/2023 and 24:00:00 01/21/2023, downloaded
on 02/22/2023 (data of the same creation time window downloaded at a later
time may be different as some open requests by 02/22/2023 could have been
closed. This subset is available in [CSV format](https://github.com/statds/ids-s23/blob/8c68649925d069a1d93a71022b87b26a61b0c180/data/nyc311_011523-012123_by022023.csv) from the course note repo
of the 2023 spring Introduction to Data Science at UConn.
Read the data dictionary to understand the meaning of the variables.


The scientific exercises of the jamboree are:

+ Data cleaning.
    - For ease of comparison across languages, make the column names consistent
      in style with lowercase using underscore to separate words within a name.
    - Check for obvious errors or inefficiencies. For example, are there records
      whose Closed Date is earlier than or exactly the same as the Created
      Date? Are their invalid values for any columns? Are any columns redundant?
    - Fill in missing values if possible. For example, if incident zip code is
      missing but the location is not, the zip code could be recovered by
      geocoding.
    - Summarize your suggestions to the data curator in several bullet points.
+ Data manipulation. Focus only on requests made to NYPD. 
    - Create a a new variable `duration`, which represents the time period from
      the Created Date to Closed Date. Note that duration may be censored for
      some requests.
    - Visualize the distribution of uncensored duration by weekdays/weekend and
      by borough, and test whether the distributions are
      the same across weekdays/weekends of their creation and across boroughs.
    - Basic information at the zipcode level such as population density, median
      home value, and median household income is available from the US
      Census. Convenient accesses are, for example, R package `zipcodeR` and
      Python package `uszipcode`; there seems to no Julia equivalent yet but
      Julia can call R or Python easily. Merge the zipcode level information
      with the NYPD requests data.
+ Data analysis. 
    - Define a binary variable `over3h` which is 1 if duration is greater than 3
      hours. Note that it can be obtained even for censored duration.
	- Build a logistic model to predict over3h using the 311 request data as
      well as those zip code level covariates. If your model has tuning
      parameters, justify their choices. Use appropriate metrics to assess the
      performance of the model.
    - Repeat the analysis with another model (e.g., random forest; neural
      network; etc.).
