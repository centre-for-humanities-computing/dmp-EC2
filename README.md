# EC2 Data Management Plan

# EuropeanCity² (EC2) Data Management Plan

This repository contains the living Data Management Plan (DMP) and structured data specifications for the Horizon Europe project **EuropeanCity² (EC2)**. The project explores new computational methods for democratic innovation, including agent-based and quantum voting simulations, grounded in the FAIR data principles.

## 📁 Repository Structure

```
.
├── README.md                       # This file
├── data-specification             # Structured metadata for EC2 datasets
│   ├── README.md                  # Metadata schema and usage overview
│   ├── data-access-control.csv    # Who has access to which data
│   ├── data-archiving.csv         # Where and how datasets are archived
│   ├── data-collections.csv       # List and properties of datasets
│   ├── data-event-log.csv         # Log of data-related project events
│   ├── data-provenance.csv        # Legal basis, source, and generation context
│   ├── data-systems.csv           # Infrastructure used for storage and compute
│   ├── data_set-format_provenance
│   │   ├── <dataset>_format.md       # Format specification per dataset
│   │   └── <dataset>_provenance.md   # Provenance file per dataset
│   └── org-data-access-control.csv # Inter-organizational sharing records
└── horizon_template_v1_ec2.md    # Formal DMP document
```

## 📄 Key Files

- **`horizon_template_v1_ec2.md`** — The current Horizon Europe-compliant Data Management Plan.
- **`data-specification/`** — All metadata about EC2 datasets, access, provenance, and infrastructure.
- **`data_set-format_provenance/`** — Per-dataset format and provenance documentation in markdown.

## 🔁 Versioning

This repository is version-controlled using Git. Formal DMP versions are tagged (e.g. `v1.0`, `v1.1`) and linked to publication milestones in the project.

## 📜 License

All non-sensitive metadata and documentation are provided under the **Creative Commons Attribution 4.0 International (CC BY 4.0)** license.

## 🔗 Related Resources

- Project website: _TBD_
- Zenodo archive (when published): _TBD_
- GitHub issues and pull requests are used for change tracking and review.

---

Maintained by [Centre for Humanities Computing, Aarhus University](https://chc.au.dk).