


# Face Recognition 
- this is the implmentation of eigenfaces algorithm 
- EigenFaces Algorithm is simply using LDA or PCA for reduce dimension then applying a simple classifier
- We hace used ![ORL Faces Dataset](http://nimfa.biolab.si/nimfa.examples.orl_images.html)
- ORL Datasaet has 10 images paer 40 subjects. Every image is a grayscale image of size 92x112.
- there too much graphs in the notebook because It was our first time exploring the field.
- results ![](results/k_values.jpg)
- in this graph you will find that always LDA getting a higher accuracy , and that's expected because LDA is considering the labels 
- PCA Algorithm ![](results/pca.jpg)
- LDA Algorithm ![](results/lda.jpg)
- to use LDA for multiclass we must modify it 
	- calculate the mean vector for each class
	- We have modifed B Matrix to Sb ![](results/Sb.jpg)
- refrences
	-  data minning and analysis book(free)
	- [web sitea](http://www.dataminingbook.info/pmwiki.php)

	
