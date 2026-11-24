# Referencias · Reconocimiento de señales de tránsito con CNN en un robot seguidor de línea

**Autores:** Cristian García Nastar · Juan Fernando García Restrepo
**Curso:** Visión Artificial · Retos 1 y 2 · 2026-2 · Universidad de Caldas

Código y modelo: [github.com/jgarciarf2/Reto1](https://github.com/jgarciarf2/Reto1) (la CNN está en la rama [`cristian-reentreno-pare-siga`](https://github.com/jgarciarf2/Reto1/tree/cristian-reentreno-pare-siga))

---

## Metodología 1 · Visión clásica (Reto 1)

1. Gonzalez, R. C., & Woods, R. E. (2018). *Digital image processing* (4.ª ed.). Pearson.
2. Szeliski, R. (2022). *Computer vision: Algorithms and applications* (2.ª ed.). Springer.
3. Bradski, G. (2000). The OpenCV library. *Dr. Dobb's Journal of Software Tools, 25*(11), 120–125.
4. Smith, A. R. (1978). Color gamut transform pairs. *ACM SIGGRAPH Computer Graphics, 12*(3), 12–19. (Espacio de color HSV)
5. Suzuki, S., & Abe, K. (1985). Topological structural analysis of digitized binary images by border following. *Computer Vision, Graphics, and Image Processing, 30*(1), 32–46. (Contornos, `findContours`)
6. Douglas, D. H., & Peucker, T. K. (1973). Algorithms for the reduction of the number of points required to represent a digitized line or its caricature. *Cartographica, 10*(2), 112–122. (`approxPolyDP`)
7. MacQueen, J. (1967). Some methods for classification and analysis of multivariate observations. En *Proceedings of the Fifth Berkeley Symposium on Mathematical Statistics and Probability* (Vol. 1, pp. 281–297). University of California Press. (K-Means)

## Metodología 2 · CNN con transfer learning (Reto 2)

8. Howard, A. G., Zhu, M., Chen, B., Kalenichenko, D., Wang, W., Weyand, T., Andreetto, M., & Adam, H. (2017). MobileNets: Efficient convolutional neural networks for mobile vision applications. *arXiv:1704.04861*.
9. Deng, J., Dong, W., Socher, R., Li, L.-J., Li, K., & Fei-Fei, L. (2009). ImageNet: A large-scale hierarchical image database. En *IEEE Conference on Computer Vision and Pattern Recognition* (pp. 248–255).
10. Simonyan, K., & Zisserman, A. (2015). Very deep convolutional networks for large-scale image recognition. En *International Conference on Learning Representations*. *arXiv:1409.1556*. (VGG16, VGG19)
11. He, K., Zhang, X., Ren, S., & Sun, J. (2016). Deep residual learning for image recognition. En *IEEE Conference on Computer Vision and Pattern Recognition* (pp. 770–778). (ResNet50)
12. Huang, G., Liu, Z., van der Maaten, L., & Weinberger, K. Q. (2017). Densely connected convolutional networks. En *IEEE Conference on Computer Vision and Pattern Recognition* (pp. 4700–4708). (DenseNet121)
13. Yosinski, J., Clune, J., Bengio, Y., & Lipson, H. (2014). How transferable are features in deep neural networks? En *Advances in Neural Information Processing Systems 27* (pp. 3320–3328). (Transfer learning)
14. Lin, M., Chen, Q., & Yan, S. (2014). Network in network. En *International Conference on Learning Representations*. *arXiv:1312.4400*. (Global Average Pooling)
15. Srivastava, N., Hinton, G., Krizhevsky, A., Sutskever, I., & Salakhutdinov, R. (2014). Dropout: A simple way to prevent neural networks from overfitting. *Journal of Machine Learning Research, 15*, 1929–1958.

## Herramientas

16. Abadi, M., Barham, P., Chen, J., Chen, Z., Davis, A., Dean, J., … Zheng, X. (2016). TensorFlow: A system for large-scale machine learning. En *12th USENIX Symposium on Operating Systems Design and Implementation* (pp. 265–283).
17. Chollet, F., et al. (2015). *Keras*. https://keras.io
18. Pedregosa, F., Varoquaux, G., Gramfort, A., Michel, V., Thirion, B., Grisel, O., … Duchesnay, É. (2011). Scikit-learn: Machine learning in Python. *Journal of Machine Learning Research, 12*, 2825–2830.
19. Harris, C. R., Millman, K. J., van der Walt, S. J., Gommers, R., Virtanen, P., Cournapeau, D., … Oliphant, T. E. (2020). Array programming with NumPy. *Nature, 585*(7825), 357–362.
20. Makeblock. (s. f.). *mBot: robot educativo*. https://www.makeblock.com
