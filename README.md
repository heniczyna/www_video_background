# [Create a Website With Video Background | HTML & CSS](https://www.youtube.com/watch?v=8MgpE2DTTKA)

# [Google Fonts](https://fonts.google.com/)

# [Code snippets]
Selector usage in SCSS files:
```
.toggle{
    .active{
    }
}
```
Sass compiler compiles it to:
```
.toggle .active {
} 
```
it refers to element with class `active` inside element with class `toggle`. Something like below:
```
<div class="toggle">
    <div class="active"></div>
</div>
```

If you use selector `&`:
```
.toggle{
    &.active{
    }
}
```
Sass compiler compiles it to:
```
.toggle.active {
} 
```
it refers to element with class `toggle active`.