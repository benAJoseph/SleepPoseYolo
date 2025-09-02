# SleepPoseYolo

# Dataset used
Training: https://universe.roboflow.com/sam-vcqdz/object-detection-ikxzz/dataset/1   
Testing: https://universe.roboflow.com/thesis-dx8vu/sleepig-position/dataset/2

# Results:
Training: 
```
Class     Images  Instances      Box(P          R      mAP50  mAP50-95): 100% 29/29 [00:10<00:00,  2.78it/s]
                   all        903        903      0.946      0.877      0.945      0.654
                 Prone         97         97      0.919      0.866      0.907      0.592
                Supine        299        299      0.934      0.899      0.955      0.658
               To-Left        281        281      0.977      0.879      0.964      0.699
              To-Right        226        226      0.956      0.864      0.954      0.668
```

Testing:
```
Class     Images  Instances      Box(P          R      mAP50  mAP50-95): 100% 3/3 [00:01<00:00,  2.11it/s]
                   all         42         42      0.467          1      0.488      0.373
                 Prone          1          1     0.0233          1     0.0231     0.0162
                Supine         41         41      0.911          1      0.952       0.73
```
