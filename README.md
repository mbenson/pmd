# PMD

[![Build Status](https://travis-ci.org/pmd/pmd.svg?branch=master)](https://travis-ci.org/pmd/pmd)

## About

PMD is a source code analyzer. It finds common programming flaws like unused variables, empty catch blocks,
unnecessary object creation, and so forth. It supports Java, JavaScript, XML, XSL.
Additionally it includes CPD, the copy-paste-detector. CPD finds duplicated code in
Java, C, C++, C#, PHP, Ruby, Fortran, JavaScript.

## Source

Our latest source of PMD can be found on [GitHub]. Fork us!

### How to build PMD?

Simply use maven in the top-level directory:

    mvn clean package

This will create the zip files in the directory `pmd-dist/target`:

    cd pmd-dist/target
    ls *.zip

That's all !

### Bug Reports

We are using Sourceforge for bug tracking. Please file your bugs at <https://sourceforge.net/p/pmd/bugs/>.

### Pull Requests

Pull requests are always welcome: <https://github.com/pmd/pmd/pulls>


## News and Website

More information can be found on our [Website] and on [SourceForge].


[GitHub]: https://github.com/pmd/pmd
[Website]: https://pmd.github.io
[SourceForge]: https://sourceforge.net/projects/pmd/
