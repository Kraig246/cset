- My favorite CSS property so far would definitely have to be background-image. The reason why I lke background-image so much is because there's a lot you can do with just that one element.
It can be used to add images and gradients. It can also be used in concert with other background elements like background-color, background-position, background-repeat and background-size.
There's also so much that you can do with these properties because of the millions of colors available in CSS. The creative possibilities feel unlimited!

- If I was making a website for a restaurant and I had to style the menu options to show spicy, vegetarian and gluten free, I would color code the elements by using class selectors and the color property.
I would have a class for spicy, a class for vegetarian, and a class for gluten-free. I would use class selectors for these foods because more often than not, restaurants tend to have more than one
kind of spicy, vegetarian or gluten free food item. Each item fitting this description gets put under any of these three classes. Then, I would color-code the foods by type.
Spicy would be a red color, vegetarian would be a green color, and gluten-free would be a light blue color. For an example:
```
<p class="spicy">Buffalo Hot Wings</p>

.spicy {
    color: red;
}
```
- The difference between cascade, inheritance, and specificity in CSS is that inheritance refers to he relationship between HTML and CSS tags, cascading refers to the fact that styles across multiple CSS rules
are applied to all HTML tags, and specificity means that the CSS rule with the highest priority will be applied to HTML tags before other tags in order of greater or lesser priority. You can use these concepts to organize
your CSS because you can use cascading for styling across all HTML tags of a specific name, you can use inheritance to relate certain properties between tags in HTML and CSS and you can use specificity to organize rules about the same tag
that are more or less specific than one another.
