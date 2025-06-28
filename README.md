# SSL Plant Disease Demo

The project is about finetuning self-supervised learning models (SimCLR, MoCo, BYOL, DINO) on images of diseased plant/leaves and comparing the performance of various models
All the code from loading models, data augmentations, pretraining ssl models, finetuning models, comparison and analysis are included in:
- **ssl_plant_disease_detection.ipynb**

## Acknowledgements / References

This project heavily relies on and acknowledges the foundational work and resources from the following repositories and datasets:

* **PlantVillage Dataset:**
    * The primary dataset for plant disease image classification was sourced from the [PlantVillage Dataset on Kaggle](https://github.com/spMohanty/PlantVillage-Dataset)

    * Citation:
        ```bibtex
        @article{Mohanty_Hughes_Salathé_2016,
        title={Using deep learning for image-based plant disease detection},
        volume={7},
        DOI={10.3389/fpls.2016.01419},
        journal={Frontiers in Plant Science},
        author={Mohanty, Sharada P. and Hughes, David P. and Salathé, Marcel},
        year={2016},
        month={Sep}
        }

* **Contrastive Learning Frameworks:**
    * **SimCLR:** Implementations and insights for SimCLR were adapted from Google research's SimCLR [Github Repo](https://github.com/google-research/simclr).

    * Citation:
    ```bibtex
        @article{chen2020simple,
        title={A Simple Framework for Contrastive Learning of Visual Representations},
        author={Chen, Ting and Kornblith, Simon and Norouzi, Mohammad and Hinton, Geoffrey},
        journal={arXiv preprint arXiv:2002.05709},
        year={2020}
        }
    ```

    * **MoCo v2:** Implementations and insights for MoCo v2 were adapted from Facebook research's [Github Repo](https://github.com/facebookresearch/moco).

    * Citation:
    ```bibtex
        @Article{chen2020mocov2,
        author  = {Xinlei Chen and Haoqi Fan and Ross Girshick and Kaiming He},
        title   = {Improved Baselines with Momentum Contrastive Learning},
        journal = {arXiv preprint arXiv:2003.04297},
        year    = {2020},
        }
    ```

    * **DINO:** Implementations and insights for DINO were adapted from Facebook research's [Github Repo](https://github.com/facebookresearch/dino).

    * Citation:
    ```bibtex
        @inproceedings{caron2021emerging,
        title={Emerging Properties in Self-Supervised Vision Transformers},
        author={Caron, Mathilde and Touvron, Hugo and Misra, Ishan and J\'egou, Herv\'e  and Mairal, Julien and Bojanowski, Piotr and Joulin, Armand},
        booktitle={Proceedings of the International Conference on Computer Vision (ICCV)},
        year={2021}
        }
    ```

    * **BYOL:** Implementations and insights for SimCLR were adapted from byol-pytorch [Github Repo](https://github.com/lucidrains/byol-pytorch).

    * Citation:
    ```bibtex
        @misc{grill2020bootstrap,
        title = {Bootstrap Your Own Latent: A New Approach to Self-Supervised Learning},
        author = {Jean-Bastien Grill and Florian Strub and Florent Altché and Corentin Tallec and Pierre H. Richemond and Elena Buchatskaya and Carl Doersch and Bernardo Avila Pires and Zhaohan Daniel Guo and Mohammad Gheshlaghi Azar and Bilal Piot and Koray Kavukcuoglu and Rémi Munos and Michal Valko},
        year = {2020},
        eprint = {2006.07733},
        archivePrefix = {arXiv},
        primaryClass = {cs.LG}
    }

        @misc{chen2020exploring,
        title={Exploring Simple Siamese Representation Learning}, 
        author={Xinlei Chen and Kaiming He},
        year={2020},
        eprint={2011.10566},
        archivePrefix={arXiv},
        primaryClass={cs.CV}
    }
    ```
