# Final Project Report Structure

All artifacts referenced in this report must be deployed in the official workshop GitHub organization. Each team will work in a dedicated repository.

---

## Repository Structure (Mandatory)

Each team repository must follow this structure:

```
/docs
    final_report.pdf
    lifecycle_traceability.md
/literature
    search_strategy.md
    literature_table.csv
    extracted_metadata.json
/models
    research_lifecycle_model.png
    conceptual_model.md
/data
    raw/
    processed/
    data_collection_log.md
    entity_list.csv
/knowledge_graph
    adjacency_matrix.csv
    taxonomy_mapping.md
    graph.ttl
/software
    requirements.md
    architecture.md
    src/
    tests/
    README.md
/ai_usage
    prompt_log.md
    ai_decisions.md
```

---

## 1. Introduction

### Purpose
- Introduce the research problem addressed in the workshop  
- State the objective of the project  
- Describe the selected technology domain  

### Required Content
- Research motivation  
- Scope and assumptions  
- Short overview of the lifecycle approach used  

**Artifacts referenced**
- `/software/README.md`

---

## 2. Research Modeling and Literature Study

### 2.1 Research Questions and Modeling Perspective
- Research questions focused on how research is performed and modeled  
- Definition of the research lifecycle under study  

**Artifacts**
- `/models/conceptual_model.md`

---

### 2.2 Literature Search Strategy
- Databases used  
- Search queries  
- Inclusion and exclusion criteria  
- Quality metrics such as venue ranking and citation thresholds  

**Artifacts**
- `/literature/search_strategy.md`

---

### 2.3 Literature Corpus Description
- Overview of selected papers  
- Distribution by venue, year, and citations  

**Artifacts**
- `/literature/literature_table.csv`

---

### 2.4 Document Analysis and Metadata Extraction
- Description of extracted lifecycle phases, activities, inputs, and outputs  
- Role of Generative AI in extraction  
- Verification process  

**Artifacts**
- `/literature/extracted_metadata.json`  
- `/ai_usage/prompt_log.md`

---

### 2.5 Conceptual Research Lifecycle Model and Gap Analysis
- Description of the research lifecycle model derived from the literature  
- Identified gaps and inconsistencies  
- Discussion of modeling decisions  

**Artifacts**
- `/models/research_lifecycle_model.png`

---

## 3. Data Collection Lifecycle

### 3.1 Data Sources and Collection Design
- Description of selected data sources  
- Rationale for source selection  
- Ethical and legal considerations  

**Artifacts**
- `/data/data_collection_log.md`

---

### 3.2 Automated Data Collection Process
- Tools and scripts used  
- Role of GenAI and automation  
- Filtering and normalization steps  

**Artifacts**
- `/data/raw/`  
- `/data/processed/`

---

### 3.3 Entity Extraction and Data Quality
- Entity types and attributes  
- Data quality issues encountered  
- Resolution strategies  

**Artifacts**
- `/data/entity_list.csv`

---

## 4. Knowledge Graph Construction

### 4.1 Domain Modeling and Taxonomy Alignment
- Conceptual model of the selected domain  
- Use of IEEE taxonomy or equivalent  

**Artifacts**
- `/knowledge_graph/taxonomy_mapping.md`

---

### 4.2 Knowledge Graph Design
- Entities and relationships  
- Modeling assumptions  
- Adjacency matrix representation  

**Artifacts**
- `/knowledge_graph/adjacency_matrix.csv`

---

### 4.3 Knowledge Graph Implementation
- TTL serialization process  
- Validation and consistency checks  

**Artifacts**
- `/knowledge_graph/graph.ttl`

---

## 5. Research Software Development

### 5.1 Software Requirements
- Functional requirements  
- Non-functional requirements  
- Traceability to research models and data  

**Artifacts**
- `/software/requirements.md`

---

### 5.2 Architecture and Design
- System architecture  
- Component interactions  
- Conceptual model of the software artifact  

**Artifacts**
- `/software/architecture.md`

---

### 5.3 Implementation
- Description of the recommender system  
- Retrieval and ranking strategy  
- Use of a knowledge graph and a decision model  

**Artifacts**
- `/software/src/`

---

### 5.4 Testing and Validation
- Test strategy  
- Test cases and results  
- Evaluation of recommendation quality  

**Artifacts**
- `/software/tests/`

---

### 5.5 Deployment and Execution
- Execution instructions  
- Environment requirements  
- Reproducibility notes  

**Artifacts**
- `/software/README.md`

---

## 6. Use of Generative AI

### 6.1 GenAI Usage Overview
- Tasks supported by GenAI  
- Rationale for AI usage  

---

### 6.2 Prompt Engineering and Control
- Prompt design strategies  
- Output constraints  
- Human verification process  

**Artifacts**
- `/ai_usage/prompt_log.md`

---

### 6.3 Limitations and Risks
- Errors introduced by GenAI  
- Bias and hallucination risks  
- Mitigation strategies  

**Artifacts**
- `/ai_usage/ai_decisions.md`

---

## 7. Lifecycle Traceability

### 7.1 Traceability Across Phases
- Mapping from literature to conceptual models  
- Mapping from data to knowledge graph  
- Mapping from knowledge graph to software features  

**Artifacts**
- `/docs/lifecycle_traceability.md`

---

### 7.2 Lessons Learned
- Where structure helped  
- Where human judgment was critical  
- Where automation failed  

---

## 8. Discussion
- Strengths of the lifecycle-aware approach  
- Limitations of the project  
- Threats to validity  
- Generalizability of results  

---

## 9. Conclusion and Future Work
- Summary of outcomes  
- Recommendations for improving lifecycle-aware research  
- Possible extensions of the software artifact  

---

## 10. References
- All cited papers  
- Tools and libraries used  
- Taxonomies and datasets referenced  

---

## Certification Requirement

To receive the **Certificate of Completion from Shiraz University**, teams must:

- Submit the final report  
- Deploy all required artifacts in the GitHub organization  
- Pass basic reproducibility checks  
- Demonstrate traceability across lifecycle phases