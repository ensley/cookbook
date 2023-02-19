# cookbook

![CodeBuild](https://codebuild.us-west-2.amazonaws.com/badges?uuid=eyJlbmNyeXB0ZWREYXRhIjoiN3B1MWdrMm16c1FGaXM1VXN5VEFTaTRtbmNlV0pKd1dOUTc0ZS9qZnBJalJOa1lCZTJQN3VMUi9nY2JPeHFENGpLcmRNV2RkNnB2VTBJUTVoSFFjNzhBPSIsIml2UGFyYW1ldGVyU3BlYyI6IlFBZVhVanZPc21aWEJYdjciLCJtYXRlcmlhbFNldFNlcmlhbCI6MX0%3D&branch=master)

A collection of recipes we like to make.

## Developing

### Prerequisites

Needs [Jekyll](https://jekyllrb.com/docs/) to be installed.

### Installation

```
bundle install
````

### Serving locally

```
bundle exec jekyll serve
```

### Adding a recipe

Each recipe is a Markdown file.

##### **`_recipes/example-recipe.md`**
```markdown
---
layout: recipe
title: Example Recipe
image: /assets/image/sm/example-image.jpg

servings: 4
cookmins: 20
prepmins: 30

ingredients:
  - quantity: 1
  - unit: tbsp
  - ingredient: sugar

instructions:
  - Preheat the oven.
  - Do something.

categories: dessert
cuisine: American
---
Lorem ipsum dolor sit amet.
```

### Publishing changes

Changes are automatically published on a push to the main branch. After a few minutes, view the new recipe at [cookbook.john-ensley.com](https://cookbook.john-ensley.com.).
