# GPT Image 2 Prompt: gLM Attention Educational Diagram

Mode note: `gpt-image-2` detected non-Garden mode in this workspace, so this prompt is saved for host-native image generation or reuse. The implemented HTML uses the same visual concept as an interactive DOM/canvas learning artifact.

## Template Basis

- `slides-and-visual-docs/educational-diagram-slide.md`
- `academic-figures/neural-network-architecture.md`

## Final Prompt

Create a 16:9 educational scientific diagram for graduate-level computational genomics learners titled "How genomic language models attend to DNA context".

Visual style:
- Clean academic web-course figure, white background, restrained ink/navy typography, muted teal, oxblood red, amber, and soft violet accents.
- Crisp vector-clean rendering, thin lines, no photorealism, no glossy 3D, no cartoon mascots, no decorative gradients.
- Korean and English mixed labels are acceptable, but keep all technical labels short and readable.

Central composition:
- A horizontal DNA sequence rail made of nucleotide tokens A/C/G/T and variable BPE/k-mer chunks.
- Above the rail, draw 4 attention heads as distinct arc families:
  1. local motif block around a TATA/SP1-like promoter motif,
  2. long-range enhancer-to-promoter bridge,
  3. splice donor/acceptor boundary links,
  4. reverse-complement consistency path.
- Next to the rail, show a compact heatmap matrix labeled "token x token attention / dependency", with brighter cells on the motif block and enhancer-promoter off-diagonal links.

Side panels:
- Tokenization panel: character tokens preserve base-level edits, k-mers overlap and can leak masked-token identity, BPE compresses sequence length but can split or preserve motifs depending on vocabulary.
- Model panel: DNABERT / Nucleotide Transformer / GROVER / Enformer use transformer attention; HyenaDNA / Caduceus use long-convolution or state-space alternatives for very long DNA.
- Interpretation caveat panel: attention is a useful lens but not causal proof; perturbation-based nucleotide dependency maps test functional coupling more directly.

Scientific constraints:
- Do not invent numeric benchmark values.
- Keep formulas minimal: show only "self-attention cost O(n^2)" and "masked token prediction".
- Make the figure feel like a paper-quality explainer, not a marketing hero image.

