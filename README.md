
fasta2ali.py

- Converts fasta file to ali format for modeller**

            usage: fasta2ali.py ID fasta_file
                     
            
            
            
<br /> <br /> <br /> 

Dope_compare.py 

- Script to automate single, multi and loop model generation and DOPE comparison in MODELLER.
- Produces final plot to compare DOPE scores of different modelling methods: single template, multi-template, automatic loop refinement on multi-template model.
<br /> <br /> <br /> 

Requirements:
- Python modules: modeller, pylab, os, sys 
- Python 2.7
<br /> <br /> <br /> 

![alt text](Modeller-scripts/DOPE_compare/dope_example.png)



<br /> <br /> <br /> 

      usage:  template1 template2 chainid_template1 chainid_template2 query_ID

<br /> <br /> <br /> 
Notes:
- template1 should be the template with the highest sequence % id to query.
- The query_ID needs to be the same as the ID used to generate the .ali file**
- chainid needs to be capitalised. 
- Depending on compute power n models could be changed - look for starting_model and ending_model. 
- To look out for; best DOPE score not necessarily best model - particularly for loop models, hint: view it in pymol.
