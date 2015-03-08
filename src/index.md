---
{
  "template": "index.html",
  "title": "My Page Title",
  "lists": [
    "oh",
    "yeah"
  ],
  "sections":[
    {
      "title": "secition 1",
      "description": "sec1 sec1 sec1"
    },
    {
      "title": "secition 2",
       "description": "sec2 sec2 sec"
    }
  ]
}
---
# {{title}}

{{#each sections}}
## {{this.title}}
{{this.description}}
{{/each}}

{{#each lists}}
* {{this}}
{{/each}}