# Final Artificial Intelligence Project: Hi, Gomoku!

This repository contains the final project of (Fudan University) DATA130008: Introduction to Artificial Intelligence

## Acknowledgement
Thanks to Dr.[Zhongyu Wei](http://www.sdspeople.fudan.edu.cn/zywei/), who is the Instructor of this course.

## Remark
* This Project is a group work implemented by [Shun Zhang](https://github.com/zhangshun97), [Pingxuan Huang](https://github.com/Explorerhpx) and [Donghao Li](https://github.com/Lidonghao1996).  Codes are available, if you want to utilize them, however, please indicate the source;
* If you have any question, please don't hesitate to contact *1336076538@qq.com* for help.
* Some related papers are provided as references (you can obtain them at the [*References*](#reference) part);

## Introduction

### Requirement

*More detailed information could be found in the [Introduction.pdf]();*

* Students are required to implement an AI to play [Gomoku](https://en.wikipedia.org/wiki/Gomoku);
* Gomoku Rule: Free Gomoku Rule (five or more);
* The Gomoku AIs are based on the [Gomocup standard](http://gomocup.org/). You can create your own `AI.exe` through `pisqpipe`, related codes and document are [here]();

### Our work

*Please check [Report.pdf]() for the detail information about our algorithms, AIs and experiments.*

Based on 3 different algorithms, our groups successfully implemented 3 AIs:
* [Monte-Carlo Tree Search]()
* [Genetic Algorithm]()
* [Minimax Search]()

## Note

All the algorithms can be packed into a **win32** *exe* (less than 20M with Numpy version 1.13.1) with the help of `pisqpipe`. However, since the `pisqpipe`  platform is not perfect, we provided the terminal APIs. Therefore, you can easily play with our AIs through command `$python AI-name.py`. 

## <span id="reference"> References </span>
\[1\] Jun Hwan Kang,Hang Joon Kim, Effective Monte-Carlo Tree Search Strategies for Gomoku AI, IJCTA, 9(10), 2016, pp. 4833-4841

\[2\] Junru Wanga, Lan Huangb,Evolving Gomoku Solver by Genetic Algorithm,IEEE WARTIA,2014

\[3\] JINXING XIE and JIEFANG DONG,Heuristic Genetic Algorithms for General Capacitated Lot-Sizing Problems,2001

\[4\] Louis Victor Allis,Searching for Solutions in Games and Articial Intelligence,Version 8.0 of July 1, 1994
