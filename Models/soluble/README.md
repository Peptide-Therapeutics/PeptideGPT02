---
license: apache-2.0
base_model: nferruz/ProtGPT2
tags:
- generated_from_trainer
metrics:
- accuracy
model-index:
- name: output_sol_3
  results: []
---

<!-- This model card has been generated automatically according to the information the Trainer had access to. You
should probably proofread and complete it, then remove this comment. -->

# output_sol_3

This model is a fine-tuned version of [nferruz/ProtGPT2](https://huggingface.co/nferruz/ProtGPT2) on an unknown dataset.
It achieves the following results on the evaluation set:
- Loss: 5.6849
- Accuracy: 0.2249

## Model description

More information needed

## Intended uses & limitations

More information needed

## Training and evaluation data

More information needed

## Training procedure

### Training hyperparameters

The following hyperparameters were used during training:
- learning_rate: 1e-06
- train_batch_size: 1
- eval_batch_size: 8
- seed: 42
- optimizer: Adam with betas=(0.9,0.999) and epsilon=1e-08
- lr_scheduler_type: linear
- num_epochs: 50.0

### Training results

| Training Loss | Epoch | Step  | Validation Loss | Accuracy |
|:-------------:|:-----:|:-----:|:---------------:|:--------:|
| 6.7291        | 1.0   | 387   | 6.4419          | 0.1754   |
| 6.5666        | 2.0   | 774   | 6.2737          | 0.1847   |
| 6.4479        | 3.0   | 1161  | 6.1396          | 0.1918   |
| 6.3439        | 4.0   | 1548  | 6.0359          | 0.1974   |
| 6.2577        | 5.0   | 1935  | 5.9318          | 0.2031   |
| 6.172         | 6.0   | 2322  | 5.8617          | 0.2083   |
| 6.0943        | 7.0   | 2709  | 5.8212          | 0.2115   |
| 6.0318        | 8.0   | 3096  | 5.7983          | 0.2132   |
| 5.9812        | 9.0   | 3483  | 5.7818          | 0.2151   |
| 5.9436        | 10.0  | 3870  | 5.7673          | 0.2163   |
| 5.9144        | 11.0  | 4257  | 5.7563          | 0.2171   |
| 5.8923        | 12.0  | 4644  | 5.7452          | 0.2185   |
| 5.8723        | 13.0  | 5031  | 5.7387          | 0.2190   |
| 5.8549        | 14.0  | 5418  | 5.7320          | 0.2193   |
| 5.8427        | 15.0  | 5805  | 5.7259          | 0.2199   |
| 5.8306        | 16.0  | 6192  | 5.7219          | 0.2203   |
| 5.8176        | 17.0  | 6579  | 5.7186          | 0.2204   |
| 5.8129        | 18.0  | 6966  | 5.7153          | 0.2206   |
| 5.8055        | 19.0  | 7353  | 5.7119          | 0.2211   |
| 5.7954        | 20.0  | 7740  | 5.7097          | 0.2213   |
| 5.7906        | 21.0  | 8127  | 5.7078          | 0.2219   |
| 5.7834        | 22.0  | 8514  | 5.7061          | 0.2221   |
| 5.7779        | 23.0  | 8901  | 5.7042          | 0.2224   |
| 5.7718        | 24.0  | 9288  | 5.7019          | 0.2226   |
| 5.7664        | 25.0  | 9675  | 5.7002          | 0.2231   |
| 5.7616        | 26.0  | 10062 | 5.6989          | 0.2234   |
| 5.7596        | 27.0  | 10449 | 5.6972          | 0.2234   |
| 5.7553        | 28.0  | 10836 | 5.6960          | 0.2236   |
| 5.7525        | 29.0  | 11223 | 5.6948          | 0.2235   |
| 5.7488        | 30.0  | 11610 | 5.6939          | 0.2236   |
| 5.7445        | 31.0  | 11997 | 5.6930          | 0.2237   |
| 5.7409        | 32.0  | 12384 | 5.6919          | 0.2237   |
| 5.7389        | 33.0  | 12771 | 5.6912          | 0.2237   |
| 5.739         | 34.0  | 13158 | 5.6904          | 0.2239   |
| 5.7339        | 35.0  | 13545 | 5.6896          | 0.2239   |
| 5.731         | 36.0  | 13932 | 5.6891          | 0.2240   |
| 5.7285        | 37.0  | 14319 | 5.6885          | 0.2240   |
| 5.724         | 38.0  | 14706 | 5.6881          | 0.2241   |
| 5.7241        | 39.0  | 15093 | 5.6874          | 0.2242   |
| 5.724         | 40.0  | 15480 | 5.6871          | 0.2244   |
| 5.7199        | 41.0  | 15867 | 5.6867          | 0.2245   |
| 5.7212        | 42.0  | 16254 | 5.6863          | 0.2244   |
| 5.7209        | 43.0  | 16641 | 5.6859          | 0.2245   |
| 5.7169        | 44.0  | 17028 | 5.6857          | 0.2245   |
| 5.7185        | 45.0  | 17415 | 5.6856          | 0.2247   |
| 5.7165        | 46.0  | 17802 | 5.6853          | 0.2247   |
| 5.7202        | 47.0  | 18189 | 5.6851          | 0.2248   |
| 5.7183        | 48.0  | 18576 | 5.6850          | 0.2248   |
| 5.7179        | 49.0  | 18963 | 5.6849          | 0.2248   |
| 5.7164        | 50.0  | 19350 | 5.6849          | 0.2249   |


### Framework versions

- Transformers 4.38.0.dev0
- Pytorch 2.2.0
- Datasets 2.16.1
- Tokenizers 0.15.1
