> [!WARNING]
> This repository is no longer being updated. Please use [simplstyles](https://github.com/garland-culbreth/simplstyles) for a maintained version.

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

All styles have a font stack that attempts to use Roboto, then falls back on Helvetica or Arial, then falls back on Matplotlib defaults. Roboto is available for free on [Google fonts](https://fonts.google.com/specimen/Roboto).

# Examples

<details>
  <summary>github-light</summary>
  
  ![github-light](https://github.com/garland-culbreth/github-matplotlib-theme/assets/70354045/5ad8f88c-acfe-4c0a-bd12-1f57ea8bc139)
</details>

<details>
  <summary>github-light-talk</summary>
  
  ![github-light-talk](https://github.com/garland-culbreth/github-matplotlib-theme/assets/70354045/db1ec084-9d94-4527-95e5-a2c7613d36a0)
</details>

<details>
  <summary>github-dimmed</summary>
  
  ![github-dimmed](https://github.com/garland-culbreth/github-matplotlib-theme/assets/70354045/27580937-18ff-4e5d-8173-199d897664c6)
</details>

<details>
  <summary>github-dimmed-talk</summary>
  
  ![github-dimmed-talk](https://github.com/garland-culbreth/github-matplotlib-theme/assets/70354045/39c576db-f772-4cc5-aca9-557e0f1a563c)
</details>
