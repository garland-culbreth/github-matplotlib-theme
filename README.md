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
  
  ![github-light](https://github.com/garland-culbreth/github-matplotlib-theme/assets/70354045/4c748e14-08fd-4fcd-a04f-a12f7c02615b)
</details>

<details>
  <summary>github-light-talk</summary>
  
  ![github-light-talk](https://github.com/garland-culbreth/github-matplotlib-theme/assets/70354045/71dc1fb1-18eb-4d17-9896-682fc3e28639)
</details>

<details>
  <summary>github-dimmed</summary>
  
  ![github-dimmed](https://github.com/garland-culbreth/github-matplotlib-theme/assets/70354045/0b493309-37c3-4673-bf1c-8454758fa65c)
</details>

<details>
  <summary>github-dimmed-talk</summary>
  
  ![github-dimmed-talk](https://github.com/garland-culbreth/github-matplotlib-theme/assets/70354045/d1bf32a2-b322-4006-9f22-09e6a5577001)
</details>
