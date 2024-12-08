---
title: About
---

Dang-Khanh Nguyen
============

I am a software engineer and a philomath. Check my coding activities at <a
    id="cy-effective-github-url"
    class="underline"
     href="https://github.com/khanhnd185"
     target="orcid.widget"
     rel="me noopener noreferrer"
     style="vertical-align: top">
     <img
        src="https://cdn-icons-png.flaticon.com/512/25/25231.png"
        style="width: 1em; margin-inline-start: 0.5em"
        alt="ORCID iD icon"/>
    </a>.
<br>
My research record can be found at <a
    id="cy-effective-orcid-url"
    class="underline"
     href="https://orcid.org/0000-0002-7459-7095"
     target="orcid.widget"
     rel="me noopener noreferrer"
     style="vertical-align: top">
     <img
        src="https://orcid.org/sites/default/files/images/orcid_16x16.png"
        style="width: 1em; margin-inline-start: 0.5em"
        alt="ORCID iD icon"/>
    </a> or <a
    id="cy-effective-scholar-url"
    class="underline"
     href="https://scholar.google.com/citations?user=5AdBep8AAAAJ"
     target="orcid.widget"
     rel="me noopener noreferrer"
     style="vertical-align: top">
     <img
        src="https://upload.wikimedia.org/wikipedia/commons/c/c7/Google_Scholar_logo.svg"
        style="width: 1em; margin-inline-start: 0.5em"
        alt="Google Scholar icon"/>
    </a>.

Education
---------

