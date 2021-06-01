# Best Practices
{markdown: ./breadcrumb.md}

### Family Search

#### Workflow - PR comments

1. If the list is empty we need to return a ```HttpStatus.NO_CONTENT``` (not a ```HttpStatus.NOT_FOUND```)... 404s are 
   too generic (mistyping a path for instance)
2. Also, if we return an ```HttpStatus.NO_CONTENT```, we should leave off the body (return new 
   ```ResponseEntity<>(HttpStatus.NO_CONTENT)```, not return an empty list in the body
3. Is the events == null needed? We've already handled that in the DBA
4. Use ```StringUtils.hasText()``` - from SpringFramework, but not in a model class as will be bringing in too much unneeded 
   code into the model.

### Links
