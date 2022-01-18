1. Download dataset from [imagenette](https://github.com/fastai/imagenette)

2. Extract the dataset so that the structure look like this:
```
root/
|
+--imagewang
   +--train
   +--unsup
   +--val
+--runs
+--main.ipynb
```

3. ```pip install -r requirements.txt```
4. Open up main.ipynb and set ```model_name```
5. Run the code. To skip the training process, simply skip the line ```train(model, ...)```
