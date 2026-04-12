# 课程安排与实验教学方案

## 一、课程周次安排

| 周次 | 教学主题 | 说明 |
|---|---|---|
| 第一周 | 绪论 | 介绍课程 |
| 第二周 | 数据治理 | 讲授 3 学时，1 学时课程翻转，学生讲 LDA |
| 第三周 | 数据预处理 | 实验 1 周 |
| 第四周 | 分类 | 讲授 3 学时，1 学时课程翻转，学生讲 Softmax |
| 第五周 | 分类 | 实验 1 周 |
| 第六周 | 集成学习 | 讲授 3 学时，1 学时课程翻转，学生讲 GBDT |
| 第七周 | 集成学习 | 实验 1 周 |
| 第八周 | 课堂翻转 | 逻辑回归、岭回归、LASSO、双聚类、麻雀算法、朴素贝叶斯、CART、MCMC |
| 第九周 | 聚类 | 讲授 3 学时，1 学时课程翻转，学生讲自组织映射 |
| 第十周 | 聚类 | 实验 1 周 |
| 第十一周 | 群智能 | 讲授 3 学时，1 学时课程翻转，学生讲蜻蜓算法 |
| 第十二周 | 群智能 | 实验 1 周 |
| 第十三周 | 强化学习 | 讲授 3 学时，1 学时课程翻转，学生讲 DQN |
| 第十四周 | 提示学习 | 讲授 2 学时，2 学时实验 |
| 第十五周 | 结课汇报 | 学生讲项目 |

---

## 二、Pipeline 1 - Data Preprocessing

### 1. Spider Experiment (HYR)

| 编号 | 内容 | 说明 |
|---|---|---|
| 1.1 | Bazhuayu Test | Retrieve specific webpage |
| 1.2 | Introduction of Scrapy | PPT |
| 1.3 | Experiment Environment Configuration | VS Code、Python、Scrapy、其他依赖安装 |
| 1.4 | Scrapy Coding | 完整爬虫项目开发流程 |

#### 1.3 Experiment Environment Configuration
- VS Code（Downloading, Setup, Add-ins）
- Python（Downloading, Setup）
- Scrapy（pip）
- Other dependencies（pip）

#### 1.4 Scrapy Coding
- How to start a Scrapy project
- How to find useful information from webpage (HTML & CSS)
- How to extract useful information from webpage (Template)
- How to set up validation webpage (RegEx)
- How to persistent spider results (Excel)
- How to run a Scrapy project

### 2. Feature Selection

| 编号 | 内容 | 说明 |
|---|---|---|
| 2.1 | Experiment Environment Configuration | pip |
| 2.2 | Dataset Introduction | iris |
| 2.3 | SFFS etc. | 2D-Scatter chart |
| 2.4 | Anova Introduction | 2D-Scatter chart & Boxplot |
| 2.5 | Classification Result Comparison | acc、Training cost、prediction cost 对比 |

### 3. Feature Extraction

| 编号 | 内容 | 说明 |
|---|---|---|
| 3.1 | Experiment Environment Configuration | pip |
| 3.2 | Dataset Introduction | iris |
| 3.3 | LDA Introduction | Linear Discriminant Analysis, 2D-Scatter chart |
| 3.4 | PCA Introduction | 2D-Scatter chart |
| 3.5 | Classification Result Comparison | acc、Training cost、prediction cost 对比 |

---

## 三、Pipeline 2 – Classification & Regression

### 1. SVM Experiment (CC)

| 编号 | 内容 |
|---|---|
| 1.1 | Brief Introduction of SVM |
| 1.2 | Brief Introduction of scikit-learn (PPT) |
| 1.3 | SVM for Classification with cross validation (iris, Decision surface plot) |
| 1.4 | SVM for Classification with feature selection and extraction (iris, Decision surface plot) |
| 1.5 | SVM with different kernels and grid searching |
| 1.6 | SVR for Regression (boston, scatter curve plot) |
| 1.7* | Explore SVR with feature selection, feature extraction, different kernels and grid searching (boston, scatter curve plot) |

### 2. ANN Experiment (DXD)

| 编号 | 内容 |
|---|---|
| 2.1 | Brief Introduction of ANN with sklearn |
| 2.2 | ANN for Classification with cross validation (iris, ROC curve plot) |
| 2.3 | ANN for Classification with feature selection and extraction (iris, ROC curve plot) |
| 2.4 | ANN with different Activation Functions, output layers and learning models |
| 2.5 | ANN for Regression (boston, scatter curve plot) |
| 2.6* | Explore ANN with feature selection, feature extraction, different Activation Functions, output layers and learning models (boston, scatter curve plot) |

