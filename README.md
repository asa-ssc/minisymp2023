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

### MacOS

+ Install `ruby`, `jekyll`, `bundler`: https://youtu.be/UKB9ylw0G4U?t=318
+ `bundle install`
+ `bundle exec jekyll serve`
  - Note: If you've installed Ruby 3.0 or later (which you may have if
    you installed the default version via Homebrew), you might get an
    error at this step. That's because these versions of Ruby no
    longer come with webrick installed.
  - To fix the error, try running bundle add webrick, then re-running bundle exec jekyll serve.
+ To preview your site, in your web browser, navigate to http://localhost:4000
+ Live preview may not work well; therefore, to ensure proper
  functionality, stop the server, make edits, and then restart it.


### Help page

https://docs.github.com/en/pages/setting-up-a-github-pages-site-with-jekyll/testing-your-github-pages-site-locally-with-jekyll


## Nav bar background

+ `_01_settings_colors.scss` line 37 `$topbar-background`
+ `_navigation.html` line 13 `background-color:`


## Nav bar text color

+ `_01_settings_colors.scss` line 38 `$topbar-text-color`
+ `_01_settings_colors.scss` line 39 `$topbar-active-color` (active page)
+ Title color: `_navigation.html` line 23 `style="color:white"`