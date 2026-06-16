Data cleaning in file train_V2_cleaning
Steps taken so far: 
1. Ordinal data > one-hot target encoding.
   - client_segment -> client_segment_0, client_segment_1, client_segment_2, client_segment_3, client_segment_4, client_segment_5
   client_segment deleted.
3. Binary variables coded numerically.
   - gender (M/L) -> 1/0
   - married_cd (TRUE/FALSE) -> 1/0


Next steps: 
- Imputation - selected constant, or predicted values?
- Min-max normalization?
- Duplicate removal?
