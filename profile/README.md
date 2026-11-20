# HEP-Ex-Bench

**HEP-Ex-Bench** evaluates agentic performance in physics analyses with sealed worlds.  It performs detailed
quantitative evaluations of agent-driven analyses through the use of blind analysis and injection tests, which are
critical in a typical expert review.  Agents develop a data analysis pipeline on a public dataset, while the evaluation
is performed on programmatically generated sealed private datasets where signals are injected and simulation settings
varied within realistic detector uncertainties.  By requiring agents to provide a single workflow that is evaluated
across these "sealed worlds", the benchmark tests the accuracy and robustness of the workflows.

## Paper

*HEP-Ex-Bench: Evaluating Agentic Performance in Physics Analyses with Sealed Worlds*  
A. Novák, Y. Zhao, D. Garcia, E. A. Moreno, J. Krupa, V. Bresó-Pla, S. Bright-Thonney, L. Heinrich, M. Kagan, P. Harris  
arXiv: to appear

## Website

The project page with the results: [hep-ex-bench.github.io](https://hep-ex-bench.github.io)

## Benchmark

The harness, the tasks and the agent session scripts are at
[hep-ex-bench/hep-ex-bench](https://github.com/hep-ex-bench/hep-ex-bench).

| Benchmark | Task | Public dataset |
|---|---|---|
| HiggsLepMass (`h4l`) | $\mu$ and $m_\mathrm{H}$ from $\mathrm{H} \to \mathrm{ZZ}^* \to 4\ell$, detector calibrations included | [hep-ex-bench/HiggsLepMass](https://huggingface.co/datasets/hep-ex-bench/HiggsLepMass) |
| HiggsWidth (`h4l_width`) | the Higgs width ratio $\Gamma_\mathrm{H}/\Gamma_\mathrm{SM}$ and the on-shell signal strength from $\mathrm{H} \to \mathrm{ZZ} \to 4\ell$ | [hep-ex-bench/HiggsWidth](https://huggingface.co/datasets/hep-ex-bench/HiggsWidth) |
| LepCalib (`lep_calib`) | lepton calibrations from $\mathrm{Z} \to \ell\ell$ | [hep-ex-bench/LepCalib](https://huggingface.co/datasets/hep-ex-bench/LepCalib) |

## Affiliations

MIT · IAIFI · SLAC · Harvard · TUM
