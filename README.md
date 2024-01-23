# ConceptThread
The code for paper "ConceptThread: Visualizing Threaded Concepts in MOOC Videos"

- **An interactive MOOC video-watching system.**
- **A threaded-based visualization for concept map**
- **(only works on Desktop Chrome / Edge)**

![fig_dataVis](https://raw.githubusercontent.com/Clover-yee/ConceptThread/main/src/assets/img/teaser-revised-minor.png)


> [**ConceptThread: Visualizing Threaded Concepts in MOOC Videos**](https://arxiv.org/abs/2401.11132)
> 
> Zhiguang Zhou, Li Ye, Lihong Cai, Lei Wang, Yigang Wang, Yongheng Wang, Wei Chen, and Yong Wang
>
> [[Paper](https://arxiv.org/abs/2401.11132) || [Video](https://youtu.be/4y2Y68n0JkA)]


## Abstract
Massive Open Online Courses (MOOCs) platforms are becoming increasingly popular in recent years. Online learners need to watch the whole course video on MOOC platforms to learn the underlying new knowledge, which is often tedious and time-consuming due to the lack of a quick overview of the covered knowledge and their structures. In this paper, we propose ConceptThread, a visual analytics approach to effectively show the concepts and the relations among them to facilitate effective online learning. Specifically, given that the majority of MOOC videos contain slides, we first leverage video processing and speech analysis techniques, including shot recognition, speech recognition and topic modeling, to extract core knowledge concepts and construct the hierarchical and temporal relations among them. Then, by using a metaphor of thread, we present a novel visualization to intuitively display the concepts based on video sequential flow, and enable learners to perform interactive visual exploration of concepts. We conducted a quantitative study, two case studies, and a user study to extensively evaluate ConceptThread. The results demonstrate the effectiveness and usability of ConceptThread in providing online learners with a quick understanding of the knowledge content of MOOC videos.

## Install
1. install `npm install`
2. `npm run serve` to run this application
3. `cd server-mongdb` and `node index` to run the server

## ToDo
- [ ] Improve the user interface:
    - [ ] Enable online edit mode
    - [ ] Add support panel function
- [ ] Release more cases data
- [ ] Release the system pipeline
- [ ] Better document the code

## Citation
```
@misc{zhou2024conceptthread,
      title={ConceptThread: Visualizing Threaded Concepts in MOOC Videos}, 
      author={Zhiguang Zhou and Li Ye and Lihong Cai and Lei Wang and Yigang Wang and Yongheng Wang and Wei Chen and Yong Wang},
      year={2024},
      eprint={2401.11132},
      archivePrefix={arXiv},
      primaryClass={cs.HC}
}
```
