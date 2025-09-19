<div align="center">

<picture>
  <img width="100%" src="https://capsule-render.vercel.app/api?type=waving&amp;color=gradient&amp;customColorList=0,1,2,3,4,5,6,7,8,9,10,11,12,13,14,15,16,17,18,19,20&amp;height=300&amp;section=header&amp;text=Apricity%20State&amp;fontSize=84&amp;animation=fadeIn&amp;fontAlignY=36&amp;desc=Environmental%20Systems%20%E2%80%94%20Energy%20Balance%2C%20Cycles%2C%20Adaptive%20Design&amp;descAlignY=62&amp;descSize=20&amp;fontColor=FFF8FD" alt="Header"/>
</picture>

<picture>
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&amp;weight=600&amp;size=20&amp;duration=3400&amp;pause=900&amp;color=E6C6FF&amp;center=true&amp;vCenter=true&amp;multiline=true&amp;width=980&amp;height=70&amp;lines=Apricity%3A%20the%20warmth%20of%20sunlight%20in%20winter%E2%80%94a%20design%20lens%20for%20climate%20systems;Science-forward%20models%20for%20urban%20microclimate%2C%20water%2C%20carbon%2C%20and%20resilience" alt="Typing subtitle"/>
</picture>

<p>
  <img src="https://img.shields.io/badge/Scope-Science--Forward-FFE0F5?style=for-the-badge&amp;labelColor=E6E0FF" alt="Science">
  <img src="https://img.shields.io/badge/Domains-Climate%20%E2%80%A2%20Hydrology%20%E2%80%A2%20Urban-99D1FF?style=for-the-badge&amp;labelColor=FFE0F5" alt="Domains">
  <img src="https://img.shields.io/badge/Methods-PDE%20%E2%80%A2%20Optimal%20Transport%20%E2%80%A2%20Inference-D4FFE4?style=for-the-badge&amp;labelColor=E6E6FA" alt="Methods">
  <img src="https://img.shields.io/badge/Ethos-Stewardship-FDE1C9?style=for-the-badge&amp;labelColor=E6E0FF" alt="Ethos">
</p>

<picture>
  <img src="https://capsule-render.vercel.app/api?type=rect&amp;color=gradient&amp;customColorList=20,18,16,14,12,10,8,6,4,2,0&amp;height=4" width="100%" alt="Divider"/>
</picture>

</div>

*Author: **Cazzy Aporbo, MS***

> **Reading Guide &amp; Scope**
>
> Apricity State is a **science-oriented, theory-first** architecture for environmental systems. Equations and models are provided to **structure thinking and simulation**, not to assert empirical claims in a specific locale. Treat biological parallels as **analogies**; treat design patterns as **theoretical architectures** requiring local data, calibration, and governance.

---

## 1. Why “Apricity”?

**Apricity**—the felt warmth of winter sun—captures a design aim: **maximize beneficial heat and light while minimizing harmful extremes**. We translate that intuition into **physics-grounded** models for energy, water, air, and living structure, then bind them into decision workflows.

<div align="center">
  <div style="background: linear-gradient(135deg,#FFE0F5,#E6E0FF); padding: 12px 16px; border-radius: 12px; display:inline-block; margin:6px; font-weight:600;">Sensing → Modeling → Inference → Design</div>
  <div style="background: linear-gradient(135deg,#D4FFE4,#FFE5CC); padding: 12px 16px; border-radius: 12px; display:inline-block; margin:6px; font-weight:600;">Planetary Laws → Local Constraints → Human Outcomes</div>
</div>

---

## 2. Energy Balance — From Zero-D to Urban Tiles

**Global/column energy balance (zero-D):**
$$
C\,\frac{dT}{dt} \;=\; \frac{(1-\alpha)S_0}{4} \;-\; \varepsilon\sigma T^4 \;+\; F(t)
$$

- \(C\): effective heat capacity; \(\alpha\): albedo; \(S_0\): solar constant; \(\varepsilon\): emissivity; \(\sigma\): Stefan–Boltzmann; \(F(t)\): external forcing (e.g., aerosols, land-use).

**Urban tile (surface–canopy two-layer):**
$$
\begin{aligned}
C_s \dot{T}_s &= (1-\alpha_s) S_\downarrow + L_\downarrow - \varepsilon_s \sigma T_s^4 - H - LE - G + Q_{\text{anth}} \\
C_c \dot{T}_c &= H + LE + Q_{\text{adv}} - Q_{\text{vent}}
\end{aligned}
$$

- Fluxes: sensible \(H\), latent \(LE\), ground \(G\), anthropogenic \(Q_{\text{anth}}\), advection \(Q_{\text{adv}}\), ventilation \(Q_{\text{vent}}\).  
- **Design levers:** \(\alpha_s\) (cool materials), \(\varepsilon_s\) (radiative coatings), roughness length (ventilation), leaf-area index (evapotranspiration).

