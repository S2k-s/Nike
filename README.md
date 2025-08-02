# Nike

Online store of Nike sneakers. 

From the "dev" branch, lists and a copy of the provide section were added during the merge.<br> 
And the text color and site background were also changed, but for some reason without conflict, although the main branch had other styles different from the dev branch.

main:
```css
.body {
    background: var(--general-color);
    color: var(--general-color-two);
    font-family: 'WorkSans', "Arial", sans-serif;
    line-height: 1.5;
}
```
dev:
```css
.body {
    background: var(--general-color-two);
    color: var(--general-color);
    font-family: 'WorkSans', "Arial", sans-serif;
    line-height: 1.5;
}
```


The site header background was removed.
```css
.header {
    background: url("../img/bg/header-bg.png") no-repeat;
}
```