# BMVOS

This is the official PyTorch implementation of our paper:

> **Pixel-Level Bijective Matching for Video Object Segmentation**, *WACV'22*\
> [Suhwan Cho](https://github.com/suhwan-cho), Heansung Lee, Minjung Kim, Sungjun Jang, Sangyoun Lee

URL: [[open access]](https://openaccess.thecvf.com/content/WACV2022/html/Cho_Pixel-Level_Bijective_Matching_for_Video_Object_Segmentation_WACV_2022_paper.html) [[arXiv]](https://arxiv.org/abs/2110.01644)\
PDF: [[open access]](https://openaccess.thecvf.com/content/WACV2022/papers/Cho_Pixel-Level_Bijective_Matching_for_Video_Object_Segmentation_WACV_2022_paper.pdf) [[arXiv]](https://arxiv.org/pdf/2110.01644.pdf)

```
@inproceedings{BMVOS,
  title={Pixel-Level Bijective Matching for Video Object Segmentation},
  author={Cho, Suhwan and Lee, Heansung and Kim, Minjung and Jang, Sungjun and Lee, Sangyoun},
  booktitle={Proceedings of the IEEE/CVF Winter Conference on Applications of Computer Vision},
  pages={129--138},
  year={2022}
}
```


## Preparation
1\. Download [DAVIS](https://davischallenge.org/davis2017/code.html) for network main training and testing.

2\. Download [YouTube-VOS](https://competitions.codalab.org/competitions/19544#participate-get-data) for network main training and testing.

3\. Replace dataset paths in *"run.py"* file with your dataset paths.


## Training
Please follow the instructions in [EMVOS](https://github.com/suhwan-cho/EMVOS).


## Testing
1\. Make sure the pre-trained models are in your *"trained_model"* folder.

2\. Select a pre-trained model and testing datasets in *"run.py"* file.

3\. Run **BMVOS** testing!!
```
python run.py
```

4\. (Optional) Download [pre-computed results](https://drive.google.com/file/d/1AokjFfA8Gb65dIQ3T3V4lM5CuOfKuIqm/view?usp=sharing).



## Note
Code and models are only available for non-commercial research purposes.

If you have any questions, please feel free to contact me :)
```
E-mail: chosuhwan@yonsei.ac.kr
```