---

## 3. Advection–Diffusion–Reaction (ADR) for Heat &amp; Air

**Scalar transport (temperature/particulate) on domain \(\Omega\):**
$$
\frac{\partial \phi}{\partial t} + \mathbf{u}\cdot\nabla \phi
= \nabla\cdot(\kappa \nabla \phi) + R(\phi,\mathbf{x},t) + S(\mathbf{x},t)
$$

- \(\phi\): temperature or concentration; \(\mathbf{u}\): wind field; \(\kappa\): eddy diffusivity; \(R\): sinks/sources (e.g., deposition, chemistry); \(S\): emissions/heat sources.

**Control objective (cool corridors / clean-air lanes):**
$$
\min_{\mathcal{D}} \int_\Omega w(\mathbf{x})\,\phi(\mathbf{x})\,d\mathbf{x}
\quad \text{s.t. ADR dynamics and siting constraints on } \mathcal{D}
$$

\(\mathcal{D}\) encodes placement/size of shade trees, water features, porous pavements.

---

## 4. Water Balance — Catchments to City Blocks

**Bucket model (daily):**
$$
\frac{dS}{dt} = P - E(S) - Q(S) - I(S)
$$

- \(S\): soil storage; \(P\): precipitation; \(E\): evapotranspiration; \(Q\): runoff; \(I\): infiltration to groundwater.  
- **Green-blue infrastructure** tunes \(E, Q, I\) via canopy, soils, wetlands, bioswales.

**Coupling to heat:** latent flux \(LE = \rho\lambda E\) cools surfaces; design for **co-benefits**.

---

## 5. Carbon Cycling — Simple Compartments for Planning

Let \(C_a, C_t, C_s\) be atmospheric, terrestrial, and surface pools.

$$
\begin{aligned}
\dot{C}_a &= E_{\text{anth}} + \rho_{t\to a}(T)\,C_t + \rho_{s\to a}(T)\,C_s - \rho_{a\to t}(T)\,C_a - \rho_{a\to s}(T)\,C_a \\
\dot{C}_t &= \rho_{a\to t}(T)\,C_a - \rho_{t\to a}(T)\,C_t \\
\dot{C}_s &= \rho_{a\to s}(T)\,C_a - \rho_{s\to a}(T)\,C_s
\end{aligned}
$$

- \(\rho_{\cdot}(T)\) capture temperature-sensitive exchange.  
- Use for **scenario stress-tests**; calibrate locally before claims.

---

## 6. Remote Sensing &amp; Data Assimilation

**State-space model:**
$$
x_{t+1} = f(x_t) + \eta_t,\qquad y_t = h(x_t) + \epsilon_t
$$

- \(x_t\): latent fields (e.g., \(T_s\), soil moisture, PM\(_{2.5}\)); \(y_t\): satellite/in-situ observations.  
- Filters: **EKF/EnKF** to merge physics predictions with observations; track uncertainty.  
- Provenance: every tile keeps **sensor, timestamp, QA, license**.

---

## 7. Optimal Transport (OT) for Microclimate Routing

We frame **cool-air distribution** or **pollution re-routing** with OT.

**Benamou–Brenier dynamic OT:**
$$
\min_{\rho,v} \int_0^1\!\!\int_\Omega \rho \|v\|^2\,d\mathbf{x}\,dt
\quad \text{s.t.}\quad \partial_t \rho + \nabla\cdot(\rho v)=0,\;
\rho(\cdot,0)=\mu_0,\;\rho(\cdot,1)=\mu_1.
$$

- \(\mu_0\): current hot-spot intensity; \(\mu_1\): desired cooled distribution.  
- Yields **least-effort flow fields** that inform placement of vents, voids, and vegetation corridors.

---

## 8. Biodiversity &amp; Connectivity

Let habitat parcels be a graph \(G=(V,E)\) with weights \(w_{ij}\) (suitability).

- **Algebraic connectivity** \(\lambda_2(L)\) tracks robustness; maximize \(\lambda_2\) by adding minimal corridors.  
- **Effective resistance** \(R_{ij}\) highlights **pinch points** for protection.

