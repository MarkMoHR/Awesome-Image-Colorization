# Awesome-Image-Colorization

[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)


A collection of **Deep Learning** based Image Colorization papers and corresponding source code/demo program, including Automatic and User Guided (*i.e.* with User Interaction) colorization, as well as video colorization.

> Feel free to create a PR or an issue.  (Pull Request is preferred)

![examples](https://github.com/MarkMoHR/Awesome-Image-Colorization/blob/master/examples.png)

**Outline**

- [Automatic Image Colorization](#1-automatic-image-colorization)
  - [Software / Demo](#11-software--demo)
  - [Papers](#12-papers)
- [User Guided Image Colorization](#2-user-guided-image-colorization)
  - [Based on scribble](#21-based-on-scribble)
  - [Based on reference image](#22-based-on-reference-image)
  - [Based on palette](#23-based-on-palette)
  - [Based on language(text)](#24-based-on-language-or-text)
  - [Multi-modal](#25-multi-modal)
  - [Interactive Colorization](#26-interactive-colorization)
- [Techniques of Improving Image Colorization](#3-techniques-of-improving-image-colorization)
- [Video Colorization](#4-video-colorization)
  - [Survey](#40-survey)
  - [Automatically](#41-automatically)
  - [Based on reference](#42-based-on-reference)
  - [Based on scribble](#43-based-on-scribble)
  - [Based on text](#44-based-on-text)


---

## 1. Automatic Image Colorization


### 1.1 Software / Demo

| Name | Author/Owner | Code/Project Link  |
| --- | --- | --- |
| DeOldify | Jason Antic | [[link]](https://github.com/jantic/DeOldify) |
| Palette.fm | Emil Wallner | [[link]](https://palette.fm/) |


### 1.2 Papers

- Natural images

| Paper | Source | Code/Project Link  |
| --- | --- | --- |
| [Learning Large-Scale Automatic Image Colorization](http://openaccess.thecvf.com/content_iccv_2015/papers/Deshpande_Learning_Large-Scale_Automatic_ICCV_2015_paper.pdf) | ICCV 2015 | [[project]](http://vision.cs.illinois.edu/projects/lscolor/) [[code]](https://github.com/aditya12agd5/iccv15_lscolorization) |
| [Deep Colorization](http://openaccess.thecvf.com/content_iccv_2015/papers/Cheng_Deep_Colorization_ICCV_2015_paper.pdf) | ICCV 2015 |  |
| [Learning Representations for Automatic Colorization](https://arxiv.org/pdf/1603.06668.pdf) | ECCV 2016 | [[project]](http://people.cs.uchicago.edu/~larsson/colorization/) [[code]](https://github.com/gustavla/autocolorize) |
| [Colorful Image Colorization](https://arxiv.org/pdf/1603.08511.pdf) | ECCV 2016 | [[project]](http://richzhang.github.io/colorization/) [[code]](https://github.com/richzhang/colorization) |
| [Let there be Color!: Joint End-to-end Learning of Global and Local Image Priors for Automatic Image Colorization with Simultaneous Classification](http://iizuka.cs.tsukuba.ac.jp/projects/colorization/data/colorization_sig2016.pdf) | SIGGRAPH 2016 | [[project]](http://iizuka.cs.tsukuba.ac.jp/projects/colorization/en/) [[code]](https://github.com/satoshiiizuka/siggraph2016_colorization) |
| [Learning Diverse Image Colorization](http://openaccess.thecvf.com/content_cvpr_2017/papers/Deshpande_Learning_Diverse_Image_CVPR_2017_paper.pdf) | CVPR 2017 | [[code]](https://github.com/aditya12agd5/divcolor) |
| [Structural Consistency and Controllability for Diverse Colorization](http://openaccess.thecvf.com/content_ECCV_2018/papers/Safa_Messaoud_Structural_Consistency_and_ECCV_2018_paper.pdf) | ECCV 2018 |  |
| [Coloring With Limited Data: Few-Shot Colorization via Memory Augmented Networks](http://openaccess.thecvf.com/content_CVPR_2019/papers/Yoo_Coloring_With_Limited_Data_Few-Shot_Colorization_via_Memory_Augmented_Networks_CVPR_2019_paper.pdf) | CVPR 2019 | [[project]](https://sjooyoo.github.io/MemoPainter_CVPR2019/)<br/><br/> Unofficial:<br/> [[code (PyTorch)]](https://github.com/dongheehand/MemoPainter-PyTorch)|
| [ChromaGAN: Adversarial Picture Colorization with Semantic Class Distribution](http://openaccess.thecvf.com/content_WACV_2020/papers/Vitoria_ChromaGAN_Adversarial_Picture_Colorization_with_Semantic_Class_Distribution_WACV_2020_paper.pdf) | WACV 2020 | [[code]](https://github.com/pvitoria/ChromaGAN) |
| [Instance-aware Image Colorization](http://openaccess.thecvf.com/content_CVPR_2020/papers/Su_Instance-Aware_Image_Colorization_CVPR_2020_paper.pdf) | CVPR 2020 | [[code]](https://github.com/ericsujw/InstColorization) [[project]](https://ericsujw.github.io/InstColorization/) |
| [Pixelated Semantic Colorization](https://search.proquest.com/docview/2388669369?pq-origsite=gscholar&fromopenview=true) | IJCV 2020 |  |
| [Colorization Transformer](https://arxiv.org/abs/2102.04432) | ICLR 2021 | [[code]](https://github.com/google-research/google-research/tree/master/coltran) |
| [Focusing on Persons: Colorizing Old Images Learning from Modern Historical Movies](https://arxiv.org/abs/2108.06515) | ACM MM 2021 | [[code]](https://github.com/BestiVictory/MHMD) |
| [Towards Vivid and Diverse Image Colorization with Generative Color Prior](https://arxiv.org/abs/2108.08826) | ICCV 2021 | [[code]](https://github.com/ToTheBeginning/GCP-Colorization) |
| [SCSNet: An Efficient Paradigm for Learning Simultaneously Image Colorization and Super-Resolution](https://www.aaai.org/AAAI22Papers/AAAI-528.ZhangJ.pdf) (also reference based) | AAAI 2022 | |
| [Bridging the Domain Gap towards Generalization in Automatic Colorization](https://github.com/Lhyejin/DG-Colorization) | ECCV 2022 | [[code]](https://github.com/Lhyejin/DG-Colorization) |
| [ColorFormer: Image Colorization via Color Memory assisted Hybrid-attention Transformer](https://www.ecva.net/papers/eccv_2022/papers_ECCV/papers/136760020.pdf) | ECCV 2022 | [[code]](https://github.com/jixiaozhong/ColorFormer) |
| [BigColor: Colorization using a Generative Color Prior for Natural Images](https://kimgeonung.github.io/bigcolor/) | ECCV 2022 | [[project]](https://kimgeonung.github.io/bigcolor/) [[code]](https://github.com/KIMGEONUNG/BigColor) |
| [CT2: Colorization Transformer via Color Tokens](https://ci.idm.pku.edu.cn/Weng_ECCV22b.pdf) | ECCV 2022 | [[code]](https://github.com/shuchenweng/CT2) |
| [Disentangled Image Colorization via Global Anchors](https://menghanxia.github.io/papers/2022_disco_main.pdf) | SIGGRAPH Asia 2022 | [[code]](https://github.com/MenghanXia/DisentangledColorization) [[project]](https://menghanxia.github.io/projects/disco.html) |
| [UniColor: A Unified Framework for Multi-Modal Colorization with Transformer](https://arxiv.org/abs/2209.11223) (also multi-modal) | SIGGRAPH Asia 2022 | [[project]](https://luckyhzt.github.io/unicolor) |
| [Improved Diffusion-based Image Colorization via Piggybacked Models](https://arxiv.org/abs/2304.11105) | arxiv 23.04 | [[project]](https://piggyback-color.github.io/) |
| [DDColor: Towards Photo-Realistic and Semantic-Aware Image Colorization via Dual Decoders](https://arxiv.org/abs/2212.11613) | ICCV 2023 | [[code]](https://github.com/piddnad/DDColor) [[project]](https://www.modelscope.cn/models/damo/cv_ddcolor_image-colorization/summary) |
| [Diffusing Colors: Image Colorization with Text Guided Diffusion](https://arxiv.org/abs/2312.04145) (also text-based) | SIGGRAPH Asia 2023 | [[project]](https://aharonazulay.github.io/project_page_colorization/) |
| [Automatic Controllable Colorization via Imagination](https://arxiv.org/abs/2404.05661) | CVPR 2024 | [[code]](https://github.com/xy-cong/imagine-colorization) [[project]](https://xy-cong.github.io/imagine-colorization/) |
| [Control Color: Multimodal Diffusion-based Interactive Image Colorization](https://arxiv.org/abs/2402.10855) | arxiv 24.02 | [[code]](https://github.com/ZhexinLiang/Control-Color) [[project]](https://zhexinliang.github.io/Control_Color/) |
| [MultiColor: Image Colorization by Learning from Multiple Color Spaces](https://openreview.net/forum?id=Zo4P2F7xLY) | ACM MM 2024 |  |


- Line arts

| Paper | Source | Code/Project Link  |
| --- | --- | --- |
| [Region Assisted Sketch Colorization](https://ieeexplore.ieee.org/abstract/document/10303276/) | TIP 2023 |  |


## 2. User Guided Image Colorization

### 2.1 Based on scribble

- Software / Demo

| Image Type | Name | Author/Owner | Code/Project Link  |
| --- | --- | --- | --- |
| Line art | Petalica Paint (Old version: PaintsChainer) | Preferred Networks, Inc. | [[Petalica Paint (Online service)]](https://petalica.com/) [[PaintsChainer V1 code]](https://github.com/pfnet/PaintsChainer) |
| Line art | Style2Paints (SEPA) | Style2Paints Research | [[link]](https://github.com/lllyasviel/style2paints) |

- Papers

| Image Type | Paper | Source | Code/Project Link  |
| --- | --- | --- | --- |
| Manga | [Manga colorization](http://www.cse.cuhk.edu.hk/~ttwong/papers/manga/manga.pdf) | SIGGRAPH 2006 | [[Project]](http://www.cse.cuhk.edu.hk/~ttwong/papers/manga/manga.html) |
| Line art / Sketch / Manga | [LazyBrush: Flexible Painting Tool for Hand-drawn Cartoons](https://dcgi.fel.cvut.cz/home/sykorad/Sykora09-EG.pdf) | Eurographics 2009 | [[Project Home & Software]](https://dcgi.fel.cvut.cz/home/sykorad/lazybrush.html) <br/><br/>Unofficial:<br/> [[code(Matlab)]](https://github.com/kosua20/LazyBrush-implementation) |
| Line art / Sketch | [Outline Colorization through Tandem Adversarial Networks](https://arxiv.org/abs/1704.08834) | 1704.08834 | [[code]](https://github.com/kvfrans/deepcolor) |
| Natural Gray-Scale | [Real-Time User-Guided Image Colorization with Learned Deep Priors](https://arxiv.org/abs/1705.02999) | SIGGRAPH 2017 | [[project]](https://richzhang.github.io/ideepcolor/) [[code1]](https://github.com/junyanz/interactive-deep-colorization) [[code2]](https://github.com/richzhang/colorization-pytorch) |
| Sketch | [Scribbler: Controlling Deep Image Synthesis with Sketch and Color](http://openaccess.thecvf.com/content_cvpr_2017/papers/Sangkloy_Scribbler_Controlling_Deep_CVPR_2017_paper.pdf) | CVPR 2017 |  |
| Line art / Sketch | [Auto-painter: Cartoon Image Generation from Sketch by Using Conditional Generative Adversarial Networks](https://arxiv.org/pdf/1705.01908.pdf) | Neurocomputing 2018  | [[code]](https://github.com/irfanICMLL/Auto_painter) |
| Line art | [User-Guided Deep Anime Line Art Colorization with Conditional Adversarial Networks](https://arxiv.org/pdf/1808.03240.pdf) | ACM MM 2018 | [[code]](https://github.com/orashi/AlacGAN) |
| Line art | [Two-stage Sketch Colorization](http://www.cse.cuhk.edu.hk/~ttwong/papers/colorize/colorize.pdf) | SIGGRAPH Asia 2018 | [[Project]](https://www.cse.cuhk.edu.hk/~ttwong/papers/colorize/colorize.html) |
| Line art | [User-Guided Line Art Flat Filling with Split Filling Mechanism](https://openaccess.thecvf.com/content/CVPR2021/papers/Zhang_User-Guided_Line_Art_Flat_Filling_With_Split_Filling_Mechanism_CVPR_2021_paper.pdf) | CVPR 2021 | [[Project]](https://lllyasviel.github.io/SplitFilling/) [[code]](https://github.com/lllyasviel/SplitFilling) |
| Line art | [Dual Color Space Guided Sketch Colorization](https://ieeexplore.ieee.org/abstract/document/9515572) | TIP 2021 |  |
| Natural Gray-Scale | [iColoriT: Towards Propagating Local Hint to the Right Region in Interactive Colorization by Leveraging Vision Transformer](https://arxiv.org/pdf/2207.06831.pdf) | WACV 2023 | [[project]](https://pmh9960.github.io/research/iColoriT/) [[code]](https://github.com/pmh9960/iColoriT) |


### 2.2 Based on reference image

| Image Type | Paper | Source | Code/Project Link  |
| --- | --- | --- |--- |
| Manga | [Comicolorization: Semi-Automatic Manga Colorization](https://arxiv.org/pdf/1706.06759.pdf) | SIGGRAPH Asia 2017 Technical Briefs | [[code]](https://github.com/DwangoMediaVillage/Comicolorization) |
| Sketch | [TextureGAN: Controlling Deep Image Synthesis with Texture Patches](http://openaccess.thecvf.com/content_cvpr_2018/papers/Xian_TextureGAN_Controlling_Deep_CVPR_2018_paper.pdf) | CVPR 2018 | [[code]](https://github.com/janesjanes/Pytorch-TextureGAN) |
| Natural Gray-Scale | [Deep Exemplar-based Colorization](https://arxiv.org/pdf/1807.06587.pdf) | SIGGRAPH 2018 | [[code]](https://github.com/msracver/Deep-Exemplar-based-Colorization) |
| Natural Gray-Scale | [Example-Based Colourization Via Dense Encoding Pyramids](http://www.shengfenghe.com/uploads/1/5/1/3/15132160/cgf_13659_rev_ev.pdf) (also palette based) | Pacific Graphics 2018 | [[code]](https://github.com/chufengxiao/Example-based-Colorization-via-Dense-Encoding-pyramids) |
| Natural Gray-Scale | [A Superpixel-based Variational Model for Image Colorization](https://ieeexplore.ieee.org/abstract/document/8676327) | TVCG 2019 |  |
| Natural Gray-Scale | [Automatic Example-based Image Colourisation using Location-Aware Cross-Scale Matching](https://ieeexplore.ieee.org/abstract/document/8699109) | TIP 2019 |  |
| Line art / Sketch | [Adversarial Colorization Of Icons Based On Structure And Color Conditions](https://arxiv.org/pdf/1910.05253.pdf) | ACM MM 2019 | [[Code]](https://github.com/jxcodetw/Adversarial-Colorization-Of-Icons-Based-On-Structure-And-Color-Conditions) |
| Line art / Sketch | [Reference-Based Sketch Image Colorization using Augmented-Self Reference and Dense Semantic Correspondence](http://openaccess.thecvf.com/content_CVPR_2020/papers/Lee_Reference-Based_Sketch_Image_Colorization_Using_Augmented-Self_Reference_and_Dense_Semantic_CVPR_2020_paper.pdf) | CVPR 2020 | [[project]](https://ssuhan.github.io/RSC_CVPR20/) |
| Natural Gray-Scale | [Stylization-Based Architecture for Fast Deep Exemplar Colorization](http://openaccess.thecvf.com/content_CVPR_2020/papers/Xu_Stylization-Based_Architecture_for_Fast_Deep_Exemplar_Colorization_CVPR_2020_paper.pdf) | CVPR 2020 | [[code]](https://github.com/xuzhongyou/Colorization) |
| Manga | [Manga Filling Style Conversion with Screentone Variational Autoencoder](http://www.cse.cuhk.edu.hk/~ttwong/papers/screenstyle/screenstyle.pdf) | SIGGRAPH Asia 2020 | [[project]](https://www.cse.cuhk.edu.hk/~ttwong/papers/screenstyle/screenstyle.html) |
| Line art / Sketch | [Colorization of Line Drawings with Empty Pupils](https://www.gwern.net/docs/anime/2020-akita.pdf) | PG 2020 |  |
| Line art / Sketch | [Active Colorization for Cartoon Line Drawings](https://ieeexplore.ieee.org/abstract/document/9143503) | TVCG 2020 |  |
| Natural Gray-Scale | [Gray2ColorNet: Transfer More Colors from Reference Image](https://dl.acm.org/doi/abs/10.1145/3394171.3413594) | ACM MM 2020 |  |
| Line art / Sketch | [Line Art Correlation Matching Feature Transfer Network for Automatic Animation Colorization](https://arxiv.org/abs/2004.06718) | WACV 2021 |  |
| Natural Gray-Scale | [Globally and Locally Semantic Colorization via Exemplar-Based Broad-GAN](https://ieeexplore.ieee.org/abstract/document/9566701) | TIP 2021 |  |
| Natural Gray-Scale | [Yes, "Attention Is All You Need", for Exemplar based Colorization](https://dl.acm.org/doi/abs/10.1145/3474085.3475385) | ACM MM 2021 |  |
| Natural Gray-Scale | [SCSNet: An Efficient Paradigm for Learning Simultaneously Image Colorization and Super-Resolution](https://www.aaai.org/AAAI22Papers/AAAI-528.ZhangJ.pdf) (also automatic) | AAAI 2022 | |
| Line art / Sketch | [Style-Structure Disentangled Features and Normalizing Flows for Diverse Icon Colorization](https://openaccess.thecvf.com/content/CVPR2022/papers/Li_Style-Structure_Disentangled_Features_and_Normalizing_Flows_for_Diverse_Icon_Colorization_CVPR_2022_paper.pdf) | CVPR 2022 |  |
| Line art / Sketch | [Eliminating Gradient Conflict in Reference-based Line-Art Colorization](https://arxiv.org/abs/2207.06095) | ECCV 2022 | [[code]](https://github.com/kunkun0w0/SGA) |
| Natural Gray-Scale | [Semantic-Sparse Colorization Network for Deep Exemplar-based Colorization](https://arxiv.org/abs/2112.01335) | ECCV 2022 |  |
| Line art / Sketch | [Self-driven Dual-path Learning for Reference-based Line Art Colorization under Limited Data](https://ieeexplore.ieee.org/abstract/document/10182273) | TCSVT 2023 |  |
| Natural Gray-Scale | [Unsupervised Deep Exemplar Colorization via Pyramid Dual Non-local Attention](https://ieeexplore.ieee.org/abstract/document/10183846) | TIP 2023 | [[code]](https://github.com/wd1511/PDNLA-Net) |
| Line art / Sketch | [FlexIcon: Flexible Icon Colorization via Guided Images and Palettes](https://dl.acm.org/doi/abs/10.1145/3581783.3612182) (also palette based) | ACM MM 2023 |  |
| Line art / Sketch | [AnimeDiffusion: Anime Face Line Drawing Colorization via Diffusion Models](https://arxiv.org/abs/2303.11137) | TVCG 2024 | [[code]](https://github.com/xq-meng/AnimeDiffusion) |
| Natural Gray-Scale | [Lightweight Deep Exemplar Colorization via Semantic Attention-Guided Laplacian Pyramid](https://ieeexplore.ieee.org/abstract/document/10526459) | TVCG 2024 |  |


### 2.3 Based on palette

| Image Type | Paper | Source | Code/Project Link  |
| --- | --- | --- |--- |
| Natural Image | [Palette-based Photo Recoloring](https://gfx.cs.princeton.edu/pubs/Chang_2015_PPR/chang2015-palette_small.pdf) | SIGGRAPH 2015 | [[project]](https://gfx.cs.princeton.edu/pubs/Chang_2015_PPR/index.php) |
| Natural Gray-Scale | [Coloring with Words: Guiding Image Colorization Through Text-based Palette Generation](https://arxiv.org/pdf/1804.04128.pdf) (also text based) | ECCV 2018 | [[code]](https://github.com/awesome-davian/Text2Colors/) |
| Natural Gray-Scale | [Example-Based Colourization Via Dense Encoding Pyramids](http://www.shengfenghe.com/uploads/1/5/1/3/15132160/cgf_13659_rev_ev.pdf) (also reference based) | Pacific Graphics 2018 | [[code]](https://github.com/chufengxiao/Example-based-Colorization-via-Dense-Encoding-pyramids) |
| Natural Gray-Scale | [PalGAN: Image Colorization with Palette Generative Adversarial Networks](https://github.com/shepnerd/PalGAN) | ECCV 2022 | [[code]](https://github.com/shepnerd/PalGAN) |
| Line art / Sketch | [FlexIcon: Flexible Icon Colorization via Guided Images and Palettes](https://dl.acm.org/doi/abs/10.1145/3581783.3612182) (also reference based) | ACM MM 2023 |  |
| Line art / Sketch | [SketchDeco: Decorating B&W Sketches with Colour](https://arxiv.org/abs/2405.18716) | arxiv 24.05 | [[code]](https://github.com/CHAITron/sketchdeco-code) [[webpage]](https://chaitron.github.io/SketchDeco/) |

### 2.4 Based on language or text

| Image Type | Paper | Source | Code/Project Link  |
| --- | --- | --- |--- |
| Natural Gray-Scale / Sketch | [Language-Based Image Editing with Recurrent Attentive Models](https://arxiv.org/pdf/1711.06288.pdf) | CVPR 2018 | [[code]](https://github.com/Jianbo-Lab/LBIE) |
| Natural Gray-Scale | [Coloring with Words: Guiding Image Colorization Through Text-based Palette Generation](https://arxiv.org/pdf/1804.04128.pdf) (also palette based) | ECCV 2018 | [[code]](https://github.com/awesome-davian/Text2Colors/) |
| Natural Gray-Scale | [Learning to Color from Language](https://arxiv.org/pdf/1804.06026.pdf) | NAACL 2018 | [[code]](https://github.com/superhans/colorfromlanguage) |
| Line art | [Tag2Pix: Line Art Colorization Using Text Tag With SECat and Changing Loss](https://arxiv.org/pdf/1908.05840.pdf) | ICCV 2019 | [[code]](https://github.com/blandocs/Tag2Pix) [[code2 (GUI)]](https://github.com/MerHS/tag2pix-gui) |
| Scene Sketch | [Language-based Colorization of Scene Sketches](http://sweb.cityu.edu.hk/hongbofu/doc/language-based_sketch_colorization_SA19.pdf) | SIGGRAPH Asia 2019 | [[code]](https://github.com/SketchyScene/SketchySceneColorization) [[project]](https://sketchyscene.github.io/SketchySceneColorization/) |
| Line art | [Line Art Colorization Based on Explicit Region Segmentation](https://onlinelibrary.wiley.com/doi/abs/10.1111/cgf.14396) | Pacific Graphics 2021 | [[code]](https://github.com/Ricardo-L-C/ColorizationWithRegion) |
| Natural Gray-Scale | [L-CoDe: Language-based Colorization using Color-object Decoupled Conditions](https://ci.idm.pku.edu.cn/Weng_AAAI22.pdf) | AAAI 2022 | [[code]](https://github.com/changzheng123/L-CoDe) |
| Natural Gray-Scale | [L-CoDer: Language-based Colorization with Color-object Decoupling Transformer](https://ci.idm.pku.edu.cn/Weng_ECCV22g.pdf) | ECCV 2022 | [[code]](https://github.com/changzheng123/L-CoDer) |
| Natural Gray-Scale | [L-CoIns: Language-based Colorization with Instance Awareness](https://openaccess.thecvf.com/content/CVPR2023/papers/Chang_L-CoIns_Language-Based_Colorization_With_Instance_Awareness_CVPR_2023_paper.pdf) | CVPR 2023 |  |
| Natural Gray-Scale | [L-CAD: Language-based Colorization with Any-level Descriptions](https://arxiv.org/abs/2305.15217) | NeurIPS 2023 | [[code]](https://github.com/changzheng123/L-CAD) |
| Sketch | [Adding Conditional Control to Text-to-Image Diffusion Models](https://openaccess.thecvf.com/content/ICCV2023/papers/Zhang_Adding_Conditional_Control_to_Text-to-Image_Diffusion_Models_ICCV_2023_paper.pdf) | ICCV 2023 | [[code]](https://github.com/lllyasviel/ControlNet) |
| Natural Gray-Scale | [Diffusing Colors: Image Colorization with Text Guided Diffusion](https://arxiv.org/abs/2312.04145) | SIGGRAPH Asia 2023 | [[project]](https://aharonazulay.github.io/project_page_colorization/) |


### 2.5 Multi-modal


| Image Type | Paper | Input | Source | Code/Project Link  |
| --- | --- |--- | --- |--- |
| Natural Gray-Scale | [Interactive Deep Colorization Using Simultaneous Global and Local Inputs](https://ieeexplore.ieee.org/abstract/document/8683686) | stroke + palette | ICASSP 2019 |  |
| Natural Gray-Scale | [UniColor: A Unified Framework for Multi-Modal Colorization with Transformer](https://arxiv.org/abs/2209.11223) | stroke + exemplar + text | SIGGRAPH Asia 2022 | [[project]](https://luckyhzt.github.io/unicolor) |
| Line art | [Two-Step Training: Adjustable Sketch Colourization via Reference Image and Text Tag](https://onlinelibrary.wiley.com/doi/full/10.1111/cgf.14791) | exemplar + text | CGF 2023 | [[code]](https://github.com/tellurion-kanata/sketch_colorizer) |
| Natural Gray-Scale | [Control Color: Multimodal Diffusion-based Interactive Image Colorization](https://arxiv.org/abs/2402.10855) | text, stroke, exemplar | arxiv 24.02 | [[code]](https://github.com/ZhexinLiang/Control-Color) [[project]](https://zhexinliang.github.io/Control_Color/) |
| Natural Gray-Scale | [Versatile Vision Foundation Model for Image and Video Colorization](https://dl.acm.org/doi/abs/10.1145/3641519.3657509) | text, scribble, exemplar | SIGGRAPH 2024 | |


### 2.6 Interactive Colorization

| Image Type | Paper | Source | Code/Project Link  |
| --- | --- | --- |--- |
| Line art | [Guiding Users to Where to Give Color Hints for Efficient Interactive Sketch Colorization via Unsupervised Region Prioritization](https://arxiv.org/abs/2210.14270) | WACV 2023 |  |


## 3. Techniques of Improving Image Colorization

| Paper | Source | Code/Project Link  |
| --- | --- |--- |
| [Deep Edge-Aware Interactive Colorization against Color-Bleeding Effects](https://arxiv.org/abs/2107.01619) | ICCV 2021 | [[project]](https://eungyeupkim.github.io/edge-enhancing-colorization/) [[code(metric)]](https://github.com/niceDuckgu/CDR)|
| [Line Art Colorization Based on Explicit Region Segmentation](https://www.sysu-imsl.com/files/PG2021/line_art_colorization_pg2021_main.pdf) | Pacific Graphics 2021 | [[code]](https://github.com/Ricardo-L-C/ColorizationWithRegion) |
| [FlatGAN: A Holistic Approach for Robust Flat-Coloring in High-Definition with Understanding Line Discontinuity](https://dl.acm.org/doi/abs/10.1145/3581783.3613788) | ACM MM 2023 | [[code]](https://github.com/hanish3464/FlatGAN) |


## 4. Video Colorization

### 4.0 Survey

| Image Type | Paper | Source | Code/Project Link  |
| --- | --- | --- |--- |
|  | [Video Colorization: A Survey](https://jcst.ict.ac.cn/en/article/doi/10.1007/s11390-024-4143-z) | JCST 2024 | |

### 4.1 Automatically

| Image Type | Paper | Source | Code/Project Link  |
| --- | --- | --- |--- |
| Natural Gray-Scale | [Fully Automatic Video Colorization with Self-Regularization and Diversity](http://openaccess.thecvf.com/content_CVPR_2019/papers/Lei_Fully_Automatic_Video_Colorization_With_Self-Regularization_and_Diversity_CVPR_2019_paper.pdf) | CVPR 2019 | [[code]](https://github.com/ChenyangLEI/Fully-Automatic-Video-Colorization-with-Self-Regularization-and-Diversity) |


### 4.2 Based on reference

| Image Type | Paper | Source | Code/Project Link  |
| --- | --- | --- |--- |
| Natural Gray-Scale | [Switchable Temporal Propagation Network](http://openaccess.thecvf.com/content_ECCV_2018/papers/Sifei_Liu_Switchable_Temporal_Propagation_ECCV_2018_paper.pdf) | ECCV 2018 |  |
| Natural Gray-Scale | [Tracking Emerges by Colorizing Videos](http://openaccess.thecvf.com/content_ECCV_2018/papers/Carl_Vondrick_Self-supervised_Tracking_by_ECCV_2018_paper.pdf) | ECCV 2018 | [[code]](https://github.com/wbaek/tracking_via_colorization) |
| Natural Gray-Scale | [Deep Exemplar-based Video Colorization](http://openaccess.thecvf.com/content_CVPR_2019/papers/Zhang_Deep_Exemplar-Based_Video_Colorization_CVPR_2019_paper.pdf) | CVPR 2019 | [[code]](https://github.com/zhangmozhe/Deep-Exemplar-based-Video-Colorization) |
| Natural Gray-Scale | [DeepRemaster: Temporal Source-Reference Attention Networks for Comprehensive Video Enhancement](http://iizuka.cs.tsukuba.ac.jp/projects/remastering/data/remastering_siggraphasia2019.pdf) | SIGGRAPH Asia 2019 | [[code]](https://github.com/satoshiiizuka/siggraphasia2019_remastering) [[project]](http://iizuka.cs.tsukuba.ac.jp/projects/remastering/en/index.html) |
| Natural Gray-Scale | [Reference-Based Video Colorization with Spatiotemporal Correspondence](https://arxiv.org/abs/2011.12528) | 2011.12528 |  |
| Line art | [The Animation Transformer: Visual Correspondence via Segment Matching](https://arxiv.org/abs/2109.02614) | ICCV 2021 | [[App]](https://cadmium.app/) |
| Line art | [Line Art Correlation Matching Feature Transfer Network for Automatic Animation Colorization](https://openaccess.thecvf.com/content/WACV2021/papers/Zhang_Line_Art_Correlation_Matching_Feature_Transfer_Network_for_Automatic_Animation_WACV_2021_paper.pdf) | WACV 2021 | |
| Line art | [Reference-Based Deep Line Art Video Colorization](https://orca.cardiff.ac.uk/146848/1/RefLineArtVideoColorizationTVCG.pdf) | TVCG 2022 |  |
| Line art | [Learning Inclusion Matching for Animation Paint Bucket Colorization](https://arxiv.org/abs/2403.18342) | CVPR 2024 | [[webpage]](https://ykdai.github.io/projects/InclusionMatching) [[code]](https://github.com/ykdai/BasicPBC) |
| Natural Gray-Scale | [BiSTNet: Semantic Image Prior Guided Bidirectional Temporal Feature Fusion for Deep Exemplar-based Video Colorization](https://arxiv.org/abs/2212.02268) | TPAMI 2024 | [[code]](https://github.com/yyang181/BiSTNet) [[project]](https://yyang181.github.io/BiSTNet/) |
| Natural Gray-Scale | [Exemplar-based Video Colorization with Long-term Spatiotemporal Dependency](https://arxiv.org/abs/2303.15081) | KBS 2024 |  |
| Natural Gray-Scale | [ColorMNet: A Memory-based Deep Spatial-Temporal Feature Propagation Network for Video Colorization](https://arxiv.org/abs/2404.06251) | ECCV 2024 | [[code]](https://github.com/yyang181/colormnet) [[project]](https://yyang181.github.io/colormnet/) |
| Line art | [ToonCrafter: Generative Cartoon Interpolation](https://arxiv.org/abs/2405.17933) | SIGGRAPH Asia 2024 | [[code]](https://github.com/ToonCrafter/ToonCrafter) [[webpage]](https://doubiiu.github.io/projects/ToonCrafter/) |
| Line art | [LVCD: Reference-based Lineart Video Colorization with Diffusion Models](https://arxiv.org/abs/2409.12960) | SIGGRAPH Asia 2024 | [[webpage]](https://luckyhzt.github.io/lvcd) |



### 4.3 Based on scribble

| Image Type | Paper | Source | Code/Project Link  |
| --- | --- | --- |--- |
| Natural Gray-Scale | [SVCNet: Scribble-based Video Colorization Network with Temporal Aggregation](https://arxiv.org/abs/2303.11591) | TIP 2023 | [[code]](https://github.com/zhaoyuzhi/SVCNet) |


### 4.4 Based on text

| Image Type | Paper | Source | Code/Project Link  |
| --- | --- | --- |--- |
| Natural Gray-Scale | [Video Colorization with Pre-trained Text-to-Image Diffusion Models](https://arxiv.org/abs/2306.01732) | arxiv 23.06 | [[code]](https://github.com/ColorDiffuser/ColorDiffuser) [[project]](https://colordiffuser.github.io/) |
| Natural Gray-Scale | [Towards Photorealistic Video Colorization via Gated Color-Guided Image Diffusion Models](https://openreview.net/forum?id=4k79es7Guv) | ACM MM 2024 |  |

