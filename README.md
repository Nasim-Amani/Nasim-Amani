## Hi, I'm Nasim Amani 👋

**Deep learning researcher working on time series, images and language.**
Most of my work starts with real data that is noisy, incomplete or simply messy, and ends with a model I can trust and explain.
I also teach AI through published online courses.


### 🧭 My research path

Most projects started with a question the previous one left open.

**1. Can comfort explain demand?** ⚡
My MSc began with Transformers for electricity load forecasting, using **human thermal comfort indices**
instead of raw weather data as inputs.
*(manuscript under review)*

**2. Which attention works, and when?** 🔍
That made me curious about attention itself. I compared **additive, global and multi-head attention**
in Seq2Seq models across forecast horizons, with more climate variables and Bayesian optimisation for each horizon.
The answer: no single mechanism wins everywhere.
→ [IEEE ICEE 2026](https://doi.org/10.1109/ICEE70628.2026.11710637) · *IET Renewable Power Generation* (accepted) · [code](https://github.com/Nasim-Amani/AttnSeq2Seq-LoadForecasting)

**3. How much does preprocessing really matter?** 🌬️
With 13 years of real airport observations from Oman, I tested this step by step. I built a pipeline for outlier correction, gap-aware imputation and wavelet denoising, measured what each stage added, and found that careful preprocessing, especially denoising, improved gust forecasts more than model tuning.
*(manuscript under review)*

**4. Can a model show *why* it decides?** 🦠
In a collaborative study, we applied transfer learning to SEM images of fuel-cell electrodes and used **Grad-CAM**
to check that the models looked at the right regions, validated against independent electrochemical measurements.
→ *Bioresources and Bioprocessing* (accepted) · [code](https://github.com/Nasim-Amani/sem-mfc-biofilm-classification)

**5. Now: rare and abrupt events** 📉
I'm working on sudden ramp events in 1-second solar data, where common metrics can make forecasts look better than they are,
and on fault prediction from power-grid outage records.

**6. Now: teaching AI agents to tag products** 🤖
How should a new product with no history get the right tags? I'm building an **agentic AI system** where an LLM
reads the product description, retrieves similar products, proposes candidate tags and checks them before deciding,
compared step by step with graph-based recommenders such as LightGCN and hypergraph models.

### 🧩 Other projects
- 💹 **Financial time series:** LSTM/RNN vs. Black-Scholes for option pricing → [repo](https://github.com/Nasim-Amani/Option_Pricing)

### 🎓 Teaching
- **Transformers in Python** (5 h, Persian): [course](https://hamruyesh.com/product/transformers-python-tutorial/) · [code](https://github.com/Nasim-Amani/Transformers-from-Scratch)
- **Reinforcement Learning: Snake AI project** (1 h 45 min, Persian): [course](https://hamruyesh.com/product/reinforcement-learning-by-snake-project-tutorial) · [code](https://github.com/Nasim-Amani/SnakeAI)

### 🛠 Tools
Python · PyTorch · TensorFlow/Keras · scikit-learn · pandas · PyWavelets · OpenCV · MATLAB · VHDL

**Also familiar with:** digital communications (modulation, BER analysis) and FPGA/digital design

### 📫 Contact
amaniinasim@gmail.com
