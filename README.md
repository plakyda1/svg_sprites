# Установить зависимости и запустить gulp
####Требуется node.js

npm i

bower i

## Для SVG-Sprite

###Установить плагины

####npm install gulp-svg-sprite gulp-svgmin gulp-cheerio gulp-replace -g
####npm link gulp-svg-sprite gulp-svgmin gulp-cheerio gulp-replace

###Файл шаблона(для генрации scss) в папке sass/templates/_sprite_template.svg
###Подключить сгенерированый файл стилей _spriteSvg.scss (src/sass/base/_spriteSvg.scss)
###Готовый sprite в папкe img/sprites/sprite.svg

####gulp (для слежки за файлами)
####gulp svgSprite (для сборки svg спрайта)


