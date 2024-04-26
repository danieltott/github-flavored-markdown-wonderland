# Code Blocks

## Plain code block

###### Rendered example:

```
ThisIsSomeFancyCode() {
  see?.it();
}
```

###### Markdown code:

````md
```
ThisIsSomeFancyCode() {
  see?.it();
}
```
````

## Name the language

[List of all languages supported](https://github.com/github-linguist/linguist/blob/master/lib/linguist/languages.yml) - look at the `extensions` key for the code to use.

###### Rendered example:

```jsx
ThisIsSomeFancyCode() {
  see?.it();
}
```

###### Markdown code:

````md
```jsx
ThisIsSomeFancyCode() {
  see?.it();
}
```
````

## Suggest some changes

###### Rendered example:

```diff
ThisIsSomeFancyCode() {
-  see?.it();
+  dontsee?.it();
}
```

###### Markdown code:

````md
```diff
ThisIsSomeFancyCode() {
-  see?.it();
+  dontsee?.it();
}
```
````

## Escape code fence inside code fence

###### Rendered example:

````md
```
This is an example of a code fence
```
````

###### Markdown code:

`````md
````md
```
This is an example of a code fence
```
````
`````
