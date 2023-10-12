### Data Augmentation
Why Data Augmentation and History
 - Overcome over-fitting
 - Make your model robust and better generalization to unseen data
 - Improved Localization
 - Create a regularization effect
 - Generate additional data with no effect - have transformations which are more suitable for target use cases

<img width="736" alt="aug" src="https://github.com/hafeezbabar/ComputerVision/assets/55141069/46a3dedd-b260-48d0-bab0-64deb17fe5d9">

## CutMIX 
 **CUTMIX Augmentation : Regularization Strategy to Train Strong Classifier with Localizable Features  (Published on 13 May 2019)**
 1. Regional dropout startegies have been proposed to enhance the performance of convolutional neural network classifiers.
 2. Proved to be effective for guiding the model to attend on less disriminative parts of objects (e.g. leg as opposed to head of a person), thereby letting the network generalized better and have better object localization capabilites.
 <img width="486" alt="cutmix" src="https://github.com/hafeezbabar/ComputerVision/assets/55141069/0a8161db-ece1-4ffe-bfdd-cb0e3eedb029">

 - Patches are cut and pasted among trainig images where the ground truth labels are also mixed proportionality to the area of the patches.
 - CutMix share the similarities wiht Mixup and cutout
   <img width="233" alt="equ" src="https://github.com/hafeezbabar/ComputerVision/assets/55141069/ecbc19de-483f-429f-a8da-8a2d9c830630">
   <img width="408" alt="image" src="https://github.com/hafeezbabar/ComputerVision/assets/55141069/0ed97f9f-a035-43d4-9f5d-6e6c669139f5">

## CUTMIX RESULTS
![image](https://github.com/hafeezbabar/ComputerVision/assets/55141069/65014c74-dcbd-464a-bb1a-664663518578)

## Impact of CUTMIX on Transfer Learning of Pretrained Model to other tasks, object Detection and Image Captioning.
![image](https://github.com/hafeezbabar/ComputerVision/assets/55141069/6c3d6e01-638a-4b82-826e-129d774d4856)

## CUTMIX Algorithm
![image](https://github.com/hafeezbabar/ComputerVision/assets/55141069/f4645454-dcff-4a3c-b2b1-20923e91b6ef)
![image](https://github.com/hafeezbabar/ComputerVision/assets/55141069/a845273f-a9a3-4cff-a67d-541cb05732b3)




