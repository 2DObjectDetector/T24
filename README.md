# T2.4 Qualitative analysis

Plots ground truth (blue), true positives (green), false positives (red) and false negatives (amber) for three validation images (000136, 000232, 000189), comparing the first and best fine-tuned configurations. Part of [2D Object Detector](https://github.com/2DObjectDetector).

**Matching thresholds:** confidence 0.25 and IoU 0.5. The best configuration had one fewer false positive than the baseline on image 000189 (4 vs 5); the other two images showed no change in counts.

**Run:** Outputs are saved in the notebook, so the results are visible without running it. To rerun: use a Colab GPU runtime and add the `kitti3k_yolo` dataset (not included) and update its path.
