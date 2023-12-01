# ntb_mall_recommendation

## Preprocessing Dataset

  Berikut adalah beberapa preprocessing yang dilakukan dalam dataset:
  - Check Missing Values and Data Duplication
  - Remove HTML Tag
  - Concate Feature Column
  - Text Preprocessing


## Feature Extraction

  Using TF-IDF Algorithm .....

  
## Content Based Filtering Algorithm

  Dalam menyelesaikan permasalahan ini akan digunakan algoritma Cosine Similarity dan Euclidean Distance.
  - Euclidean Distance
  - Cosine Similarity
    

## Evaluation
Rekomendasi barang NTB Mall

Information:

1 query = 15 data

Total data yang diperoleh adalah

1500 query x 15 data = 22500 row

Untuk hasil akurasi (benar/total) dari kedua metode tersebut adalah sebagai berikut:
| Algoritma           | Accuracy |
|--------------------|--------------------|
| Euclidean Distance | 0.6011999999999995 |
| Cosine Similarity  | 0.7965777777777748 |


tabel 

| Algoritma          | Euclidean Distance | Euclidean Distance | Cosine Similarity | Cosine Similarity  |
| Jumlah Query       |   Acc   |   MRR    |   Acc   |   MRR    |
|--------------------|---------|----------|---------|----------|
|   5                |  0.746  |  0.883   | 0.890   |  0.952   |
|   10               |  0.642  |  0.888   | 0.834   |  0.953   |
|   15               |  0.572  |  0.889   | 0.796   |  0.954   |


| Algoritma           | ET |
|--------------------|--------------------|
| Euclidean Distance | 0.6011999999999995 |
| Cosine Similarity  | 0.7965777777777748 |

