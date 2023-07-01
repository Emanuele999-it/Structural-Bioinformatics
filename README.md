# Structural-Bioinformatics

<h3>Dependencies:</h3>
The project has the following dependencies:
 <ul>
  <li>biopython</li>
  <li>pandas</li>
  <li>request</li>
  <li>subprocess</li>
  <li>joblib</li>
  <li>dssp</li>
  <li>torch</li>
  <li>torchinfo</li>
</ul> 

Make sure the above dependencies are installed before running the program.

<h3>Execution:</h3>
Before running the software you need to edit the "configuration.json" file in the "contacts_classification" folder. Specifically, it is necessary to modify the path of "dssp_file" by placing the path that points to the "mkdssp" dependency.
Before launching the program it is also necessary to verify that in the "models/" folder there is at least one model for each subfolder (it must necessarily be one of those generated by the supplied ".ipynb" file).
At this point it will be possible to launch the program by executing the command "$python3 main.py" and follow the requests that will be displayed.


<h3>Re-train models:</h3>
To use new models with different training it is necessary to re-run the delivered ".ipynb" file and save the
models in a new subfolder in the "models" project folder. At this point, just start the program and choose the desired model when prompted.

<h3>Results:</h3>
The execution results can be located both in the terminal and in the "outputFolder" folder.
