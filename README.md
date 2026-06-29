## document: train_V2_cleaning
**Working clean copy of train_V2.** Steps taken so far: 
1. Ordinal data > binary data, using one-hot encoding.
   - client_segment (catergories 0-5) -> client_segment_0, client_segment_1, client_segment_2, client_segment_3, client_segment_4, client_segment_5
   - client_segment deleted.
3. Binary variables coded numerically.
   - gender (M/L) -> 1/0
   - married_cd (TRUE/FALSE) -> 1/0

# Next steps: 
- Imputation - selected constant, or predicted values?
- Min-max normalization?
- Duplicate removal?
# Model
- The model use the clean data from the train_clean and score_clean files.
- The model is ready and trained based on the system design figure.
- scored_applicants is the model output result file.
  
