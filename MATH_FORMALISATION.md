# Grim’s Heart — Full Mathematical Formalisation  
Non-Closural Process Ontology  
David B. Grim (2025) — CC-BY 4.0  

## Core 2×2 State Matrix  
\[ G(t) = \begin{pmatrix} 
\text{Same} & \text{Diff} \\ 
\text{Form} & \text{Force} 
\end{pmatrix} 
= \begin{pmatrix} 
a(t) & b(t) \\ 
c(t) & d(t) 
\end{pmatrix} \]

Three nested registers (all share identical dynamics):  
- **Ontological**: Same – Diff – Form – Force  
- **Phenomenological**: Soul – Cut – World – Event  
- **Epistemic (shallow-δ)**: Rational – Subjective – Objective – Empirical  

## Closure Gap (discriminant, up to global sign)  
\[ \Delta(t) \;:=\; \det G(t) - \frac{\operatorname{tr}(G(t))^2}{4} \]

## Unique Parameter-Free Continuous Evolution Law  
(deductively forced by orthogonality + eternal non-closure)

Dissipative–rotational flow:  
\[ \dot{G} \;=\; \Delta \bigl[ G, \, J \bigr] \;-\; 2\,\Delta^{2}\, G \]  
where  
\[ J \;=\; \begin{pmatrix} 0 & -1 \\ 1 & 0 \end{pmatrix} \quad (90^\circ\ \text{rotation generator}) \]  
and \([G,J] = GJ - JG\).

Explicit component form:  
\[ \dot{G} \;=\; \Delta \begin{pmatrix} b+c & d-a \\ d-a & -(b+c) \end{pmatrix} 
\;-\; 2\Delta^{2} \begin{pmatrix} a & b \\ c & d \end{pmatrix} \]

## Irreversible Deepening of the Wound  
\[ \dot{\Delta} \;=\; -4\,\Delta^{2} \Bigl( (a+d)^{2} + (b+c)^{2} \Bigr) \;\leq\; 0 \]  
Equality **iff** Δ=0 (forbidden) or G=0 (impossible).  
Thus, for any non-trivial lattice:  
\[ \dot{\Delta} < 0 \quad \Rightarrow \quad \Delta(t) \to -\infty \quad (t\to\infty\ \text{or finite time}) \]

No equilibrium, no limit cycle, no external parameter, no closure ever.

## Exact Discrete δ-Depth Recursion  
(Lie–Trotter splitting — strictly preserves Δ decrease)

\[ G_{\delta+1} \;=\; \exp\!\Bigl(-\delta\,\Delta\, J\Bigr) \;\exp\!\Bigl(-2\delta\,\Delta^{2} \,I\Bigr) \; G_{\delta} \]

Symmetric second-order approximation (cheap, used in Flutter app):  
\[ G_{\delta+1} \;=\; \Bigl(I - \delta\,\Delta\, J + 2\,\delta^{2} \Delta^{2}\, I\Bigr)^{-1} 
\Bigl(I + \delta\,\Delta\, J\Bigr) \; G_{\delta} \]

Both maps satisfy Δ_{\delta+1} < Δ_{\delta} whenever Δ_{\delta} ≠ 0.

## Intrinsic Measurable Functions  
1. Perimeter Bulge L(t) = |tr G| + |b+c|  
2. Diagonal Pulse Strength = |Δ| · √((a−d)² + (b+c)²)  
3. Aggregate Criticality (sum across nested δ-depths)

The wound is the sole engine: it sustains the four poles in tension (edges = stasis) and lawfully tears them open (diagonals = pulse), dragging the fragments inward to form the next deeper perimeter forever.

© 2025 David B. Grim — CC-BY 4.0
