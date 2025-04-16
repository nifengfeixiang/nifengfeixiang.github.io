---
title: "CARE: Compatibility-Aware Incentive Mechanisms for Federated Learning with Budgeted Requesters"
collection: publications
category: conferences
permalink: /publication/2025-CARE: Compatibility-Aware Incentive Mechanisms for Federated Learning with Budgeted Requesters
excerpt: 'In this paper, we investigate the scenario in FL where multiple budgeted requesters seek training services from incompatible workers with private training costs.'
date: 2025-05-18
venue: 'IEEE International Conference on Computer Communications (INFOCOM-2025)'
# paperurl: 'http://nifengfeixiang.github.io/files/Budget-Feasible_Mechanisms_in_Two-Sided_Crowdsensing_Markets_Truthfulness_Fairness_and_Efficiency.pdf'
# citation: 'Liu, Xiang, et al. "Budget-feasible mechanisms in two-sided crowdsensing markets: Truthfulness, fairness, and efficiency." IEEE Transactions on Mobile Computing (2022).'
---

Federated learning (FL) is a promising approach that allows requesters (e.g., servers) to obtain local training models from workers (e.g., clients). Since workers are typically unwilling to provide training services/models freely and voluntarily, many incentive mechanisms in FL are designed to incentivize participation by offering monetary rewards from requesters. However, existing studies neglect two crucial aspects of real-world FL scenarios. First, workers can possess inherent incompatibility characteristics (e.g., communication channels and data sources), which can lead to degradation of FL efficiency (e.g., low communication efficiency and poor model generalization). Second, the requesters are budgeted, which limits the amount of workers they can hire for their tasks. In this paper, we investigate the scenario in FL where multiple budgeted requesters seek training services from incompatible workers with private training costs. We consider two settings: the cooperative budget setting where requesters cooperate to pool their budgets to improve their overall utility and the non-cooperative budget setting where each requester optimizes their utility within their own budgets. To address efficiency degradation caused by worker incompatibility, we develop novel compatibility-aware incentive mechanisms, CARE-CO and CARE-NO, for both settings to elicit true private costs and determine workers to hire for requesters and their rewards while satisfying requester budget constraints. Our mechanisms guarantee individual rationality, truthfulness, budget feasibility, and approximation performance. We conduct extensive experiments using real-world datasets to show that the proposed mechanisms significantly outperform existing baselines.

[Download paper here](http://nifengfeixiang.github.io/files/INFOCOM25_Compatibility_Aware_Incentive_Mechanisms_for_Federated_Learning_with_Budgeted_Requesters.pdf)

<!-- Recommended citation: Liu, X., Chan, H., Li, M., Wu, W., & Zhao, Y. (2023). Budget-feasible Mechanisms for Proportionally Selecting Agents from Groups. Artificial Intelligence, 103975. -->