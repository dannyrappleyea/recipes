---
tags: a/repo
url: https://github.com/dannyrappleyea/recipes
---
in:: [[topics]]
near:: [[cooking]]

# Notes

A start at a recipe collection


```dataview
LIST FROM -"_templates"
WHERE contains(topic, this.file.name)
SORT file.name
```
