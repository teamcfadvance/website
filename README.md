website
=======

Our public website. Want to help, just fork master, make your additions and send a pull request.

The [Website Issues List](https://github.com/teamcfadvance/website/issues) contains tasks you can help with. If you see something that's needed but not on the list, please create a new issue so we can discuss.


## How To
1. Fork the repo and clone to your development box.
2. Make sure you've got Node.js installed and then from terminal just run `npm install`. NPM will install all the build dependancies listed in package.json.
3. Next run `bower install` to install our site dependancies listed in bower.json.
4. We're using Gulp.js as our build manager. From terminal run `gulp watch` which will spin up a live reload server and open a browser tab so you can see your edits live.
5. When you're done making changes run `gulp` to run the full build task and update the dist folder. (dist is what we actually load on the server.)
6. Got any questions, just ping us on [Twitter](https://twitter.com/TeamCFAdvance) or [Google+](https://plus.google.com/+TeamCFAdvanceOrg).
