# Assignment 1
### Part I: 馬可夫決策過程 (MDP)

* **檔案**: `PartI_MDP.ipynb`, `MDP.py`
* **內容**: 實作了 MDP 的基礎求解演算法，包含：
    * 價值迭代 (Value Iteration)
    * 策略迭代 (Policy Iteration)
    * 改進版策略迭代 (Modified Policy Iteration)
  
### Part II: Q-Learning

* **檔案**: `PartII_RL.ipynb`
* **內容**: 在一個迷宮環境 (Maze) 中實作了 Q-Learning 演算法，並探討了不同 `epsilon` (探索率) 數值對學習成果的影響。

### Part III: 深度 Q 網路 (Deep Q-Network, DQN)

* **檔案**: `PartIII_DQN.ipynb`
* **內容**: 實作了 DQN 演算法來解決 OpenAI Gym 中的「CartPole-v0」環境。此部分深入分析了兩個關鍵超參數的影響：
    1.  **目標網路更新頻率 (Target Network Update Frequency)**
    2.  **經驗回放的批次大小 (Minibatch Size)**
 
### 套件:
`numpy`, `matplotlib`, `torch`, `gym`, `tqdm`
