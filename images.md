# Images

## Image online

###### Markdown code:

```md
![Ron F'n Swanson](https://images.inc.com/uploaded_files/image/1920x1080/parks-and-recreation_32716.jpg)
```

###### Rendered example:

![Ron F'n Swanson](https://images.inc.com/uploaded_files/image/1920x1080/parks-and-recreation_32716.jpg)

## Image with `title` attribute

###### Markdown code:

```md
![99 little bugs in the code](./img/hacking.gif 'This is my life')
```

###### Rendered example:

![99 little bugs in the code](./img/hacking.gif 'This is my life')

## Image in repo

###### Markdown code:

```md
![This is my alt text](./img/hacking.gif 'HACKING')
```

###### Rendered example:

![This is my alt text](./img/hacking.gif 'HACKING')

## Switching images based on theme

###### Markdown code:

```md
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://user-images.githubusercontent.com/25423296/163456776-7f95b81a-f1ed-45f7-b7ab-8fa810d529fa.png">
  <source media="(prefers-color-scheme: light)" srcset="https://user-images.githubusercontent.com/25423296/163456779-a8556205-d0a5-45e2-ac17-42d089e3c3f8.png">
  <img alt="Shows an illustrated sun in light mode and a moon with stars in dark mode." src="https://user-images.githubusercontent.com/25423296/163456779-a8556205-d0a5-45e2-ac17-42d089e3c3f8.png">
</picture>
```

###### Rendered example:

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://user-images.githubusercontent.com/25423296/163456776-7f95b81a-f1ed-45f7-b7ab-8fa810d529fa.png">
  <source media="(prefers-color-scheme: light)" srcset="https://user-images.githubusercontent.com/25423296/163456779-a8556205-d0a5-45e2-ac17-42d089e3c3f8.png">
  <img alt="Shows an illustrated sun in light mode and a moon with stars in dark mode." src="https://user-images.githubusercontent.com/25423296/163456779-a8556205-d0a5-45e2-ac17-42d089e3c3f8.png">
</picture>
