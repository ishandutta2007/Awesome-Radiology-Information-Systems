# Awesome-Radiology-Information-Systems

## Top Radiology Information Systems Ecosystem



**Curated List of SaaS Products & Open-Source GitHub Projects**  

*Focused on RIS, Radiology Workflow, Scheduling, Reporting, Worklist Management, PACS Integration & Imaging Operations*  

**Last updated: September 2026**



This repository tracks notable **SaaS/commercial platforms** and **open-source projects** for **Radiology Information Systems (RIS)**. These systems manage the administrative and clinical workflow of radiology departments—including patient scheduling, modality worklists, reporting, results distribution, billing integration, and close coupling with PACS and imaging viewers.



**Examples** include RamSoft, Intelerad, Merge Imaging, Novarad, Carestream, Visage Imaging, Sectra, Philips IntelliSpace, Fuji Synapse, and GE Centricity RIS (the category leaders).



**Open-source emphasis**: Full enterprise RIS platforms with deep EHR/PACS integration, regulatory compliance, and large-scale workflow orchestration are predominantly commercial. Open-source activity includes dedicated RIS projects (**Sirius RIS**, **KloudRIS**), academic implementations, DICOM/PACS foundations (**Orthanc**), and web viewers (**OHIF**). This section lists every significant relevant project found.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [SaaS/Hosted Platforms](#saas-hosted-platforms)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms



- **[RamSoft (OmegaAI)](https://www.ramsoft.com/)**  

  Cloud-native RIS/PACS platform with progressive loading, reporting, analytics, and patient engagement features aimed at imaging centers and radiology groups.



- **[Intelerad](https://www.intelerad.com/)**  

  Enterprise imaging and RIS solutions focused on distributed radiology, image exchange, workflow orchestration, and cloud-enabled collaboration.



- **[Sectra](https://sectra.com/)**  

  Highly regarded enterprise imaging and RIS/PACS platform known for radiology, breast imaging, and multi-specialty workflows; frequent Best in KLAS recognition.



- **[GE HealthCare (Centricity / True PACS & RIS)](https://www.gehealthcare.com/)**  

  Widely deployed RIS and PACS solutions with a large installed base, supporting high-volume hospital and multi-site radiology operations.



- **[Philips IntelliSpace / HealthSuite Imaging](https://www.philips.com/)**  

  Enterprise imaging platform including RIS capabilities, advanced visualization, and cloud offerings for radiology departments.



- **[Fujifilm Synapse](https://www.fujifilm.com/)**  

  Enterprise imaging and VNA-oriented platform with strong RIS/PACS integration and multi-department support.



- **[Visage Imaging, Carestream, Novarad, Merge](https://visageimaging.com/)**  

  Specialized imaging and RIS/PACS vendors offering viewers, workflow tools, and departmental or enterprise solutions.



- **[Other RIS & enterprise imaging platforms](https://www.ramsoft.com/)**  

  Additional commercial systems covering teleradiology, AI-assisted reporting, and integrated radiology operations.



## Open-Source GitHub Projects



- **[Sirius RIS](https://github.com/opendicom/sirius-ris)**  

  Open-source radiological information system built with modern web technologies (Angular, Node.js, MongoDB). Supports multi-language, worklists, DICOM integration, and is designed for clinical use alongside open PACS components.



- **[KloudRIS](https://github.com/KloudMedical/KloudRIS)**  

  Open-source, multi-tenant, web-based outpatient RIS and practice management solution aimed at managing the full radiology workflow from a browser.



- **[Orthanc](https://www.orthanc-server.com/)**  

  Lightweight, open-source DICOM server / PACS that serves as a foundational building block for many open imaging and RIS workflows.



- **[OHIF Viewer](https://github.com/OHIF/Viewers)**  

  Leading open-source web-based medical imaging viewer frequently paired with open RIS and PACS systems for diagnostic review.



- **[Academic & research RIS implementations](https://github.com/search?q=Radiology+Information+System+OR+RIS+DICOM)**  

  University and research projects implementing core RIS functions (worklists, reporting, patient tracking, HL7/DICOM communication).



- **[PACS/RIS crawlers & research tools](https://github.com/pacs-ris-crawler/pacs-ris-crawler)**  

  Tools for searching, indexing, and extracting data from PACS and RIS systems to support research and secondary use.



- **[DICOM & HL7 open-source stacks](https://github.com/search?q=DICOM+OR+HL7+OR+MWL+open+source)**  

  Libraries and servers for modality worklists, image routing, and healthcare messaging that underpin custom RIS solutions.



- **[Other open imaging workflow projects](https://github.com/search?q=open+source+RIS+OR+radiology+workflow)**  

  Emerging community efforts around reporting, scheduling, and radiology operations.



### Additional Strong Open-Source Options



- **DCM4CHE / dcm4che toolkit**: Java-based DICOM and IHE tools widely used in open imaging infrastructures.

- **Weasis / other open viewers**: Alternative diagnostic and clinical viewers.

- **HL7 interface engines**: Mirth Connect (next-gen community editions) or similar for integrating RIS with EHR and billing.

- **Reporting templates & structured reporting**: Open tools for radiology report generation and NLP-assisted drafting.

- **Research data pipelines**: Projects that de-identify and extract imaging + RIS data for AI and analytics.

- Containerized deployments (Docker/Kubernetes) of Orthanc + OHIF + custom RIS front-ends.



**Frameworks for building custom systems**:  

A practical open-source stack often combines **Sirius RIS** or **KloudRIS** (or a custom web RIS) with **Orthanc** as the PACS archive and **OHIF** as the viewer.  

Add HL7/DICOM modality worklist services and an interface engine for EHR integration.  

Commercial RIS platforms (RamSoft, Intelerad, Sectra, GE, Philips, Fuji, etc.) provide mature workflow engines, regulatory support, advanced reporting, analytics, and vendor-backed service that most open-source assemblies still require significant clinical IT effort to match.  

Many academic centers and smaller practices successfully run hybrid environments using open PACS/viewers alongside commercial or custom RIS components.



## How to Contribute



1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer



- This is a **community-curated** list — not exhaustive and not an endorsement.

- Radiology Information Systems handle protected health information (PHI), diagnostic workflows, and patient safety–critical processes. Any system must meet applicable regulatory requirements (HIPAA, GDPR, local medical device and data-protection rules) and undergo proper clinical validation.

- Open-source RIS and imaging tools offer transparency and flexibility but require expertise in healthcare IT, DICOM/HL7, security hardening, backup, and ongoing maintenance. They are not automatically equivalent to certified commercial platforms for production clinical use. Operators remain fully responsible for compliance, reliability, and patient safety.



---



**Made for radiology administrators, imaging IT teams, radiologists, PACS administrators, and healthcare technologists.**  

Let's expand open, interoperable tools for radiology workflows while recognizing the essential role of mature commercial RIS and enterprise imaging platforms.
