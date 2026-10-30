---
title: "Does Quantization Forget the Quiet Murmurs? (ongoing research)"
excerpt: "Trustworthiness audit of INT8/INT4 quantized pediatric heart-sound (PCG) classifiers on the CirCor DigiScope dataset — measuring what compression does to calibration, robustness, and clinically relevant failure modes, not just accuracy."
collection: portfolio
---

Edge deployment of medical audio classifiers demands aggressive compression — but a model that stays "accurate" after INT8/INT4 quantization can still silently degrade on the quiet, low-energy murmurs that matter most clinically.

This ongoing research audits post-training quantization of pediatric phonocardiogram classifiers (CirCor DigiScope dataset) across:

* Accuracy, calibration, and per-class degradation (do rare murmur classes suffer disproportionately?)
* Robustness to noise and recording conditions
* Failure-mode shifts that matter for clinical triage

[Code on GitHub](https://github.com/Mustafa-bacha/pcg-quant-audit)
