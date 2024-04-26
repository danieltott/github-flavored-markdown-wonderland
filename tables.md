# Tables

## You can create a table in markdown

###### Rendered example:

| Command      | Description                                    |
| ------------ | ---------------------------------------------- |
| `git status` | List all new or modified files                 |
| `git diff`   | Show file differences that haven't been staged |

###### Markdown code:

```md
| Command      | Description                                    |
| ------------ | ---------------------------------------------- |
| `git status` | List all new or modified files                 |
| `git diff`   | Show file differences that haven't been staged |
```

## You can also use html

###### Rendered example:

<table>
  <thead>
    <tr>
      <th scope="col">Command</th>
      <th scope="col">Description</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th scope="row"><code>git status</code></th>
      <td>List all new or modified files</td>
    </tr>
    <tr>
      <th scope="row"><code>git diff</code></th>
      <td>Show file differences that haven't been staged</td>
    </tr>
  </tbody>
</table>

###### Markdown code:

```md
<table>
  <thead>
    <tr>
      <th scope="col">Command</th>
      <th scope="col">Description</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th scope="row"><code>git status</code></th>
      <td>List all new or modified files</td>
    </tr>
    <tr>
      <th scope="row"><code>git diff</code></th>
      <td>Show file differences that haven't been staged</td>
    </tr>
  </tbody>
</table>
```
