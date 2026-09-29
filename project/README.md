# Proiect: Dezvoltarea Aplicațiilor Web (#WADe)

Acest director conține cerințele generale, calendarul de livrabile și propunerile de proiecte pentru disciplina **Web Application Development**.

---

## 1. Documente de Referință

- [web-projects.html](web-projects.html) – Cerințe tehnice generale, arhitectură, livrabile, calendar de evaluare și bonusuri.
- [projects_index.html](projects_index.html) – Lista detaliată a temelor de proiect propuse pentru anul curent.

---

## 2. Teme de Proiect Propuse

### 1. DiO (Distributed System Ontology)
- **Obiectiv:** Dezvoltarea unui sistem Web bazat pe o ontologie specifică pentru modelarea, navigarea și căutarea conceptelor din domeniul sistemelor distribuite (consensus, replication, partition tolerance, RPC, event-driven architecture etc.).
- **Componente:** Ontologie OWL/RDFS, endpoint SPARQL, interfață Web interactivă, vizualizarea grafului de cunoștințe și API REST/GraphQL.

### 2. kro (Artwork Provenance)
- **Obiectiv:** O platformă Web pentru gestionarea și urmărirea provenienței operelor de artă (istoric de proprietate, transferuri, restaurări, licitații, autenticitate), utilizând modelare Linked Data și vocabulare standard (CIDOC-CRM, Getty Vocabularies, PROV-O).
- **Componente:** Adnotare semantică, validare SHACL, căutare fațetată și integrare cu seturi de date deschise din patrimoniul cultural.

### 3. WAS (Web Application Security Control)
- **Obiectiv:** O aplicație Web pentru auditul și controlul securității aplicațiilor Web, corelând vulnerabilități cunoscute (CWE, CVE, OWASP Top 10) prin modelare semantică (ontologii de securitate) și inferență automată a riscurilor.
- **Componente:** Modul de analiză/verificare, raționament OWL DL pentru detectarea dependențelor vulnerabile, dashboard explicativ și recomandări automate de remediere.

---

## 3. Livrabile & Calendar

1. **Etapa 1 (Săptămâna 8):**
   - Schiță de arhitectură software (C4 model / diagrame de componente).
   - Documentație preliminară în format [Scholarly HTML](https://w3c.github.io/scholarly-html/).
   - Modelul conceptual preliminar (ontologie OWL / schemă RDF).
2. **Etapa 2 (Săptămâna 14):**
   - Aplicația complet funcțională cu cod sursă deschis pe GitHub.
   - Endpoint SPARQL și API expus conform cerințelor.
   - Raportul final de arhitectură și specificație tehnică.
   - Demonstrație video / prezentare live conform programării.
