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

| Platform | Description | Pricing (Starting Tier) | Free Tier / Trial Limit |
| :--- | :--- | :--- | :--- |
| **[PostDICOM](https://www.postdicom.com/)** | Cloud-native PACS and RIS platform with web-based HTML5 diagnostic DICOM viewer, multi-modality routing, and reporting worklists. | Starts at **$79/month** (Essential tier; includes 50 GB cloud storage, HTML5 diagnostic viewer, 1 user; or $948/year) | **7-day free trial** (up to 50 GB cloud storage, full diagnostic viewer and plan features; auto-renews unless cancelled) |
| **[SonicDICOM Cloud PACS](https://sonicdicom.com/)** | Web-based Cloud PACS and medical imaging platform offering DICOM archive, zero-footprint web viewer, and modality integration. | Starts at **$39/month** (Basic Plan; monthly or annual subscription) | **14-day free trial** (full access to Cloud PACS features, web viewer, and storage) |
| **[CrelioHealth PACS](https://creliohealth.com/radiology/pacs/pacs-system/)** | Cloud radiology information and reporting platform with integrated PACS, diagnostic worklists, and multi-center workflow orchestration. | Starts at **$50/month** minimum commitment ($0.01/study for X-Ray/USG, $0.04/study for MRI, $0.08/study for CT-Scan) | **14-day free trial** (guided interactive demo sandbox with full reporting workflow and worklist automation) |
| **[Medicai](https://medicai.io/)** | Collaborative cloud PACS and radiology workflow infrastructure with browser-based DICOM viewer, patient/doctor portal, and cloud archive. | Starts at **$249/month** ($209/month billed annually; Starter tier with 500 GB storage and unlimited users) | **14-day free trial** (500 GB storage, unlimited user accounts); Free tier: browser DICOM viewer only (0 GB cloud storage, no account required) |
| **[Tricefy](https://triceimaging.com/)** | Cloud-hosted medical imaging platform providing zero-footprint DICOM viewing, mobile image routing, patient sharing, and reporting. | Starts at **$42/month** ($500/year billed annually) or $749/month (Standard tier with 2 TB storage) | **30-day free trial** (full access to cloud archive, diagnostic viewing, and mobile image routing) |
| **[Softneta MedDream](https://www.softneta.com/products/medical-imaging/meddream-dicom-viewer/)** | FDA-cleared and CE-certified HTML5 web-based DICOM viewer and web-PACS engine designed for integration with RIS, HIS, and EHR. | Starts at **~$130/user/month** (£1,200/user/year for commercial license tier) | **45-day trial license** (fully functional diagnostic toolset and integration APIs); permanent live online browser demo sandbox |
| **[OnePacs](https://onepacs.com/)** | Cloud teleradiology and outpatient RIS/PACS platform featuring structured reporting, worklist orchestration, and integrated web viewer. | Starts at **$200/month** (minimum platform subscription tier with volume-tiered study routing) | Free courtesy tier for testing/research (up to **10 studies/month**); **30-day free trial** for imaging practices |
| **[RamSoft (OmegaAI)](https://www.ramsoft.com/)** | Cloud-native imaging EMR and RIS/PACS platform offering automated scheduling, unified worklists, and progressive image streaming. | Starts at **$800/month** minimum commitment (~$1.50 per study, includes unlimited users and facilities) | **30-day free trial** (guided proof-of-concept pilot and sandbox access to full cloud RIS/PACS workflow) |
| **[Ambra Health (Intelerad)](https://www.ambrahealth.com/)** | Cloud enterprise imaging suite and medical image management platform with teleradiology worklists, DICOM routing, and EHR integration. | Starts at **$500/month** (base tier for outpatient clinics and single-site imaging centers) | **30-day free trial** (guided cloud sandbox with full access to image exchange and diagnostic viewing) |
| **[Novarad (NovaRIS)](https://www.novarad.net/novaris-radiology-information-system)** | Integrated radiology information system and PACS platform offering patient tracking, custom report generation, and turnkey image archiving. | Starts at **$400/month** (turnkey subscription / Evergreen service contract for single imaging facility) | **30-day free trial** (guided pilot sandbox for workflow evaluation upon qualification) |
| **[MedicsRIS (Advanced Data Systems)](https://www.adsc.com/radiology-information-system-medicsris)** | Comprehensive radiology information system featuring intelligent patient scheduling, insurance verification, and automated reporting. | Starts at **$500/month** (entry tier for single practitioner / 1 user seat) | **14-day free trial** (guided sandbox demo with full access to scheduling, reporting, and PACS integration) |
| **[GE HealthCare (Edison True PACS & RIS)](https://www.gehealthcare.com/)** | Cloud-enabled radiology PACS and workflow orchestration platform designed for outpatient clinics, diagnostic centers, and hospital imaging. | Starts at **$500/month** (entry cloud subscription tier for small imaging practices) | **30-day free trial** (guided proof-of-concept deployment with full clinical workflow features) |
| **[Philips IntelliSpace / HealthSuite Imaging](https://www.philips.com/)** | Enterprise imaging platform featuring cloud-based radiology informatics, advanced visualization, and integrated clinical workflows. | Starts at **$1,200/month** (base cloud subscription tier for diagnostic imaging departments) | **30-day free trial** (guided evaluation pilot in cloud sandbox with synthetic clinical datasets) |
| **[Fujifilm Synapse](https://www.fujifilm.com/)** | Enterprise imaging and VNA-oriented platform providing robust RIS/PACS integration, server-side rendering, and multi-department support. | Starts at **$1,000/month** (base cloud-managed service agreement for imaging practices) | **30-day free trial** (guided clinical evaluation trial with workflow testing and modality connectivity) |
| **[Sectra Workstation & PACS](https://sectra.com/)** | Best-in-KLAS enterprise imaging and RIS/PACS platform recognized for radiology reporting, high reliability, and multi-specialty workflows. | Starts at **$1,500/month** (Sectra One Cloud entry subscription tier for departmental imaging centers) | **30-day free trial** (proof-of-concept evaluation sandbox with simulated clinical workflow) |
| **[Visage Imaging (Visage 7)](https://visageimaging.com/)** | High-performance enterprise imaging platform utilizing server-side rendering for ultra-fast streaming of large radiology datasets. | Starts at **$1,000/month** (base cloud instance license tier for imaging centers) | **30-day free trial** (cloud proof-of-concept deployment with full viewer features) |
| **[Carestream (Vue RIS/PACS)](https://www.carestream.com/)** | Web-enabled RIS and PACS solution offering automated worklists, diagnostic reporting, and centralized departmental image management. | Starts at **$750/month** (entry cloud-hosted eHealth services subscription tier) | **30-day free trial** (guided sandbox demo with access to Vue reporting and worklist modules) |



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
