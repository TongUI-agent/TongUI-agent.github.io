<template>

  <head>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.1/css/all.min.css">
    <!-- <meta charset="UTF-8"> -->
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
  </head>
  <div class="main">
    <div class="section header">
      <div class="title">TongUI</div>
      <div class="subtitle">
        Building Generalized GUI Agents by Learning <br>from Multimodal Web Tutorials
        <!-- TongUI: Building Generalized GUI Agents by Learning \\ from Multimodal Web Tutorials -->
      </div>


      <div class="author-list">
        <!-- &#9733 &#9993;-->
        <span class="author">
          <el-link href="https://bofei5675.github.io/">Bofei Zhang</el-link>
          <span class="ind">1&#9733;</span>,
        </span>
        <span class="author">
          <el-link href="">Zirui Shang</el-link>
          <span class="ind">2,1&#9733;</span>,
        </span>
        <span class="author">
          <el-link href="https://zhigao2017.github.io/">Zhi Gao</el-link>
          <span class="ind">1,3&#9733;</span>,
        </span>
        <span class="author">
          <el-link href="">Wang Zhang</el-link>
          <span class="ind">1</span>,
        </span>
        <span class="author">
          <el-link href="">Rui Xie</el-link>
          <span class="ind">1,4</span>,
        </span>
        <br>
        <span class="author">
          <el-link href="https://jeasinema.github.io/">Xiaojian Ma</el-link>
          <span class="ind">1</span>,
        </span>
        <span class="author">
          <el-link href="https://i.yt.sb/">Tao Yuan</el-link>
          <span class="ind">1</span>,
        </span>
        <span class="author">
          <el-link href="">Xinxiao Wu</el-link>
          <span class="ind">2</span>,
        </span>
        <span class="author">
          <el-link href="https://www.zhusongchun.net/">Song-Chun Zhu</el-link>
          <span class="ind">1,3,5</span>,
        </span>
        <span class="author">
          <el-link href="https://liqing.io/">Qing Li</el-link>
          <span class="ind">1 &#9993;</span>
        </span>
      </div>
      <div class="author-list">
        <span class="org">
          <span class="ind">1</span>
          State Key Laboratory for General Artificial Intelligence, BIGAI
        </span>
        <br>
        <span class="org">
          <span class="ind">2</span>
          Beijing Key Laboratory of Intelligent Information Technology, School of Computer Science & Technology, Beijing Institute of Technology
        </span>
        <br>
        <span class="org">
          <span class="ind">3</span>
          School of Intelligence Science and Technology, Peking University
        </span>
        <span class="org">
          <span class="ind">4</span>
          Shanghai Jiao Tong University
        </span>
        <span class="org">
          <span class="ind">5</span>
          Department of Automation, Tsinghua University
        </span>
      </div>

      <span class="link-block">
        <a href="https://arxiv.org/pdf/2504.12679" class="external-link button is-normal is-rounded is-dark">
          <span class="icon">
            <svg xmlns="http://www.w3.org/2000/svg" width="1.0em" height="1.0em" viewBox="0 0 24 24">
              <path fill="currentColor"
                d="M3.842 0a1 1 0 0 0-.922.608c-.153.369-.044.627.294 1.111l6.919 8.36l-1.023 1.106a1.04 1.04 0 0 0 .003 1.423l1.23 1.313l-5.44 6.444c-.28.3-.453.823-.297 1.199a1.025 1.025 0 0 0 .959.635a.91.91 0 0 0 .689-.34l5.783-6.126l7.49 8.005a.85.85 0 0 0 .684.26a.96.96 0 0 0 .877-.615c.158-.377-.017-.75-.306-1.14L13.73 13.9l1.064-1.13a.963.963 0 0 0 .009-1.316L4.633.464S4.26.01 3.867 0zm0 .272h.017c.218.005.487.272.564.364l.005.006l.005.005l10.17 10.99a.69.69 0 0 1-.008.946l-1.066 1.133l-1.498-1.772l-8.6-10.39c-.328-.472-.352-.619-.26-.841a.73.73 0 0 1 .671-.44Zm14.341 1.57a.88.88 0 0 0-.655.242l-5.696 6.158l1.694 1.832l5.309-6.514c.325-.433.479-.66.325-1.029a1.12 1.12 0 0 0-.977-.689m-7.655 12.282l1.318 1.414l-5.786 6.13a.65.65 0 0 1-.496.26a.75.75 0 0 1-.706-.467c-.112-.269.036-.687.244-.909l.005-.005l.005-.006z" />
            </svg>
          </span>
          <span>arXiv</span>
        </a>
      </span>
      <span class="link-block">
        <a href="https://github.com/TongUI-agent/TongUI-agent?tab=readme-ov-file" class="external-link button is-normal is-rounded is-dark">
          <span class="icon">
            <i class="fab fa-github"></i>
          </span>
          <span>Code</span>
        </a>
      </span>

      <span class="link-block">

        <a target="_blank" href="https://huggingface.co/datasets/Bofeee5675/TongUI-1M"
          class="external-link button is-normal is-rounded is-dark">
          <span class="icon">
            <i class="fa fa-database"></i>
          </span>
          <span>Data</span>
        </a>
      </span>

      <span class="link-block">

        <a target="_blank" href="https://huggingface.co/Bofeee5675/TongUI-3B"
          class="external-link button is-normal is-rounded is-dark">
          <span class="icon">
            <i class="fa fa-robot"></i>
          </span>
          <span>Model</span>
        </a>
      </span>

      <span class="link-block">

        <a target="_blank" href="https://huggingface.co/spaces/Bofeee5675/TongUI"
          class="external-link button is-normal is-rounded is-dark">
          <span class="icon">
            <svg xmlns="http://www.w3.org/2000/svg" x="0px" y="0px" width="20" height="20" viewBox="2 0 32 22"
            style="fill:#EBEBEB;">
            <path d="M30.362,8.749c-0.218-1.179-0.989-2.168-2.064-2.647c-0.508-0.228-1.096,0.002-1.32,0.506	c-0.226,0.505,0.001,1.096,0.506,1.32c0.473,0.211,0.814,0.654,0.912,1.185c0.005,0.029,0.009,0.058,0.014,0.087	c0.001,0.093,0.014,0.185-0.002,0.28c-0.145,0.815-0.918,1.362-1.738,1.217c-6.302-1.111-13.09-1.128-20.188-0.053	c-0.518,3.798-0.475,8.104,0.132,11.988c0.127,0.818-0.433,1.586-1.251,1.714c-0.078,0.012-0.156,0.018-0.233,0.018	c-0.361,0-0.699-0.131-0.962-0.353c-0.003-0.002-0.006-0.004-0.008-0.006c-0.119-0.101-0.217-0.226-0.3-0.361	c-0.01-0.017-0.025-0.03-0.035-0.047c-0.085-0.151-0.146-0.319-0.175-0.501c-0.71-4.556-0.697-9.662,0.035-14.01	c0.106-0.632,0.603-1.126,1.233-1.23c0.437-0.073,0.871-0.132,1.306-0.197c5.965-0.766,11.879-0.861,17.592-0.262	c0.567,0.064,1.041-0.342,1.099-0.89c0.058-0.55-0.341-1.042-0.89-1.099C17.738,4.749,11.227,4.896,4.668,5.841	C3.156,6.06,1.93,7.259,1.685,8.759c-0.808,4.979-0.822,9.893-0.043,14.604c0.266,1.597,1.546,2.835,3.113,3.013	c3.665,0.414,7.384,0.621,11.132,0.621c3.772,0,7.575-0.21,11.379-0.63c1.547-0.172,2.827-1.378,3.113-2.934	C31.271,18.569,31.266,13.628,30.362,8.749z M13,13.958c0-0.879,0.944-1.434,1.712-1.007l5.475,3.042c0.79,0.439,0.79,1.576,0,2.015	l-5.475,3.042C13.944,21.476,13,20.92,13,20.042V13.958z"></path>
            </svg>
          </span>
          <span>Demo</span>
        </a>
      </span>

    </div>

    <div class="section">
      <el-card class="teaser">
        <el-image src="./tongui/teaser.png"></el-image>
      </el-card>
    </div>


    <div class="section">
      <div class="section-title">Introduction</div>
      <p class="intro">
        Building Graphical User Interface (GUI) agents is a promising research direction, which simulates human interaction with computers or mobile phones to perform diverse GUI tasks. However, a major challenge in developing generalized GUI agents is the lack of sufficient trajectory data across various operating systems and applications, mainly due to the high cost of manual annotations. 
        In this paper, we propose the TongUI framework that transforms millions of multimodal web tutorials into GUI trajectories for generalized GUI agents. Concretely, we crawl GUI videos and articles from the Internet and process them into GUI agent trajectory data. Based on this, we construct the GUI-Net-1M dataset, which contains 1 million trajectories across five operating systems and over 280 applications. To the best of our knowledge, this is the <b>largest open-source GUI trajectory dataset</b>. 
        We develop the TongUI agent by fine-tuning Qwen2.5-VL-3B/7B/32B models on GUI-Net-1M, which shows consistent performance improvements on commonly used grounding and navigation benchmarks, outperforming baseline agents by 10% on multiple benchmarks, showing the effectiveness of the GUI-Net-1M dataset and underscoring the significance of our TongUI framework. We will <b>fully open-source</b> the code, raw data, the GUI-Net-1M dataset, and the trained models.
      </p>
    </div>

    <video width="80%" height=auto controls>
      <source src="/intro.mp4" type="video/mp4">
    </video>


    <div class="section">
      <div class="section-title">Dataset Generation</div>
      <p class="intro"> We design the TongUI framework composed of three steps: tutorial crawling, tutorial processing, and trajectory generation. 
