# Link Prediction using Graph Neural Networks

This project demonstrates a link prediction pipeline on social networks using lightweight GNN architectures (GraphSAGE and LightGCN). Built as part of a hands-on experiment, it shows how machine learning can model relationship formation—and explain its recommendations with mutual-friend visuals.

We use a Facebook ego-network graph to train GNNs for link prediction. The model suggests new connections and explains its reasoning by highlighting shared friends.


## Business Application

This pipeline simulates real-world applications like:
- **Friend suggestions** in social platforms (Facebook, LinkedIn)
- **Team-matching** or **collaborator recommendations** in enterprise tools
- **Network-based outreach** in professional apps

## Pipeline Walkthrough

1. **Data Setup** 
2. **Model Definition**  *(see details below)*
3. **Training & Evaluation** 
4. **Explainability** 



   *Models*
     - **GraphSAGE**: Learns representations by aggregating local neighborhood info.
     - **LightGCN**: Lightweight alternative for efficient, deep collaborative filtering.


## Getting Started

### 1. Installation

Install all required Python packages:
```bash
pip install torch torch_geometric scikit-learn
pip install torch-scatter -f https://data.pyg.org/whl/torch-2.6.0+cu124.html
pip install torch-sparse  -f https://data.pyg.org/whl/torch-2.6.0+cu124.html
pip install torch-cluster -f https://data.pyg.org/whl/torch-2.6.0+cu124.html
pip install torch-spline-conv -f https://data.pyg.org/whl/torch-2.6.0+cu124.html
````
### 2. Download the Dataset
Download and extract `facebook.tar.gz` into `/content/facebook`.

### 3. Run the Notebook
Open the notebook and run each section in order:

### 4. Save or Analyze Outputs
Final models are saved to `/checkpoints` and can be reloaded for further analysis or deployment.

-----
### 🎥 Video Walkthrough  
- [Watch a short video explanation here](https://youtu.be/1qhz2FeR8lY)

------
### References and Inspiration
- [Using Graph Neural Networks to Predict & Analyze Links in Friendship Networks - Medium Article](https://medium.com/@patwei/using-graph-neural-networks-to-predict-analyze-links-in-friendship-networks-5df020830ced)
- [Dataset (Standford SNAP)](https://snap.stanford.edu/data/egonets-Facebook.html)
-------
## License
This project is licensed under the MIT License. See the LICENSE file for full details.

Feel free to fork this repo, open issues, or contribute improvements!

