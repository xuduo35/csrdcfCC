# CSRDCF
C++ test code for the tracker described in the CVPR16 paper "Discriminative Correlation Filter Tracker with Channel and Spatial Reliability" by Alan Lukežič. CSRDCF C++ code is from opencv module(https://github.com/opencv/opencv_contrib) which is contributed by Alan Lukežič.

@Article{Lukezic_IJCV2018,
author={Luke{\v{z}}i{\v{c}}, Alan and Voj{'i}{\v{r}}, Tom{'a}{\v{s}} and {\v{C}}ehovin Zajc, Luka and Matas, Ji{\v{r}}{'i} and Kristan, Matej},
title={Discriminative Correlation Filter Tracker with Channel and Spatial Reliability},
journal={International Journal of Computer Vision},
year={2018},
}

I wrote this code only for testing CSRDCF performance. Seems CSRDCF tracking accuracy is better than STAPLE, but STAPLE can run in high FPS and bundling box is more adaptable to object size change. FYI, It's only a rough estimate.

Some code from:

https://github.com/foolwood/DAT

https://github.com/ppaanngggg/fhog

Original matlab version:
https://github.com/alanlukezic/csr-dcf

Testset vot2015:
http://box.vicos.si/vot/vot2015.zip
