<h1 align="center">Hi 👋, I'm Paweł Wypych</h1>
<h3 align="center">Data Science MSc student specializing in Machine Learning, Algorithms, and data-driven systems.</h3>
<br><br>

## Featured Projects
### ♠️ Poker Adaptive Opponent Model ♠️

**Problem:**  
Static poker policies may perform well against one playing style but fail against another. This project investigates whether online opponent classification and switching between specialized reinforcement-learning policies improves performance over a fixed general policy in heads-up Texas Hold'em.

**Approach:**  
- Built an experimental framework on top of PyPokerEngine
- Implemented tabular Monte Carlo, Q-learning, SARSA and Double Q-learning
- Trained one general policy and specialists for tight, aggressive and calling opponents
- Developed an adaptive agent that classifies opponents during play and selects an appropriate specialist policy
- Compared adaptive agents with fixed general policies, family-informed Oracle agents and simple sanity baselines
- Evaluated training opponents, unseen variants, stress-test strategies and learned agents in cross-play
- Created a frozen, multi-seed protocol using paired evaluations and seed-level confidence intervals
- Implemented a fail-fast, resumable pipeline for training, evaluation, validation and automatic report generation
- Added classifier-quality, seed-stability and learning-curve diagnostics

**Tech Stack:**  
Python, NumPy, Pandas, SciPy, PyPokerEngine, Matplotlib, pytest, Ruff

**Current Status and Preliminary Findings:**  
- The complete verification pipeline finished successfully, executing all 33 training, evaluation and reporting stages
- Q-learning achieved the strongest preliminary average performance among adaptive agents
- The classifier is highly accurate when it identifies an opponent, although coverage is lower against aggressive variants
- Adaptive agents generally remain close to the family-informed Oracle, suggesting that policy quality is a larger limitation than switching cost
- Verification has not yet established a broad statistically significant advantage of adaptation over fixed general policies
- Diagnostic experiments identified benchmark limitations, including vulnerability to `always_raise`, saturated results against tight opponents and positional asymmetry in the poker engine
- Final conclusions will be based on the frozen 10,000-episode, five-seed experiment

🔗 [View Project](https://github.com/pawel00wypych/poker-adaptive-opponent-model)
<br><br>

## Algorithmic problems
<p align="left">
  <a href="https://leetcode.com/u/pawel00wypych/" target="_blank">
    <img src="https://leetcard.jacoblin.cool/pawel00wypych?theme=dark&font=Inter" height="150" alt="LeetCode Stats" />
  </a>
  <a href="https://github.com/pawel00wypych/neetcode-submissions-pawel00wypych">
    <img width="338" height="294" alt="image" src="https://github.com/user-attachments/assets/1ec2195f-15e4-405c-b6bc-99f9cfa998a2" />
  </a>
</p>
<br><br>

## Languages and Tools
<table>
  <tr>
    <td align="center"><strong>Languages</strong><br><br>
      <a href="https://www.python.org" target="_blank">
        <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg" width="40"/>
      </a>
      <a href="https://www.java.com" target="_blank">
        <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/java/java-original.svg" width="40"/>
      </a>
    </td>
    <td align="center"><strong>Data & ML</strong><br><br>
      <a href="https://pandas.pydata.org/" target="_blank">
        <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/pandas/pandas-original.svg" width="40"/>
      </a>
      <a href="https://scikit-learn.org/" target="_blank">
        <img src="https://upload.wikimedia.org/wikipedia/commons/0/05/Scikit_learn_logo_small.svg" width="40"/>
      </a>
    </td>
    <td align="center"><strong>Databases</strong><br><br>
      <a href="https://www.postgresql.org" target="_blank">
        <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/postgresql/postgresql-original-wordmark.svg" width="40"/>
      </a>
    </td>
  </tr>
  <tr>
    <td align="center"><strong>DevOps</strong><br><br>
      <a href="https://www.docker.com/" target="_blank">
        <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/docker/docker-original-wordmark.svg" width="40"/>
      </a>
      <a href="https://www.linux.org/" target="_blank">
        <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/linux/linux-original.svg" width="40"/>
      </a>
    </td>
    <td align="center"><strong>Frontend</strong><br><br>
      <a href="https://reactjs.org/" target="_blank">
        <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/react/react-original-wordmark.svg" width="40"/>
      </a>
      <a href="https://www.w3.org/html/" target="_blank">
        <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/html5/html5-original-wordmark.svg" width="40"/>
      </a>
      <a href="https://www.w3schools.com/css/" target="_blank">
        <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/css3/css3-original-wordmark.svg" width="40"/>
      </a>
    </td>
  </tr>
</table>
<br><br>

## Education

- 🎓 MSc in Data Science (2025 – present)  
  Cracow University of Technology

- 🎓 BSc in Computer Science (2020 – 2024)  
  Cracow University of Technology
<br><br>

## Connect with me
<p align="left">
<a href="https://linkedin.com/in/wypych-pawel" target="blank">
  <img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/linked-in-alt.svg" alt="www.linkedin.com/in/wypych-pawel" height="60" width="70" /></a>
</p>
