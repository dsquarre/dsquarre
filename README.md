# Hi, I'm Danish 👋

Final-year B.Tech student at **IIT (BHU) Varanasi** working on applied machine learning: computer vision, reinforcement learning, federated learning and LLM agents.
I like implementing methods from papers from scratch and testing whether they actually work.

🎯 Looking for **full-time Applied Scientist / Data Scientist / ML Engineer roles** starting 2027 (India).

---

### 🔬 Research & work

- **Federated learning (AWS-sponsored research, IIT BHU, ongoing).**
  Centralized FL system built from scratch (Python, FastAPI WebSockets, TensorFlow) for privacy-preserving atrial-fibrillation detection on ECG. FedAvg, FedFV, FedAdam and q-FedAvg implemented from their papers, plus LinUCB and hierarchical RL client selection. Deployed as 100 networked Docker clients on 10 AWS EC2 instances. An empirical study showed that no information available before aggregation predicts even the one-round greedy client choice under highly skewed data. Manuscript in preparation for TMLR.
- **Dental X-ray detection (Data Science Intern, Dobbe AI).**
  Detection and segmentation models (YOLO, DINO, U-Net, Keypoint R-CNN) for a production X-ray service.
  Wrote a dynamic-programming sequence-alignment post-processor that raised tooth-numbering F1 from about 75% to over 90% on validation data.

### 🛠️ Selected projects

| Project | What it is |
|---|---|
| **[Crop Planning POMDP + Oracle RLVR harness](https://github.com/dsquarre/FarmSimulator)** | 10-season farm simulation with NP-hard mechanics for RL-training LLMs against an exact dynamic-programming oracle. A scratchpad-and-verify prompt took GPT Luna from 12–13 to 30+ rounds, reaching 82% of oracle profit on one seed. |
| **[AlphaZero for Dots and Boxes](https://github.com/dsquarre/DotGame)** | AlphaZero from scratch in Python, NumPy and PyTorch (MCTS + CNN policy/value heads). Much higher Elo than minimax on boards from 2x2 to 5x5. |
| **[Synthetic data for scarce tabular data](https://github.com/dsquarre/SynthDataGen)** | 3 imputation methods x 5 generators (CART, Gaussian Copula, CopulaGAN, CTGAN, TVAE) under leakage-free 5-fold CV. First-author paper at ICSRI 2026. |
| **[vLLM stress test](https://github.com/dsquarre/vllm-testing)** | Load-tested a vLLM inference agent under heavy traffic with 0% cache hits on Kaggle free-tier T4 GPUs. |


### 📄 Publications

- **D. Dubey** et al., *Synthetic Data Augmentation and Robust Preprocessing for Predicting Cyclic Response of CFST Columns*, ICSRI 2026 (first author).

### Tools

Python · PyTorch · TensorFlow · scikit-learn · XGBoost · OpenCV · vLLM · FastAPI · Docker · AWS · SQL