```mermaid
flowchart LR
A[Core Habitat] -- corridor --> B[Patch]
B -- corridor --> C[Patch]
A -. pinch point .-> C
````

---

## 9. Materials & Radiative Design

**Net longwave exchange (surface $s$ vs. sky):**

$$
q_{\text{LW}} \approx \varepsilon_s \sigma (T_s^4 - T_{\text{sky}}^4)
$$

* Increase $\varepsilon_s$ in the **atmospheric window** (8–13 µm) for passive radiative cooling; control $\alpha_s$ for solar gains in winter.
* **Trade-off:** maximize **apricity** (useful gains) while bounding peak heat.

---

## 10. Risk & Resilience — Budgets and Tails

**Risk composition:** $\text{Risk} = \text{Hazard} \times \text{Exposure} \times \text{Vulnerability}$.

**Robust siting (CVaR):**

$$
\min_{z\in\mathcal{Z}} \ \text{CVaR}_{\beta}\big(L(z,\xi)\big)
\quad \text{s.t. budgets, equity, ecology}
$$

* $\xi$: scenario uncertainty; ensure **equity constraints** (e.g., heat relief coverage for vulnerable blocks).

---

## 11. Evaluation — The Apricity Index

We combine physics, ecology, and human comfort.

| Axis         | Metric (examples)                                | Direction |
| ------------ | ------------------------------------------------ | --------- |
| Thermal      | ΔT$_{\text{max}}$ (°C), WBGT, UHI intensity      | ↓         |
| Hydrology    | Peak runoff %, baseflow stability                | ↓ / ↑     |
| Air          | Mean PM$_{2.5}$, NO$_2$ exposure hours           | ↓         |
| Carbon       | Net ecosystem exchange, storage gain             | ↑         |
| Biodiversity | $\lambda_2(L)$, effective resistance percentiles | ↑ / ↓     |
| Equity       | Share of benefits to high-risk groups            | ↑         |

**Composite (illustrative):**

$$
\mathsf{AI} = w_T(1-\hat{T}) + w_H(1-\hat{Q}) + w_A(1-\hat{P}) + w_C\hat{C} + w_B\hat{B} + w_E\hat{E}
$$

Hats denote normalized scores $[0,1]$.

---

## 12. Governance, Ethics, and Community

* **Consentful sensing:** clear notices, opt-outs, privacy by design.
* **Attribution & licenses:** datasets carry origin and allowed uses.
* **Maintenance plans:** infrastructure degrades; budgets must include care cycles.
* **No techno-solutionism:** local knowledge and co-design are first-class inputs.

---

## 13. Reference Pipeline (Pseudocode)

```python
def apricity_pipeline(site, sensors, satellite):
    """
    Theory-first environmental workflow (requires local calibration).
    """
    # 1) Ingest + QC
    y = collect_observations(sensors, satellite)
    y = quality_filter(y); provenance_log(y)

    # 2) Initialize states (heat, water, air, carbon)
    x0 = initialize_states(site.meteorology, site.landcover)

    # 3) Forecast + assimilate
    for t in horizon:
        x_pred = physics_step(x0, forcings=site.forcings[t])
        x = enkf_update(x_pred, y[t], H=obs_operator)

    # 4) Design candidates
    designs = propose_designs(site.constraints, levers=["albedo","LAI","permeable","voids"])

    # 5) Evaluate (ADR, EBMs, CVaR, connectivity)
    scored = [score_design(d, models=["adr","ebm","hydro","ot","spectral"]) for d in designs]

    # 6) Select under multi-criteria + equity
    chosen = pareto_front(scored, weights=stakeholder_weights, equity_rules=rules)

    # 7) Monitoring plan
    kpis = build_monitoring(chosen, sensors, audits=True)
    return chosen, kpis
```

---

## 14. Reading Transitions — Preventing Category Errors

1. **Physics first:** conservation laws bound what’s feasible.
2. **Then inference:** combine models with data, track uncertainty.
3. **Then design:** pick levers that move the metrics **you value**.
4. **Then governance:** verify consent, equity, and maintenance.
5. **Iterate:** measure, compare, and update models.

---

## 15. Math Pocket Guide

* **Energy balance:** $C\dot T=(1-\alpha)S_0/4-\varepsilon\sigma T^4+F$.
* **ADR:** $\partial_t \phi + \mathbf{u}\cdot\nabla\phi = \nabla\cdot(\kappa\nabla\phi)+R+S$.
* **Water bucket:** $\dot S=P-E-Q-I$.
* **Dynamic OT:** Benamou–Brenier formulation.
* **Spectral:** $\lambda_2(L)$ for connectivity; effective resistance for pinch points.
* **Risk:** CVaR minimization under budgets & equity constraints.

---

<div align="center">
<picture>
  <img src="https://capsule-render.vercel.app/api?type=rect&amp;color=gradient&amp;customColorList=20,18,16,14,12,10,8,6,4,2,0&amp;height=4" width="100%" alt="Divider"/>
</picture>
<i>Apricity State is a science-forward, theory-first blueprint. Calibrate locally, validate empirically, and govern with care.</i>
</div>
```
::contentReference[oaicite:0]{index=0}
