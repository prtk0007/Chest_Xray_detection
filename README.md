# Chest_Xray_detection
Colab notebooks
Locations of Final notebooks:
#### For Binary Classification: (Normal vs Pneumonia)

1) VGG-16 - branch: exp_binary;  filename: project_ray_4_VGG16_precision_91.ipynb 
            pres-92 rec-95 f1-94 acc-92

2) VGG-19 -branch: exp_binary;  filename: project_ray_5_vgg19.ipynb (Latest commit 01ae17c on Feb 14)
           pres-91 rec-98 f1-93 acc-91
           
3) ResNet-50 -branch: exp_binary; filename:Project_ray_6_resnet.ipynb (Latest commit ef2b544 25 days ago)
           pres-88 rec-93 f1-90 acc-89
           
4) Inception-  branch: exp_binary; filename: Project_ray_7_Inception_acc_90_70_.ipynb(Latest commit 01b7fba 25 days ago)
             pres-91.5 rec-94 f1-93 acc-91 **but prev file has better results not commited here

5) Scartch CNN 1 (spatial conv) : branch: exp_binary; filename: scratch_cnn_1.ipynb (Latest commit f4553be 28 days ago)
                                pres-92 rec-98.7 f1-95 acc-94 (final consideration)

6)Scartch CNN 3 (seperable conv) : branch: exp_binary; filename:scratch_cnn_3.ipynb (Latest commit 65aa0af 22 days ago)
                                   pres-91 rec-96.2 f1-93.4 acc-91.5 (final Consideration)

#### For 3 class classification:(Covid vs Normal vs Pneumonia)

1) Scratch CNN 1 (spatial conv) : branch: Covid detect; Filename: scratch_cnn_1.ipynb (Latest commit f5ed828 25 days ago) 
                                    pres-95 rec-95 f1-95 acc-95 (final consideration)
                                    
2) VGG-16 (3 class) : branch: Covid detect; Filename: VGG16_3class_acc93.ipynb  (Latest commit a9d1516 on Mar 8)
                                   pres-94 rec-93 f1-93 acc-93.67 (final Considrarion)
                                   
### for Heatmap visualization and Prediction ###
1) All class predictor with random choose : branch: Main; Filename: Predictor_1class_2class_3class.ipynb  (Latest commit 41b693d)
                                                1)norm vs pneu 2) covid vs norm vs pneu (final consideration)

2) Heatmap visualization for pneumonia and normal : branch: Main; Filename:Heatmap_visualization_pneumonia.ipynb (Latest commit b299cc8)
                                                   1) we get single filter or feature map after maxpool and get heatmap on image
