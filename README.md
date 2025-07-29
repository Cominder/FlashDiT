
# FlashDiT

## Introduction

FlashDiT is built on the [Lightning DiT project](https://github.com/hustvl/LightningDiT). Unlike LightningDiT, FlashDiT uses the interleaved window attention from the [Iwin Transformer](https://github.com/Cominder/Iwin-Transformer) and removes the positional encoding. FlashDiT is more training faster than LightningDiT. A more powerful model will be released later.

## Train Your Own Models

Follow [detailed tutorial](docs/tutorial.md) for training your own models.

## Acknowledgements

This repo is mainly built on [LightningDiT]((https://github.com/hustvl/LightningDiT)). Thanks for the great work.


## Citation

If you find the work useful, please cite our related paper:

```
@misc{huo2025iwin,
      title={Iwin Transformer: Hierarchical Vision Transformer using Interleaved Windows}, 
      author={Simin Huo and Ning Li},
      year={2025},
      eprint={2507.18405},
      archivePrefix={arXiv},
      primaryClass={cs.CV},
      url={https://arxiv.org/abs/2507.18405}, 
}
```
