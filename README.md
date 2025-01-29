# B-RIGHT: Benchmark Re-evaluation for Integrity in Generalized Human-Object Interaction Testing

[[Arxiv]](https://arxiv.org/abs/2501.16724) | [[Dataset]](https://drive.google.com/drive/folders/1hpPFYBcRx_ymnoSTP4VSW3UllGMIr4cO?usp=sharing)

### Authors
Yoojin Jang*, Junsu Kim*, Hayeon Kim, Eun-ki Lee, Eun-sol Kim, Seungryul Baek, Jaejun Yoo (*Equal contributors)


## Abstract
Human-object interaction (HOI) is an essential problem in artificial intelligence (AI) which aims to understand the visual world that involves complex relationships between humans and objects. However, current benchmarks such as HICO-DET face the following limitations: (1) severe class imbalance and (2) varying number of train and test sets for certain classes. These issues can potentially lead to either inflation or deflation of model performance during evaluation, ultimately undermining the reliability of evaluation scores. In this paper, we propose a systematic approach to develop a new class-balanced dataset, **B**enchmark **R**e-evaluation for **I**ntegrity in **G**eneralized **H**uman-object **I**nteraction **T**esting (**B-RIGHT**), that addresses these imbalanced problems. B-RIGHT achieves class balance by leveraging balancing algorithm and automated generation-and-filtering processes, ensuring an equal number of instances for each HOI class. Furthermore, we design a balanced zero-shot test set to systematically evaluate models on unseen scenario. Re-evaluating existing models using B-RIGHT reveals substantial the reduction of score variance and changes in performance rankings compared to conventional HICO-DET. Our experiments demonstrate that evaluation under balanced conditions ensure more reliable and fair model comparisons. 




## Citation
```
@misc{jang2025brightbenchmarkreevaluationintegrity,
      title={B-RIGHT: Benchmark Re-evaluation for Integrity in Generalized Human-Object Interaction Testing}, 
      author={Yoojin Jang and Junsu Kim and Hayeon Kim and Eun-ki Lee and Eun-sol Kim and Seungryul Baek and Jaejun Yoo},
      year={2025},
      eprint={2501.16724},
      archivePrefix={arXiv},
      primaryClass={cs.CV},
      url={https://arxiv.org/abs/2501.16724}, 
}
```

## Acknowledge
This dataset was created based on the HICO-DET dataset. We sincerely appreciate their excellent work.
