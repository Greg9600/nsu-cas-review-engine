# README.md

# CAS Admissions Preliminary Review Engine

## Author

Gregory Edwards

## Project Status

Version: v0.1.0

Development Status: Conceptual Architecture and Requirements Definition

Repository Created: June 2026

---

# Overview

The CAS Admissions Preliminary Review Engine is an AI-assisted workflow automation platform designed to streamline the preliminary review process for graduate and professional school admissions applications.

The purpose of the platform is to reduce repetitive administrative workload by automatically extracting, validating, organizing, and evaluating applicant information from centralized application service (CAS) documents prior to human review.

This project is designed as a decision-support system rather than a decision-making system. Human reviewers remain responsible for all final admissions determinations.

---

# Project Goals

The primary goals of this project are:

* Reduce administrative review time.
* Improve consistency of preliminary application review.
* Reduce human error.
* Standardize applicant evaluation workflows.
* Automatically identify complete and incomplete applications.
* Generate structured review reports.
* Provide scalable workflow automation for admissions offices.

---

# Core Features

## Document Processing

* PDF ingestion
* OCR processing
* Text extraction
* Structured data parsing
* Metadata generation

## Applicant Matching

* Applicant identification
* Multi-factor record matching
* Confidence scoring
* Duplicate detection
* Manual review exception handling

## Information Extraction

The system extracts:

* Applicant identifiers
* GPA
* Science GPA
* MCAT scores
* Letters of recommendation
* Evaluator information
* Supplemental materials
* Program-specific requirements

## Rules Engine

The rules engine evaluates:

* Required test scores
* Required letters of recommendation
* Missing documentation
* Incomplete submissions
* Administrative deficiencies
* Program-specific criteria

## Excel Dashboard Generation

The system generates:

* Color-coded review spreadsheets
* Ready-for-review indicators
* Missing requirement alerts
* Manual review flags
* Exception reports
* Administrative dashboards

---

# Planned Workflow

CAS Application PDF

↓

OCR and Document Processing

↓

AI-Assisted Data Extraction

↓

Applicant Matching Engine

↓

Rules-Based Evaluation

↓

Excel Review Dashboard

↓

Human Admissions Review

---

# Technology Stack

## Version Control

* GitHub

## Programming Languages

* Python

## Document Processing

* OCRmyPDF
* PyMuPDF
* Docling
* Marker
* Unstructured

## Artificial Intelligence

* Microsoft Copilot
* Local language models
* Structured extraction pipelines

## Data Processing

* Pandas
* OpenPyXL
* JSON

## Workflow Automation

* Python automation
* GitHub Actions
* Local execution agents

## User Interface

* Microsoft Excel
* Conditional formatting dashboards

---

# Development Roadmap

## Version 0.1

* Repository creation
* Documentation
* Requirements gathering

## Version 0.2

* Excel template creation

## Version 0.3

* PDF ingestion engine

## Version 0.4

* Applicant matching system

## Version 0.5

* AI extraction engine

## Version 0.6

* Rules engine

## Version 0.7

* Dashboard generation

## Version 0.8

* Exception handling

## Version 0.9

* Internal testing

## Version 1.0

* Minimum viable product release

---

# Repository Structure

/
├── docs
├── pdfs
├── extracted_data
├── excel_templates
├── rules
├── scripts
├── models
├── output
├── tests
├── README.md
└── LICENSE

---

# Long-Term Vision

The long-term objective of this project is to develop a scalable admissions workflow automation platform capable of supporting multiple academic institutions and admissions processes while preserving institution-specific review criteria.

This platform is intended to function as an intelligent administrative copilot that augments human expertise, reduces repetitive labor, and improves operational efficiency.

---

Copyright © 2026 Gregory Edwards

All original concepts, architecture, documentation, and implementations contained within this repository are attributed to the repository owner unless otherwise indicated.
