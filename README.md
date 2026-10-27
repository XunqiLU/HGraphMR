# Heterogeneous Graph Neural Network for Mathematical Reasoning

> 📅 **Project Note:** This project was developed and completed in **Jan. 2024** as part of our research work. It is open-sourced here now for archival and reference purposes.

This repository contains the implementation of our heterogeneous graph-based reasoning model, which extends and enhances **GraphMR** (EMNLP 2021).

## Key Contributions & Highlights

- **Heterogeneous Graph Modeling:** Enhanced the original GraphMR framework by introducing heterogeneous graph structures, effectively addressing the limitations of homogeneous node representations in semantic discrimination.
- **Advanced Architecture:** Developed a robust mathematical reasoning model leveraging a Relational Graph Convolutional Network (**R-GCN**) encoder and a **Transformer** decoder.
- **Superior Performance:** Achieved state-of-the-art results on challenging symbolic expression tasks at the time, including **99.7% accuracy on POLY1** and **92.9% accuracy on MBA**.

---

## Environment & Dependencies (Legacy)

*Note: This repository preserves the original stable environment used during development in 2024.*

- `torch == 1.7.1`
- `torchtext == 0.8.1`
- `torch-geometric == 1.6.3`

---

## Acknowledgment & Citation

This work builds upon and extends the following research. If you find this repository helpful, please cite the original GraphMR paper:

```bibtex
@inproceedings{feng-etal-2021-graphmr,
  title={GraphMR: Graph Neural Network for Mathematical Reasoning},
  author={Feng, W. and Liu, B. and Xu, D. and Zheng, Q. and Xu, Y.},
  booktitle={Proceedings of the 2021 Conference on Empirical Methods in Natural Language Processing},
  pages={3395--3404},
  year={2021}
}
```
