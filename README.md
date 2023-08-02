## ASA minisymposium pages

+ Homepage: https://asa-ssc.github.io/minisymp2023/.
+ The template is cloned from https://github.com/Phlow/feeling-responsive.
+ Documentations are avaliable at https://phlow.github.io/feeling-responsive/ 
  and `pages/documentation.md`.


## Edit/add pages

+ Site title: `_config.yml`->`title`.
+ Menu bar: `_data/navigation.yml`.
+ Homepage: `pages/pages-root-folder/index.md`.
+ Add `.md` file into `pages` folder and link to `data/navigation.yml` 
  to create new pages.

## View/test site locally

https://docs.github.com/en/pages/setting-up-a-github-pages-site-with-jekyll/testing-your-github-pages-site-locally-with-jekyll


## Nav bar background

+ `_01_settings_colors.scss` line 37 `$topbar-background`
+ `_navigation.html` line 13 `background-color:`


## Nav bar text color

+ `_01_settings_colors.scss` line 38 `$topbar-text-color`
+ `_01_settings_colors.scss` line 39 `$topbar-active-color` (active page)
+ Title color: `_navigation.html` line 23 `style="color:white"`