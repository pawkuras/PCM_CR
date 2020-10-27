# PCM_CR 

Reducing CR in Pairwise Comparison Matrices using different algorithms. v0.1<br/>
Jiri Mazurek, Dominik Strzalka, Bartosz Kowal, Pawel Kuras<br/>
Silesian University in Opava (CZ), Rzeszow University of Technology (PL), Nov 2020<br/>

All instructions are present during executing the program on Microsoft Windows platform.<br/>
Program will return correct results ONLY if matrices will be properly construct pairwise comparison matrices.<br/>
To be 100% sure, we recommend using our generating functions.<br/>
Please unpack programm in localization, where Administrator rights are not neccesary to write/load file from.<br/>
All files will be available in working directory of app.<br/>

Format of properly formatted matrix_load.csv document:<br/>

for n=4 (n is matrix size)<br/>
```
A11,A12,A13,A14,A21,A22,A23,A24,A31,A32,A33,A34,A41,A42,A43,A44,(next columns doesn't matter, you could use also generated matrix_with_values.csv from app)
1.0,0.125,4.0,0.2,8.0,1.0,0.5,0.3333,0.25,2.0,1.0,0.1429,5.0,3.0,7.0,1.0,(next columns doesn't matter)
... next rows
```
for n=8<br/>
```
A11,A12,A13,A14,A15,A16,A17,A18,A21,A22,A23,A24,A25,A26,A27,A28,A31,A32,A33,A34,A35,A36,A37,A38,A41,A42,A43,A44,A45,A46,A47,A48,A51,A52,A53,A54,A55,A56,A57,A58,A61,A62,A63,A64,A65,A66,A67,A68,A71,A72,A73,A74,A75,A76,A77,A78,A81,A82,A83,A84,A85,A86,A87,A88,(next columns doesn't matter, you could use also generated matrix_with_values.csv from app)
1.0,6.0,0.1429,3.0,4.0,4.0,5.0,9.0,0.1667,1.0,9.0,6.0,3.0,0.125,7.0,0.1667,7.0,0.1111,1.0,4.0,5.0,8.0,3.0,0.1111,0.3333,0.1667,0.25,1.0,8.0,9.0,0.1429,1.0,0.25,0.3333,0.2,0.125,1.0,0.2,6.0,4.0,0.25,8.0,0.125,0.1111,5.0,1.0,0.1667,0.2,0.2,0.1429,0.3333,7.0,0.1667,6.0,1.0,0.1111,0.1111,6.0,9.0,1.0,0.25,5.0,9.0,1.0, (next columns doesn't matter)
... next rows
```
