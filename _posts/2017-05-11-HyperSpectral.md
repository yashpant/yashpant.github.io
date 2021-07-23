---
layout: post
title:  "Generalized Robust PCA"
date:   2017-05-11 21:36:43
categories: blog
---
We consider the generalized robust PCA problem, for more details please refer to the [<a href="/docs/Dictionary_based_generalization_of_robust_PCA_Sirisha_R.pdf">slides</a>].

<div><img src="/docs/grpca/main_fig.png" style="width:550px;display:block; margin: 0px auto;margin-top: -5px;margin-bottom: 5px;"/></div>


# Demo: Target detection in Hyperspectral imaging

 We have here a demo showing the performance of the proposed algorithm on the [Indian Pines] dataset. The video shows the recovery of class 16, the stone-steel towers, for increasing values of the regularization parameter, which penalizes the sparsity of the coefficient matrix. 

<br>
<div style="text-align: center">
<video style="display:block; margin: 0px auto;margin-top: -5px;margin-bottom: 5px;" width="620"  controls preload> 
    <source src="/docs/grpca/LplusDA_hyper_spectral.mp4"></source> 
    <source src="/docs/grpca/LplusDA_hyper_spectral.webm"></source> 
</video></div>
<br>

Interestingly, at about 5 sec. into the video, a diagonal line appears at the top right corner. This line corresponds to the rail-tracks in the scene, that is mostly composed of agricultural land, and are closely related to the spectral signatures of the stone-steel towers.  

[Indian Pines]:  http://www.ehu.eus/ccwintco/index.php?title=Hyperspectral_Remote_Sensing_Scenes

<br/>
<script  src="//platform.linkedin.com/in.js" type="text/javascript"> lang: en_US</script>
<script type="IN/Share"></script>    <a href="https://twitter.com/share" class="twitter-share-button" data-text="An interesting read " data-via="siri_r" data-count="none">Tweet</a> <script>!function(d,s,id){var js,fjs=d.getElementsByTagName(s)[0],p=/^http:/.test(d.location)?'http':'https';if(!d.getElementById(id)){js=d.createElement(s);js.id=id;js.src=p+'://platform.twitter.com/widgets.js';fjs.parentNode.insertBefore(js,fjs);}}(document, 'script', 'twitter-wjs');</script>
