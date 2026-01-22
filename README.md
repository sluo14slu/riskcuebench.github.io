# RiskCueBench
Benchmarking anticipatory risk reasoning from early visual cues in video–language models.

## Paper
**RiskCueBench: Benchmarking Anticipatory Reasoning from Early Risk Cues in Video-Language Models**  
ACL Rolling Review (ARR), January 2026

📄 arXiv: coming soon


## Why RiskCueBench?
RiskCueBench is designed to evaluate *predictive* risk reasoning rather than post-hoc video understanding.

Unlike existing benchmarks, RiskCueBench:
- Focuses on **early risk signals before incidents occur**
- Requires **anticipatory forecasting under uncertainty**
- Evaluates **reasoning grounding**, not just final answers
- Covers **real-world safety scenarios** (traffic incidents and protests)

  
## Dataset Overview
- Domains: Traffic incidents, Protests
- Total videos: 986
- Annotations:


## Evaluation
Models are evaluated using:
- F1 score (risk prediction)
- Reasoning Grounding Accuracy (RGA)
- Temporal Reasoning Difference (TRD)
- Self-Correction Degradation (SCD)
See the paper for full metric definitions.


## Resources

-  Dataset : Hugging Face
  https://huggingface.co/datasets/slu083/RiskCueBench

-  Evaluation code :
  https://github.com/slu014slu/riskcuebench


## Citation
```bibtex
@article{riskcuebench2026,
  title={RiskCueBench: Benchmarking Anticipatory Reasoning from Early Risk Cues in Video-Language Models},
  author={...},
  journal={ACL Rolling Review},
  year={2026}
}


# Website License
<a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-sa/4.0/88x31.png" /></a><br />This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/">Creative Commons Attribution-ShareAlike 4.0 International License</a>.
