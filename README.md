# Python for Beginners

This is a polished Quarto book template for a beginner Python course.

## Build locally

Open this folder in Positron and run:

```bash
quarto render
```

The website will be created in:

```text
_book/
```

Open:

```text
_book/index.html
```

## Add lessons

Put new lesson files in the `lessons/` folder and add them to `_quarto.yml`.

## Add images

Put screenshots in the `images/` folder and refer to them from lessons using paths such as:

```markdown
![The Positron editor](../images/positron-editor.png)
```
