# 🧬 Drug Repurposing for Liver Cancer
### 🔗 Gene-Drug Interaction Network using DGIdb and TCGA-LIHC data

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/shubh-1909/liver-cancer-drug-repurposing/blob/main/notebooks/liver_cancer_dgidb_network.ipynb)

---

## 📖 About this project

This project builds a **gene-drug interaction network** to explore **drug repurposing opportunities** in liver cancer (TCGA-LIHC).  
It leverages:

- 🧬 Hub genes from transcriptomic studies  
- 💊 Drug interaction data from DGIdb  
- 🐍 Python (NetworkX, matplotlib) to construct and visualize the networks

The primary aim is to identify existing or investigational drugs that could be repositioned for liver cancer therapy.

---

## 🚀 Features

- 📂 Loads DGIdb TSV files (gene-drug interactions)
- 🌐 Builds a bipartite network (genes vs drugs)
- 🎨 Colors genes vs drugs distinctly
- 📈 Scales node sizes by degree (highlighting hubs)
- 💾 Exports high-quality PNG figures & CSV tables

---

## 🚀 How to run

1. Click below to open directly in **Google Colab**:

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/shubh-1909/liver-cancer-drug-repurposing/blob/main/notebooks/liver_cancer_dgidb_network.ipynb)

2. Upload your DGIdb TSV file (like `dgidb_mock_large.tsv`) when prompted.

3. Run all cells to generate:

   - ✅ Network visualization
   - ✅ Node degree analysis (to find hub genes/drugs)
   - ✅ Exported CSV & PNG outputs

---

## 👤 Author

- 📝 **Shubhkarandeep Singh Judge**  
- 🔗 [GitHub: shubh-1909](https://github.com/shubh-1909)

---

## 📜 License

This project is licensed under the MIT License.  
You are free to use, modify, and distribute it with attribution.  


