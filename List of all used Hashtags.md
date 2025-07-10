#Overview 


```dataviewjs
let tags = [];
for (let page of dv.pages('"Studium"')) {
  if (page.file && page.file.tags) {
    for (let tag of page.file.tags) {
      if (!tags.includes(tag)) {
        tags.push(tag);
      }
    }
  }
}
dv.paragraph(`Found ${tags.length} tags`); dv.list(tags);
```