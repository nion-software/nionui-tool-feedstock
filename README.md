About nionui-tool
=================

Home: http://github.com/nion-software/nionui-tool

Package license: Apache-2.0

Feedstock license: BSD 3-Clause

Summary: A native launcher for Nion UI apps.



Current build status
====================

[![Linux](https://img.shields.io/circleci/project/github/nion-software/nionui-tool-feedstock/master.svg?label=Linux)](https://circleci.com/gh/nion-software/nionui-tool-feedstock)
[![OSX](https://img.shields.io/travis/nion-software/nionui-tool-feedstock/master.svg?label=macOS)](https://travis-ci.org/nion-software/nionui-tool-feedstock)
[![Windows](https://img.shields.io/appveyor/ci/nion-software/nionui-tool-feedstock/master.svg?label=Windows)](https://ci.appveyor.com/project/nion-software/nionui-tool-feedstock/branch/master)

Current release info
====================

| Name | Downloads | Version | Platforms |
| --- | --- | --- | --- |
| [![Conda Recipe](https://img.shields.io/badge/recipe-nionui--tool-green.svg)](https://anaconda.org/nion/nionui-tool) | [![Conda Downloads](https://img.shields.io/conda/dn/nion/nionui-tool.svg)](https://anaconda.org/nion/nionui-tool) | [![Conda Version](https://img.shields.io/conda/vn/nion/nionui-tool.svg)](https://anaconda.org/nion/nionui-tool) | [![Conda Platforms](https://img.shields.io/conda/pn/nion/nionui-tool.svg)](https://anaconda.org/nion/nionui-tool) |

Installing nionui-tool
======================

Installing `nionui-tool` from the `nion` channel can be achieved by adding `nion` to your channels with:

```
conda config --add channels nion
```

Once the `nion` channel has been enabled, `nionui-tool` can be installed with:

```
conda install nionui-tool
```

It is possible to list all of the versions of `nionui-tool` available on your platform with:

```
conda search nionui-tool --channel nion
```




Updating nionui-tool-feedstock
==============================

If you would like to improve the nionui-tool recipe or build a new
package version, please fork this repository and submit a PR. Upon submission,
your changes will be run on the appropriate platforms to give the reviewer an
opportunity to confirm that the changes result in a successful build. Once
merged, the recipe will be re-built and uploaded automatically to the
`nion` channel, whereupon the built conda packages will be available for
everybody to install and use from the `nion` channel.
Note that all branches in the nion-software/nionui-tool-feedstock are
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

* [@cmeyer](https://github.com/cmeyer/)

