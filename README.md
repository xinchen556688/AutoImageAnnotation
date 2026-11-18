# AutoImageAnnotation

**Turn any image into a museum-style wall label, alt text and caption — in seconds.**

Upload a photo of an object, an archival scan, or a museum piece and get a structured,
gallery-grade description you can publish as-is. Built for galleries, accessibility,
image SEO and AI search.

🌐 **[autoimageannotation.com](https://www.autoimageannotation.com/)**

---

## What it does

One upload produces four artifacts from the same analysis:

| Output | What you get | Where it's used |
|---|---|---|
| **Wall label** | Museum placard text — title, date, medium, dimensions, interpretive line | Exhibitions, catalogues, kiosks |
| **Description** | 40–300 word prose description of the image | CMS, product pages, archives |
| **Alt text** | Concise, screen-reader-ready description | Accessibility (WCAG), image SEO |
| **Caption** | Short social-ready copy | Social posts, newsletters |

Because all four come from one pass, they stay consistent — the alt text and the wall
label describe the same details, not two different readings of the same photo.

---

## Why it exists

Writing image descriptions is a bottleneck that most teams solve by **not** doing it.
The result is a catalogue that is invisible to screen readers, unindexed by image
search, and unquotable by AI answer engines.

The three failure modes we kept seeing:

- **Blank alt attributes.** Bulk-uploaded assets ship with `alt=""`, which is valid
  HTML but tells assistive tech to skip the image entirely.
- **Descriptions written for humans, not for retrieval.** "Beautiful sunset over the
  harbour" is lovely and completely unsearchable.
- **Label drift.** Twenty people write twenty different descriptions of the same
  collection, and none of them match.

AutoImageAnnotation is built around a fixed annotation schema
(identify → date and place → medium and dimensions → one interpretive line), so output
stays consistent no matter who runs it or how large the batch is.

---

## Eight scene styles

Different exhibition contexts need different registers. The same object gets a
different label in a natural-history hall than in a contemporary gallery:

```
General · Museum · Gallery · Archive · Natural history
Product · Portrait · Documentary
```

Each style changes vocabulary, sentence length and what gets emphasised — not just
the tone of voice.

---

## How it works

```
1. Upload an image (or a batch — "image packs")
2. Pick a scene style
3. Review the generated wall label, description, alt text and caption
4. Edit anything that needs a human eye
5. Publish — copy, export, or push to your CMS
```

Bilingual output (English / 中文) is available for the same image.

---

## When to use it

- **Museums and galleries** — catalogue objects faster than a registrar can type
- **E-commerce** — product images that are findable in image search
- **Archives and libraries** — legacy scans that have no metadata at all
- **Accessibility remediation** — clearing a backlog of empty `alt` attributes
- **Publishers** — captions that match the house style every time

---

## Further reading

- **[How to write a museum wall label: a practical guide](https://www.autoimageannotation.com/services/wall-label)** —
  the four-step method, a spec table, and worked examples across four media types
- **[AutoImageAnnotation on Dev.to](https://dev.to/achilles556688/how-to-write-a-museum-wall-label-a-practical-guide-18pk)** —
  the same guide with a developer-facing framing

---

## Notes

This repository is the project's public presence. The application itself runs at
[autoimageannotation.com](https://www.autoimageannotation.com/).
Issues and questions are welcome here.
