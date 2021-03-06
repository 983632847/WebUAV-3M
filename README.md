# WebUAV-3M: A Benchmark Unveiling the Power of Million-Scale Deep UAV Tracking [[Paper Link](https://arxiv.org/abs/2201.07425)]
### Abstract

In this work, we contribute a new million-scale Unmanned Aerial Vehicle (UAV) tracking benchmark, called WebUAV-3M. Firstly, we collect 4,485 videos with more than 3M frames from the Internet. Then, an efficient and scalable Semi-Automatic Target Annotation (SATA) pipeline is devised to label the tremendous WebUAV-3M in every frame. To the best of our knowledge, the densely bounding box annotated WebUAV-3M is by far the largest public UAV tracking benchmark. We expect to pave the way for the follow-up study in the UAV tracking by establishing a million-scale annotated benchmark covering a wide range of target categories. Moreover, considering the close connections among visual appearance, natural language and audio, we enrich WebUAV-3M by providing natural language specification and audio description, encouraging the exploration of natural language features and audio cues for UAV tracking. Equipped with this benchmark, we delve into million-scale deep UAV tracking problems, aiming to provide the community with a dedicated large-scale benchmark for training deep UAV trackers and evaluating UAV tracking approaches. Extensive experiments on WebUAV-3M demonstrate that there is still a big room for robust deep UAV tracking improvements. The dataset, toolkits and baseline results will be available at this page.

![image](https://github.com/983632847/WebUAV-3M/blob/main/imgs/Representative_Videos.png)


### TODO
- [ ] Evaluation Toolkits 
- [ ] Video Sequences of WebUAV-3M Dataset
- [ ] Language and Audio Annotations
- [ ] Baseline Results

### WebUAV-3M dataset

Download the whole dataset through Google drive: [WebUAV-3M](https://docs.google.com/forms/d/e/1FAIpQLSe5Usq9VUSGjKollBCI1heln_o6u4SuiMcBRn_FNqp4v2d0Kw/viewform?usp=pp_url)

Download the whole dataset through Baidu Pan: [WebUAV-3M](https://github.com/983632847/WebUAV-3M)

### Evaluation toolkits

Download the Evaluation Toolkits through Google drive: [Evaluation Toolkits](https://docs.google.com/forms/d/e/1FAIpQLSe5Usq9VUSGjKollBCI1heln_o6u4SuiMcBRn_FNqp4v2d0Kw/viewform?usp=pp_url)

Download the Evaluation Toolkits through Baidu Pan: [Evaluation Toolkits](https://github.com/983632847/WebUAV-3M)

### Baseline results

Download the Baseline Results through Google drive: [Baseline Results](https://docs.google.com/forms/d/e/1FAIpQLSe5Usq9VUSGjKollBCI1heln_o6u4SuiMcBRn_FNqp4v2d0Kw/viewform?usp=pp_url)

Download the Baseline Results through Baidu Pan: [Baseline Results](https://github.com/983632847/WebUAV-3M)


### Environment

The experiments are implemented using PyTorch or MATLAB with an Intel (R) Xeon (R) Gold 6230R CPU @ 2.10GHz and three NVIDIA RTX A5000 GPUs on an Ubuntu 18.04 server.


### Citation

If you find the dataset and toolkits useful in your research, please consider citing:

    @inproceedings{WebUAV_3M_2022,
        title={WebUAV-3M: A Benchmark Unveiling the Power of Million-Scale Deep UAV Tracking},
        author = {Chunhui Zhang, and Guanjie Huang, and Li Liu, and Shan Huang, and Yinan Yang, and Yuxuan Zhang, and Xiang Wan, and Shiming Ge},
        journal = {arXiv:2201.07425},
        year = {2022}
      }


### Acknowledgments
Thanks for the great [[GOT-10k toolkit](https://github.com/got-10k/toolkit)]

