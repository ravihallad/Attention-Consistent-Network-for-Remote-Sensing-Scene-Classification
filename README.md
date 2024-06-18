                        Attention Consistent Network for Remote Sensing Scene
                                     Classification


To explore the spatial information for HSI classification, pixels with its adjacent pixels are usually
directly cropped from hyper spectral data to form HSI cubes in CNN-based methods. However,
the spatial land-cover distributions of cropped HSI cubes are usually complicated. The land-cover
label of a cropped HSI cube cannot simply be determined by its center pixel.

In addition, the spatial land cover distribution of a cropped HSI cube is fixed and has less diversity.
For CNN-based methods, training with cropped HSI cubes will result in poor generalization to the
changes of spatial land-cover distributions
In this paper, an end-to-end fully convolutional segmentation network (FCSN) is proposed to
simultaneously identify land-cover labels of all pixels in a HSI cube. First, several experiments are
conducted to demonstrate that recent CNN-based methods show the weak generalization
capabilities.

Second, a fine label style is proposed to label all pixels of HSI cubes to provide detailed spatial
land-cover distributions of HSI cubes. Third, a HSI cube generation method is proposed to
generate plentiful HSI cubes with fine labels to improve the diversity of spatial land-cover
distributions.

Finally, a FCSN is proposed to explore spectral-spatial features from finely labeled HSI cubes for
HSI classification. Experimental results show that FCSN has the superior generalization capability
to the changes of spatial land-cover distributions
![indian_pines](https://github.com/ravihallad/Attention-Consistent-Network-for-Remote-Sensing-Scene-Classification/assets/78427451/c05bbc34-ebb3-4492-ab51-58f0537535f6)
![CNN_Architecture](https://github.com/ravihallad/Attention-Consistent-Network-for-Remote-Sensing-Scene-Classification/assets/78427451/547f7883-b253-4dc5-87be-f5b1353707d0)



