第一次运行结果 20190303 11:56am
using GPU
==> Building model..
==> Resuming from checkpoint..
==> loading checkpoint sysu_id_drop_0.0_lr_1.0e-02_dim_512_resnet50_best.t
==> loaded checkpoint sysu_id_drop_0.0_lr_1.0e-02_dim_512_resnet50_best.t (epoch 58)
==> Loading data..
Dataset statistics:
  ------------------------------
  subset   | # ids | # images
  ------------------------------
  query    |    96 |     3803
  gallery  |    96 |      301
  ------------------------------
Data Loading Time:	 7.226
Extracting Query Feature...
Extracting Time:	 19.860

Extracting Gallery Feature...
Extracting Time:	 3.400
Test Trial: 0
FC: top-1: 23.74% | top-5: 51.17% | top-10: 66.37%| top-20: 81.30%
mAP: 26.05%
POOL5: top-1: 22.01% | top-5: 46.70% | top-10: 62.37%| top-20: 78.62%
mAP: 23.07%

Extracting Gallery Feature...
Extracting Time:	 1.425
Test Trial: 1
FC: top-1: 24.06% | top-5: 52.56% | top-10: 67.00%| top-20: 82.01%
mAP: 27.17%
POOL5: top-1: 21.67% | top-5: 46.20% | top-10: 62.61%| top-20: 79.86%
mAP: 24.05%

Extracting Gallery Feature...
Extracting Time:	 1.436
Test Trial: 2
FC: top-1: 23.90% | top-5: 51.83% | top-10: 66.68%| top-20: 83.57%
mAP: 26.48%
POOL5: top-1: 20.72% | top-5: 47.44% | top-10: 63.53%| top-20: 79.94%
mAP: 22.84%

Extracting Gallery Feature...
Extracting Time:	 1.438
Test Trial: 3
FC: top-1: 23.35% | top-5: 53.19% | top-10: 69.42%| top-20: 84.09%
mAP: 26.54%
POOL5: top-1: 22.25% | top-5: 50.17% | top-10: 65.47%| top-20: 81.01%
mAP: 24.24%

Extracting Gallery Feature...
Extracting Time:	 1.441
Test Trial: 4
FC: top-1: 22.22% | top-5: 51.38% | top-10: 66.76%| top-20: 83.09%
mAP: 26.32%
POOL5: top-1: 20.80% | top-5: 48.75% | top-10: 63.21%| top-20: 79.31%
mAP: 23.70%

Extracting Gallery Feature...
Extracting Time:	 1.419
Test Trial: 5
FC: top-1: 23.43% | top-5: 49.96% | top-10: 65.84%| top-20: 81.86%
mAP: 26.08%
POOL5: top-1: 19.56% | top-5: 43.97% | top-10: 61.00%| top-20: 78.15%
mAP: 22.20%

Extracting Gallery Feature...
Extracting Time:	 1.397
Test Trial: 6
FC: top-1: 24.56% | top-5: 51.99% | top-10: 67.32%| top-20: 80.83%
mAP: 26.59%
POOL5: top-1: 21.11% | top-5: 48.36% | top-10: 63.66%| top-20: 79.60%
mAP: 23.58%

Extracting Gallery Feature...
Extracting Time:	 1.415
Test Trial: 7
FC: top-1: 24.69% | top-5: 51.33% | top-10: 66.13%| top-20: 82.51%
mAP: 27.38%
POOL5: top-1: 20.54% | top-5: 47.28% | top-10: 61.56%| top-20: 76.41%
mAP: 23.58%

Extracting Gallery Feature...
Extracting Time:	 1.440
Test Trial: 8
FC: top-1: 22.38% | top-5: 48.80% | top-10: 64.98%| top-20: 81.30%
mAP: 25.78%
POOL5: top-1: 19.06% | top-5: 44.31% | top-10: 60.74%| top-20: 76.97%
mAP: 22.18%

Extracting Gallery Feature...
Extracting Time:	 1.430
Test Trial: 9
FC: top-1: 26.06% | top-5: 54.30% | top-10: 67.26%| top-20: 81.25%
mAP: 27.81%
POOL5: top-1: 21.80% | top-5: 48.23% | top-10: 62.45%| top-20: 78.18%
mAP: 23.41%

All Average:
FC: top-1: 23.84% | top-5: 51.65% | top-10: 66.78%| top-20: 82.18%
mAP: 26.62%
POOL5: top-1: 20.95% | top-5: 47.14% | top-10: 62.66%| top-20: 78.80%
mAP: 23.29%


