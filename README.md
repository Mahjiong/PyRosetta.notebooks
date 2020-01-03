
[//]: # (DO NOT EDIT. README.md is generated by nbpages. Make changes templates/README.md.jinja.)
# PyRosetta Workshops

## Getting Started

### Students

_Step 1:_ Sign in to [Google Drive](https://drive.google.com/drive/u/0/my-drive).

_Step 2:_ Make a new folder called “PyRosetta” in your top level directory on Google Drive.
![PyRosetta folder](https://github.com/RosettaCommons/PyRosetta.notebooks/blob/master/notebooks/Media/PyRosetta-folder.png?raw=true)

_Step 3:_ Get your [PyRosetta license](https://els.comotion.uw.edu/licenses/88).

_Step 4:_ Download the Linux [PyRosetta package](http://www.pyrosetta.org/dow) that is called "Python-3.6.MinSizeRel".
![Linux Download](https://github.com/RosettaCommons/PyRosetta.notebooks/blob/master/notebooks/Media/linux-download.png?raw=true)

_Step 5:_ Upload the Linux PyRosetta package (.tar file) to the PyRosetta folder in your Google Drive.

_Step 6:_ Go to https://github.com/RosettaCommons/PyRosetta.notebooks and download the ZIP folder.
![ZIP](https://github.com/RosettaCommons/PyRosetta.notebooks/blob/master/notebooks/Media/zip.png?raw=true)

_Step 7:_ Upload either (or both) the student-notebooks folder and the notebooks folder to the top-level directory of your Google Drive.
![nb](https://github.com/RosettaCommons/PyRosetta.notebooks/blob/master/notebooks/Media/nb.png?raw=true)
![Google Drive](https://github.com/RosettaCommons/PyRosetta.notebooks/blob/master/notebooks/Media/google-drive.png?raw=true)

_Step 8:_ From the notebooks or student-notebooks folder, open up “01.01-PyRosetta-Google-Drive-Setup.ipynb” in Google Colab by right-clicking, going under “Open With…” and clicking Google Colaboratory.

_Step 9:_ Follow steps to install PyRosetta. You will see a bar and a lot of output, and it should take 10-15 minutes.
Note: You only need to do this once since this installation will be associated with your Google Drive account.
![install](https://github.com/RosettaCommons/PyRosetta.notebooks/blob/master/notebooks/Media/install.png?raw=true)

_Step 10:_
Open up “01.02-PyRosetta-Google-Drive-Usage-Example.ipynb” in Colab to make sure that PyRosetta was installed properly. You are now ready to move on to the other notebooks!

### Instructors

_Step 1:_ Please install extensions [nbgrader](https://nbgrader.readthedocs.io/en/stable/user_guide/highlights.html) and [nbpages](https://pypi.org/project/nbpages/).

_Step 2:_ Make any changes to the workshops in the "notebooks" folder. (You can follow the directions for students and edit them in [Google Colab](https://colab.research.google.com/notebooks/welcome.ipynb) or on your own computer using a Jupyter Notebooks browser.)

_Step 3:_ When you are done making changes, run make-student-nb.bash to automatically generate the student notebooks in a separate folder, the table of contents you see below, and the keyword index. The student notebooks are copies of the instructor's version that have omitted solutions. 

### [Table of Contents](http://nbviewer.jupyter.org/github/RosettaCommons/PyRosetta.notebooks/blob/master/notebooks/toc.ipynb?flush=true)
### [Keyword Index](http://nbviewer.jupyter.org/github/RosettaCommons/PyRosetta.notebooks/blob/master/notebooks/index.ipynb?flush=true)

### [Chapter 1.0 How to Get Started](http://nbviewer.jupyter.org/github/RosettaCommons/PyRosetta.notebooks/blob/master/notebooks/01.00-How-to-Get-Started.ipynb)
- [1.1 PyRosetta Google Drive Setup](http://nbviewer.jupyter.org/github/RosettaCommons/PyRosetta.notebooks/blob/master/notebooks/01.01-PyRosetta-Google-Drive-Setup.ipynb)
- [1.2 PyRosetta Google Drive Usage Example](http://nbviewer.jupyter.org/github/RosettaCommons/PyRosetta.notebooks/blob/master/notebooks/01.02-PyRosetta-Google-Drive-Usage-Example.ipynb)
- [1.3 How to Get PyRosetta on Your Personal Computer](http://nbviewer.jupyter.org/github/RosettaCommons/PyRosetta.notebooks/blob/master/notebooks/01.03-How-to-Get-Local-PyRosetta.ipynb)

### [Chapter 2.0 Introduction to PyRosetta](http://nbviewer.jupyter.org/github/RosettaCommons/PyRosetta.notebooks/blob/master/notebooks/02.00-Introduction-to-PyRosetta.ipynb)
- [2.1 Pose Basics](http://nbviewer.jupyter.org/github/RosettaCommons/PyRosetta.notebooks/blob/master/notebooks/02.01-Pose-Basics.ipynb)
- [2.2 Working with Pose residues](http://nbviewer.jupyter.org/github/RosettaCommons/PyRosetta.notebooks/blob/master/notebooks/02.02-Working-with-Pose-Residues.ipynb)
- [2.3 Accessing PyRosetta Documentation](http://nbviewer.jupyter.org/github/RosettaCommons/PyRosetta.notebooks/blob/master/notebooks/02.03-Accessing-PyRosetta-Documentation.ipynb)
- [2.4 Getting spatial features from a Pose](http://nbviewer.jupyter.org/github/RosettaCommons/PyRosetta.notebooks/blob/master/notebooks/02.04-Getting-Spatial-Features-from-Pose.ipynb)
- [2.5 Protein Geometry](http://nbviewer.jupyter.org/github/RosettaCommons/PyRosetta.notebooks/blob/master/notebooks/02.05-Protein-Geometry.ipynb)
- [2.6 Visualization with the `PyMOLMover`](http://nbviewer.jupyter.org/github/RosettaCommons/PyRosetta.notebooks/blob/master/notebooks/02.06-Visualization-and-PyMOL-Mover.ipynb)
- [2.7 RosettaScripts in PyRosetta](http://nbviewer.jupyter.org/github/RosettaCommons/PyRosetta.notebooks/blob/master/notebooks/02.07-RosettaScripts-in-PyRosetta.ipynb)
- [2.8 Visualization and `pyrosetta.distributed.viewer`](http://nbviewer.jupyter.org/github/RosettaCommons/PyRosetta.notebooks/blob/master/notebooks/02.08-Visualization-and-pyrosetta.distributed.viewer.ipynb)

### [Chapter 3.0 Rosetta Energy Score Functions](http://nbviewer.jupyter.org/github/RosettaCommons/PyRosetta.notebooks/blob/master/notebooks/03.00-Rosetta-Energy-Score-Functions.ipynb)
- [3.1 Score Function Basics](http://nbviewer.jupyter.org/github/RosettaCommons/PyRosetta.notebooks/blob/master/notebooks/03.01-Score-Function-Basics.ipynb)
- [3.2 Practice: Analyzing energy between residues](http://nbviewer.jupyter.org/github/RosettaCommons/PyRosetta.notebooks/blob/master/notebooks/03.02-Analyzing-energy-between-residues.ipynb)
- [3.3 Energies and the PyMOL Mover](http://nbviewer.jupyter.org/github/RosettaCommons/PyRosetta.notebooks/blob/master/notebooks/03.03-Energies-and-the-PyMOLMover.ipynb)

### [Chapter 4.0 Introduction to Folding](http://nbviewer.jupyter.org/github/RosettaCommons/PyRosetta.notebooks/blob/master/notebooks/04.00-Introduction-to-Folding.ipynb)
- [4.1 Basic Folding Algorithm](http://nbviewer.jupyter.org/github/RosettaCommons/PyRosetta.notebooks/blob/master/notebooks/04.01-Basic-Folding-Algorithm.ipynb)
- [4.2 Low-Res Scoring and Fragments](http://nbviewer.jupyter.org/github/RosettaCommons/PyRosetta.notebooks/blob/master/notebooks/04.02-Low-Res-Scoring-and-Fragments.ipynb)

### [Chapter 5.0 Structure Refinement](http://nbviewer.jupyter.org/github/RosettaCommons/PyRosetta.notebooks/blob/master/notebooks/05.00-Structure-Refinement.ipynb)
- [5.1 High-Resolution Movers](http://nbviewer.jupyter.org/github/RosettaCommons/PyRosetta.notebooks/blob/master/notebooks/05.01-High-Res-Movers.ipynb)
- [5.2 Refinement Protocol](http://nbviewer.jupyter.org/github/RosettaCommons/PyRosetta.notebooks/blob/master/notebooks/05.02-Refinement-Protocol.ipynb)

### [Chapter 6.0 Packing & Design](http://nbviewer.jupyter.org/github/RosettaCommons/PyRosetta.notebooks/blob/master/notebooks/06.00-Introduction-to-Packing-and-Design.ipynb)
- [6.1 Side Chain Conformations and Dunbrack Energies](http://nbviewer.jupyter.org/github/RosettaCommons/PyRosetta.notebooks/blob/master/notebooks/06.01-Side-Chain-Conformations-and-Dunbrack-Energies.ipynb)
- [6.2 Packing and Relax](http://nbviewer.jupyter.org/github/RosettaCommons/PyRosetta.notebooks/blob/master/notebooks/06.02-Packing-design-and-regional-relax.ipynb)
- [6.3 Protein Design with a Resfile and FastRelax](http://nbviewer.jupyter.org/github/RosettaCommons/PyRosetta.notebooks/blob/master/notebooks/06.03-Design-with-a-resfile-and-relax.ipynb)
- [6.4 Protein Design 2](http://nbviewer.jupyter.org/github/RosettaCommons/PyRosetta.notebooks/blob/master/notebooks/06.04-Protein-Design-2.ipynb)
- [6.5 HBNet Before Design](http://nbviewer.jupyter.org/github/RosettaCommons/PyRosetta.notebooks/blob/master/notebooks/06.05-HBNet-Before-Design.ipynb)
- [6.6 *De Novo* Parametric Backbone Design](http://nbviewer.jupyter.org/github/RosettaCommons/PyRosetta.notebooks/blob/master/notebooks/06.06-Introduction-to-Parametric-backbone-design.ipynb)
- [6.7 *De Novo* Protein Design with PyRosetta](http://nbviewer.jupyter.org/github/RosettaCommons/PyRosetta.notebooks/blob/master/notebooks/06.07-Introduction-to-DeNovo-protein-design.ipynb)

### [Chapter 7.0 Docking](http://nbviewer.jupyter.org/github/RosettaCommons/PyRosetta.notebooks/blob/master/notebooks/07.00-Docking.ipynb)
- [7.1 Fast Fourier Transform Based Docking via ZDOCK](http://nbviewer.jupyter.org/github/RosettaCommons/PyRosetta.notebooks/blob/master/notebooks/07.01-Fast-Fourier-Transform-Based-Docking-via-ZDOCK.ipynb)
- [7.2 Docking Moves in Rosetta](http://nbviewer.jupyter.org/github/RosettaCommons/PyRosetta.notebooks/blob/master/notebooks/07.02-Docking-Moves-in-Rosetta.ipynb)
- [7.3 Ligand Refinement in PyRosetta (a.k.a. High-Resolution Local Docking) Using the `ligand.wts` Scorefunction](http://nbviewer.jupyter.org/github/RosettaCommons/PyRosetta.notebooks/blob/master/notebooks/07.03-Ligand-Docking-PyRosetta.ipynb)
- [7.4 Global Ligand Docking using `XMLObjects` Using the `ref2015.wts` Scorefunction](http://nbviewer.jupyter.org/github/RosettaCommons/PyRosetta.notebooks/blob/master/notebooks/07.04-Ligand-Docking-XMLObjects.ipynb)
- [7.5 `GALigandDock` Protocol with `pyrosetta.distributed` Using the `beta_cart.wts` Scorefunction](http://nbviewer.jupyter.org/github/RosettaCommons/PyRosetta.notebooks/blob/master/notebooks/07.05-Ligand-Docking-pyrosetta.distributed.ipynb)

### [Chapter 9.0 Working With Symmetry](http://nbviewer.jupyter.org/github/RosettaCommons/PyRosetta.notebooks/blob/master/notebooks/09.00-Working-With-Symmetry.ipynb)

### [Chapter 10.0 Working With Density](http://nbviewer.jupyter.org/github/RosettaCommons/PyRosetta.notebooks/blob/master/notebooks/10.00-Working-With-Density.ipynb)

### [Chapter 11.0 Working With Antibodies](http://nbviewer.jupyter.org/github/RosettaCommons/PyRosetta.notebooks/blob/master/notebooks/11.00-Working-With-Antibodies.ipynb)
- [11.1 RosettaAntibody Framework](http://nbviewer.jupyter.org/github/RosettaCommons/PyRosetta.notebooks/blob/master/notebooks/11.01-RosettaAntibody-Framework-and-SimpleMetrics.ipynb)
- [11.2 RosettaAntibodyDesign](http://nbviewer.jupyter.org/github/RosettaCommons/PyRosetta.notebooks/blob/master/notebooks/11.02-RosettaAntibodyDesign-RAbD.ipynb)

### [Chapter 12.0 RosettaCarbohydrates](http://nbviewer.jupyter.org/github/RosettaCommons/PyRosetta.notebooks/blob/master/notebooks/12.00-RosettaCarbohydrates-Working-with-Glycans.ipynb)
- [12.1 RosettaCarbohydrates: Trees, Selectors and Movers](http://nbviewer.jupyter.org/github/RosettaCommons/PyRosetta.notebooks/blob/master/notebooks/12.01-Glycan-Trees-Selectors-and-Movers.ipynb)
- [12.2 RosettaCarbohydrates: Modeling and Design](http://nbviewer.jupyter.org/github/RosettaCommons/PyRosetta.notebooks/blob/master/notebooks/12.02-Glycan-Modeling-and-Design.ipynb)

### [Chapter 13.0 RNA in PyRosetta](http://nbviewer.jupyter.org/github/RosettaCommons/PyRosetta.notebooks/blob/master/notebooks/13.00-RNA-Basics.ipynb)

### [Chapter 15.0 Running Rosetta in Parellel](http://nbviewer.jupyter.org/github/RosettaCommons/PyRosetta.notebooks/blob/master/notebooks/15.00-Running-PyRosetta-in-Parellel.ipynb)
- [15.1 Distributed analysis example: exhaustive ddG PSSM](http://nbviewer.jupyter.org/github/RosettaCommons/PyRosetta.notebooks/blob/master/notebooks/15.01-PyData-ddG-pssm.ipynb)
- [15.2 Distributed computation example: miniprotein design](http://nbviewer.jupyter.org/github/RosettaCommons/PyRosetta.notebooks/blob/master/notebooks/15.02-PyData-miniprotein-design.ipynb)
- [15.3 Example of Using PyRosetta with GNU Parallel](http://nbviewer.jupyter.org/github/RosettaCommons/PyRosetta.notebooks/blob/master/notebooks/15.03-GNU-Parallel-Via-Slurm.ipynb)
- [15.4 Examples Using the `dask` Module](http://nbviewer.jupyter.org/github/RosettaCommons/PyRosetta.notebooks/blob/master/notebooks/15.04-dask.delayed-Via-Slurm.ipynb)
- [15.5 Part I: Parallelized Global Ligand Docking with `pyrosetta.distributed`](http://nbviewer.jupyter.org/github/RosettaCommons/PyRosetta.notebooks/blob/master/notebooks/15.05-Ligand-Docking-dask.ipynb)
