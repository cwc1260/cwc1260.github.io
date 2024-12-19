---
layout: archive
title: ""
# permalink: /about/
permalink: /
author_profile: true
redirect_from:
  - /about/
  - /about.html
  # - /
---

I am currently a postdoctoral research fellow in the Computer Vision and Robotic Perception (CVRP) laboratory at <strong>National University of Singapore (NUS)</strong>, supervised by [Prof. Gim Hee Lee](https://www.comp.nus.edu.sg/~leegh/).  My research interests lie in 3D computer vision, especially in human hand pose estimation, motion detection and embodied AI.
I recived my Ph.D. degree in Artificial Intelligence from <strong>Sungkyunkwan University (SKKU)</strong> in 2024, advised by [Prof. Jong Hwan Ko](https://iris.skku.edu/professor/), and my M.S. degree in Artificial Intelligence from <strong>Sungkyunkwan University (SKKU)</strong> in 2020, advised by [Prof. Sukhan Lee](https://ieeexplore.ieee.org/author/37293425600).


News
======
<style>
  .news-container p {
    margin: 5px 0; /* 调整段落间距 */
    line-height: 1.2; /* 调整行高 */
  }

  .show-more-link {
    text-align: center;
    display: block;
    margin-top: 10px;
  }
</style>

<div class="news-container">
  <p>✌️[07.2024] One paper <a href="https://arxiv.org/abs/2407.20542">HandDAGT</a> is accepted at ECCV 2024!</p>
  <p>🎉[03.2024] Joined CVRP lab of NUS as a postdoctoral research fellow supervised by Gim Hee Lee!</p>
  <p>✌️[02.2024] One paper <a href="https://openaccess.thecvf.com/content/CVPR2024/papers/Cheng_HandDiff_3D_Hand_Pose_Estimation_with_Diffusion_on_Image-Point_Cloud_CVPR_2024_paper.pdf">HandDiff</a> is accepted at CVPR 2023 (<span style="color: red;">highlight</span>)!!</p>
  <p> 🎓[02.2024] Recieved my Ph.D. degree from Sungkyunkwan University.</p>
  <div id="hidden-news" style="display: none;">
    <p>✌️[07.2024] Two papers <a href="https://openaccess.thecvf.com/content/CVPR2024/papers/Cheng_HandDiff_3D_Hand_Pose_Estimation_with_Diffusion_on_Image-Point_Cloud_CVPR_2024_paper.pdf">HandR2N2</a>  <a href="https://openaccess.thecvf.com/content/ICCV2023/papers/Cheng_Multi-Scale_Bidirectional_Recurrent_Network_with_Hybrid_Correlation_for_Point_Cloud_ICCV_2023_paper.pdf">MSBRN</a> are accepted at ICCV 2023!</p>
    <!-- 你可以在这里添加更多隐藏的新闻项 -->
  </div>
</div>

<a href="#" class="show-more-link" id="show-more-link">⬇ SHOW MORE ⬇</a>

<script>
  document.getElementById('show-more-link').addEventListener('click', function(event) {
    event.preventDefault();
    var hiddenNews = document.getElementById('hidden-news');
    if (hiddenNews.style.display === 'none') {
      hiddenNews.style.display = 'block';
      this.textContent = '⬆ SHOW LESS ⬆';
    } else {
      hiddenNews.style.display = 'none';
      this.textContent = '⬇ SHOW MORE ⬇';
    }
  });
</script>


Featured Publications
======
<div style="display: flex; align-items: center; margin-bottom: 40px;">
  <img src="images/HandDGAT.png" alt="HandDAGT: A Denoising Adaptive Graph Transformer for 3D Hand Pose Estimation" style="width: 350px; height: auto; margin-right: 20px;">
  <div>
    <h3 style="margin: 0;"><a href="https://arxiv.org/abs/2407.20542" style="text-decoration: none;">HandDAGT: A Denoising Adaptive Graph Transformer for 3D Hand Pose Estimation</a></h3>
    <p style="margin: 5px 0;">
      <strong>Wencan Cheng</strong>,
      <a href="https://iris.skku.edu/authors/mp05_eunji_kim/">Eunji Kim</a>,
      <a href="https://iris.skku.edu/professor/">Jong Hwan Ko</a>
      <br>
      <strong>ECCV</strong>, 2024
      <br>
      <a href="https://arxiv.org/abs/2407.20542" style="text-decoration: none;">[PDF]</a>
      <a href="https://github.com/cwc1260/HandDAGT" style="text-decoration: none;">[Code]</a>
    </p>
  </div>
</div>

<div style="display: flex; align-items: center; margin-bottom: 40px;">
  <img src="images/HandDiff.png" alt="HandDiff: 3D Hand Pose Estimation with Diffusion on Image-Point Cloud" style="width: 350px; height: auto; margin-right: 20px;">
  <div>
    <h3 style="margin: 0;"><a href="https://openaccess.thecvf.com/content/CVPR2024/papers/Cheng_HandDiff_3D_Hand_Pose_Estimation_with_Diffusion_on_Image-Point_Cloud_CVPR_2024_paper.pdf" style="text-decoration: none;">HandDiff: 3D Hand Pose Estimation with Diffusion on Image-Point Cloud</a></h3>
    <p style="margin: 5px 0;">
      <strong>Wencan Cheng</strong>,
      <a href="https://ha0tang.github.io">Hao Tang</a>,
      <a href="https://www.trace.ethz.ch/team/members/luc.html">Luc Van Gool</a>
      <a href="https://iris.skku.edu/professor/">Jong Hwan Ko</a>
      <br>
      <strong>CVPR <span style="color: red;">highlight</span></strong>, 2024
      <br>
      <a href="https://openaccess.thecvf.com/content/CVPR2024/papers/Cheng_HandDiff_3D_Hand_Pose_Estimation_with_Diffusion_on_Image-Point_Cloud_CVPR_2024_paper.pdf" style="text-decoration: none;">[PDF]</a>
      <a href="https://github.com/cwc1260/HandDiff" style="text-decoration: none;">[Code]</a>
    </p>
  </div>
</div>

<div style="display: flex; align-items: center; margin-bottom: 40px;">
  <img src="images/MSBRN.png" alt="Multi-Scale Bidirectional Recurrent Network with Hybrid Correlation for Point Cloud Based Scene Flow Estimation" style="width: 350px; height: auto; margin-right: 20px;">
  <div>
    <h3 style="margin: 0;"><a href="https://openaccess.thecvf.com/content/ICCV2023/papers/Cheng_Multi-Scale_Bidirectional_Recurrent_Network_with_Hybrid_Correlation_for_Point_Cloud_ICCV_2023_paper.pdf" style="text-decoration: none;">Multi-Scale Bidirectional Recurrent Network with Hybrid Correlation for Point Cloud Based Scene Flow Estimation</a></h3>
    <p style="margin: 5px 0;">
      <strong>Wencan Cheng</strong>,
      <a href="https://iris.skku.edu/professor/">Jong Hwan Ko</a>
      <br>
      <strong>ICCV</strong>, 2023
      <br>
      <a href="https://openaccess.thecvf.com/content/ICCV2023/papers/Cheng_Multi-Scale_Bidirectional_Recurrent_Network_with_Hybrid_Correlation_for_Point_Cloud_ICCV_2023_paper.pdf" style="text-decoration: none;">[PDF]</a>
      <a href="https://github.com/cwc1260/MSBRN" style="text-decoration: none;">[Code]</a>
    </p>
  </div>
</div>

<div style="display: flex; align-items: center; margin-bottom: 40px;">
  <img src="images/HandR2N2.png" alt="HandR2N2: Iterative 3D Hand Pose Estimation Using a Residual Recurrent Neural Network" style="width: 350px; height: auto; margin-right: 20px;">
  <div>
    <h3 style="margin: 0;"><a href="https://openaccess.thecvf.com/content/ICCV2023/papers/Cheng_HandR2N2_Iterative_3D_Hand_Pose_Estimation_Using_a_Residual_Recurrent_ICCV_2023_paper.pdf" style="text-decoration: none;">HandR2N2: Iterative 3D Hand Pose Estimation Using a Residual Recurrent Neural Network</a></h3>
    <p style="margin: 5px 0;">
      <strong>Wencan Cheng</strong>,
      <a href="https://iris.skku.edu/professor/">Jong Hwan Ko</a>
      <br>
      <strong>ICCV</strong>, 2023
      <br>
      <a href="https://openaccess.thecvf.com/content/ICCV2023/papers/Cheng_HandR2N2_Iterative_3D_Hand_Pose_Estimation_Using_a_Residual_Recurrent_ICCV_2023_paper.pdf" style="text-decoration: none;">[PDF]</a>
      <a href="https://github.com/cwc1260/HandR2N2" style="text-decoration: none;">[Code]</a>
    </p>
  </div>
</div>

<div style="display: flex; align-items: center; margin-bottom: 40px;">
  <img src="images/dynamic.png" alt="Dynamic Inference Acceleration of 3D Point Cloud Deep Neural Networks Using Point Density and Entropy" style="width: 350px; height: auto; margin-right: 20px;">
  <div>
    <h3 style="margin: 0;"><a href="https://openaccess.thecvf.com/content/CVPR2023W/ECV/papers/Park_Dynamic_Inference_Acceleration_of_3D_Point_Cloud_Deep_Neural_Networks_CVPRW_2023_paper.pdf" style="text-decoration: none;">Dynamic Inference Acceleration of 3D Point Cloud Deep Neural Networks Using Point Density and Entropy</a></h3>
    <p style="margin: 5px 0;">
      Gyudo Park, SooHyeok Kang, <strong>Wencan Cheng</strong>,
      <a href="https://iris.skku.edu/professor/">Jong Hwan Ko</a>
      <br>
      CVPRW, 2023
      <br>
      <a href="https://openaccess.thecvf.com/content/CVPR2023W/ECV/papers/Park_Dynamic_Inference_Acceleration_of_3D_Point_Cloud_Deep_Neural_Networks_CVPRW_2023_paper.pdf" style="text-decoration: none;">[PDF]</a>
    </p>
  </div>
</div>


<div style="display: flex; align-items: center; margin-bottom: 40px;">
  <img src="images/BiFlow.png" alt="Bi-PointFlowNet: Bidirectional Learning for Point Cloud Based Scene Flow Estimation" style="width: 350px; height: auto; margin-right: 20px;">
  <div>
    <h3 style="margin: 0;"><a href="https://arxiv.org/abs/2207.07522" style="text-decoration: none;">Bi-PointFlowNet: Bidirectional Learning for Point Cloud Based Scene Flow Estimation</a></h3>
    <p style="margin: 5px 0;">
      <strong>Wencan Cheng</strong>,
      <a href="https://iris.skku.edu/professor/">Jong Hwan Ko</a>
      <br>
      <strong>ECCV <span style="color: red;">oral</span></strong>, 2022
      <br>
      <a href="https://arxiv.org/abs/2207.07522" style="text-decoration: none;">[PDF]</a>
      <a href="https://github.com/cwc1260/BiFlow" style="text-decoration: none;">[Code]</a>
    </p>
  </div>
</div>


<div style="display: flex; align-items: center; margin-bottom: 40px;">
  <img src="images/HandQuant.png" alt="Element-wise Partial Product Quantization for Efficient Deep Learning Accelerators" style="width: 350px; height: auto; margin-right: 20px;">
  <div>
    <h3 style="margin: 0;"><a href="https://ieeexplore.ieee.org/abstract/document/9954834" style="text-decoration: none;">Element-wise Partial Product Quantization for Efficient Deep Learning Accelerators</a></h3>
    <p style="margin: 5px 0;">
      Kim, Si Yeon,<strong>Wencan Cheng</strong>,
      <a href="https://iris.skku.edu/professor/">Jong Hwan Ko</a>
      <br>
      ICCE-Asia, 2021
      <br>
      <a href="https://ieeexplore.ieee.org/abstract/document/9954834" style="text-decoration: none;">[PDF]</a>
    </p>
  </div>
</div>


<div style="display: flex; align-items: center; margin-bottom: 40px;">
  <img src="images/HandFold.png" alt="HandFoldingNet: A 3D Hand Pose Estimation Network Using Multiscale-Feature Guided Folding of a 2D Hand Skeleton" style="width: 350px; height: auto; margin-right: 20px;">
  <div>
    <h3 style="margin: 0;"><a href="https://openaccess.thecvf.com/content/ICCV2021/papers/Cheng_HandFoldingNet_A_3D_Hand_Pose_Estimation_Network_Using_Multiscale-Feature_Guided_ICCV_2021_paper.pdf" style="text-decoration: none;">HandFoldingNet: A 3D Hand Pose Estimation Network Using Multiscale-Feature Guided Folding of a 2D Hand Skeleton</a></h3>
    <p style="margin: 5px 0;">
      <strong>Wencan Cheng</strong>, Jae Hyun Park, 
      <a href="https://iris.skku.edu/professor/">Jong Hwan Ko</a>
      <br>
      <strong>ICCV</strong>, 2021
      <br>
      <a href="https://openaccess.thecvf.com/content/ICCV2021/papers/Cheng_HandFoldingNet_A_3D_Hand_Pose_Estimation_Network_Using_Multiscale-Feature_Guided_ICCV_2021_paper.pdf" style="text-decoration: none;">[PDF]</a>
      <a href="https://github.com/cwc1260/HandFold" style="text-decoration: none;">[Code]</a>
    </p>
  </div>
</div>


<div style="display: flex; align-items: center; margin-bottom: 40px;">
  <img src="images/BIL.png" alt="https://link.springer.com/chapter/10.1007/978-3-030-33723-0_6" style="width: 350px; height: auto; margin-right: 20px;">
  <div>
    <h3 style="margin: 0;"><a href="https://ieeexplore.ieee.org/abstract/document/9954834" style="text-decoration: none;">Point auto-encoder and its application to 2D-3D transformation.</a></h3>
    <p style="margin: 5px 0;">
      <strong>Wencan Cheng</strong>,
      <a href="https://ieeexplore.ieee.org/author/37293425600">Sukhan Lee </a>
      <br>
      ISVC, 2020
      <br>
      <a href="https://link.springer.com/chapter/10.1007/978-3-030-33723-0_6" style="text-decoration: none;">[PDF]</a>
    </p>
  </div>
</div>
