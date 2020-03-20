## Meta Anti-spoofing: Learning to Learn in Face Anti-spoofing

We define face antispoofing as a few-shot learning problem with evolving new
attacks and propose a novel face anti-spoofing approach
via meta-learning named Meta Face Anti-spoofing (MetaFAS). Meta-FAS addresses the above-mentioned problems
by training the classifiers how to learn to detect the spoofing faces with few examples. To assess the effectiveness of
the proposed approach, we propose a series of evaluation
benchmarks based on public datasets (e.g., OULU-NPU,
SiW, CASIA-MFSD, Replay-Attack, MSU-MFSD, 3D-MAD,
and CASIA-SURF), and the proposed approach shows its
superior performances to compared methods.


- To the best of our  knowledge, we are the first to define
face anti-spoofing as a few-shot learning problem with
evolving new attacks. We further consider zero-shot
scenario as a boundary condition of this issue.
- We propose a novel meta-learning based approach –
Meta-FAS – by imitating the process of few-shot scenarios to learn the capability of learning the discrimination between living and spoofing faces.
- Three novel few-shot face anti-spoofing benchmarks
are developed: MiniOULU for the single-domain,
MiniCrossfor the cross-domain, and MiniSURF for the
cross-modal. These benchmarks provide protocols for
evaluation of both supervised learning based models
and meta-learning based models.
- Extensive experiments demonstrate that Meta-FAS
achieves state-of-the-art results on all three few-shot
anti-spoofing benchmarks as well as one general antispoofing benchmark.
