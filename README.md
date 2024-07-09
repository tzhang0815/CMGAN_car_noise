# CMGAN_car_noise: conformer-based metric GAN particulatly fine-tuned for in-car noise speech enhancement

## Title
CMGAN-Based Speech Enhancement for Automotive Environments: Targeted Noise Reduction

## Abstract
This research employs a Conformer Metric Generative Adversarial Network (CMGAN) model, trained on a tailored in-car noisy speech dataset. The methodology incorporates pre-training, hy- brid training, and targeted training to assess the model’s performance in speech enhancement tasks. In total, four experiments were conducted to determine the most effective training strategies for the model. Results from these experimental setups confirm that this targeted training approach signifi- cantly enhances the ASR system’s accuracy and reliability. Particularly when fine-tuned for specific noise conditions, the CMGAN model demonstrated substantial improvements in evaluation metrics, such as the Perceptual Evaluation of Speech Quality (PESQ). Moreover, this study shows that the CMGAN model excels in reducing driving noise but shows less efficacy against street noise and air-conditioner noise. In addition to identifying the most effective training strategies for specific noise datasets, these findings also clarify the relationships between noise types and the effectiveness of speech enhancement. This research concludes that focusing on adaptive and specialized train- ing frameworks can greatly improve ASR performance in real-world noise environments, providing valuable insights for advancing speech recognition technology in practical applications.

## Enhanced Audio samples
link: 

## Environment
Hints: the model training is conducted on the RUG High Performance Computing cluster - Hábrók (V100 GPU)

1-Environment activation


```

python3 -m venv $HOME/venvs/cmgan1
source $HOME/venvs/cmgan1/bin/activate
module load Python/3.8.16-GCCcore-11.2.0
module load PyTorch/1.12.0-foss-2022a-CUDA-11.7.0

```



## Data Preparation

## Model training

## Evaluation
