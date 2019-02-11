# Gingershots Tasks 
### Not a complete list
1. Product description two columns (left column text, right column nutrition label image)
```html
/* Product description: text in one column, image in other column */
<div style="float:left; width: 48%;padding: 10px">
    You'll see everything you need to know on the label. Only two ingredients. Organic ginger juice + organic apple juice. That means no preservatives, no additives, nothing watering down our cold pressed organic ginger shot.

    We think that whole 'apple a day' thing is pretty great, but maybe they were missing something. The second you take a gulp of pure ginger extract mixed with fresh, organic apple juice, you'll know what we're talking about. Ginger and apple is an unbeatable combination.

    FREE SHIPPING when you order 2 packs (of 6) or more!
</div>
<img src="http://ginger.wpkdesign.com/wp-content/uploads/2018/06/FDA_Nutrition_Facts_Label_2006-153x300.jpg" alt="" style="float:right; width: 48%;" class="alignnone size-medium wp-image-26706" />
```
Before:
![Task1Before](Task1Before.png)
After:
![Task1After](Task1After.png)
2. Put social icons into footer
Before:
![Task2Before](Task2Before.png)
After:
![Task2After](Task2After.png)
3. Make social icons white when hovered on
```css
/* Social media icons turn white when hovered on*/
.socials-colored-hover a:hover .socials-item-icon.facebook {
    color: #ffffff;
}
.socials-colored-hover a:hover .socials-item-icon.twitter {
    color: #ffffff;
}
.socials-colored-hover a:hover .socials-item-icon.pinterest {
    color: #ffffff;
}
.socials-colored-hover a:hover .socials-item-icon.instagram {
    color: #ffffff;
}
.socials-colored-hover a:hover .socials-item-icon.youtube {
    color: #ffffff;
}
```
Result:
![Task3After](Task3After.png)
4. Hide social icons only on the homepage
```css
/* Hide social media icons in footer on homepage */
.page-id-26475 #footer-nav .socials-item
{
    visibility: hidden;
}
```
Before:
![Task4Before](Task4Before.png)
After:
![Task4After](Task4After.png)
5. Make social icons black in copyright footer
```css
/* Make social media icons black */
.socials-colored a .socials-item-icon.facebook{
    color: #000000;
}
.socials-colored a .socials-item-icon.twitter{
    color: #000000;
}
.socials-colored a .socials-item-icon.pinterest{
    color: #000000;
}
.socials-colored a .socials-item-icon.instagram{
    color: #000000;
}
.socials-colored a .socials-item-icon.youtube{
    color: #000000;
}
```
Before:
![Task5Before](Task5Before.png)
After:
![Task5After](Task5After.png)
