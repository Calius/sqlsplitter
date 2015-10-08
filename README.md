# sqlsplitter
A simple console tool that splits large SQL files into smaller ones.


Usage:
- Either compile from source or use the precompiled version inside the bin folder.
- Simply use sqlsplitter <large_file.sql> <size-of-each-part-in-bytes>
  Example: sqlsplitter largeFile.sql 500000000 splits a large sql file into 500MB chunks which you can then import in sequence.
