# Awesome2Dmaterials  [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

A curated list of resources dedicated to 2D materials.

<!-- We have pages for other topics: [awesome-rnn](https://github.com/kjw0612/awesome-rnn), [awesome-deep-vision](https://github.com/kjw0612/awesome-deep-vision), [awesome-random-forest](https://github.com/kjw0612/awesome-random-forest) -->

Maintainers: [Rongzhi Dong](http://www.cse.sc.edu), [Jianjun Hu](http://www.cse.sc.edu/~jianjunh)  from University of South Carolina

We are looking for more contributors and maintainers!


## Contributing
Please feel free to [pull requests](https://github.com/usccolumbia/awesome2dmaterials/pulls)

## Table of Contents
 - [Researchers](#researchers)
 - [Theory](#theory)
   - [Lectures](#lectures)
   - [Books](#books)
   - [Surveys](#surveys)
   - [Papers / Thesis](#papers--thesis)
 - [Applications](#applications)
   - [Game Playing](#game-playing)
   - [Robotics](#robotics)
   - [Control](#control)
   - [Operations Research](#operations-research)
   - [Human Computer Interaction](#human-computer-interaction)
 - [Codes](#codes)
 - [Tutorials / Websites](#tutorials--websites)
 - [Databases](#Databases)
 - [Open Source Reinforcement Learning Platforms](#open-source-reinforcement-learning-platforms)

## Codes
 - Codes for examples and exercises in Richard Sutton and Andrew Barto's Reinforcement Learning: An Introduction
    - [Python Code](https://github.com/ShangtongZhang/reinforcement-learning-an-introduction)
    - [MATLAB Code (BROKEN LINK)](http://waxworksmath.com/Authors/N_Z/Sutton/sutton.html)
    - [C/Lisp Code](http://incompleteideas.net/book/code/code2nd.html)
    - [Julia Code](https://github.com/Ju-jl/ReinforcementLearningAnIntroduction.jl)
    - [Book](http://incompleteideas.net/book/RLbook2018.pdf)
    - [Exercise Solutions](https://github.com/LyWangPX/Reinforcement-Learning-2nd-Edition-by-Sutton-Exercise-Solutions)
 - Simulation code for Reinforcement Learning Control Problems
    - [Pole-Cart Problem](http://pages.cs.wisc.edu/~finton/poledriver.html)
    - [Q-learning Controller](http://pages.cs.wisc.edu/~finton/qcontroller.html)
 - [MATLAB Environment and GUI for Reinforcement Learning](http://www.cs.colostate.edu/~anderson/res/rl/matlabpaper/rl.html)
 

## Research Labs
 Labs
  - [MIT Graphene](https://scholar.google.com/citations?hl=en&user=kJhEIh0AAAAJ&view_op=list_works&sortby=pubdate)

 Researers
  - [MIT Graphene](https://scholar.google.com/citations?hl=en&user=kJhEIh0AAAAJ&view_op=list_works&sortby=pubdate)


## Theory

### Research Groups
- [DeepMind x UCL] [Reinforcement Learning Lecture Series 2021](https://deepmind.com/learning-resources/reinforcement-learning-series-2021)
 - [UCL] [COMPM050/COMPGI13 Reinforcement Learning](http://www0.cs.ucl.ac.uk/staff/d.silver/web/Teaching.html) by David Silver
 - [UC Berkeley] CS188 Artificial Intelligence by Pieter Abbeel
   - [Lecture 8: Markov Decision Processes 1](https://www.youtube.com/watch?v=i0o-ui1N35U)
   - [Lecture 9: Markov Decision Processes 2](https://www.youtube.com/watch?v=Csiiv6WGzKM)
   - [Lecture 10: Reinforcement Learning 1](https://www.youtube.com/watch?v=ifma8G7LegE)
   - [Lecture 11: Reinforcement Learning 2](https://www.youtube.com/watch?v=Si1_YTw960c)
 
    

### Books
 - Richard Sutton and Andrew Barto, Reinforcement Learning: An Introduction (1st Edition, 1998) [[Book]](http://incompleteideas.net/book/ebook/the-book.html) [[Code]](http://incompleteideas.net/book/code/code.html)
 


### Surveys
 - Leslie Pack Kaelbling, Michael L. Littman, Andrew W. Moore, Reinforcement Learning: A Survey (JAIR 1996) [[Paper]](https://www.jair.org/index.php/jair/article/download/10166/24110/)
 
### Papers / Thesis
Foundational Papers
 - Marvin Minsky, Steps toward Artificial Intelligence, Proceedings of the IRE, 1961. [[DOI]](https://dx.doi.org/10.1109/JRPROC.1961.287775) [[Paper]](http://staffweb.worc.ac.uk/DrC/Courses%202010-11/Comp%203104/Tutor%20Inputs/Session%209%20Prep/Reading%20material/Minsky60steps.pdf) (discusses issues in RL such as the "credit assignment problem")

  
Methods
 - Dynamic Programming (DP):
   - Christopher J. C. H. Watkins, Learning from Delayed Rewards, Ph.D. Thesis, Cambridge University, 1989. [[Thesis]](https://www.cs.rhul.ac.uk/home/chrisw/new_thesis.pdf)
 - Monte Carlo:
   - Andrew Barto, Michael Duff, Monte Carlo Inversion and Reinforcement Learning, NIPS, 1994. [[Paper]](http://papers.nips.cc/paper/865-monte-carlo-matrix-inversion-and-reinforcement-learning.pdf)
   - Satinder P. Singh, Richard S. Sutton, Reinforcement Learning with Replacing Eligibility Traces, Machine Learning, 1996. [[Paper]](http://www-all.cs.umass.edu/pubs/1995_96/singh_s_ML96.pdf)
 

    

## Applications
### Game Playing
Traditional Games
  - Backgammon - Gerald Tesauro, "TD-Gammon" game play using TD(λ) (ACM 1995) [[Paper]](http://www.bkgm.com/articles/tesauro/tdl.html)
  - Chess - Jonathan Baxter, Andrew Tridgell and Lex Weaver, "KnightCap" program using TD(λ) (1999) [[arXiv]](http://arxiv.org/pdf/cs/9901002v1.pdf)
  - Chess - Matthew Lai, Giraffe: Using deep reinforcement learning to play chess (2015) [[arXiv]](http://arxiv.org/pdf/1509.01549v2.pdf)

Computer Games
  - Atari 2600 Games - Volodymyr Mnih, Koray Kavukcuoglu, David Silver et al., Human-level Control through Deep Reinforcement Learning (Nature 2015) [[DOI]](https://dx.doi.org/doi:10.1038/nature14236) [[Paper]](http://www.readcube.com/articles/10.1038%2Fnature14236?shared_access_token=Lo_2hFdW4MuqEcF3CVBZm9RgN0jAjWel9jnR3ZoTv0P5kedCCNjz3FJ2FhQCgXkApOr3ZSsJAldp-tw3IWgTseRnLpAc9xQq-vTA2Z5Ji9lg16_WvCy4SaOgpK5XXA6ecqo8d8J7l4EJsdjwai53GqKt-7JuioG0r3iV67MQIro74l6IxvmcVNKBgOwiMGi8U0izJStLpmQp6Vmi_8Lw_A%3D%3D) [[Code]](https://sites.google.com/a/deepmind.com/dqn/) [[Video]](https://www.youtube.com/watch?v=iqXKQf2BOSE)
  - Flappy Bird - Sarvagya Vaish, [Flappy Bird Reinforcement Learning](https://github.com/SarvagyaVaish/FlappyBirdRL) [[Video]](https://www.youtube.com/watch?v=xM62SpKAZHU)
  




## Codes
 - Codes for examples and exercises in Richard Sutton and Andrew Barto's [Book](#books) Reinforcement Learning: An Introduction
    - [Python Code](https://github.com/ShangtongZhang/reinforcement-learning-an-introduction) (2nd Edition)
    - [MATLAB Code](https://waxworksmath.com/Authors/N_Z/Sutton/RLAI_1st_Edition/sutton.html) (1st Edition)
 - Simulation code for Reinforcement Learning Control Problems
    - [Pole-Cart Problem](http://pages.cs.wisc.edu/~finton/poledriver.html)
    - [Q-learning Controller](http://pages.cs.wisc.edu/~finton/qcontroller.html)
 - [MATLAB Environment and GUI for Reinforcement Learning](http://www.cs.colostate.edu/~anderson/res/rl/matlabpaper/rl.html)
 
 
 
 
 ## Tutorials / Websites
  - Mance Harmon and Stephanie Harmon, [Reinforcement Learning: A Tutorial](http://old.nbu.bg/cogs/events/2000/Readings/Petrov/rltutorial.pdf)
  - C. Igel, M.A. Riedmiller, et al., Reinforcement Learning in a Nutshell, ESANN, 2007. [[Paper]](http://image.diku.dk/igel/paper/RLiaN.pdf)
  - UNSW - [Reinforcement Learning](http://www.cse.unsw.edu.au/~cs9417ml/RL1/index.html)
    - [Introduction](http://www.cse.unsw.edu.au/~cs9417ml/RL1/introduction.html)
    - [TD-Learning](http://www.cse.unsw.edu.au/~cs9417ml/RL1/tdlearning.html)
    - [Q-Learning and SARSA](http://www.cse.unsw.edu.au/~cs9417ml/RL1/algorithms.html)
    - [Applet for "Cat and Mouse" Game](http://www.cse.unsw.edu.au/~cs9417ml/RL1/applet.html)
  


## Databases
 - [Real-world demonstrations of Reinforcement Learning](http://www.dcsc.tudelft.nl/~robotics/media.html)
 - [Deep Q-Learning Demo](http://cs.stanford.edu/people/karpathy/convnetjs/demo/rldemo.html) - A deep Q learning demonstration using ConvNetJS
 - [Deep Q-Learning with Tensor Flow](https://github.com/nivwusquorum/tensorflow-deepq) - A deep Q learning demonstration using Google Tensorflow
 - [Reinforcement Learning Demo](http://cs.stanford.edu/people/karpathy/reinforcejs/) - A reinforcement learning demo using reinforcejs by Andrej Karpathy


## Open Source Reinforcement Learning Platforms
- [OpenAI gym](https://github.com/openai/gym) - A toolkit for developing and comparing reinforcement learning algorithms


## valuable Contributors👩‍💻👨‍💻 :

<p align="center"><a href="">
  <img src="" />
</a></p>
