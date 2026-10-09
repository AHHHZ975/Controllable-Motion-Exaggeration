The (coming soon) code for the paper:
# Controllable Exaggeration for Generative Motion Models via Training-Time Adaptation and Inference-Time Guidance

* ### See the project webpage [[here]](https://ahhhz975.github.io/ControllableMotionExaggeration/)
* ### See the paper [[here]](https://arxiv.org/pdf/2610.12316)

<img width="2318" height="1058" alt="Teaser_v5" src="https://github.com/user-attachments/assets/de49ee04-af0e-4f33-b9b4-710461750f34" />


Recent motion generative models have demonstrated strong capabilities in synthesizing physically plausible character motion, but often overlook established animation principles used by professional animators to ground and design their animation work. Understanding and incorporating these principles into motion generative pipelines is essential for producing motions that serve not only physically grounded applications but also the needs of the character animation community. This enables the creation of characters that not only move in physically plausible ways but also feel alive, expressive, and engaging. 

To close this gap, we focus on the Exaggeration principle of animation and investigate how it can be incorporated into modern motion generative pipelines to produce more expressive character motions. To this end, we introduce a framework that operates at two stages of existing motion generative pipelines. The first stage introduces exaggeration during training, where we perform supervised fine-tuning of pre-trained text-to-motion models on our curated exaggeration dataset. The second stage operates at inference time, where we: (i) introduce a mathematical formulation of exaggeration based on dynamic movement primitives (DMPs); and (ii) leverage this formulation as an exaggeration guidance signal to guide existing diffusion and flow-matching text-to-motion generation models toward exaggerated motion without additional training. Through qualitative and quantitative evaluations against three strong motion generation models, we show that our methods generate more exaggerated and expressive motions while preserving neutral reference motion intent and physical plausibility.

### The code is coming soon, stay tuned!


# Citation
We appreciate your interest in our research. If you find this study useful in your work, we kindly ask that you cite it using the following format.

```
@inproceedings{zamani2026controllable,
  title={Controllable Exaggeration for Generative Motion Models via Training-Time Adaptation and Inference-Time Guidance},
  author={Zamani, Amirhossein and Rampini, Arianna and Roy, Bruno},
  booktitle={arXiv},
  year={2026},
  url={https://arxiv.org/pdf/2610.12316}
}
```
