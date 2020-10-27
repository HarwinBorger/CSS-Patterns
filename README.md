# CSS-Patterns
BEM, OOCSS, ITCSS and More

## The problems to solve
There is a big list with issues to overcome when you work with unstructured and plain CSS. The biggest problems to solve are:

- Writing errorless and efficient code
- Working with multiple people / teams on the same CSS / SASS codebase

## Writing errorless and efficient code
### How to avoid nesting of CSS to improve readability and code debugging? 
To much nesting of CSS code makes it very hard to overwrite code. The trick is to avoid overwriting code at first place by bringing CSS nesting to a minimum.

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

## Working with multiple people / teams on the same CSS / SASS codebase
### How to write sharable code which is understood by other developers
### Different ways of thinking and problem solving
### Not knowing where to search for files / classes
### The lack of strict naming conventions
### How to make self sustaining / explaining documentation? 
[BEM] [SMACSS] [ITCSS]

Most of the times CSS is bad to understand by itself and the reasons why we make choices. This is the reason CSS should be written in such way it is self-sustaining and self-explaining. This can be done in several ways:

- Use BEM notation for components. 
- Classname should match the filename. This way you can always find back the correspondending file. 
- Use a logic file structure and methology such as SMACSS or ITCSS. When you have a SASS project I recommmend ITCSS since this fits better. 