In the tutorial crawling step, we write some seed tasks and use LLMs to extend them into a wider collection of tasks, ensuring comprehensive coverage and enhanced realism of real-world GUI tasks. 
The generated tasks serve as keywords for retrieving content from hosts for online GUI tutorials (such as articles from WikiHow and videos from YouTube).
The tutorial processing step aims to extract the textual descriptions and screenshots of multimodal tutorials.
We first obtain textual descriptions of multimodal tutorials via automatic speech recognition (ASR) or captioning, through which task queries and plans are produced using LLMs on the obtained textual descriptions.
Then, we extract salient frames from videos as the screenshot of each step, while the images in articles are directly regarded as screenshots.
Finally, we leverage one zero-shot GUI agent to automatically recognize trajectories, including reasoning thoughts and actions between two steps. Throughout these stages, a multi-step data filtering pipeline is applied to remove duplicates, discard GUI-irrelevant content, and filter out low-quality trajectories, ensuring high data quality and relevance.</p>

      <el-card class="teaser">
        <el-image src="./tongui/flow.png"></el-image>
      </el-card>

    </div>

    <div class="section">
      <div class="section-title">Agent Tuning</div>
      <p class="intro"> Based on GUI-Net-1M, we develop the TongUI agent using Qwen2.5-VL-3B/7B models. 
      The architecture of the used model is shown below.
      </p>

      <el-card class="teaser">
        <el-image src="./tongui/network.png"></el-image>
      </el-card>

    </div>


    <div class="section">
      <div class="section-title">GUI-Net Dataset </div>
      <div class="intro">Based on the tutorial collection pipeline, we construct a GUI-Net dataset that contains 1M data across five operating systems with more than 280 applications. 
        <br>
        We show the <b>operating system distribution</b> in (a). Our dataset covers a diverse range of operating systems, including Windows, Android, iOS, MacOS, and Linux, ensuring a broad representation of GUI interactions across both desktop and mobile environments.
