# Viterbi Character Correction

## Overview
Viterbi is a Python 3.5 application developed on Jupyter Notebook, mainly to correct the misspelled characters. The project details and the data were obtained from [COS 402: Artificial Intelligence Homework #5 - Correcting typos without a dictionary](http://www.cs.princeton.edu/courses/archive/fall04/cos402/assignments/viterbi/index.html).

## The Project
An Hidden Markov Model was developed to predict the following character.

The Initial State probabilities of each character are given in the table below.

| Character | Probability  |
|:---------:|:------------:|
|    a      | 0.1059087895 |
|    b      | 0.0500994622 |
|    c      | 0.0418846239 |
|    d      | 0.0285493259 |
|    e      | 0.0299123259 |
|    f      | 0.0350327857 |
|    g      | 0.0162086495 |
|    h      | 0.0358063803 |
|    i      | 0.0808590584 |
|    j      | 0.0017682163 |
|    k      | 0.0028733515 |
|    l      | 0.0241656229 |
|    m      | 0.0411847049 |
|    n      | 0.0251234068 |
|    o      | 0.0810800855 |
|    p      | 0.051757165  |
|    q      | 0.0010314595 |
|    r      | 0.0265600825 |
|    s      | 0.0745597878 |
|    t      | 0.1736904148 |
|    u      | 0.0101672438 |
|    v      | 0.0047889192 |
|    w      | 0.05474103   |
|    x      | 0            |
|    y      | 0.0022471082 |
|    z      | 0            |


The success rate of the algorithm is given in the following two tables.


| Words    | Numbers		  | Rates 	          |
|	       | Correct  | Wrong | Correct  | Wrong  |
|:--------:|:--------:|:-----:|:--------:|:------:|
| Before   |	2121  |  1290 |  62.18%	 | 37.82% |
| Viterbi  |    2363  |  1048 |  69.28%	 | 30.72% |


| Characters | Numbers          | Rates 	        |
|            | Correct  | Wrong | Correct  | Wrong  |
|:----------:|:--------:|:-----:|:--------:|:------:|
| Before     |	14934   |  1654 |  90.03%  |  9.97% |
| Viterbi    |  15258   |  1330 |  91.98%  |  8.02% |


## Dependencies
* numpy library is required to perform matrix operations.


















