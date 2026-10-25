### Hi, I'm Sam 👋

Infrastructure and operations analyst in Sydney, working in data-centre operations: monitoring, power and telemetry data, Modbus, and reporting. On my own time I measure **local AI on AMD hardware** the same way: power, cost, failure modes, and what an organisation is really buying when it keeps AI in-house.

**🔬 [rdna4-local-ai-lab](https://github.com/getsamsultan/rdna4-local-ai-lab)**: 3× Radeon AI PRO R9700 (96 GB), measured and reproducible

- 🧠 Blind test on my own work questions: a 177B model scored 27/30, an 80B 18/30, and the 80B answered 3.7× faster
- 🚀 Update llama.cpp, not ROCm: a newer engine gave ~+20% (54.5 → 65.3 tokens/s); ROCm 7.2 → 10.1 on the same build was no faster (and ~3% slower on a 177B)
- 🔧 Traced one config line costing 61% of serving speed
- ⚡ A$0.71 of electricity per million tokens, but ~17 years to pay back the hardware vs renting: local AI is a control decision

**🧪 [model-editing-lab](https://github.com/getsamsultan/model-editing-lab)**: what it costs to change an open model's weights

**How I test:** one variable at a time, raw data published, and A–B–A, the omega-3 of benchmarking: baseline, change, baseline again.

**Running different hardware?** [Send me your numbers](https://github.com/getsamsultan/rdna4-local-ai-lab/issues/new?template=rig-results.yml).

[X @sultanminutes](https://x.com/sultanminutes) · [LinkedIn](https://www.linkedin.com/in/samsultan-it)
