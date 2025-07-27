## 🎯 Problem Statement

Given a list of 100 wallet addresses, the objective was to:

   1.Fetch their transaction history from the Compound V2/V3 protocol.
   
   2.Engineer meaningful features that reflect risk exposure.
   
   3.Assign a risk score between 0 and 1000 for each wallet.
   
   4.Justify the scoring logic using DeFi and financial risk modeling principles.

## 📊 Key Highlights
 ✅ No transaction history found for the provided wallets on Compound V2/V3.
 
 ⚙️ Implemented deterministic feature simulation using wallet hashes (e.g., account age, asset diversity).
 
 🧠 scoring model based on:
      PCA
      Elbow Method
      
📉 Risk scores range: Cluster 1 → High value + high activity

                       Cluster 2 → Low value, low activity

                       Cluster 3 → High failure rate

                       Cluster 0 → Average users with long history

## 🛠️ Tech Stack

   Python (Pandas, NumPy, Matplotlib)
   
   Google Colab Notebook
   
   Google Colab (Runtime)
   
   Excel + CSV for wallet ID alignment
