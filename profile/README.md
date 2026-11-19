# HEP-Ex-Bench

**HEP-Ex-Bench** benchmarks AI agents that carry out experimental high-energy physics measurements.  It evaluates an
agent's analysis quantitatively with blind analysis and injection tests, the checks at the heart of an expert review.
The agent develops a data analysis pipeline on a public dataset.  That single pipeline is then evaluated on sealed
worlds: private datasets generated programmatically, with injected signals and with simulation settings varied within
realistic detector uncertainties.  This tests both the accuracy and the robustness of the workflow.  The benchmarks
are built from CMS open data.

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
