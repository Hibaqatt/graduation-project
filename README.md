# Analysis of Volumetric Locking in Nearly Incompressible Hyperelastic Materials Using Abaqus

## 📌 Project Overview
This thesis investigates the numerical challenge of volumetric locking in nearly incompressible hyperelastic materials using the finite element software Abaqus.

Nearly incompressible materials (such as rubber-like and biological tissues) exhibit numerical difficulties when analyzed using standard displacement-based finite elements, leading to inaccurate and overly stiff results due to volumetric locking.

This study focuses on evaluating different finite element types, mesh refinement strategies, and analysis approaches to improve accuracy and convergence.

---

## 🎯 Objectives
- Analyze volumetric locking behavior in nearly incompressible hyperelastic materials
- Compare different finite element types (standard, reduced integration, hybrid)
- Study the effect of mesh refinement on accuracy and convergence
- Identify the most effective strategy to reduce or eliminate volumetric locking

---

## ❓ Research Questions
- How do standard, reduced, and hybrid elements affect volumetric locking?
- How does mesh refinement influence numerical accuracy?
- Can hybrid elements reduce volumetric locking compared to standard elements?
- Which element type provides the best balance between accuracy and efficiency?

---

## 🛠️ Methodology
- Finite Element Analysis using Abaqus
- Cook’s Membrane model as benchmark case study
- Neo-Hookean hyperelastic material model
- Different Poisson’s ratio values close to incompressibility (ν → 0.5)
- Displacement-controlled and force-controlled loading approaches
- Mesh refinement studies for convergence analysis

---

## 📊 Key Findings
- Standard fully integrated elements suffer from volumetric locking
- Hybrid elements significantly reduce locking and improve convergence
- Mesh refinement improves accuracy and solution stability
- Force-controlled analysis provides clearer convergence behavior
- Displacement-controlled analysis offers better numerical stability in some cases

---

## 📌 Conclusions
- Volumetric locking is a major issue in nearly incompressible materials
- Proper element selection is critical for accurate simulations
- Hybrid elements are the most reliable for mitigating locking
- Mesh refinement plays a key role in achieving convergence

---

## 📁 Repository Contents
- `presentation.pdf` → Presentation slides
---

## 📌 Recommendations
- Avoid standard full integration elements in nearly incompressible problems
- Prefer hybrid elements for improved accuracy
- Extend study to other hyperelastic models (Mooney-Rivlin, Ogden)
- Perform further mesh sensitivity studies for complex geometries

---

## 👩‍💻 Author
Finite Element Analysis Graduation Project using Abaqus
