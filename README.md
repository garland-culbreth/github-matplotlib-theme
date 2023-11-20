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
plt.style.use("github-dimmed")
```
The styles work best when used together with Seaborn, especially `sns.despine()`.

All styles have a font stack that attempts to use Gill Sans, then falls back on Helvetica or Arial, then falls back on Matplotlib defaults. Gill Sans is a standard system font on both Windows (as Gill Sans MT) and macOS (as Gill Sans). Windows users can also get Gill Sans Nova as a system font by installing the optional [Pan-European Supplemental Fonts](https://docs.microsoft.com/en-us/windows/deployment/windows-10-missing-fonts#install-optional-fonts-manually-without-changing-language-settings) for free.


# Examples

<details>
  <summary>github-light</summary>
  
  ![github-light](https://github.com/garland-culbreth/github-matplotlib-theme/assets/70354045/7ebfebdf-1620-43d2-9d0c-47578235bd61)
</details>

<details>
  <summary>github-light-talk</summary>
  
  ![github-light-talk](https://github.com/garland-culbreth/github-matplotlib-theme/assets/70354045/42d55336-7f21-4f61-a6df-0ecdc433c432)
</details>

<details>
  <summary>github-dimmed</summary>
  
  ![github-dimmed](https://github.com/garland-culbreth/github-matplotlib-theme/assets/70354045/35167669-6ea4-492c-86ff-5e09e4f1d663)
</details>

<details>
  <summary>github-dimmed-talk</summary>
  
  ![github-dimmed-talk](https://github.com/garland-culbreth/github-matplotlib-theme/assets/70354045/7840373e-75e1-4485-8843-7b707be20980)
</details>
