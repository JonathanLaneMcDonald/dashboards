# RL Dashboards

This repository hosts reinforcement learning dashboards for a custom implementation of Gumbel AlphaZero that I'm applying to 9x9 Gomoku with SGD (I'm experimenting with optimisers).

---

## Training Progress

**Self-Play Elo**  
![Self-Play Elo](plots/elo_vs_states.png)

**Training Metrics**  
![Training Metrics](plots/training_metrics.png)

---

## Game Metrics

**Game Length**  
![Game Length](plots/game_length.png)

**Game Outcome**  
![Game Outcome](plots/avg_outcome.png)

**Variety in Self-Play**  
![Game Variation](plots/unique_plies.png)

**Stone Mass (in Concentric Rings)**
![Concentric Rings](plots/ring_utilisation.png)

---

## Opening Move

**Opening Move by Symmetry Group**
![Symmetry Groups](plots/symmetry_groups.png)

**Opening Moves in Most Common Symmetry Group**
![Game Opening Symmetry Groups](plots/symmetry_discovery.png)

**Opening Moves Played in Concentric Rings**  
![Concentric Rings](plots/ring_utilisation_for_opening_move.png)

---

## More on Symmetry

**Duplication in n-Ply Game-Opening Sequences**  
![Game Opening Duplication](plots/duplication_awareness.png)

**Ratio of Symmetries in Opening Sequences**
![Game Opening Duplication](plots/symmetry_awareness.png)

---

## Model Evaluation

**Performance in Evaluation Games**  
![Evaluation](plots/evaluation_games.png)

**Parameter Updates**  
![Parameter Updates](plots/param_updates.png)

**Policy Entropy**  
![Policy Entropy](plots/policy_entropy.png)

---

## Performance

**Pipeline Performance**  
![Pipeline Performance](plots/pipeline_performance.png)

---

_All plots are automatically updated as training progresses._
