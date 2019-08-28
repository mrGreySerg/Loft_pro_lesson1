#node.js

###learning npm
1. global install or local. Nowdays documentation say that local, and global install is only for **npm cli**.
2. checked: npm list -g --depth=0 (for global modules) and npm list --depth=0 (for local).
3. npm (config) get prefix - where our modules instaling global.
4. npm install -D(devdependencies) -S(dependencies) gulp.
5. package.json - file manifest.
6. npm link gulp browser-sync  -  installing links from global installed modules, but out project think that its installed local. and they are in package.json. But if delete modules installed globally, links installed modules will crash.
link is the reference to the global package.
7. commonJS - module system(export/require).
8. npm -v; node -v; npm version - more unwrapped(развернутая).
9. node - run repl and you can use javascript not only in browser. (as for me - not good).
10. npm init -y short form enitialization of package.json.
11. npm install jquery@1.6 -S - bower is died )). AND normalize -S ).
12. npm outdated - npm said us what library is get old.
13. npm update -S  - update libraries to wanted not latest becouse our programm can crash if we install latest versions.
14. npm uninstall -S normalize - uninstall not only at node_modules and also at package.json (-S help us).
15. module.exports = function(a,b){return ...}; -> const summa = require("./modules/sum.js(js not compalsary)) 
console.log(summa(a,b))