# Awesome-Image-Colorization

[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)


A collection of **Deep Learning** based Image Colorization papers and corresponding source code/demo program, including Automatic and User Guided (*i.e.* with User Interaction) colorization, as well as video colorization.

> Feel free to create a PR or an issue.  (Pull Request is preferred)

![examples](https://github.com/MarkMoHR/Awesome-Image-Colorization/blob/master/examples.png)

**Outline**

- [Automatic Image Colorization](#1-automatic-image-colorization)
- [User Guided Image Colorization](#2-user-guided-image-colorization)
  - [Based on color strokes](#21-based-on-color-strokes)
  - [Based on reference color image](#22-based-on-reference-color-image)
  - [Based on color palette](#23-based-on-color-palette)
  - [Based on language(text)](#24-based-on-language-or-text)
- [Video Colorization](#3-video-colorization)
  - [Automatically](#31-automatically)
  - [Based on reference](#32-based-on-reference)


---

## 1. Automatic Image Colorization

| Paper | Source | Code/Project Link  |
| --- | --- | --- |
| [Learning Large-Scale Automatic Image Colorization](http://openaccess.thecvf.com/content_iccv_2015/papers/Deshpande_Learning_Large-Scale_Automatic_ICCV_2015_paper.pdf) | ICCV 2015 | [[project]](http://vision.cs.illinois.edu/projects/lscolor/) [[code]](https://github.com/aditya12agd5/iccv15_lscolorization) |
| [Deep Colorization](http://openaccess.thecvf.com/content_iccv_2015/papers/Cheng_Deep_Colorization_ICCV_2015_paper.pdf) | ICCV 2015 |  |
| [Learning Representations for Automatic Colorization](https://arxiv.org/pdf/1603.06668.pdf) | ECCV 2016 | [[project]](http://people.cs.uchicago.edu/~larsson/colorization/) [[code]](https://github.com/gustavla/autocolorize) |
| [Colorful Image Colorization](https://arxiv.org/pdf/1603.08511.pdf) | ECCV 2016 | [[project]](http://richzhang.github.io/colorization/) [[code]](https://github.com/richzhang/colorization) |
| [Let there be Color!: Joint End-to-end Learning of Global and Local Image Priors for Automatic Image Colorization with Simultaneous Classification](http://iizuka.cs.tsukuba.ac.jp/projects/colorization/data/colorization_sig2016.pdf) | SIGGRAPH 2016 | [[project]](http://iizuka.cs.tsukuba.ac.jp/projects/colorization/en/) [[code]](https://github.com/satoshiiizuka/siggraph2016_colorization) |
| [Unsupervised Diverse Colorization via Generative Adversarial Networks](https://arxiv.org/pdf/1702.06674.pdf) | ECML-PKDD 2017 | [[code]](https://github.com/ccyyatnet/COLORGAN) |
| [Learning Diverse Image Colorization](http://openaccess.thecvf.com/content_cvpr_2017/papers/Deshpande_Learning_Diverse_Image_CVPR_2017_paper.pdf) | CVPR 2017 | [[code]](https://github.com/aditya12agd5/divcolor) |
| [Structural Consistency and Controllability for Diverse Colorization](http://openaccess.thecvf.com/content_ECCV_2018/papers/Safa_Messaoud_Structural_Consistency_and_ECCV_2018_paper.pdf) | ECCV 2018 |  |
| [Coloring With Limited Data: Few-Shot Colorization via Memory Augmented Networks](http://openaccess.thecvf.com/content_CVPR_2019/papers/Yoo_Coloring_With_Limited_Data_Few-Shot_Colorization_via_Memory_Augmented_Networks_CVPR_2019_paper.pdf) | CVPR 2019 | [[project]](https://sjooyoo.github.io/MemoPainter_CVPR2019/)<br/><br/> Unofficial:<br/> [[code (PyTorch)]](https://github.com/dongheehand/MemoPainter-PyTorch)|
| [ChromaGAN: Adversarial Picture Colorization with Semantic Class Distribution](http://openaccess.thecvf.com/content_WACV_2020/papers/Vitoria_ChromaGAN_Adversarial_Picture_Colorization_with_Semantic_Class_Distribution_WACV_2020_paper.pdf) | WACV 2020 | [[code]](https://github.com/pvitoria/ChromaGAN) |
| [Instance-aware Image Colorization](http://openaccess.thecvf.com/content_CVPR_2020/papers/Su_Instance-Aware_Image_Colorization_CVPR_2020_paper.pdf) | CVPR 2020 | [[code]](https://github.com/ericsujw/InstColorization) [[project]](https://ericsujw.github.io/InstColorization/) |
| [Pixelated Semantic Colorization](https://search.proquest.com/docview/2388669369?pq-origsite=gscholar&fromopenview=true) | IJCV 2020 |  |
| [Colorization Transformer](https://arxiv.org/abs/2102.04432) | ICLR 2021 | [[code]](https://github.com/google-research/google-research/tree/master/coltran) |

## 2. User Guided Image Colorization

### 2.1 Based on color strokes

| Image Type | Paper | Source | Code/Project Link  |
| --- | --- | --- |--- |
| Manga | [Manga colorization](http://www.cse.cuhk.edu.hk/~ttwong/papers/manga/manga.pdf) | SIGGRAPH 2006 | [[Project Home]](http://www.cse.cuhk.edu.hk/~ttwong/papers/manga/manga.html) <br/>Unofficial: [[code]](https://github.com/OVGULIU/Manga-Colorization)|
| Line art / Sketch / Manga | [LazyBrush: Flexible Painting Tool for Hand-drawn Cartoons](https://dcgi.fel.cvut.cz/home/sykorad/Sykora09-EG.pdf) | Eurographics 2009 | [[Project Home & Software]](https://dcgi.fel.cvut.cz/home/sykorad/lazybrush.html) <br/><br/>Unofficial:<br/> [[code1 (Matlab)]](https://github.com/kosua20/LazyBrush-implementation) <br/> [[code2 (C#)]](https://github.com/furaga/LazyBrushSharp) <br/> [[code3]](https://github.com/Evarin/LazyBrush) |
| Line art / Sketch | [Outline Colorization through Tandem Adversarial Networks](https://arxiv.org/abs/1704.08834) | 1704.08834 | [[code]](https://github.com/kvfrans/deepcolor) |
| Line art / Sketch | [Auto-painter: Cartoon Image Generation from Sketch by Using Conditional Generative Adversarial Networks](https://arxiv.org/pdf/1705.01908.pdf) | 1705.01908 | [[code]](https://github.com/irfanICMLL/Auto_painter) |
| Natural Gray-Scale | [Real-Time User-Guided Image Colorization with Learned Deep Priors](https://arxiv.org/abs/1705.02999) | SIGGRAPH 2017 | [[project]](https://richzhang.github.io/ideepcolor/) [[code1]](https://github.com/junyanz/interactive-deep-colorization) [[code2]](https://github.com/richzhang/colorization-pytorch) |
| Sketch | [Scribbler: Controlling Deep Image Synthesis with Sketch and Color](http://openaccess.thecvf.com/content_cvpr_2017/papers/Sangkloy_Scribbler_Controlling_Deep_CVPR_2017_paper.pdf) | CVPR 2017 |  |
| Line art | [User-Guided Deep Anime Line Art Colorization with Conditional Adversarial Networks](https://arxiv.org/pdf/1808.03240.pdf) | ACM MM 2018 | [[code]](https://github.com/orashi/AlacGAN) |
| Line art | Style2paints V3 : [Two-stage Sketch Colorization](http://www.cse.cuhk.edu.hk/~ttwong/papers/colorize/colorize.pdf) | SIGGRAPH Asia 2018 | [[Project]](https://www.cse.cuhk.edu.hk/~ttwong/papers/colorize/colorize.html) <br/> [[Paper's code(V3)]](https://github.com/lllyasviel/style2paints/tree/master/V3) <br/> [[Portable software(V4.5)]](https://github.com/lllyasviel/style2paints) <br/><br/>Unofficial:<br/> [[code1]](https://github.com/Pengxiao-Wang/Style2Paints_V3)  [[code2]](https://github.com/SerialLain3170/Colorization)  <br/> [[PaintsTensorFlow]](https://github.com/rapidrabbit76/PaintsTensorFlow)|
| Natural Gray-Scale | [Interactive Deep Colorization Using Simultaneous Global and Local Inputs](https://ieeexplore.ieee.org/abstract/document/8683686) (also palette based) | ICASSP 2019 |  |
| Line art | PaintsChainer (Petalica Paint) | Online Demo (by Preferred Networks, Inc.) | [[V3 Demo]](https://paintschainer.preferred.tech/) [[V1 code]](https://github.com/pfnet/PaintsChainer) |


### 2.2 Based on reference color image

| Image Type | Paper | Source | Code/Project Link  |
| --- | --- | --- |--- |
| Line art | Style2paints V1 : [Style Transfer for Anime Sketches with Enhanced Residual U-net and Auxiliary Classifier GAN](https://arxiv.org/abs/1706.03319) | ACPR 2017 | [[Code]](https://github.com/lllyasviel/style2paints#style2paints-v1) <br/><br/>Unofficial:<br/>[[code]](https://github.com/SerialLain3170/Colorization) |
| Manga | [Comicolorization: Semi-Automatic Manga Colorization](https://arxiv.org/pdf/1706.06759.pdf) (also palette based) | SIGGRAPH Asia 2017 | [[code]](https://github.com/DwangoMediaVillage/Comicolorization) |
| Sketch | [TextureGAN: Controlling Deep Image Synthesis with Texture Patches](http://openaccess.thecvf.com/content_cvpr_2018/papers/Xian_TextureGAN_Controlling_Deep_CVPR_2018_paper.pdf) | CVPR 2018 | [[code]](https://github.com/janesjanes/Pytorch-TextureGAN) |
| Natural Gray-Scale | [Deep Exemplar-based Colorization](https://arxiv.org/pdf/1807.06587.pdf) | SIGGRAPH 2018 | [[code]](https://github.com/msracver/Deep-Exemplar-based-Colorization) |
| Natural Gray-Scale | [Example-Based Colourization Via Dense Encoding Pyramids](http://www.shengfenghe.com/uploads/1/5/1/3/15132160/cgf_13659_rev_ev.pdf) (also palette based) | Pacific Graphics 2018 | [[code]](https://github.com/chufengxiao/Example-based-Colorization-via-Dense-Encoding-pyramids) |
| Natural Gray-Scale | [A Superpixel-based Variational Model for Image Colorization](https://ieeexplore.ieee.org/abstract/document/8676327) | TVCG 2019 |  |
| Natural Gray-Scale | [Automatic Example-based Image Colourisation using Location-Aware Cross-Scale Matching](https://ieeexplore.ieee.org/abstract/document/8699109) | TIP 2019 |  |
| Line art / Sketch | [Adversarial Colorization Of Icons Based On Structure And Color Conditions](https://arxiv.org/pdf/1910.05253.pdf) | ACM MM 2019 | [[Code]](https://github.com/jxcodetw/Adversarial-Colorization-Of-Icons-Based-On-Structure-And-Color-Conditions) |
| Line art / Sketch | [Reference-Based Sketch Image Colorization using Augmented-Self Reference and Dense Semantic Correspondence](http://openaccess.thecvf.com/content_CVPR_2020/papers/Lee_Reference-Based_Sketch_Image_Colorization_Using_Augmented-Self_Reference_and_Dense_Semantic_CVPR_2020_paper.pdf) | CVPR 2020 | Unofficial: [[code]](https://github.com/SerialLain3170/Colorization) |
| Natural Gray-Scale | [Stylization-Based Architecture for Fast Deep Exemplar Colorization](http://openaccess.thecvf.com/content_CVPR_2020/papers/Xu_Stylization-Based_Architecture_for_Fast_Deep_Exemplar_Colorization_CVPR_2020_paper.pdf) | CVPR 2020 | [[code]](https://github.com/xuzhongyou/Colorization) |
| Manga | [Manga Filling Style Conversion with Screentone Variational Autoencoder](http://www.cse.cuhk.edu.hk/~ttwong/papers/screenstyle/screenstyle.pdf) (also palette based) | SIGGRAPH Asia 2020 | [[project]](https://www.cse.cuhk.edu.hk/~ttwong/papers/screenstyle/screenstyle.html) |
| Line art / Sketch | [Active Colorization for Cartoon Line Drawings](https://ieeexplore.ieee.org/abstract/document/9143503) | TVCG 2020 |  |
| Natural Gray-Scale | [Gray2ColorNet: Transfer More Colors from Reference Image](https://dl.acm.org/doi/abs/10.1145/3394171.3413594) | ACM MM 2020 |  |
| Line art / Sketch | [Line Art Correlation Matching Feature Transfer Network for Automatic Animation Colorization](https://arxiv.org/abs/2004.06718) | WACV 2021 |  |


### 2.3 Based on color palette

| Image Type | Paper | Source | Code/Project Link  |
| --- | --- | --- |--- |
| Natural Image | [Palette-based Photo Recoloring](https://gfx.cs.princeton.edu/pubs/Chang_2015_PPR/chang2015-palette_small.pdf) | SIGGRAPH 2015 | [[project]](https://gfx.cs.princeton.edu/pubs/Chang_2015_PPR/index.php) |
| Manga | [Comicolorization: Semi-Automatic Manga Colorization](https://arxiv.org/pdf/1706.06759.pdf) (also reference based) | SIGGRAPH Asia 2017 | [[code]](https://github.com/DwangoMediaVillage/Comicolorization) |
| Natural Gray-Scale | [Coloring with Words: Guiding Image Colorization Through Text-based Palette Generation](https://arxiv.org/pdf/1804.04128.pdf) (also text based) | ECCV 2018 | [[code]](https://github.com/awesome-davian/Text2Colors/) |
| Natural Gray-Scale | [Example-Based Colourization Via Dense Encoding Pyramids](http://www.shengfenghe.com/uploads/1/5/1/3/15132160/cgf_13659_rev_ev.pdf) (also reference based) | Pacific Graphics 2018 | [[code]](https://github.com/chufengxiao/Example-based-Colorization-via-Dense-Encoding-pyramids) |
| Natural Gray-Scale | [Interactive Deep Colorization Using Simultaneous Global and Local Inputs](https://ieeexplore.ieee.org/abstract/document/8683686) (also strokes based) | ICASSP 2019 |  |

### 2.4 Based on language or text

| Image Type | Paper | Source | Code/Project Link  |
| --- | --- | --- |--- |
| Natural Gray-Scale / Sketch | [Language-Based Image Editing with Recurrent Attentive Models](https://arxiv.org/pdf/1711.06288.pdf) | CVPR 2018 | [[code]](https://github.com/Jianbo-Lab/LBIE) |
| Natural Gray-Scale | [Coloring with Words: Guiding Image Colorization Through Text-based Palette Generation](https://arxiv.org/pdf/1804.04128.pdf) (also palette based) | ECCV 2018 | [[code]](https://github.com/awesome-davian/Text2Colors/) |
| Natural Gray-Scale | [Learning to Color from Language](https://arxiv.org/pdf/1804.06026.pdf) | NAACL 2018 | [[code]](https://github.com/superhans/colorfromlanguage) |
| Line art | [Tag2Pix: Line Art Colorization Using Text Tag With SECat and Changing Loss](https://arxiv.org/pdf/1908.05840.pdf) | ICCV 2019 | [[code]](https://github.com/blandocs/Tag2Pix) [[code2 (GUI)]](https://github.com/MerHS/tag2pix-gui) |
| Scene Sketch | [Language-based Colorization of Scene Sketches](http://sweb.cityu.edu.hk/hongbofu/doc/language-based_sketch_colorization_SA19.pdf) | SIGGRAPH Asia 2019 | [[code]](https://github.com/SketchyScene/SketchySceneColorization) [[project]](https://sketchyscene.github.io/SketchySceneColorization/) |


## 3. Video Colorization

### 3.1 Automatically

| Image Type | Paper | Source | Code/Project Link  |
| --- | --- | --- |--- |
| Natural Gray-Scale | [Fully Automatic Video Colorization with Self-Regularization and Diversity](http://openaccess.thecvf.com/content_CVPR_2019/papers/Lei_Fully_Automatic_Video_Colorization_With_Self-Regularization_and_Diversity_CVPR_2019_paper.pdf) | CVPR 2019 | [[code]](https://github.com/ChenyangLEI/Fully-Automatic-Video-Colorization-with-Self-Regularization-and-Diversity) |


### 3.2 Based on reference

| Image Type | Paper | Source | Code/Project Link  |
| --- | --- | --- |--- |
| Natural Gray-Scale | [Switchable Temporal Propagation Network](http://openaccess.thecvf.com/content_ECCV_2018/papers/Sifei_Liu_Switchable_Temporal_Propagation_ECCV_2018_paper.pdf) | ECCV 2018 |  |
| Natural Gray-Scale | [Tracking Emerges by Colorizing Videos](http://openaccess.thecvf.com/content_ECCV_2018/papers/Carl_Vondrick_Self-supervised_Tracking_by_ECCV_2018_paper.pdf) | ECCV 2018 | [[code]](https://github.com/wbaek/tracking_via_colorization) |
| Natural Gray-Scale | [Deep Exemplar-based Video Colorization](http://openaccess.thecvf.com/content_CVPR_2019/papers/Zhang_Deep_Exemplar-Based_Video_Colorization_CVPR_2019_paper.pdf) | CVPR 2019 | [[code]](https://github.com/zhangmozhe/Deep-Exemplar-based-Video-Colorization) |
| Natural Gray-Scale | [DeepRemaster: Temporal Source-Reference Attention Networks for Comprehensive Video Enhancement](http://iizuka.cs.tsukuba.ac.jp/projects/remastering/data/remastering_siggraphasia2019.pdf) | SIGGRAPH Asia 2019 | [[code]](https://github.com/satoshiiizuka/siggraphasia2019_remastering) [[project]](http://iizuka.cs.tsukuba.ac.jp/projects/remastering/en/index.html) |
| Line art | [Deep Line Art Video Colorization with a Few References](https://arxiv.org/abs/2003.10685) | 2003.10685 |  |
| Natural Gray-Scale | [Reference-Based Video Colorization with Spatiotemporal Correspondence](https://arxiv.org/abs/2011.12528) | 2011.12528 |  |
