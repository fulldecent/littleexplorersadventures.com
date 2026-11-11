# littleexplorersadventures.com

This project is built based on [best practices documented in github-pages-template](https://github.com/fulldecent/github-pages-template), release 1.9.0. The lint workflow is that release's .github/workflows/lint.yml. Jekyll build scripts from the template are omitted. Prettier's liquid HTML parser does not reach a fixed point on `index.html`, so `.prettierignore` lists those files. `.prettierignore` lists jQuery, jQuery UI, Owl Carousel, and the old Internet Explorer stylesheets. Pushes to master run the lint workflow, because master is the default branch.
