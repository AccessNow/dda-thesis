# dda-thesis

Hi and thanks for visiting!

This data set was originally compiled for an undergraduate research project in international relations. 
Please reach out to the author at deniz@accessnow.org if you have questions about the data set (such as methodology, assumptions, etc.) or would like to re-use it for your own research / data viz project.

Below you can find a list of of contents, and their sources.


- Country: Country name, 41 included in total.

- oecd: Dummy variable, 1 for OECD members (34 in the data set) and 0 for non-members.

- eu: Dummy variable, 1 for EU members (28 in the data set) and 0 for non-members.

- eyes: Dummy variable, 1 for members of the Five Eyes intelligence partnership (UK, US, CA, AUS, NZ).

- developing: Dummy variable. Value is 1 for any country classified as "developing" according to World Bank lending categories.
Source: http://data.worldbank.org/about/country-and-lending-groups

- scode: Alpha country code, via Polity IV project. Facilitates merge with popular PoliSci data sets. 
Source: http://www3.nd.edu/~mcoppedg/crd/PolityIVUsersManualv2002.pdf

- population_estimate: From the United Nations Statistics Division, last updated February 17, 2015.
Source: http://unstats.un.org/unsd/demographic/products/vitstats/serATab2.pdf

- population_latest_cens: From the United Nations Statistics Division, used for verification.
Source: http://unstats.un.org/unsd/demographic/products/vitstats/

- percintuse13: Internet Users per 100 people, 2013 (latest available as of March 2015). 
ITU via World Bank World Development Indicators
Source: http://data.worldbank.org/indicator/IT.NET.USER.P2

- no_intusers13: Number of internet users in 2013.*
- no_intusers14: Number of internet users in 2014.*
*Two are same as ITU data was not available for 2014 by the time this data was compiled.

- totalaccreqs13: Total number of user information requests, per country, for 2013.**
Source: Compiled from transparency reports for 2013 (both halves) of Apple, Facebook, Google, Microsoft.
Apple: https://www.apple.com/privacy/docs/government-information-requests-20131105.pdf and https://www.apple.com/privacy/docs/government-information-requests-20131231.pdf
Facebook: Downloaded data sets via https://govtrequests.facebook.com/
Google: Downloaded data sets via https://www.google.com/transparencyreport/userdatarequests/countries/
Microsoft: Downloaded data sets via https://www.microsoft.com/about/corporatecitizenship/en-us/reporting/transparency/


- totalaccreqs14: Total number of user information requests, per country, for the first half of 2014.**
Source: Compiled from transparency reports for 2014 first half of Apple, Facebook, Google, Microsoft.
Apple: https://www.apple.com/privacy/docs/government-information-requests-20140630.pdf
Facebook: Downloaded data sets via https://govtrequests.facebook.com/
Google: Downloaded data sets via https://www.google.com/transparencyreport/userdatarequests/countries/
Microsoft: Downloaded data sets via https://www.microsoft.com/about/corporatecitizenship/en-us/reporting/transparency/

  **Latest access to above transparency reports was on June 8, 2015.

- survindex13: Number of user account informaton requests for 2013, coded per 100,000 internet users.

- survindex14: Number of user account informaton requests for 2014 (first half), coded per 100,000 intenet users.

- terrorindex14 and terrorindex13: Global Terrorism Index (GTI) is used to measure the direct and relative impacts of terrorism on a country. Compiled by the non-profit think tank Institute for Economics and Peace, the index “combines a number of factors associated with terrorist attacks to build a thorough picture of the impact of terrorism over a 10-year period.” 

For 2014, the 2014 edition is used: http://www.visionofhumanity.org/#/page/our-gti-findings

For 2013, the 2012 edition is used: http://economicsandpeace.org/wp-content/uploads/2011/09/2012-Global-Terrorism-Index-Report.pdf

- homiciderate12: Assault rates for 2012 (per 100,000 population). The data is compiled by United Nations Office on Drugs and Crime.
Source: https://www.unodc.org/gsh/en/data.html

- FHcl13inv: Inverted scores for Civil Liberties, from Freedom House's Freedom in the World 2014 edition.
Source: https://freedomhouse.org/report-types/freedom-world#.VXYCO2RViko
- FHcl14inv: Inverted scores for Civil Liberties, from Freedom House's Freedom in the World 2015 edition. 
Source: https://freedomhouse.org/report/freedom-world/freedom-world-2015

- gdppc: GDP / capita in current U.S. dollars for 2013, via World Bank.
Source: http://data.worldbank.org/indicator/NY.GDP.PCAP.CD
