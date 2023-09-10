# PLSQL_resequence_package



--- package written in sql that contains a procedure and 2 cursors for grabbing data based on user input. This uses a row_number
--- window function to sequence the rows without extra permissions and avoiding triggers. This is helpful when working with and ERP
--- that overrides any changes that are made to tables. In this particular sample the seqno column had reached it's 3 integer max 
--- but there was plenty of space left. This modification was accomodated by the merge into script  Merge_sequence to take advantage of 
--- the unused realestate.
