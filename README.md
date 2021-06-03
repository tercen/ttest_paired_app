# ttest_paired_app

##### Description

`ttest_paired_app` is an application that determines if there is a significant difference between the means of two groups of matched pairs.

##### Details

The application consists of a data input, a workflow and a data output. 

The input data is the log transformed [ptk dataset](https://tercen.com/r/35c33fa33c9e6aba0dce6483f59174e3)

The workflow has 2 operators:

* [two_sample_ttest_operator](https://github.com/tercen/two_sample_ttest_operator)
* [zscore_scaling_operator](https://github.com/tercen/zscore_scaling_operator)

Furthermore it has 2 views:

* Volcano plot
* Significant treatment effects

##### See Also

[ttest_paired_app](https://github.com/tercen/ttest_paired_app)

