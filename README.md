# Visualizing Dynamically Generated Protein Interactions

A Python library for visualizing dynamically generated protein interactions using 3D node-link layout.

[DEMO Video](https://drive.google.com/file/d/1asdQyc7OI6UoSYfjNL5yBujIoi59XTUy/view?usp=sharing)

## Installation

1. Clone the github repository


2. Requires `anaconda` and `python=3.8`

   ```
   conda create -n myenv python=3.8
   conda activate myenv
   ```
3. Install packages
    ```
    cd src/
    pip install -r requirements.txt
    ```
Note: You may need to install [pygraphvis](https://pygraphviz.github.io/documentation/stable/install.html) using conda forge:
`conda install --channel conda-forge pygraphviz`

4. The data file in dot file format should be stored in
   ```
   ./src/visg/static/data/
   ```

5. Start server
   ```
   ./start.sh
   ```

6. Open browser (Google Chrome preferred)
    ```angular2html
    http://127.0.0.1:5000/index
    ```


## Instructions to start the server

1. Change directory to `./src`

   ```
   cd /path/to/project/src
   ```

2. Activate conda environment

   ```
   conda activate myenv
   ```

3. Start server
   ```
   ./start.sh
   ```

4. Open browser (Google Chrome preferred)
    ```angular2html
    http://127.0.0.1:5000/index
    ```


### References 
1. A. Vasan et al., "High Performance Binding Affinity Prediction with a Transformer-Based Surrogate Model," 2024 IEEE International Parallel and Distributed Processing Symposium Workshops (IPDPSW), San Francisco, CA, USA, 2024, pp. 571-580, doi: 10.1109/IPDPSW63119.2024.00114. keywords: {Proteins;Ion radiation effects;Accuracy;Computational modeling;Pipelines;Transformers;Supercomputers;drug discovery;virtual screening;docking surrogates;high performance computing;transformers},

2. Libraries used: [D3](https://d3js.org), [Flask](https://flask.palletsprojects.com/en/stable/),  [3d-force-graph](https://github.com/vasturiano/3d-force-graph?tab=readme-ov-file)
   
