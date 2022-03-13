# "Practical Training Approaches for Discordant Atopic Dermatitis Severity Datasets: Merging Methods with Soft-label and Train-set Pruning", IEEE Journal of Biomedical and Health Informatics, 2022 (under review)
![overview](./assets/Figure1.jpg)

## Training Approaches for CNN
(1) Individual vs Merging (Integration vs Ensemble)
- Integration: merge the grade from the five dermatologists before training
- Ensemble: train each individual dataset and merge the outcomes for each model

(2) Hard-Label vs Soft Label
- Hard-Label: merge the grade using the median values 
- Soft-Label: consider the distributions of each grading

(3) Whole Dataset vs Train-set Pruning
- Train-set Pruning: excluding discordant train-set (defined as discordant when the maximum number of matched raters was not more than two)

---
## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details

---
## Contact

dhlee.jubilee@gmail.com

