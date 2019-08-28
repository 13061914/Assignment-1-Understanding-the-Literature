# Assignment-1-Understanding-the-Literature
31005 Machine Learning Spring 2019

Review Report on "Eigenfaces vs. Fisherfaces: Recognition Using Class Specific Linear Projection"

Introduction
In this assignment, it chose one journal article named “Eigenfaces vs. Fisherfaces: Recognition Using Class Specific Linear Projection”, the authors of article are Peter N. Belhumeur, Joao P. Hespanha, and David J. Kriegman, and it published on IEEE in July 1997. The reason interest in this article is because HuaWei Pr30 was launched a few months ago, which is famous for its ultra-high-definition camera computing technology, and this article is about solving the problem of face recognition, which is an image processing analysis and recovery process. This article is about Face recognition algorithms, so I also thought about the Face ID unlock feature used by iPhone X to increase the privacy of the phone. Face recognition technology is also being used on payment platforms in China, this makes more curious about read this article.
This report includes a summary of the content, comparison of algorithms, quality of technology, application of technology and overall quality of the article.

Content
A face recognition algorithm independent of illumination and facial expression changes is proposed in this journal article. At the beginning of this paper, we briefly introduce and explain that the two requirements of current face recognition technology are illumination and facial expression respectively, but the accuracy is poor, Belhumeur et al. (1997) hope to improve this technology algorithm. They used four methods to study current technical algorithms and divided the results into three categories to reach their final conclusion.The research method uses learning set and test set data to verify their advantages and disadvantages through four algorithms. The first is the nearest neighbor classifier used by the relatively simple algorithm. The second is the eigenfaces algorithm which is calculated by a large number of data sets and then is dimensionality reduction by principal components analysis (PCA) and reconstructed by model. The third is a linear subspace algorithm which is not affected by large illumination conditions. The fourth is Fisherface, similar to the feature face algorithm but based on the Linear Discriminant Analysis (LDA) theory. In the results section, Belhumeur et al. (1997) talked about their results from three angles, using two sets of databases related to changes in lighting conditions and to changes in facial expressions. These include the effects of changes in light conditions, facial expressions, eye wear, light conditions and glasses. The final conclusion Belhumeur et al. (1997) come to is that the Fisherface algorithm is the best one at present, but there are many problems with other algorithms. Fisherface, however, is still in doubt, requiring new tests to support his idea.
While, this paper is been 22 years since this article was published, and these problems should have been solved by now, such as Face ID unlock, Face ID pay, face recognition algorithms that are already in use.

Innovation
Belhumeur et al. (1997) point out that the first developed face recognition technology was Robert Fisher in 1936. While before 1997, there are two good algorithms were discovered for face recognition, one by feature face algorithm pattern of principal components analysis (PCA), and the other by Fisherfaces algorithm pattern of the Linear Discriminant Analysis (LDA) theory, while in here use a derivative of Fisher 's Linear Discriminant (FLD) (Belhumeur et al., 1997). At the time, however, these methods were unable to implement effective, reliable face recognition techniques in extreme light, facial expressions and postures. The experiment of this paper is to compare four face recognition algorithms, they hope to find a way to break through this problem through this experiment.
Among the four algorithms, the nearest neighbor classifier is the simplest, and its operation process is called correlation. However, this method has obvious drawbacks, such as, large amounts of data are required as learning sets, expensive logical relationship calculations, and large amounts of storage space. From the method of linear subspace, it is found by taking three-dimensional linear subspace of portrait that when the viewpoint is fixed and there is no shadow and noise influence, this algorithm is not only unaffected by lighting conditions but also very accurate. On the contrary, it needs to consider other factors such as distance or selection, which is a very expensive algorithm technique. The other two approaches have similarities, in that the FLD of PCA rain faces with feature faces all undergo dimensionality reduction to improve accuracy. However, PCA may confuse the scattered points in 2D to 1D images, leading to an increase in error rate.
The advantages and disadvantages can be more obviously compared by selecting four different but related algorithm technologies. However, the learning set used in the experiment is the same set of data as the test set. If the learning set data is larger than the test set data, the experimental results can be more comparable.

Technical quality
In the experiment, they tell two groups of databases respectively through four kinds of algorithm technology experiment, from which three kinds of conditions change. When only light conditions change, it is found that there are huge differences in the effects of the four algorithms on light deviation, with the fisherfaces algorithm having the best effect, the error rate is smaller than that of the feature face algorithm, and the time is shorter. In the context of facial expressions, eye wear and light conditions, the technical effect of fisherfaces algorithm is improved by increasing the number of changes in facial features, and the linear subspace algorithm is disappointing. Similarly, the fisherface algorithm achieves good performance in the variation of glasses conditions. Therefore, the fisherface algorithm is the most accurate of the four algorithms, and it is the most prominent in the changes of facial expression and glasses.
When Belhumeur et al. (1997) designed the experiment, they set up a different database from the one they used to get the experimental results, and the new database was better than the original one. New database also exist some suspects, however, a group of 330 faces data related to light conditions, another group of 160 portrait images related to facial expressions and light conditions, if put together two groups of data by upset that it becomes a new data set, and then find a set of the face is not set conditions as in the other group, a set of data that may be found on their technology is not affected by conditions of face recognition algorithm has more help.

Application and X-factor
Face recognition algorithm technology has been widely used, from mobile phone selfie camera to face recognition enterprise management, from surveillance camera to personal identity information recognition, life, the network has been widely used. Even in 1997, face recognition technology was used to hunt people suspected of being involved in a crime. Previously, face recognition technology was supposed to be accurate on 1D and 2D images, but now it can do 3D portrait recognition and even extract personal information from the iris of the eye. The impact of this technology on people's lives is still deepening. In China, the payment system will gradually replace QR code payment. However, there are still some unsecured aspects of the technology, such as the ability to unlock a phone or make payments using video, which uses a photo or a face, life will no longer be safe and secure.

Presentation
This article is very clear in structure and classification. In the introduction of the four algorithms, each algorithm is described, and its advantages and disadvantages are analyzed. At the time of drawing the experimental conclusion, the category is divided in detail, and four algorithms are compared. However, at the end, the Belhumeur et al. (1997) raised them own question but did not give the answer in this article. It would be more appealing if they could experiment and answer their questions, since face recognition technology is a topic that is closely linked to everyday and social life.

References
BEL97: Belhumeur, P.N., Hespanha, J.P.& Kriegman, D.J. 1997, 'Eigenfaces vs. Fisherfaces: Recognition Using Class Specific Linear Projection', IEEE TRANSACTIONS ON PATTERN ANALYSIS AND MACHINE INTELLIGENCE, VOL. 19, NO. 7, pp. 711-720.
