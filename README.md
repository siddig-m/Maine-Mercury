# Project Examining Mercury Levels in Maine's Lakes

## Executive Summary

In this project, we explore the factors influencing mercury levels in fish in Maine's lakes. We address three key research questions using data from 120 lakes in Maine. First, we determine whether mercury levels in Maine's fish are of concern based on various thresholds. Second, we investigate whether the presence of dams or other human infrastructure affects mercury content in fish. Finally, we examine whether mercury levels vary among different lake types: oligotrophic, mesotrophic, or eutrophic.

To answer these questions, we employ statistical methods, including one-sample t-tests, two-sided t-tests, and an ANOVA test. The results provide valuable insights into the state of mercury levels in Maine's fish and can inform policy decisions and actions.

## Introduction

Maine's lakes and ponds play a significant role in the state's lifestyle, making it crucial to ensure their health and maintenance. Mercury accumulation in fish is a common issue in these bodies of water, resulting from various factors in the food chain. This study analyzes key variables that may affect mercury levels in fish using data collected from 120 lakes in Maine.

## Methods

We use three methods to address the research questions:

1. **Assessing Mercury Concern:** We compare the average mercury levels in fish to thresholds set by policymakers, such as the U.S. FDA, the State of Maine, and other states. One-sample t-tests are employed to determine if the average levels are significantly higher than these thresholds.

2. **Effects of Dams:** We examine whether the presence of a dam or human infrastructure leads to higher mercury levels in fish. A two-sided t-test is used to compare average mercury levels in lakes with and without dams.

3. **Variation by Lake Type:** To assess if mercury levels vary by lake type, we utilize an Analysis of Variance (ANOVA) test to compare means across oligotrophic, mesotrophic, and eutrophic lakes.

## Results

- The analysis suggests concern regarding mercury levels in fish in Maine, with approximately half of the lakes exceeding the State of Maine's threshold of 0.43 ppm.
- Lakes near dams do not exhibit significantly higher mercury levels in fish compared to lakes without dams.
- There is no significant difference in mercury levels among different lake types (oligotrophic, mesotrophic, eutrophic).
<div style="display: flex; align-items: center;">
  <!-- Mercury Levels Histogram -->
  <div style="flex: 1; margin-right: 10px;">
    <img src="https://github.com/siddig-m/Maine-Mercury/assets/55728795/6203df13-5c9a-4520-a847-37aaacabd6de" width="400" height="300">
    <p style="text-align: center;">Mercury Levels Histogram</p>
  </div>

  <!-- Mercury Levels Near Dams (Box Plot) -->
  <div style="flex: 1; margin-right: 10px;">
    <img src="https://github.com/siddig-m/Maine-Mercury/assets/55728795/604edf1b-e455-4102-9ff3-01254e914c48" width="400" height="300">
    <p style="text-align: center;">Mercury Levels Near Dams (Box Plot)</p>
  </div>

  <!-- Mercury Levels by Lake Type (Box Plots) -->
  <div style="flex: 1;">
    <img src="https://github.com/siddig-m/Maine-Mercury/assets/55728795/80d7a3a4-33d5-430a-8ebf-c1169537cb84" width="400" height="300">
    <p style="text-align: center;">Mercury Levels by Lake Type (Box Plots)</p>
  </div>
</div>

## Discussion

While the results are informative, several limitations should be considered, including the normality assumption of the data and the assumption of independence among lakes. Sampling size variations could also impact the results.

## Conclusion

In conclusion, the data suggests some concern regarding mercury levels in Maine's lakes, especially when compared to the State of Maine's threshold of 0.43 ppm. However, further investigation is needed to assess long-term risks for lakes exceeding the 0.50 and 1.00 ppm thresholds. The presence of dams does not appear to significantly impact mercury levels in fish. Lastly, lake types are not a significant indicator of higher mercury levels.

Future steps may involve gathering more data to confirm and expand upon these findings and exploring other variables that may contribute to elevated mercury levels in fish.

---

This README provides an overview of the project's objectives, methodology, results, and implications. For more detailed information and code related to the analysis, please refer to the project's documentation and files.

