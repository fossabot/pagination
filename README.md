# Neumorphism_Pagination
[![FOSSA Status](https://app.fossa.com/api/projects/git%2Bgithub.com%2FSri-hari%2Fpagination.svg?type=shield)](https://app.fossa.com/projects/git%2Bgithub.com%2FSri-hari%2Fpagination?ref=badge_shield)


# Installation :

1. Copy the neumorph_pagination folder in your repo.
2. Add neumorphism as a dependency in your package.json file.

```json
{
  "dependencies": {
    "neumorphism": "file:../neumorph_pagination"
  }
}
```

# Note :

Add this css snippet when passing input or button through slot .

```css
button, input{
    width: 100%;
    height: 100%;
    background-color:transparent;
    text-color: black;
}
```

# Pagination

<img src="sample_images/pagination.png" width="" height="">

Import:
```html
<element name='neupagination' src='../../../../../../node_modules/neumorphism/pagination/pagination.hml'></element>
```

Usage:
```html
<neupagination color="" width="300px" height="50px" border="50px"  @previous-event="previousEvent" @next-event="nextEvent">
  <button>1</button>
  <button>2</button>
  <button>3</button>
  <button>4</button>
  <button>5</button>
</neupagination>
```

# Reference:

<a href="https://neumorphism.io/">neumorphism.io</a>

<a href="https://ismail9k.github.io/neomorphism/">ismail9k.github.io/neomorphism</a>

## License
[![FOSSA Status](https://app.fossa.com/api/projects/git%2Bgithub.com%2FSri-hari%2Fpagination.svg?type=large)](https://app.fossa.com/projects/git%2Bgithub.com%2FSri-hari%2Fpagination?ref=badge_large)