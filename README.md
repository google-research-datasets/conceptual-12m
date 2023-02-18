# Conceptual 12M

<p align="center">
  <img width="192" height="312" src="/images/cc12m_1.jpg">
  <img width="192" height="312" src="/images/cc12m_2.jpg">
</p>

We introduce the Conceptual 12M (CC12M), a dataset with ~12 million image-text pairs meant to be used for vision-and-language pre-training.
It is larger and covers a much more diverse set of visual concepts than [the Conceptual Captions](https://github.com/google-research-datasets/conceptual-captions) (CC3M), a dataset that is widely used for pre-training and end-to-end training of image captioning models.
Check our [paper](https://arxiv.org/abs/2102.08981) for further details.

## Download
Click [here](https://storage.googleapis.com/conceptual_12m/cc12m.tsv) to download (2.5GB)


**Format (.tsv)**
<div class="highlight highlight-source-shell"><pre>
[image_url_1]\t[caption_1]
[image_url_2]\t[caption_2]
[image_url_3]\t[caption_3]
…
[image_url_N]\t[caption_N]
</pre></div>

### Hashcodes
Click [here](https://storage.googleapis.com/cc_hashes/cc12m.tsv.gz)
**Format (.tsv)**
[image_url_n]\t[SHA256]\t[MD5]

## Cite

If you use this dataset in your research, please cite:

Soravit Changpinyo, Piyush Sharma, Nan Ding, Radu Soricut.
[Conceptual 12M: Pushing Web-Scale Image-Text Pre-Training To Recognize Long-Tail Visual Concepts](https://arxiv.org/abs/2102.08981).
CVPR 2021.

<div class="highlight highlight-source-shell"><pre>
@inproceedings{changpinyo2021cc12m,
  title = {{Conceptual 12M}: Pushing Web-Scale Image-Text Pre-Training To Recognize Long-Tail Visual Concepts},
  author = {Changpinyo, Soravit and Sharma, Piyush and Ding, Nan and Soricut, Radu},
  booktitle = {CVPR},
  year = {2021},
}
</pre></div>

## FAQs

**Q1**: Can you provide image pixels?

**A1**: We do not own any of the images in the dataset and hence cannot legally provide them to you. The owner of an image can choose to delete it at anytime, in which case the image will no longer be available. Due to this, unfortunately, some images in the dataset will be lost over time, and we are unable to help with this issue.
###

**Q2**: Is it normal that a subset of images cannot be retrieved from the provided URLs?

**A2**: Yes. See Q1.

**Q3**: Is CC12M an “expanded” CC3M?

**A3**: No, CC12M is on purpose designed for vision-and-language pre-training, and meant to be disjoint from CC3M. CC3M is cleaner and more appropriate for fine-tuning, but can be used in conjunction with CC12M for pre-training, as illustrated in our paper. Coincidentally, their intersection is found to be non-zero — approximately 63K URLs.

## Contact Us

If you have a question not provided in the FAQs above, please create an issue in this repository. 

If you would like to share feedback or report concerns, please email us at conceptual-captions@google.com.

