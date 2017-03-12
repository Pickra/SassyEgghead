# Learn the Best and Most Useful SCSS

Have you ever wished for iteration when writing styles? How cool would it be to use functions to write styles?
SCSS has that and more! SCSS is a superset of CSS. Any valid CSS is SCSS, they even have the same syntax.
SCSS borrows features from other languages to write smarter, reusable and more readable styles.
[This course](https://egghead.io/) will focus on how to use SCSS’s more useful features,
compare them against each other and assess when their usage is appropriate.

## Lesson Titles:

[Organize SCSS into Multiple Files with Partials:](https://github.com/Pickra/SassyEgghead/commits/feature/partials)
Tired of dealing with monolithic CSS files? In this lesson we learn how to separate our styles with SCSS partials,
and the difference between SCSS and CSS imports.

[Organize Styles with SCSS Nesting and the Parent Selector:](https://github.com/Pickra/SassyEgghead/commits/feature/nesting)
In this lesson we learn how to remove the redundancy of targeting pseudo-elements/classes,
and child elements by taking advantage of SCSS’s nesting and parent selectors.

[Use SCSS Variables for Readable and Maintainable Stylesheets:](https://github.com/Pickra/SassyEgghead/commits/feature/variables)
Updating the same color or metric multiple times is no fun. SCSS variables improve maintainability
by allowing 1 name to represent a value that can be used anywhere.
SCSS variables also give us the power of creating our own naming conventions to express the intent of specific values.
In this lesson we learn how to use SCSS variables to assign user friendly names to colors/metrics
so 1 value change will update that value in all the right places.

[Use Standard Built-in SCSS Functions for Common Operations:](https://github.com/Pickra/SassyEgghead/commits/feature/builtInFunctions)
We can use javascript for color and opacity variations, math, list and map logic or to see if something exists.
SCSS includes functions for a wide range of common use cases for logic in our styles.
In this lesson we look at some of the more useful color functions to improve development velocity, readability, and simplify the code.
Be sure to checkout all the [SCSS functions](http://sass-lang.com/documentation/Sass/Script/Functions.html)

[Reusing Styles with the SCSS @mixin Directive:](https://github.com/Pickra/SassyEgghead/commits/feature/mixins)
Copy/pasting the same code is redundant at best. Plus, updating copy/pasted code slows development velocity.
In this lesson we learn how to write reusable styles with the SCSS @mixin directive and make copy/paste a thing of the past.

[Reusing Styles with the SCSS @extend Directive:](https://github.com/Pickra/SassyEgghead/commits/feature/extend)
We can write reusable styles with the SCSS @extend or @mixin directives. Which one is better?
In this lesson we learn about writing reusable styles with the @extend directive and how it compares to the @mixin directive.

[Write similar classes with the SCSS @for Control Directive:](https://github.com/Pickra/SassyEgghead/commits/feature/iterateWithTheForDirective)
Writing similar classes with minor variations, like utility classes, can be a pain to write and update.
Sometimes just a single character is the only difference between classes and updating
the defining parameter means we need to change it for every class name and value.
In this lesson we learn how to leverage the power of the SCSS @for control directive to relieve the pain.

[Loop Over Data with the SCSS @each Control Directive:](https://github.com/Pickra/SassyEgghead/commits/feature/iterateWithTheEachDirective)
The SCSS @for directive is great when we know how many iterations are required and we only need 1 variable.
What if we need multiple variables to iterate over data sets? Hello SCSS maps and the @each control directive!
In this lesson, we’ll check out iterating with lists and looping over data sets with maps and the @each directive.

[Write Custom Functions with the SCSS @function Directive:](https://github.com/Pickra/SassyEgghead/commits/feature/functionDirective)
SCSS provides a ton of great features, but sometimes we just want to roll our own function. We can do that too!
In this lesson, we learn how and when to use SCSS function directives.