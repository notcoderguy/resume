## NotCoderGuy's Resume

This repo is clone of [Thomashighbaugh/resume](https://github.com/Thomashighbaugh/resume) but is adjusted to work with [notcoderguy/web-taste](https://github.com/notcoderguy/web-taste). Hence you can clone the original base directory according to your requirements.

## How to run it
Clone the git repository
```
git clone https://github.com/notcoderguy/resume.notcoderguy.com
```

Install the dependencies:

```
npm install
```

After that, fire up vite using:

```
npm run dev
```

To build final build use:

```
npm run build
```

Navigate to the base directory:

```
cd src
```
<hr>

## Starting Point

`src/index.html` is the main content file. By copying HTML: add pages, sections, subsection, and other parts.

`npm run build` rebuilds all src files into `dist` directory with minified and optimized HTML and CSS.

<hr>

## Tailwind CSS

A nice bootstrap alternative that doesn't have as much opinionation that is all the rage these days with the 'hates css' crowd that while not a part of, I definitely didn't want to fall behind and thus I took this oppurtunity to practice a bit. 

**Note:** The way I am using Tailwind here varies wildly from the way I use it elsewhere and is a bit of an old school way to deploy it but `it works` just fine so I am not going to throw the monkey wrench in the project anytime soon on that front. 

<hr>


## Custom CSS

Code from `tailwind.config.js` and `src/resources/css/app.css` transpiles to `dist/assets/index.[salt].css`.

<hr/>

## Balanced Columns

Removing `col-fill-auto` class will make both columns equally tall. Moreover, removing `md:h-letter` and `md:h-letter-col` classes will eliminate fixed proportions of the letter or A4 page — thereby removing unnecessary vertical space when displaying short columns.

<hr/>


## Printing

### Chrome

Right-click → Print.  

OR 

You can save it as a PDF which will probably keep the SVG image and the other things being stripped out by the print optimizations, but there are use cases for that as well and its not like there really is a `right way` 

------

### Firefox

File → Print.

### Adobe Acrobat Reader

File → Print.

By clicking on the **Page Setup** button, you are taken to the window with A4 and Letter options.