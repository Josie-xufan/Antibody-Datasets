# The tutorial for the databases of antibody

## SAbDab

- **Link:** https://opig.stats.ox.ac.uk/webapps/sabdab-sabpred/sabdab

- **Brief Introduction:**  A database containing all the antibody structures available in the PDB file.

- **Statistics:**  

  ![image-20240415160934327](C:\Users\Administrator\AppData\Roaming\Typora\typora-user-images\image-20240415160934327.png)

- **Download:** ../antibody_design/diffab/data(Note that ../ refers to my own directory.)

  ![image-20240416111101802](C:\Users\Administrator\AppData\Roaming\Typora\typora-user-images\image-20240416111101802.png)

## PBD File

- **Reference:** https://www.biostat.jhsph.edu/~iruczins/teaching/260.655/links/pdbformat.pdf

- **Each line** in the PDB file refers to a record, which has several different types, including ATOM, HETATM...

- **Examples of PDB Format:**

  ![image-20240416111459254](C:\Users\Administrator\AppData\Roaming\Typora\typora-user-images\image-20240416111459254.png)

  - col 1: record type
  - col 2: atom serial number
  - col 3: atom name (C: carbon atoms, N: nitrogen, O: oxygen, the next character is the remoteness indicator code, the last character is a branch indicator)
  - col 4: residue type
  - col 5: residue sequence number
  - col 6-8: X, Y, and Z coordinate values
  - col 9: occupancy
  - col 10: temperature factor (B value)

  ![image-20240416111916113](C:\Users\Administrator\AppData\Roaming\Typora\typora-user-images\image-20240416111916113.png)

  - the fifth col is the single-character chain indicator

## Structure Display

- pymol: https://pymol.org/

