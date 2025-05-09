#### 11. How is the `<p>` tag used ?

##### Answer:
- Purpose : The `<p>` tag is used to define a paragraph of text in HTML.
- Block-Level Element: It is a block-level element, meaning it starts on a new line by default.
- Whitespace Handling: The `<p>` tag does not preserve extra whitespace (like multiple spaces or intentional line breaks). Any extra white space is generally collapsed into a single space.

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Paragraph Tag</title>
</head>
<body>
    <!-- Standard paragraph -->33
    <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Beatae molestias magnam dolor itaque, eligendi iste sed culpa debitis, quis dolorum commodi, veritatis nemo. Blanditiis praesentium vel sed est sapiente excepturi!</p>
    <!-- `<p>` tag does not preserve extra whitespace , Any extra white space is generally collapsed into a single space.-->
    <p>Lorem         ipsum dolor sit amet consectetur adipisicing elit. Beatae molestias magnam dolor itaque, eligendi iste sed culpa debitis, quis dolorum commodi, veritatis nemo. Blanditiis praesentium vel sed est sapiente excepturi!</p>  
</body>
</html>
```