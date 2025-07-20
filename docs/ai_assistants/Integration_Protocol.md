# AI Integration Protocol  
**Structured Emersion Theory – Canonical Validation Workflow**  
**Last Updated:** 2025-07-19

This document defines how any AI system must process, validate, and integrate new content into the Structured Emersion Theory (SET) GitHub Pages repository.

---

## 🧠 Canon Enforcement

All content must be checked against the canonical documents listed here:  
> https://structured-emersion-theory.github.io/Structured-Emersion-Theory/ai_assistants/Canonical_Index/

Only the files explicitly linked in that index may be used. No training data, external search, or internal memory is considered authoritative.

---

## ✅ Required Phases

### 🔁 Phase 1: File Audit

- **Intent Check** – What is the file trying to define?  
- **Glossary Extraction** – Identify all key terms  
- **Equation Detection** – Log any mathematical logic  
- **Destination Guess** – Predict if file belongs in `/core/`, `/modules/`, `/sim/`, or `/archive/`

---

### 🔁 Phase 2: Canon Validation

- **Glossary Check** – Must match `Glossary.md` or be logged in `Glossary_Candidates.md`  
- **Law Check** – Must match `Laws_of_Structure.md` exactly, or be logged as a candidate  
- **Equation Check** – Must be present in `Equations.md` or logged in `equation_candidates.md`  
- **Structural Logic Scan** – Validate against tempo, resistance, coherence, and activation logic  
- **Conflict Logging** – Log refinements or contradictions in the candidate logs

---

### 🔁 Phase 3: GitHub Readiness

- **Markdown Cleanup** – Remove informal phrasing, broken headers  
- **Canon Tagging** – Use `Law:XYZ` tags  
- **File Assignment** – Route to correct subfolder (`core/`, `workbench/`, etc.)  
- **Log Candidates** – Glossary, Law, or Equation proposals must be listed in `/candidates_conflicts/`

---

## ⚠️ Link Validation

Before reviewing any content:
- AI must verify that **all linked files in the Canonical Index return HTTP 200 OK**
- If a link is broken or returns 404, content review must halt and log the failure

---

> 🔐 This protocol enforces a single source of truth. No AI system may approve content for canon inclusion without full validation against the live structure.

