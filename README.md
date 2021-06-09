# TrailerAffect Dataset

## Data Access
The [TrailerFaces](https://data.vision.ee.ethz.ch/zzhiwu/trailerFaces-tfrecords.zip) dataset is publicly available. (**Note that we tentatively release the tfrecord data to avoid the copyright issue.**)

  * The dataset contains approximately 200,000 individual clips of various facial expressions, where the faces are cropped with 256x256 resolution from about 6,000 high resolution movie trailers on YouTube. We convert them to tfrecord with resolutions range from 4x4 to 256x256. More about the data processing please refer to the ETH master thesis [Towards high resolution video generation (Arxiv)](https://arxiv.org/pdf/1810.02419.pdf). 
  

TrailerFaces sample (For video exmaples, please find 'trailerfaces_reals.avi' attached):
![Trailerfaces sample](https://github.com/musikisomorphie/swd/blob/master/progressive_training/trailer_faces_samples.png)


## Citation
* If you use the TrailerFace dataset for your research, please cite our papers.
```
@inproceedings{jqwu&zwhuang2019swgm,
  title={Sliced Wasserstein Generative Models},  
  author={Jiqing Wu, Zhiwu Huang, Dinesh Acharya, Wen Li, Janine Thoma, Danda Pani Paudel, Luc Van Gool},
  booktitle={Proceedings of the IEEE Conference on Computer Vision and Pattern Recognition},
  year={2019}  
}
@inproceedings{acharya2018towards,
  title={Towards High Resolution Video Generation with Progressive Growing of Sliced {Wasserstein GANs}},  
  author={Dinesh Acharya, Zhiwu Huang, Danda Pani Paudel, Luc Van Gool},
  booktitle={arXiv preprint arXiv:1810.02419},
  year={2018}  
}
