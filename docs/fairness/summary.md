# Summary

<table class="tg">
<thead>
  <tr>
    <th class="tg-c3ow">Tool</th>
    <th class="tg-c3ow">Setup</th>
    <th class="tg-c3ow">Open source user license</th>
    <th class="tg-c3ow">Release date</th>
    <th class="tg-c3ow">Organization</th>
    <th class="tg-c3ow">Open for anyone to contribute code?</th>
    <th class="tg-c3ow">Models covered</th>
    <th class="tg-c3ow"></th>
    <th class="tg-c3ow"></th>
    <th class="tg-c3ow"></th>
    <th class="tg-c3ow">Group fairness</th>
    <th class="tg-c3ow"></th>
    <th class="tg-c3ow"></th>
    <th class="tg-c3ow"></th>
    <th class="tg-c3ow"></th>
    <th class="tg-c3ow"></th>
    <th class="tg-c3ow">Individual fairness</th>
    <th class="tg-c3ow"></th>
    <th class="tg-c3ow">Other fairness metrics</th>
    <th class="tg-c3ow">Mitigation</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-0pky">Regression</td>
    <td class="tg-0pky">Classification   (binaryoutcome)</td>
    <td class="tg-0pky">Multi-class   outcome</td>
    <td class="tg-0pky">Handles   multi-class protected feature?</td>
    <td class="tg-0pky">Demographic   parity (statistical parity)</td>
    <td class="tg-0pky">Equal   opportunity / True positive parity / false positive error rate balance</td>
    <td class="tg-0pky">Equal odds   (True positive and false positive parity)</td>
    <td class="tg-0pky">Disparate   impact</td>
    <td class="tg-0pky">Discovery   rate</td>
    <td class="tg-0pky">Omission   rate</td>
    <td class="tg-0pky">Counterfactual   fairness</td>
    <td class="tg-0pky">Sample   distortion metrics</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
  </tr>
  <tr>
    <td class="tg-0pky">Scikit-fairness   / scikit-lego</td>
    <td class="tg-0pky">python (sklearn)</td>
    <td class="tg-0pky">MIT</td>
    <td class="tg-0pky">2019-03-31</td>
    <td class="tg-0pky">N/A</td>
    <td class="tg-0pky">✓</td>
    <td class="tg-0pky">✓</td>
    <td class="tg-0pky">✓</td>
    <td class="tg-0pky">X</td>
    <td class="tg-0pky">X</td>
    <td class="tg-0pky">✓</td>
    <td class="tg-0pky">✓</td>
    <td class="tg-0pky">X</td>
    <td class="tg-0pky">X</td>
    <td class="tg-0pky">X</td>
    <td class="tg-0pky">X</td>
    <td class="tg-0pky">X</td>
    <td class="tg-0pky">X</td>
    <td class="tg-0pky">N/A</td>
    <td class="tg-0pky">Pre-processing:   information filter</td>
  </tr>
  <tr>
    <td class="tg-0pky">IBM Fairness 360</td>
    <td class="tg-0pky">python   3.5+, R</td>
    <td class="tg-0pky">Apache 2.0</td>
    <td class="tg-0pky">2018-06-01</td>
    <td class="tg-0pky">IBM</td>
    <td class="tg-0pky">✓</td>
    <td class="tg-0pky">X</td>
    <td class="tg-0pky">✓</td>
    <td class="tg-0pky">✓</td>
    <td class="tg-0pky">✓</td>
    <td class="tg-0pky">✓</td>
    <td class="tg-0pky">✓</td>
    <td class="tg-0pky">✓</td>
    <td class="tg-0pky">✓</td>
    <td class="tg-0pky">✓</td>
    <td class="tg-0pky">✓</td>
    <td class="tg-0pky">X</td>
    <td class="tg-0pky">✓</td>
    <td class="tg-0pky">Generalized   Entropy Index<br>     Differential Fairness and Bias Amplification <br>     (full list here:   <a href="https://aif360.readthedocs.io/en/latest/modules/generated/aif360.metrics.ClassificationMetric.html"><span style="color:#905">https://aif360.readthedocs.io/en/latest/modules/generated/aif360.metrics.ClassificationMetric.html</span></a>)</td>
    <td class="tg-0pky">Optimized Preprocessing, Disparate Impact Remover, Equalized   Odds Post-processing, Reweighing, Reject Option Classification, Prejudice   Remover Regularizer, Calibrated Equalized Odds Postprocessing, Learning Fair   Representations, Adversarial Debiasing, Meta-Algorithm for Fair   Classification, Rich Subgroup Fairness</td>
  </tr>
  <tr>
    <td class="tg-0pky">Aequitas tool</td>
    <td class="tg-0pky">python   3.6+</td>
    <td class="tg-0pky">Custom</td>
    <td class="tg-0pky">2018-02-13</td>
    <td class="tg-0pky">UChicago</td>
    <td class="tg-0pky">✓</td>
    <td class="tg-0pky">X</td>
    <td class="tg-0pky">✓</td>
    <td class="tg-0pky">X</td>
    <td class="tg-0pky">✓</td>
    <td class="tg-0pky">✓</td>
    <td class="tg-0pky">✓</td>
    <td class="tg-0pky">✓</td>
    <td class="tg-0pky">X</td>
    <td class="tg-0pky">✓</td>
    <td class="tg-0pky">✓</td>
    <td class="tg-0pky">X</td>
    <td class="tg-0pky">X</td>
    <td class="tg-0pky">N/A</td>
    <td class="tg-0pky">N/A</td>
  </tr>
  <tr>
    <td class="tg-0pky">Google What-if tool</td>
    <td class="tg-0pky">Tensorboard   / Jupyter or Colab notebook</td>
    <td class="tg-0pky">Apache 2.0</td>
    <td class="tg-0pky">2018-09-11</td>
    <td class="tg-0pky">Google</td>
    <td class="tg-0pky">✓</td>
    <td class="tg-0pky">✓</td>
    <td class="tg-0pky">✓</td>
    <td class="tg-0pky">✓</td>
    <td class="tg-0pky">✓</td>
    <td class="tg-0pky">✓</td>
    <td class="tg-0pky">✓</td>
    <td class="tg-0pky">X</td>
    <td class="tg-0pky">X</td>
    <td class="tg-0pky">X</td>
    <td class="tg-0pky">X</td>
    <td class="tg-0pky">✓</td>
    <td class="tg-0pky">X</td>
    <td class="tg-0pky">Group   thresholds</td>
    <td class="tg-0pky">Threshold optimization based on fairness constraints</td>
  </tr>
  <tr>
    <td class="tg-0pky">PyMetrics audit-ai</td>
    <td class="tg-0pky">python</td>
    <td class="tg-0pky">MIT</td>
    <td class="tg-0pky">2018-05-18</td>
    <td class="tg-0pky">PyMetrics</td>
    <td class="tg-0pky">X</td>
    <td class="tg-0pky">✓</td>
    <td class="tg-0pky">✓</td>
    <td class="tg-0pky">X</td>
    <td class="tg-0pky">X</td>
    <td class="tg-0pky">X</td>
    <td class="tg-0pky">X</td>
    <td class="tg-0pky">X</td>
    <td class="tg-0pky">✓</td>
    <td class="tg-0pky">X</td>
    <td class="tg-0pky">X</td>
    <td class="tg-0pky">X</td>
    <td class="tg-0pky">X</td>
    <td class="tg-0pky">Statistical   tests to determine chance the disparity is due to random chance (ANOVA,   4/5th, fisher, z-test, bayes factor, chi squared<br>     sim beta ratio, classifier posterior_probabilities)</td>
    <td class="tg-0pky">N/A</td>
  </tr>
  <tr>
    <td class="tg-0pky">Fairlearn</td>
    <td class="tg-0pky">python</td>
    <td class="tg-0pky">MIT</td>
    <td class="tg-0pky">2018-05-15</td>
    <td class="tg-0pky">Microsoft</td>
    <td class="tg-0pky">✓</td>
    <td class="tg-0pky">✓</td>
    <td class="tg-0pky">✓</td>
    <td class="tg-0pky">X</td>
    <td class="tg-0pky">✓</td>
    <td class="tg-0pky">✓</td>
    <td class="tg-0pky">✓</td>
    <td class="tg-0pky">✓</td>
    <td class="tg-0pky">X</td>
    <td class="tg-0pky">X</td>
    <td class="tg-0pky">X</td>
    <td class="tg-0pky">X</td>
    <td class="tg-0pky">X</td>
    <td class="tg-0pky">Group   max / min /  summary</td>
    <td class="tg-0pky">Exponentiated Gradient, GridSearch, Threshold Optimizer</td>
  </tr>
</tbody>
</table>
