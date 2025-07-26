# AMF-sequences-thesis-2025
This project investigated whether the introduction of intraspecific variation in arbuscular mycorrhizal fungi (AMF) affects a local AMF community. 
Soil samples were collected from three vineyard sites in the Okanagan region of British Columbia, Canada. Soils were pooled and used as growing media in mesocosms containing a mixed plant community.
After a 17 week growing period, samples were taken from each mesocosms and sequenced using a semi-nested appraoch with AMF specific primers.

## Sample Information
- **Land Type:** Agricultural (vineyards)
- **Geographic Region:** Okanagan, Southern British Columbia, Canada  
- **Soil Types (pooled):** Loam and sandy-loam  
- **Sampling Locations:**  
  - Loam: 49°48′22.61″N, 119°30′5.51″W  
  - Sandy-loam: 49°38′42.00″N, 119°44′6.00″W  
  - Loam: 50°52′10.80″N, 119°20′50.40″W  
- **Sample Type:** Soil  
- **Collection Date:** November 10, 2023
  
## DNA Extraction and PCR
- **DNA Extraction:** QIAGEN DNeasy PowerSoil Kit (0.2 g samples)
- **PCR Cleanup Kit:** QIAquick PCR Purification Kit (Qiagen Inc.)  

### Primer Region
- **Targeted Region:** SSU rRNA  
- **Semi-nested PCR:**
  - **Round 1:** AML1 (forward) & AML2 (reverse) — *Lee et al., 2008*  
  - **Round 2:** WANDA (forward) & AML2 (reverse) — *Dumbrell et al., 2011*

### PCR Conditions
- **Round 1 followed Lee et al. (2008)**
- **Round 2 followed protocols outlined by the Integrated Microbiomae Resource (IMR), Dalhousie University**

## Sequencing
- **Platform:** Illumina MiSeq (2×300 bp)  
- **Facility:** Integrated Microbiome Resource (IMR), Dalhousie University  
- **Protocol:** [https://imr.bio/protocols.html](https://imr.bio/protocols.html)

## Data Files

| Filename              | Description                                                   |
|-----------------------|---------------------------------------------------------------|
| `raw_reads.fastq.gz`  | Raw paired-end Illumina MiSeq reads (gzip-compressed FASTQ)   |
| `METADATA.tsv`        | Sample metadata including treatment, mesocosm ID, and harvest date|

- ** Importing Convention:** `Cassava1.8: demultiplexed, paired-end raw sequences`
  

## References

- Lee, J., Lee, S., & Young, J. P. W. (2008). Improved PCR primers for the detection and identification of arbuscular mycorrhizal fungi. *FEMS Microbiology Ecology*, 65(2), 339–349.
- Dumbrell, A. J., et al. (2011). Distinct seasonal assemblages of arbuscular mycorrhizal fungi revealed by massively parallel pyrosequencing. *New Phytologist*, 190(3), 794–804.

---
