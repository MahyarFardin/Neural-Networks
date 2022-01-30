  # Overviwe

In this project I tried to use ANN to predict whether there are valid paychecks or not from a data were extracted from images 
that were taken for the evaluation of an authentication procedure for banknotes.

  # Features
  
1. variance of Wavelet Transformed image (continuous)
2. skewness of Wavelet Transformed image (continuous)
3. curtosis of Wavelet Transformed image (continuous)
4. entropy of image (continuous)
5. class (integer) 

  # Walkthrough

First I loaded my data (It was a text file so I manually loaded and prepared it) and I tried to gather information about the data that 
it contains but because I did not have any information about features I could not get through information of the pair plot, which seemed 
full of information because of the uncommon shapes. Then I prepared my test and train data and I applied it one by one to my models.

  # Models

- First: The simplest ANN without any addons
- Second: Added early stop because it was not efficient to do 2000 epochs 
- Third: Adding dropouts (it was not logical because of the low number of nodes I had but it did pretty well)
- Forth: I tried differant batch sizes but non of them worked well

  # Results & Ranking
  
 <table>
  <tr>
    <th>      </th>
    <th>First</th>
    <th>Second</th>
    <th>Third</th>
    <th>Forth</th>
  </tr>
  <tr>
    <td>Accuracy</td>
    <td>99.2</td>
    <td>99.5</td>
    <td>98.6</td>
    <td>97.7</td>
  </tr>
</table> 
  
  
