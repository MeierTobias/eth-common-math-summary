# ETHZ Common Math Summary  <!-- omit from toc -->

![action status](https://github.com/meiertobias/eth-common-math-summary/actions/workflows/build_deploy.yml/badge.svg)

This repository contains the LaTex source of some common math sections that are used repeatedly in various summaries.

[Overview.pdf](https://meiertobias.github.io/eth-common-math-summary/main.pdf)

Topics documented in this ReadMe:

- [How to use this template](#how-to-use-this-template)
  - [Include this repo as a submodule](#include-this-repo-as-a-submodule)
  - [Include sections in your summary](#include-sections-in-your-summary)
- [Contributing](#contributing)
- [License](#license)

## How to use this template

### Include this repo as a submodule

Navigate to the root folder of your existing repository and execute the following command:

``` bash
git submodule add https://github.com/MeierTobias/eth-common-math-summary.git src/common-math-sections
```

This adds the template repo to the folder `src/common-math-sections`

> **_Remember:_** If you later want to clone your repository to another machine you need to add the `--recurse-submodules` flag to your clone command to pull the submodules. `git clone --recurse-submodules https://github.com/your/repository.git`

### Include sections in your summary

Now you can just use the `\input{common-mat-sections/xxx.tex}` command to include the desired sections. To get an overview of the available chapters take a look at the prebuilt [Overview.pdf](https://meiertobias.github.io/eth-common-math-summary/main.pdf).

## Contributing

Feel free to fork this repository and create a pull request to integrate your corrections and extensions.

## License

Distributed under the MIT License. See [LICENSE](LICENSE) for more information.
