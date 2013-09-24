Stylper
=============

Stylus Helper is a small helper for your Stylus files that would make your life a little easier.

### How did it happen?

Well, I was working on a front-end project and I've made this file. After that, I started another project and I realized that I missed this file. That's it. So i decided to make a bower component that would be easy to install.

# What is in there?

### `vendor`

Input

```stylus
vendor(opacity, 0.2)
```

Output

```css
-webkit-opacity: 0.2;
-moz-opacity: 0.2;
-ms-opacity: 0.2;
-o-opacity: 0.2;
opacity: 0.2;
```

### `absolute`, `fixed`

Input:

```stylus
absoulte: top 5px left 20% bottom
```

Output:
```css
position: absolute;
top: 5px;
left: 20%;
bottom: 0;
```

### `bg`

Input

```stylus
bg: white .3
...
bg: red
```

Output

```css
background-color: rgba(255,255,255,0.30);
...
background-color: #f00;
```

### `bgg`

Usage is simple: `bgg: [vert | hor | rag] [colorFrom] [position] [colorTo] [position]`

### `dims`

Input

```stylus
dims: 30px 10%
```

Output

```css
width: 30px;
height: 10%;
```

### `pos`

Input

```stylus
pos: 20px 100px
```

Output

```css
top: 2px;
left: 1px;
```

### `touchless`

Prevent selection of text or images.

### `scrollable`

Adds scroll to element