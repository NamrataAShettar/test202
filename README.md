
This site is based on the brilliantly minimalist <a href="https://github.com/sergiokopplin/indigo">Indigo theme</a> by <a href="https://github.com/sergiokopplin">Kopplin</a></p>


## Setup
1. Clone repo.
2. Install Jekyll, NodeJS and Bundler.
3. `bundle install`
4. `bundle exec jekyll serve --config _config.yml,_config-dev.yml`
5. Site can be viewed at `http://localhost:4000`

## Changes and Deployment
1. Switch to gh-pages branch using `git checkout gh-pages`.
2. Make changes and preview using commands described in the earlier section.
3. Commit and push to `origin/gh-pages`.
4. Switch to master using `git checkout master`.
5. Merge from `gh-pages` using `git merge gh-pages`.
6. Push to `origin/master`.

## License

[MIT](http://kopplin.mit-license.org/) License © Sérgio Kopplin
