<div align="center">

<h1 align="center">🤖 Artificial Intelligence Spring 2025</h1>
<h3 align="center">Core AI Algorithms & Implementation | Sharif University of Technology</h3>

[**GitHub**](https://github.com/javdaninasim/AI_PHW_Spring_2025) &nbsp; ⬩ &nbsp; [**University**](https://sharif.edu/)

</div>

---

### 📚 Course Blueprint

```python
class ArtificialIntelligence_Spring_2025:
    def __init__(self):
        self.institution = "Sharif University of Technology"
        self.course_code = "CE 40417"
        self.instructor = "Dr. Mohammad Hossein Rohban"
        self.semester = "Spring 2025"
        self.format = "Interactive Jupyter Notebooks"
        
    def core_topics(self):
        return [
            "🔍 Constraint Satisfaction & Backtracking",
            "🎯 Adversarial Search & Game Theory",
            "🔗 Probabilistic Models (HMMs, Bayesian Networks)",
            "🧠 Neural Networks & Deep Learning",
            "📊 Machine Learning & Classification",
            "🤖 Reinforcement Learning & Decision Making"
        ]
    
    def philosophy(self):
        return "Implement algorithms from scratch. Understand the 'why' before the 'how'."
```

---

### 📂 Repository Structure & Content

#### **1. 🔍 Constraint Satisfaction Problems (CSP)**
📁 **Folder:** `CSP/`  
📓 **Notebook:** `CSP.ipynb` (69.7 KB)

Core implementation of constraint satisfaction with:
- **Backtracking algorithms** with pruning strategies
- **Variable selection heuristics** (MRV, Degree heuristic)
- **Arc Consistency (AC-3)** for constraint propagation
- **Classic problems:** N-Queens puzzle, map coloring, scheduling
- **Complexity analysis** and performance benchmarks

**Key Algorithms:** Depth-First Search with constraints, forward checking, MRV heuristic

---

#### **2. 🎯 Minimax & Adversarial Search**
📁 **Folder:** `Minimax/`  
📓 **Notebook:** `Minimax.ipynb` (35.5 KB)

Game-playing agents and two-player strategic reasoning:
- **Minimax algorithm** with game-tree evaluation
- **Alpha-Beta pruning** for computational efficiency
- **Evaluation functions** for incomplete searches
- **Classic games:** Tic-Tac-Toe, Connect Four
- **Adversarial reasoning** under uncertainty

**Key Algorithms:** Minimax, Alpha-Beta pruning, iterative deepening

---

#### **3. 🔗 Hidden Markov Models (HMM)**
📁 **Folder:** `HiddenMarkovModel/`  
📓 **Notebook:** `HiddenMarkovModel.ipynb` (22.9 KB)

Probabilistic inference over sequences:
- **Forward algorithm** for likelihood computation
- **Viterbi algorithm** for maximum-likelihood decoding
- **Baum-Welch algorithm** for parameter learning
- **Applications:** Speech recognition, sequence tagging, weather prediction
- **Filtering vs. Smoothing** vs. Most likely explanation

**Key Algorithms:** Forward pass, Viterbi decoding, Baum-Welch EM algorithm

---

#### **4. 🧠 Neural Networks & Deep Learning**
📁 **Folder:** `NeuralNetworks/`  
📓 **Notebook:** `NeuralNetwork.ipynb` (188.2 KB)

Comprehensive neural network implementation:
- **Multilayer Perceptrons (MLPs)** from scratch
- **Backpropagation algorithm** with gradient computation
- **Activation functions:** ReLU, Sigmoid, Tanh
- **Regularization techniques:** L1/L2, Dropout
- **Modern frameworks:** PyTorch and TensorFlow integration
- **Visualization:** Loss curves, weight matrices, decision boundaries
- **Advanced topics:** Batch normalization, learning rate scheduling

**Key Concepts:** Forward propagation, backpropagation, gradient descent, optimization

---

#### **5. 📊 Machine Learning & Classification**
📁 **Folder:** `MachineLearning&Classification/`  
📓 **Notebook:** `MachineLearning&Classification.ipynb` (384.3 KB) ⭐ **Largest notebook**

Comprehensive supervised learning pipeline:
- **k-Nearest Neighbors (kNN)** – Distance metrics, complexity analysis
- **Decision Trees** – Information gain, entropy, pruning
- **Naive Bayes** – Probabilistic classification, feature independence
- **Model evaluation:** Precision, Recall, F1-score, Confusion matrix
- **Cross-validation** and hyperparameter tuning
- **Real datasets:** Classification benchmarks with detailed analysis
- **Comparison study** across different algorithms

**Key Concepts:** Feature engineering, model selection, evaluation metrics, overfitting

---

#### **6. 🤖 Bayesian Networks & Robot Navigation**
📁 **Folder:** `ModelingRobotNavigationUsingBayesianNetwork_Spring/`  
📓 **Notebook:** `ModelingRobotNavigationUsingBayesianNetwork.ipynb` (123.1 KB)

Probabilistic inference and robot localization:
- **Bayesian Networks** – Structure, conditional independence
- **Variable Elimination** algorithm for exact inference
- **Belief propagation** in probabilistic graphical models
- **Robot navigation problem:** Sensor uncertainty, position tracking
- **Localization & mapping:** Handling noisy measurements
- **Inference queries:** Most likely explanation, filtering over time

**Key Concepts:** Joint probability, conditional independence, probabilistic inference

---

#### **7. 🎮 Reinforcement Learning**
📁 **Folder:** `ReinforcementLearning/`  
📓 **Notebook:** `ReinforcementLearning.ipynb` (1.4 MB) ⭐ **Largest & Most Comprehensive**

Advanced decision-making algorithms:
- **Markov Decision Processes (MDPs)** – State space, reward functions, policies
- **Value Iteration** – Dynamic programming for optimal policy computation
- **Policy Iteration** – Policy evaluation and improvement
- **Q-Learning** – Model-free learning from experience
- **SARSA** – On-policy temporal difference learning
- **Convergence analysis** – Theoretical guarantees and practical considerations
- **Complex environments:** Grid worlds, game playing, navigation tasks
- **Deep Q-Networks (DQN)** – Neural network function approximation
- **Exploration vs. Exploitation:** Epsilon-greedy, UCB strategies

**Key Concepts:** Bellman equations, temporal difference learning, policy optimization, function approximation

---

### ⚡ Technology Stack

<div align="left">
  <img src="https://img.shields.io/badge/Python-1A1A1A?style=for-the-badge&logo=python&logoColor=3776AB" alt="Python" />
  <img src="https://img.shields.io/badge/Jupyter-1A1A1A?style=for-the-badge&logo=jupyter&logoColor=F37726" alt="Jupyter" />
  <img src="https://img.shields.io/badge/NumPy-1A1A1A?style=for-the-badge&logo=numpy&logoColor=013243" alt="NumPy" />
  <img src="https://img.shields.io/badge/SciPy-1A1A1A?style=for-the-badge&logo=scipy&logoColor=8CAAE6" alt="SciPy" />
  <img src="https://img.shields.io/badge/PyTorch-1A1A1A?style=for-the-badge&logo=pytorch&logoColor=EE4C2C" alt="PyTorch" />
  <img src="https://img.shields.io/badge/TensorFlow-1A1A1A?style=for-the-badge&logo=tensorflow&logoColor=FF6F00" alt="TensorFlow" />
  <img src="https://img.shields.io/badge/scikit--learn-1A1A1A?style=for-the-badge&logo=scikit-learn&logoColor=F7931E" alt="scikit-learn" />
  <img src="https://img.shields.io/badge/Matplotlib-1A1A1A?style=for-the-badge&logo=python&logoColor=11557C" alt="Matplotlib" />
</div>

<br>

> **Core Dependencies:** `numpy` • `scipy` • `scikit-learn` • `torch` • `tensorflow` • `matplotlib` • `pandas` • `jupyter`

---

### 📈 Assignment Completion Status

| # | Algorithm | Topic | Size | Status |
|:---:|:---|:---|:---:|:---:|
| **1** | **CSP** | Constraint Satisfaction, Backtracking, Arc Consistency | 69.7 KB | ✅ Complete |
| **2** | **Minimax** | Game Theory, Adversarial Search, Alpha-Beta | 35.5 KB | ✅ Complete |
| **3** | **HMM** | Probabilistic Sequences, Viterbi, Baum-Welch | 22.9 KB | ✅ Complete |
| **4** | **Neural Networks** | MLPs, Backprop, PyTorch, TensorFlow | 188.2 KB | ✅ Complete |
| **5** | **ML & Classification** | kNN, Decision Trees, Naive Bayes, Evaluation | 384.3 KB | ✅ Complete |
| **6** | **Bayesian Networks** | Probabilistic Inference, Robot Localization | 123.1 KB | ✅ Complete |
| **7** | **Reinforcement Learning** | Q-Learning, SARSA, Policy Iteration, DQN | 1.4 MB | ✅ Complete |

---

### 🎓 Learning Outcomes

Upon completing these assignments, you will have:

✅ **Deep understanding** of classical AI algorithms and when to use them  
✅ **Practical experience** implementing algorithms from mathematical formulations  
✅ **Intuition** about algorithm trade-offs (time complexity, optimality, convergence)  
✅ **Hands-on skills** with machine learning frameworks (PyTorch, TensorFlow)  
✅ **Problem-solving abilities** in decision-making and reasoning under uncertainty  
✅ **Code optimization** techniques for performance-critical algorithms  
✅ **Ability to extend** these algorithms to novel domains and problems  

---

### ℹ️ Course Information

| Aspect | Details |
|:---|:---|
| **Institution** | Sharif University of Technology, Dept. of Computer Engineering |
| **Course Code** | CE 40417 |
| **Instructor** | Dr. Mohammad Hossein Rohban |
| **Semester** | Spring 2025 (Farvardin–Ordibehesht 1404) |
| **Prerequisites** | Data Structures, Discrete Mathematics, Linear Algebra, Probability |
| **Format** | Lectures + Programming Assignments (Jupyter Notebooks) |
| **Assessment** | Implementation quality, correctness, analysis, and insights |

---

### 💡 Key Insights & Takeaways

| Topic | Key Insight | Practical Impact |
|:---|:---|:---|
| **CSP** | Constraint propagation reduces search space exponentially | Scheduling, configuration, puzzle solving |
| **Game Theory** | Pruning dramatically improves minimax efficiency without loss of optimality | Real-time game AI, strategic planning |
| **HMM** | Forward-backward passes decouple inference from model structure | Speech recognition, sequence tagging, forecasting |
| **Neural Networks** | Gradient-based learning discovers powerful feature hierarchies | Computer vision, NLP, signal processing |
| **ML Classification** | Algorithm choice matters less than feature engineering | Production ML systems, data quality first |
| **Bayesian Networks** | Conditional independence enables tractable inference in complex domains | Medical diagnosis, sensor fusion, robotics |
| **RL** | Temporal difference learning balances bootstrapping and full returns | Autonomous control, game AI, optimization |
<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=FF0000&height=100&section=footer" width="100%"/>
</div>
