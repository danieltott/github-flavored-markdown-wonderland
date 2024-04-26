# Code Blocks

## Plain code block

```
ThisIsSomeFancyCode() {
  see?.it();
}
```

## Name the language

[List of all languages supported](https://github.com/github-linguist/linguist/blob/master/lib/linguist/languages.yml) - look at the `extensions` key for the code to use.

```jsx
ThisIsSomeFancyCode() {
  see?.it();
}
```

## Suggest some changes

```diff
ThisIsSomeFancyCode() {
-  see?.it();
+  dontsee?.it();
}
```

## Escape code fence inside code fence

````md
```
This is an example of a code fence
```
````
