# Unguided Cerebral Organoid Protocol

Welcome to the open, detailed, and visual protocol for generating unguided cerebral organoids from iPSCs.

<div class="cards">
  <div class="card">
    <h3>💡 Quick Start</h3>
    <p>Step-by-step, image-rich protocol for reproducible results.</p>
  </div>
  <div class="card">
    <h3>📖 Appendix & Troubleshooting</h3>
    <p>Clear guidance for cell counting, seeding, and managing organoid fusion or sticking.</p>
  </div>
  <div class="card">
    <h3>🖼️ Gallery</h3>
    <p>Chronological images for every stage: EB, embedding, maturation.</p>
  </div>
</div>

!!! tip "Best Practice"
    For optimal results, follow sterile technique and monitor EB morphology at every stage.

---

# Protocol for Generating Unguided Cerebral Organoids

_With Illustrated Steps and Timeline_

**Author:**  
Evgenii Kachkin

**Affiliation:**  
Heidelberg University / ZMBH / Kaessmann Lab

**Version:**  
February 17, 2025

---

## Contents

1. [References](#references)
2. [Introduction](#introduction)
3. [Materials and Equipment](#materials-and-equipment)
   - 3.1 Cell Lines and Media
     - 3.1.1 Media Compositions
   - 3.2 Reagents
     - 3.2.1 Anti-apoptotic Inhibitors Compositions
   - 3.3 Plastics and Disposables
   - 3.4 Equipment
4. [Pre-Protocol Considerations](#pre-protocol-considerations)
5. [Detailed Protocol](#detailed-protocol)
   - 5.1 Timeline Overview
   - 5.2 Stage I: Cell Cultivation and Seeding (Day 0)
     - 5.2.1 Stem Cell Cultivation
     - 5.2.2 Dissociation of iPSCs
     - 5.2.3 Harvesting and Counting Cells
     - 5.2.4 Seeding into 96-Well Plate
     - 5.2.5 Media Change Technique (at 2 Days Post Seeding)
   - 5.3 Stage II: Embryoid Body Growth
   - 5.4 Stage III: Neuroinduction
   - 5.5 Stage IV: Embedding in Basement Membrane Matrix (Days 7–9)
     - 5.5.1 Post-Embedding Maintenance (Full-Volume Changes in a Dish)
   - 5.6 Stage V: Retinoic Acid Addition and Ventricle Formation (Days 13–15+)
A. [Appendix: Counting Cells in a Neubauer Chamber with Trypan Blue and Detailed Seeding Example](#appendix-a)
   - A.1 Preparing and Loading the Chamber
   - A.2 Microscopy and Counting
   - A.3 Cell Concentration and Viability Calculation
   - A.4 Detailed Example: Preparing for a 96-Well Plate
   - A.5 Final Notes and Tips
B. [Appendix: Preventing and Managing Sticking of Organoids](#appendix-b)
   - B.1 Preventive Measures
   - B.2 Managing Stuck or Fused Organoids
   - B.3 Additional Tips
C. [Image Gallery](#image-gallery)
   - C.1 Seeding for Embryoid Body Formation
   - C.2 Embryoid Body Formation
   - C.3 Embedded Organoid Development
   - C.4 Organoid Maturation
   - C.5 Plate 1: Early Embedding (8 dps) and Early Vitamin A Addition (14 dps)
   - C.6 Plate 2: Early Embedding (8 dps) and Early Vitamin A Addition (14 dps)
   - C.7 Plate 3: Late Embedding (9 dps) and Late Vitamin A Addition (15 dps)

---

## 1. References

Based on, with modifications:

1. JoVE (2023), DOI: 10.3791/65176.
2. Lancaster, M.A., Knoblich, J.A. Generation of Cerebral Organoids from Human Pluripotent Stem Cells. Nat Protoc. 9, 2329–2340 (2014).

---

## 2. Introduction

Cerebral organoids are three-dimensional multicellular structures derived from pluripotent stem cells that mimic brain-like regions. This protocol outlines the generation of “unguided” cerebral organoids from induced pluripotent stem cells (iPSCs), allowing spontaneous formation of dorsal forebrain–like areas. Applications include studying embryonic brain development, species-specific neurogenesis differences, and modeling neurodevelopmental disorders.

---

## 3. Materials and Equipment

### 3.1 Cell Lines and Media

- iPSC Lines: Human, chimpanzee, or rhesus monkey.
- iPSC Culture Media: mTeSR Plus (human/chimpanzee) or iPSC Brew (macaque).
- Neuroinduction Media (NIM): DMEM/F12 with supplements.
- Differentiation Media (DM): DMEM/F12 and Neurobasal with supplements, and with or without vitamin A (retinoic acid).

#### 3.1.1 Media Compositions

**Table 1: NIM (Neuroinduction Media) for 50 mL**

| Component                 | Amount   |
|---------------------------|----------|
| DMEM/F12                  | 48.5 mL  |
| N2 supplement             | 500 µL   |
| GlutaMax (100x stock)     | 500 µL   |
| MEM NEAA (100x stock)     | 500 µL   |
| Heparin (1 mg/mL stock)   | 50 µL    |

**Table 2: DM -A or +A (Differentiation Media without or with retinoic acid) for 50 mL**

| Component                 | Amount   |
|---------------------------|----------|
| DMEM/F12                  | 24 mL    |
| Neurobasal                | 25 mL    |
| B27 -A or +A              | 500 µL   |
| N2 supplement             | 250 µL   |
| MEM NEAA (100x stock)     | 250 µL   |
| GlutaMax (100x stock)     | 500 µL   |
| Pen-Strep (100 U/mL stock)| 500 µL   |
| 2-MeEtOH (1:100)          | 17.5 µL  |
| Insulin                   | 12.5 µL  |

### 3.2 Reagents

- DPBS (Dulbecco’s Phosphate-Buffered Saline)
- Accutase
- DMEM/F-12
- Pro-survival compound (PSC) or CET (mix of anti-apoptotic inhibitors) with Polyamine (CET+P)
- Basement membrane matrix (Matrigel)
- Retinoic acid (vitamin A)

#### 3.2.1 Anti-apoptotic Inhibitors Compositions

**Table 3: PSC Dilutions**

| Component | Dilution |
|-----------|----------|
| PSC       | 1:1000   |

**Table 4: CET+P (or CEPT) Dilutions**

| Component  | Dilution |
|------------|----------|
| CET        | 1:4000   |
| Polyamine  | 1:1000   |

### 3.3 Plastics and Disposables

- 96-well ultralow attachment plates
- 15 mL conical tubes, 60 mm Petri dishes
- Parafilm
- Sterile scissors, forceps, and pipette tips
- Neubauer chamber or automated cell counter

### 3.4 Equipment

- **Laminar Flow Hood:** For sterile work and UV sterilization.
- **Incubator:** 37°C, 5% CO₂, 95% humidity.
- **Centrifuge:** Capable of 300 ×g.
- **Orbital Shaker:** 65 rpm capacity.

---

## 4. Pre-Protocol Considerations

1. **iPSC Quality:** Ensure iPSCs exhibit minimal spontaneous differentiation and are mycoplasma-free.
2. **Passaging iPSCs:** Split cells to achieve approximately 80% confluency on the day of EB seeding.
3. **Sterile Technique:** Disinfect surfaces with 70–80% ethanol and maintain sterile conditions to prevent contamination.

---

## 5. Detailed Protocol

### 5.1 Timeline Overview

![Figure 1: Schematic Overview of Organoid Production Timeline](images/timeline.png)

### 5.2 Stage I: Cell Cultivation and Seeding (Day 0)

#### 5.2.1 Stem Cell Cultivation

Maintain iPSCs in culture, monitoring their viability post-thaw. Allow cells to recover, proliferate, and reach 80% confluency before passaging, using a splitting ratio of 1:6 to 1:15 based on colony density and health. Limit passaging to three passages to preserve genomic stability.

![Figure 2: Cultivation of Induced Pluripotent Stem Cells](images/6.png)

#### 5.2.2 Dissociation of iPSCs

1. When iPSCs reach 80–90% confluency, aspirate the medium.
2. Wash cells with DPBS.
3. Add 400 µL Accutase and incubate at 37°C for 5–7 minutes until cells detach.
4. Visually confirm under a microscope that all cells are fully detached from the culture surface.
5. Stop the reaction by adding 1 mL prewarmed DMEM/F12. For sensitive cell lines, you may use DMEM/F12 supplemented with an anti-apoptotic compound.
6. Gently pipette up and down 5–10 times to obtain a single cell suspension.

#### 5.2.3 Harvesting and Counting Cells

For a detailed explanation of cell counting in the Neubauer chamber, please see [Appendix A](#appendix-a).

1. Transfer the cell suspension to a 15 mL conical centrifuge tube.
2. Centrifuge at 300 ×g for 5 minutes at room temperature.
3. Aspirate the supernatant and resuspend the pellet in 2 mL DMEM/F12. For sensitive cell lines, you may use DMEM/F12 supplemented with an anti-apoptotic compound.
4. Count cells using a Neubauer chamber or an automated cell counter.

#### 5.2.4 Seeding into 96-Well Plate

For a detailed explanation of cell seeding and calculations, please see [Appendix A](#appendix-a).

1. Adjust cell density to 9,000 cells per 150 µL (60,000 cells/mL) using iPSC culture medium supplemented with anti-apoptotic compounds.
2. Dispense 150 µL of the cell suspension into each well of an ultralow attachment 96-well plate.
3. Important: While pipetting, gently shake the tube containing the cell suspension to prevent cell sedimentation. Add cells to the wells in a single slow motion to avoid creating separate drops.
4. Incubate at 37°C, 5% CO₂ without disturbance for the first 48 hours.
5. At 2 days post seeding (dps), remove 100 µL of medium from each well and add 150 µL of fresh iPSC culture medium without PSC.

#### 5.2.5 Media Change Technique (at 2 Days Post Seeding)

**1. Gently Remove Medium:**
- Hold the 96-well plate at a slight angle so that the embryoid bodies (EBs) collect near one side of the well.
- Using a P200 pipette set to 100 µL (or 150 µL if possible), place the pipette tip against the wall of the well at an angle of about 45 degrees, making sure the tip is above the EBs.
- Slowly aspirate 100 µL of the old medium. Avoid touching the EB or creating turbulent flow that might damage or aspirate the EB.
- Keep the pipette tip away from the bottom of the well; do not scrape the surface.

**2. Add Fresh Medium:**
- Gently dispense 150 µL of fresh iPSC culture medium (without PSC) down the side of the well (again at an angle), allowing it to flow in slowly.
- This prevents excessive turbulence and keeps the EB in place.

![Figure 3: Seeding of 9,000 Cells per Well](images/1.png)

---

### 5.3 Stage II: Embryoid Body Growth

1. **Medium Changes Every Other Day:**
   - After seeding EBs, allow them to grow undisturbed for the first 48 hours.
   - Starting from day 2 post-seeding (dps), perform medium changes every other day.
   - Gently remove 150 µL of spent medium from each well using a P200 pipette. If some volume has evaporated, remove less to avoid disturbing the EB.
   - Angle the pipette tip near the well wall, keeping clear of the EBs in the center. Aspirate slowly to prevent drawing EBs into the tip.
   - Replenish with 150 µL of fresh iPSC medium (without anti-apoptotic compounds). Slowly dispense the medium along the side of the well to minimize shear stress.
   - Tip: Prewarm all media to 37°C before use.

2. **Morphology and Growth by 4–5 dps:**
   - By days 4–5 post-seeding, EBs typically appear smooth, spherical, and often display translucent edges.
   - EBs may range from ∼150–300 µm in diameter at this stage, though size can vary based on cell line.
   - **Contamination Check:** Use a microscope to inspect for bacterial or fungal contamination. Discard any compromised wells to protect the rest of the culture.

---

### 5.4 Stage III: Neuroinduction

1. **Switching from iPSC Medium to NIM:**
   - For macaque EBs: switch on day 4 post-seeding (4 dps).
   - For human/chimpanzee EBs: switch on day 5 post-seeding (5 dps).
   - Replace as much of the old iPSC medium as possible with 150 µL of Neuroinduction Medium (NIM) in each well.

2. **Ongoing NIM Changes (Every Other Day):**
   - Continue to feed with NIM every other day by removing 150 µL (or less in case of evaporation) and replacing it with fresh, prewarmed NIM.
   - Maintain careful pipetting technique to avoid aspirating or damaging the EBs.

---

### 5.5 Stage IV: Embedding in Basement Membrane Matrix (Days 7–9)

1. **Timing:** Approximately 7 dps for rhesus macaque or 8–9 dps for human/chimpanzee EBs.

2. **Preparation:**
   - (Sterilising of scissors and forceps in Sekusept once a month).
   - UV-sterilize scissors and forceps under the laminar flow hood.
   - Thaw Matrigel on ice for 30–60 minutes (1.5 mL is sufficient for 96 EBs).

3. **Creating Parafilm Dimples:**
   - Cut a piece of Parafilm to approximately 6 cm × 6 cm. This size is sufficient to form a grid of 16 dimples (4×4).
   - Place the Parafilm over a 200 µL pipette tip rack (with a 4×4 arrangement of tips removed).
   - Gently press the Parafilm down over the empty tip holes to create shallow wells. These will become your individual dimples.
   - Tip: Ensure each dimple is deep enough to hold one EB in a small droplet of Matrigel but not so large that the droplet spreads too thin.
   - After forming the dimples, carefully cut away any excess Parafilm around the edges to create a neat 4×4 section. This step helps the dimpled Parafilm fit evenly in a 60 mm Petri dish.
   - Transfer the dimpled Parafilm into a sterile 60 mm Petri dish, ensuring the dimples face upwards.

4. **Transferring EBs:**
   - Slightly tilt the plate to allow EBs to collect on one side of each well.
   - Use a cut 200 µL pipette tip (2–3 mm) to widen the opening. This prevents excessive shear stress on the EBs while pipetting.
   - Set your pipette to a volume of 150–200 µL. Place the tip near the EBs (but not directly on them) and gently aspirate. Move slowly to avoid damaging the EBs or creating bubbles.
   - Transfer one EB per Parafilm dimple (4×4 = 16 dimples). Dispense carefully at a low angle, allowing the EB to settle in the center of the dimple. Avoid excess agitation that might cause EBs to roll out.
   - After transferring a few EBs, any medium accumulating in the dimple can be gently aspirated. Use a new small pipette tip (20 µL) to remove extra medium without disturbing the EB. Keep enough moisture so that the EB does not dry, but remove as much liquid as possible to ensure that Matrigel will not be overly diluted in the next step.

5. **Adding Matrigel:**
   - Use a 200 µL pipette tip to handle Matrigel (kept on ice).
   - Pipette the whole volume of cold Matrigel from the tube and pipette directly onto each EB-containing dimple by droplet. Work quickly to avoid premature polymerization at room temperature.
   - Using a 10 µL pipette tip or a microdissection tool, gently push or nudge the EB toward the middle of the Matrigel droplet. Do not disrupt the droplet border—avoid piercing through the Matrigel layer.
   - If the droplet appears too small to fully cover the EB, add another small droplet of Matrigel.
   - If the EB is too close to the droplet edge, gently move it inward and deposit more Matrigel to keep the EB fully surrounded.
   - Ensure the Matrigel does not spread so thin that it fails to provide adequate 3D support.

6. **Polymerization:**  
   - Incubate the dish at 37°C for 15–30 minutes to allow Matrigel to polymerize.

7. **Detaching to Shaker Culture:**
   - Prepare a dish with fresh DM (no Vitamin A): Fill a 60 mm Petri dish (or similar) with sufficient differentiation medium (DM) without vitamin A—enough volume (e.g., 5–6 mL) to fully submerge the Parafilm sheet. Keep this dish under sterile conditions in the laminar flow hood.
   - Carefully pick up with forceps the Parafilm by its edges (to avoid disturbing the embedded EBs).
   - Invert (flip) it so that the Matrigel droplets/EBs face downward. Gently submerge the flipped Parafilm in the dish containing DM. The Matrigel droplets should now be in direct contact with the medium.
   - Swirl or gently roll the Parafilm: Holding the Petri dish at a slight angle, swirl the dish in a circular motion. If needed, use a gentle rolling motion of the Parafilm itself (e.g., tipping it slightly side-to-side) to dislodge the Matrigel-embedded EBs from the film surface.  
     Note: Avoid vigorous shaking—excessive shear can damage the EBs. A few gentle swirls typically loosen them.
   - Check for EBs that remain attached: Ensure all EBs have been released into the medium. If any droplets remain stuck, use a wide-bore pipette tip (200 µL tip with the end cut off) to gently coax them off the Parafilm.
   - Once all EBs are detached, remove the Parafilm from the dish and discard it.
   - Place the Petri dish (now containing Matrigel-embedded EBs in DM) onto an orbital shaker set to 65 rpm.
   - Incubate at 37°C with 5% CO₂ and 95% humidity.

![Figure 4: EBs during transfer and embedding.](images/2.png) (images/3.png)

---

#### 5.5.1 Post-Embedding Maintenance (Full-Volume Changes in a Dish)

- **Full Media Change Schedule (Without Vitamin A):**
  - Every other day, remove and replace the entire volume of differentiation medium (DM) (5–6 mL).
  - This ensures fresh nutrients and reduces waste/toxin buildup.

- **Gathering Organoids in the Center:**
  - Before aspirating, gently rotate or swirl the dish on a flat, horizontal surface.
  - This slow, circular motion helps organoids drift toward the center of the dish.
  - Note: Avoid vigorous tilting or swirling, which can cause organoids to stick to the edges or become damaged.

- **Aspirating the Medium:**
  - Use a 1000 µL pipette set to 1 mL at a time.
  - Carefully place the pipette tip near the edge of the dish, away from the cluster of organoids.
  - Slowly aspirate the medium in successive 1 mL pulls until only a small layer of liquid remains.
  - Monitor for any organoids that might drift toward the pipette tip; if so, gently release them back into the center.

- **Refilling with Fresh DM (Without Vitamin A):**
  - Slowly add 5–6 mL of fresh DM down the side of the dish, allowing it to flow around the organoids.
  - Lightly swirl the dish afterward to distribute fresh medium evenly, but avoid creating excessive shear stress.

- **Observation and Maintenance:**
  - Examine the organoids regularly under a microscope or good lighting for necrosis, fusion, or contamination.
  - If organoids stick together or to the dish edge, use a wide-bore pipette tip to gently separate them.

![Figure 5: Organoid Growth in Differentiation Medium on the Shaker (No Vitamin A).](images/4.png)

---

### 5.6 Stage V: Retinoic Acid Addition and Ventricle Formation (Days 13–15+)

1. **Switch to Vitamin A DM:**
   - At the appropriate day (13 for rhesus, 14–15 for human/chimpanzee), perform a full-volume media change just as described above, but use DM containing vitamin A (retinoic acid).
   - Use the same volume (5–6 mL) and gentle technique to avoid shearing the organoids.
   - All subsequent feeds now include vitamin A (unless otherwise specified for experimental design).

2. **Feeding Frequency (Every 3–4 Days):**
   - After the initial vitamin A switch, continue replacing the entire medium volume every 3–4 days.
   - If organoids grow large or consume nutrients rapidly, you may increase the frequency of full-volume changes to every 2–3 days.

3. **Morphological Expectations:**
   - Over the next 1–2 weeks, expect to see ventricle-like cavities lined by neuroepithelial cells.
   - Monitor carefully for fusion if organoids become large or numerous. Consider gently separating fused organoids.

![Figure 6: Organoid Growth Post-Retinoic Acid Addition on the Shaker.](images/5.png)

**Final Remarks:**  
This detailed protocol provides a comprehensive guide for producing unguided cerebral organoids. Adhere to sterile techniques and monitor EB morphology closely. Adjust timelines based on specific iPSC lines and species to ensure successful organoid development. Incorporate best practices such as regular sterility checks and consistent Matrigel batch testing to maintain high-quality outcomes.

---

## Appendix A: Counting Cells in a Neubauer Chamber with Trypan Blue and Detailed Seeding Example

Accurate cell counting is essential for reproducible organoid formation. This section outlines how to prepare your sample for counting in a Neubauer (hemocytometer) chamber, how to factor in trypan blue for viability assessment, and how to calculate the volume needed for a 96-well plate when each well should receive 9,000 cells.

### A.1 Preparing and Loading the Chamber

1. **Sample Preparation:**
   - Gently resuspend your cell pellet in an appropriate medium (e.g., DMEM/F12 + PSC) to ensure a homogeneous cell suspension.
   - If the cell density is very high, pre-dilute the suspension (e.g., 1:2 or 1:10) to avoid overcrowding on the chamber grid.
   - **Trypan Blue Staining:** To assess viability, mix 10 µL of your cell suspension with 10 µL of trypan blue (1:1).
     - This introduces a 2-fold dilution factor to be accounted for in the final calculation.
     - Non-viable cells will appear dark or deep blue; viable cells remain unstained or faintly stained.

2. **Loading the Chamber:**
   - Clean the hemocytometer with 70% ethanol and place a coverslip over the counting grid.
   - Using a pipette, carefully load 10 µL of your (stained) cell suspension on the edge of the coverslip. Capillary action should pull the fluid under the coverslip, covering the grid.
   - Avoid introducing bubbles or overfilling the chamber; if you see fluid run into the outer channels, discard and reload.

---

### A.2 Microscopy and Counting

1. **Focus and Identify the Grid Lines:**
   - Place the hemocytometer on the microscope stage.
   - Under low magnification, focus on the central counting area. Each Neubauer chamber has 9 large squares.

2. **Count Cells in Four Corner Squares:**
   - Typically, you count the cells in four corner squares (each corner is subdivided into 16 smaller squares).
   - Include cells touching the top or left boundary lines; exclude cells on the bottom or right boundary lines to avoid double counting.
   - If cells are too densely packed, prepare a further dilution.

3. **(Optional) Calculate Viability by Using Trypan Blue:**
   - Record how many cells are stained vs. unstained to determine the viability percentage:  
     **Viability (%) = Number of unstained (viable) cells / Total cells × 100**

---

### A.3 Cell Concentration and Viability Calculation

1. **Average Cell Count:**
   - Suppose you count cells in four large squares: 45, 50, 48, and 52.
   - Average = (45 + 50 + 48 + 52) / 4 = 48.75 cells per large square.

2. **Convert to Cells/mL:**
   - In a Neubauer chamber, multiply by 10⁴ to obtain cells/mL:  
     48.75 × 10⁴ = 4.875 × 10⁵ cells/mL.

3. **Account for Trypan Blue Dilution:**
   - If you mixed the cell suspension with trypan blue at 1:1, that is a 2-fold total dilution.
   - Multiply the above result by 2:  
     4.875 × 10⁵ × 2 = 9.75 × 10⁵ cells/mL.
   - This is your final cell concentration.

---

### A.4 Detailed Example: Preparing for a 96-Well Plate

**Goal:** Seed 9,000 cells per well in 150 µL for each of 96 wells.

1. **Determine the Target Cell Density for Seeding:**
   - Each well requires 9,000 cells in 0.15 mL (150µL):  
     Target density = 9,000 cells / 0.15 mL = 60,000 cells/mL.

2. **Compare Your Final Measured Concentration to the Target:**
   - From the calculation above, your suspension is at 9.75 × 10⁵ cells/mL.
   - You need 6.0 × 10⁴ cells/mL for seeding.
   - The required dilution factor is:  
     9.75 × 10⁵ / 6.0 × 10⁴ ≈ 16.25.

   - In other words, you must dilute your cell suspension 16.25-fold to reach 60,000 cells/mL.

3. **Calculate the Final Volume Needed:**
   - If you currently have 1 mL of the concentrated suspension at 9.75 × 10⁵ cells/mL, to dilute it 16.25-fold, you need a total of:  
     16.25 mL − 1 mL = 15.25 mL of additional medium (with PSC if desired).
   - This gives you 16.25 mL at 6.0 × 10⁴ cells/mL once mixed thoroughly.

4. **Seeding a 96-Well Plate:**
   - Total volume needed for a 96-well plate:  
     96 × 0.15 mL = 14.4 mL.
   - You will have 16.25 mL total, which is enough for all 96 wells plus extra for pipetting errors.
   - Aliquot 150 µL into each well; each well now contains 9,000 cells.

---

### A.5 Final Notes and Tips

- **Check Viability:** If using trypan blue, ensure an acceptable percentage of viable (unstained) cells prior to seeding.
- **Mix Gently and Often:** Cells can settle quickly. Gently swirl or invert the tube before each pipetting step to keep the suspension homogeneous.
- **Add a Margin:** Preparing slightly more than the minimum needed for 96 wells (e.g., enough for 100 wells) helps avoid running short due to pipetting loss.

---

## Appendix B: Preventing and Managing Sticking of Organoids

Organoids may sometimes stick to each other or adhere to the dish walls. Below are practical tips for prevention and remediation:

### B.1 Preventive Measures

1. **Optimize Seeding Density:**
   - Avoid over-seeding dishes such that large numbers of organoids end up in close proximity.
   - Excessively high density promotes fusion and sticking.
   - To prevent overcrowding, sticking and ensure adequate nutrient supply, limit cultivation to a maximum of 16 organoids per 60 mm Petri dish.

2. **Proper Embedding:**
   - Press Gently: Use moderate force when pressing Parafilm over the tip rack. Excessive indentation can result in lumps or ridges.
   - Check for Bumps: Inspect dimples for an even, shallow shape to ensure a smooth Matrigel droplet later on.
   - Irregular Matrigel surfaces can trap organoids in ridges or corners, raising the risk of sticking and making it harder to properly embed each organoid.
   - Allowing Matrigel to polymerize for longer than 30 minutes during embedding can reduce the overall adhesivity around organoids.
   - Conversely, prematurely transferring organoids after a very short solidification period (e.g., <15 minutes) may leave the Matrigel too soft, increasing the risk of fusion or sticking.

3. **Gentle Orbital Shaking:**
   - Keep organoids in constant, slow motion (e.g., 65 rpm) to reduce the likelihood of them settling and sticking to each other or the surface.
   - Confirm that the shaker is level and the speed is correct; too slow may allow settling, while too fast can induce shear stress.

4. **Regular Medium Changes:**
   - Replace medium on schedule (every 2–3 days, depending on the protocol stage) to remove debris and cell clumps that can promote sticking.
   - During medium changes, swirl the dish gently before aspiration so that organoids gather away from the edges.

5. **Use of Wide-Bore Pipette Tips:**
   - When transferring organoids, always use cut or wide-bore tips to reduce mechanical damage that creates sticky debris.
   - Slow pipetting helps avoid pushing organoids together.

---

### B.2 Managing Stuck or Fused Organoids

1. **Separation:**
   - Initial Swirl: Gently swirl or tilt the dish to see if the organoids will naturally separate from each other or from the dish surface.
   - Aspirate and Dispense: If they remain fused, use a pipette (preferably with a wide-bore or cut tip) to aspirate and dispense medium directly onto the fusion point.
   - Use Minimal Force: Apply gentle pressure to avoid creating a high-flow jet that could damage the organoids.

2. **Lower the Culture Density:**
   - If fusion is frequent, reduce the total number of organoids per dish or well.
   - Splitting a heavily populated plate into two plates can alleviate crowding.

---

### B.3 Additional Tips

1. **Frequent Monitoring:**
   - Check the cultures daily, at least briefly, to catch early signs of sticking or fusion.
   - Early intervention (e.g., gently separating partially fused organoids) is less damaging than dealing with a large fused cluster.

2. **Record Keeping:**
   - Maintain detailed notes of any sticking or fusion events, and any corrective actions taken.
   - This log helps troubleshoot future occurrences by revealing patterns or batch-specific issues.

**Final Note:**  
Implementing these preventive measures and gentle mechanical interventions early usually resolves mild sticking or fusion.

---

## Image Gallery

This gallery showcases the photographs captured during the generation of cerebral organoids using the protocol outlined above. Each image is organized chronologically and corresponds to specific stages in the protocol.

### C.1 Seeding for Embryoid Body Formation

![Figure 7: Large and healthy iPSC colonies prepared for EB formation on November 17, 2024.](path/to/image)

### C.2 Embryoid Body Formation

- (a) EB (2 dps) on November 19, 2024.
- (b) EB (3 dps) on November 20, 2024.
- (c) EB (5 dps) on November 22, 2024.
- (d) EB (6 dps) on November 23, 2024.

![Figure 8: Morphology of EBs.](path/to/image)

### C.3 Embedded Organoid Development

- (a) Early Embedding (8 dps) on November 25, 2024.
- (b) Late Embedding (9 dps) on November 26, 2024.

![Figure 9: Morphology of Organoids.](path/to/image)

### C.4 Organoid Maturation

- (a) Organoid (11 dps) of E8 on November 28, 2024.
- (b) Organoid (11 dps) of E9 on November 28, 2024.

![Figure 10: Morphology of Organoids.](path/to/image)

### C.5 Plate 1: Early Embedding (8 dps) and Early Vitamin A Addition (14 dps)

- (a) Sample p1-3.1
- (b) Sample p1-5.2

![Figure 11: Early Embedding and Early Vitamin A Addition Organoids – 26 dps; December 13, 20224 (Collected on December 16, 2024).](path/to/image)

### C.6 Plate 2: Early Embedding (8 dps) and Early Vitamin A Addition (14 dps)

- (a) Sample p2-3.1
- (b) Sample p2-4.2

![Figure 12: Early Embedding and Early Vitamin A Addition Organoids – 26 dps; December 13, 2024 (Collected on December 16, 2024).](path/to/image)

### C.7 Plate 3: Late Embedding (9 dps) and Late Vitamin A Addition (15 dps)

- (a) Sample p3-2.2
- (b) Sample p3-3.2

![Figure 13: Late Embedding and Late Vitamin A Addition Organoids – 26 dps; December 13, 2024 (Collected on December 16, 2024).](path/to/image)