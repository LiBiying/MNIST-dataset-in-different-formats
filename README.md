# MNIST-dataset-in-different-formats
Just a MNIST dataset in different formats

~~~
THE MNIST DATABASE of handwritten digits

Yann LeCun, Courant Institute, NYU
Corinna Cortes, Google Labs, New York
Christopher J.C. Burges, Microsoft Research, Redmond

Just a mirror of http://yann.lecun.com/exdb/mnist/
~~~

For classification error % results introduced in literature please refer to
~~~
1. http://yann.lecun.com/exdb/mnist/
2. http://rodrigob.github.io/are_we_there_yet/build/classification_datasets_results.html#4d4e495354
~~~

For examples and practical results:
~~~
1) https://www.kaggle.com/c/digit-recognizer
~~~

Data folder:
~~~
1) Original dataset - Original MNIST dataset in binary format(not compressed)
        http://yann.lecun.com/exdb/mnist/
2) CSV format - MNIST IN CSV fromat
        http://pjreddie.com/projects/mnist-in-csv/
3) Matlab format - MNIST IN Matlab .mat fromat
        http://ufldl.stanford.edu/wiki/index.php/Using_the_MNIST_Dataset
        also not conventional .mat can be found here http://www.cs.nyu.edu/~roweis/data.html
~~~

How to load MNIST in X language:
~~~
in R: 
  https://gist.github.com/brendano/39760
in Python:
        1. https://github.com/sorki/python-mnist
        
        2. using sklearn.datasets.fetch_mldata                      
        http://scikit-learn.org/stable/datasets/#downloading-datasets-from-the-mldata-org-repository
        
        3. Also you can convert MNIST to csv and read .csv file in python.
in C++:
  http://stackoverflow.com/questions/8286668/how-to-read-mnist-data-in-c
  https://compvisionlab.wordpress.com/2014/01/01/c-code-for-reading-mnist-data-set/
in Java:
  http://stackoverflow.com/questions/8286668/how-to-read-mnist-data-in-c
in F#:
  http://stackoverflow.com/questions/19370314/reading-the-mnist-dataset-using-f
  
  
~~~

Visualization of MNIST:
1. t-sne
      http://lvdmaaten.github.io/tsne/
