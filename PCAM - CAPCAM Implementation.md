# Implementation Progress:
## Downloading Dataset: 
- They have readme and description about them, go through that while making notes about dataset ([CXR8](https://nihcc.app.box.com/v/ChestXray-NIHCC), [CheXpert](https://stanfordaimi.azurewebsites.net/datasets/8cbd9ed4-2eb9-4565-affc-111cf4f7ebe2))
- **NOTE:** CheXpert is used for external testing, you only need NIH chest X rays dataset for now  

## Two different Models:
| Repository | Role |
|---|---|
| [CX-Ultranet](https://github.com/labsroy007/CX-Ultranet) | The chest X-ray **classifier and feature extractor** used as CAPCAM’s backbone. |
| [Confidence-Aware-PCAM](https://github.com/bad-eastwind/Confidence-Aware-PCAM) | Code associated with the **CAPCAM method**, which adds PCAM pooling and the paper’s anomaly and confidence components to the backbone. |

## P Utkarsh Repo Structure
```
/home/aadeshk/projects/capcam-replication/
├── repos/        # The two GitHub repositories, kept as separate checkouts
├── configs/      # Environment specification and experiment settings
├── manifests/    # Exact image IDs, splits, file inventory and checksums
├── scripts/      # Our setup, validation and Slurm job scripts
└── notes/        # Paper-to-code discrepancies and decisions
```
