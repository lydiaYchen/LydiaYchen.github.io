---
layout: page
title: Research (Papers with code)
---
{::options parse_block_html="true" /}
<a name="top"></a> 




**TabWak: A Watermark for Tabular Diffusion Models** 🏆  
*ICLR 2025 (Spotlight)*  
💻 **Code:** [GitHub](https://github.com/chaoyitud/TabWak)  
📝 **BibTeX:** <details>
<summary>Show citation</summary>
```bibtex
@inproceedings{zhu2025tabwak,
  title={TabWak: A Watermark for Tabular Diffusion Models},
  author={Zhu, Chaoyi and Tang, Jiayi and Galjaard, Jeroen M. and Chen, Pin-Yu and Birke, Robert and Bos, Cornelis and Chen, Lydia Y.},
  booktitle={International Conference on Learning Representations},
  year={2025},
  note={Spotlight}
}
```
</details>


<!--
Our research themes span in the following areas. 

- [Generative Models](#generative-models)
- [Robust, and Private Learning](#robust-and-private-learning)
- [Federated Learning ](#federated-learning-)
  

# Generative Models<a name="Generative"></a>

While big data is powering up the deep learning models, it is costly and inevitably intrudes privacy to curate such data. Synthetically generated data not only alleviates the cost of collecting data but also overcome the privacy concerns and legislation boundary. How to generate synthetic data that fulfill the requirements of data similarity, analysis utility, privacy and generalization?

We are exploring a wide range of generative models for synthesizing tabular data, ranging from Generative Adversarial Networks (GANs), latent difussion, flow models, and large language models. 
We are also actively collaborating with various industrial partners to explore synthetic data as a privacy-preserving data sharing solution, such as major European energy companies, and finacial companies. 



# Robust, and Private Learning<a name="RPFlearning"></a> 

Artificial intelligence (AI) and machine learning (ML) are ubiquitous in our daily lives in the form of search engines, machine translation, self-driving cars and much more. The prevailing assumptions of existing ML algorithms are that data is neutral and can be freely accessed (without breaching privacy). As a result, the existing algorithms fall short of addressing challenges in realistic scenarios, i.e., against adversarial examples, dirty data, and unreliable execution environments while still preserving data privacy. These issues are further exacerbated by large and distributed learning problems, the data for which is collected over multiple sources and must be computed on distributed nodes.

In this line of research, we are designing robust, privacy-preserving and fair learning algorithms. Topics include:
- Robust Machine Learning: designing learning algorithms that are robust to dirty data inputs.
- Adversarial Attacks and Defenses: designing adversarial attacks and defense mechanisms for deployed deep models.
- Differential private (deep) learning: designing effective differential private ML models with precise accuracy accounting.

<figure>
 <a href="#top">
  <img src="../assets/img/top.png" alt="top" style="float: right;" width="30" height="30">
 </a>
</figure>

# Federated Learning <a name="eLInf"></a> 
Data is constantly generated and collected by edge devices (of the network) to power up today’s AI and ML analyses. With the advancement of algorithmic compression techniques and hardware technology, the ability to train neural networks and run inference on edge devices has gone from myth to reality. Federated learning (FL) is an emerging learning paradigm where distributed edge nodes collaboratively learn the weights of neural networks iteratively without directly sharing data. It is largely unexplored how existing deep learning algorithms can be realized within a FL framework, thereby overcoming network communications and adversarial threats. Moreover, owing to the vast number of available trained models and highly heterogeneous mobile devices, it is no mean feat to identify and deploy the right model for individual edge devices.

In this line of research, we are designing learning algorithms and prototyping system solutions for ML training and inference on distributed edge devices. Topics include:

- Confidential Vertical Learning for Manufacturer: collaborating with the world leading material manufacturers to design confidential vertical federated learning on variety of machine learning models
- Attacks and Defenses in Federated Learning: designing data free model poisoning attacks, gradient inversion attacks, and freerider attacks for various federated learning systems
- Continue Federated Learning and Domain Adaptation: designing federated learning systems that tackle two foundemntal challenges in real life: data continitously evolves through different domains and learning tasks also change over time. 
- Deep Model Inferences on Edge Devices: designing and prototyping an inference engine that can search for optimal models and configurations for edge devices at scale.

<figure>
 <a href="#top">
  <img src="../assets/img/top.png" alt="top" style="float: right;" width="30" height="30">
 </a>
</figure>

-->
