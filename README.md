# Finsler speech morphing

This repository contains some audible results of the speech morphing procedure illustrated in Section V of the paper:

G. Baggio, A. Ferrante, R. Sepulchre, "Conal Distances Between Rational Spectral Densities", *IEEE Transactions on Automatic Control*, vol. 64, no. 5, pp. 1848-1857, May 2019. (pre-print available at https://arxiv.org/abs/1708.02818)


**Instructions:**

- files "speech_man.wav" and "speech_woman.wav" contain a sentence spoken by a male and female individual
- files "synt_speech_man.wav" and "synt_speech_woman.wav" contain the resulting synthesized sentences obtained via Linear Predictive Coding
- file "morphed_sentence_interp.wav" contain some samples of the interpolated speech signal (from synthesized female to synthesized male voice) obtained using Finsler geodesic path according to the method discussed in the above reference
- file "morphed_sentence_extrap_woman.wav" contain some samples of the extrapolated speech signal (from synthesized female voice) obtained using Finsler geodesic path according to the method discussed in the above reference

