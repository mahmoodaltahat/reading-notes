# Images, Color, Text


### HTML Images

##### Images can improve the design and the appearance of a web page.

![image](https://res.cloudinary.com/practicaldev/image/fetch/s--XdEzFu31--/c_imagga_scale,f_auto,fl_progressive,h_420,q_auto,w_1000/https://dev-to-uploads.s3.amazonaws.com/i/12yinjh00gskbwavqtqp.png)


##### The HTML img tag is used to embed an image in a web page.

##### Images are not technically inserted into a web page; images are linked to web pages. The img tag creates a holding space for the referenced image.

##### The img tag has two required attributes

##### src - Specifies the path to the image 

##### alt - Specifies an alternate text for the image

##### Image Size - Width and Height,You can use the style attribute to specify the width and height of an image.


##### The width and height attributes always define the width and height of the image in pixels.

# Aligning Images Horizontally

## align
##### chapter-05/aligning-images-horizontally.html HTML The align attribute was commonly used to indicate how the other parts of a page should flow around an image. It has been removed from HTML5 and new websites should use CSS to control the alignment of images

## left This aligns the image to the left

##### right This aligns the image to the right

# Aligning Images Vertically
##### There are three values that the align attribute can take that control how the image should align vertically with the text that surrounds it:

# top
##### This aligns the first line of the surrounding text with the top of the image.

# middle

##### This aligns the first line of the surrounding text with the middle of the image.

# bottom
##### This aligns the first line of the surrounding text with the bottom of the image

# Tools to Edit & Save Images
- Adobe Photoshop
- Adobe Fireworks
- Pixelmator
- PaintShop Pro
- Paint.net
- Online Editors
- www.photoshop.com
- www.pixlr.com
- www.splashup.com
- www.ipiccy.com
- Image Resolution
- Images created for the web should be saved at a resolution of 72 ppi. 

##### The higher the resolution of the image, the larger the size of the file.

# Color
##### The color CSS property sets the foreground color value of an element’s text and text decorations, and sets the value. currentcolor may be used as an indirect value on other properties and is the default for other color properties, such as border-color


# CSS Colors
##### Colors in CSS can be specified by the following methods:

# Hexadecimal colors
# Hexadecimal colors with transparency
- RGB colors
- RGBA colors
- HSL colors
- HSLA colors
- Predefined/Cross-browser color names

##### With the currentcolor keyword
##### Background Color background-color

##### CSS treats each HTML element as if it appears in a box, and the background-color property sets the color of the background for that box. You can specify your choice of background color in the same three ways you can specify foreground colors: RGB values, hex codes, and color names (covered on the next page). If you do not specify a background color, then the background is transparent. By default, most browser windows have a white background, but browser users can set a background color for their windows, so if you want to be sure that the background is white you can use the background-color property on the body element.


# Text

#### HTML Text Formatting
##### HTML contains several elements for defining text with a special meaning.

##### HTML Formatting Elements Formatting elements were designed to display special types of text:

- b - Bold text
- strong - Important text
- i - Italic text
- em - Emphasized text
- mark - Marked text
- small - Smaller text -del- - Deleted text
- ins - Inserted text
- sub - Subscript text
- sup - Superscript text

# font-family
##### Generic Font Families In CSS there are five generic font families:

##### Serif fonts have a small stroke at the edges of each letter. They create a sense of formality and elegance.
##### Sans-serif fonts have clean lines (no small strokes attached). They create a modern and minimalistic look.
##### Monospace fonts - here all the letters have the same fixed width. They create a mechanical look.
##### Cursive fonts imitate human handwriting.
##### Fantasy fonts are decorative/playful fonts. All the different font names belong to one of the generic font families.

# Font size

##### The font-size property enables you to specify a size for the font. There are several ways to specify the size of a font. The most common are: pixels Pixels are commonly used because they allow web designers very precise control over how much space their text takes up. The number of pixels is followed by the letters px. percentages The default size of text in browsers is 16px. So a size of 75% would be the equivalent of 12px, and 200% would be 32px. If you create a rule to make all text inside the body element to be 75% of the default size (to make it 12px), and then specify another rule that indicates the content of an element inside the body element should be 75% size, it will be 9px (75% of the 12px font size). ems An em is equivalent to the width of a letter m.


# font-weight
#### The font-weight property allows you to create bold text. There are two values that this property commonly takes: normal This causes text to appear at a normal weight. bold This causes text to appear bold. In this example, you can see that the element whose class attribute has a value of credits has been bolded. You might wonder why there is a normal weight. This is because if, for example, you created a rule for the body element indicating that all text inside the body should appear bold, you might need an option that allows the text in certain instances to appear normal weight. So it is essentially used as an “off switch.”

# font-style
##### If you want to create italic text, you can use the font-style property. There are three values this property can take: normal This causes text to appear in a normal style (as opposed to italic or oblique). italic This causes text to appear italic. oblique This causes text to appear oblique. In this example, you can see that the credits have been italicized. Italic fonts were traditionally stylized versions of the font based on calligraphy, whereas an oblique version would take the normal version and put it on an angle. It is not unusual for the browser to fail to find an italic version of a typeface, in which case it will use an algorithm to place the normal version of the type on a slant, which means that a lot of italic text online is actually oblique.

# UpperCase & LowerCase
##### text-transform The text-transform property is used to change the case of text giving it one of the following values:
- uppercase This causes the text to appear uppercase.
- lowercase This causes the text to appear lowercase.

##### capitalize This causes the first letter of each word to appear capitalized. In this example, the h1 element is uppercase, the h2 element is lowercase, and the credits are capitalized. In the HTML, the word by in the credits had a lowercase b.

# text-decoration
##### The text-decoration property allows you to specify the following values:

- none This removes any decoration already applied to the text.
- underline This adds a line underneath the text.
- overline This adds a line over the top of the text.
- line-through This adds a line through words.

##### blink This animates the text to make it flash on and off (however this is generally frowned upon, as it is considered rather annoying).

# line-height
##### Leading (pronounced ledding) is a term typographers use for the vertical space between lines of text. In a typeface, the part of a letter that drops beneath the baseline is called a descender, while the highest point of a letter is called the ascender. Leading is measured from the bottom of the descender on one line to the top of the ascender on the next.

# Text
##### There are properties to control the choice of font, size, weight, style, and spacing.
##### There is a limited choice of fonts that you can assume most people will have installed.

##### If you want to use a wider range of typefaces there are several options, but you need to have the right license to use them.
##### You can control the space between lines of text, individual letters, and words. Text can also be aligned to the left, right, center, or justified. It can also be indented.

##### You can use pseudo-classes to change the style of an element when a user hovers over or clicks on text, or when they have visited a link.

