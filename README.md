
## Submission by :
**Name** :  Vibhav Shukla
<br>
**Roll No** : 102003772

## Sampling Assignment

**Dataset Used:** [Census Dataset]('https://archive.ics.uci.edu/ml/machine-learning-databases/adult/adult.data')

| Number of Instances:  | 48842 |
|-----------------------|--------|
| Number of Attributes: | 14     |

## Tasks Performed
1. Download the dataset
2. Pre-process the dataset
3. Create ten samples 
4. Split the samples in  70 : 30 for training and testing
5. Optimise SVM using randomisation for every sample and report best accuracy and best parameters
6. For the best sample plot the convergence graph


## Results

### Compartitive performance of SVM with different samples
|Sample|	Accuracy |	Kernel |	C 	 |     Gamma |
|------|-----------|--------|---------|-----------|
|S1	| 0.7419889502762431 |	rbf	   |0.519505	|0.007584 |
S2	| 0.7419889502762431	|sigmoid	|0.452718	|0.075356|
S3	| 0.7419889502762431	|rbf	|0.057398	|0.177306|
S4	| 0.7599447513812154	|rbf	|0.550068	|0.00068|
S5	| 0.7599447513812154	|rbf	|0.550068	|0.00068|
S6	| 0.7599447513812154	|rbf	|0.550068	|0.00068|
S7	| 0.7729281767955801	|rbf	|0.550068	|0.00068|
S8	| 0.7729281767955801  |rbf	|0.550068	|0.00068|
S9	| 0.7729281767955801	|rbf	|0.668707	|0.544932|
S10	| 0.7729281767955801	|rbf	|0.668707	|0.544932|

### Convergence graph for Sample 9 : 
![image](https://user-images.githubusercontent.com/74780852/233284150-badfcb32-0dd8-44ad-9f6f-c50a06ccaed9.png)
