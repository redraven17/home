---
layout: default
title: ""
permalink: /esac/
author_profile: false
---

<center><h1>Evolve To Control: Evolution-based Soft Actor-Critic for Scalable Reinforcement Learning</h1></center>  

<pre>
<p align="center">      <img src="/images/cmte.PNG" height="125" widht="125"/>              <img src="/images/rbc.png" height="100" widht="100"/>             <img src="/images/uoft.png" height="100" widht="100"/></p>

<center><h3>          Karush Suri                 Xiao Qi Shi                 Yuri A. Lawryshyn        Konstantinos N. Plataniotis<br/>
    University of Toronto         RBC Captial Markets           University of Toronto        University of Toronto<br/>
karush.suri@mail.utoronto.ca     xiaoqi.shi@borealisai.ca     yuri.lawryshyn@utoronto.ca     kostas@ece.utoronto.ca</h3></center>
</pre>


<h2>About ESAC</h2>

Evolution-based   Soft   Actor   Critic(ESAC) is  an  algorithm  combining  Evolution Strategies (ES)  with  Soft Actor-Critic (SAC)  for state-of-the-performance equivalent to SAC and scalability comparable to ES. ESAC abstracts exploration from exploitation by exploring policies in weight space using evolutions and optimizing gradient-based knowledge using the SAC framework. ESAC makes use ofa novel soft winner selection function  and carries out genetic crossovers in hindsight. ESAC also introduces the novel Automatic Mutation Tuning (AMT) which maximizes the mutation rate of ES in a small clipped region and provides significant hyperparameter robustness.  


<p align="center"><img src="/images/schematic.gif" height="400" width="650" /></p>


<h2>Scalable Reinforcement Learning</h2>

Concepts and applications of Reinforcement Learning (RL) have seen a tremendous growth over the past decade. These consist of applications in arcade games, board games and lately, robotic control tasks. Primary reason for this growth is the usage of computationally efficient function approximators such as neural networks. Modern-day RL algorithms make use of parallelization to reduce training times and boost agent’s performance through effective exploration giving rise to scalable methods, commonly referred to as Scalable Reinforcement Learning (SRL). However,a number of open problems such as approximation bias, lack of scalability in the case of long time horizons and lack of diverse exploration restrict the application of SRL to complex control and robotic tasks.  


