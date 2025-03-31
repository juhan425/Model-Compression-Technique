# Model-Compression-Technique
**Pruning**
- Method: Nework Slimimg Pruning 
- Model: ResNet50
 <img src="pruning/ref/network_slimimg.jpg" width="65%">
 <img src="pruning/ref/network_slimimg.gif" width="35%">

**Knowlwdge Distillation**
- Teacher Model: ResNet38
- Student Model: ResNet18
- Dataset: cifar10
- Parameter: 21.3M(teacher) → 11.2M(student)
- Accuracy: 87.11%(teacher) → 87.77%(student)
<img src="knowledge_distillation/kd.png" width="65%">

**Quantize**
- Post Training Quantization (PTQ)
  
  <img src="quantize/ref/ptq.png" width="30%">
  
- Quantization-Aware Training (QAT)
  
  <img src="quantize/ref/qat.png" width="30%">
