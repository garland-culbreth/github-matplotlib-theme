# GitHub styles for Matplotlib

Github themed stylesheets for [Matplotlib](https://matplotlib.org/). Colors selected from the [primer palette](https://github.com/primer/primitives). Styles strongly inspired by [Seaborn](https://seaborn.pydata.org/).


# Installation and Use

Download the mplstyle files and save them to your Matplotlib style library. To locate your Matplotlib style library, run:
```py
import matplotlib
matplotlib.get_configdir()
```
in an active environment. In the directory returned by the command, look for a subdirectory named `stylelib`; you may need to create one. Save the downloaded `.mplstyle` files in the `stylelib` directory.

Once the styles are in `mpl_configdir/stylelib` you can load them with `plt.style.use()`. For example:
```py
import matplotlib.pyplot as plt
plt.style.use("nord")
```
The styles work best when used together with Seaborn, especially `sns.despine()`.

All styles have a font stack that attempts to use Gill Sans, then falls back on Helvetica or Arial, then falls back on Matplotlib defaults. Gill Sans is a standard system font on both Windows (as Gill Sans MT) and macOS (as Gill Sans). Windows users can also get Gill Sans Nova as a system font by installing the optional [Pan-European Supplemental Fonts](https://docs.microsoft.com/en-us/windows/deployment/windows-10-missing-fonts#install-optional-fonts-manually-without-changing-language-settings) for free.


# Examples

<details>
  <summary>github-light</summary>
  
  ![ex-github-light](https://github.com/garland-culbreth/github-matplotlib-theme/assets/70354045/091088a8-007f-4acc-bf1f-37fd2d431243)
</details>

<details>
  <summary>github-light-talk</summary>
  
  ![ex-github-light-talk](https://github.com/garland-culbreth/github-matplotlib-theme/assets/70354045/4de6474e-7fc8-4325-b7b5-4b1034d6b261)
</details>

<details>
  <summary>github-dimmed</summary>
  
  ![ex-github-dimmed](https://github.com/garland-culbreth/github-matplotlib-theme/assets/70354045/69668335-e553-4f82-9aae-c87c24a31d8f)
</details>

<details>
  <summary>github-dimmed-talk</summary>
  
  ![ex-github-dimmed-talk](https://github.com/garland-culbreth/github-matplotlib-theme/assets/70354045/896a0ff2-4e01-4611-8657-bcf6e3689165)
</details>
