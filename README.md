# Dodd.Css

**Css for the background color of "Dodd"**

## :pushpin: Document

### Class name

`dodd` (Default), `dodd-saturate` (Saturate Color), `dodd-lighten` (Light Color), `dodd-desaturate` (Desaturate Color), `dodd-darken` (Dark Color)

## :pushpin: Usage 

### CSS

* _base.scss + _variables.scss + other required scss files.

 - When using all classes, all scss files are necessary.

* There are also *min.css* files with all the classes set.

```
<link rel="stylesheet" href="path/min.css">
```

* Please give the element a **class name**.

#### Default color example

```
<div class="dodd"></div>
```

### Use jQuery together

* To use jQuery you need "**[jQuery](https://jquery.com/) file**".

```
<script src="path/jquery-3.2.1.min.js"></script>
```
 
* Please give the element a **class name**.

#### Default color example

```
<script>
        $('element').addClass('.dodd');
</script>
```

## :clock3: Update History

* [Change log](https://github.com/hana-mignon/Dodd.Css/commits/master)

## License

:heavy_exclamation_mark: [MIT License](https://github.com/hana-mignon/Dodd.Css/blob/master/LICENSE)
