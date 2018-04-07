# Git Markdown Training

a training for github flavored markdown

## Basic Elements

# \# Header 1
## \#\# Header 2
### \#\#\# Header 3
#### \#\#\#\#\# Header 4
##### \#\#\#\#\#\# Header 5
###### \#\#\#\#\#\#\# Header 6

### Text

` **bold**` **bold**

` _italic_ ` _italic_

### Link

` [link](README.md) ` [link](README.md)

### Image

```
![](img.jpg)
```

![](img.jpg)

```
![](img.jpg)

*caption*
```

![](img.jpg)

*caption*

#### using table for caption display.

```
|![](img.jpg)|
|:---:|
|*caption*|
```

|![](img.jpg)|
|:---:|
|*caption*|

### Lists

```
* unordered list 1
  * unordered sublist 1
  * unordered sublist 2
  * unordered sublist 3
* unordered list 2
* unordered list 3
```

* unordered list 1
  * unordered sublist 1
  * unordered sublist 2
  * unordered sublist 3
* unordered list 2
* unordered list 3

```
1. ordered list 1
1. ordered list 2
1. ordered list 3
```

1. ordered list 1
1. ordered list 2
1. ordered list 3

### Quotes

```
> This is a quote
> \- zeddit
```

> This is a quote
> \- zeddit

### Codes

```
In line codes: `print "zeddit"`
```

In line codes: `print "zeddit"`

block codes:(using indentation for escaping three backticks in code block)

    ```typing language for highlight use
    #This is code block;
    print "zeddit"
    ```

block codes:
```python
#This is code block;
print "zeddit"
```

## Additional Elements

### Task Lists

```
- [x] task completed 1
- [x] task completed 2
- [ ] task 1
- [ ] task 2
```

- [x] task completed 1
- [x] task completed 2
- [ ] task 1
- [ ] task 2

### Tables

```
Header 1 | Header 2 | Header 3
:--- | :---: | ---:
left aligned | center aligned | right aligned 
```
at least three hyphens needed to divide headers and contents.

Header 1 | Header 2 | Header 3
:--- | :---: | ---:
left aligned | center aligned | right aligned 

### Table of Content

Using github's automatically generated section links, e.g. \#Tables to create ToC.

```
* [Tables](#tables)
* [Task lists](#task-lists)
* [Basic Elements](#basic-elements)
```

* [Tables](#tables)
* [Task lists](#task-lists)
* [Basic Elements](#basic-elements)

## Extented Elements 

### Latex Supported 

```
![](http://latex.codecogs.com/gif.latex?\\e^{ix}=cosx+isinx)
```
Notice! Escaping back slash by `\\`

![](http://latex.codecogs.com/gif.latex?\\e^{ix}=cosx+isinx)

### some UMLs

TODO:

