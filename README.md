### An evaluation of skewed tabulation and staged solving on the topic of Context-Free Language Reachability optimization

This is the README file of the reproduce package of the project paper "An evaluation of skewed tabulation and staged solving on the topic of Context-Free Language Reachability optimization".

### 1. download & import docker images

the graphs of the programs in SPEC CPU 2017 benchmark, along with the two artifacts, are packaged into the two docker images `skewedTabulation.tar` and `stagedSolving.tar`.

1. download the two docker image files through this link:

    https://pan.quark.cn/s/a3a887f136fd

2. run the `docker import` command to import these two images.

### 2. reproduce section 2

1. launch the docker image of `skewedTabulation.tar.`
2. run the script `/root/CFLSKewed/bench/myfullExp.sh.`.
3. the results will print on the screen.

### 3. reproduce section 3

1. launch the docker image of `stagedSolving.tar`.
2. run the script `/root/eval/run_all.sh`.
3. the results will be written into the files `aa-result.txt` and `vf-result.txt`.

### 4. reproduce section 4

1. launch the docker image of `skewedTabulation.tar`,
2. run the script `/root/CFLSkewed/bench/myfullExpStaged.sh`.
3. the results will be print on the screen.

### 5. more information

you can refer to the original READMEs of the two artifacts:

https://doi.org/10.6084/m9.figshare.26156944.v4

https://doi.org/10.5281/zenodo.10892936