About testproject
=================

Home: 

Package license: 

Feedstock license: BSD-3-Clause

Summary: 



Current build status
====================


<table><tr>
    <td>CircleCI</td>
    <td>
      <a href="https://circleci.com/gh/mehdizadehm/testproj-feedstock">
        <img alt="Linux" src="https://img.shields.io/circleci/project/github/mehdizadehm/testproj-feedstock/master.svg?label=Linux">
      </a>
    </td>
  </tr>
</table>

Current release info
====================

| Name | Downloads | Version | Platforms |
| --- | --- | --- | --- |
| [![Conda Recipe](https://img.shields.io/badge/recipe-testproject-green.svg)](https://anaconda.org/meissam/testproject) | [![Conda Downloads](https://img.shields.io/conda/dn/meissam/testproject.svg)](https://anaconda.org/meissam/testproject) | [![Conda Version](https://img.shields.io/conda/vn/meissam/testproject.svg)](https://anaconda.org/meissam/testproject) | [![Conda Platforms](https://img.shields.io/conda/pn/meissam/testproject.svg)](https://anaconda.org/meissam/testproject) |

Installing testproject
======================

Installing `testproject` from the `meissam` channel can be achieved by adding `meissam` to your channels with:

```
conda config --add channels meissam
```

Once the `meissam` channel has been enabled, `testproject` can be installed with:

```
conda install testproject
```

It is possible to list all of the versions of `testproject` available on your platform with:

```
conda search testproject --channel meissam
```




Updating testproject-feedstock
==============================

If you would like to improve the testproject recipe or build a new
package version, please fork this repository and submit a PR. Upon submission,
your changes will be run on the appropriate platforms to give the reviewer an
opportunity to confirm that the changes result in a successful build. Once
merged, the recipe will be re-built and uploaded automatically to the
`meissam` channel, whereupon the built conda packages will be available for
everybody to install and use from the `meissam` channel.
Note that all branches in the mehdizadehm/testproject-feedstock are
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


