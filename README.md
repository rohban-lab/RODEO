# RODEO
[RODEO: Robust Outlier Detection via Exposing Adaptive Out-of-Distribution Samples](https://proceedings.mlr.press/v235/mirzaei24a.html)

This repository contains the code and experimental setup for RODEO, a novel approach for robust outlier detection presented at ICML 2024. RODEO introduces an adaptive Outlier Exposure (OE) technique, combining adversarial training and synthetic outliers generated from text-to-image models. This method effectively creates "near-distribution", "diverse" and "contextually analogous" outliers, enhancing the model's performance in both clean and adversarial settings. Experiments demonstrate significant improvements in robustness over existing methods, especially against adversarial attacks.

<p align="center">
  <img src="[https://example.com/path/to/image.jpg](https://rohban-lab.github.io/rodeo/fig-samples-icml.png)" alt="Main method overview" />
</p>

## Citation
If you find this useful, please cite our paper:
```
@inproceedings{mirzaei2024rodeo,
  title={RODEO: Robust Outlier Detection via Exposing Adaptive Out-of-Distribution Samples},
  author={Mirzaei, Hossein and Jafari, Mohammad and Dehbashi, Hamid Reza and Ansari, Ali and Ghobadi, Sepehr and Hadi, Masoud and Soltani Moakhar, Arshia and Azizmalayeri, Mohammad and Soleymani Baghshah, Mahdieh and Rohban, Mohammad Hossein},
  booktitle={Proceedings of the 41st International Conference on Machine Learning (ICML)},
  year={2024}
}
```
