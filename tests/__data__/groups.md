---
id: group-by
slug: /group-by
title: Schema Documentation
sidebar_position: 1
sidebar_class_name: navbar__toggle
---

This is an example of documentation with grouping by GraphQL directive using the `groupByDirective` option (see [documentation](/#about-groupbydirective)):

```json
{
  "schema": "data/schema_with_grouping.graphql",
  "rootPath": "./docs",
  "baseURL": "group-by",
  "linkRoot": "/",
  "homepage": "data/groups.md",
  "groupByDirective": {
    "directive": "doc",
    "field": "category",
    "fallback": "Common"
  }
}
```

<small><i>Generated on ##generated-date-time##.</i></small>
