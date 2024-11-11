
## TO DO
- [ ] **Deep Attentional Multimodal Similarity Model (DAMSM)**

## Dataset
### Text
* [birds](https://drive.google.com/file/d/1O_LtUP9sch09QH3s_EBAgLEctBQ5JBSJ/view)

### Image
* [birds](http://www.vision.caltech.edu/visipedia/CUB-200-2011.html)


## Usage
```
├── dataset
   └── YOUR_DATASET_NAME
       ├── images
           ├── domain1 (domain folder)
               ├── xxx.jpg (domain1 image)
               ├── yyy.png
               ├── ...
           ├── domain2
               ├── aaa.jpg (domain2 image)
               ├── bbb.png
               ├── ...
           ├── domain3
           ├── ...
       ├── text
           ├── captions.pickle
           ├── filenames_train.pickle
           ├── filenames_test.pickle
```

### Train
```
python main.py --dataset birds --phase train
```

### Test
```
python main.py --dataset birds --phase test
```

