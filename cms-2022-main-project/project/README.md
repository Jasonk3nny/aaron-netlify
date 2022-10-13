# Aaron G. Miller's website


## Webdev-Dependencies
`npm i`
 
## Live server / browser syncing
`(cd ./dist && npx browser-sync start -s  --files='**/*' --watch)`
`npx browser-sync dist -w`


## Build
Run `./build` to
* compile sass
* bundle JavaScript
* copy the index-file
* copy the `/images'-folder
* ...


### Clean Build
Run `./clean-build` to build a new dist-folder from scratch.


## Deploy with netlify
If you only need a static site and set up netlify, simply push to main, which then automatically triggers a new deployment.


