# Local Subsequence-based Distribution for Time Series Clustering



## Usage
For datasets less than 150 in length:
```shell
python main.py --dataset TwoLeadECG --type 1 --d 40
python main.py --dataset CBF --type 1 --d 60
```

For datasets greater than 150 in length:
```shell
python main.py --dataset FaceFour --type 0 --d 60
python main.py --dataset StarLightCurves --type 0 --d 72
```
 
## Dependencies
- numpy
- scipy
- joblib
- tslearn
- scikit-learn


### Cite this paper

Gong, L., Zhang, H., Liu, Z., Ting, K.M., Cao, Y., Zhu, Y. (2024). Local Subsequence-Based Distribution for Time Series Clustering. In: Yang, DN., Xie, X., Tseng, V.S., Pei, J., Huang, JW., Lin, J.CW. (eds) Advances in Knowledge Discovery and Data Mining. PAKDD 2024. Lecture Notes in Computer Science(), vol 14645. Springer, Singapore. https://doi.org/10.1007/978-981-97-2242-6_21

