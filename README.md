# Linking multiple README -files

With this repository I'm testing how linking markdown files works, and how these are shown on GitHub.

- [Second markdown file in a root folder](another.md)
- A folder with `README.md`
  - [Pointing to the folder](folder-readme)
  - [Pointing to the README markdown file](folder-readme/README.md)
  - [Pointing to a dummy markdown file](folder-readme/dummy.md)
- Another folder without `README.md`
  - [Pointing to the folder](folder-normal)

```markdown
- [Second markdown file in a root folder](another.md)
- A folder with `README.md`
  - [Pointing to the folder](folder-readme)
  - [Pointing to the README markdown file](folder-readme/README.md)
  - [Pointing to a dummy markdown file](folder-readme/dummy.md)
- Another folder without `README.md`
  - [Pointing to the folder](folder-normal)
```