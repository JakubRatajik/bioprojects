# Systems Biology – Boolean Modeling of Immune Response and Gene Enrichment Analysis in Viral Infection

Download the **Boolean model** of **signaling pathways** that control the **immune response of a cell** depending on the presence of **interferons in the extracellular environment**.  

The model was **machine-generated** from an **SBGN diagram** using **CaSQ** (the original model in **CellDesigner** is available here: **Interferon1_stable.xml** or via **FAIRDOMhub** at [this link](https://fairdomhub.org/models/713)).  

#### **Task Instructions**  

1. **Import** the model into the **AEON tool**, apply **layout settings**, and visually **identify**:  
   - **Input nodes** for two considered **drugs** (**Azithromycin, GRL0617**)  
   - **Input phenotype** for **viral replication**  
   - **Output nodes** for **monitored biological phenotypes**  
   
2. **Connect the produced interferons** with the corresponding **input variables** (creating a **positive feedback loop**).  

3. **Consider two scenarios for viral protein input variables:**  
   - **All viral proteins set to "true"** (the **virus is physically present** inside the cell).  
   - **All viral proteins set to "false"** (the **virus is not present** inside the cell).  

4. **Run attractor analysis** in **AEON**. The tool will provide an **example attractor** for each **identified attractor class**. Focus on cases where the **inflammatory phenotype** is **activated**. Summarize the results for each input variable setting in a **PDF report**.  

5. **For each variant**, select one **attractor** (at your discretion) that includes an **active inflammation phenotype** and perform a **gene enrichment analysis** for **human cell genes** that are **stably expressed** in that attractor. Conduct the analysis in **Gene Ontology (GO)** and document the findings for each variant in the **PDF report**.  
