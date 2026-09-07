# Shreshth Saini

PhD from the Laboratory for Image and Video Engineering at UT Austin, advised by Alan C. Bovik. I work on generative models for video (guidance, efficient sampling, test-time search, RL post-training) and on perceptual quality of HDR and user-generated video, in collaboration with YouTube / Google Media Algorithms. Papers, talks, and blog: [shreshthsaini.github.io](https://shreshthsaini.github.io)

## Selected work

| | What it is | Code and data |
|---|---|---|
| **Rectified-CFG++** (NeurIPS 2025) | Training-free on-manifold guidance for rectified-flow text-to-image models | [code](https://github.com/shreshthsaini/Rectified-CFGpp) · [paper](https://arxiv.org/abs/2510.07631) |
| **CachedSearch** (2026) | Training-free cached exploration for test-time search in video diffusion: most of best-of-N's gain at a fraction of the cost | [code](https://github.com/shreshthsaini/CachedSearch) · [paper](https://arxiv.org/abs/2607.23159) · [blog](https://shreshthsaini.github.io/blogs/cachedsearch.html) |
| **LumaFlux** (2026) | Prompt-free SDR-to-HDR with a frozen FLUX transformer, 8 steps, training-free video stabilization | [code](https://github.com/shreshthsaini/LumaFlux) · [weights](https://huggingface.co/shreshthsaini/LumaFlux) · [paper](https://arxiv.org/abs/2604.02787) |
| **LumaGuide** (2026) | Distribution shaping for training-free HDR generation in diffusion models | [code](https://github.com/shreshthsaini/LumaGuide) · [paper](https://arxiv.org/abs/2607.26237) |
| **Beyond8Bits** (CVPR 2026) | The largest HDR-UGC video quality dataset (41k clips, 1.46M ratings) and HDR-Q, an MLLM for HDR VQA | [code](https://github.com/shreshthsaini/Beyond8Bits) · [dataset](https://huggingface.co/datasets/shreshthsaini/Beyond8Bits) · [paper](https://arxiv.org/abs/2603.00938) |
| **BrightRate / BrightVQ** (WACV 2026) | No-reference HDR-UGC VQA model and its 2,100-clip subjective dataset | [code](https://github.com/shreshthsaini/BrightVQ) · [dataset](https://huggingface.co/datasets/shreshthsaini/BrightVQ) · [MLLM follow-up](https://github.com/shreshthsaini/BrightRate-LM) |
| **CHUG** (ICIP 2025) | First crowdsourced HDR-UGC video quality dataset | [code](https://github.com/shreshthsaini/CHUG) · [dataset](https://huggingface.co/datasets/shreshthsaini/CHUG) · [paper](https://arxiv.org/abs/2510.09879) |

All papers, datasets, and models in one place: [Hugging Face collection](https://huggingface.co/collections/shreshthsaini/hdr-video-and-diffusion-research-6a9e5fae53c81ffb7be668fa).

Also maintained: [fleetcraft](https://github.com/shreshthsaini/fleetcraft), queue workers and Slurm templates for keeping GPU fleets busy on shared HPC, and [Awesome-Perceptual-Quality](https://github.com/shreshthsaini/Awesome-Perceptual-Quality), a tagged catalog of IQA and VQA methods and datasets.

## Writing

The [Scratch Pad](https://shreshthsaini.github.io/blogs.html): notes on RL for video, GPU infrastructure for video generation, rectified flow, and CFG++.

Happy to advise and collaborate. Reach me at saini[dot]2[at]utexas[dot]edu.
