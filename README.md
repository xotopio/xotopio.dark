# xotopio for [Visual Studio Code](http://code.visualstudio.com)

xotopio is a dark window theme for vs code, inspired by neon based designs.</br>
This theme will be optimised when ever I find something to improve. </br>
If you have any problems or wishes to improve the theme, please message me to xotopio@gmail.com to make this your optimised theme as well!

## Installation
Download it from the [Marketplace](https://marketplace.visualstudio.com/items?itemName=xotopio.xotopio-dark) or on
[GitHub](https://github.com/xotopio/xotopio.dark) via:

```
git clone https://github.com/xotopio/xotopio.dark
```

### step by step from the vs store

1.  Install [Visual Studio Code](https://code.visualstudio.com/)
2.  Launch Visual Studio Code
3.  Choose **Extensions** from menu
4.  Search for `xotopio-dark`
5.  Click **Install** to install it
6.  Click **Reload** to reload the Code
7.  From the menu bar click: Code > Preferences > Color Theme > Pick your xotopio theme

## Support language

- [x] HTML
- [x] VUE-HTML
- [x] CSS
- [x] SCSS
- [ ] SASS
- [ ] LESS
- [ ] Stylus
- [x] JavaScript
- [x] Markdown

## How do I enable the glow seen in the screenshot?
[Read instructions here](https://github.com/robb0wen/synthwave-vscode#to-enable-the-glow).

`xotopio.css` stylesheet:

```css
[aria-label="Editor actions"] { display:none!important } 
.mtk36 { color: #afc3e7; text-shadow: 0 0px 10px #afc3e7, 0 0px 2px black; } 
.mtk76 { color: #52b1fff3; text-shadow: 0 1px 16px #73c0ff, 0 0px 2px black; } 
.mtk75 { color: #30ffe3; text-shadow: 0 0px 10px #30ffe3, 0 0px 2px black; } 
.lightbulb-glyph { background:url("data:image/svg+xml,%3Csvg id='Layer_1' data-name='Layer 1' xmlns='http://www.w3.org/2000/svg' viewBox='0 0 16 16'%3E%3Crect fill='%23ffffff' x='5.68' y='6.93' width='2.1' height='6.1' rx='0.96' transform='translate(-1.94 1.63) rotate(-12.09)'/%3E%3Cpath fill='%2303edf9' d='M7.08,13.5a1.46,1.46,0,0,1-1.43-1.16L4.77,8.26A1.47,1.47,0,0,1,5.9,6.53l.17,0A1.46,1.46,0,0,1,7.81,7.61l.87,4.09a1.46,1.46,0,0,1-1.12,1.73l-.18,0Zm-.7-6h-.1l-.17,0a.45.45,0,0,0-.29.21.45.45,0,0,0-.07.34l.88,4.09a.46.46,0,0,0,.54.35l.18,0a.46.46,0,0,0,.29-.2.48.48,0,0,0,.07-.35L6.83,7.82A.46.46,0,0,0,6.38,7.46Z'/%3E%3Crect fill='%23ffffff' x='8.22' y='6.93' width='2.1' height='6.1' rx='0.96' transform='translate(16.25 21.68) rotate(-167.91)'/%3E%3Cpath fill='%2303edf9' d='M8.93,13.5a1.63,1.63,0,0,1-.31,0l-.18,0A1.46,1.46,0,0,1,7.32,11.7l.87-4.09A1.47,1.47,0,0,1,9.93,6.49l.18,0a1.45,1.45,0,0,1,.92.63,1.47,1.47,0,0,1,.2,1.1l-.88,4.08a1.45,1.45,0,0,1-.63.93A1.48,1.48,0,0,1,8.93,13.5Zm.69-6a.45.45,0,0,0-.25.07.5.5,0,0,0-.2.29L8.3,11.9a.43.43,0,0,0,.06.35.46.46,0,0,0,.29.2l.18,0a.47.47,0,0,0,.55-.35l.87-4.09a.45.45,0,0,0-.06-.34A.47.47,0,0,0,9.9,7.5l-.18,0Z'/%3E%3Cpath fill='%23ffffff' d='M11.77,9l-3.53.67a1,1,0,0,1-1.15-.88h0A1.09,1.09,0,0,1,7.9,7.48l3.53-.67a1,1,0,0,1,1.15.89h0A1.08,1.08,0,0,1,11.77,9Z'/%3E%3Cpath fill='%2303edf9' d='M8.07,10.18A1.54,1.54,0,0,1,6.6,8.83a1.74,1.74,0,0,1,.25-1.22,1.46,1.46,0,0,1,1-.66l3.52-.67A1.51,1.51,0,0,1,13.07,7.6a1.61,1.61,0,0,1-1.22,1.88l-3.52.67A1.15,1.15,0,0,1,8.07,10.18ZM11.6,7.34h-.09L8,8a.53.53,0,0,0-.4.62.5.5,0,0,0,.57.44l3.52-.67a.54.54,0,0,0,.41-.62A.53.53,0,0,0,11.6,7.34Z'/%3E%3Cpath fill='%23ffffff' d='M11.74,6.74,4.67,8.08A1,1,0,0,1,3.52,7.2h0A1.08,1.08,0,0,1,4.33,6l7.06-1.34a1,1,0,0,1,1.16.88h0A1.08,1.08,0,0,1,11.74,6.74Z'/%3E%3Cpath fill='%2303edf9' d='M4.5,8.64a1.44,1.44,0,0,1-.86-.29A1.64,1.64,0,0,1,3,7.29a1.72,1.72,0,0,1,.25-1.21,1.48,1.48,0,0,1,1-.67l7.07-1.34a1.39,1.39,0,0,1,1.11.27A1.65,1.65,0,0,1,13,5.4a1.72,1.72,0,0,1-.25,1.21,1.48,1.48,0,0,1-1,.67L4.76,8.62Zm7.07-3.5h-.09L4.42,6.49a.45.45,0,0,0-.32.22.56.56,0,0,0-.09.4.61.61,0,0,0,.21.35.47.47,0,0,0,.36.09L11.65,6.2A.47.47,0,0,0,12,6a.51.51,0,0,0,.08-.4.55.55,0,0,0-.2-.35A.47.47,0,0,0,11.57,5.14Z'/%3E%3Cpath fill='%23ffffff' d='M11.7,4.52,4.64,5.86A1,1,0,0,1,3.49,5h0A1.09,1.09,0,0,1,4.3,3.72l7.06-1.34a1,1,0,0,1,1.15.88h0A1.09,1.09,0,0,1,11.7,4.52Z'/%3E%3Cpath fill='%2303edf9' d='M4.46,6.42a1.36,1.36,0,0,1-.85-.3,1.58,1.58,0,0,1-.61-1A1.61,1.61,0,0,1,4.21,3.19l7.07-1.34a1.35,1.35,0,0,1,1.11.27,1.58,1.58,0,0,1,.61,1,1.74,1.74,0,0,1-.25,1.22,1.44,1.44,0,0,1-1,.66L4.72,6.39A1.09,1.09,0,0,1,4.46,6.42Zm7.07-3.51h-.08L4.38,4.26a.53.53,0,0,0-.4.62.5.5,0,0,0,.57.44L11.62,4a.47.47,0,0,0,.32-.22.62.62,0,0,0,.08-.4.56.56,0,0,0-.2-.35A.53.53,0,0,0,11.53,2.91Z'/%3E%3Cpath fill='%23ffffff' d='M8.34,2.89,4.57,3.6a1,1,0,0,1-1.15-.88h0a1.08,1.08,0,0,1,.81-1.25L8,.75a1,1,0,0,1,1.15.89h0A1.08,1.08,0,0,1,8.34,2.89Z'/%3E%3Cpath fill='%2303edf9' d='M4.4,4.16a1.44,1.44,0,0,1-.86-.29,1.69,1.69,0,0,1-.61-1.05A1.74,1.74,0,0,1,3.18,1.6a1.51,1.51,0,0,1,1-.67L7.91.22A1.38,1.38,0,0,1,9,.49a1.58,1.58,0,0,1,.61,1.05,1.74,1.74,0,0,1-.25,1.22,1.47,1.47,0,0,1-1,.66l-3.77.72A1.18,1.18,0,0,1,4.4,4.16ZM8.17,1.28H8.09L4.32,2A.45.45,0,0,0,4,2.23a.51.51,0,0,0-.08.4.55.55,0,0,0,.2.35.49.49,0,0,0,.37.09l3.77-.72a.47.47,0,0,0,.32-.22.62.62,0,0,0,.08-.4.56.56,0,0,0-.2-.35A.53.53,0,0,0,8.17,1.28Z'/%3E%3Cpolygon fill='%231e1e1e' points='5.5 11.1 5.5 11.1 5.5 14.4 7.1 16 9.1 16 10.6 14.4 10.6 11.1 5.5 11.1'/%3E%3Cpath fill='%23c5c5c5' d='M6.5,12h3v1h-3Zm1,3H8.6l.9-1h-3Z'/%3E%3C/svg%3E") 40% no-repeat!important; filter:drop-shadow(0 0 5px #03edf9) } 
```

#### HTML:
<img src="https://raw.githubusercontent.com/xotopio/xotopio.dark/master/imgs/examples/html.png" width="700" height="600">

#### JAVA:
<img src="https://raw.githubusercontent.com/xotopio/xotopio.dark/master/imgs/examples/java.png" width="700" height="600">

#### Javascript:
<img src="https://raw.githubusercontent.com/xotopio/xotopio.dark/master/imgs/examples/js.png" width="700" height="600">

#### CSS:
<img src="https://raw.githubusercontent.com/xotopio/xotopio.dark/master/imgs/examples/css.png" width="300" height="580">

#### C++:
<img src="https://raw.githubusercontent.com/xotopio/xotopio.dark/master/imgs/examples/c++.png"  width="720" height="580">

#### Ruby:
<img src="https://raw.githubusercontent.com/xotopio/xotopio.dark/master/imgs/examples/ruby.png"  width="700" height="580">

#### IN BLACK AND WHITE : Xotopio-light | Xotopio-Dark
<img src="https://raw.githubusercontent.com/xotopio/xotopio.dark/master/imgs/examples/new.png" width="800" height="500">

##### Contact
by [xotopio](https://github.com/xotopio)

<!-- [license]() -->

**Enjoy!**
