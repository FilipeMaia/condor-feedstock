About condor
============

Home: https://github.com/FXIhub/condor

Package license: BSD

Feedstock license: BSD 3-Clause

Summary: A simulation tool for flash X-ray imaging



Current build status
====================


<table>
    
  <tr>
    <td>Azure</td>
    <td>
      <details>
        <summary>
          <a href="https://dev.azure.com/FilipeMaia/feedstock-builds/_build/latest?definitionId=&branchName=master">
            <img src="https://dev.azure.com/FilipeMaia/feedstock-builds/_apis/build/status/condor-feedstock?branchName=master">
          </a>
        </summary>
        <table>
          <thead><tr><th>Variant</th><th>Status</th></tr></thead>
          <tbody><tr>
              <td>linux_python3.7</td>
              <td>
                <a href="https://dev.azure.com/FilipeMaia/feedstock-builds/_build/latest?definitionId=&branchName=master">
                  <img src="https://dev.azure.com/FilipeMaia/feedstock-builds/_apis/build/status/condor-feedstock?branchName=master&jobName=linux&configuration=linux_python3.7" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>osx_python3.7</td>
              <td>
                <a href="https://dev.azure.com/FilipeMaia/feedstock-builds/_build/latest?definitionId=&branchName=master">
                  <img src="https://dev.azure.com/FilipeMaia/feedstock-builds/_apis/build/status/condor-feedstock?branchName=master&jobName=osx&configuration=osx_python3.7" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>win_python3.7</td>
              <td>
                <a href="https://dev.azure.com/FilipeMaia/feedstock-builds/_build/latest?definitionId=&branchName=master">
                  <img src="https://dev.azure.com/FilipeMaia/feedstock-builds/_apis/build/status/condor-feedstock?branchName=master&jobName=win&configuration=win_python3.7" alt="variant">
                </a>
              </td>
            </tr>
          </tbody>
        </table>
      </details>
    </td>
  </tr>
  <tr>
    <td>Linux_ppc64le</td>
    <td>
      <img src="https://img.shields.io/badge/ppc64le-disabled-lightgrey.svg" alt="ppc64le disabled">
    </td>
  </tr>
</table>

Current release info
====================

| Name | Downloads | Version | Platforms |
| --- | --- | --- | --- |
| [![Conda Recipe](https://img.shields.io/badge/recipe-condor-green.svg)](https://anaconda.org/filipemaia/condor) | [![Conda Downloads](https://img.shields.io/conda/dn/filipemaia/condor.svg)](https://anaconda.org/filipemaia/condor) | [![Conda Version](https://img.shields.io/conda/vn/filipemaia/condor.svg)](https://anaconda.org/filipemaia/condor) | [![Conda Platforms](https://img.shields.io/conda/pn/filipemaia/condor.svg)](https://anaconda.org/filipemaia/condor) |

Installing condor
=================

Installing `condor` from the `filipemaia` channel can be achieved by adding `filipemaia` to your channels with:

```
conda config --add channels filipemaia
```

Once the `filipemaia` channel has been enabled, `condor` can be installed with:

```
conda install condor
```

It is possible to list all of the versions of `condor` available on your platform with:

```
conda search condor --channel filipemaia
```




Updating condor-feedstock
=========================

If you would like to improve the condor recipe or build a new
package version, please fork this repository and submit a PR. Upon submission,
your changes will be run on the appropriate platforms to give the reviewer an
opportunity to confirm that the changes result in a successful build. Once
merged, the recipe will be re-built and uploaded automatically to the
`filipemaia` channel, whereupon the built conda packages will be available for
everybody to install and use from the `filipemaia` channel.
Note that all branches in the FilipeMaia/condor-feedstock are
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

* [@F](https://github.com/F/)
* [@M](https://github.com/M/)
* [@a](https://github.com/a/)
* [@e](https://github.com/e/)
* [@i](https://github.com/i/)
* [@l](https://github.com/l/)
* [@p](https://github.com/p/)

