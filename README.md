# Sinhala-Text-Simplification-Dataset-and-Evaluation

This repository contains the data and code for the paper "SiTSE: Sinhala Text Simplification Dataset and Evaluation".

## Abstract of the Paper

Text Simplification is a task that has been minimally explored for low-resource languages. Consequently, there are only a few manually curated datasets. In this paper, we present a human curated sentence-level text simplification dataset for the Sinhala language. Our evaluation dataset contains 1,000 complex sentences and corresponding 3,000 simplified sentences produced by three different human annotators. We model the text simplification task as a zero-shot and zero resource sequence-to-sequence (seq-seq) task on the multilingual language models mT5 and mBART. We exploit auxiliary data from related seq-seq tasks and explore the possibility of using intermediate task transfer learning (ITTL). Our analysis shows that ITTL outperforms the previously proposed zero-resource methods for text simplification. Our findings also highlight the challenges in evaluating text simplification systems, and support the calls for improved metrics for measuring the quality of automated text simplification systems that would suit low-resource languages as well. 

## Citation

If you use our dataset in your research, please cite our paper:

**APA:**

Ranathunga, S., Madhusanka, R., Rathnayake, H., de Silva, L., Aluthwala, T., Peramuna, S., & Shekhar, R. (2025). SiTSE: Sinhala Text Simplification Dataset and Evaluation. ACM Trans. Asian Low-Resour. Lang. Inf. Process. doi:10.1145/3723160

**BibTeX:**
```bibtex
@article{10.1145/3723160,
author = {Ranathunga, Surangika and Madhusanka, Rumesh and Rathnayake, Himashi and de Silva, Lahiru and Aluthwala, Thamindu and Peramuna, Saman and Shekhar, Ravi},
title = {SiTSE: Sinhala Text Simplification Dataset and Evaluation},
year = {2025},
publisher = {Association for Computing Machinery},
address = {New York, NY, USA},
issn = {2375-4699},
url = {https://doi.org/10.1145/3723160},
doi = {10.1145/3723160},
journal = {ACM Trans. Asian Low-Resour. Lang. Inf. Process.},
month = mar
}
