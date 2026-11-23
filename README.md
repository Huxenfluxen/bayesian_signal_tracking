# Bayesian tracking of non-stationary and periodic signals in an environment with structured noise
A statistical signal processing project exploring state-space inference forisolating and tracking drifting periodic rhythms where crossing interference is present.
## Scope
1. Generate realistic, non-stationary periodic signls with known ground truth. Instant phase integrsation, harmonic series, AM/FM coupling, structured crossing interference. Time domain plots and STFT Spectrogram
2. Isolate signal energyt and form likelihoodsurface over frequency. Bandpass filtering, FastICA (when muultiple signals),nSTFT/Morlet,CWT power spectrum. Peak picking baseline MAE during clean vs. interference crossing intervals.
3. Bayesian tracking of drifting frequenciy through crossings and quantify uncertainty. State space transition model, Bootstrap (SMC), Posterior credible intervals.
MAE reductions vs. stage 2 and sanity checks of true CIs.
