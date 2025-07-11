# Iterative Event-based Motion Segmentation by Variational Contrast Maximization

The official repository for [**Iterative Event-based Motion Segmentation by Variational Contrast Maximization**](https://arxiv.org/abs/2504.18447),
CVPR 2025 Workshop on Event Vision,
by Ryo Yamaki, [Shintaro Shiba](http://shibashintaro.com/), [Guillermo Callego](https://sites.google.com/view/guillermogallego), and [Yoshimitsu Aoki](https://aoki-medialab.jp/aokiyoshimitsu-en/).


If you use this work in your research, please cite it (see also [here](#citation)):

```bibtex
@Article{Yamaki25cvprw,
  author        = {Ryo Yamaki and Shintaro Shiba and Guillermo Gallego and Yoshimitsu Aoki},
  title         = {Iterative Event-based Motion Segmentation by Variational Contrast Maximization},
  journal       = {CVPR Workshop on Event Vision},
  year          = 2025,
}
```


<p align="center">
  <a href="https://arxiv.org/pdf/2504.18447" target="_blank">
    <img src="https://img.shields.io/badge/Paper-arXiv%3A2504.18447-b31b1b.svg?logo=arxiv&logoColor=white" alt="arXiv Paper">
  </a>
</p>

## 📄 Abstract
Event cameras provide rich signals that are suitable for motion estimation since they respond to changes in the scene. As any visual changes in the scene produce event data, it is paramount to classify the data into different motions (i.e., motion segmentation), which is useful for various tasks such as object detection and visual servoing. We propose an iterative motion segmentation method, by classifying events into background (e.g., dominant motion hypothesis) and foreground (independent motion residuals), thus extending the Contrast Maximization framework. Experimental results demonstrate that the proposed method successfully classifies event clusters both for public and selfrecorded datasets, producing sharp, motion-compensated edge-like images. The proposed method achieves state-ofthe-art accuracy on moving object detection benchmarks with an improvement of over 30%, and demonstrates its possibility of applying to more complex and noisy realworld scenes. We hope this work broadens the sensitivity of Contrast Maximization with respect to both motion parameters and input events, thus contributing to theoretical advancements in event-based motion segmentation estimation.

## ▶️ Explanation Video
<p align="center">
  <a href="https://www.youtube.com/watch?v=D4s-mj_h5oQ">
    <img src="https://img.youtube.com/vi/D4s-mj_h5oQ/0.jpg" alt="Method" width="560">
  </a>
</p>

-------
# Additional Resources

* [Research page (Keio University, Aoki Media Lab)](https://aoki-medialab.jp/home-en/)
* [Research page (TU Berlin, RIP lab)](https://sites.google.com/view/guillermogallego/research/event-based-vision)
* [Survey paper](http://rpg.ifi.uzh.ch/docs/EventVisionSurvey.pdf)
* [List of Resources](https://github.com/uzh-rpg/event-based_vision_resources)
