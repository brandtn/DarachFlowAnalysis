# flow

Scripts for processing flow cytometry and FACS data

The overall strategy for using flow cytometry analysis is:

1. Put your `.fcs` files and a `SampleSheet.txt` in a folder.
2. Modify the script to point at that folder, or folders.
3. Run the script, gating when prompted. Modify the gating to gate
   on different parameters than those implemented.

`./src/` contains snippets of R code for functions and things.

To run the example script, download the dataset 
[from here](https://osf.io/ka5xx/).
You can see the example of this analysis 
[here](docs/Gresham_Lab_Flow_Cytometry_Analysis.html).


We should have these pairs of example datasets and analyses, more of
them. 

- ~12 samples of dye concentration
[here](docs/Gresham_Lab_Flow_Cytometry_Analysis.html).
- a plate of GAP1::GFP
- something else
- [coulter counting](docs/exampleTwoCoulterZ2.html)

# paging

To make it so that you can view HTML pages, go to repository
settings and enable github pages and set it to read the master 
branch. Then put a link in here, if you want to. Note the relative
links above work just fine.

