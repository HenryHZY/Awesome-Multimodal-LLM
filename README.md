# Awesome-Multimodal-LLM
Research Trends in `LLM-guided Multimodal` Learning.

- Multi Modalities:
	- text, vision (image and video), audio, ... 
- Large Language Model (LLM) Backbones:
	- LLaMA, Alpaca, Vicuna, Bloom, GLM, OPT, ... 
	- LLM should be `open-source and research-friendly`
	- relatively small backbones (e.g., BART and T5) are also OK
- Learning Techniques:
	- full fine-tuning, parameter-efficient tuning (Adapter, LoRA, ... )
	- in-context learning, instruction tuning
	- ... 
- Examples of `LLM-guided Multimodal Model` :
	- OpenFlamingo, MiniGPT-4, Otter, InstructBILP, ...
- Examples of `Evaluation on Multimodal LLM`:
	- MultiInstruct, POPE, AttackVLM, ...

## 2023 May

- **Transfer Visual Prompt Generator across LLMs**. arXiv:2305.01278.

  *Ao Zhang, Hao Fei, Yuan Yao, Wei Ji, Li Li, Zhiyuan Liu, Tat-Seng Chua.* [[Paper](https://arxiv.org/abs/2305.01278)] [[Code](https://github.com/VPGTrans/VPGTrans)]

  `Backbone`: OPT (125M, 350M, 1.3B, and 2.7B) and Flan-T5 (base, large, and XL).

- **Video-LLaMA: An Instruction-Finetuned Visual Language Model for Video Understanding**.

  *Zhang, Hang and Li, Xin and Bing, Lidong.* [Paper] [[Code](https://github.com/DAMO-NLP-SG/Video-LLaMA/tree/main)]

  `Backbone`: Vicuna-7B and Vicuna-13B.


- **LMEye: An Interactive Perception Network for Large Language Models**. arXiv:2305.03701.

  *Yunxin Li, Baotian Hu, Xinyu Chen, Lin Ma, Min Zhang.* [[Paper](https://arxiv.org/abs/2305.03701)] [[Code](https://github.com/YunxinLi/LingCloud)]

  `Backbone`: LLaMA-7B, LLaMA-13B and Bloomz-7B.
  
- **Otter: A Multi-Modal Model with In-Context Instruction Tuning**. arXiv:2305.03726.

  *Bo Li, Yuanhan Zhang, Liangyu Chen, Jinghao Wang, Jingkang Yang, Ziwei Liu.* [[Paper](https://arxiv.org/abs/2305.03726)] [[Code](https://github.com/Luodian/Otter)]

  `Backbone`: based on OpenFlamingo-9B.

- **X-LLM: Bootstrapping Advanced Large Language Models by Treating Multi-Modalities as Foreign Languages**. arXiv:2305.04160.

  *Feilong Chen, Minglun Han, Haozhi Zhao, Qingyang Zhang, Jing Shi, Shuang Xu, Bo Xu.* [[Paper](https://arxiv.org/abs/2305.04160)] [[Code](https://github.com/phellonchen/X-LLM)]

  `Backbone`: ChatGLM.

- **MultiModal-GPT: A Vision and Language Model for Dialogue with Humans**. arXiv:2305.04790.

  *Tao Gong, Chengqi Lyu, Shilong Zhang, Yudong Wang, Miao Zheng, Qian Zhao, Kuikun Liu, Wenwei Zhang, Ping Luo, Kai Chen.* [[Paper](https://arxiv.org/abs/2305.04790)] [[Code](https://github.com/open-mmlab/Multimodal-GPT)]

  `Backbone`: based on OpenFlamingo.


- **VideoChat: Chat-Centric Video Understanding**. arXiv:2305.06355.

  *KunChang Li, Yinan He, Yi Wang, Yizhuo Li, Wenhai Wang, Ping Luo, Yali Wang, Limin Wang, Yu Qiao.* [[Paper](https://arxiv.org/abs/2305.06355)] [[Code](https://github.com/OpenGVLab/Ask-Anything)]

  `Backbone`: based on MiniGPT-4, MOSS and StableLM.

- **InstructBLIP: Towards General-purpose Vision-Language Models with Instruction Tuning**. arXiv:2305.06500.

  *Wenliang Dai, Junnan Li, Dongxu Li, Anthony Meng Huat Tiong, Junqi Zhao, Weisheng Wang, Boyang Li, Pascale Fung, Steven Hoi.* [[Paper](https://arxiv.org/abs/2305.06500)] [[Code](https://github.com/salesforce/LAVIS/tree/main/projects/instructblip)]

  `Backbone`: Flan-T5-XL (3B), Flan-T5-XXL (11B), Vicuna-7B and Vicuna-13B.

- **ArtGPT-4: Artistic Vision-Language Understanding with Adapter-enhanced MiniGPT-4**. arXiv:2305.07490.

  *Zhengqing Yuan, Huiwen Xue, Xinyi Wang, Yongming Liu, Zhuanzhe Zhao, Kun Wang.* [[Paper](https://arxiv.org/abs/2305.07490)] [[Code](https://github.com/DLYuanGod/ArtGPT-4)]

  `Backbone`: based on MiniGPT-4.

- **Evaluating Object Hallucination in Large Vision-Language Models**. arXiv:2305.10355.

  *Yifan Li, Yifan Du, Kun Zhou, Jinpeng Wang, Wayne Xin Zhao, Ji-Rong Wen.* [[Paper](https://arxiv.org/abs/2305.10355)] [[Code](https://github.com/RUCAIBox/POPE)]
  
  `Evaluation`

- **EmbodiedGPT: Vision-Language Pre-Training via Embodied Chain of Thought**. arXiv:2305.15021.

  *Yao Mu, Qinglong Zhang, Mengkang Hu, Wenhai Wang, Mingyu Ding, Jun Jin, Bin Wang, Jifeng Dai, Yu Qiao, Ping Luo.* [[Paper](https://arxiv.org/abs/2305.15021)] [[Code](https://github.com/EmbodiedGPT/EmbodiedGPT_Pytorch)]

  `Backbone`: LLaMA-7B.

- **Cheap and Quick: Efficient Vision-Language Instruction Tuning for Large Language Models**. arXiv:2305.15023.

  *Gen Luo, Yiyi Zhou, Tianhe Ren, Shengxin Chen, Xiaoshuai Sun, Rongrong Ji.* [[Paper](https://arxiv.org/abs/2305.15023)] [[Code](https://github.com/luogen1996/LaVIN)]

  `Backbone`: LLaMA-7B and LLaMA-13B.
  
- **On Evaluating Adversarial Robustness of Large Vision-Language Models**. arXiv:2305.16934.

  *Yunqing Zhao, Tianyu Pang, Chao Du, Xiao Yang, Chongxuan Li, Ngai-Man Cheung, Min Lin.* [[Paper](https://arxiv.org/abs/2305.16934)] [[Code](https://github.com/yunqing-me/AttackVLM)]
  
  `Evaluation`


- **VisualGLM-6B**. 

  *ChatGLM Team.* [Paper] [[Code](https://github.com/THUDM/VisualGLM-6B)]

  `Backbone`: ChatGLM-6B. 

- **Generating Images with Multimodal Language Models**. arXiv:2305.17216.

  *Jing Yu Koh, Daniel Fried, Ruslan Salakhutdinov.* [[Paper](https://arxiv.org/abs/2305.17216)] [Code]

  `Backbone`: OPT-6.7B.

## 2023 April

- **Visual Instruction Tuning**. arXiv:2304.08485.

  *Haotian Liu, Chunyuan Li, Qingyang Wu, Yong Jae Lee.* [[Paper](https://arxiv.org/abs/2304.08485)] [[Code](https://github.com/haotian-liu/LLaVA)]

  `Backbone`: Vicuna-13B.

- **MiniGPT-4: Enhancing Vision-Language Understanding with Advanced Large Language Models**. arXiv:2304.10592.

	*Deyao Zhu, Jun Chen, Xiaoqian Shen, Xiang Li, Mohamed Elhosein.*  [[Paper](https://arxiv.org/abs/2304.10592)] [[Code](https://github.com/Vision-CAIR/MiniGPT-4)]

  `Backbone`: Vicuna-7B.

- **mPLUG-Owl: Modularization Empowers Large Language Models with Multimodality**. arXiv:2304.14178.

  *Qinghao Ye, Haiyang Xu, Guohai Xu, Jiabo Ye, Ming Yan, Yiyang Zhou, Junyang Wang, Anwen Hu, Pengcheng Shi, Yaya Shi, Chenliang Li, Yuanhong Xu, Hehong Chen, Junfeng Tian, Qian Qi, Ji Zhang, Fei Huang.* [[Paper](https://arxiv.org/abs/2304.14178)] [[Code](https://github.com/X-PLUG/mPLUG-Owl)]
  
  `Backbone`: LLaMA-7B. 
  
- **LLaMA-Adapter V2: Parameter-Efficient Visual Instruction Model**. arXiv:2304.15010.

  *Peng Gao, Jiaming Han, Renrui Zhang, Ziyi Lin, Shijie Geng, Aojun Zhou, Wei Zhang, Pan Lu, Conghui He, Xiangyu Yue, Hongsheng Li, Yu Qiao.* [[Paper](https://arxiv.org/abs/2304.15010)] [[Code](https://github.com/ZrrSkywalker/LLaMA-Adapter)]

  `Backbone`: LLaMA-7B.

## 2023 Jan. to Mar.

- **BLIP-2: Bootstrapping Language-Image Pre-training with Frozen Image Encoders and Large Language Models**. arXiv:2301.12597.

  *Junnan Li, Dongxu Li, Silvio Savarese, Steven Hoi.* [[Paper](https://arxiv.org/abs/2301.12597)] [[Code](https://github.com/salesforce/LAVIS/tree/main/projects/blip2)]

  `Backbone`: OPT-2.7B, OPT-6.7B, FLAN-T5-XL and FLAN-T5-XXL.

- **Grounding Language Models to Images for Multimodal Inputs and Outputs**. arXiv:2301.13823. ICML2023.

  *Jing Yu Koh, Ruslan Salakhutdinov, Daniel Fried.* [[Paper](https://arxiv.org/abs/2301.13823)] [[Code](https://github.com/kohjingyu/fromage)]

  `Backbone`: OPT-6.7B.

- **Multimodal Chain-of-Thought Reasoning in Language Models**. arXiv:2302.00923.

  *Zhuosheng Zhang, Aston Zhang, Mu Li, Hai Zhao, George Karypis, Alex Smola.* [[Paper](https://arxiv.org/abs/2302.00923)] [[Code](https://github.com/amazon-science/mm-cot)]

  `Backbone`: T5 and FLAN-T5.


- **Language Is Not All You Need: Aligning Perception with Language Models**. arXiv:2302.14045.

  *Shaohan Huang, Li Dong, Wenhui Wang, Yaru Hao, Saksham Singhal, Shuming Ma, Tengchao Lv, Lei Cui, Owais Khan Mohammed, Barun Patra, Qiang Liu, Kriti Aggarwal, Zewen Chi, Johan Bjorck, Vishrav Chaudhary, Subhojit Som, Xia Song, Furu Wei.* [[Paper](https://arxiv.org/abs/2302.14045)] [Code]

  `Backbone`: MAGNETO.


- **PaLM-E: An Embodied Multimodal Language Model**. arXiv:2303.03378.

  *Danny Driess, Fei Xia, Mehdi S. M. Sajjadi, Corey Lynch, Aakanksha Chowdhery, Brian Ichter, Ayzaan Wahid, Jonathan Tompson, Quan Vuong, Tianhe Yu, Wenlong Huang, Yevgen Chebotar, Pierre Sermanet, Daniel Duckworth, Sergey Levine, Vincent Vanhoucke, Karol Hausman, Marc Toussaint, Klaus Greff, Andy Zeng, Igor Mordatch, Pete Florence.* [[Paper](https://arxiv.org/abs/2303.03378)] [Code]

  `Backbone`: PaLM-8B, PaLM-62B and PaLM-540B.

- **OpenFlamingo**.

  *Awadalla, Anas and Gao, Irena and Gardner, Joshua and Hessel, Jack and Hanafy, Yusuf and Zhu, Wanrong and Marathe, Kalyani and Bitton, Yonatan and Gadre, Samir and Jitsev, Jenia and Kornblith, Simon and Koh, Pang Wei and Ilharco, Gabriel and Wortsman, Mitchell and Schmidt, Ludwig.* [Paper] [[Code](https://github.com/mlfoundations/open_flamingo)]

  `Backbone`: LLaMA-7B.

- **LLaMA-Adapter: Efficient Fine-tuning of Language Models with Zero-init Attention**. arXiv:2303.16199.

  *Renrui Zhang, Jiaming Han, Aojun Zhou, Xiangfei Hu, Shilin Yan, Pan Lu, Hongsheng Li, Peng Gao, Yu Qiao.* [[Paper](https://arxiv.org/abs/2303.16199)] [[Code](https://github.com/ZrrSkywalker/LLaMA-Adapter)]

  `Backbone`: LLaMA-7B.

## 2022

- **VL-Adapter: Parameter-Efficient Transfer Learning for Vision-and-Language Tasks**. arXiv:2112.06825. CVPR 2022.

  *Yi-Lin Sung, Jaemin Cho, Mohit Bansal.* [[Paper](https://arxiv.org/abs/2112.06825)] [[Code](https://github.com/ylsung/VL_adapter)]

  `Backbone`: BART and T5.

- **HyperPELT: Unified Parameter-Efficient Language Model Tuning for Both Language and Vision-and-Language Tasks**. arXiv:2203.03878.

  *Zhengkun Zhang, Wenya Guo, Xiaojun Meng, Yasheng Wang, Yadao Wang, Xin Jiang, Qun Liu, Zhenglu Yang.* [[Paper](https://arxiv.org/abs/2203.03878)] [Code]

  `Backbone`: T5.

- **Flamingo: a Visual Language Model for Few-Shot Learning**. arXiv:2204.14198. NeurIPS 2022.

	*Jean-Baptiste Alayrac, Jeff Donahue, Pauline Luc, Antoine Miech, Iain Barr, Yana Hasson, Karel Lenc, Arthur Mensch, Katie Millican, Malcolm Reynolds, Roman Ring, Eliza Rutherford, Serkan Cabi, Tengda Han, Zhitao Gong, Sina Samangooei, Marianne Monteiro, Jacob Menick, Sebastian Borgeaud, Andrew Brock, Aida Nematzadeh, Sahand Sharifzadeh, Mikolaj Binkowski, Ricardo Barreira, Oriol Vinyals, Andrew Zisserman, Karen Simonyan.* [[Paper](https://arxiv.org/abs/2204.14198)] [Code]

	`Backbone`: Chinchilla-70B.

- **LST: Ladder Side-Tuning for Parameter and Memory Efficient Transfer Learning**. arXiv:2206.06522. NeurIPS 2022.

  *Yi-Lin Sung, Jaemin Cho, Mohit Bansal.* [[Paper](https://arxiv.org/abs/2206.06522)] [[Code](https://github.com/ylsung/Ladder-Side-Tuning)]

  `Backbone`: T5.

- **Zero-Shot Video Question Answering via Frozen Bidirectional Language Models**. arXiv:2206.08155. NeurIPS 2022.

	*Antoine Yang, Antoine Miech, Josef Sivic, Ivan Laptev, Cordelia Schmid.* [[Paper](https://arxiv.org/abs/2206.08155)] [[Code](https://github.com/antoyang/FrozenBiLM)]

	`Backbone`: DeBERTa-V2-XLarge.

- **MultiInstruct: Improving Multi-Modal Zero-Shot Learning via Instruction Tuning**. arXiv:2212.10773.

  *Zhiyang Xu, Ying Shen, Lifu Huang.* [[Paper](https://arxiv.org/abs/2212.10773)] [Code]
  
  `Evaluation`

## 2021

- **Unifying Vision-and-Language Tasks via Text Generation**. arXiv:2102.02779. ICML 2021.

	*Jaemin Cho, Jie Lei, Hao Tan, Mohit Bansal.* [[Paper](https://arxiv.org/abs/2102.02779)] [[Code](https://github.com/j-min/VL-T5)]

	`Backbone`: BART and T5..


- **Multimodal Few-Shot Learning with Frozen Language Models**. arXiv:2106.13884. NeurIPS 2021.

	*Maria Tsimpoukelli, Jacob Menick, Serkan Cabi, S. M. Ali Eslami, Oriol Vinyals, Felix Hill.* [[Paper](https://arxiv.org/abs/2106.13884)] [Code]

	`Backbone`: Transformer-7B.

## Useful Links

Currently, most multimodal LLM are Vision-and-Language.

Vision-and-Language LLM = LLM backbone + Vision backbone.

Here are some useful links for your reference:

- https://github.com/eugeneyan/open-llms

  LLM backbone list (especially open-source LLM).

- https://github.com/bethgelab/model-vs-human

  Vision backbone list (e.g., ViT-22B and ViT-L).

- https://github.com/zhengzangw/awesome-huge-models

  LLM & Vision backbone list.

- https://huggingface.co/spaces/HuggingFaceH4/open_llm_leaderboard

	HuggingFace LLM leaderboard.

- https://github.com/BradyFU/Awesome-Multimodal-Large-Language-Models

	Multimodal LLM Learning & Tools (e.g., Visual ChatGPT and HuggingGPT) & Dataset list.

- https://twitter.com/_akhaliq

	Cutting-edge AI papers.


## Contribution

<a href="https://github.com/HenryHZY/Awesome-Multimodal-LLM/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=HenryHZY/Awesome-Multimodal-LLM" />
</a>

Feel free to pull request! `LLM-guided multimodal` learning is the only limitation.

Please update the paper information with the following format:

- **Title**. arXiv (if any). Conference/Journal (if any).

	Authors. [[Paper]]() [[Code]]()

	`Backbone` or `Evaluation`.

For any interesting news about LLM-guided multimodal learning on Twitter, you can also @[Zi_Yuan_Hu](https://twitter.com/intent/follow?original_referer=https%3A%2F%2Fhenryhzy.github.io%2F&ref_src=twsrc%5Etfw%7Ctwcamp%5Ebuttonembed%7Ctwterm%5Efollow%7Ctwgr%5EZi_Yuan_Hu&screen_name=Zi_Yuan_Hu) to follow and update it at our Awesome-Multimodal-LLM GitHub repo. 

Hope everyone enjoy the LLM-guided future :)

