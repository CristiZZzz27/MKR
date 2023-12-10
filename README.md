# MKR

## Requirements
Tested under
- Python == 3.10
- PyTorch >= 1.4
- scikit-learn, tqdm, numpy, matplotlib, tensorboardX





## Running the code
There are two way to run the code

1. Use local editors like vscode
2. Use the colab/kaggle to do it online ( recommend, we do it in this way )



### 1. local

step 1

in src \ \ preprocess.py

```
python preprocess.py --dataset 'movie'    # for MovieLens-1M dataset

python preprocess.py --dataset 'music'    # for Last.FM dataset  
```
step 2

in src \ \ main.py

```
python main.py --dataset 'movie'# for MovieLens-1M dataset

python main.py --dataset 'music'# for Last.FM dataset  
```



### 2. online

just use my github clone

step 1

```
!git clone -b master https://github.com/CristiZZzz27/MKR.git
```

```
cd MKR//src
```

step 2

```
!python preprocess.py --dataset 'movie'    # for MovieLens-1M 

!python preprocess.py --dataset 'music'    # for Last.FM 
```

step 3

```
!python main.py --dataset 'movie'   # for MovieLens-1M dataset

!python main.py --dataset 'music'   # for Last.FM dataset  
```

