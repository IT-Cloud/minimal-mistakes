---
title:  "Windows RDP license extension - Registry method"
search: false
categories: 
  - jekyll
last_modified_at: 2018-02-19T08:06:00-05:00
---

<<<<<<< HEAD
<<<<<<< HEAD
<<<<<<< HEAD
<<<<<<< HEAD
ეს არის საცდელი პოსტი 2 34345341
=======
ეს არის საცდელი პოსტი 2233
>>>>>>> 0d6f57796363bf3d5087446cef2b7c34dc480f8f
=======
ეს არის საცდელი პოსტი
>>>>>>> parent of d7ff380... Move default posts to OLD
=======
ეს არის საცდელი პოსტი
>>>>>>> parent of d7ff380... Move default posts to OLD
=======
ეს არის საცდელი პოსტი
>>>>>>> parent of d7ff380... Move default posts to OLD

This post should not appear in the search index because it has the following YAML Front Matter:

```yaml
search: false
```

**Note:** `search: false` only works to exclude posts when using Lunr as a search provider.
{: .notice--info}

To exclude files when using Algolia as a search provider add an array to `algolia.files_to_exclude` in your `_config.yml`. For more configuration options be sure to check their [full documentation](https://community.algolia.com/jekyll-algolia/options.html).

```yaml
algolia:
  # Exclude more files from indexing
  files_to_exclude:
    - index.html
    - index.md
    - excluded-file.html
    - _posts/2017-11-28-post-exclude-search.md
    - subdirectory/*.html
```
