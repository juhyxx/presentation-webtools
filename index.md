# Build?


---

# (MY) Story of web app build

* nobuild
* custom build
    - PHP parser
* Ant
* Sencha Build

---

## AIM

* Less requests onload <!-- .element: class="fragment roll-in"-->
* Less data on load <!-- .element: class="fragment roll-in"-->
* Handling of source caching <!-- .element: class="fragment roll-in"-->

---

# Solution

* Concat (Less requests onload)
* Minify (Less data on load)

---

# Playground

* HTML
* CSS
* JavaScript

---

# HTML

----

## HTML minify
* remove useles white spaces <!-- .element: class="fragment roll-in"-->
* extract list of linked file - useminPrepare <!-- .element: class="fragment roll-in"-->
* convert HTML templates to JavaScript <!-- .element: class="fragment roll-in"-->

----

## HTML concat

* merge templates

---

# CSS

----

## CSS minify
* remove whitespaces

----

## CSS concat
- SASS, LESS

---

# JavaScript

----

## JavaScript minify

----

## Javascript concat

---

# Uglify tricks
* remove useles white spaces
* optimalizations ?


---

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
