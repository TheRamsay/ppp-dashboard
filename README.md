# PPP Heat Solver — Performance Dashboard

Interactive performance dashboard for the parallel heat-equation solver benchmarked on Barbora (IT4Innovations).

**Live:** https://theramsay.github.io/ppp-dashboard/

Self-contained HTML — open `index.html` locally or via GitHub Pages. No build step, no server. Plotly/Tailwind/Alpine load from CDN.

## Contents

- 420 benchmark runs across 3 decompositions (MPI 2D, Hybrid 1D, Hybrid 2D)
- 5 grid sizes (256²–4096²), up to 256 cores
- P2P vs RMA communication, no-IO / sequential IO / parallel IO variants
- Interactive filtering, scaling / speedup / efficiency tabs, heatmaps, raw data table
