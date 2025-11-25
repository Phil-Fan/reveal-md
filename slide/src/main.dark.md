---
separator: <!--s-->
verticalSeparator: <!--v-->
theme: simple
highlightTheme: monokai-sublime
css: 
    - ./static/custom.css
    - ./static/dark.css
revealOptions:
    transition: 'slide'
    transitionSpeed: fast
    center: false
    slideNumber: "c/t"
    width: 1000
---

<!-- .slide: data-background="./assets/cover-01.png" -->

<!--s-->

<!-- .slide: data-background="./assets/cover-03.png" -->

<div class="middle center">
<div style="width: 100%">

# Part.1 大标题

一些 markdown

</div>
</div>

<!--v-->
<!-- .slide: data-background="./assets/cover-02.png" -->

## 标题

> test

<hr/>

```rust [1|2-3]
fn main() {
    println!("Hello World!")
}
```

...

- list 1
- list 2
  - list 2.1

1. 有序

<!--v-->
<!-- .slide: data-background="./assets/cover-02.png" -->

## 标题1

<div class="three-line">

|表头 a|表头 b|表头 c|
|:--:|:--:|:--:|
|这是一个|一些内容|...|
|三线表|...|...|

</div>

|表头 a|表头 b|表头 c|
|:--:|:--:|:--:|
|这是一个|一些内容|...|
|普通表格|...|...|

<!--s-->
<!-- .slide: data-background="./assets/cover-03.png" -->
<div class="middle center">
<div style="width: 100%">

# Part.2 布局

</div>
</div>

<!--v-->
<!-- .slide: data-background="./assets/cover-02.png" -->

## 多列布局

<div class="mul-cols">
<div class="col">

第一列

- list
- list

</div>

<div class="col">

第二列

```python
class MyClass:
    def __init__(self, ...):
        ...
    def method(self, ...):
        ...
```

</div>

</div>

<div class="mul-cols">
<div class="col">

第一列

- list
- list

</div>

<div class="col">

第二列

1. list
2. list
    - list

</div>
<div class="col">

第三列

```python
class MyClass:
    def __init__(self, ...):
        ...
    def method(self, ...):
        ...
```

</div>
</div>
