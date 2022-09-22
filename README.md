# Hangeul Stroke Order Diagrams
<img src="samples/hangeul_consonants_with_stroke_order.svg" style="width:
100%" alt="The stroke order of the Hangeul consonant letters" />

These are high-quality vector images in SVG format illustrating the stroke
order of 35 of the 40 letters of the Korean alphabet known as Hangeul
(한글). Stroke order diagrams for the five tense consonants were omitted
because they are simply doubled versions of other consonantal letters.

## Using These Images in Anki
These SVG files have had their elements labelled to permit customized
styling using CSS. The arrows, circled numbers, and Hangeul letters can all
be styled individually using CSS.

If you want to use these images in [Anki](https://apps.ankiweb.net/) as
part of your Hangeul study strategy, I recommend that you paste the SVG
code directly into Anki’s HTML editing mode (accessed using Ctrl+Shift+X).
This will permit styling these graphics to display differently depending on
whether Night Mode is enabled. For example, I am using the following CSS in
my own Hangeul deck:

```css
/* Color the SVG stroke order diagrams to match light/dark mode */
.jamo path { fill: #000 }
.stroke-number path { fill: #7e00cc }
path.order-arrow { fill: #bf80e6 }

.nightMode .jamo path { fill: #fff }
.nightMode .stroke-number path { fill: #ef8354 }
.nightMode path.order-arrow { fill: #f7c1aa }
```

## Credits
These images were originally created by Adam Stone using
[Inkscape](https://inkscape.org/). The fonts used are
[UnPen](http://kldp.net/unfonts/) and [Inter](https://rsms.me/inter/). The
SVG code was optimized using
[Scour](https://github.com/scour-project/scour) and subsequently manually
edited.

## License
This project is licensed under the [CC BY-SA
4.0](https://creativecommons.org/licenses/by-sa/4.0/).
