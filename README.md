# owf-data-co-legislature-districts #

This repository contains [Open Water Foundation (OWF)](https://openwaterfoundation.org)
dataset files for Colorado State legislature districts,
based on [Colorado Independent Redistricting Commissions (CIRC)](https://redistricting.colorado.gov/content/senate-final-approved-errata) data.

This repository contains the workflow to convert the CIRC data from zipped shapefiles to GeoJSON files.
The dataset files are also published on
[`data.openwaterfoundation.org`](https://data.openwtaerfoundation.org)
and are used in data analyses and web applications.

The following sections provide a summary of the project repository:

* [Repository Contents](#repository-contents)
* [How to Use the Data](#how-to-use-the-data)
* [License](#license)
* [Maintainers](#maintainers)

## Repository Contents ##

The repository contains the following:

```text
/C/Users/user/                              Windows user files.
  owf-dev/                                  Open Water Foundation development files.
    data.openwaterfoundation.org/
      git-repos/
---------------- above folders are recommended --------------------
        owf-website-data/                   Repository that provides shared files to create dataset cloud landing page.
        owf-data-co-legislature-districts/  This repository.
          .gitattributes                    Git configuration file indicate repository configuration,
                                            in particular handling of line-ending and binary files.
          .gitignore                        Git configuration file to ignore files that should not be committed to the repository.
          README.md                         This file.
          versions/                         Folders containing local copy of data versions, corresponding to data provider publishing dates.
            2021/                           Results of the 2021 redistricting.
              data/                         The data files for the dataset, output from the workflow.
              downloads/                    Downloaded files for the dataset, from the original source.
              workflow/                     Workflow files to process the dataset.
            2011/                           Results of the 2011 redistricting (manually processed).
              data/                         The data files for the dataset, output from the workflow.
              workflow/                     Workflow files to process the dataset.
```

## How to Use the Data ##

The GeoJSON files can be used directly by GIS and web mapping applications.

## License ##

The data from the State of Colorado are public.
No restrictions are currently placed on the OWF dataset.
Using attribution consistent with the following license is appreciated.

[Attribution-ShareAlike 4.0 International](https://creativecommons.org/licenses/by-sa/4.0/)

## Maintainers ##

Steve Malers (@smalers, steve.malers@openwaterfoundation.org) is the primary contact.
