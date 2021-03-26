# GLR-methodology
## css methodology based on some studies and application models that i did recently.
The GLR (Global and Local Rules), is a methodology for developing CSS, its goal is to help keep the code as clean as possible. Its use is very simple, the first step is to write our global selectors that have repeated declarations in several selectors. After writing the global selectors, we move on to the local characteristics, these local selectors will have isolated declarations, that is, they are not repeated in other places. Below is an example of use.

```css
/*Global Rules*/
h2, p{
  font-family: arial;
}
/*Local Rules*/
h2{
  font-size: 4.8vw;
}
p{
  font-size: 2vw;
}

```
