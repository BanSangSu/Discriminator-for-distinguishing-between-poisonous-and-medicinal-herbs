# Discriminator-for-distinguishing-between-poisonous-and-medicinal-herbs
## Discriminator for Distinguishing between Poisonous Herbs and Medicinal Herbs
(동의보감 독초 판별기)

### 3rd prize 🏆
- **Organiser**: The Ministry of Science and ICT
- **Period**: 25th - 29th Nov, 2021

## Abstract
We created a poisonous herb and medicinal herb discriminator using poisonous and medicinal herb data. This model was trained on approximately **600GB** of herb data, and overfitting was prevented by performing **cropping**, **flipping**, and **rotation** in the preprocessing process. In addition, **EfficientNet** model was used as a backbone and the performance was improved by normalising the data by adding an **SE block layer**.

## Feature
1. Configure **EfficientNet** as a backbone.
2. Improved performance with **SE blocks**.

## Summary
1. The performance can be more improved by extracting the optimal model by applying the Ensemble learning method. 
2. Since the model has not yet converged, you can train it further by reducing the learning rate.

## License
[Apache License 2.0](LICENSE)
