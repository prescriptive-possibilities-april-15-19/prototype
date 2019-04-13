# FIELDS -- (warning, subject to me being wrong) 

`BindingDB Reactant_set_id": ` a reference to another record

`"BindingDB Ligand Name":` -- a list of references to antoher record, just like reactant_set_id

 `"Target Name Assigned by Curator or DataSource"`, `"Target Source Organism According to Curator or DataSource"` -- names of diseases being targeted. apparently, also, viruses.  

`articleid`, `publication doi`, `authors`, `institution` --- to do wtih publication (can be dropped?) 

``` "Link to Ligand in BindingDB": "http://www.bindingdb.org/bind/chemsearch/marvin/MolStructure.jsp?monomerid=21",
 "Link to Ligand-Target Pair in BindingDB": "http://www.bindingdb.org/jsp/dbsearch/PrimarySearch_ki.jsp?energyterm=kJ/mole&tag=r21&monomerid=21&enzyme=HIV-1+Protease&column=ki&startPg=0&Increment=50&submit=Search",
 "Ligand HET ID in PDB": "ZD6",
 "PDB ID(s) for Ligand-Target Complex": "2IVU",
 "PubChem CID": "3081361",
 "PubChem SID": "8030012",
 "ChEBI ID of Ligand": "49960",
 "ChEMBL ID of Ligand": "CHEMBL24828",
 "DrugBank ID of Ligand": "DB08764",
 "ZINC ID of Ligand": "ZINC03834198",<Paste>
```
i have utterly no idea what any of these are or if they're useful (but i could sort of figure them out) 

`indingDB Target Chain Sequence` --- this is the signature of the protein that the drug is targeting???

`fasta_seqs`, `pdb_ids` --- these are very important

# What can we drop? 

definitely: `From: bindingdb.org`

possibly: `article id, publication doi, authors, institution, link to ligand-target pair in bidningdb, ligand het id in pdb" 

so out of 20 features, as many as 6+ could be dropped? how much will this help us with scaling? 
