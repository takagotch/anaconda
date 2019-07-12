### anaconda
---
https://anaconda.org/anaconda/python

https://github.com/Anaconda-Platform


### miniconda(win)
https://conda.io/miniconda.html



### conda
https://conda.io/docs/user-guide/install/download.html

#### sublime text
https://github.com/DamnWidget/anaconda

```
where python
conda-build recipeDirectory --python=3.5
conda build --test <path to package>.tar.bz2
conda skeleton pypi sep
cd sep

conda build
conda config --set anaconda_upload yes
```

```
requirements:
  host:
    - python
    - numpy x.x
    
  run:
    - python
    - numpy x.x
    
test:
  imports:
    - sep
  
patches:
  - 0001-windowshdf5.patch
  - 0002-multiprocesor.patch
  - 0003-disable_jpeg12.patch
```

