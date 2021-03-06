<center><h1 class="rsection"><b>Q-Learning for autonomous navigation of UAVs in indoor environments</b></h1></center>

<center><h2><b>Advanced Flight Simulation Laboratory, Aerospace Engineering Division, IISc.</b></h2></center>

<div class="container-fluid">
  <div class="row">
    <!-- <div class="col-md-6">
        <img class="rimg" src="{{ site.github.url }}/media/biped_trained.gif" />
    </div> -->
    <div class="col-md-12">
        <!-- <h3 class="rtitle"><b>Bipedal walking robot using Deep Deterministic Policy Gradient.</b></h3> -->
        <p style="text-align:justify; font-family: 'Merriweather','Hiragino Sans GB','Microsoft YaHei', 'WenQuanYi Micro Hei', sans-serif;">
        Indoor Path Planning and Navigation of an ArDrone based on simple <strong>PID control+Q-Learning</strong>. The quadrotor learns to manoeuvres towards the goal point, along the uniform grid distribution(5X5) in the simulation environment based on a reward of -1 while not ending up in the goal state and a reward of +100 for reaching the goal.
        </p>
        <br>
        <center>
            <div class="image-wrapper">
                <a class ="image-popup" href="https://nav74neet.github.io/media/drone_qlearning.gif" title="UAV">
                    <img src="https://nav74neet.github.io/media/drone_qlearning.gif" alt="UAV" style="border:2px solid black;" align="center">
                </a>
                <p class="image-caption" style="font-size:14px; text-align: center;">
                    Autonomous navigation from start to goal position.
                </p>
            </div>
        </center>
        <p style="text-align:justify; font-family: 'Merriweather', 'Hiragino Sans GB','Microsoft YaHei', 'WenQuanYi Micro Hei', sans-serif;">
            <b>Reference:</b> Pham, Huy X., et al. "<b>Autonomous uav navigation using reinforcement learning.</b>" arXiv preprint arXiv:1801.05086 (2018).[<a href="https://arxiv.org/abs/1801.05086" class="md-link">arxiv</a>]</p>
        <br>
        <p style="text-align:justify; font-family: 'Merriweather', 'Hiragino Sans GB', 'Microsoft YaHei', 'WenQuanYi Micro Hei', sans-serif;">
        <!-- <img class="center" src="{{ site.github.url }}/media/drone_qlearning.gif" /> -->
        <a href="https://github.com/nav74neet/rl_ardrone" class="md-link btn-default btn rbtn">Code</a>
        <!-- <a href="https://arxiv.org/abs/1801.05086" class="md-link btn-default btn rbtn">Paper</a> -->
        <a href="https://www.youtube.com/watch?v=SDqPfhUeoCo&feature=youtu.be" class="md-link btn-default btn rbtn">Video</a>
        </p>
  </div>
</div>
<br>