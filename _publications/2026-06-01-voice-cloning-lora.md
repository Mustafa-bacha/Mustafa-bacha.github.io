---
title: "Parameter-Efficient Voice Cloning for South Asian English via LoRA Fine-Tuning of Chatterbox TTS"
collection: publications
category: manuscripts
permalink: /publication/2026-06-01-voice-cloning-lora
excerpt: 'We curate a 577-speaker South Asian English corpus and adapt a 520M-parameter Llama-backbone TTS system with LoRA adapters on 210 transformer projections — training only ~0.1% of weights on under 40 minutes of audio. Speaker similarity improves by 5.06% and the zero-shot baseline&apos;s inverse pitch correlation is reversed, with zero added inference cost after adapter merging.'
date: 2026-06-01
venue: 'Undergraduate thesis manuscript, GIKI (in preparation for submission)'
paperurl: 'https://mustafa-bacha.github.io/files/voice_cloning_lora_tts.pdf'
citation: 'Shah, M. M. (2026). &quot;Parameter-Efficient Voice Cloning for South Asian English via LoRA Fine-Tuning of Chatterbox TTS.&quot; <i>Manuscript</i>.'
---

Zero-shot TTS systems such as VALL-E and Chatterbox clone voices with high fidelity — but fail on underrepresented linguistic varieties like South Asian English, spoken by over 500 million people. This work mitigates that accent gap with a parameter-efficient pipeline:

* **Novel corpus**: 577 speakers of South Asian English with word-level temporal alignments, curated for accent-adaptation research.
* **LoRA-driven adaptation**: adapters injected into all 210 linear projections (attention + feed-forward) of the 30-layer Llama T3 backbone — ~0.1% of the 520M parameters trained on 38.68 minutes of audio.
* **Results**: speaker similarity (ECAPA-TDNN) +5.06% (0.8103 → 0.8513), F0 pitch correlation reversed from −0.164 to +0.093, energy correlation doubled, SNR +3.67 dB.
* **Free at deployment**: adapters merge back into base weights, adding no parameters or latency.

This research underpins **SpeechEcho**, our final-year project showcased at the GIKI Industrial Open House 2026.
