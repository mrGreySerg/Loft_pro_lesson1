#node.js

###learning npm
1. global install or local. Nowdays documentation say that local, and global install is only for **npm cli**.
2. checked: npm list -g --depth=0 (for global modules) and npm list --depth=0 (for local).
3. npm config get prefix - where our modules instaling global.
4. npm install -D(devdependencies) -S(dependencies) gulp.
5. package.json - file manifest.
6. npm link gulp browser-sync  -  installing links from global installed modules, but out project think that its installed local. and they are in package.json. But if delete modules installed globally, links installed modules will crash.
link is the reference to the global package.
7. commonJS - module system(export/require).
8. npm -v; node -v; npm version - more unwrapped(развернутая).
