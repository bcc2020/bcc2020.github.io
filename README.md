# Bioinformatics Community Conference 2020 Website

## Website: https://bcc2020.github.io/

## About

The BCC2020 website is built on top of [Jekyll](http://jekyllrb.com/) - simple, blog-aware, static site generator. Jekyll also happens to be the engine behind GitHub Pages, which means you can use Jekyll to host your website from GitHub’s servers for free. [Learn more about Jekyll](http://jekyllrb.com/).

Template is brought by [GDG Lviv](http://gdg.org.ua/) team. Substantial modifications were made to get it working for a non-GDG event.

## Local development

Check if you have [all requirements for local environment](http://jekyllrb.com/docs/installation/).
To install all development dependencies install [Bundler](http://bundler.io/).
```bash
    gem install bundler
```
and run next command from root folder:

```bash
  bundle install
```  

To start Jekyll run:
```bash
    bundle exec jekyll clean && bundle exec jekyll serve --incremental
```
Site will be available at http://127.0.0.1:4000/ or http://localhost:4000/ (on Windows)

**NOTE:** in this mode all changes to html, image, and css files will be automatically regenerated, but most changes to .yml files, layouts, and `_config.yml` will not. If your website is not updating, kill the `serve` command and make sure you are running `bundle exec jekyll clean` before re-launch.

### Sass(Compass) support
**Note:** You need to install [Node.js](http://nodejs.org/download/)

To watch changes of `.sass` files and compile it to the `.css` on a fly change property `safe: true` to `safe: false` in `_config.yml`.
**Note: It works only on local machine, because GitHub runs Jekyll in `--safe` [mode](https://help.github.com/articles/using-jekyll-with-pages/#configuration-overrides)**

Learn more about Sass development from [documentation](https://github.com/gdg-x/zeppelin/wiki/Sass-development).

### Documentation

[Full documentation](https://github.com/gdg-x/zeppelin/wiki) on the original template is available from GDG-X.


### Contributors
* The BCC committee
* For the original template, see [list of contributors](https://github.com/gdg-x/zepplin/graphs/contributors)

### License
Project is published under the [MIT license](https://github.com/gdg-x/zeppelin/blob/master/LICENSE.txt). Feel free to clone and modify repo as you want, but don't forget to add reference to authors :)


### Images from Unsplash

- Hero image by Juan Davila @juanster
- Team image by Chang Duong @chang612
- Submission image by ron dyar @prolabprints
- Collabfest image by You X Ventures @youxventures
- Partners image by Tom Crew @tomcrewceramics
- About section:
  - Speaker image by Wonderlane @wonderlane
  - Workshop image by Priscilla Du Preez @priscilladupreez
  - CoFest image by Marvin Meyer @marvelous
- Keynote image by Andrew Seaman @amseaman
