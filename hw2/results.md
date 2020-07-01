# 685

`mask.shape torch.Size([100, 14])`

`embeddings.shape torch.Size([100, 14, 50])`

`sent_emb torch.Size([100, 50])`

# GLOVE

## Tunable

### Embedding 50
```
{'best_epoch': 53,
 'best_validation_accuracy': 0.5876334519572953,
 'best_validation_loss': 0.6752463371857352,
 'epoch': 72,
 'peak_cpu_memory_MB': 4340.02,
 'peak_gpu_0_memory_MB': 3105,
 'training_accuracy': 0.7165775401069518,
 'training_cpu_memory_MB': 4340.02,
 'training_duration': '0:00:32.386640',
 'training_epochs': 72,
 'training_gpu_0_memory_MB': 3105,
 'training_loss': 0.6273433764775594,
 'training_start_epoch': 0,
 'validation_accuracy': 0.5814056939501779,
 'validation_loss': 0.6769823431968689}
 ```

 ### Embedding 100
 ```
 {'best_epoch': 59,
 'best_validation_accuracy': 0.5960854092526691,
 'best_validation_loss': 0.6745052285816359,
 'epoch': 78,
 'peak_cpu_memory_MB': 4343.424,
 'peak_gpu_0_memory_MB': 3105,
 'training_accuracy': 0.7219251336898396,
 'training_cpu_memory_MB': 4343.424,
 'training_duration': '0:00:35.087230',
 'training_epochs': 78,
 'training_gpu_0_memory_MB': 3105,
 'training_loss': 0.5982290546099345,
 'training_start_epoch': 0,
 'validation_accuracy': 0.5867437722419929,
 'validation_loss': 0.6882727534874625}
 ```


 ### Embedding 300
 ```
 {'best_epoch': 18,
 'best_validation_accuracy': 0.6072064056939501,
 'best_validation_loss': 0.6746641138325566,
 'epoch': 37,
 'peak_cpu_memory_MB': 4361.144,
 'peak_gpu_0_memory_MB': 3105,
 'training_accuracy': 0.7219251336898396,
 'training_cpu_memory_MB': 4361.144,
 'training_duration': '0:00:17.520355',
 'training_epochs': 37,
 'training_gpu_0_memory_MB': 3105,
 'training_loss': 0.6175007303555806,
 'training_start_epoch': 0,
 'validation_accuracy': 0.5925266903914591,
 'validation_loss': 0.6731283820193746}
 ```

## Frozen Weights

### Embedding 50
```
{'best_epoch': 97,
 'best_validation_accuracy': 0.5404804270462633,
 'best_validation_loss': 0.6907647614893706,
 'epoch': 99,
 'peak_cpu_memory_MB': 4361.144,
 'peak_gpu_0_memory_MB': 3105,
 'training_accuracy': 0.5454545454545454,
 'training_cpu_memory_MB': 4361.144,
 'training_duration': '0:00:43.462317',
 'training_epochs': 99,
 'training_gpu_0_memory_MB': 3105,
 'training_loss': 0.6904354969660441,
 'training_start_epoch': 0,
 'validation_accuracy': 0.5382562277580071,
 'validation_loss': 0.6909222447353861
 ```

### Embedding 100
```
{'best_epoch': 96,
 'best_validation_accuracy': 0.576067615658363,
 'best_validation_loss': 0.6875602680703868,
 'epoch': 99,
 'peak_cpu_memory_MB': 4361.144,
 'peak_gpu_0_memory_MB': 3105,
 'training_accuracy': 0.5614973262032086,
 'training_cpu_memory_MB': 4361.144,
 'training_duration': '0:00:43.543979',
 'training_epochs': 99,
 'training_gpu_0_memory_MB': 3105,
 'training_loss': 0.6864671508471171,
 'training_start_epoch': 0,
 'validation_accuracy': 0.5693950177935944,
 'validation_loss': 0.6874744762545046}
 ```

### Embeding 300
 ```
 {'best_epoch': 72,
 'best_validation_accuracy': 0.5751779359430605,
 'best_validation_loss': 0.6879452829775603,
 'epoch': 91,
 'peak_cpu_memory_MB': 4361.144,
 'peak_gpu_0_memory_MB': 3105,
 'training_accuracy': 0.5748663101604278,
 'training_cpu_memory_MB': 4361.144,
 'training_duration': '0:00:40.227724',
 'training_epochs': 91,
 'training_gpu_0_memory_MB': 3105,
 'training_loss': 0.6861123641331991,
 'training_start_epoch': 0,
 'validation_accuracy': 0.5667259786476868,
 'validation_loss': 0.6878742679305698}
 ```

