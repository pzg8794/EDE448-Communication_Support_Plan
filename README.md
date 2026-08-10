# EDE 448 Communication Support Plan

This repository contains the editable, review-ready Module 3 paper **Communication That Travels With the Student: A Neurodiversity-Affirming, Culturally and Health Responsive Support Plan**.

## Status

- Review-ready draft
- Not submitted to Blackboard
- `main.tex` is the single LaTeX source of truth for GitHub and Overleaf
- The local review PDF compiles to nine pages; generated build files remain ignored

## Review Order

1. `main.tex` - formatted submission paper
2. `draft.md` - accessible content mirror
3. `references.bib` - course readings, prior EDE 448 work, and de-identified practice sources

## Evidence Design

Mateo, Eli, and Luca are fictional pooled composites. No profile is a disguised biography or a one-to-one stand-in for a child. All three may draw from the same de-identified bank of camp and teaching-placement strategies when the access condition fits.

The showcase analysis separates its evidence types. Camp records document data organized by day and activity and youth use of the trifold, photographs, model, samples, and tools. The de-identified practitioner reflection contributes the sequence of adult-partner actions and the instructional interpretation. A completed home-school record then simulates how those conditions and supports could inform Mateo's plan; it is explicitly not an observed child's record or verbatim student/family language. The paper does not infer motive, assign a diagnosis to an observed learner, or claim that an observed child used AAC.

## Build

```bash
latexmk -pdf main.tex
```

The public course package and assignment navigation remain in [pzg8794/EDE448](https://github.com/pzg8794/EDE448). The dedicated repository contains only the paper package needed for GitHub/Overleaf review.
