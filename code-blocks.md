# Code Blocks

## Plain code block

###### Markdown code:

````md
```
ThisIsSomeFancyCode() {
  see?.it();
}
```
````

###### Rendered example:

```
ThisIsSomeFancyCode() {
  see?.it();
}
```

## Name the language

[List of all languages supported](https://github.com/github-linguist/linguist/blob/master/lib/linguist/languages.yml) - look at the `extensions` key for the code to use.

###### Markdown code:

````md
```jsx
ThisIsSomeFancyCode() {
  see?.it();
}
```
````

###### Rendered example:

```jsx
ThisIsSomeFancyCode() {
  see?.it();
}
```

## Suggest some changes

###### Markdown code:

````md
```diff
ThisIsSomeFancyCode() {
-  see?.it();
+  dontsee?.it();
}
```
````

###### Rendered example:

```diff
ThisIsSomeFancyCode() {
-  see?.it();
+  dontsee?.it();
}
```

## Escape code fence inside code fence

###### Markdown code:

`````md
````md
```
This is an example of a code fence
```
````
`````

###### Rendered example:

````md
```
This is an example of a code fence
```
````
