# Primate Shoulder AI — Data Science Workflow

**Kevin P. Klier**  
M.A. Biological Anthropology, University at Buffalo  
Buffalo Human Evolutionary Morphology Lab (BHEML)  

---

## Master's Project (Primary)  
**699 3D primate shoulder girdle specimens** (clavicle, scapula, humerus)  
- GPA alignment → PCA → Procrustes ANOVA → Mantel tests (10,000 perms)  
- Identified *Hylobates lar* as extreme locomotor outlier  
- [Download PDF](masters_project_pectoral_girdle.pdf)  

---

## Undergrad Senior Thesis (Supporting)  
**215 right clavicles** from 6 catarrhine species  
- First geometric morphometric analysis (7 landmarks)  
- Found *Gorilla gorilla* highest disparity, *Hylobates lar* lowest  
- [Download PDF](undergrad_thesis_clavicle.pdf)  

---

## Workflow (Reproducible in MorphoJ & PAST)  
1. **Data**: 3D scans → `.dta` landmarks  
2. **Preprocessing**: GPA  
3. **Analysis**: PCA, ANOVA, Mantel  
4. **Validation**: Phylogenetic & locomotor signals  

---

## Tools  
- MorphoJ, Landmark 3.6, FlexScan3D, PAST, PASSaGE  

---

## Visualizations  
<image-card alt="Humerus PCA Plot" src="Scatter%20Plot%20and%20Wireframe%20Humeri%203.png" ></image-card>  
*PC1 vs PC2 — Hylobates lar = extreme outlier*

<image-card alt="Neighbor-Joining Tree" src="Neighbor-joining%20tree.png" ></image-card>  
*Phylogenetic signal from Procrustes distances*

---

**No custom code. 100% original data. Methods follow published protocols.**  
*IBM AI Fundamentals + Capstone certified (Nov 2025)*
