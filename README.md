📒 MACHINE LEARNING – MATH QUICK NOTES

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
LINEAR ALGEBRA
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
• Vector: x ∈ ℝⁿ
• Matrix: X ∈ ℝⁿˣᵈ
• Dot product: a · b = aᵀb
• Eigenvalue: Av = λv
• Positive Definite: xᵀAx > 0

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
PROBABILITY
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
• Mean (μ) = E[X]
• Variance = E[(X − μ)²]
• Std = √Variance
• Bayes Theorem:
  P(A|B) = P(B|A)P(A) / P(B)
• Independent:
  P(A ∩ B) = P(A)P(B)

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
NORMAL DISTRIBUTION
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
• X ~ N(μ, σ²)
• 68% → μ ± σ
• 95% → μ ± 2σ
• 99.7% → μ ± 3σ

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
CALCULUS
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
• d/dx (x²) = 2x
• Gradient: ∇f(w)
• Chain Rule used in backprop
• d/dx (log x) = 1/x

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
SIGMOID
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
σ(x) = 1 / (1 + e⁻ˣ)
σ′(x) = σ(x)(1 − σ(x))

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
LOSS FUNCTIONS
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
• MSE = (y − ŷ)²
• Log Loss:
  −[y log(p) + (1−y) log(1−p)]

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
GRADIENT DESCENT
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
w = w − α ∇L
• α too large → diverge
• α too small → slow learning

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
WHY LOG LOSS?
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
• Penalizes confident wrong predictions
• Works with probabilities
• Convex for logistic regression
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
