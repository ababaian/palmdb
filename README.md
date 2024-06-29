![palmDB](https://s3.amazonaws.com/palm.db/img/palmdb_header.png)

## Current Release: `2023-04-26`. sOTU count: `508,607`

### 

- `palmdb` is a database of viral polymerase palmprint (barcode) sequences classified by clustering sequences into species-like operational taxonomic units (OTUs) at 90% amino acid identity.
- `palm_annot` [(link)](https://github.com/rcedgar/palm_annot) is a command-line tool to identify RdRp sequences and annotate the palmprints within them.
- `palmID` [(link)](https://serratus.io/palmid) is a web-tool to query `palmdb` with an RdRp sequence, and retrieve matches in the SRA.

![palmDB](https://s3.amazonaws.com/palm.db/img/palmprint_structure.png)

The hallmark gene for RNA viruses is the RNA-dependent RNA-polymerase (`RdRp`). Palmprints are a ~100aa sub-sequence of `RdRp` delineated by the conserved catalytic motifs "A", "B", and "C" in the palm sub-domain. 

### [Learn more...](https://github.com/ababaian/palmdb/wiki)

## Download

- Release: [`palmdb.current.tar.gz`](https://s3.amazonaws.com/palm.db/palmdb.current.tar.gz) (4 GB)

#### Palmprint sequences
- sOTU palmprints: [`sotus.palmprint.faa`](https://s3.amazonaws.com/palm.db/final/sotus.palmprint.faa)  (63 MB)
- all-unique palmprints, unclustered: [`unique.palmprint.faa`](https://s3.amazonaws.com/palm.db/final/unique.palmprint.faa)  (131.3 MB)
- sOTU source labels: [`label_sotu.tsv`](https://s3.amazonaws.com/palm.db/final/label_sotu.tsv)  (178.2 MB)

#### RdRp sequences

Source-original sequences are avaialble in the  `raw/` folder of the [`Current Release`](https://s3.amazonaws.com/palm.db/palmdb.current.tar.gz)

### References

- Babaian and Edgar, 2022. [Ribovirus classification by a polymerase barcode sequence. _PeerJ_](https://peerj.com/articles/14055/)

- Edgar _et al._, 2022. [Petabase-scale sequence alignment catalyses viral discovery. _Nature_](https://www.nature.com/articles/s41586-021-04332-2)
