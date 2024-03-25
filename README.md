In questo progetto ho cercato di realizzare una conditional GAN (arxiv.org/abs/1411.1784) capace di prendere immagini di esseri umani e trasformarli in anime.
Come architettura della GAN ho utilizzato una DCGAN (https://arxiv.org/abs/1511.06434) dotata di un primo strato di fully connected net e di vari strati convolutivi.
Per allenare l'encoder e il discriminatore ho seguito questo paper:https://arxiv.org/abs/1611.06355.

Sia la GAN che l'encoder sono stati addestrati per 25 epoche (più o meno) e nel notebook sono presenti due paremetri per rete scelti tra i 25 che trovavo migliori.

Di seguito tre immagini di esempio 
