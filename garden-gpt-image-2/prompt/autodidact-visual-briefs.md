# GPT Image 2 Visual Briefs For Autodidact Interactives

These prompts are written for public educational assets. They avoid non-public project references, vendor logos, fake data values, decorative gradients, and photorealistic lab claims that could be mistaken for real measurements.

## 1. RNA-seq DEG And Pseudobulk

```json
{
  "type": "academic method pipeline overview",
  "goal": "Create a clean graphical abstract for a student-facing interactive about RNA-seq differential expression and pseudobulk analysis.",
  "canvas": {
    "aspect_ratio": "16:9",
    "background": "pure white",
    "style": "publication-quality vector-clean schematic, thin lines, restrained color, readable in grayscale"
  },
  "layout": {
    "flow": "left to right, five equal stages connected by thin arrows",
    "stages": [
      {"label": "Raw counts", "visual": "gene by sample count matrix with small integer blocks"},
      {"label": "Normalize", "visual": "different measuring cups becoming equal-sized cups"},
      {"label": "Model variance", "visual": "negative binomial curve with wider tails than Poisson"},
      {"label": "Test condition effect", "visual": "coefficient beta with error bar"},
      {"label": "FDR-ranked DEG list", "visual": "short ranked list with green and gray marks"}
    ]
  },
  "colors": ["deep blue", "muted green", "warm amber", "charcoal"],
  "constraints": [
    "no fabricated numerical values",
    "no 3D rendering",
    "no marketing poster style",
    "short English labels only",
    "keep all text inside stage boxes"
  ]
}
```

## 2. GWAS Fine-Mapping

```json
{
  "type": "academic graphical abstract",
  "goal": "Explain how a broad GWAS association peak becomes a smaller credible set through LD, functional prior, and cross-ancestry evidence.",
  "canvas": {"aspect_ratio": "16:9", "background": "white"},
  "layout": {
    "sections": [
      {"label": "Association peak", "visual": "wide locus plot with many linked points"},
      {"label": "LD structure", "visual": "triangular LD heatmap blocks"},
      {"label": "Functional prior", "visual": "small chromatin track and enhancer mark"},
      {"label": "Credible set", "visual": "few highlighted variants with posterior bars"}
    ]
  },
  "style": "minimal, journal figure, geometric, sharp typography",
  "constraints": ["no real rsIDs", "no fabricated p-values", "no glossy effects"]
}
```

## 3. ASD Cohort Atlas

```json
{
  "type": "educational cohort map",
  "goal": "Show how ASD genomics cohorts differ by family design, phenotype depth, and genetic evidence layer.",
  "canvas": {"aspect_ratio": "16:9", "background": "white"},
  "layout": {
    "main_visual": "network-like map of cohort cards grouped into simplex families, multiplex families, population registries, clinical sequencing, and biobank meta-analysis",
    "side_panel": "stacked evidence layers: common SNP, de novo coding, CNV/SV, inherited rare, noncoding WGS, phenotype measures"
  },
  "style": "clean data atlas, muted colors, precise labels",
  "constraints": ["no patient faces", "no medical diagnosis imagery", "no private cohort identifiers beyond public cohort names"]
}
```

## 4. Organoid Research Map

```json
{
  "type": "scientific schematic",
  "goal": "Introduce organoid culture as a path from stem cell source to patterned 3D tissue model and quality-control readouts.",
  "canvas": {"aspect_ratio": "16:9", "background": "white"},
  "layout": {
    "flow": "stem cell source -> patterning cues -> 3D culture format -> assay readouts -> model limitations",
    "visuals": [
      "simple stem cell colony",
      "small cue labels WNT, BMP, SHH, FGF",
      "spheroid embedded in matrix",
      "single-cell atlas and electrophysiology icons",
      "QC checklist for identity, maturity, function, reproducibility"
    ]
  },
  "style": "journal schematic, soft but restrained colors",
  "constraints": ["no photorealistic tissue claim", "no saturated colors", "no dense paragraphs"]
}
```

## 5. Human Brain Single-Cell Atlas

```json
{
  "type": "research overview poster",
  "goal": "Show human brain single-cell studies as a coordinate system of cell type, developmental time, brain region, and regulatory genome.",
  "canvas": {"aspect_ratio": "16:9", "background": "white"},
  "layout": {
    "center": "minimal brain outline subdivided into regions",
    "axes": ["cell type", "developmental time", "brain region", "regulatory genome"],
    "surrounding_elements": "small panels for transcriptome, chromatin, spatial map, disease genetics"
  },
  "style": "clean neuroscience atlas schematic, muted blue-green-coral palette",
  "constraints": ["no MRI-looking fake scan", "no realistic human subject", "no invented numbers"]
}
```

## 6. Single-Cell Foundation Models

```json
{
  "type": "method comparison infographic",
  "goal": "Compare tokenization choices in single-cell foundation models: gene identity, expression value, and ordering.",
  "canvas": {"aspect_ratio": "16:9", "background": "white"},
  "layout": {
    "left": "single-cell count vector",
    "middle": "three design axes: gene identity, expression encoding, gene order",
    "right": "model tasks: cell embedding, perturbation prediction, annotation, imputation"
  },
  "style": "technical infographic, precise grid, no decorative background",
  "constraints": ["no model logos", "no fake leaderboard numbers", "keep labels short"]
}
```

## 7. Genomic Language Model Attention

```json
{
  "type": "technical attention schematic",
  "goal": "Explain how genomic language models attend to motifs, splice boundaries, and long-range enhancer-promoter relationships.",
  "canvas": {"aspect_ratio": "16:9", "background": "white"},
  "layout": {
    "top": "DNA sequence tokens with three tokenization granularities",
    "middle": "attention matrix with local motif block and long-range bridge",
    "bottom": "three scenarios: motif, splice site, enhancer-promoter"
  },
  "style": "clean matrix-based diagram, muted green and blue, publication figure",
  "constraints": ["no real genome coordinates", "no decorative helix background", "no fabricated model score"]
}
```

## 8. CWAS Rare Noncoding Variant Categories

```json
{
  "type": "academic method schematic",
  "goal": "Explain category-wide association testing for rare noncoding variants in whole-genome sequencing.",
  "canvas": {"aspect_ratio": "16:9", "background": "white"},
  "layout": {
    "flow": "left to right, five stages",
    "stages": [
      {"label": "WGS variants", "visual": "sparse dots along a genome line"},
      {"label": "Functional annotation", "visual": "promoter, enhancer, conserved locus, and cell-type CRE tracks"},
      {"label": "Category matrix", "visual": "small grid combining variant type, region, gene set, annotation, score"},
      {"label": "Burden test", "visual": "case and control count bars with error marks"},
      {"label": "Corrected signals", "visual": "few highlighted regulatory categories after effective-test correction"}
    ]
  },
  "style": "clean journal figure, restrained red-blue-gold palette, thin arrows, no decorative background",
  "constraints": [
    "no real patient data",
    "no fabricated p-values or rsIDs",
    "short English labels only",
    "make the multiple-testing correction visually explicit",
    "do not include lab, repository, or private dataset names"
  ]
}
```
