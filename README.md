# Hi, I'm Aastha Thakkar! 👋
CSE Student at IIIT Vadodara, Gujarat, India 🇮🇳

I'm interested in backend engineering, healthcare data systems, and open source development.

## 🏥 GSoC 2026 — Alaska / Diomede Project

Currently contributing to **KathiraveluLab/Diomede** for GSoC 2026. Building a pipeline for creating shareable albums from locally stored DICOM medical images (Project #13), with a focus on consuming Niffler's existing metadata extraction pipeline rather than reimplementing it.

| PR | Description | Tests |
|---|---|---|
| **#132** | Niffler-consuming album indexer — `POST /index-from-niffler`, generator-based CSV streaming, memory-efficient batch DB queries, path traversal protection (CWE-22) | 18 |

### What I built in PR #132
- Reads Niffler's CSV output and feeds it into the album index pipeline
- Generator-based processing for memory-efficient handling of large DICOM datasets (10,000×10,000 scale)
- Batched SQLite queries using `IN` operator to avoid loading all paths into memory
- Path traversal security using `os.path.normpath` + `os.path.commonpath`
- Flask REST endpoint that integrates cleanly with the existing `DICOMAlbumCreator` pipeline

## 🛠️ Skills

- **Languages:** Python, C, C++
- **Frameworks:** Flask, pandas, SQLAlchemy, numpy, Node.js, Express.js
- **Tools:** pydicom, pytest, Git, SQLite
- **Domains:** Backend APIs, Medical Imaging (DICOM), Open Source

## 📍 Find me

- **GitHub:** [@aasthathakkar](https://github.com/aasthathakkar)
- **Location:** Gandhinagar, Gujarat, India (IST — UTC+5:30)
  
