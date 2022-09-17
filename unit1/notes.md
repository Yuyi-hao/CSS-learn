## <h1><center>Unit One<center></h1>

**CSS - cascading style sheet**

It mainly use fro styling of documentation written in [HTLM](https://www.w3schools.com/html/) or XML(including dialects such as SVG,MathML or XHTML).\
CSS describe how elements should be render on screen, on paper, in speech, or on any other device.

There are three ways to add styles in HTML document -:
* External style sheet - by using an external .CSS file. 
* Internal Style tag - by using an internal `<style>...</style>` tag in `<head>...</head>` tag.
* Inline style - by using a style attribute in HTML tags itself.

## External Style sheet
This can we done with the use of an external .CSS file.\
We describe all our styling in that ss file and link it to HTML document using `<link>` tag in `<head>...</head>` tag  
```HTML
<link rel="stylesheet" herf="path to your style sheet"  type ="text/CSS">
```
_You can omit the type attribute in link tag as ths style not in use now._

## Internal Style 
This can be done by using a `<style>...</style>` tag in `<head>...</head>` tag.\
The syntax in ths tag is same as we describe in any .CSS file.

```HTML
<Style>
    /* your code goes here */ 
</Style>
```
## Inline CSS 
We apply style in tag itself using `style` attribute.
```HTML
<p style="color : white; font-size: 20px">This is an example of inline CSS</p>
```
--

The order in which these style is applied depends on which style we applied in last. If we put `<link>` tag before the `<style>` tag then the style in `<style>` tag will  displayed as result vice-versa.\
But if we have inline style then that will be applied for sure.

<hr>

## **Code structure of a CSS statement**
```css
p{
    color : Purple;
} 
```
Every CSS code block(called as **ruleset** ) start with some **selector** here `p` us selector for all the `<p>...</p>` tag in HTML document\
The `{...}` denotes the starting an ending of a CSS style block.\
Each line in CSS ruleset called as a declaration.
Every CSS Declaration have `property : value;` pair like structure.\

![css code structure](https://cdn-images-1.medium.com/max/1600/1*naFDyXh9iGtmvNRhhFY-og.png)

_CSS uses mainly American spelling._\
If you have any error in CSS file it just ignore it, unlike any other language it won't be throwing any error.
So to check our CSS is valid or not we can use any CSS validator e.g. - [W3C world wide web consortium](https://jigsaw.w3.org/css-validator/)













