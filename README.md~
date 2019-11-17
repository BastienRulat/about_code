# Get started

`hugo-theme-learn` is a first good way for building a website.

Using a terminal with a PowerShell or PowerShell Core interpreter on Windows 10, go to your $HOME, your personal user repostirory.

`PS > cd $HOME`

Next, we use a pakage manager named `scope` for install hugo in easy way.
For installing it,

`PS > iwr -useb get.scoop.sh | iex`

If you encountered somes problem, please refer [offical scoop website](https://scoop.sh/).
Dont-panic if it's just an execution policy error.
Next, we can install hugo with scope in one line :


`PS > scoop install hugo`

Test if hugo is well installed.

`PS > hugo version`

```
PS > hugo
Error: Unable to locate config file or config directory. Perhaps you need to create a new site.
Run `hugo help new` for details.
```

For our hugo projects, we create a dedicated repository.

`PS > mkdir hugo`

We go in.

`PS > cd hugo`

Well. First we use hugo for create a new site project.

`PS > hugo new site hugo-theme-learn`

Next, we install the theme with the git cloning command into the themes repository.

`PS > git clone https://github.com/matcornic/hugo-theme-learn.git ./themes`

You can now edit the file `config.toml` :

```
baseURL = "http://example.org/"
languageCode = "en-us"
title = "My New Hugo Site"

# Change the default theme to be use when building the site with Hugo
theme = "hugo-theme-learn"
```

Now we can create our first chapter :

`hugo new --kind chapter basics/_index.md`

You can edit tne new file into `Content/`
Don't forget to turn off the draft yaml parameter in the front mater of your new chapter page if you want to see your page published in your website.


Before building, we create our first content page in the previously created chapter.

`hugo new basics/first-content.md`

