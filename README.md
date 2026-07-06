# Behavioral Proxy Conditioning for Financial Stress Scenario Generation with a Pretrained Diffusion Model

Official repository for our ICML 2026 Workshop paper.

<h2 align="justify">Abstract</h2>

<p align="justify">
Controllable financial scenario generation is challenging because historical crises are rare and difficult to model directly. To address this, we adapt a pretrained diffusion model for financial time-series generation using interpretable behavioral proxy conditioning. The proxy combines HMM regime probabilities, cross-market correlation, and realized volatility rank, allowing the model to generate calm and stress scenarios for seven global equity indices. To make conditioning more robust, we randomly drop proxy groups during training, allowing the model to use information from all components. These design choices enable the model to generate realistic financial scenarios that remain responsive to regime conditions. The final model passes <b>27/28 regime-separation checks</b> across four random seeds (20/21 risk/tail checks and 7/7 volatility sanity checks), achieving an average <b>stress-to-calm volatility ratio of 2.47 ± 0.08×</b> with <b>0% exact replay</b> of historical windows. Portfolio-level stress scenarios also exhibit substantially worse <b>CVaR<sub>95</sub></b> than calm scenarios, suggesting that behavioral proxy conditioning can effectively adapt pretrained generative models for downstream financial stress testing under data scarcity.
</p>

## Poster

📄 **ICML 2026 Workshop Poster**

- `ICML2026_Poster.pdf`

## Paper

📑 **Workshop Paper**

- `ICML2026_Workshop_Paper.pdf`

## Highlights

- Pretrained diffusion model adapted without architectural changes
- Interpretable 5-D behavioral proxy conditioning
- Controllable calm ↔ stress generation
- 27/28 regime-separation checks
- 0% exact replay of historical windows
- Improved downside-risk control on held-out real returns

## Citation

```bibtex
@inproceedings{kuular2026behavioral,
  title={Behavioral Proxy Conditioning for Financial Stress Scenario Generation with a Pretrained Diffusion Model},
  author={Kuular, Elena and Choe, Junsuk},
  booktitle={ICML Workshop on Foundation Models for Structured Data},
  year={2026}
}
```

## Contact

- **Elena Kuular**
- 📧 eakuular@sogang.ac.kr - 📧 eakuular@gmail.com
- 💼 LinkedIn: https://www.linkedin.com/in/elena-kuular/
- 🏫 Sogang University, Department of Computer Science & Engineering
