- `render(x)` seems like a bigass hijack of the word
- FunctionalCollections dependency
- Allowing Context creation to wait on JS dependency loading makes:
  - Context creation async
  - And by extension node creation async
  - context.dom no longer can be a DOM node
  - it will be a tree of promises