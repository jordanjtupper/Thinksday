[README.md](https://github.com/user-attachments/files/28360038/README.md)# Thinksday

Weekly reflections by **Nat Tupper**, published every Thursday.

A simple archive of personal essays — each one a photo, a thought, a memory, and a brief story.

> *"Why should I let fawning fidelity to facts ruin an otherwise good story?"*

---

## How it works

Each week's piece is a PDF stored in the `files/` folder. The `index.html` page lists them all chronologically with a link to read each one.

## Adding a new entry

1. Convert the .docx to PDF (File → Export as PDF in Word, or print to PDF).
2. Name the file consistently: `Title-M-D-YY.pdf` — e.g., `Beautiful-Souls-5-28-26.pdf`
3. Drop it into the `files/` folder.
4. Add a new `<li class="entry">` row in `index.html` at the top of the list, following the existing pattern.
5. Commit and push. GitHub Pages publishes automatically.

## Repo structure

```
/
├── index.html        ← the archive page
├── files/            ← PDF files, one per Thinksday
│   ├── Marcescence-3-19-26.pdf
│   ├── Dagny-4-9-26.pdf
│   └── ...
└── README.md
```

## Setting up GitHub Pages

1. Go to **Settings → Pages** in this repository.
2. Under *Source*, select **Deploy from a branch**.
3. Choose `main` branch, `/ (root)`.
4. Save. Your site will be live at `https://yourusername.github.io/thinksday/`

---

*Happy Thinksday.*
