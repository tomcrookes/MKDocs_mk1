# Setting Themes

There are two build-in themes for mkdocs:

`mkdocs`: built as a custom Bootstrap theme is the defualt option that supports almost every feature of mkdocs.

![mkdocs](/img/mkdocs-format.png)

`readthedocs`: offers the same restricted feature set as its parent theme. 

![readthedocs](/img/readthedocs-format.png)


## Setting the theme 
To set the theme, edit the `.yml` configuration file to contain:

```
theme:
    name: readthedocs
```
Or another option listed above. If you wish to use a custom or third party theme instead, see the section below.


## Third Party Themes
Extra third party themes can be found in the MkDocs community wiki, posted <a href= "https://github.com/mkdocs/mkdocs/wiki/MkDocs-Themes">here</a>