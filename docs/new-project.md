# Getting Started


## Installation 
When installing MkDocs, run the `
pip` command to install the package:

``` sql
pip install mkdocs 
```
If using Windows, the above command may not work. Instead, use:

``` sql 
python -m pip install mkdocs
```


## Creating a New Project

First, start by creating a project using:

``` sql
mkdocs new project-name
```

With `project-name` being the name of the project being used. 

Now, `cd` into your project. In your folder, you should see a `.yml` file as well as a docs folder that stores your `.md` files. The `.yml` file is your confuguration file to set up the layout of your page, while the `.md` stores the documenation and content of each page. 


## Locally Testing MkDocs
To locally test your build, run:

``` sql
$ mkdocs serve
INFO    - Building documentation...
INFO    - Clearning site directory
INFO    - [16:05:32] Serving on http://127.0.0.1:8000
```

Similarly, if you are having trouble running the commands in windows, run the command `python -m mkdocs serve`

Open the `http://127.0.0.1:8000` in your browser, and you should see your home page displayed.

<mark>
Note:
You can make changes to the document while the script is running. Each time a save is made, the web page will refresh and display your recent changes.
</mark>


