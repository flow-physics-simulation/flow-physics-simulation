# FPS Web Site

[Flow Physics and Simulation (FPS)](https://github.com/flow-physics-simulation/flow-physics-simulation/edit/gh-pages/index.md) is a compuational laboratory for studying a wide range of fluid mechanics phenomena.  

FPS is composed of a range of individual codes, each a different GitHub repository, that can be used together to solve complex fluid mechanics program (both linear and nonlinear).

The flagship code is [LNS3D](https://sscollis.github.io/lns3d/) which is the primary solver for both compressible linear and nonlinear analyses.  In general there are codes for both compressible and incompressible flows, although the primary focus of FPS has been on compressible flow so that the capabilities are more extensive.

## Compressible

Code     |     Description
---------|--------------------------------------------------------
LNS3D    |  Primary 2d3c linear and nonlinear Navier-Stokes solver
FSC      |  3D boundary layer similarity solutions
COMPBL   |  3D boundary layer similarity solutions
NPOT     |  Compressible potential flow
STAB     |  Direct linear stabilty solver (curvature and receptivity included)
SHOOT    |  Shooting linear stability solver (curvature and nonparallel)

## Incompressible

Code     |     Description
---------|--------------------------------------------------------
DYNISO   |  Isotropic homogeneous turbulence solver
PSE      |  Parabolized Stabilty Equation (PSE) solver
OS-STAB  |  Orr-Sommerfeld solver using Conte shooting (Blasius solver included)

----

## Welcome to GitHub Pages

You can use the [editor on GitHub](https://github.com/flow-physics-simulation/flow-physics-simulation/edit/gh-pages/index.md) to maintain and preview the content for your website in Markdown files.

Whenever you commit to this repository, GitHub Pages will run [Jekyll](https://jekyllrb.com/) to rebuild the pages in your site, from the content in your Markdown files.

### Markdown

Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for

```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see [Basic writing and formatting syntax](https://docs.github.com/en/github/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/flow-physics-simulation/flow-physics-simulation/settings/pages). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://docs.github.com/categories/github-pages-basics/) or [contact support](https://support.github.com/contact) and we’ll help you sort it out.
