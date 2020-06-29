# -DataMining

'训练结果'

(base) C:\Users\###\Desktop\新版代码与数据>python train.py --train --config cnn.ini
args:  Namespace(config='cnn.ini', test=True, train=True, verbose=False)
False
TextCNN(
  (word_embedding): Embedding(3475, 256)
  (convs): ModuleList(
    (0): Conv2d(1, 16, kernel_size=(2, 256), stride=(1, 1))
    (1): Conv2d(1, 16, kernel_size=(3, 256), stride=(1, 1))
    (2): Conv2d(1, 16, kernel_size=(4, 256), stride=(1, 1))
  )
  (dropout): Dropout(p=0.5, inplace=False)
  (fc): Linear(in_features=48, out_features=15, bias=True)
)
epoch 1 [0/1668], valid loss: 14783.91
epoch 1 [20/1668], valid loss: 13505.89
epoch 1 [40/1668], valid loss: 13145.82
epoch 1 [60/1668], valid loss: 12986.81
epoch 1 [80/1668], valid loss: 12847.90
epoch 1 [100/1668], valid loss: 12713.81
epoch 1 [120/1668], valid loss: 12593.03
epoch 1 [140/1668], valid loss: 12489.64
epoch 1 [160/1668], valid loss: 12381.40
epoch 1 [180/1668], valid loss: 12250.77
epoch 1 [200/1668], valid loss: 12130.89
epoch 1 [220/1668], valid loss: 12006.50
epoch 1 [240/1668], valid loss: 11907.39
epoch 1 [260/1668], valid loss: 11818.63
epoch 1 [280/1668], valid loss: 11755.94
epoch 1 [300/1668], valid loss: 11662.78
epoch 1 [320/1668], valid loss: 11588.75
epoch 1 [340/1668], valid loss: 11508.68
epoch 1 [360/1668], valid loss: 11437.18
epoch 1 [380/1668], valid loss: 11390.20
epoch 1 [400/1668], valid loss: 11331.11
epoch 1 [420/1668], valid loss: 11253.42
epoch 1 [440/1668], valid loss: 11181.61
epoch 1 [460/1668], valid loss: 11136.77
epoch 1 [480/1668], valid loss: 11089.73
epoch 1 [500/1668], valid loss: 11038.34
epoch 1 [520/1668], valid loss: 10970.49
epoch 1 [540/1668], valid loss: 10916.26
epoch 1 [560/1668], valid loss: 10873.96
epoch 1 [580/1668], valid loss: 10830.02
epoch 1 [600/1668], valid loss: 10792.85
epoch 1 [620/1668], valid loss: 10752.68
epoch 1 [640/1668], valid loss: 10710.04
epoch 1 [660/1668], valid loss: 10664.70
epoch 1 [680/1668], valid loss: 10597.33
epoch 1 [700/1668], valid loss: 10563.00
epoch 1 [720/1668], valid loss: 10517.08
epoch 1 [740/1668], valid loss: 10484.64
epoch 1 [760/1668], valid loss: 10469.71
epoch 1 [780/1668], valid loss: 10449.42
epoch 1 [800/1668], valid loss: 10400.95
epoch 1 [820/1668], valid loss: 10359.91
epoch 1 [840/1668], valid loss: 10318.32
epoch 1 [860/1668], valid loss: 10279.08
epoch 1 [880/1668], valid loss: 10233.58
epoch 1 [900/1668], valid loss: 10197.62
epoch 1 [920/1668], valid loss: 10177.00
epoch 1 [940/1668], valid loss: 10147.59
epoch 1 [960/1668], valid loss: 10113.99
epoch 1 [980/1668], valid loss: 10064.16
epoch 1 [1000/1668], valid loss: 10069.07
epoch 1 [1020/1668], valid loss: 10046.19
epoch 1 [1040/1668], valid loss: 10030.45
epoch 1 [1060/1668], valid loss: 10006.70
epoch 1 [1080/1668], valid loss: 9983.32
epoch 1 [1100/1668], valid loss: 9963.31
epoch 1 [1120/1668], valid loss: 9921.14
epoch 1 [1140/1668], valid loss: 9877.69
epoch 1 [1160/1668], valid loss: 9869.91
epoch 1 [1180/1668], valid loss: 9866.46
epoch 1 [1200/1668], valid loss: 9842.67
epoch 1 [1220/1668], valid loss: 9808.55
epoch 1 [1240/1668], valid loss: 9773.13
epoch 1 [1260/1668], valid loss: 9747.65
epoch 1 [1280/1668], valid loss: 9723.39
epoch 1 [1300/1668], valid loss: 9707.15
epoch 1 [1320/1668], valid loss: 9694.13
epoch 1 [1340/1668], valid loss: 9687.16
epoch 1 [1360/1668], valid loss: 9673.37
epoch 1 [1380/1668], valid loss: 9652.29
epoch 1 [1400/1668], valid loss: 9638.83
epoch 1 [1420/1668], valid loss: 9633.16
epoch 1 [1440/1668], valid loss: 9622.24
epoch 1 [1460/1668], valid loss: 9593.53
epoch 1 [1480/1668], valid loss: 9559.98
epoch 1 [1500/1668], valid loss: 9552.53
epoch 1 [1520/1668], valid loss: 9531.85
epoch 1 [1540/1668], valid loss: 9505.11
epoch 1 [1560/1668], valid loss: 9482.59
epoch 1 [1580/1668], valid loss: 9462.30
epoch 1 [1600/1668], valid loss: 9432.90
epoch 1 [1620/1668], valid loss: 9428.57
epoch 1 [1640/1668], valid loss: 9433.76
epoch 1 [1660/1668], valid loss: 9425.77


'测试结果'

(base) C:\Users\###\Desktop\新版代码与数据>python test.py --config cnn.ini
args:  Namespace(config='cnn.ini', test=True, train=False, verbose=False)
False
f1_score:36.3194%
precision_score:40.4859%
recall_score:39.8389%
acc_score:43.7000%
