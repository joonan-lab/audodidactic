# GPT Image 2 Prompt: GWAS Fine-Mapping Graphical Abstract

Mode note: `gpt-image-2` detected non-Garden mode in this workspace, so this prompt is saved for host-native image generation or reuse. The implemented HTML uses the same visual concept as an interactive canvas/web learning artifact.

## Template Basis

- `academic-figures/graphical-abstract.md`
- `academic-figures/method-pipeline-overview.md`

## Final Prompt

Create a 16:9 publication-quality scientific graphical abstract titled "GWAS Fine-Mapping: from association peak to experimental priority".

Visual style:
- Clean academic figure, paper-white background, crisp vector-clean rendering, thin graphite lines, restrained genomic blue, annotation green, oxblood red, ancestry amber, and muted violet accents.
- Sophisticated computational genetics visual language; it should look like a high-end Nature Genetics / Methods explainer figure, not a marketing poster.
- No photorealism, no glossy 3D, no decorative gradient blobs, no cartoon characters, no fake logos, no invented numeric benchmark values.
- Text labels must be short and readable; English labels preferred for image generation.

Central composition:
- A horizontal genomic locus rail running left to right, with small SNP markers of varying height showing association strength.
- Several SNPs are connected by soft LD arcs above the rail; high-LD arcs cluster together, while cross-ancestry recombination breaks some proxy links.
- One lead SNP is marked in oxblood as "lead SNP"; a different functional candidate is marked in green as "top PIP".
- A translucent 95% credible set band surrounds several candidate SNPs.
- Bubble sizes encode PIP, but without a numeric legend beyond "PIP".

Four surrounding panels:
1. "GWAS peak" — a small Manhattan-like local peak with many correlated variants.
2. "LD matrix" — a compact triangular heatmap, darker near the diagonal.
3. "Bayesian posterior" — candidate bubbles shrink into a 95% credible set.
4. "Functional validation" — enhancer / eQTL / MPRA / CRISPR labels flowing toward experimental priority.

Pipeline labels:
- GWAS summary statistics
- ancestry-matched LD
- multi-signal model
- PIP + credible set
- functional prior
- colocalization
- assay validation

Constraints:
- Do not fabricate exact P-values, sample sizes, percentages, or performance metrics.
- Keep all arrows and callouts aligned; no overlapping labels.
- Keep the figure readable in grayscale print.
- Use only a small set of short labels, no paragraphs.
- Final mood: elegant, precise, quiet, research-grade.
