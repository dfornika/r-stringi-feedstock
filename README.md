About r-stringi
===============

Home: http://www.gagolewski.com/software/stringi

Package license: FOSS

Feedstock license: BSD 3-Clause

Summary: Allows for fast, correct, consistent, portable, as well as convenient character string/text processing in every locale and any native encoding. Owing to the use of the ICU library, the package provides R users with platform-independent functions known to Java, Perl, Python, PHP, and Ruby programmers. Available features include: pattern searching (e.g., with ICU Java-like regular expressions or the Unicode Collation Algorithm), random string generation, case mapping, string transliteration, concatenation, Unicode normalization, date-time formatting and parsing, etc.



Current build status
====================

Linux: [![Circle CI](https://circleci.com/gh/conda-forge/r-stringi-feedstock.svg?style=shield)](https://circleci.com/gh/conda-forge/r-stringi-feedstock)
OSX: [![TravisCI](https://travis-ci.org/conda-forge/r-stringi-feedstock.svg?branch=master)](https://travis-ci.org/conda-forge/r-stringi-feedstock)
Windows: [![AppVeyor](https://ci.appveyor.com/api/projects/status/github/conda-forge/r-stringi-feedstock?svg=True)](https://ci.appveyor.com/project/conda-forge/r-stringi-feedstock/branch/master)

Current release info
====================
Version: [![Anaconda-Server Badge](https://anaconda.org/conda-forge/r-stringi/badges/version.svg)](https://anaconda.org/conda-forge/r-stringi)
Downloads: [![Anaconda-Server Badge](https://anaconda.org/conda-forge/r-stringi/badges/downloads.svg)](https://anaconda.org/conda-forge/r-stringi)

Installing r-stringi
====================

Installing `r-stringi` from the `conda-forge` channel can be achieved by adding `conda-forge` to your channels with:

```
conda config --add channels conda-forge
```

Once the `conda-forge` channel has been enabled, `r-stringi` can be installed with:

```
conda install r-stringi
```

It is possible to list all of the versions of `r-stringi` available on your platform with:

```
conda search r-stringi --channel conda-forge
```


About conda-forge
=================

conda-forge is a community-led conda channel of installable packages.
In order to provide high-quality builds, the process has been automated into the
conda-forge GitHub organization. The conda-forge organization contains one repository
for each of the installable packages. Such a repository is known as a *feedstock*.

A feedstock is made up of a conda recipe (the instructions on what and how to build
the package) and the necessary configurations for automatic building using freely
available continuous integration services. Thanks to the awesome service provided by
[CircleCI](https://circleci.com/), [AppVeyor](http://www.appveyor.com/)
and [TravisCI](https://travis-ci.org/) it is possible to build and upload installable
packages to the [conda-forge](https://anaconda.org/conda-forge)
[Anaconda-Cloud](http://docs.anaconda.org/) channel for Linux, Windows and OSX respectively.

To manage the continuous integration and simplify feedstock maintenance
[conda-smithy](http://github.com/conda-forge/conda-smithy) has been developed.
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


Updating r-stringi-feedstock
============================

If you would like to improve the r-stringi recipe or build a new
package version, please fork this repository and submit a PR. Upon submission,
your changes will be run on the appropriate platforms to give the reviewer an
opportunity to confirm that the changes result in a successful build. Once
merged, the recipe will be re-built and uploaded automatically to the
`conda-forge` channel, whereupon the built conda packages will be available for
everybody to install and use from the `conda-forge` channel.
Note that all branches in the conda-forge/r-stringi-feedstock are
immediately built and any created packages are uploaded, so PRs should be based
on branches in forks and branches in the main repository should only be used to
build distinct package versions.

In order to produce a uniquely identifiable distribution:
 * If the version of a package **is not** being increased, please add or increase
   the [``build/number``](http://conda.pydata.org/docs/building/meta-yaml.html#build-number-and-string).
 * If the version of a package **is** being increased, please remember to return
   the [``build/number``](http://conda.pydata.org/docs/building/meta-yaml.html#build-number-and-string)
   back to 0.