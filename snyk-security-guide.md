# Synk Security Guide

## Searching for Vulnerabilities 

Step 1: Go to the Reports page

![Reports Page](./reports-page.png)

Step 2: Click Add filter and select CVE from the dropdown menu

![Filter by CVE](./filtering-by-cve.png)

Step 3: Enter the CVE you want to search for as the filter optionde

![Searching by CVE](./searching-by-cve.png)



## Searching for Malicious Packages

### Searching For Specific Packages 

Step 1: Go to the Dependencies page

![Dependencies Page](./dependencies-page.png)

Step 2: Filter for the type of package you want

![Filtering by Package Type](./filter-package-type.png)

Step: 3: Enter the specific package names in the search dropdown

![Searching for a Package](./searching-for-package.png)


### Searching For All Malicious 

Step 1: Go to the Reports page

![Reports Page](./reports-page.png)

Step 2: Click Add filter and select CWE from the dropdown menu

![Filtering for CWE](./filter-for-cwe.png)

Step 3: Enter CWE-506 (CWE for malicious packages) as the filter option

![Searching for CWE](./searching-for-cwe.png)

Step 4: Add a new filter of Type (projects) and the malicious package type you are searching for (i.e. Javascript (npm or yarn)) 

![Filtering by Package Type](./filtering-by-package-type.png)

![Filtering for npm](./filtering-for-npm.png)


## Searching Across All Organizations

- To search across all organisations use the Groups menu and select giffgaff Group.
- Use the Reports and Dependencies pages here to search for vulnerabilities and weaknesses across all organisations.

![Searching Across All Organizations](./search-across-all-org.png)


## Searching Across Individual Organizations

- To search individual organisations use the Organization menu and the Switch org button to find the organisation you want to search.
- Use the Reports and Dependencies pages here to search for vulnerabilities and weaknesses for a specific organisation

![Searching Across Individual Organizations](./search-across-individual-orgs.png)