We provide statistics on the <b>data filtering flow</b> in (b). Throughout the data filtering pipeline, we observe a gradual reduction in data volume, reflecting the progressive refinement of the dataset. 
We show the <b>step distribution</b> in (c).  Our dataset includes GUI interactions with varying step lengths, ranging from single-step actions to 9-step tasks. The distribution shows that shorter tasks (1-3 steps) are more frequent, while longer tasks gradually decrease in numbers. 
The <b>action distribution</b> is shown in (d). Our dataset encompasses a diverse range of GUI actions, with Click and Tap being the most frequent, reflecting their central role in both desktop and mobile interactions. Other common actions include HotKey, Swipe, and Drag, covering various forms of user interactions.

      </div>

      <br>
      <el-card class="teaser">
        <el-image src="./tongui/dataset_statistics.png"></el-image>
      </el-card>
    </div>

    <div class="section">
      <div class="section-title">Evaluation and Results </div>
      <div class="intro">We evaluate the TongUI agent on offline benchmarks: <b>ScreenSpot</b>, <b>ScreenSpot-V2</b>, <b>ScreenSpot-Pro</b>, <b>AITW</b>, <b>AndroidControl</b>, <b>Mind2Web</b>, and <b>UI-Vision</b>. We also evaluate the TongUI agent on one online benchmark: <b>MiniWob</b>.
