# VISD
VISD generally stands for **Veirisimilar Image Synthesis Dataset**, which is proposed and created by @fnzhan in paper: [ECCV'18: Verisimilar image synthesis for accurate detection and recognition of texts in scenes](https://openaccess.thecvf.com/content_ECCV_2018/html/Fangneng_Zhan_Verisimilar_Image_Synthesis_ECCV_2018_paper.html). VISD uses semantic segmenation and saliency to locate a semantically sensitive region for texts, which is superior to the SynthText dataset by a large margin when tested on real world datasets.

### Dataset Download
Sample datasets for scene text detection and recognition as described in the [paper](https://openaccess.thecvf.com/content_ECCV_2018/html/Fangneng_Zhan_Verisimilar_Image_Synthesis_ECCV_2018_paper.html)

Detection:

1K: [dropbox](https://www.dropbox.com/s/5hirb8eal44ek4d/1K.tar.gz?dl=0)

10K: [dropbox](https://www.dropbox.com/s/fu49xa4vqxhtrwm/10K.tar.gz?dl=0)

### Annotation
The groundtruth are given in bounding box by 4 corner points like：
```
# img_id.txt
x0,y0
x1,y1
x2,y2
x3,y3
hard
```

### Citation
If you find this project helpful for your research, please cite the following paper:
```
@article{fnzhan2018,
  author  = {Fangneng Zhan, Shijian Lu and Chuhui Xue},
  title   = {Verisimilar Image Synthesis for Accurate Detection and Recognition of Texts in Scenes},
  journal = {ECCV},
  pages   = {257-273},
  year    = {2018}
  }
```

# CopyRight
The dataset is created and released totally by the original authors. I just collected the download link and related information for followers' using, as searching `VISD` in Google may not direct people to the correct dataset download link, whereas VISD is a commonly cited name in many famous text detection papers.
