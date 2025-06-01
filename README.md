# Δ(structure): Problem Geometry and the XOR Puzzle

This repository explores the divergence between cognitive topography and verifier-induced structure in tractable problems—a concept we call **Δ(structure)**.

Our canonical example: a 3x3 binary grid governed by overlapping 2x2 XOR constraints. Despite being solvable via linear algebra, naive bit-flip heuristics yield a maximally fragmented solution space in Hamming geometry.

## 🔍 What’s Inside

- `xor_puzzle.py`: Generates valid 3x3 XOR grids and checks verifier constraints.
- `visualize_hamming_graph.py`: Visualizes the solution space’s fragmentation in Hamming space.
- `delta_tools.py`: (Coming Soon) Tools for scoring and visualizing Δ(structure).
- `notebooks/`: Jupyter notebooks for experiments, metrics, and solver comparisons.

## 💡 Key Concepts

- **Verifier Geometry**: The hidden structure imposed by a problem’s constraints.
- **Cognitive Topography**: The solver’s perceived landscape (e.g., bit-flip adjacency).
- **Δ(structure)**: The divergence between the two—high Δ correlates with high perceived difficulty.

## 🧠 Why It Matters

Even in low-complexity problems, naive solvers can fail due to misaligned geometry. Understanding Δ(structure) helps us design better puzzles, hint systems, interpretable AI, and insight-driven curricula.

## 🚧 Coming Soon

- Δ puzzle generator templates
- Δ metrics for solvers
- Insight-triggering scaffold design tools
- Formal write-up and arXiv preprint

## 🧪 Citation

If you use this work, please cite the forthcoming paper:
> Law, S. (2025). *Toward a Unified Theory of Problem Geometry*.

## 📜 License

MIT License

---

*Built with nerd-fueled geometric rage.*