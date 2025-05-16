# [Artificial Intelligence] Mini Project
Let's implement CIFAR-10 image classification in various ways.

You can simply run **pipeline.ipynb** to do so.

All needed functions are defined at **1. Baseline**.

If you want to run code only for the other part, don't miss to run code for **1. Baseline** first.

## About pipeline.ipynb
pipeline.ipynb consists of following three parts.

1. Baseline

2. Variants
   
   2.1. Random Label Shuffle
   
   2.2. Label Noise

   2.3. Input Perturbation
   - crop
   - blur

   2.4. Class Imbalance

3. Comparison

## Note
I omitted 'data' and 'model' directories due to their large size.

Please refer to following directory structure to implement 'pipeline.ipynb'.
```
25ai_mini_project
ㄴdata
ㄴmodel
   ㄴ1_baseline
   ㄴ2-1_var1   
   ㄴ2-2_var2
   ㄴ2-3_1_var3_1
   ㄴ2-3_var3
   ㄴ2-4_var4
   ㄴbest_models
ㄴpipeline.ipynb
```
