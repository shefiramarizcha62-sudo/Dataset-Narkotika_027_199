# NARCO-IR
### Indonesian Narcotics Court Decision Dataset

<p align="center">
  <strong>A Collection of Indonesian Narcotics Court Decisions for Information Retrieval Research</strong>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Domain-Legal%20Documents-blue">
  <img src="https://img.shields.io/badge/Category-Narcotics-red">
  <img src="https://img.shields.io/badge/Format-PDF%20%7C%20XLSX-green">
  <img src="https://img.shields.io/badge/Project-Academic-orange">
</p>

---

## About NARCO-IR

NARCO-IR (Narcotics Information Retrieval) is a curated collection of Indonesian court decision documents related to narcotics offenses.

This repository is developed as part of the Information Retrieval course project. It aims to provide structured legal documents that can be used for document processing, metadata analysis, indexing, and information retrieval research.

The dataset consists of court decisions obtained from the official Indonesian Supreme Court Decision Directory.

## Dataset Overview

The dataset focuses on criminal cases involving narcotics and psychotropic substances.

| Attribute | Description |
|---|---|
| Document Domain | Legal Documents |
| Case Classification | Special Criminal – Narcotics and Psychotropic Substances |
| Jurisdiction | Indonesia |
| Court Level | District Court (Pengadilan Negeri) |
| Court | Pengadilan Negeri Surabaya |
| Collection Method | Manual Document Acquisition |
| Document Format | PDF |
| Metadata Format | XLSX |
| Source | Supreme Court Decision Directory |

### Dataset Scope

The initial collection contains 6 manually acquired court decisions.

Additional documents collected through the crawling process will be documented separately when available.

## Dataset Collection

Court decision documents are collected from the official [Supreme Court Decision Directory](https://putusan3.mahkamahagung.go.id/direktori.html).

The manual acquisition process follows these criteria:

- Directory: Special Criminal Cases (Pidana Khusus).
- Classification: Narcotics and Psychotropic Substances.
- Court: Pengadilan Negeri Surabaya.
- Recommended publication period: 2023–2025.
- Case status: Decisions that are not classified as legally binding (Berkekuatan Hukum Tetap/BHT), according to the assignment requirements.

Each document is reviewed to identify relevant case information, evidence, and court decisions.

## Repository Structure

```text
Narcotics-Judgment-Dataset/
│
├── Dataset/
│   └── Narkotika.zip
│
├── Overview/
│   └── Overview.xlsx
│
└── README.md
```

### Directory Description

| Directory/File | Description |
|---|---|
| `Dataset/` | Contains the collected court decision documents. |
| `Narkotika.zip` | Compressed archive of PDF court decisions. |
| `Overview/` | Contains structured summaries of the collected documents. |
| `Overview.xlsx` | Spreadsheet containing court decision metadata, evidence, and verdict summaries. |
| `README.md` | Project documentation. |

## Metadata Schema

The `Overview.xlsx` file provides a structured summary of each court decision.

| Field | Description |
|---|---|
| No. | Sequential document number. |
| No Putusan | Official court decision number. |
| Lembaga Peradilan | Name of the issuing court. |
| Barang Bukti | Description of evidence presented in the case. |
| Amar Putusan | Final ruling or decision issued by the court. |

## Usage

To access the dataset:

1. Clone or download this repository.
2. Navigate to the `Dataset/` directory.
3. Download and extract `Narkotika.zip` to access the PDF documents.
4. Open `Overview/Overview.xlsx` to review the corresponding metadata and decision summaries.

The dataset can be used for academic activities involving:

- Legal document analysis.
- PDF text extraction and preprocessing.
- Metadata identification and structuring.
- Document indexing.
- Information retrieval and legal document search.

## Contributors

This project is maintained by the following contributors:

| Name | Student ID | Role |
|---|---|---|
| Shefira Marizcha | 202310370311027 | Data Collection and Documentation |
| Ridha Dewi Safirah | 202310370311199 | Data Collection and Metadata Structuring |

## References

- [Direktori Putusan Mahkamah Agung Republik Indonesia](https://putusan3.mahkamahagung.go.id/direktori.html)

## Disclaimer

This repository is intended for academic and research purposes. The court decision documents are sourced from the official Supreme Court Decision Directory.

Users should refer to the original source documents for authoritative legal information. This repository does not modify or replace the original court decisions.
