#### 10. What is the difference between `<h1>` to `<h6>` tags?

##### Answer:
- Browser apply decreasing font sizes from `<h1>` to `<h6>` by default.
- Html Headings Are Titles Or Subtitles That You Want To Display On A Webpage.

| Tag    | Purpose                 | Default Size | Usage Suggestion                |
| ------ | ----------------------- | ------------ | ------------------------------- |
| `<h1>` | Most important heading       | Largest      | Once per page (main title)      |
| `<h2>` | Section heading         | Smaller      | Subsections under `<h1>`        |
| `<h3>` | Subsection heading      | Smaller      | Under `<h2>`                    |
| `<h4>` | Sub-subsection heading  | Smaller      | Under `<h3>`                    |
| `<h5>` | Minor heading           | Smaller      | Less commonly used              |
| `<h6>` | Least important heading | Smallest     | Rarely used, very minor details |

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Headers tag</title>
</head>
<body>
    <h1>Hi</h1>
    <h2>Hi</h2>
    <h3>Hi</h3>
    <h4>Hi</h4>
    <h5>Hi</h5>
    <h6>Hi</h6>
</body>
</html>
```