
<h1 class="rsection"><b>Bipedal walking robot using Deep Deterministic Policy Gradient</b></h1>

<h2><b>Computational Intelligence Laboratory, Aerospace Engineering Division, IISc.</b></h2>

<div class="container-fluid">
  <div class="row">
    <!-- <div class="col-md-6">
        <img class="rimg" src="{{ site.github.url }}/media/biped_trained.gif" />
    </div> -->
    <div class="col-md-12">
        <!-- <h3 class="rtitle"><b>Bipedal walking robot using Deep Deterministic Policy Gradient.</b></h3> -->
        <p style="text-align:justify">
        Machine learning algorithms have found several applications in the field of robotics and control systems. The control systems community has started to show interest towards several machine learning algorithms from the sub-domains such as supervised learning, imitation learning and reinforcement learning to achieve autonomous control and intelligent decision making. Amongst many complex control problems, stable bipedal walking has been the most challenging problem.</p> 
        <p style="text-align:justify">
        The autonomous stable walking of the planar bipedal walker in simulation environment is achieved using <strong>Deep Deterministic Policy Gradient(DDPG)</strong> based on an <strong>actor-critic learning framework</strong> [for continuos action space]. The robot demonstrates successful walking behaviour by learning through several of its trial and errors, without any prior knowledge of itself or the world dynamics.
        </p>
        <p style="text-align:justify">
        After training the model in simulation, it was observed that, with a proper shaped reward function, the robot achieved faster walking or even rendered a running gait with an average speed of 0.83 m/s. The gait pattern of the bipedal walker was compared with the actual human walking pattern. The results show that the bipedal walking pattern had similar characteristics to that of a human walking pattern.</p>
        <a href="https://github.com/nav74neet/ddpg_biped" class="md-link btn-default btn rbtn">Code</a>
        <a href="https://arxiv.org/abs/1807.05924" class="md-link btn-default btn rbtn">Paper</a>
        <a href="https://www.youtube.com/watch?v=Q4N78P7cink" class="md-link btn-default btn rbtn">Video</a>
    </div>
  </div>
</div>
<br>