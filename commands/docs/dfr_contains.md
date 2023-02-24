---
title: dfr contains
categories: |
  dataframe
version: 0.76.0
dataframe: |
  Checks if a pattern is contained in a string
usage: |
  Checks if a pattern is contained in a string
---

# <code>{{ $frontmatter.title }}</code> for dataframe

<div class='command-title'>{{ $frontmatter.dataframe }}</div>

## Signature

```> dfr contains ```

## Examples

Returns boolean indicating if pattern was found
```shell
> [abc acb acb] | dfr into-df | dfr contains ab
```