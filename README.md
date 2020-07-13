# make_descriptor_simpleNN

Make descriptor from SIMPLE-NN's cffi scripts, and reformat into AMP style input. 

### Setup: 
- Install SIMPLE-NN. 

    - `pip install git+https://github.com/mshuaibii/SIMPLE-NN.git`
    - Note that this fork contains a previous version of SIMPLE-NN module that does not automatically calculate fingerprints for stresses. 

- Other required modules:
    - `ase`
    - `numpy`
    - `scipy`