
# SET Canon Integration Protocol

This protocol defines the official checklist used to verify, scrub, and integrate any file into the Structured Emersion Theory (SET) repository.

---

## ✅ Phase 1 – File Audit

1. **Intent Check**  
   What is the purpose of the file?  
   - Theory explanation  
   - Equation development  
   - Simulation logic  
   - Glossary definition  
   - White paper or reference  

2. **Term Extraction**  
   - Identify all new terminology, including invented phrases or symbolic labels  
   - Flag terms not yet listed in `Glossary.md`  

3. **Equation Detection**  
   - Check for mathematical statements  
   - Ensure equations match existing entries in `Equations.md`  
   - If not present but needed, propose addition to `equation_candidates.md`

---

## 🔁 Phase 2 – Canon Validation

4. **Law Reference Check**  
   - Ensure all referenced laws match `Laws_of_Structure.md`  
   - Remove or rewrite deprecated law names  
   - If a behavior implies a new law, propose it to `law_candidates.md`  

5. **Glossary Compliance**  
   - All unique terms must either:
     - Exist in `Glossary.md`, or  
     - Be proposed for inclusion with definition  

6. **Structural Logic Scan**  
   - Validate that document logic does not violate any confirmed law  
   - Refactor text if internal contradiction is found  
   - Annotate clearly where behavior supports or emerges from a law  

---

## 🔄 Phase 3 – GitHub Readiness

7. **Rewrite & Reformat**  
   - Remove informal tone or speculative draft phrasing  
   - Use consistent markdown formatting (headings, spacing, etc.)  

8. **Folder Placement**  
   - `/docs/Workbench/`: Experimental or under review  
   - `/docs/`: Confirmed reference material  
   - `/modules/`: Core theoretical content  
   - `/sim/`: Simulation engines or logic rules  

9. **Canon Tagging**  
   - Annotate file with all law references used  
   - Add `[Canonical]` tag to header if the file passes all validation  

---

## 🧠 Ongoing Candidate Logs

Use the following files to track emerging theory:
- `law_candidates.md` — Proposed additions to the Laws of Structure  
- `equation_candidates.md` — Proposed equations pending formal review  

---

_This document governs structural integrity for all contributions to SET._
