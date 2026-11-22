# Project visual sources

The repository images below are copied unchanged from the author's project repositories. The new SVGs summarize the referenced work; none depicts a new experiment or a clinical deployment.

## HistoPilot

Source revision: `ae5ad03d10a2c74c97691f126710c3ae0f9ae2ac` in [Lyce24/HistoPilot](https://github.com/Lyce24/HistoPilot).

| Portfolio asset | Source path | Meaning |
| --- | --- | --- |
| `histopilot-ui.png` | `docs/assets/blca/overview.png` | Browser workspace, synthetic BLCA demo |
| `histopilot-cli.svg` | `docs/assets/readme/terminal.svg` | CLI output from the synthetic study |
| `histopilot-mcp.svg` | `docs/assets/readme/agent.svg` | Illustrative AI exchange written from the same synthetic results |

The screenshots and interface examples do not contain actual patient records or clinical performance results. Public TCGA/CPTAC benchmark results are documented separately in the HistoPilot repository.

## KRAS CRC

`kras-transfer.svg` recreates two equal-cohort summary estimates from [figures/fig2_transfer_base.py](https://github.com/Lyce24/CRC_KRAS/blob/14cdb521da44233d3415c695c2518209fd41b724/figures/fig2_transfer_base.py), source blob `2a5a1a2195c9b885b47a1fc61cb9e255ac3a8d7d`.

| Frozen UNI-v1 summary | AUROC | 95% confidence interval |
| --- | ---: | --- |
| Primary tumors (CPTAC and RIH) | 0.726 | 0.659–0.792 |
| Metastases (RIH and SurGen) | 0.606 | 0.515–0.699 |

This is a descriptive display of the public study values. It does not claim a statistically significant difference between groups. SurGen metastases come from SR1482, whose primary tumors were included in development.

## PaCX-MAE

`pacx-architecture.png` is the original `Figs/ssl (2).png` figure from [Lyce24/PACX-MAE](https://github.com/Lyce24/PACX-MAE/tree/b72274577bce83ba5732391fcfee14d039be3c96), source blob `99872acdf46b8bcc7ed3816c3e35352172d25a58`.

`pacx-overview.svg` is a simplified vector summary based on the same repository's README and architecture figure. `pacx-overview-mobile.svg` presents the same training and inference stages in a portrait layout for narrow screens. They distinguish training with chest X-ray, ECG, and laboratory information from chest-X-ray-only inference. Their X-ray symbols are schematic icons, not medical images.
