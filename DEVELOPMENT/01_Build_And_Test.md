# Build and Test

**Project:** `HI_ML`
**Upstream:** https://github.com/microsoft/hi-ml
**License:** MIT

## Quick Start

```bash
git clone https://github.com/microsoft/hi-ml
cd hi-ml
pip install -r requirements-anticloud.txt
python anticloud_main.py --offline --pax-local
```

## Anticloud Improvements Applied

1. PAX L5 Narrow L2 General 27B local clinical decision support — air-gapped hospital deployment
2. AIOSS tamper-evident EHR audit chain (HL7 FHIR event log)
3. AES-256 encryption for all patient data at rest and in transit
4. Single-binary deployment on clinical workstations
5. HIPAA-compliant zero-cloud architecture
6. Offline diagnostic inference: image analysis, lab result interpretation
7. GPU/CPU equalizer: runs on clinical GPU workstation or standard CPU server
8. Open CLI for EHR integration replacing proprietary HL7 middleware

## Benchmark Targets

| Metric | Target |
| --- | --- |
| Latency | Clinical NLP inference: <2s per document |
| Throughput | 200 patient records processed/hour |
| Memory | <16GB clinical workstation RAM |
| Accuracy | ICD-10 coding accuracy >95% vs human baseline |

## Build Status

Not yet measured. Run verified build and record actual figures above.