The results show that the TongUI agent exhibits consistent improvements in grounding and navigation capabilities. 
The results demonstrate the generalization of the TongUI agent, since it is trained on high-quality data across diverse applications, underscoring the effectiveness of the TongUI framework that improves the agents in a low-cost manner without the need for expensive manual annotation.<br></div>

      <div class="intro"><b>Metric.</b> After training, we perform zero-shot evaluation of the model's grounding capability on ScreenSpot. 
      The annotation of ScreenSpot gives a bounding box for each interactive element. 
      The action from the model is considered correct when the point predicted falls within the bounding box. 
      For online evaluations, the environment of MiniWob provides reward functions, which suggests if a trajectory is correct. 
      For offline evaluations such as Mind2Web, AITW, and Baidu Experience, the model will be asked to output actions with parameters. 
      We evaluate if the action is correct by the exact match. For parameters, we do the exact match for string parameters and check if a point parameter falls within the bounding box based on annotations. 
      We evaluate the model after fine-tuning on Mind2Web, AITW, and MiniWob.
      In other evaluation datasets, we use the pre-trained model.<br><br>
      </div>

      <div class="intro"><b>Grounding.</b> In Table 2, we show the zero-shot grounding performance of TongUI on ScreenSpot, ScreenSpot-V2, and ScreenSpot-pro. Similar to previous works, grounding on icons is much harder than grounding on text. 
The collected data leads to significant improvements on the baseline Qwen2.5-VL model. 
Compared with ShowUI, our method has about 5% - 20% improvements.
TongUI has a comparable performance to UI-TARS, but UI-TARS only releases the models without training details and data.
These results demonstrate that GUI-Net-1M can indeed improve the grounding capability of GUI agents.<br></div>
      <el-card class="stats-img-1">
        <el-image src="./tongui/results_screenspot.png"></el-image>
      </el-card>

      <div class="intro"><b>Offline Navigation.</b> We evaluate the offline navigation capability of GUI agents on the AITW, AndroidControl, Mind2Web, and UI-Vision datasets, and results on the AITW and Mind2Web are shown in Table 3 and Table 6, respectively.
No matter whether on a small model (3B) or a big model (32B), using GUI-Net-1M data leads to competitive performance. 
For example, TongUI-3B achieves better performance compared to ShowUI-2B by 1.6\% on AITW. The larger model, TongUI-7B, gains better performance compared to TongUI-3B, which is consistent with common sense. This highlights that the collected data improves the generalization capability of GUI agents. 
We argue that the reason is that the collected data involves diverse applications and operating systems, improving generalization.<br></div>
      <div class="img-container">
        <el-card class="stats-img-1">
          <el-image src="./tongui/results_aitw.png"></el-image>
        </el-card>

        <div class="divider"></div>

        <el-card class="stats-img-1">
          <el-image src="./tongui/results_mind2web.png"></el-image>
        </el-card>
      </div>

      <div class="intro"><b>Online Navigation.</b> We evaluate the online navigation performance on MiniWob, as shown in Table 7. 
Compared with offline navigation, online navigation is more challenging, since it processes dynamic environments, handles unexpected obstacles, and adapts to changes in the navigation path. In this case, TongUI, which learns from multimodal tutorials, achieves improvements again. 
Considering that the multimodal tutorials are offline data, the improvements confirm the generalization of TongUI.<br></div>
      <el-card class="stats-img-2">
        <el-image src="./tongui/results_miniwob.png"></el-image>
      </el-card>
    </div>

    <div class="section">
      <div class="section-title">Video Demo</div>

      <video height="800" controls>
        <source src="/video.mp4" type="video/mp4">
      </video>

      <p class="intro">
        
      </p>

      <video width="700" height=auto controls>
        <source src="/video1.mp4" type="video/mp4">
      </video>
    </div>

  </div>


  <section class="section" id="BibTeX" style="text-align: left;">
    <div class="container is-max-desktop content" style="max-width: 100%; margin: 0 auto;">
      <h3 class="title" style="font-size: small;">
        BibTeX
      </h3>
      <div class="bibtex-container">
        <pre><code class="language-bibtex">
