![palmDB](https://s3.amazonaws.com/palm.db/img/palmdb_header.png)

## sOTU count: `508,607`

`palmDB` is a database of viral polymerase palmprint (barcode) sequences classified by clustering sequences into species-like operational taxonomic units (OTUs) at 90% amino acid identity.

### Palmprint Barcode

![palmDB](https://s3.amazonaws.com/palm.db/img/palmprint_structure.png)

The hallmark gene for RNA viruses is the RNA-dependent RNA-polymerase (`RdRp`). Palmprints are a ~100aa sub-sequence of `RdRp` delineated by the conserved catalytic motifs "A", "B", and "C" in the palm sub-domain. [Learn more...](https://github.com/ababaian/palmdb/wiki)
 
### Files

Releases are posted in sub-directories named `YYYY-MM-DD` giving the date the release was posted. Files are in FASTA (for sequences) or tab-separated values (TSV, for annotations). Files and formats are subject to change between releases.

```
YYYY-MM-DD/
	+--- acc_taxid.tsv         # 1. source accession 2. NCBI TaxID
	+--- acc_u.tsv             # 1. source accession 2. unique sequence identifier u<nnn>
	+--- otu_centroids.fa      # OTU centroid sequences
	+--- sources.fa            # palmprints from all source databases
	+--- species_ncbi_ictv.tsv # 1. species name 2. bothdbs/onedb 3. NCBI TaxID 4. ICTV Version.SortID
	+--- taxon.tsv             # 1. NCBI TaxID 2. name 3. clade names superkingdom...species
	+--- u_otu.tsv             # 1. u<nnn> 2. u<nnn> of OTU centroid
	+--- uniques.fa            # unique sequences from sources.fa, relabeled as u<nnn>
	+--- u_tax.tsv             # tab-separated file with approximate taxonomy assignments for uniques.    
```

### References

Babaian and Edgar, 2022. [Ribovirus classification by a polymerase barcode sequence. _PeerJ_](https://peerj.com/articles/14055/)

Edgar _et al._, 2022. [Petabase-scale sequence alignment catalyses viral discovery. _Nature_](https://www.nature.com/articles/s41586-021-04332-2)