# ELMO

## Frozen

### Random
```
{'best_epoch': 53,
 'best_validation_accuracy': 0.5342526690391459,
 'best_validation_loss': 0.6925953548887501,
 'epoch': 72,
 'peak_cpu_memory_MB': 5028.204,
 'peak_gpu_0_memory_MB': 7341,
 'training_accuracy': 0.5233957219251337,
 'training_cpu_memory_MB': 5028.204,
 'training_duration': '0:09:20.961782',
 'training_epochs': 72,
 'training_gpu_0_memory_MB': 7341,
 'training_loss': 0.6923484643300374,
 'training_start_epoch': 0,
 'validation_accuracy': 0.5231316725978647,
 'validation_loss': 0.6923250659652378}
```

### Pre-trained
```
{'best_epoch': 57,
 'best_validation_accuracy': 0.6579181494661922,
 'best_validation_loss': 0.6351578572522039,
 'epoch': 76,
 'peak_cpu_memory_MB': 5028.204,
 'peak_gpu_0_memory_MB': 7341,
 'training_accuracy': 0.7299465240641712,
 'training_cpu_memory_MB': 5028.204,
 'training_duration': '0:09:47.219013',
 'training_epochs': 76,
 'training_gpu_0_memory_MB': 7341,
 'training_loss': 0.5525408168633779,
 'training_start_epoch': 0,
 'validation_accuracy': 0.6432384341637011,
 'validation_loss': 0.6548716814621635}
```

## Tunable

### Random
```
{'best_epoch': 3,
 'best_validation_accuracy': 0.5133451957295374,
 'best_validation_loss': 0.6938280463218689,
 'epoch': 22,
 'peak_cpu_memory_MB': 5029.38,
 'peak_gpu_0_memory_MB': 11121,
 'training_accuracy': 0.5086898395721925,
 'training_cpu_memory_MB': 5029.38,
 'training_duration': '0:06:32.544007',
 'training_epochs': 22,
 'training_gpu_0_memory_MB': 11121,
 'training_loss': 0.7065510272979736,
 'training_start_epoch': 0,
 'validation_accuracy': 0.5,
 'validation_loss': 0.7001863769862963}
```

### Pre-trained
```
{'best_epoch': 30,
 'best_validation_accuracy': 0.8945729537366548,
 'best_validation_loss': 0.5319394151801649,
 'epoch': 49,
 'peak_cpu_memory_MB': 5029.38,
 'peak_gpu_0_memory_MB': 11123,
 'training_accuracy': 0.9859625668449198,
 'training_cpu_memory_MB': 5029.38,
 'training_duration': '0:14:09.331122',
 'training_epochs': 49,
 'training_gpu_0_memory_MB': 11123,
 'training_loss': 0.04453094533334176,
 'training_start_epoch': 0,
 'validation_accuracy': 0.8669928825622776,
 'validation_loss': 0.44221973419189453}
```

# BERT

## Random
```
{'best_epoch': 45,
 'best_validation_accuracy': 0.5511565836298933,
 'best_validation_loss': 0.6917074504105941,
 'epoch': 64,
 'peak_cpu_memory_MB': 5221.552,
 'peak_gpu_0_memory_MB': 11123,
 'training_accuracy': 0.5,
 'training_cpu_memory_MB': 5221.552,
 'training_duration': '0:05:42.279331',
 'training_epochs': 64,
 'training_gpu_0_memory_MB': 11123,
 'training_loss': 0.6954097072283427,
 'training_start_epoch': 0,
 'validation_accuracy': 0.5,
 'validation_loss': 0.6970267192177151}
```
## Pre-trained
```
{'best_epoch': 65,
 'best_validation_accuracy': 0.5542704626334519,
 'best_validation_loss': 0.6914208427719448,
 'epoch': 84,
 'peak_cpu_memory_MB': 5221.552,
 'peak_gpu_0_memory_MB': 11123,
 'training_accuracy': 0.5100267379679144,
 'training_cpu_memory_MB': 5221.552,
 'training_duration': '0:07:27.011528',
 'training_epochs': 84,
 'training_gpu_0_memory_MB': 11123,
 'training_loss': 0.6935030619303385,
 'training_start_epoch': 0,
 'validation_accuracy': 0.5431494661921709,
 'validation_loss': 0.6913978120555049}
 ```

 