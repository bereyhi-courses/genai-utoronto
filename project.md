---
layout: page
title: Project
permalink: /project/
---
<p>
<div style="background-color:#f0f0f0; padding:10px; border-radius:10px; text-align:left; width:95%; margin: 0 auto;">
  <h2><strong>Code of Honor</strong></h2>
  This project is intended to deepen your understanding and develop your skills, and it forms a substantial part of your final evaluation. It must be completed collaboratively as a group. Any form of academic dishonesty is a violation of the Code of Honor. You are encouraged to use publicly available resources, provided that all <em>sources are clearly cited</em> and your individual <em>contributions are clearly explained.</em> Failure to properly acknowledge your contribution may be considered a <strong>lack of participation</strong>, and projects without meaningful individual contributions will be deemed <strong>incomplete.</strong>
</div>
</p>

The project topic should be defined, such that it covers __at least two topics covered in the course.__ The groups must __conduct background research, contribute to implementation, conduct enough experiments, and use their findings to draw a conclusion.__ The topic of the project can focus on a hands-on project and/or an interesting research study. Regardless of the topic of the project, the following steps should be addressed:

1. Make a group of 3. Due to the course size, smaller group size is only accepted under __special circumstances.__ 
2. Do your research and choose your topic by the end of __Week 6 (June 12).__ It is strongly suggested to choose _as soon as possible_ to get into the problem and start preliminaries.
3. You will be allocated to a TA, who could help you throughout the project.
4. Present your final result by __Week 13 (second Week of August).__
5. Deliver the paper and code by __Week 14 (third Week of August).__

<p>
<div style="background-color:#f5dcdc; padding:10px; border-radius:10px; text-align:left; width:95%; margin: 0 auto;">
  <h2><strong>Submission Procedure</strong></h2>
  The main body of work is submitted through Git. In addition, each group submits a final paper and gives a presentation. In this respect, please follow these steps.
  <ul>
    <li>
      Each group must maintain a Git repository, e.g., GitHub or GitLab, for the project. By the time of final submission, the repository should have:
      <ul>
        <li>Well-documented codebase</li>
        <li>Clear <code>README.md</code> with setup and usage instructions</li>
        <li>A <code>requirements.txt</code> file listing all required packages or an <code>environment.yaml</code> file with a reproducible environment setup</li>
        <li>Demo script or notebook showing sample input-output</li>
        <li><em>If applicable,</em> a <code>/doc</code> folder with extended documentation</li>
      </ul>
    </li>
    <li>
      A final report (maximum <em>5 pages</em>) must be submitted in a PDF format. The report should be written in the provided formal style, including an abstract, introduction, method, experiments, results, and conclusion.<br>
      <strong>Important:</strong> Submissions that do not use template are considered <em>incomplete.</em>
    </li>
    <li>
      A 5-minute presentation (maximum <em>5 slides including the title slide</em>) is given on the internal seminar on Week 13, i.e., <em>Aug 10 to Aug 14,</em> by the group. For presentation, any template can be used.
    </li>
  </ul>
</div>
</p>

<!-- ## Project Topics -->

<!-- ### Category A: _Multimodal Generative Models_ -->

<!-- #### __Topic A-1: Text-to-Image Generation using Pretrained LMs and Generative Architectures__ -->
<!-- - [See Complete Project Description]({{site.baseurl}}/assets/Project_Materials/CategoryA/TopicA_1.pdf) 
- __Objective:__ Design and implement a _multimodal_ generative model that takes text descriptions as input and generates corresponding images. For language processing, a pretrained LM, e.g., BERT or RoBERTa, is used. The designed multimodal model should integrate this pretrained LM into a generative architecture such as a VAE, GAN, or diffusion model.
- __Supervisor:__ [Amir Hossein Mobasheri](mailto:amir.mobasheri@mail.utoronto.ca) -->

<!-- #### __Topic A-2: Image-to-Text Generation using Pretrained Vision Models and LMs__ -->
<!-- - [See Complete Project Description]({{site.baseurl}}/assets/Project_Materials/CategoryA/TopicA_2.pdf) 
- __Objective:__ Design and implement a _multimodal_ generative model that takes an image as input and generates a descriptive caption or sentence. A pretrained vision model, e.g., ResNet, ViT, or CLIP, is used to extract image features, which are then passed into a LM to generate coherent textual descriptions.
- __Supervisor:__ [Likun Cai](mailto:likun.cai@mail.utoronto.ca) -->

<!-- #### __Topic A-3: Learning Cross-Modal Embeddings for Image-Text Alignment__ -->
<!-- - [See Complete Project Description]({{site.baseurl}}/assets/Project_Materials/CategoryA/TopicA_3.pdf) 
- __Objective:__ Build a model that learns a _shared embedding_ for text and image inputs. Given a text-image pair, the model should embed both modalities into a common space such that semantically aligned pairs are close together and misaligned pairs are distant. This is a foundational task for generative models and retrieval-based generation methods.
- __Supervisor:__ [Amir Hossein Mobasheri](mailto:amir.mobasheri@mail.utoronto.ca) -->

