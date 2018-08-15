About allennlp
==============

Home: https://github.com/allenai/allennlp

Package license: Apache 2.0

Feedstock license: BSD 3-Clause

Summary: An open-source NLP research library, built on PyTorch.

An open-source NLP research library, built on PyTorch.

Current build status
====================

[![Linux](https://img.shields.io/circleci/project/github/nelson-liu/allennlp-feedstock/master.svg?label=Linux)](https://circleci.com/gh/nelson-liu/allennlp-feedstock)
[![OSX](https://img.shields.io/travis/nelson-liu/allennlp-feedstock/master.svg?label=macOS)](https://travis-ci.org/nelson-liu/allennlp-feedstock)
![Windows disabled](https://img.shields.io/badge/Windows-disabled-lightgrey.svg)

Current release info
====================

| Name | Downloads | Version | Platforms |
| --- | --- | --- | --- |
| [![Conda Recipe](https://img.shields.io/badge/recipe-allennlp-green.svg)](https://anaconda.org/allennlp/allennlp) | [![Conda Downloads](https://img.shields.io/conda/dn/allennlp/allennlp.svg)](https://anaconda.org/allennlp/allennlp) | [![Conda Version](https://img.shields.io/conda/vn/allennlp/allennlp.svg)](https://anaconda.org/allennlp/allennlp) | [![Conda Platforms](https://img.shields.io/conda/pn/allennlp/allennlp.svg)](https://anaconda.org/allennlp/allennlp) |

Installing allennlp
===================

Installing `allennlp` from the `allennlp` channel can be achieved by adding `allennlp` to your channels with:

```
conda config --add channels allennlp
```

Once the `allennlp` channel has been enabled, `allennlp` can be installed with:

```
conda install allennlp
```

It is possible to list all of the versions of `allennlp` available on your platform with:

```
conda search allennlp --channel allennlp
```




Updating allennlp-feedstock
===========================

If you would like to improve the allennlp recipe or build a new
package version, please fork this repository and submit a PR. Upon submission,
your changes will be run on the appropriate platforms to give the reviewer an
opportunity to confirm that the changes result in a successful build. Once
merged, the recipe will be re-built and uploaded automatically to the
`allennlp` channel, whereupon the built conda packages will be available for
everybody to install and use from the `allennlp` channel.
Note that all branches in the conda-forge/allennlp-feedstock are
immediately built and any created packages are uploaded, so PRs should be based
on branches in forks and branches in the main repository should only be used to
build distinct package versions.

In order to produce a uniquely identifiable distribution:
 * If the version of a package **is not** being increased, please add or increase
   the [``build/number``](https://conda.io/docs/user-guide/tasks/build-packages/define-metadata.html#build-number-and-string).
 * If the version of a package **is** being increased, please remember to return
   the [``build/number``](https://conda.io/docs/user-guide/tasks/build-packages/define-metadata.html#build-number-and-string)
   back to 0.
