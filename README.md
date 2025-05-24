# DARRT
Dymanic Adaptive of Rules for Reasoning Temporal Knowledge Graphs

# Replication
## Environment setups
- python 3.12.0
- GPU is required
- OPENAI API KEY is required to conduct dynamic adapting using LLM APIs. Please refer to .env.template file.  (FYI: single experiment charged ~10$)

## 1. Dynamic Adaption
- Run all cells of the following notebook files in order.
    - `dynamic_adaption_1_rule_sampling.ipynb`
    - `dynamic_adaption_2_iteration_reasoning.ipynb`
    - `dynamic_adaption_3_rank_rules.ipynb`

## 2. LLM reasoning of TKG using Subgraph Retrieval (RQ1)
- Run all cells of following notebook files in order.
    - `llm_reasoning_1_subgraph_retrieval.ipynb`
    - `llm_reasoning_2_evaluation.ipynb`

## 3. LLM-DA as an adapter of a SPARK framework (RQ2)
- Run `SPARK_LLM_DA_ADAPTER.ipynb`.

# References
1. [Wang, Jiapu, et al. "Large language models-guided dynamic adaptation for temporal knowledge graph reasoning." Advances in Neural Information Processing Systems 37 (2024): 8384-8410.](https://proceedings.neurips.cc/paper_files/paper/2024/hash/0fd17409385ab9304e5019c6a6eb327a-Abstract-Conference.html)
2. [Yin, Gongzhu, et al. "Ignite Forecasting with SPARK: An Efficient Generative Framework for Refining LLMs in Temporal Knowledge Graph Forecasting." arXiv preprint arXiv:2503.22748 (2025).](https://arxiv.org/abs/2503.22748)
3. [Liao, Ruotong, Xu Jia, Yangzhe Li, Yunpu Ma, and Volker Tresp. "GenTKG: Generative Forecasting on Temporal Knowledge Graph with Large Language Models." Findings of the Association for Computational Linguistics: NAACL 2024, 2024, pp. 4303–4317.](https://arxiv.org/abs/2310.07793)
4. [Liu, Yushan, et al. "Tlogic: Temporal logical rules for explainable link forecasting on temporal knowledge graphs." Proceedings of the AAAI conference on artificial intelligence. Vol. 36. No. 4. 2022.](https://ojs.aaai.org/index.php/AAAI/article/view/20330)
5. [Han, Zhen, et al. "xerte: Explainable reasoning on temporal knowledge graphs for forecasting future links." arXiv preprint arXiv:2012.15537 (2020).](https://arxiv.org/abs/2012.15537)