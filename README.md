<!-- ### News -->
<!-- * `2024/3/3` We have released the full code to run on our preprocessed dataset, see [Run.md](docs/Run.md) for more details. -->


# DoRA: Improved Co-located Relightable Avatar

Why called *DoRA*? 
This work is an improved version of our previous work [CoRA](https://github.com/yxuhan/CoRA) using diffusion prior. 
D is the next letter of C in the alphabet, which means DoRA is the next work of CoRA.
Besides, D also stands for the use of **D**iffusion prior.

<img src="misc/teaser.gif" width="100%" >

This is a PyTorch implementation of the following paper:

**Facial Appearance Capture at Home with Patch-Level Reflectance Prior**, SIGGRAPH 2025.

Yuxuan Han, Junfeng Lyu, Kuan Sheng, Minghao Que, Qixuan Zhang, Lan Xu, and Feng Xu

[Project Page](https://yxuhan.github.io/DoRA/index.html) | [Video]() | [Paper]()

## Release Plan
Due to the license issue, we can not release the diffusion prior trained on the 3D Scanstore dataset.
To help the research community reimplement our work, we plan to release the diffusion prior trained on the [GauFace dataset](https://dafei-qin.github.io/TransGS.github.io/) and provide the full inverse rendering code.
Gauface is also a Light Stage dataset containing 4Kx4K diffuse albedo, specular albedo, and the tangent-space normal maps.
This version of code can still achieve near production-level results as we shown in the paper and the video.

*Stay tuned; I'm working on clean the research code.*


## Contact
If you have any questions, please contact Yuxuan Han (hanyx22@mails.tsinghua.edu.cn).


## License
This repository can <b>only be used for personal/research/non-commercial purposes</b>.


## Citation
Please cite the following paper if it helps your research:

    @inproceedings{han2025dora,
        author = {Han, Yuxuan and Lyu, Junfeng and Sheng, Kuan and Que, Minghao and Zhang, Qixuan and Xu, Lan, and Xu, Feng},
        title = {Facial Appearance Capture at Home with Patch-Level Reflectance Prior},
        journal={SIGGRAPH},
        year={2025}
    }

    @inproceedings{han2024cora,
        author = {Han, Yuxuan and Lyu, Junfeng and Xu, Feng},
        title = {High-Quality Facial Geometry and Appearance Capture at Home},
        journal={CVPR},
        year={2024}
    }


## Acknowledgments
We thank [Jingwang Ling](https://gerwang.github.io/) and [Linjie Lyu](https://people.mpi-inf.mpg.de/~llyu/) (the author of [DPI](https://github.com/LinjieLyu/DPI), which inspires our work a lot) for their insightful suggestions.
