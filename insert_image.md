# How to Insert an Image in Markdown

Use this basic syntax:

```markdown
![alt text](path/to/image.png)
```

---

## How to Write the Image Path

### Case 1: Image and `.md` file are in the same folder

```text
project/
├── README.md
└── cat.png
```

```markdown
![A cute cat](cat.png)
```

---

### Case 2: Image is in a subfolder (most common)

```text
project/
├── README.md
└── images/
    └── cat.png
```

```markdown
![A cute cat](images/cat.png)
```

---

### Case 3: Image is in a parent folder

```text
project/
├── cat.png
└── docs/
    └── README.md
```

```markdown
![A cute cat](../cat.png)
```

---

## Example: Cat Image in This Project

```markdown
![A small cat](images/cat.jpg)
```

![A small cat](images/cat.jpg)