---

## 四、Pipeline 3 – Ensemble Learning

### 1. Random Forest Experiment (CC)

| 编号 | 内容 |
|---|---|
| 1.1 | Brief Introduction of RF (main idea & parameters) |
| 1.2 | RF for Classification with cross validation (iris, Decision surface plot) |
| 1.3 | List the most important top-10 features by RF and introduce the selection strategy |
| 1.4 | RF for Regression (boston, scatter curve plot) |
| 1.5* | Explore RF with different parameters (boston, scatter curve plot) |

### 2. XGBoost Experiment (ZJC)

| 编号 | 内容 |
|---|---|
| 2.1 | Brief Introduction of XGBoost (main idea & parameters) |
| 2.2 | XGBoost for Classification with cross validation (iris, ROC curve plot) |
| 2.3 | List the top-10 features by XGBoost and introduce the selection strategy |
| 2.4 | XGBoost for Regression (boston, scatter curve plot) |
| 2.5* | Explore XGBoost with different parameters (boston, scatter curve plot) |

### 3. Kaggle Experiment (DXD)

| 编号 | 内容 |
|---|---|
| 3.1 | Brief Introduction of Kaggle |
| 3.2 | How to Register a team on Kaggle |
| 3.3 | How to use the dataset from Kaggle |
| 3.4 | How to submit Ur Results or Codes to Kaggle |
| 3.5 | How to check Ur rank |

---

## 五、Pipeline 4 – Clustering

### 1. K-means Clustering Experiment (ZJC)

| 编号 | 内容 |
|---|---|
| 1.1 | Brief Introduction of K-means (main idea & parameters) |
| 1.2 | K-means for clustering with visualization (iris, scatter plot by PCA each iter, mark the center) |
| 1.3 | Explore K-means with different parameters (K, iters, assessed by DBI) |

### 2. Affinity Propagation Clustering Experiment (ZJC)

| 编号 | 内容 |
|---|---|
| 2.1 | Brief Introduction of AP (main idea & parameters) |
| 2.2 | AP for clustering with visualization (iris, scatter plot by t-SNE each iter, mark the center) |
| 2.3 | Explore AP with different parameters (p, iters, assessed by DBI with KM) |

### 3. DBSCAN Experiment (LSH)

| 编号 | 内容 |
|---|---|
| 3.1 | Brief Introduction of DBSCAN (main idea & parameters) |
| 3.2 | DBSCAN for clustering with visualization (iris, scatter plot by PCA, mark the core) |
| 3.3 | Explore DBSCAN with different parameters (min_samples and eps, assessed by DBI with KM) |

### 4. Agglomerative Clustering Experiment (WH)

| 编号 | 内容 |
|---|---|
| 4.1 | Brief Introduction of Agglomerative (main idea & parameters) |
| 4.2 | Agglomerative for clustering with visualization (iris, tree plot by t-SNE each iter) |
| 4.3 | Explore Agglomerative with different parameters (linkage, assessed by DBI with KM) |

---

## 六、Pipeline 5 – Optimization

### 1. Particle Swarm Optimization Experiment (CC)

| 编号 | 内容 |
|---|---|
| 1.1 | Brief Introduction of PSO (main idea & parameters) |
| 1.2 | PSO for House price prediction with feature selection & parameter optimization (curve plot each iter, compare results before optimization) |
| 1.3 | Explore PSO with different parameters (iters, weights) |

### 2. Genetic Algorithm Experiment (CC & HYR)

| 编号 | 内容 |
|---|---|
| 2.1 | Brief Introduction of GA (main idea & parameters) |
| 2.2 | GA for House price prediction with feature selection & parameter optimization (curve plot each iter, compare results before optimization and PSO) |
| 2.3 | GA for TSP (curve plot each iter, visualization of best solution) |
| 2.4 | Explore GA with different parameters (iters, different selector, crossover) |

### 3. PPO Experiment (ZJC)

| 编号 | 内容 |
|---|---|
| 3.1 | Brief Introduction of Reinforcement Learning and PPO (main idea & parameters) |
| 3.2 | PPO for TSP (curve plot each iter, visualization of best solution, comparison with GA) |
| 3.3 | Explore PPO with different parameters |

---
