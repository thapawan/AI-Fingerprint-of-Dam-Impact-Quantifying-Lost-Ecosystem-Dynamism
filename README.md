AI Fingerprint of Dam Impact: Quantifying Lost Ecosystem Dynamism

Project Summary

This project introduces a novel, unsupervised approach to quantify the ecological impact of dams by measuring the loss of natural ecosystem variability (dynamism) in river floodplains. We move beyond traditional single-band indices (like $\text{NDVI}$) by utilizing state-of-the-art AlphaEarth Satellite Embeddings—a 64-dimensional $\text{AI}$ vector representation of the Earth's surface—to generate a holistic "AI Change Score."

The study uses a crucial paired-river comparison (one dam-regulated, one free-flowing) to isolate the dam's effect and validate the $\text{AI}$ metric without relying on expensive, time-consuming ground truth data.

🔬 Research Framework

1. Research Question (The Why)

Can an $\text{AI}$-derived "change score" (AlphaEarth embedding distance) accurately measure how much a dam makes a floodplain unnaturally stable compared to a natural river?

2. Hypothesis

The dam-regulated floodplain will exhibit a significantly lower $\text{AI}$ change score (i.e., less dynamism) than the unregulated floodplain, demonstrating that flow stabilization drastically suppresses the natural, multi-dimensional changes essential for ecosystem health.

3. Prediction

The average AlphaEarth Change Score for the unregulated river floodplain will be statistically $\mathbf{3x}$ to $\mathbf{5x}$ higher than the score for the regulated river floodplain, proving the $\text{AI}$ metric is sensitive to the stabilizing effect of the dam.

💻 Methodology (The How)

1. Data Acquisition

Satellite Embeddings: Utilizes annual, 64-dimensional $\text{AlphaEarth}$ embedding layers for two defined study areas (Regulated River and Unregulated River) across a 5-year period (e.g., $\text{Y1}$ to $\text{Y5}$).

Study Area: Focus on the $\mathbf{5 \text{ km}}$ buffer zone surrounding the river channel in the downstream floodplain of both systems.

2. Computing the "AI Change Score"

The core metric is the Euclidean Distance between the $\text{AlphaEarth}$ vectors for the same location over time:

<img width="418" height="58" alt="image" src="https://github.com/user-attachments/assets/19ed4ce5-a0c1-446c-b05b-ce1dbae2b82c" />


This calculation is repeated annually for every pixel ($P$) within the defined floodplain mask for both the regulated and unregulated sites.

3. Validation Strategy (No Ground Truth)

Due to the lack of ground data, we employ an unsupervised, three-part validation approach:

<img width="449" height="279" alt="image" src="https://github.com/user-attachments/assets/a9230120-bc76-4273-843a-cdbc51dbef21" />

🚀 Potential Impact

This project demonstrates a scalable, cost-effective method to monitor ecosystem health globally, offering environmental managers and conservationists a powerful new tool for rapid, continuous assessment of infrastructure impact without the need for extensive field campaigns.
