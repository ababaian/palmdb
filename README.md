![palmDB](https://s3.amazonaws.com/palm.db/img/palmdb_header.png)

## Current Release: `2023-04-26`. sOTU count: `508,607`

#### Palmprint sequences
- sOTU palmprints (63 MB) [`sotus.palmprint.faa`](https://s3.amazonaws.com/palm.db/final/sotus.palmprint.faa)
- all-unique palmprints, unclustered (131.3 MB) [`unique.palmprint.faa)`](https://s3.amazonaws.com/palm.db/final/unique.palmprint.faa)
- sOTU source labels (178.2 MB) [`label_sotu.tsv`](https://s3.amazonaws.com/palm.db/final/label_sotu.tsv)

#### RdRp sequences
Download [`palmdb.current.tar.gz` (4 GB)](https://s3.amazonaws.com/palm.db/palmdb.current.tar.gz)

`palmDB` is a database of viral polymerase palmprint (barcode) sequences classified by clustering sequences into species-like operational taxonomic units (OTUs) at 90% amino acid identity.

### Palmprint Barcode

![palmDB](https://s3.amazonaws.com/palm.db/img/palmprint_structure.png)

The hallmark gene for RNA viruses is the RNA-dependent RNA-polymerase (`RdRp`). Palmprints are a ~100aa sub-sequence of `RdRp` delineated by the conserved catalytic motifs "A", "B", and "C" in the palm sub-domain. [Learn more...](https://github.com/ababaian/palmdb/wiki)
 
### References

Babaian and Edgar, 2022. [Ribovirus classification by a polymerase barcode sequence. _PeerJ_](https://peerj.com/articles/14055/)

Edgar _et al._, 2022. [Petabase-scale sequence alignment catalyses viral discovery. _Nature_](https://www.nature.com/articles/s41586-021-04332-2)
