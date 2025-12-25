# ML-Decision-Tree-Visualization

Visualizing Decision Trees

The tree.plot_tree(clf, filled=True) function from scikit-learn is used to visualize a trained Decision Tree model.
It displays the tree structure showing feature splits, threshold values, impurity (Gini/Entropy), sample counts, and class predictions, while the filled=True option colors the nodes based on the majority class, making the decision process easier to interpret.

Decision Tree Visualiation Techniques used:

**1.tree.export_text**

**2.tree.plot_tree**

**3.tree.export_graphviz**

**4.dtreeviz**
---
Cost-Complexity Pruning (ccp_alpha)

ccp_alpha is a regularization parameter used to prune decision trees and prevent overfitting.
Higher values of ccp_alpha result in a simpler tree with fewer nodes, improving generalization by removing branches that add little predictive power.
---

**Cancer DATASET:**

**Cost Complexity Pruning done** on cancer datset to find out the best ccp alhpha value and max_depth:


![image](https://user-images.githubusercontent.com/68188457/118977750-2317e900-b994-11eb-9047-cf0caa45c981.png)


So , ccp_alpha = 0.03 is slected for training the model


![image](https://user-images.githubusercontent.com/68188457/118977904-4fcc0080-b994-11eb-83bc-7e4b0dcf466b.png)


This avoides overfitting and now model is having low bias and low Variance.
---
