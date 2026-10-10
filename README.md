# 🚀 Machine Learning & Deep Learning Interview Mastery System

[![Deploy to GitHub Pages](https://github.com/gvrathodd/MLDL-Interview-Mastery/actions/workflows/pages.yml/badge.svg)](https://github.com/gvrathodd/MLDL-Interview-Mastery/actions/workflows/pages.yml)
[![Live Site](https://img.shields.io/badge/Live_Site-GitHub_Pages-2ea44f?style=for-the-badge&logo=github)](https://gvrathodd.github.io/MLDL-Interview-Mastery/)
[![Curriculum](https://img.shields.io/badge/Curriculum-10_Complete_Modules-38bdf8?style=for-the-badge)](#curriculum-breakdown)
[![FAANG Questions](https://img.shields.io/badge/FAANG_Q&As-250+-c084fc?style=for-the-badge)](#highlights)
[![Interactive Quizzes](https://img.shields.io/badge/Interactive_Quizzes-100_Questions-34d399?style=for-the-badge)](#interactive-quizzes)

> **Live Interactive Portal:** [**https://gvrathodd.github.io/MLDL-Interview-Mastery/**](https://gvrathodd.github.io/MLDL-Interview-Mastery/)

An industry-grade, interview-ready **10-Module Machine Learning & Deep Learning Curriculum** engineered for aspiring Machine Learning Engineers (MLEs), Applied Scientists, and Research Scientists targeting top-tier tech companies (FAANG / AI Labs).

---

## 🌟 Key Features

1. **First-Principles Rigor (Zero Hand-Waving):** Every single algorithm starts with a physical analogy, progresses to formal linear algebra and multivariable calculus proofs, and concludes with production engineering realities.
2. **Solved Toy Numerical Walkthroughs:** Step-by-step arithmetic calculated by hand with real numbers (XGBoost 3-row split gains, 2-2-1 MLP backpropagation, GMM-EM updates, Candidate Elimination, and Multi-Head Scaled Dot-Product Attention).
3. **250+ FAANG Interview Questions:** Complete technical answers covering tricky conceptual edge cases, mathematical derivations, and systems trade-offs asked at Meta, Google, OpenAI, Anthropic, Apple, and Microsoft.
4. **100 Interactive Self-Assessment Quizzes:** Client-side instant grading with green/red visual cues and detailed explanations.
5. **Phone & Tablet Optimized:** Responsive dark UI with a collapsible mobile hamburger drawer, fluid KaTeX math rendering, and zero-token offline usability.

---

## 📚 Curriculum Breakdown

### 📊 Part I: Classical Machine Learning Mastery

| Module | Title | Live Link | Key Topics & Mathematical Proofs |
| :--- | :--- | :--- | :--- |
| **ML 1** | **Foundations & Concept Learning** | [Open Module 1](https://gvrathodd.github.io/MLDL-Interview-Mastery/module1_interview_guide.html) | Find-S algorithm, Candidate Elimination, Version Spaces, No Free Lunch theorem, PAC learning, and Covariate vs Concept drift. |
| **ML 2** | **Data Engineering & Evaluation** | [Open Module 2](https://gvrathodd.github.io/MLDL-Interview-Mastery/module2_interview_guide.html) | Rubin's Missing Taxonomy (MCAR/MAR/MNAR), Tukey 1.5 IQR proof, Target Encoding leakage, PR vs ROC curves, Micro-F1 = Accuracy proof, SMOTE, and Platt scaling. |
| **ML 3** | **Linear Models & Optimization** | [Open Module 3](https://gvrathodd.github.io/MLDL-Interview-Mastery/module3_interview_guide.html) | Normal Equation derivation, SVD Pseudoinverse ($X^+$), Momentum/Adam optimizers, Bias-Variance algebraic proof, Lasso Diamond geometry, L.I.N.E. assumptions & VIF, and BCE global convexity. |
| **ML 4** | **Ensembles & Gradient Boosters** | [Open Module 4](https://gvrathodd.github.io/MLDL-Interview-Mastery/module4_interview_guide.html) | Strict concavity of Gini/Entropy, 14-row PlayTennis calculation, Cost-Complexity Pruning ($CCP_\alpha$), Ensemble variance proof ($\rho \sigma^2 + \frac{1-\rho}{B}\sigma^2$), OOB $1/e \approx 36.8\%$ proof, AdaBoost, XGBoost 2nd-order Taylor expansion with 3-row numerical walkthrough, LightGBM (GOSS/EFB), and CatBoost. |
| **ML 5** | **Bayesian Learning & PGMs** | [Open Module 5](https://gvrathodd.github.io/MLDL-Interview-Mastery/module5_interview_guide.html) | Base rate fallacy, MLE vs MAP vs Full Bayesian, Gaussian $\implies$ MSE proof, Bernoulli $\implies$ Log-Loss proof, Naïve Bayes spam calculation, BBN d-separation (Explaining Away), EM Jensen's Inequality ELBO, GMM 1D numerical walkthrough, $K$-Means zero-variance limit proof, and Thompson Sampling. |

---

### 🧠 Part II: Deep Learning & Generative AI Mastery

| Module | Title | Live Link | Key Topics & Mathematical Proofs |
| :--- | :--- | :--- | :--- |
| **DL 1** | **Neural Foundations & Calculus** | [Open DL-1](https://gvrathodd.github.io/MLDL-Interview-Mastery/dl_module1_interview_guide.html) | Perceptrons, Minsky XOR crisis algebraic proof, Activation Zoo (Sigmoid saturation $\le 0.25$, Tanh, ReLU, GELU, Swish), Vectorized Backpropagation Jacobian chain rule ($\delta^{[l]}$), 2-2-1 MLP numerical walkthrough, Xavier & He initialization proofs, Softmax-CE gradient ($\hat{y} - y$), and Cybenko Universal Approximation. |
| **DL 2** | **Loss Landscapes & Optimizers** | [Open DL-2](https://gvrathodd.github.io/MLDL-Interview-Mastery/dl_module2_interview_guide.html) | High-dimensional saddle points, Hessian condition number $\kappa$, Momentum & NAG look-ahead, Complete Adam bias-correction proof ($\frac{m_t}{1-\beta_1^t}$), AdamW decoupled weight decay proof ($L_2 \ne \text{Weight Decay}$), Cosine Annealing, BatchNorm Lipschitz smoothing proof, RMSNorm, Inverted Dropout $1/(1-p)$, Deep Double Descent, and DDP Ring-AllReduce $2M$ volume proof. |
| **DL 3** | **CNNs & Computer Vision** | [Open DL-3](https://gvrathodd.github.io/MLDL-Interview-Mastery/dl_module3_interview_guide.html) | Spatial locality & translation equivariance, 2D conv output shape formula $\lfloor \frac{W-K+2P}{S} \rfloor + 1$, Receptive Field recursive calculus with 3-layer calculation, $1\times 1$ conv bottlenecks, Dilated convs, VGG two $3\times 3$ stacking proof ($18C^2 < 25C^2$), ResNet gradient highway proof ($\mathbf{I} + \dots$), MobileNet depthwise separable 8x FLOPs reduction proof, ResNeXt, ConvNeXt, YOLO, and U-Net. |
| **DL 4** | **RNNs, LSTMs & Attention** | [Open DL-4](https://gvrathodd.github.io/MLDL-Interview-Mastery/dl_module4_interview_guide.html) | Sequence modeling physics, Vanilla RNN & BPTT unrolling, BPTT vanishing gradient Jacobian product proof ($\prod W_{hh}^T \text{diag}(1-h_k^2)$), LSTM Constant Error Carousel additive gradient highway proof, Forget gate $+1$ bias initialization, GRU 2-gate math, Seq2Seq information bottleneck crisis, Bahdanau additive vs Luong multiplicative attention, worked toy attention numerical walkthrough, CTC loss, and Beam Search. |
| **DL 5** | **Transformers & Generative DL** | [Open DL-5](https://gvrathodd.github.io/MLDL-Interview-Mastery/dl_module5_interview_guide.html) | Scaled Dot-Product $\sqrt{d_k}$ variance preservation proof, Multi-Head Attention projections, Rotary Position Embeddings (RoPE) complex plane rotation derivation, Pre-LN vs Post-LN gradient stability proof, SwiGLU & RMSNorm, BERT vs GPT vs T5 archetypes, exact KV cache VRAM formula ($2 \times L \times H \dots$), GQA, FlashAttention SRAM tiling & online softmax, Chinchilla scaling laws ($C \approx 6ND$), SFT prompt loss masking, DPO closed-form reward proof, LoRA low-rank $BA$ math, QLoRA NF4, PTQ (AWQ vs GPTQ vs SmoothQuant), VAE ELBO & reparameterization trick, and DDPM diffusion math. |

---

## 💻 Local Offline Usage

You can also clone this repository and view all modules completely offline in any web browser without needing any internet connection, local web server, or Node.js runtime:

```bash
# Clone the repository
git clone https://github.com/gvrathodd/MLDL-Interview-Mastery.git

# Enter directory
cd MLDL-Interview-Mastery

# Open the master portal in your default browser (Windows)
start index.html

# On macOS
open index.html

# On Linux
xdg-open index.html
```

---

## 🛠️ Tech Stack

* **Frontend:** Clean Vanilla HTML5, CSS3 (Modern Flexbox & CSS Grid, Custom Properties, Dark Mode).
* **Math Typesetting:** [KaTeX](https://katex.org/) (High-performance $\LaTeX$ rendering loaded via jsDelivr CDN).
* **Deployment:** GitHub Pages & GitHub Actions automated CI/CD.
* **Dependencies:** Zero runtime dependencies, zero build step required.

---

## 📜 License

Created for educational and interview preparation purposes. Open access for students, engineers, and researchers worldwide.