@article{zhang2025tongui,
  title={TongUI: Building Generalized GUI Agents by Learning from Multimodal Web Tutorials},
  author={Zhang, Bofei and Shang, Zirui and Gao, Zhi and Zhang, Wang and Xie, Rui and Ma, Xiaojian and Yuan, Tao and Wu, Xinxiao and Zhu, Song-Chun and Li, Qing},
  journal={arXiv preprint arXiv:2504.12679},
  year={2025}
}
        </code></pre>
      </div>
    </div>
  </section>

</template>



<style scoped>
.main {
  text-align: center;
  color: #333;
}

.header {
  margin: 60px 0 0 0 !important;
}

.title {
  font-size: 5em;
}

.subtitle {
  font-size: 2.5em;
  color: #555;
}

.author-list {
  margin-top: 20px;
}

.author a {
  font-size: 1.2em;
  font-weight: normal;
  color: #337ecc;
}

.org {
  margin: 0 4px 0 4px;
}

.ind {
  font-size: 0.8em;
  vertical-align: super;
}

.section {
  margin: 50px 0;
}

.tldr {
  text-align: left;
  font-size: 1em;
  max-width: 1360px;
  line-height: 150%;
}

.section-title {
  margin: 20px;
  font-size: 2em;
  font-weight: bold;
}

.conference {
  text-align: center;
  margin: 20px;
  font-size: 1.5em;
  color: #665;
}

.uns {
  text-decoration: underline;
}

.mat-icon {
  width: 0.8em;
  height: 0.8em;
  margin-right: 0.2em;
}

.teaser {
  max-width: 840px;
  margin: 0 auto;
}

.stats-img {
  height: 300px;
}

.stats-img-1 {
  max-width: 67%;
  max-height: 95%;
  object-fit: contain;
  margin: 0 auto;
  display: block;
}

.stats-img-2 {
  max-width: 35%;
  max-height: 95%;
  object-fit: contain;
  margin: 0 auto;
  display: block;
}

.intro {
  text-align: justify;
  font-size: 1em;
  max-width: 1360px;
  line-height: 150%;
}

.link-block a {
  margin-top: 5px;
  margin-bottom: 5px;
}

.example-dialog {
  width: 800px;
}

.footer {
  color: #aaa;
  margin: 100px 0 60px 0;
}


/* The top button */
.external-link {
  display: inline-block;
  padding: 8px 16px;
  /* inner margin */
  margin: 4px;
  /* outer margin */
  border: 1px solid #9a9c9e;
  /* color of border */
  border-radius: 9px;
  background-color: #8a8b8b;
  color: white;
  text-decoration: none;
  font-size: 20px;
  transition: background-color 0.3s;
}

.external-link:hover {
  background-color: #8e8f90;
}

.external-link .icon {
  margin-right: 8px;
}

.external-link .fas {
  font-size: 18px;
}

.bibtex-container {
  background-color: #e1e4e9;
  /* Change background color to match the theme */
  padding: 1em;
  /* Add padding for better readability */
  border-radius: 5px;
  /* Add border radius for rounded corners */
  text-align: left;
  white-space: pre;
  /* Preserve formatting and prevent line breaks */
  overflow-x: auto;
  /* Add horizontal scroll bar */
}

pre {
  margin: 0;
}

code {
  font-family: 'Courier New', Courier, monospace;
  /* Change font to monospace */
  color: #0a0b0b;
  /* Change text color to match the theme */
}

.img-container {
  display: flex;
  flex-direction: column;
  align-items: center;
}

.divider {
  width: 70%; /* 与图宽对齐 */
  margin: 6px 0;
  border-color: #141414; /* 分割线颜色 */
}

</style>
