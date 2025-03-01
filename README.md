## Modeling Semantic Relationships for Natural Language Inference

## 📁 Folder Structure

```markdown
MODELING_SEMANTIC_RELATIONSHIP/
│── Code/                                # Contains implementation notebooks
│   ├── Diagram/                         
│   │   ├── plot_test_score.ipynb        # Generates test accuracy comparison plots
│   ├── bilstm_with_attention.ipynb  # Implements BiLSTM with attention mechanism
│   ├── stacked_BiLSTM.ipynb         # Implements Stacked BiLSTM model
│── Report/                              # Stores the final report and figures
│   ├── Figures/                         # Contains plots and visualizations used in the report
│   ├── Modeling Semantic Relationships Report.pdf  # Final report detailing methodology & results
│── README.md                             # Project documentation
```


## 🚀 How to Run the Code

### **1️⃣ Installation**
- The required dependencies are listed at the beginning of each Jupyter Notebook.
- To install them, **uncomment the installation commands** and run the corresponding cell.

### **2️⃣ Running Experiments**
- **Run `bilstm_with_attention.ipynb`** to train and evaluate a **BiLSTM model with an attention mechanism** using different embedding strategies.
- **Run `stacked_BiLSTM.ipynb`** to test a **Stacked BiLSTM architecture** for improved performance.
- **Run `plot_test_score.ipynb`** to generate accuracy comparison plots across models.

### **3️⃣ Reproducing Results**
- The models are trained using **Google Colab (free version)**.
- Due to **hardware constraints**, results may slightly vary across runs.
- The dataset used is **SNLI (Stanford Natural Language Inference)**, which is automatically downloaded when running the code.

## 📊 Key Results
The **Stacked BiLSTM model with fine-tuned embeddings** achieves the best performance, demonstrating the impact of deeper sequential modeling for NLI.

For detailed insights and analysis, refer to the **[Modeling Semantic Relationships Report.pdf](Report/Modeling%20Semantic%20Relationships%20Report.pdf)**.

