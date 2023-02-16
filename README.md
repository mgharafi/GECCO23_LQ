# GECCO23_LQ


### Algorithms names :
- `LQ` : refers to COMO-lq-CMA-ES
- `Como` : refers to COMO-CMA-ES
- `ker` prefix refers to the performance assessment based only on the HV of kernels' incumbents.
- `All` prefix refers to the performance assessment of such algorithm based on the archive of non-dominated solutions and kernels' incumbents.
### Data for LQ/COMO with `popsize_factor=4`:
#### Dimension 2,3,5 and 10:
- data plots: [COCO](P4K10\MUTLI_DIM\index.html)
- budget: 1e4
### Data for LQ/COMO with `popsize_factor=1`:
#### Dimension 2,3,5,10 and 20:
- data plots: [COCO](data_1\index.html)
- budget: 1e2

#### Dimension 2,3,5,10 and 20:
- data plots for ker only: [COCO-ker-only](budget-1000-D\data_ker_only\index.html)
- data plots for ker only: [COCO-archive](budget-1000-D\data_All\index.html)
- budget: 1e3

#### Check AllComo with sigma = sqrt(dimension)
- data : [COCO](check)
- budget = 1e3

#### Single algorithms check:
- kerLQ : [single-post](data_kerLQ/index.html)
- kerComo : [single-post](data_KerComo/index.html)