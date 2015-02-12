# Web Build?


---

# (MY) Story of web app build

----

# Nobuild

----

# Custom build

----

# Ant

----

# Sencha Build

---


## LESS <!-- .element: style="display:inline-block;font-size:4em"-->
* requests  <!-- .element: class="fragment roll-in"-->
* data <!-- .element: class="fragment roll-in"-->


----

# Concatenation <!-- .element: class="fragment roll-in"-->
# Minification <!-- .element: class="fragment roll-in"-->

---


# HTML <!-- .element: class="fragment " style="display:inline-block;font-size:4em"-->&nbsp;
# CSS <!-- .element: class="fragment " style="display:inline-block;font-size:4em"-->&nbsp;&nbsp;
# JS <!-- .element: class="fragment " style="display:inline-block;font-size:4em"-->

----

# JavaScript

----



## Minify

- whitespaces
```
\t \r \n
```
- semicolons
- remove dead and unused code

----

## Optimize
- shorten definition using literals
``` 
    var a = new Array(); → var a=[]
```
-  optimize property access
``` 
    a["foo"] → a.foo
```
- evaluate constant expressions
```
var hun = 10*10 → var hun = 100 
```

----

## Optimize 2

- join join consecutive statemets
```
var x;var y; → var x,y
```

- optimize boolean operations
```
var x = false; → var x=!0
```
- optimize conditions

```
if (this.group) {
    this.group.remove();
} → this.group&&this.group.remove(); 
```

----

## Mangle 

```
function on(eventName, fn) {
    this._el.addEventListener(eventName, fn);
};

function on(n,e){this._el.addEventListener(n,e)}
```

----


# Uglify tricks
* remove useles white spaces
* optimalizations


---

# Into

- stats 
- lint

----

# NodeJS

* Grunt
* Gulp
* Broccoli

---

# Grunt

----

## Grunt
* json config

---

# Gulp

----

## Gulp

* pipeline

---

# Broccoli

----

# Broccoli

* all in memory
