Submitting Author:
- Jingjing Zhi ([@zhijingjing1](https://github.com/zhijingjing1))
- Fei Chang ([@fei-chang](https://github.com/fei-chang))
- Mengyuan Zhu ([@Julie-M-Zhu](https://github.com/Julie-M-Zhu))

Package Name: ploteasy

One-Line Description of Package: This is a python package that offers beginner-friendly functions for generating data visualization plots.

Repository Link: https://github.com/UBC-MDS/ploteasy

Version submitted: v0.3.0

Editor: TBD  

Reviewer 1: TBD  

Reviewer 2: TBD  

Archive: TBD  

Version accepted: TBD   

---

## Description

This is a python package that offers beginner-friendly functions to do data visualizations. The functions have build-in theme and other settings, which are complicated for the beginners of python but are compulsory for plotting in mainstream plotting packages like Altair. Also, potential users of Altair may take baby steps from PlotEasy, for its intuitive way to use and its similarity with the most well-know panda functions. PlotEasy can minimize the code when calling a plot in Python, and can path your journey to EDA as smooth as silk!

- The function plot_hist() draw histogram plot
- The function plot_scatter() draw scatter plot
- The function plot_bar() draw bar plot


## Scope 
- Please indicate which [category or categories][PackageCategories] this package falls under:
	- [ ] Data retrieval
	- [ ] Data extraction
	- [ ] Data munging
	- [ ] Data deposition
	- [ ] Reproducibility
	- [ ] Geospatial
	- [ ] Education
	- [x] Data visualization*

\* Please fill out a pre-submission inquiry before submitting a data visualization package. For more info, see [notes on categories][NotesOnCategories] of our guidebook.

- Explain how the and why the package falls under these categories (briefly, 1-2 sentences):

ploteasy falls under data visualization because it has functionality to make three kinds of plots.

-   Who is the target audience and what are scientific applications of this package?  

The target audience would be people who are new to Python and are interested in simple data visualization.

-   Are there other Python packages that accomplish the same thing? If so, how does yours differ?

There are other Python packages that accomplish the similar thing such as "Pandas Profiling" or "Altair". However, ploteasyr is more friendly to new learner of Python, easier to understand and focus on three plots. 

-   If you made a pre-submission enquiry, please paste the link to the corresponding issue, forum post, or other discussion, or `@tag` the editor you contacted:

NA

## Technical checks

For details about the pyOpenSci packaging requirements, see our [packaging guide][PackagingGuide]. Confirm each of the following by checking the box.  This package:

- [x] does not violate the Terms of Service of any service it interacts with. 
- [x] has an [OSI approved license][OsiApprovedLicense].
- [x] contains a README with instructions for installing the development version. 
- [x] includes documentation with examples for all functions.
- [x] contains a vignette with examples of its essential functions and uses.
- [x] has a test suite.
- [x] has continuous integration, such as Travis CI, AppVeyor, CircleCI, and/or others.

## Publication options

- [ ] Do you wish to automatically submit to the [Journal of Open Source Software][JournalOfOpenSourceSoftware]? If so:

<details>
 <summary>JOSS Checks</summary>  

- [ ] The package has an **obvious research application** according to JOSS's definition in their [submission requirements][JossSubmissionRequirements]. Be aware that completing the pyOpenSci review process **does not** guarantee acceptance to JOSS. Be sure to read their submission requirements (linked above) if you are interested in submitting to JOSS.
- [ ] The package is not a "minor utility" as defined by JOSS's [submission requirements][JossSubmissionRequirements]: "Minor ‘utility’ packages, including ‘thin’ API clients, are not acceptable." pyOpenSci welcomes these packages under "Data Retrieval", but JOSS has slightly different criteria.
- [ ] The package contains a `paper.md` matching [JOSS's requirements][JossPaperRequirements] with a high-level description in the package root or in `inst/`.
- [ ] The package is deposited in a long-term repository with the DOI: 

*Note: Do not submit your package separately to JOSS*
  
</details>

## Are you OK with Reviewers Submitting Issues and/or pull requests to your Repo Directly?
This option will allow reviewers to open smaller issues that can then be linked to PR's rather than submitting a more dense text based review. It will also allow you to demonstrate addressing the issue via PR links.

- [x] Yes I am OK with reviewers submitting requested changes as issues to my repo. Reviewers will then link to the issues in their submitted review.

## Code of conduct

- [x] I agree to abide by [pyOpenSci's Code of Conduct][PyOpenSciCodeOfConduct] during the review process and in maintaining my package should it be accepted.


**P.S.** *Have feedback/comments about our review process? Leave a comment [here][Comments]

## Editor and Review Templates

[Editor and review templates can be found here][Templates]

[PackagingGuide]: https://www.pyopensci.org/contributing-guide/authoring/index.html#packaging-guide

[PackageCategories]: https://www.pyopensci.org/contributing-guide/open-source-software-peer-review/aims-and-scope.html?highlight=data#package-categories

[NotesOnCategories]: https://www.pyopensci.org/contributing-guide/open-source-software-peer-review/aims-and-scope.html?highlight=data#notes-on-categories


[JournalOfOpenSourceSoftware]: http://joss.theoj.org/

[JossSubmissionRequirements]: https://joss.readthedocs.io/en/latest/submitting.html#submission-requirements

[JossPaperRequirements]: https://joss.readthedocs.io/en/latest/submitting.html#what-should-my-paper-contain

[PyOpenSciCodeOfConduct]: https://www.pyopensci.org/contributing-guide/open-source-software-peer-review/code-of-conduct.html?highlight=code%20conduct

[OsiApprovedLicense]: https://opensource.org/licenses

[Templates]: https://www.pyopensci.org/contributing-guide/appendices/templates.html

[Comments]: https://github.com/pyOpenSci/governance/issues/8
