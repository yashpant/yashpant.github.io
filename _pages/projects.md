---
layout: page
title: research
permalink: /projects/
description: Also see the publications page
---
### Learning-to-Fly (L2F): Learning-based mission-aware Collision Avoidance

In order for fleets of drones managed by different operators to share an airspace, they require a fast, reliable and fair Collision Avoidance (CA) approach to ensure safety. This project aims to develop such methods by combining learning-based decision making and decentralized Model Predictive Control to perform on-the-fly, predictive Collision Avoidance (CA) between two (co-operative) drones. In addition to performing CA in real-time, L2F also ensures that the drones do not violate their original mission requirements. The video below shows a simulation where two pairs of drones are have conflicting pre-planned trajectories, and also shows the resulting safe trajectories obtained via L2F.

<iframe width="640" height="480" src="https://www.youtube.com/embed/KXXPIx0Pnbw" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>


#### Related Publications:

1. Rodionova, Pant, Jang, Abbas, Mangharam. Mission-aware, [Learning-to-Fly: Learning-based Collision Avoidance for Scalable Urban Air Mobility](https://arxiv.org/abs/2006.13267){:target="_blank"}. IEEE International Conference on Intelligent Transportation Systems (ITSC), 2020.
2. Jang, Pant, Rodionova,  Mangharam. Learning-to-Fly RL: Reinforcement Learning-based Collision Avoidance for Scalable Urban Air Mobility. AIAA/IEEE Digital Avionics Systems Conference (DASC), 2020.

### Fly-by-Logic: Safe-planning for Drone Fleets

<!--- <iframe width="480" height="360" src="https://www.youtube.com/embed/7LvY-Bj85Us" frameborder="0" allowfullscreen></iframe> --->

Safe planning and control of multi-rotor drone fleets performing complex missions has been a challenging problem. Methods that offer guarantees on safety and mission satisfaction generally do not scale well. On the other hand, more computationally tractable approaches do not offer any safety guarantees. This project develops methods that overcomes these limitations for a wide variety of missions, e.g. the video below shows a mission where 2 pairs of drones are tasked with patrolling two regions within predefined time intervals, and while avoiding a no-fly zone and collisions with each other.

<iframe width="640" height="480" src="https://www.youtube.com/embed/xBQnEweVwZs" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>


<!---
In general the missions that we consider that can consist of a combination of the following objectives: 

1. spatial objectives, e.g. geofenced no fly zones, or delivery zones, 
2. temporal objectives, e.g. a time window to monitor wireless signal strengths in an area,
3. reactive objectives, e.g. in case of a drone failure, another drone picks up its mission.

Our approach [1], while being computationally tractable, offers guarantees on mission satisfaction, and avoids the oversimplifying abstractions found in many methods. We use Signal Temporal Logic (STL) for mission specification, which allows us to specify a wide variety of missions. Starting from the given STL mission specification, we formulate a non-convex optimization problem, solved to local optimality in a centralized manner, that incorporates an efficient representation of the multi-rotor drone's trajectories. We also formulate additional constraints which result in trajectories that can be tracked near perfectly by off-the-shelf lower level controllers. 

We show the performance, scalability and real-time applicability of our method through simulations and experiments on actual quadrotor drones. 
--->
#### Related Publications:

1. Pant, Quaye, Abbas, Varre, Mangharam. [Fly-by-Logic: A Tool for Unmanned Aircraft System Fleet Planning using Temporal Logic](https://repository.upenn.edu/cgi/viewcontent.cgi?article=1139&context=mlab_papers){:target="_blank"}, NASA FM, 2019.
2. Pant, Abbas, Quaye, Mangharam. [Fly-by-Logic: Control of Multi-Drone Fleets with Temporal Logic Objectives](https://repository.upenn.edu/cgi/viewcontent.cgi?article=1127&context=mlab_papers){:target="_blank"}, ICCPS, 2018.
3. Pant, Abbas, Mangharam. Smooth Operator, [Smooth Operator: Control using the Smooth Robustness of Temporal Logic](https://repository.upenn.edu/cgi/viewcontent.cgi?article=1119&context=mlab_papers){:target="_blank"}, CCTA, 2017.

### Co-design of Anytime Computation and Control for Autonomous Systems


Perception-based state estimation for autonomous system is generally a computationally expensive process, both in terms of execution time and energy consumption on the computation platform. This work develops a contract-driven framework for closed-loop interplay between: a) a predictive control algorithm and b) a flexible [*anytime*](https://en.wikipedia.org/wiki/Anytime_algorithm){:target="_blank"} perception-based state estimator to trade-off computation time (and energy) for estimation accuracy while guaranteeing robust (or chance-constrained) constraint satisfaction of the autonomous system. Experimental results show the benefit of this framework over approaches that do not leverage this co-design.

<img src="/assets/img/anytime.png" alt="drawing" width="700"/>

#### Related Publications:

1. Pant, Abbas, Mohta, Quaye, Nghiem, Devietti, Mangharam. [Anytime Computation and Control for Autonomous Systems](https://ieeexplore.ieee.org/abstract/document/9051687){:target="_blank"}, IEEE Transactions on Control Systems Technology, 2020.
2. Pant, Abbas, Mangharam. [Robust Model Predictive Control for Non-Linear Systems with Input and State Constraints via Feedback Linearization](https://repository.upenn.edu/cgi/viewcontent.cgi?article=1113&context=mlab_papers){:target="_blank"}, CDC, 2016.
3. Pant, Abbas, Mohta, Nghiem, Devietti, Mangharam. [Co-design of Anytime Computation and Robust Control](https://repository.upenn.edu/cgi/viewcontent.cgi?article=1110&context=mlab_papers){:target="_blank"}, RTSS, 2015.
4. Pant, Abbas, Nischal, Kelkar, Kumar, Devietti, Mangharam [Power-efficient Algorithms for Autonomous Navigation](https://ieeexplore.ieee.org/document/7385991){:target="_blank"}, ICCSE, 2015.

### Protodrive: Peak Power Reduction for Hybrid Energy Storage Systems with Limited Load Forecasts

<iframe width="640" height="480" src="https://www.youtube.com/embed/ZWIuTwJ4Npk" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

#### Related Publications:

1. Pant, Nghiem, Mangharam. [Peak Power Reduction in Hybrid Energy Systems with Limited Load Forecasts](https://repository.upenn.edu/cgi/viewcontent.cgi?article=1084&context=mlab_papers){:target="_blank"}, ACC, 2014.
2. Price, Jain, Pant, Mangharam. Final Report: Protodrive: Simulation of Electric Vehicle Powertrains, World Embedded Software Competition (*third place finish*), 2013.
### AutoPlug: Hardware-in-the-loop Electronic Controller Unit Testing

<iframe width="640" height="480" src="https://www.youtube.com/embed/vchbkNtnr-U" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

#### Related Publications:

1. Drolia, Wang, Pant, Mangharam. [Autoplug: An automotive test-bed for electronic controller unit testing and verification](https://repository.upenn.edu/cgi/viewcontent.cgi?article=1045&context=mlab_papers){:target="_blank"}, ITSC, 2011.

<!--- <iframe width="560" height="315" src="https://www.youtube.com/embed/7LvY-Bj85Us" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe> 


<video width="320" height="240" controls>
  <source src="~/Videos/8Quad.avi" type="video/avi">
</video>--->
<!---
<div class="img_row">
    <img class="col one left" src="{{ site.baseurl }}/assets/img/1.jpg" alt="" title="example image"/>
    <img class="col one left" src="{{ site.baseurl }}/assets/img/2.jpg" alt="" title="example image"/>
    <img class="col one left" src="{{ site.baseurl }}/assets/img/3.jpg" alt="" title="example image"/>
</div>
--->

<!---
{% for project in site.projects %}

{% if project.redirect %}
<div class="project">
    <div class="thumbnail">
        <a href="{{ project.redirect }}" target="_blank">
        {% if project.img %}
        <img class="thumbnail" src="{{ project.img | prepend: site.baseurl | prepend: site.url }}"/>
        {% else %}
        <div class="thumbnail blankbox"></div>
        {% endif %}    
        <span>
            <h1>{{ project.title }}</h1>
            <br/>
            <p>{{ project.description }}</p>
        </span>
        </a>
    </div>
</div>
{% else %}

<div class="project ">
    <div class="thumbnail">
        <a href="{{ project.url | prepend: site.baseurl | prepend: site.url }}">
        {% if project.img %}
        <img class="thumbnail" src="{{ project.img | prepend: site.baseurl | prepend: site.url }}"/>
        {% else %}
        <div class="thumbnail blankbox"></div>
        {% endif %}    
        <span>
            <h1>{{ project.title }}</h1>
            <br/>
            <p>{{ project.description }}</p>
        </span>
        </a>
    </div>
</div>

{% endif %}

{% endfor %}
--->
