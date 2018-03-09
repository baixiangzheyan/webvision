# WebVision

WebVision is an exploratory project which wants to find ways to learn from noisy data.

The process pipeline is as follows:
- Filter data
- Train baseline model
- Extract features and clustering
- Design curriculim learning strategy
- Train models from easy to hard

Please check out [this site](http://www.vision.ee.ethz.ch/webvision/index.html) for dataset details.

## Results

### Comparison of Models
![fig_1](results/res.png)

### Training Curve

#### (1) Target
![fig_2](results/inception_v3/inception_v3_a.png)

#### (2) Baseline
![fig_3](results/inception_v3/inception_v3_baseline.png)

#### (3) Q10
![fig_4](results/inception_v3/inception_v3_q10_v2.png)

### Data Visulization

#### (1) Examples in  Tench
![fig_5](results/clean_noisy_visu.png)

#### (2) All images of Bulbul
![fig_6](results/tsne_visu_1.jpg)

#### (3) Clean images of Bulbul
![fig_7](results/tsne_visu_3.jpg)

#### (4) Noisy images of Bulbul
![fig_8](results/tsne_visu_2.jpg)