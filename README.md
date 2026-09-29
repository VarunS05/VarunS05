<p align="center">
  <img src="assets/banner.svg" width="100%" alt="Varun S — Full-stack engineer. ML/CV & RAG systems." />
</p>

<p align="center">
  <img src="https://readme-typing-svg.demolab.com/?font=Fira+Code&size=20&duration=2800&pause=1200&color=D8B877&background=00000000&center=true&vCenter=true&width=600&lines=ship+it%2C+then+check+if+it's+actually+correct;subject-independent+%E2%89%A0+subject-dependent;beats+the+baseline%2C+or+it+doesn't+count" alt="typing banner" />
</p>

I build things across the stack, then go back and check whether they're actually correct — a tracker that demos well but has never been evaluated on unseen subjects isn't finished, it's just unverified. That gap is most of what I find interesting.

Software Engineer Intern at **L7 Informatics** (RAG assistant + CI automation). Before that, real-time lane detection with YOLOv8 at the **National University of Singapore**.

<br/>

<p align="center">
  <img src="https://skillicons.dev/icons?i=py,js,react,vue,nodejs,aws,docker,tensorflow,pytorch,opencv,postgres&theme=dark" alt="stack" />
</p>

<br/>

<details open>
<summary><b>colorway</b> — serverless design-asset pipeline (AWS Lambda, Step Functions, Rekognition, React)</summary>
<br/>

S3 upload → Step Functions runs thumbnail generation → dominant-color extraction → Rekognition auto-tagging → DynamoDB. React gallery on top, filterable by color and tag.

*Field note: the color palette in the banner above was extracted by this pipeline's own `color_extraction.py`, run against real test footage — not a design tool.*

[→ repo](https://github.com/VarunS05/colorway)
</details>

<details>
<summary><b>eeg-ecg-emotion-recognition</b> — valence/arousal/dominance from EEG + ECG signals (DREAMER benchmark)</summary>
<br/>

Subject-independent cross-validation, reported next to a majority-class baseline instead of one accuracy number. An earlier version of this used labels derived from the same features it was predicting — technically high accuracy, structurally meaningless. Rebuilt on real self-report ground truth.

[→ repo](https://github.com/VarunS05/eeg-ecg-emotion-recognition)
</details>

<details>
<summary><b>stocksavvy</b> — sentiment-aware price forecasting (VADER, chronological CV)</summary>
<br/>

News sentiment + technical indicators, evaluated with a chronological train/test split against a random-walk baseline. Most of the honest finding here is negative: the model doesn't beat "assume no change" — which is itself the correct, unglamorous result for short-horizon return forecasting.

[→ repo](https://github.com/VarunS05/stocksavvy)
</details>

<details>
<summary><b>video-analytics-toolkit</b> — classical CV: tracking, counting, dwell-time (OpenCV)</summary>
<br/>

Background-subtraction tracking, entry/exit line-crossing counts, multi-object dwell-time via a centroid tracker. No neural net — the interesting part is getting the classical techniques right.

[→ repo](https://github.com/VarunS05/video-analytics-toolkit)
</details>

<br/>

<p align="center">
  <img src="https://streak-stats.demolab.com?user=VarunS05&hide_border=true&background=282C2E&stroke=34464D&ring=D8B877&fire=D8B877&currStreakLabel=F2EDE3&sideLabels=F2EDE3&currStreakNum=F2EDE3&sideNums=F2EDE3&dates=8FA3A8" width="60%" alt="streak" />
</p>

<br/>

**Published**

<table>
<tr>
<td width="50%" valign="top">
<a href="https://link.springer.com/chapter/10.1007/978-3-032-16099-7_30"><img src="https://img.shields.io/badge/Springer-282C2E?style=for-the-badge&logoColor=D8B877" alt="Springer" /></a>
<br/><br/>
<sub>An Optimized ICT Framework for Lung Cancer Using Recursive Information Gain and Feature Elimination — EAI BODYNETS / Bharat 6G Workshop 2024</sub>
</td>
<td width="50%" valign="top">
<a href="https://ieeexplore.ieee.org/document/10910846"><img src="https://img.shields.io/badge/IEEE-00629B?style=for-the-badge&logo=ieee&logoColor=white" alt="IEEE" /></a>
<br/><br/>
<sub>A Hybrid Deep Learning Algorithm for Improved ChatBot Accuracy and Relevance through Advanced RAG — ICSES 2024</sub>
</td>
</tr>
</table>

<br/>

<p align="center">
  <a href="mailto:varunsgm05@gmail.com"><img src="https://img.shields.io/badge/email-282c2e?style=for-the-badge&logo=gmail&logoColor=D8B877" alt="email" /></a>
  <a href="https://www.linkedin.com/in/varun-s-46150a215/"><img src="https://img.shields.io/badge/linkedin-282c2e?style=for-the-badge&logo=linkedin&logoColor=D8B877" alt="linkedin" /></a>
</p>

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=VarunS05&label=profile+views&color=34464d&style=for-the-badge" alt="profile views" />
</p>
