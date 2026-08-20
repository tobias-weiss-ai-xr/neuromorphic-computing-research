<h1 align="center">
  <strong>Neuromorphic Computing Research Corpus</strong>
</h1>
<h3 align="center">Data-driven, auto-validated literature review for neuromorphic computing: spiking neural networks, neuromorphic hardware, memristive systems, and brain-inspired computing</h3>

### 🔗 Links

- **GitHub**: https://github.com/tobias-weiss-ai-xr/neuromorphic-computing-research
- **License**: https://github.com/tobias-weiss-ai-xr/neuromorphic-computing-research/blob/main/LICENSE
- **CI**: https://github.com/tobias-weiss-ai-xr/neuromorphic-computing-research/actions/workflows/validate.yml
- **GitHub Pages**: https://tobias-weiss-ai-xr.github.io/neuromorphic-computing-research/


> 📊 **Auto-validated corpus** — papers in `papers.yaml` are validated by
> `scripts/validate_papers.py` on every push. The README is auto-generated
> from `papers.yaml` via `scripts/generate_readme.py`.

## What you get

| Capability | How |
|------------|-----|
| 📄 **Curated corpus** | `papers.yaml` is the source of truth — one structured entry per paper |
| ✅ **Auto-validation** | `scripts/validate_papers.py` checks schema, duplicates, URL normalization |
| 🧾 **Auto-generated README** | `scripts/generate_readme.py` renders the paper list grouped by taxonomy |
| 📊 **Statistics & trends** | `scripts/standard_stats.py` → `statistics.json` |
| 🔍 **Literature review** | `scripts/analysis/generate_reports.py` → `docs/research/` |
| 🔎 **Paper discovery** | `scripts/fetch/fetch_new_papers.py` (arXiv), `fetch_openalex_bulk.py`, `fetch_other_sources.py` |
| 🤖 **Agentic workflow** | `AGENTS.md` + `config/taxonomy.yaml` make this repo agent-friendly |

## 📚 Paper list

- [📚 Spiking Neural Networks](#spiking-neural-networks)
  - [Method](#method)
  - [Reviews & Surveys](#reviews-&-surveys)
- [📚 Neuromorphic Hardware](#neuromorphic-hardware)
  - [Systems & Technology](#systems-&-technology)
- [📚 Neuromorphic Algorithms](#neuromorphic-algorithms)
- [📚 Memristive Systems](#memristive-systems)
  - [Systems & Technology](#systems-&-technology)
- [📚 Neuromorphic Sensors & Perception](#neuromorphic-sensors-&-perception)
  - [Reviews & Surveys](#reviews-&-surveys)
- [📚 Brain-Inspired Computing](#brain-inspired-computing)
- [📚 Edge & Low-Power Computing](#edge-&-low-power-computing)
- [📚 Surveys & Taxonomies](#surveys-&-taxonomies)

### Spiking Neural Networks

#### Method

##### 2021

- [2021] **Training Spiking Neural Networks Using Lessons From Deep Learning** *Proceedings of the IEEE* [[paper](https://arxiv.org/abs/2109.12894)] [[code](https://github.com/BrainML/snnTorch)] [[project](https://snntorch.readthedocs.io)]

[⬆ Back to top](#paper-list)

#### Reviews & Surveys

##### 2019

- [2019] **Towards Spike-Based Machine Intelligence with Spiking Neural Networks** *Nature Machine Intelligence 1, 421-434 (2019)* [[paper](https://arxiv.org/abs/1907.07818)]

[⬆ Back to top](#paper-list)

### Neuromorphic Hardware

#### Systems & Technology

##### 2018

- [2018] **Loihi: A Neuromorphic Manycore Processor with On-Chip Learning** *IEEE Micro 38, 82-99 (2018)* [[paper](https://arxiv.org/abs/1806.07365)] [[project](https://www.intel.com/research/neuromorphic)]

[⬆ Back to top](#paper-list)

### Neuromorphic Algorithms

### Memristive Systems

#### Systems & Technology

##### 2020

- [2020] **A Framework for Memory-Based Neuromorphic Computing** *Nature Nanotechnology* [[paper](https://arxiv.org/abs/2010.10728)]

[⬆ Back to top](#paper-list)

### Neuromorphic Sensors & Perception

#### Reviews & Surveys

##### 2020

- [2020] **Event-Based Vision: A Survey of the Event Camera Literature** *IEEE Transactions on Pattern Analysis and Machine Intelligence* [[paper](https://arxiv.org/abs/1904.08305)]

[⬆ Back to top](#paper-list)

### Brain-Inspired Computing

### Edge & Low-Power Computing

### Surveys & Taxonomies

## 📖 Citation

If you use this skeleton for a project, please cite:

```bibtex
@misc{skeleton-research,
  author = {Weiß, Tobias},
  title = {Research Corpus Skeleton: Data-Driven Agentic Literature Review},
  year = {2026},
  publisher = {GitHub},
  url = {https://github.com/<YOUR_ORG>/skeleton-research}
}
```

## 📄 License

MIT — see [LICENSE](LICENSE).
