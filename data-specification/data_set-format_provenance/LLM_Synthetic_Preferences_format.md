# Data Format: LLM_Synthetic_Preferences

## Description

This dataset contains synthetic preference profiles generated using a fine-tuned version of the Llama 3.3 70B instruct model. The profiles are derived from domain-relevant input prompts seeded from deliberative texts and simulated civic discussions.

## Structure

Each record in the dataset represents one agent's synthetic preference structure and includes the following fields:

| Field            | Type    | Description                                                             |
|------------------|---------|-------------------------------------------------------------------------|
| `agent_id`       | string  | Unique identifier for the synthetic agent                               |
| `timestamp`      | string  | ISO 8601 timestamp of data generation                                   |
| `input_context`  | string  | Prompt or source context used to seed the LLM                          |
| `preferences`    | object  | Dictionary of preference dimensions and associated intensity scores     |
| `metadata`       | object  | Includes generation parameters, temperature, model version, etc.        |

## Format

- **Primary format:** JSON (UTF-8)
- **Alternate format:** CSV (flattened preferences)

## File Naming Convention

```
llm_synthetic_prefs_YYYYMMDD_batchNN.json
```

## Volume

- Approximately 1,000,000 records
- Estimated size: ~5 GB

## Encoding

- UTF-8 for text
- JSON syntax validation applies

## Versioning

- Model version: Llama 3.3 instruct (70B)
- Data generation scripts are version-controlled in Git (tagged per batch)

## Notes

All records are synthetic and non-identifiable. No human subjects or real personal data are used.
