About gazebo_model_robotraconteur_driver
========================================

Home: http://robotraconteur.com

Package license: Apache 2.0

Feedstock license: [BSD-3-Clause](https://github.com/robotraconteur/gazebo_model_robotraconteur_driver-feedstock/blob/master/LICENSE.txt)

Summary: Robot Raconteur driver for Gazebo models, used to simulate robot controller

Current build status
====================


<table>
</table>

Current release info
====================

| Name | Downloads | Version | Platforms |
| --- | --- | --- | --- |
| [![Conda Recipe](https://img.shields.io/badge/recipe-gazebo_model_robotraconteur_driver-green.svg)](https://anaconda.org/r/gazebo_model_robotraconteur_driver) | [![Conda Downloads](https://img.shields.io/conda/dn/r/gazebo_model_robotraconteur_driver.svg)](https://anaconda.org/r/gazebo_model_robotraconteur_driver) | [![Conda Version](https://img.shields.io/conda/vn/r/gazebo_model_robotraconteur_driver.svg)](https://anaconda.org/r/gazebo_model_robotraconteur_driver) | [![Conda Platforms](https://img.shields.io/conda/pn/r/gazebo_model_robotraconteur_driver.svg)](https://anaconda.org/r/gazebo_model_robotraconteur_driver) |

Installing gazebo_model_robotraconteur_driver
=============================================

Installing `gazebo_model_robotraconteur_driver` from the `r` channel can be achieved by adding `r` to your channels with:

```
conda config --add channels r
conda config --set channel_priority strict
```

Once the `r` channel has been enabled, `gazebo_model_robotraconteur_driver` can be installed with:

```
conda install gazebo_model_robotraconteur_driver
```

It is possible to list all of the versions of `gazebo_model_robotraconteur_driver` available on your platform with:

```
conda search gazebo_model_robotraconteur_driver --channel r
```




Updating gazebo_model_robotraconteur_driver-feedstock
=====================================================

If you would like to improve the gazebo_model_robotraconteur_driver recipe or build a new
package version, please fork this repository and submit a PR. Upon submission,
your changes will be run on the appropriate platforms to give the reviewer an
opportunity to confirm that the changes result in a successful build. Once
merged, the recipe will be re-built and uploaded automatically to the
`r` channel, whereupon the built conda packages will be available for
everybody to install and use from the `r` channel.
Note that all branches in the robotraconteur/gazebo_model_robotraconteur_driver-feedstock are
immediately built and any created packages are uploaded, so PRs should be based
on branches in forks and branches in the main repository should only be used to
build distinct package versions.

In order to produce a uniquely identifiable distribution:
 * If the version of a package **is not** being increased, please add or increase
   the [``build/number``](https://docs.conda.io/projects/conda-build/en/latest/resources/define-metadata.html#build-number-and-string).
 * If the version of a package **is** being increased, please remember to return
   the [``build/number``](https://docs.conda.io/projects/conda-build/en/latest/resources/define-metadata.html#build-number-and-string)
   back to 0.

Feedstock Maintainers
=====================


