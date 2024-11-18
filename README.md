# BMI500-HW11
Shoibolina Kaushik (shoibolina.kaushik@emory.edu)

Question 1

## Key Insights
1. SIR model captures the basic infection dynamics however, it is less realistic, as there is no exposed compartment. The SEIR model introduces an incubation period, thus leading to smoother infection curves and, under certain conditions, the possibility of multi-wave patterns.
2. The basic reproductive number plays a fundamental role in infection spread and control. Effective interventions targeting β (e.g., social distancing) or increasing γ (e.g., medical care) may decrease infection curves. Sensitivity analysis underlines that the transmission β has a larger impact on infection peaks and totals than the exposed-to-infectious rate σ.
3. Birth and death rates significantly impact long-term infection waves, where higher birth rates would replenish the susceptible population and sustain the waves over time.

## Comparative model performance
1. SIR Model: Simpler and computationally efficient for short-term predictions.
   The infection spread pattern in this model is not as realistic, since it doesn't consider any incubation delay.

2. SEIR Model: More realistic in real-world scenarios, considering exposed individuals and births/deaths.
Capable of modeling multi-wave pandemics; hence, suitable for long-term simulations.
Computationally heavier because of the additional compartment and parameters.


## Relevance to model-based machine learning
1. Both SIR and SEIR models are dependent on parameter tuning: β,γ,σ,μ, which aligns with machine learning optimization techniques.
2. Machine learning techniques can be applied in order to learn parameter values from real-world data that improve predictive power for compartmental models (model generalisation).
3. Similar to feature importance in machine learning, sensitivity analysis help identify key parameters-for example, β-on which to target public health interventions.

## Suggestions for future modeling improvements
1. Add compartments for vaccination or asymptomatic carriers and incorporate seasonality and time-varying transmission rates to reflect more realistic dynamics.
2. Mechanistic models, like SIR/SEIR combined with machine learning, do a better job of prediction by capturing real-world data patterns.
3. Add stochastic modeling or Bayesian approaches to account for uncertainty in parameter estimates and predictions.
4. Extend models to simulate the impact of specific interventions-such as lockdowns and vaccination campaigns-to inform decision-making.
5. Model interactions between several regions or demographic groups, which will help capture heterogeneous transmission dynamics.




All the parts and subparts of Question 1 are answered in 'BMI 500 HW 11.ipynb'

Disclaimer: No generative AI (in any form) has been used to complete this homework.
