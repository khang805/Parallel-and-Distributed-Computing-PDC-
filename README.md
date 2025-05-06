# PDC Project Repository

This repository contains datasets, code, and reports related to research paper ( Parallel social behavior-based algorithm for identification
 of influential users in social network).

## Contents

### Datasets
  - `higgs-activity_time.txt`: Timestamps of user activities.
  - `higgs-mention_network.edgelist`: Mention network edges.
  - `higgs-reply_network.edgelist`: Reply network edges.
  - `higgs-retweet_network.edgelist`: Retweet network edges.
- **P2P Network**:
  - `p2p-Gnutella04.txt.gz`: Compressed Gnutella peer-to-peer network data.

### Code & Reports
- `Python Code.zip`: Contains Python scripts (serial,parallel, mpi and open mp implementation).
- `Project_Report_i22-1148_i22-0788_i22-0962`: Project report/documentation.
- `PDC_project phase 1 (Presentation slides).pptx`: Introductory presentation slides.

## Usage
1. **For Twitter Data**: Use the `.edgelist` files with network analysis tools (e.g., NetworkX, igraph) to study mention/reply/retweet dynamics. The `activity_time.txt` file can help analyze temporal patterns.
2. **For Gnutella Data**: Decompress `p2p-Gnutella04.txt.gz` to analyze the P2P network structure.
3. **Code**: Extract `Python Code.zip` and refer to scripts for examples of data processing or analysis pipelines.
