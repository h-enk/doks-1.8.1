---
title: "Example Guide"
description: "Guides lead a user through a specific task they want to accomplish, often with a sequence of steps."
summary: ""
date: 2023-09-07T16:04:48+02:00
lastmod: 2023-09-07T16:04:48+02:00
draft: false
weight: 810
toc: true
seo:
  title: "" # custom title (optional)
  description: "" # custom description (recommended)
  canonical: "" # custom canonical URL (optional)
  noindex: false # false (default) or true
---

Guides lead a user through a specific task they want to accomplish, often with a sequence of steps. Writing a good guide requires thinking about what your users are trying to do.

```js
// Example: Creating a simple greeting function
function greet(name) {
  return `Hello, ${name}!`;
}

console.log(greet("World"));
// Output: Hello, World!
```

## Another Example

```js {title="count.js"}
if ([1, "one", 2, "two"].includes(value)) {
  console.log("Number is either 1 or 2."); // comment
}
```

## Yet Another Example

```bash {title="Installing dependencies…"}
npm install
```

## Line numbers

```go {linenos=true,hl_lines=[8,"15-17"],linenostart=199}
// GetTitleFunc returns a func that can be used to transform a string to
// title case.
//
// The supported styles are
//
// - "Go" (strings.Title)
// - "AP" (see https://www.apstylebook.com/)
// - "Chicago" (see https://www.chicagomanualofstyle.org/home.html)
//
// If an unknown or empty style is provided, AP style is what you get.
func GetTitleFunc(style string) func(s string) string {
  switch strings.ToLower(style) {
  case "go":
    return strings.Title
  case "chicago":
    return transform.NewTitleConverter(transform.ChicagoStyle)
  default:
    return transform.NewTitleConverter(transform.APStyle)
  }
}
```

## Further reading

- Read [about how-to guides](https://diataxis.fr/how-to-guides/) in the Diátaxis framework
