# mt-mscoco
Machine Translated MSCOCO
  
captions_train2014_cn_translation.json : Chinese Translated Caption  
captions_train2014_jp_translation.json : Japanese Translated Caption  

Curretnly it's only for training data.

Json structure is like this.  
caption is the translated caption.  
id is the caption id in MSCOCO.  
image_id is the image id in MSCOCO. 
```
{
    "annotations": [
        {
            "caption": "一个很干净，装潢空浴室",
            "id": 48,
            "image_id": 318556
        },
        {
         ....
```

