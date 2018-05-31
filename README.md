## gulp commands

### pug html
gulp pug:build

(pretty: true)

### html
gulp html:build

(rigger() include file - //= file path)

### js
gulp js:build

sourcemaps/suffix .min/uglify

### css
gulp style:build

sourcemaps/sass/autoprefixer/rename .min/cleancss ie8/

### image
gulp image:build

imagemin

### sprite
gulp sprite:build

spritesmith
retima filter / *2@.png

### fonts
gulp fonts:build

### watch
gulp watch

pug, css, js, image, sprite, fonts


### web server
gulp webserver

browserSync

//config for the web server
var config = {
	server: {
		baseDir: "./build"
	},
	//tunnel: true,
	host: 'localhost',
	port: 8888,
	logPrefix: "start"
};

### default

gulp default

build, webserver, watch

# start

mkdir project name

git init

npm init
copy package json
sudo npm install

touch .gitignore

bower_components/
node_modules/
.DS_Store
.DS_Store?

copy gulpfile.js

bower init

create git folder on GitHub
git add .
git commit -m “first commit"
git remote add origin https://github.com/AlexanderDolgan/Litro.git
git push -u origin master

touch .gitignore
# OS generated files #
######################
.DS_Store
.DS_Store?
._*
.Spotlight-V100
.Trashes
ehthumbs.db
Thumbs.db

node_modules/
bower_components/

sudo npm i gulp-sass -ES --unsafe-perm=true
