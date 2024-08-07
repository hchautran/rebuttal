# Compare to ToMe

To better demonstrate the significant performance gain of PiToMe compared to ToMe, we have include several figures for each task accors wider range of ratio $r$. Overall there is one pattern that can be seen accross all task, as long as we don't reduce more than 60\% GFlops PiToMe can outperform ToME by a large margin which grow larger than as ratio $r$ reduce.
## 1.Image-text retrieval
Performance of of PiToMe versus token when applied to CLIP-large , ALBEF and BLIP and run on Flickr30k. 

![Ablation study of parameter m ](figures/itr.png)

In The figure above it can easy be seen that the performance gap between ToME and PiToMe grow larger as we reduce $r$ (lower gflops). 

## 2.Visual Question Answering with LLaVA
To better demonstrate the stregth on PiToMe in generative task like VQA. We have run LLava-7B 7 times on two dataset MME benchmark and ScienceQA.

![Ablation study of parameter m ](figures/llava.png)

It is clear that apart from better perfomance, PiToME achieve much stable accuracy compare to ToMe which is demonstrated as lower std at each ratio $r$.

## 3.Text Classification
In Text classification task, PiToMe offer much better trade off 

![Ablation study of parameter m ](figures/tc.png)

Here, PiToMe can compress more than 60% number of tokens while stil achive accuracy above 90% (about 2% drop) and even more than 80% number of tokens while still being able to achieve above 85% in accuracy.

## 4.Image classification
##### DeiT
|gflops | PiToMe| ToMe|
|----------|----------|----------|
|  | |  |
|  | |  |
|  ||  |
|  ||  |
|  ||  |
##### MAE 
|gflops | PiToMe| ToMe|
|----------|----------|----------|
|  | |  |
|  | |  |
|  ||  |
|  ||  |
|  ||  |