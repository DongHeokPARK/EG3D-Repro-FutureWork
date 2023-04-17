# EG3D-Repro-FutureWork
Repro - small / Future Work - Styleformer Generator

Reproduction : eg3d-small

We reduced about 1/3 parameters of EG3D Generator and 40% parameters EG3D Discriminator, for training the model under the limited GPU resource(one 3090).

Future Work : Styleformer model in generator backbone

EG3D uses CNN-based-GAN Generator Backbone(StyleGan). So we replace the generator backbone to Styleformer, which is ViT-based-GAN. The picture below is the result of the future work.
![fakes005000](https://user-images.githubusercontent.com/110541013/232396134-603fb973-66ff-4555-ade1-b53f18785319.png)
