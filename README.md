# CSS-Patterns 
How CSS-patterns wil help you master CSS and become a better front-end developer for yourself and to others. 

This document uses methologies such as BEM, OOCSS, ITCSS, SMACSS and personal notes.

## The problems to solve
There is a big list with issues to overcome when you work with unstructured and plain CSS. They can be brought back in two groups:

- Writing errorless and efficient code
- Working with multiple people / teams on the same CSS / SASS codebase

## Writing errorless and efficient code
### How to avoid nesting of CSS to improve readability and code debugging? 
To much nesting of CSS code makes it very hard to overwrite code. The trick is to avoid overwriting code at first place by bringing CSS nesting back to a minimum.

- Use ITCSS as methology to write less code and centralize your code as much as possible. ITCSS brings a perfect structure based on ATOMIC design principles. 

Techniques which can be used to solve this problem:[BEM] [SMACSS] [ITCSS]

### How to use multiple modules besides and inside each other without affecting each other? 
### How to write code in a Cascading order to have the result we wish?
### How to avoid multiple styles being used on one single element? 
### How to re-use modules on different locations?
### How to avoid slow rendered CSS code?
### How to simplify code and facilitate refactoring and upscaling of the project so you can continue add new features?
### How to understand and write good code in essence
### Inefficient code writing makes it hard to understand code
### Re-use of CSS code is most of the time very hard to accomplish. Causing developers to rewrite modules which are already written in essence.
### How to extend features / modules which are already made

### Practical tips
- Avoid styling on elements such as H1, H2, H3 in combination with classes. This avoids a mess of cascading styles not knowing what the result could be. 
- Avoid the use of the `!important` tag. The reason you needed it at first place means that your code is probably unstable at some point. Best practise is to solve the problem at is core by applying all tips above. Most of the time you only need `!important` for making changes in external libraries or for utility classes where you know the result should be absolute and it main purpose was to overwrite all code. 
- Avoid the use of `display: hidden;` to fix anything. Only use `display: hidden` when you have a real good reason. Such as hide a part of an image when using border-radius on a parent element . 

## Working with multiple people / teams on the same CSS / SASS codebase
Most of the time it is hard to understand choices made by other developers. Instead of rewriting the code, the time it takes to understand the code should be brought back to a minimum. Theirfor you should write your code in a similar way. 

### How to write sharable code which is understood by other developers
### Different ways of thinking and problem solving
### Not knowing where to search for files / classes
### The lack of strict naming conventions

- Classname should match the filename. This way you can always find back the correspondending file. 
- When writing OOCSS classes use classnames correspondending to it's vanilla working. Such `position-absolute` or `display-sticky`. 

### How to make self sustaining / explaining documentation? 
[BEM] [SMACSS] [ITCSS]

Most of the times CSS is bad to understand by itself and the reasons why we make choices. This is the reason CSS should be written in such way it is self-sustaining and self-explaining. This can be done in several ways:

- Use BEM notation for components. This way you know what a certain parts of the component does. 
- Use a logic file structure and methology such as SMACSS or ITCSS. When you have a SASS project I recommmend ITCSS since this fits better. 
