<!-- TITLE: Seq 1 P 1 -->
<!-- SUBTITLE: The first page in a multipage sequence -->

# Page editing
## How do I format paragraphs?
I assume all the markdown tricks work
Here is a list:
* item one
* Item 2
* 3

a numbered list?
1. foo
2. bar
3. bas

a todo list?
- [x] first
- [ ] second

Interestingly, the editor has the notion of continuing items in the same kind of list.
I wonder whether there are other tricks, e.g for definition lists?

term
: definition one

other term
:  another definition.

## Code highlights

```json
{
  name: "wiki",
  "version": "1.0.117",
  "description": "A modern, lightweight and powerful wiki app built on NodeJS, Git and Markdown",
  "main": "wiki.js",
  "scripts": {
    "start": "node wiki start",
    "stop": "node wiki stop",
    "restart": "node wiki restart",
    "build": "node tools/fuse",
    "dev": "node tools/fuse -d",
    "dev-configure": "node tools/fuse -c",
    "test": "jest",
    "postinstall": "opencollective postinstall"
  }
} 
```

```js
router.get('/', (req, res) => {
  res.redirect('/admin/profile')
})

router.get('/profile', (req, res) => {
  if (res.locals.isGuest) {
    return res.render('error-forbidden')
  }

```
	
## How do I structure sections on the same page
