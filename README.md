# Discriminator-for-distinguishing-between-poisonous-and-medicinal-herbs
## 동의보감 독초 판별기 ( 2021. 11. 25(목) ~ 11. 29.(월) )
### **3rd prize**
## Abstract
&nbsp;데이터를 독초, 약초 데이터를 활용하여 독초 판별기를 만들었다. 데이터는 대략 600Gb이며, preprocessing에서 Crop, Flip Rotation등을 실행하여 overfitting을 방지했다. 또한 EfficenNet을 기반으로 학습시켰으며, SE block layer을 추가함으로써 데이터를 Noramlisation하여 성능향상을 도모했다.

## Feature
1. EfficentNet을 Backbone으로 구성.
2. SE Block으로 성능향상.

## Summary
1. Ensemble learning method를 적용시켜 optimal model을 추출하여 성능을 개선시킬 수 있다. 
2. Learning rate를 더 줄여 convergence시켜 성능을 높일 수 있다.
