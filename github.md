# GitHub Flavored Markdown

* Ignore underscores, use asterixes instead
* Strikethrough style = use \~\~style\~\~
* make a checkbox list with - [x] Task List - notation
* Auto-hotlinking - detects a hyperlink by address
* Fenced codeblocks - can specify by language
* Tables syntax

---

## Asterixes

Some *basic content* is shown here, review for **accuracy**.

## Strikethrough

* Basic information
* ~~More information~~
* Final bit of info

## Checkbox list

- [ ] :+1:
- [x] Get Food
- [x] Send email
- [ ] \(Optional) Review content
- [ ] Drive home

## Auto-hotlinking

http://www.google.com

www.yahoo.com

## Fenced Codeblocks

```html
<div class="mainContent">
  <h1>Introduction</h1>
  <h2>Subtitles</h2>
  <p>Content text goes here</p>
</div>
```

```javascript
function getName(person) {
  if(person == "") {
    return "no person available"
  }
}
```

## Tables

* use dashes and pipes to make the layout
* use colon to specify alignment - left, right, center
* span cells with pipes next to each other without content

First Header | Second Header | Third Header
-------------|:-------------:|------------:
content one | content two | 23
[Google](http://www.google.com) | **content two** | 64
content one || 162
content one | content two | five