---
id: 1
slug: demo-file-abc123
title: Demo File
date: 2026-01-27T10:30:00
---

This is the content for the demo file.

### Does this work correctly?

1. Yes?
2. No?

```js
import { createFileRoute } from '@tanstack/react-router'

export const Route = createFileRoute('/blogs/$slug')({
  component: RouteComponent,
  loader: async ({ params }) => {
    return fetchBlog(params.slug)
  },
})
```