2022-2023
:   **Master Student, Department of AI Convergence; [Chonnam National University](https://international.jnu.ac.kr/) (Gwangju, South Korea)**
    * Graduatded in Feb 2024.

2014-2018
:   **Bachelor of Engineering, Electrical and Electronic Engineering, [Ho Chi Minh University of Technology](https://hcmut.edu.vn/en) (HCMC, Vietnam)**
    * Honor Program of Telecommunication Engineering.

Experience
----------

**Senior Software Engineer at [Aim Futrure](https://aimfuture.ai/en/)**
:   2024 - Present
    * Design and implement SDK compiling well-known computer vision models (from various frameworks: Keras, Tensorflow, Torch) to hardware-specific runtime instructions.
    * Hardware-oriented optimize DNN operations for efficient and effective computation on AI accelerator. Decompose these operations into smaller elements so that they can be executed in parallel in order to hide the memory latency and maximize the arithmetic intensity.
    * Exploit the power of our AI accelerator to provide faster implementations for inferencing deep neural networks.

**Researcher at [Smart Computing Lab](http://sclab.jnu.ac.kr/)**
:   2022 - 2023
    * My research topic is video emotion recognition, multimodal learning, and multimodal fusion.
    * Investigate and implement machine learning, deep learning model using Pytorch framework.
    * My publications and competitions that I joined are listed in the next section.

**Software Engineer at [Viettel High Technology Company](https://viettelhightech.vn/)**
:   2020 - 2021
    * Investigate [RFC](https://en.wikipedia.org/wiki/Request_for_Comments) documents to implement network protocol. Develop L2/L3  Protocol for Network Device (Switch/Router) using C programming language.
    * Some protocols that I have developed and tested: [OMCI](https://en.wikipedia.org/wiki/G.988), [SMNP](https://www.rfc-editor.org/rfc/rfc3413.html).
    * Use GDB for debugging and git to control version of team's source code.
    * Utilize Multi-thread, Inter-process communication to improve response time between devices.
    * Simulate behavior of Intermediary network device for boundary-value analysis and stress test of Gateway device.
    * Setup network topology to evaluate the behavior of the protocols on prototype device.

**Software Engineer at [Renesas Design Vietnam](http://vietnam.renesas.com/)**
:   2018 - 2019
    * Develop IP modules for virtual MCU/SoC using C++ programming language and [SystemC](https://systemc.org/overview/systemc/).
    * Some modules that I have developed and tested: Interrupt controller, Random Number Generator.
    * Embed Python APIs in C++ module. Use Python to create test script and unit test environment.
    * Guarantee code coverage >95% using GCOV. Track and resolve 100% leaking memory issues with Valgrind.
    * Work in Linux Environment, use Makefile to control building process.


Publications
--------------------

[Multiple Facial Reaction Generation Using Gaussian Mixture of Models and Multimodal Bottleneck Transformer](https://ieeexplore.ieee.org/document/10581901)
:   In Proceeding of [IEEE 18th International Conference on Automatic Face and Gesture Recognition (2024)](https://fg2024.ieee-biometrics.org/)

    * The paper introduces my solution in the [The Second REACT Challenge@IEEE FG24](https://sites.google.com/cam.ac.uk/react2024/home). We achieve top 3 in the Facial Reaction Generation.
    * Our proposed approach incorporates the Multimodal Bottleneck Token mechanism to capture interactions between acoustic and visual speaker features and utilizes the Variational Auto-encoder framework to generate latent representations of multiple listener reactions. Additionally, we employ Gaussian Mixture Models to enhance the generative capabilities of the Autoencoder.
    * Source code [here](https://github.com/khanhnd185/MBTReact).

[A Transformer-based Approach to Video Frame-level Prediction in Affective Behavior Analysis In-the-wild](https://arxiv.org/abs/2303.09293)
:   In Proceeding of [11th International Conference on Big Data Applications and Services](http://www.kbigdata.or.kr/bigdas2023/index.html)

    * The paper introduces my solution in the [CVPR 2023: 5th Workshop and Competition on Affective Behavior Analysis in-the-wild](https://ibug.doc.ic.ac.uk/resources/cvpr-2023-5th-abaw/). We achieved top 9 in the Multi-task Learning Challange.
    * We used a pre-trained EfficientNet to extract facial spatial features and a Transformer to extract temporal features. The sequence of embeddings are then used to generate frame-wise emotional predictions for a video.
    * Source code [here](https://github.com/khanhnd185/ABAW5).

[Multimodal Transformer for Automatic Depression Estimation System](https://iwfcv2023.github.io/assets/Poster/P2-7%20Multimodal%20Transformer%20for%20Automatic%20Depression%20Estimation%20System_Khanh%20Nguyen.pdf)
:   In Proceeding of [The 29th International Workshop on Frontiers of Computer Vision](https://iwfcv2023.github.io/)
    * We reviewed the transformer-based fusion methods of [Xu](https://arxiv.org/abs/2206.06488) for Depression recognition.
    * We introduce a new fusion transformer and get good performance on [D-Vlog Benchmark](https://ojs.aaai.org/index.php/AAAI/article/view/21483).
    * Source code [here](https://github.com/khanhnd185/Transformer-fusion).

[Analyzing Context and Speaker Memory using Pretrained Language Model for Emotion Recognition in Korean Conversation task](http://netkers5.cafe24.com/bigdas2022/assets/program/BIGDAS2022%20Proceeding.pdf)
:   In Proceeding of [10th International Conference on Big Data Applications and Services](http://kbigdata.or.kr/bigdas2022/)
    * We achieve 4th Prize in the [4th Emotion Recognition in Korean Conversation Competition](https://sites.google.com/view/kerc2022/).
    * We use pre-trained language model to analyze the conversation context and the speakers' memory to handle the ERC task.
    * Source code [here](https://github.com/khanhnd185/KERC22).

[Fine-tuning Wav2vec for Vocal-burst Emotion Recognition](https://arxiv.org/abs/2210.00263)
:   In Proceeding of [ACII Affective Vocal Bursts Workshop and Competition 2022 (A-VB)](https://arxiv.org/abs/2210.15754)
    * We utilize pre-trained Wav2vec to handle the Emotion Recognition from Vocal-burst. We achieve top 2 in A-VB Culture task.
    * The [competion](https://www.competitions.hume.ai/avb2022) is organized by [HumeAI](https://hume.ai/) to explore a under-studied indicator of emotion, the non-verbal sound of human.
    * Source code [here](https://github.com/khanhnd185/AVB2022).

[Affective Behavior Analysis using Action Unit Relation Graph and Multi-task Cross Attention](https://arxiv.org/abs/2207.10293)
:   In Proceeding of [ECCV Workshop (2022)](https://link.springer.com/chapter/10.1007/978-3-031-25075-0_10)

    * The paper introduces my solution in the [4th Workshop and Competition on Affective Behavior Analysis in-the-wild](https://ibug.doc.ic.ac.uk/resources/eccv-2023-4th-abaw/). We achieve top 4 in the Multi-task Learning Challange.
    * We propose a 3-head EfficientNet to resolve 3 affective tasks: emotion recognition, valence-arousal estimation, and action unit detection.
    * Source code [here](https://github.com/khanhnd185/MTL-ABAW4).
