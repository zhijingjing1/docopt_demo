Submitting Author: 
- Jingjing Zhi ([@zhijingjing1](https://github.com/zhijingjing1))
- Fei Chang ([@fei-chang](https://github.com/fei-chang))
- Mengyuan Zhu ([@Julie-M-Zhu](https://github.com/Julie-M-Zhu))
 
Repository: [ploteasyr](https://github.com/UBC-MDS/ploteasyr/tree/master)

Version submitted: v0.2.0 (TBD)

Editor: <!--editor--> TBD <!--end-editor-->

Reviewers: <!--reviewers-list--> TBD <!--end-reviewers-list-->
<!--due-dates-list--><!--end-due-dates-list-->

Archive: TBD

Version accepted: TBD

---



-   Paste the full DESCRIPTION file inside a code block below:

```
Package: ploteasyr
Title: Plot easily with default theme and settings (One Line, Title Case)
Version: 0.0.0.9000
Authors@R: 
    person(given = "Mengyuan",
           family = "Zhu",
           role = c("aut", "cre"),
           email = "zhumengyuan@126.com"),
    person(given = "Jingjing",
           family = "Zhi",
           role = c("aut", "cre"),
           email = "jzhi079@uottawa.ca"),
    person(given = "Fei",
           family = "Chang",
           role = c("aut", "cre"),
           email = "fc1271@nyu.edu"))
    )
           
Description: Plot easily with default theme and settings.
License: GNU LICENSE
Encoding: UTF-8
LazyData: true
Roxygen: list(markdown = TRUE)
RoxygenNote: 7.1.1
Imports: 
    ggplot2,
    dplyr,
    magrittr,
    testthat,
    palmerpenguins,
    stringr,
    ggthemes,
    utils,
    covr,
    imputeR,
    scales,
    tidyr,
    tidyselect,
    stats,
    rlang
Suggests: 
    testthat (>= 3.0.0)
Config/testthat/edition: 2
URL: https://github.com/UBC-MDS/ploteasyr/tree/master
BugReports: https://github.com/UBC-MDS/ploteasyr/issues

```


## Scope

- Please indicate which category or categories from our [package fit policies](https://ropensci.github.io/dev_guide/policies.html#package-categories) this package falls under: (Please check an appropriate box below. If you are unsure, we suggest you make a pre-submission inquiry.):

	- [ ] data retrieval
	- [ ] data extraction
	- [ ] data munging
	- [ ] data deposition
	- [ ] workflow automation
	- [ ] version control
	- [ ] citation management and bibliometrics
	- [ ] scientific software wrappers
	- [ ] field and lab reproducibility tools
	- [ ] database software bindings
	- [ ] geospatial data
	- [ ] text analysis
	- [x] data visualization  

- Explain how and why the package falls under these categories (briefly, 1-2 sentences):

ploteasyr offers beginner-friendly functions to do data visualizations. It has functionality to plot histogram, scatter plot and bar plot. The functions have build-in theme and other settings, which are complicated for the beginners of R but are compulsory for plotting in mainstream plotting packages like ggplot. 

-   Who is the target audience and what are scientific applications of this package?

The target audience would be people who are new to R and are interested in simple data visualization.

-   Are there other R packages that accomplish the same thing? If so, how does yours differ or meet [our criteria for best-in-category](https://ropensci.github.io/dev_guide/policies.html#overlap)?

There are other R packages that accomplish the similar thing such as "SmartEDA" or "ggplot". However, ploteasyr is more friendly to new learner of R, easier to understand and focus on three kinds of plots. 

-   (If applicable) Does your package comply with our [guidance around _Ethics, Data Privacy and Human Subjects Research_](https://devguide.ropensci.org/policies.html#ethics-data-privacy-and-human-subjects-research)?

Not applicable

-   If you made a pre-submission enquiry, please paste the link to the corresponding issue, forum post, or other discussion, or @tag the editor you contacted.

Not applicable

## Technical checks

Confirm each of the following by checking the box.

- [x] I have read the [guide for authors](https://devguide.ropensci.org/guide-for-authors.html) and [rOpenSci packaging guide](https://devguide.ropensci.org/building.html).

This package:

- [x] does not violate the Terms of Service of any service it interacts with.
- [x] has a CRAN and OSI accepted license.
- [x] contains a [README with instructions for installing the development version](https://ropensci.github.io/dev_guide/building.html#readme).
- [x] includes [documentation with examples for all functions, created with roxygen2](https://ropensci.github.io/dev_guide/building.html#documentation).
- [x] contains a vignette with examples of its essential functions and uses.
- [x] has a [test suite](https://ropensci.github.io/dev_guide/building.html#testing).
- [x] has [continuous integration](https://ropensci.github.io/dev_guide/ci.html), including reporting of test coverage using services such as Travis CI, Coveralls and/or CodeCov.

## Publication options

- [ ] Do you intend for this package to go on CRAN?
- [ ] Do you intend for this package to go on Bioconductor?

- [ ] Do you wish to submit an Applications Article about your package to [Methods in Ecology and Evolution](http://besjournals.onlinelibrary.wiley.com/hub/journal/10.1111/(ISSN)2041-210X/)? If so:

<details>
<summary>MEE Options</summary>

- [ ] The package is novel and will be of interest to the broad readership of the journal.
- [ ] The manuscript describing the package is no longer than 3000 words.
- [ ] You intend to archive the code for the package in a long-term repository which meets the requirements of the journal (see [MEE's Policy on Publishing Code](http://besjournals.onlinelibrary.wiley.com/hub/journal/10.1111/(ISSN)2041-210X/journal-resources/policy-on-publishing-code.html))
- (*Scope: Do consider MEE's [Aims and Scope](http://besjournals.onlinelibrary.wiley.com/hub/journal/10.1111/(ISSN)2041-210X/aims-and-scope/read-full-aims-and-scope.html) for your manuscript. We make no guarantee that your manuscript will be within MEE scope.*)
- (*Although not required, we strongly recommend having a full manuscript prepared when you submit here.*)
- (*Please do not submit your package separately to Methods in Ecology and Evolution*)

</details>

## Code of conduct

- [x] I agree to abide by [rOpenSci's Code of Conduct](https://ropensci.github.io/dev_guide/policies.html#code-of-conduct) during the review process and in maintaining my package should it be accepted.