using GPU
==> Building model..
==> Resuming from checkpoint..
==> loading checkpoint sysu_id_bn_relu_drop_0.0_lr_1.0e-02_dim_512_resnet50_epoch_58.t
==> loaded checkpoint sysu_id_bn_relu_drop_0.0_lr_1.0e-02_dim_512_resnet50_epoch_58.t (epoch 58)
==> Loading data..
Dataset statistics:
  ------------------------------
  subset   | # ids | # images
  ------------------------------
  query    |    96 |     3803
  gallery  |    96 |      301
  ------------------------------
Data Loading Time:	 7.370
Extracting Query Feature...
Extracting Time:	 19.297
Extracting Gallery Feature...
Extracting Time:	 3.191
Test Trial: 0
FC: top-1: 20.56% | top-5: 47.46% | top-10: 61.66%| top-20: 76.76%
mAP: 22.67%
POOL5: top-1: 19.14% | top-5: 43.44% | top-10: 56.72%| top-20: 72.44%
mAP: 20.50%
Extracting Gallery Feature...
Extracting Time:	 1.401
Test Trial: 1
FC: top-1: 20.17% | top-5: 48.46% | top-10: 63.92%| top-20: 79.36%
mAP: 22.73%
POOL5: top-1: 19.35% | top-5: 44.75% | top-10: 59.85%| top-20: 76.07%
mAP: 20.60%
Extracting Gallery Feature...
Extracting Time:	 1.417
Test Trial: 2
FC: top-1: 21.25% | top-5: 48.51% | top-10: 63.71%| top-20: 77.23%
mAP: 23.90%
POOL5: top-1: 19.30% | top-5: 43.12% | top-10: 54.83%| top-20: 70.13%
mAP: 20.68%
Extracting Gallery Feature...
Extracting Time:	 1.393
Test Trial: 3
FC: top-1: 19.56% | top-5: 44.96% | top-10: 60.77%| top-20: 76.91%
mAP: 22.34%
POOL5: top-1: 16.62% | top-5: 41.70% | top-10: 56.43%| top-20: 72.57%
mAP: 19.25%
Extracting Gallery Feature...
Extracting Time:	 1.469
Test Trial: 4
FC: top-1: 21.22% | top-5: 47.57% | top-10: 61.37%| top-20: 74.68%
mAP: 23.20%
POOL5: top-1: 17.96% | top-5: 43.60% | top-10: 59.01%| top-20: 73.44%
mAP: 19.59%
Extracting Gallery Feature...
Extracting Time:	 1.424
Test Trial: 5
FC: top-1: 22.43% | top-5: 47.41% | top-10: 61.40%| top-20: 76.68%
mAP: 23.78%
POOL5: top-1: 17.51% | top-5: 45.15% | top-10: 59.58%| top-20: 74.52%
mAP: 20.36%
Extracting Gallery Feature...
Extracting Time:	 1.442
Test Trial: 6
FC: top-1: 20.67% | top-5: 47.02% | top-10: 62.14%| top-20: 78.10%
mAP: 23.10%
POOL5: top-1: 17.85% | top-5: 43.78% | top-10: 57.74%| top-20: 73.28%
mAP: 19.39%
Extracting Gallery Feature...
Extracting Time:	 1.387
Test Trial: 7
FC: top-1: 20.56% | top-5: 46.57% | top-10: 60.66%| top-20: 75.20%
mAP: 22.80%
POOL5: top-1: 20.04% | top-5: 42.76% | top-10: 56.59%| top-20: 70.92%
mAP: 20.16%
Extracting Gallery Feature...
Extracting Time:	 1.401
Test Trial: 8
FC: top-1: 21.72% | top-5: 47.33% | top-10: 62.11%| top-20: 78.52%
mAP: 24.40%
POOL5: top-1: 18.25% | top-5: 42.49% | top-10: 57.30%| top-20: 74.99%
mAP: 20.22%
Extracting Gallery Feature...
Extracting Time:	 1.437
Test Trial: 9
FC: top-1: 20.90% | top-5: 47.94% | top-10: 63.13%| top-20: 77.75%
mAP: 22.87%
POOL5: top-1: 19.96% | top-5: 45.10% | top-10: 59.90%| top-20: 75.28%
mAP: 20.88%


All Average:
FC: top-1: 20.90% | top-5: 47.32% | top-10: 62.09%| top-20: 77.12%
mAP: 23.18%
POOL5: top-1: 18.60% | top-5: 43.59% | top-10: 57.79%| top-20: 73.37%
mAP: 20.16%