<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:0D1117,50:161B22,100:1F6FEB&height=200&section=header&text=Peerawut%20Eiamin&fontSize=42&fontColor=ffffff&animation=fadeIn&fontAlignY=35&desc=AI%20Researcher%20·%20Data%20Science%20@%20Burapha%20University&descSize=16&descAlignY=58" alt="header" />
</div>

<div align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=22&pause=1000&color=79C0FF&center=true&vCenter=true&width=680&lines=Time-series+forecasting+for+public+health;Thai+speech+and+mispronunciation+detection;Computer+vision+for+agriculture;Reproducible+ML+evaluation+protocols" alt="typing" />
</div>

<br />

<div align="center">

[![Location](https://img.shields.io/badge/Thailand-0D1117?style=for-the-badge&logo=googlemaps&logoColor=79C0FF)](https://github.com/perawutaemin)
[![University](https://img.shields.io/badge/Burapha%20University-0D1117?style=for-the-badge&logo=google-scholar&logoColor=79C0FF)](https://www.buu.ac.th)
[![ORCID](https://img.shields.io/badge/ORCID-0009--0008--6775--7290-0D1117?style=for-the-badge&logo=orcid&logoColor=A6CE39)](https://orcid.org/0009-0008-6775-7290)
[![Profile views](https://komarev.com/ghpvc/?username=perawutaemin&label=Profile%20views&color=1F6FEB&style=for-the-badge)](https://github.com/perawutaemin)

</div>

---

## About me

สวัสดีครับ ผม **พีรวุฒิ เอี่ยมอินทร์** — AI researcher ในหลักสูตร Data Science มหาวิทยาลัยบูรพา

I design **reproducible machine-learning evaluation protocols** for problems that matter in Thailand: epidemic forecasting, Thai speech assessment, and agricultural computer vision. I care more about a fair comparison under a frozen split than about proposing a new architecture every paper.

- Currently working on **one-year-ahead dengue forecasting** and **phoneme-level Thai MDD**
- Always learning **time-series ML**, **speech models**, and **evaluation design**
- Open to collaboration on **public-health AI**, **Thai NLP/speech**, and **applied computer vision**
- Ask me about **XGBoost**, **SARIMA**, **wav2vec2 / Whisper**, **YOLO**, and **walk-forward validation**
- ORCID: [0009-0008-6775-7290](https://orcid.org/0009-0008-6775-7290)

---

## Research focus

```text
Public health forecasting   Thai speech / MDD   Agricultural CV
        │                         │                    │
        ▼                         ▼                    ▼
  SARIMA · XGBoost          ASR front-ends         YOLO · TF
  cross-country lags        phoneme alignment      mobile deploy
  weather covariates        pooled calibration     leaf disease
```

| Area | What I actually do |
| --- | --- |
| **Time-series / epidemiology** | Walk-forward protocols, lagged covariates, SARIMA vs gradient boosting |
| **Speech & pronunciation** | Thai ASR front-end comparison, G2P, phoneme edit operations, F1 calibration |
| **Computer vision** | Object detection for plant disease, model selection for mobile inference |
| **Evaluation design** | Frozen splits, shared decision rules, held-out production years |

---

## Featured research

<table>
<tr>
<td width="50%" valign="top">

### Dengue forecasting in Thailand

One-year-ahead **weekly dengue** forecasts comparing **SARIMA** with four **XGBoost** setups. Partner-country case lags and weather features are screened, pruned by gain, then frozen before a held-out 2024 production year.

**XGBoost South Korea** (lag-50 cases + precipitation) reached **RMSE 1,622 / MAE 1,293**, beating SARIMA and Thailand self-lag.

[GitHub](https://github.com/perawutaemin/Dengue-Forecasting-Conf) · ICTC 2026 manuscript

`Python` `XGBoost` `SARIMA` `walk-forward`

</td>
<td width="50%" valign="top">

### Two-stage Thai MDD

A two-stage benchmark for **phoneme-level mispronunciation detection**. Stage 1 scores five Thai ASR models on WER / CER / SER. Stage 2 maps transcripts to phonemes and applies a **shared (θ, k)** rule calibrated on 800 utterances, tested on 200.

Ranking is **metric-dependent** — pick the front-end for the downstream task, not the leaderboard WER.

[GitHub](https://github.com/perawutaemin/Two-Stage-Thai-MDD-Conf)

`wav2vec2` `Whisper` `PyThaiNLP` `PER`

</td>
</tr>
<tr>
<td width="50%" valign="top">

### Durian leaf disease on mobile

Comparative study of **YOLOv5**, **YOLOv8**, and **TensorFlow** for detecting leaf spot, leaf blight, and Phytophthora fruit rot in the Ultralytics Hub mobile app.

YOLOv5 led at **93.33%** accuracy vs 80% (YOLOv8) and 63.33% (TensorFlow).

[Paper](https://doi.org/10.3233/faia241595) · EJC 2024 / FAIA 399

`YOLO` `TensorFlow` `mobile CV`

</td>
<td width="50%" valign="top">

### How I like to work

- One protocol, many models — not a new net every time
- Screen and prune on history, **never** on the test year
- Report the metric that matches the decision, not only the flattering one
- Ship code, tables, and figures so others can rerun the comparison

</td>
</tr>
</table>

---

## Publications

1. **Eiamin, P.**, Bouvry, P., Chophuk, P., & Methiyothin, T. (2026). *Forecasting Dengue Fever in Thailand Using Cross-Country Case Correlation and Weather Features.* ICTC 2026. [Code](https://github.com/perawutaemin/Dengue-Forecasting-Conf)
2. **Eiamin, P.**, Methiyothin, T., & Chophuk, P. (2026). *A Two-Stage Comparative Study of Thai-Suitable Speech Models for Phoneme-Level Mispronunciation Detection.* [Code](https://github.com/perawutaemin/Two-Stage-Thai-MDD-Conf)
3. **Eiamin, P.**, Janoum, P., Puangmanee, J., & Chophuk, P. (2024). *Comparative Evaluation of YOLOv5, YOLOv8, and TensorFlow for Optimal Model Selection in Durian Leaf Disease Detection via Mobile Application.* In *Information Modelling and Knowledge Bases XXXVI* (FAIA 399), 401–411. IOS Press. [DOI](https://doi.org/10.3233/faia241595)

---

## Stack

<div align="center">
  <img src="https://skillicons.dev/icons?i=python,pytorch,tensorflow,sklearn,opencv,anaconda,jupyter,linux,docker,git,github,vscode" alt="tech stack" />
</div>

<br />

**Machine learning**  
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![XGBoost](https://img.shields.io/badge/XGBoost-FF6600?style=flat-square)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=flat-square&logo=tensorflow&logoColor=white)
![statsmodels](https://img.shields.io/badge/statsmodels-SARIMA-4B8BBE?style=flat-square)

**Speech & language**  
![Transformers](https://img.shields.io/badge/Hugging%20Face-FFD21E?style=flat-square&logo=huggingface&logoColor=black)
![Whisper](https://img.shields.io/badge/Whisper-412991?style=flat-square)
![wav2vec2](https://img.shields.io/badge/wav2vec2-FF6F00?style=flat-square)
![PyThaiNLP](https://img.shields.io/badge/PyThaiNLP-1B5E20?style=flat-square)

**Vision & data**  
![YOLO](https://img.shields.io/badge/YOLO-00FFFF?style=flat-square&logo=yolo&logoColor=black)
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=flat-square&logo=opencv&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-11557C?style=flat-square)

---

## GitHub stats

<div align="center">
  <img height="165" src="https://github-readme-stats.vercel.app/api?username=perawutaemin&show_icons=true&theme=tokyonight&hide_border=true&count_private=true&bg_color=0D1117&title_color=79C0FF&icon_color=1F6FEB&text_color=C9D1D9" alt="GitHub stats" />
  <img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=perawutaemin&layout=compact&theme=tokyonight&hide_border=true&bg_color=0D1117&title_color=79C0FF&text_color=C9D1D9" alt="Top languages" />
</div>

<div align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=perawutaemin&theme=tokyonight&hide_border=true&background=0D1117&ring=1F6FEB&fire=79C0FF&currStreakLabel=79C0FF" alt="GitHub streak" />
</div>

---

## Connect

<div align="center">

[![GitHub](https://img.shields.io/badge/GitHub-perawutaemin-0D1117?style=for-the-badge&logo=github&logoColor=white)](https://github.com/perawutaemin)
[![ORCID](https://img.shields.io/badge/ORCID-0009--0008--6775--7290-A6CE39?style=for-the-badge&logo=orcid&logoColor=white)](https://orcid.org/0009-0008-6775-7290)
[![DOI](https://img.shields.io/badge/DOI-10.3233%2Ffaia241595-0D1117?style=for-the-badge&logo=doi&logoColor=79C0FF)](https://doi.org/10.3233/faia241595)

</div>

<p align="center">
  <em>Thanks for stopping by — if you work on forecasting, Thai speech, or applied CV, let’s compare notes.</em>
</p>

<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:1F6FEB,100:0D1117&height=120&section=footer" alt="footer" />
</div>
