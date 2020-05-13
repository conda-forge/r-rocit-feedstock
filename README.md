About r-rocit
=============

Home: https://CRAN.R-project.org/package=ROCit

Package license: GPL-3.0-only

Feedstock license: BSD 3-Clause

Summary: Sensitivity (or recall or true positive rate), false positive rate, specificity, precision (or positive predictive value), negative predictive value, misclassification rate, accuracy, F-score- these are popular metrics for assessing performance of binary classifier for certain threshold. These metrics are calculated at certain threshold values. Receiver operating characteristic (ROC) curve is a common tool for assessing overall diagnostic ability of the binary classifier. Unlike depending on a certain threshold, area under ROC curve (also known as AUC), is a summary statistic about how well a binary classifier performs overall for the classification task. ROCit package provides flexibility to easily evaluate threshold-bound metrics. Also, ROC curve, along with AUC, can be obtained using different methods, such as empirical, binormal and non-parametric. ROCit encompasses a wide variety of methods for constructing confidence interval of ROC curve and AUC. ROCit also features the option of constructing empirical gains table, which is a handy tool for direct marketing. The package offers options for commonly used visualization, such as, ROC curve, KS plot, lift plot. Along with in-built default graphics setting, there are rooms for manual tweak by providing the necessary values as function arguments. ROCit is a powerful tool offering a range of things, yet it is very easy to use.



Current build status
====================


<table><tr><td>All platforms:</td>
    <td>
      <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=9761&branchName=master">
        <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/r-rocit-feedstock?branchName=master">
      </a>
    </td>
  </tr>
</table>

Current release info
====================

| Name | Downloads | Version | Platforms |
| --- | --- | --- | --- |
| [![Conda Recipe](https://img.shields.io/badge/recipe-r--rocit-green.svg)](https://anaconda.org/conda-forge/r-rocit) | [![Conda Downloads](https://img.shields.io/conda/dn/conda-forge/r-rocit.svg)](https://anaconda.org/conda-forge/r-rocit) | [![Conda Version](https://img.shields.io/conda/vn/conda-forge/r-rocit.svg)](https://anaconda.org/conda-forge/r-rocit) | [![Conda Platforms](https://img.shields.io/conda/pn/conda-forge/r-rocit.svg)](https://anaconda.org/conda-forge/r-rocit) |

Installing r-rocit
==================

Installing `r-rocit` from the `conda-forge` channel can be achieved by adding `conda-forge` to your channels with:

```
conda config --add channels conda-forge
```

Once the `conda-forge` channel has been enabled, `r-rocit` can be installed with:

```
conda install r-rocit
```

It is possible to list all of the versions of `r-rocit` available on your platform with:

```
conda search r-rocit --channel conda-forge
```


About conda-forge
=================

[![Powered by NumFOCUS](https://img.shields.io/badge/powered%20by-NumFOCUS-orange.svg?style=flat&colorA=E1523D&colorB=007D8A)](http://numfocus.org)

conda-forge is a community-led conda channel of installable packages.
In order to provide high-quality builds, the process has been automated into the
conda-forge GitHub organization. The conda-forge organization contains one repository
for each of the installable packages. Such a repository is known as a *feedstock*.

A feedstock is made up of a conda recipe (the instructions on what and how to build
the package) and the necessary configurations for automatic building using freely
available continuous integration services. Thanks to the awesome service provided by
[CircleCI](https://circleci.com/), [AppVeyor](https://www.appveyor.com/)
and [TravisCI](https://travis-ci.com/) it is possible to build and upload installable
packages to the [conda-forge](https://anaconda.org/conda-forge)
[Anaconda-Cloud](https://anaconda.org/) channel for Linux, Windows and OSX respectively.

To manage the continuous integration and simplify feedstock maintenance
[conda-smithy](https://github.com/conda-forge/conda-smithy) has been developed.
Using the ``conda-forge.yml`` within this repository, it is possible to re-render all of
this feedstock's supporting files (e.g. the CI configuration files) with ``conda smithy rerender``.

For more information please check the [conda-forge documentation](https://conda-forge.org/docs/).

Terminology
===========

**feedstock** - the conda recipe (raw material), supporting scripts and CI configuration.

**conda-smithy** - the tool which helps orchestrate the feedstock.
                   Its primary use is in the construction of the CI ``.yml`` files
                   and simplify the management of *many* feedstocks.

**conda-forge** - the place where the feedstock and smithy live and work to
                  produce the finished article (built conda distributions)


Updating r-rocit-feedstock
==========================

If you would like to improve the r-rocit recipe or build a new
package version, please fork this repository and submit a PR. Upon submission,
your changes will be run on the appropriate platforms to give the reviewer an
opportunity to confirm that the changes result in a successful build. Once
merged, the recipe will be re-built and uploaded automatically to the
`conda-forge` channel, whereupon the built conda packages will be available for
everybody to install and use from the `conda-forge` channel.
Note that all branches in the conda-forge/r-rocit-feedstock are
immediately built and any created packages are uploaded, so PRs should be based
on branches in forks and branches in the main repository should only be used to
build distinct package versions.

In order to produce a uniquely identifiable distribution:
 * If the version of a package **is not** being increased, please add or increase
   the [``build/number``](https://conda.io/docs/user-guide/tasks/build-packages/define-metadata.html#build-number-and-string).
 * If the version of a package **is** being increased, please remember to return
   the [``build/number``](https://conda.io/docs/user-guide/tasks/build-packages/define-metadata.html#build-number-and-string)
   back to 0.

Feedstock Maintainers
=====================

* [@conda-forge/r](https://github.com/conda-forge/r/)

