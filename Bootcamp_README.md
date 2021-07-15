[![Contributors][contributors-shield]][contributors-url]
[![Forks][forks-shield]][forks-url]
[![Stargazers][stars-shield]][stars-url]

<!-- PROJECT LOGO -->
<br />

<p align="center">
  <a href="https://github.com/milvus-io/bootcamp">
    <img src="images/logo.png" alt="Logo">
  </a>
  <p align="center">
    Bootcamp for Milvus, including benchmarking, solutions, and application scenarios.
    <br />
    <br />
    <a href="https://github.com/milvus-io/bootcamp "Demo</a>
    ·
    <a href="https://github.com/milvus-io/bootcamp/issues">Report Bug</a>
    ·
    <a href="https://github.com/milvus-io/bootcamp/issues">Request Feature</a>
  </p>



<!-- TABLE OF CONTENTS -->
<details open="open">
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#mega-about-milvus-bootcamp">About Milvus Bootcamp</a>
    </li>
    <li>
      <a href="#mag-benchmark-tests">Benchmark Tests</a>
      <ul>
        <li><a href="#dart-1-million-benchmark-testing">1 million benchmark testing</a></li>
        <li><a href="#art-100-million-benchmark-testing">100 million benchmark testing</a></li>
      </ul>
    </li>
    <li><a href="#pencil-solutions">Solutions</a></li>
      <ul>
        <li><a href="#clapper-live-demo">Live demo</a></li>
        <li><a href="#fries-try-it">Have a try</a></li>
        <li><a href="#icecream-run-in-local">Run locally</a></li>
      </ul>
    <li><a href="#collaborations">Collaborations</a></li>
    <li><a href="#fire-supports">Supports</a></li>
    <li><a href="#contributors">All contributors</a></li>
  </ol>
</details>


<!-- ABOUT MILVUS Bootcamp -->

