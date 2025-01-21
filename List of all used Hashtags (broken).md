#Overview 


```dataviewjs
let tags = []
for (let tag of dv.pages("C:\Users\jakob\Documents\IDONTKNOW").file.tags) {
 if (tags.indexOf(tag) == -1) {
 tags.push(tag)
 }
}
dv.list(tags)
```