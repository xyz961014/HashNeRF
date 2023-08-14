# **NeRF** with Hash Encoding





### Experiment Table

Experiment with RTX 2060 Max-Q

|                        | Model size | Step | PSNR  | SSIM  | LPIPS |
| ---------------------- | ---------- | ---- | ----- | ----- | ----- |
| LEGO baseline          | 1192k      | 50k  | 28.73 | 0.937 | 0.073 |
| LEGO hash              | 19.2k      | 10k  | 28.45 | 0.940 | 0.068 |
| MIC baseline           | 1192k      | 50k  | 30.53 | 0.967 | 0.051 |
| MIC hash               | 19.2k      | 10k  | 28.19 | 0.960 | 0.055 |
| SHIP baseline          | 1192k      | 50k  | 27.34 | 0.834 | 0.194 |
| SHIP hash              | 19.2k      | 10k  | 26.37 | 0.834 | 0.175 |
| (llff) ORCHID hash     | 19.2k      | 10k  | 17.58 | 0.688 | 0.227 |
| (llff) ORCHID baseline | 1192k      | 50k  | 20.57 | 0.686 | 0.297 |

### T experiment

| T    | PSNR  | SSIM  | LPIPS |
| ---- | ----- | ----- | ----- |
| 13   | 25.87 | 0.878 | 0.141 |
| 16   | 27.55 | 0.921 | 0.094 |
| 19   | 28.45 | 0.940 | 0.067 |
| 21   | 28.55 | 0.943 | 0.061 |

