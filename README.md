

![PiGx Logo](http://bioinformatics.mdc-berlin.de/pigx/images/logo.svg)

# Introduction
The primary aim of PiGx was to provide genomics data processing tools that are relatively 1) easy to use, 2) easy to install, 3) easy to distribute and most importantly 4) reproducible. Data processing is the major bottleneck for analyzing large number of samples. We want to make first-pass analysis as painless and as quick as possible for the users. So that, they will have more time to spend on data integration, visualization and statistical modeling.

All the pipelines have similar interface. For the end-user, each pipeline has the same input types: a sample sheet and a settings file. The sample sheet contains the information on samples such as names, locations of raw files, covariates etc. The settings file contains the extra arguments for the tools in the pipelines.  The users can in general run pipelines as follows: 

```
$./pigx [pipeline_name] [sample_sheet] -s [settings_file]
```

Additionally, we also provide users with high quality reports and figures that contains results from basic analyses and data quality check. The following chapters provide detailed documentation for the pipelines available in PiGx.



## Contributors

- Ricardo Wurmus [Contributor to all pipelines]
- Vedran Franke [Contributor to ChIP-seq, scRNA-seq]
- Bora Uyar [Contributor to RNA-seq, scRNA-seq]
- Alexander Gosdschan [Contributor to ChIP-seq, BS-seq]
- Brendan Osberg [Contributor to BS-seq]
- Katarzyna Wreczycka [Contributor to BS-seq]
- Jonathan Ronen [Contributor to RNA-seq ]
- Altuna Akalin [Concept design, supervision]