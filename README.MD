# Tektite site docs

* Install mkdocs
* Build: `mkdocs build`
* Serve with a local server: `mkdocs serve` - then browse to [http://localhost:8000](http://localhost:8000)
* Make your changes in your own branch
* Submit a pull request against the `site` branch.

# Tektite website

Steps to deploy a new build:
- Commit your local changes.
- This will automatically start a worflow under [Actions](https://github.com/vchandela/tektite-website/actions) tab
- When workflow completes, color of status indicator will change to green.
- We can click on the commit message and see a link to the live site.

Reference: https://gohugo.io/hosting-and-deployment/hosting-on-github/