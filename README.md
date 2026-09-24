# TCA-UNet

## Perceptual Evaluation (Supplementary)

Objective metrics (PESQ, ESTOI, ERLE) are reported in the paper. We additionally report
AECMOS scores and provide listening samples below.

### AECMOS scores (higher is better)

| Model       | DT EchoMOS | DT DegMOS | FE EchoMOS | NE DegMOS |
|-------------|:----------:|:---------:|:----------:|:---------:|
| EchoFree    | 3.90       | 3.54      | 4.39       | 3.29      |
| AdaptCRN    | 3.98       | 3.50      | **4.53**   | 3.22      |
| LiSenNet    | 4.03       | 3.62      | 4.40       | 3.36      |
| **TCA-UNet (ours)** | **4.21** | **3.68** | 4.52 | **3.38** |

> Note: As discussed in Sec. 3.3 of the paper, AECMOS tends to yield inflated scores in
> double-talk and far-end scenarios and does not reliably reflect semantic alignment;
> these scores are reported as supplementary reference only.
