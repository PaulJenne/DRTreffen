# DRTreffen

Found 165019 validated image filenames belonging to 2 classes.
Found 55006 validated image filenames belonging to 2 classes.
Found 57458 validated image filenames.
Train Labels:
                                             id label  \
0  f38a6374c348f90b587e046aac6079959adf3835.tif     0   
1  c18f2d887b7ae4f6742ee445113fa1aef383ed77.tif     1   
2  755db6279dae599ebb4d39a9123cce439965282d.tif     0   
3  bc3f0c64fb968ff4a8bd33af6971ecae77c75e08.tif     0   
4  068aba587a4950175d04c680d38943fd488d6a9d.tif     0   

                                          image_path  
0  /Users/pauljenne/Downloads/train/f38a6374c348f...  
1  /Users/pauljenne/Downloads/train/c18f2d887b7ae...  
2  /Users/pauljenne/Downloads/train/755db6279dae5...  
3  /Users/pauljenne/Downloads/train/bc3f0c64fb968...  
4  /Users/pauljenne/Downloads/train/068aba587a495...  

Sample Submission:
                                         id label
0  0b2ea2a822ad23fdb1b5dd26653da899fbd2c0d5     0
1  95596b92e5066c5c52466c90b69ff089b39f2737     0
2  248e6738860e2ebcf6258cdc1f32f299e0c76914     0
3  2c35657e312966e9294eac6841726ff3a748febf     0
4  145782eb7caa1c516acbe2eda34d9a3f31c41fd6     0

![image](https://github.com/PaulJenne/DRTreffen/assets/155363394/e861ed9b-92a6-43d0-939d-b3b74989a084)
![image](https://github.com/PaulJenne/DRTreffen/assets/155363394/cdad377b-329a-4068-bb87-df0638dddeda)
![image](https://github.com/PaulJenne/DRTreffen/assets/155363394/7445b292-3568-45c3-85a4-4a8d4a958766)

Epoch 1/15
5157/5157 [==============================] - 1526s 295ms/step - loss: 0.3242 - accuracy: 0.8683 - val_loss: 0.6068 - val_accuracy: 0.7666
Epoch 2/15
5157/5157 [==============================] - 1492s 289ms/step - loss: 0.2621 - accuracy: 0.8945 - val_loss: 0.6101 - val_accuracy: 0.7601
Epoch 3/15
5157/5157 [==============================] - 1496s 290ms/step - loss: 0.2238 - accuracy: 0.9123 - val_loss: 0.2963 - val_accuracy: 0.8742
Epoch 4/15
5157/5157 [==============================] - 1502s 291ms/step - loss: 0.2018 - accuracy: 0.9217 - val_loss: 0.2743 - val_accuracy: 0.8944
Epoch 5/15
5157/5157 [==============================] - 1519s 294ms/step - loss: 0.1873 - accuracy: 0.9292 - val_loss: 0.4135 - val_accuracy: 0.8134
Epoch 6/15
5157/5157 [==============================] - 1510s 293ms/step - loss: 0.1811 - accuracy: 0.9309 - val_loss: 0.4106 - val_accuracy: 0.8446
Epoch 7/15
5157/5157 [==============================] - 1503s 291ms/step - loss: 0.1709 - accuracy: 0.9347 - val_loss: 0.4185 - val_accuracy: 0.8489
Epoch 8/15
5157/5157 [==============================] - 1507s 292ms/step - loss: 0.1608 - accuracy: 0.9395 - val_loss: 0.2982 - val_accuracy: 0.8822
Epoch 9/15
5157/5157 [==============================] - 1506s 292ms/step - loss: 0.1586 - accuracy: 0.9402 - val_loss: 0.6052 - val_accuracy: 0.7873
Epoch 10/15
5157/5157 [==============================] - 1509s 293ms/step - loss: 0.1494 - accuracy: 0.9444 - val_loss: 0.1926 - val_accuracy: 0.9280
Epoch 11/15
5157/5157 [==============================] - 1510s 293ms/step - loss: 0.1450 - accuracy: 0.9462 - val_loss: 0.1613 - val_accuracy: 0.9395
Epoch 12/15
5157/5157 [==============================] - 1512s 293ms/step - loss: 0.1388 - accuracy: 0.9485 - val_loss: 0.7662 - val_accuracy: 0.7476
Epoch 13/15
5157/5157 [==============================] - 1521s 295ms/step - loss: 0.1352 - accuracy: 0.9506 - val_loss: 0.2314 - val_accuracy: 0.9054
Epoch 14/15
5157/5157 [==============================] - 1519s 294ms/step - loss: 0.1321 - accuracy: 0.9514 - val_loss: 0.7549 - val_accuracy: 0.7192
Epoch 15/15
5157/5157 [==============================] - 1520s 295ms/step - loss: 0.1296 - accuracy: 0.9517 - val_loss: 0.2343 - val_accuracy: 0.9092
5157/5157 [==============================] - 443s 86ms/step
1719/1719 [==============================] - 152s 88ms/step
Train ROC-AUC: 0.9696
Validation ROC-AUC: 0.9670


![image](https://github.com/PaulJenne/DRTreffen/assets/155363394/2b018d08-c49c-4a56-a344-7909d42a0aaa)
![image](https://github.com/PaulJenne/DRTreffen/assets/155363394/356eeb44-3ee6-410d-bbf8-99ece514ad56)


{
	"name": "AttributeError",
	"message": "'TransferModel' object has no attribute 'grad_cam'",
	"stack": "---------------------------------------------------------------------------
AttributeError                            Traceback (most recent call last)
Untitled-1.ipynb Zelle 1 line 3
    <a href='vscode-notebook-cell:Untitled-1.ipynb?jupyter-notebook#W1sdW50aXRsZWQ%3D?line=328'>329</a> plt.subplot(2, 3, i+1)
    <a href='vscode-notebook-cell:Untitled-1.ipynb?jupyter-notebook#W1sdW50aXRsZWQ%3D?line=329'>330</a> sample_image = sample_images[i]
--> <a href='vscode-notebook-cell:Untitled-1.ipynb?jupyter-notebook#W1sdW50aXRsZWQ%3D?line=330'>331</a> heatmap = transfer_model.grad_cam(sample_image, layer_name='conv5_block3_out')
    <a href='vscode-notebook-cell:Untitled-1.ipynb?jupyter-notebook#W1sdW50aXRsZWQ%3D?line=332'>333</a> # Display the original image with the heatmap
    <a href='vscode-notebook-cell:Untitled-1.ipynb?jupyter-notebook#W1sdW50aXRsZWQ%3D?line=333'>334</a> plt.imshow(sample_image)

AttributeError: 'TransferModel' object has no attribute 'grad_cam'"
}

![image](https://github.com/PaulJenne/DRTreffen/assets/155363394/164c0c43-8bf4-481b-be92-8d94403e1a77)
