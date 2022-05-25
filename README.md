# miRNA-map
Welcome to the miRNA Heatmap. The goal of this project is as follows:

1) Display 8-length sequences of 'A', 'T', 'G', 'C', in a 2d array
2) create heatmap of known miRNA using the 2d array

The challenge of creating a 2d array of sequences is deciding how to organize it. We started by deciding that each corner would correspond to a particular nucleotide. To accomplish this, I created a fucntion that generates the different ATGC strings and sorts them according to the frequency of a given character. 