## :mega: About Milvus Bootcamp
Milvus Bootcamp is designed to expose users to both the simplicity and depth of [**Milvus**](https://milvus.io/) vector database. Discover how to run **benchmark tests** as well as build similarity search applications spanning **chatbots**, **recommendation systems**, **reverse image search**, **molecular search**, **video search**, **audio saerch**, and much more.

<!-- BENCHMARK TESTS-->

## :mag: Benchmark Tests
The [Benchmark Test](https://github.com/milvus-io/bootcamp/tree/master/benchmark_test) contains 1 million and 100 million vector tests that indicate how your system will react to differently sized datasets.
 ### :dart: [1 million benchmark testing](https://github.com/milvus-io/bootcamp/blob/master/benchmark_test/lab1_sift1b_1m.md)

We extract one million vector data from [SIFT1B Dataset](http://corpus-texmex.irisa.fr/) for **accuracy test** and **performance test**. Through [this test](https://github.com/milvus-io/bootcamp/blob/master/benchmark_test/lab1_sift1b_1m.md), you can learn the basic operations of Milvus, including creating collection, inserting data, building indexes, searching, etc.

 ### :art: [100 million benchmark testing](https://github.com/milvus-io/bootcamp/blob/master/benchmark_test/lab2_sift1b_100m.md)

We extract 100 million vector data from [SIFT1B Dataset](http://corpus-texmex.irisa.fr/) for **accuracy test** and **performance test**. Through [this test](https://github.com/milvus-io/bootcamp/blob/master/benchmark_test/lab2_sift1b_100m.md), you can learn the basic operations of Milvus, including creating collection, inserting data, building indexes, searching, etc.

<!--ALL SOLUTIONS-->

## :pencil: Solution

### :clapper: [Live demo](https://zilliz.com/milvus-demos?isZilliz=true)

[Live demo](https://zilliz.com/milvus-demos?isZilliz=true)

### :fries: [Have a Try](https://zilliz.com/solutions)

 [Have a Try](https://zilliz.com/solutions)

### :icecream: Run locally

| Solutions| Have fun with it<img width=500/>                           | Article                                                      | Video                                                  |
| ------------------------------------------------------------ | :----------------------------------------------------------- | ------------------------------------------------------------ | ------------------------------------------------------ |
| [Reverse Image Search](./solutions/reverse_image_search)<br />Build a reverse image search system using Milvus paired with YOLOv3 for object detection and ResNet-50 for feature extraction. | [Jupyter notebook](solutions/reverse_image_search/reverse_image_search.ipynb)<br />[Quick deploy](solutions/reverse_image_search/quick_deploy) | [Chinese](https://mp.weixin.qq.com/s/7lNuaI-eL3lsQlOq0eolkw)<br />[English](https://blog.milvus.io/milvus-application-1-building-a-reverse-image-search-system-based-on-milvus-and-vgg-aed4788dd1ea) | [Chinese](https://www.bilibili.com/video/BV1SN411o79n) |
| [Question Answering System](./solutions/question_answering_system)<br />Build an intelligent chatbot using Milvus and the BERT model for natural language processing (NLP). | [Jupyter notebook](solutions/question_answering_system/question_answering.ipynb)<br />[Quick deploy](solutions/question_answering_system/quick_deploy) | [Chinese](https://mp.weixin.qq.com/s/BZp4CMv2yuVb0oEyuDKNkw)<br />[English](https://medium.com/voice-tech-podcast/building-an-intelligent-qa-system-with-nlp-and-milvus-75b496702490) |                                                        |
| [Recommendation System](./solutions/recommendation_system)   | [Jupyter notebook](solutions/recommendation_system/recommendation_system.ipynb)<br />[Quick deploy](solutions/recommendation_system/quick_deploy) | [Chinese](https://mp.weixin.qq.com/s/nAr45u-ruvhWQ8LcVxbhOg) |                                                        |
| [Molecular Similarity Search](./solutions/molecular_similarity_search) | [Jupyter notebook](solutions/molecular_similarity_search/molecular_search.ipynb)<br />[Quick deploy](solutions/molecular_similarity_search/quick_deploy) | [Chinese](https://mp.weixin.qq.com/s/ZIH_zYltT6aJNQYMhOSsAg) |                                                        |
| [Video Similarity Search](./solutions/video_similarity_search) | [Jupyter notebook](solutions/video_similarity_search/video_similarity_search.ipynb)<br />[Quick deploy](solutions/video_similarity_search/quick_deploy) | [Chinese](https://mp.weixin.qq.com/s/DOfiGP5BG_9sD7zZair4ew)<br />[English](https://blog.milvus.io/4-steps-to-building-a-video-search-system-5a3ced633308) |                                                        |
| [Audio Similarity Search](./solutions/audio_similarity_search) | [Jupyter notebook](solutions/audio_similarity_search/audio_similarity_search.ipynb)<br />[Quick deploy](solutions/video_similarity_search/quick_deploy) | [Chinese](https://mp.weixin.qq.com/s/PJfO71YOTW2gXO6SL-OOuA) |                                                        |
| [Text Search Engine](./solutions/text_search_engine)         | [Jupyter notebook](solutions/text_search_engine/text_search_engine.ipynb)<br />[Quick deploy](solutions/text_search_engine/quick_deploy) | [Chinese](https://mp.weixin.qq.com/s/OUrBSCqnLuh9btyK3SxWgQ) | [Chinese](https://www.bilibili.com/video/BV1Xi4y1E7Tb) |


Name&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;  | Value
-------|-------------------
`Value-One` | Long explanation
`Value-Two` | Long explanation
`etc` | Long explanation


|Name|Value|
|----|---------|
|<img width=1000/>|<img width=500/>|

<!--THE COLLABORATIONS-->

## :two_women_holding_hands: Collaborations



## :fire: Supports



## :heart: All contributors











<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->

[contributors-shield]: https://img.shields.io/github/contributors/github_username/repo.svg?style=for-the-badge
[contributors-url]: https://github.com/milvus-io/bootcamp/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/github_username/repo.svg?style=for-the-badge
[forks-url]: https://github.com/milvus-io/bootcamp/network/members
[stars-shield]: https://img.shields.io/github/stars/github_username/repo.svg?style=for-the-badge
[stars-url]: https://github.com/milvus-io/bootcamp/stargazers

