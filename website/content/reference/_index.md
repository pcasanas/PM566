---
title: References
slug: reference
output:
  blogdown::html_page:
      toc: TRUE
---


## Markdown

-  [The Plain Person’s Guide to Plain Text Social Science](http://plain-text.co/): Why you should write data-based reports using plain-text tools.
- [Markdown tutorial](https://www.markdowntutorial.com/): An interactive tutorial to practice using Markdown.
- [Markdown cheatsheet](http://packetlife.net/media/library/16/Markdown.pdf): Useful one-page reminder of Markdown syntax.

## Helpers and Templates

- [RMarkdown Cheatsheet](https://www.rstudio.com/wp-content/uploads/2015/02/rmarkdown-cheatsheet.pdf) An overview of Markdown and RMarkdown conventions.
- [RStudio Cheatsheets](https://rstudio.com/resources/cheatsheets/) Other quick guides, including a more comprehensive RMarkdown reference and a information about using RStudio's IDE, and some of the main tools in R.


## Guides

- [R Style Guide](http://adv-r.had.co.nz/Style.html). Write readable code. 
- [Jenny Bryan's Stat 545](http://stat545-ubc.github.io/topics.html). Notes and tutorials for a Data Analysis course taught by [Jennifer Bryan](http://www.stat.ubc.ca/~jenny/) at the University of British Columbia. Lots of useful material.
- [knitr demos](http://yihui.name/knitr/demos) Documentation and examples for `knitr` by its author, Yihui Xie. There is also a [knitr book](http://www.amazon.com/dp/1498716962/) covering the same ground in more detail.
- [Rmarkdown documentation](http://rmarkdown.rstudio.com) from the makers of RStudio. Lots of good examples.
- [Plain Person's Guide](http://github.com/kjhealy/plain-text.co) The git repository for this project.
- [Karl Broman's Tutorials and Guides](http://kbroman.org/pages/tutorials) Accurate and concise guides to many of the tools and topics described here, including [getting started with reproducible research](http://kbroman.org/steps2rr), [using git and GitHub](http://kbroman.org/github_tutorial), and [working with knitr](http://kbroman.org/knitr_knutshell).
- [Makefiles for OCR and converting Shapefiles](http://lincolnmullen.com/blog/makefiles-for-ocr-and-converting-shapefiles). Some further examples of `Makefiles` in the data-analysis pipeline, by [Lincoln Mullen](http://lincolnmullen.com)
    
    
## Tools

- [Apple's Developer Tools](https://developer.apple.com/library/ios/technotes/tn2339/_index.html) Unix toolchain. Install directly with `xcode-select --install`, or just try to use e.g. `git` from the terminal and have OS X prompt you to install the tools.
- [Homebrew package manager](http://brew.sh). A convenient way to install several of the tools here, including Emacs and Pandoc.
- [R](http://r-project.org). A platform for statistical computing.
- [knitr](http://yihui.name/knitr/). Reproducible plain-text documents from within R. 
- [Python](http://python.org) and [SciPy](http://www.scipy.org/). Python is a general-purpose programming language increasingly used in data manipulation and analysis.
- [RStudio](http://rstudio.com). An IDE for R. The most straightforward way to get into using R and RMarkdown.
- [TeX and LaTeX](http://tug.org). A typesetting and document preparation system. You can write files in `.tex` format directly, but it is more useful to just have it available in the background for other tools to use. The [MacTeX Distribution](http://tug.org/mactex) is the one to install for macOS.
- [Pandoc](http://pandoc.org). Converts plain-text documents to and from a wide variety of formats. Can be installed with Homebrew. Be sure to also install `pandoc-citeproc` for processing citations and bibliographies, and `pandoc-crossref` for producing cross-references and labels.
- [Git](http://git-scm.org). Version control system. Installs with Apple's Developer Tools, or get the latest version via Homebrew.
- [GNU Make](http://www.gnu.org/software/make). You tell `make` what the steps are to create the pieces of a document or program. As you edit and change the various pieces, it automatically figures out which pieces need to be updated and recompiled, and issues the commands to do that. See Karl Broman's [Minimal Make](http://kbroman.org/minimal_make/) for a short introduction. Make will be installed automatically with Apple's developer tools.
- [lintr](https://github.com/jimhester/lintr) and [flycheck](https://github.com/flycheck/flycheck). Tools that nudge you to write neater code.
- [Zotero](http://zotero.org). A citation manager that incorporates PDF storage, annotation, and other features. Zotero is free to use and can export to BibTeX/BibLaTeX files.
    
## Paid Applications and Services

- [Backblaze](http://backblaze.com). Secure off-site backup.
- [GitHub](http://github.com). Host public Git repositories for free. Pay to host private ones. Also a source for publicly available code (e.g. R packages and utilities) written by other people.
- [Marked 2](http://marked2app.com). Live HTML previewing of Markdown documents. Mac OS X only.
- [Sublime Text](http://sublimetext.com). Python-based text editor.
- [Mendeley](http://mendeley.com), and [Papers](http://papersapp.com) are additional citation managers that incorporate PDF storage, annotation, and other features. Mendeley has a premium tier. Papers is a paid application after a trial period. I haven't used either of these, so I can't confirm whether or not they export to BibTeX/BibLaTeX files. Papers can supposedly output citation keys in pandoc's format, among several others.

## Data

Many of these websites have API to download the data. We recommend you using APIs
to get data.

### Health and Biological data

- CDC [National Center for Health Statistics](https://www.cdc.gov/nchs/data_access/ftp_data.htm)
- NIH [Cancer Surveillance](https://seer.cancer.gov/)
- World Health Organization [WHO data](https://www.who.int/gho/database/en/)
- UniProt [data](https://www.uniprot.org/)
- The Gene Ontology [Project](http://geneontology.org/)
- Gene Expression Omnibus [Data](https://www.ncbi.nlm.nih.gov/geo/)
- US Center for Disease Control and Prevention [Data](https://data.cdc.gov/)
- California Health and Human Services [Open Data Portal](https://data.chhs.ca.gov/)
- Covid Data [CovidTracker](https://covidtracking.com/)
- USC [Sustainability Data](https://sustainabilitydata.usc.edu/arcgis/apps/sites/#/usc-sustainability-data-hub)
- [Bureau of Transportation Statistics](https://www.bts.gov/browse-statistical-products-and-data)

### Academic Publications and related

- Figshare data [repository](https://figshare.com/)
- Zenodo data [repository](https://zenodo.org/)
- Harvard [Dataverse](https://dataverse.harvard.edu/)
- Elsevier [Developers API](https://dev.elsevier.com/)

### Government data

- US Open Data Initiative [DATA.GOV](https://www.data.gov/)
- Census Data [Explorer](https://data.census.gov/) and [National Historical Geographic Information System (NHGIS)](https://www.nhgis.org/)
- [Bureau of Economic Analysis](https://www.bea.gov/data)
- [Bureau of Labor Statistics](https://www.bls.gov/data/)
- Housing data [Zillow](https://www.zillow.com/howto/api/APIOverview.htm)
- [Bureau of Justice Statistics](https://bjs.ojp.gov/data)
National Center for Education Statistics: [The Nation's Report Card](https://www.nationsreportcard.gov/ndecore/landing)
- Los Angeles [city data](https://data.lacity.org/)
- Los Angeles [crime data](http://www.lapdonline.org/crime_mapping_and_compstat)

### Other data

- World Bank [open data](https://data.worldbank.org/)
- [Inter-university Consortium for Political and Social Research (ICPSR)](https://www.icpsr.umich.edu/web/pages/)
- FiveThirtyEight [open data](https://data.fivethirtyeight.com/)
- Kaggle [datasets](https://www.kaggle.com/datasets)
- Literally all of [Wikipedia](https://en.wikipedia.org/wiki/Wikipedia:Database_download)

### Social Networks

- Twitter [Developers API](https://developer.twitter.com/) (probably broken?)
- GitHub [Developers API](https://docs.github.com/en/rest)
- Instagram [Developers API](https://developers.facebook.com/docs/instagram-api/)
- LinkedIn [Developers API](https://www.linkedin.com/developers/)

