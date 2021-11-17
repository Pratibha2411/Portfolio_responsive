> > >                   SETUP-Start

## Download & Install Node.js then check version in cmd using "node --version or node - v" then:-

1. open project folder in compiler then we have download the package.json from our Compiler using commands so:-
   npm init ["hit enter"]
   hit enter again & agian till Description(Give Description You want) [hit enter] then you will find Keyword so give any number of keywords you wanna give then [hit enter]
   this will ask your name
   you will see LICENCE there [hit enter] & wait for packages to download & it'll show you hit ok to continue so just hit enter & here you done with npm.json packages: "You can see these package.json file in your Project folder"

2. It's time to download other packages LIKE:
   > > .Dart-sass or Sass: -
   > > go to website "npm.js.com" search "sass" it will show "A pure JS implementation of Sass" go in then in Usage you will see "npm install --save-dev sass" copy & paste in cmd & [hit enter] Look in project folder you may see "Node Modules" will consist of all packages we'll download.
   > > Open Project in VS code & in .json file you'll see new "Dependencies". Next-
   > > .Bootstrat 5: -
   > > go to website "getbootstarp.com" search "Installation" it will show "npm install bootstrap" copy & paste in cmd & add "-- save" LIKE: "npm install bootstrap --save"(this will save these packages in dependencies) [hit enter] Look in VS code & in .json file you'll see new "Dependencies bootstrap added". Next-
   > > .FontAwesome: -
   > > go to website "fontawesome.com" search "npm" it will show "npm install -- save fontawesomefree" copy and paste in cmd & [hit enter] & go to VS code & in .json file you'll see new "Dependencies fontawesome added". Next-
   > > .AutoPrefixer: -
   > > go to website "npm.js.com" search "autoprefixer" it will show " npm install postcss-cli autoprefixer --save" Copy & Paste in cmd & [hit enter] & go to VS code & in .json file you'll see new "Dependencies autoprefixer & postcss-cli added". Next-
   > > These all packages we'll use in this project.

## Now you can see Predefined "Script" in .json file so we'll create our own: -

1.  "compile:sass": "sass scss:assets/css"
    compile:sass is the name you can give any other you want to, then: "sass"(it's our package we installed) "scss"(it's the source of our sass file- whick will keep all our sass files) then after : "destination where we want to keep compiled css-(assests/css)"
    so Create new foleder in your Project name by "scss" &in this folder create new file named "style.scss".
2.  in cmd start .script so run command " npm run compile:sass"(here "sass" is the name of the script, which can be any name according to you.)[hit enter]
3.  in VS code you have new folder Assests and assets also have files.
4.  Search files extension for General Knowledge on Google.

> > >                   SETUP-END

Now open assestes folder & open "style.css" & make style.
before writing any style run the script again in cmd by using "npm run compile:sass" You'll have to keep script running everytime we do changes to the scss file so we need to modify this script go to .json file & add "--watch"(watch is a flag which is goin' to watch for the changes inside the scss file we are goin' to made). now no need to run the script again & gain after every change only need to run it once in cmd.

Now you may Add style in your scss file it'll automatically connect to style.css files as well.

> > >           FINALLY Done with Set-up

1. Customiz in boostrap:-
   We'll create another "custom.scss"(instead of custome you may give may name) file to overwrite our css which will overwrite our some css but not the whole scss style.
   watch out the "(\_ This under scroe is must before custom LIKE \_custom)custom.scss" for further.
