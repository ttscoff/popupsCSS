# Popups

## iOS-esque popups using basic markup with class-based styling.

(Just some CSS for the aesthetic, no implementation code.)

### Download

* [CSS](https://raw.github.com/ttscoff/popupsCSS/master/popups.css)
* [Minified](https://raw.github.com/ttscoff/popupsCSS/master/popups.min.css)


All popups use a div with a class of popup and an unordered list. For a button list, just make the list items links. Additional classes add arrows, remove dividers and justify text.

The arrows are created using a single PNG image (diamond shape with transparency) which is base64 encoded in the stylesheet.

### Markup

#### Option list

    <div class="popup">
    	<ul>
    		<li><a href="#">Option 1</a></li>
    		<li><a href="#">Option 2</a></li>
    		<li><a href="#">Option 3</a></li>
    	</ul>
    </div>					

#### Information list with arrow

    <div class="popup">
    	<ul>
    		<li>100 words</li>
    		<li>15 lines</li>
    		<li>3,504 characters</li>
    		<li>1,000,000 smiles</li>
    		<li>4 turtle doves</li>
    		<li>1 you</li>
    	</ul>
    	<span class="arrow"></span>
    </div>

### Classes

* **north, south, east, west:** add directional arrows
* **compact:** lower padding between items
* **nodivider:** remove dividers between items
* **left:** left-justify text in list items (default centered)