<!-- ### Category B: _Applications of Generative Models_ -->

<!-- #### __Topic B-1: Educational Code Generation using LLMs with Self-Refinement__  -->
<!-- - [See Complete Project Description]({{site.baseurl}}/assets/Project_Materials/CategoryB/TopicB_1.pdf) 
- __Objective:__ Design a simple intelligent agent that takes algorithmic problem descriptions, e.g., from introductory programming course or Leetcode-style tasks, and generates _not only_ the corresponding code but also _an educational breakdown of the solution_. The agent should aim to provide human-readable explanations alongside correct and runnable code, and include a _self-refinement_ mechanism to debug and correct incorrect generations.
- __Supervisor:__ [Mohammadreza Safavi](mailto:mohammadreza.safavi@mail.utoronto.ca) -->


<!-- #### __Topic B-2: Generative Adversarial Imitation Learning with Transformer-Based Policy Net__ -->
<!-- - [See Complete Project Description]({{site.baseurl}}/assets/Project_Materials/CategoryB/TopicB_2.pdf) 
- __Objective:__ Implement a modernized version of _generative adversarial imitation learning (GAIL)_, where the generator, i.e., the policy network, is modeled using a Transformer. The goal is to train the generator to imitate expert behavior in a simple reinforcement learning (RL) environment through adversarial training.
- __Supervisor:__ [Mohammadreza Safavi](mailto:mohammadreza.safavi@mail.utoronto.ca) -->


<!-- #### __Topic B-3: Sequence Modeling for Reinforcement Learning with Decision Transformers__ -->
<!-- - [See Complete Project Description]({{site.baseurl}}/assets/Project_Materials/CategoryB/TopicB_3.pdf) 
- __Objective:__ Design and implement a Decision Transformer, a generative model that treats reinforcement learning (RL) as a sequence modeling task. The model should learn to predict the next action based on the historical trajectories and a desired return-to-go.
- __Supervisor:__ [Amirhosein Rostami](mailto:amirhosein.rostami@mail.utoronto.ca) -->

<!-- ### Category C: _Tiny AI Products_ -->

<!-- #### __Topic C-1: Personalized Text-to-Speech using VAE or Diffusion Models__ -->
<!-- - [See Complete Project Description]({{site.baseurl}}/assets/Project_Materials/CategoryC/TopicC_1.pdf) 
- __Objective:__ Design and implement a simplified text-to-speech (TTS) system that generates speech audio conditioned on speaker identity. The project should use a generative model, e.g., a VAE or diffusion-based, to synthesize speech features, which can then be converted into audio using available Vocoders. 
- __Supervisor:__ [Amirhosein Rostami](mailto:amirhosein.rostami@mail.utoronto.ca) -->


<!-- #### __Topic C-2: Tiny Diffusion Model with Alternative Core for Image Generation__ -->
<!-- - [See Complete Project Description]({{site.baseurl}}/assets/Project_Materials/CategoryC/TopicC_2.pdf) 
- __Objective:__ Design and implement a _tiny diffusion model_ for low-resolution image generation, with a focus on architectural simplification, ablation analysis, and experimentation. Rather than using existing _denoising diffusion probabilistic models (DDPMs)_ implementations, students are expected to _build a minimal functional prototype from scratch_, inspired by the original DDPM paper and recent simplifications.
- __Supervisor:__ [Likun Cai](mailto:likun.cai@mail.utoronto.ca) -->


<!-- #### __Topic C-3: Text-guided Image Editing through Latent Modification in VAEs__ -->
<!-- - [See Complete Project Description]({{site.baseurl}}/assets/Project_Materials/CategoryC/TopicC_3.pdf) 
- __Objective:__ Design and implement an image editing pipeline that modifies visual content based on a given textual prompt. The goal is to build a lightweight but effective multimodal editing system that uses text embeddings to guide latent modifications in a VAE-based generative model.
- __Supervisor:__ [Likun Cai](mailto:likun.cai@mail.utoronto.ca) -->

<!-- ### Category D: _Open-ended_ -->
<!-- - __Description:__ An open-ended project can be selected given that the project description is prepared similar to the standard course projects (see tha sample below). The project description should clearly specify the _objective, motivation, considered requirements and milestones._ You can submit your topic along with the description through Crowdmark.
- [Sample Project Description]({{site.baseurl}}/assets/Project_Materials/CategoryC/TopicC_1.pdf) 
- __Supervisor:__ [Amirhosein Rostami](mailto:amirhosein.rostami@mail.utoronto.ca) -->

## Template for Report
<!-- * [Proposal Template]({{site.baseurl}}/assets/Project_Materials/Proposal_Template.zip) This is the template for _Category D: Open-ended._ You _can_ use other template as well -->
* [Report Template - LaTex]({{site.baseurl}}/assets/Project_Materials/Project_Report_Template.zip): Other templates are __not__ accepted! 
<!-- * [Prsentation Template]({{site.baseurl}}/assets/Project_Materials/Template_Slides_Presentation.zip) You _can_ use other template as well -->



