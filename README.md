# UVM Salary Project

This is a python datascience project exploring all publically available salary data for University of Vermont employees over 20 years.  The goal of this project is to make the data more accessible for the public eye, and to even allow users to interact with the data through a json of the data in a browser. 

The data is available <a href="https://www.uvm.edu/~oir/?Page=base_pay.html&SM=submenu_fac_staff.html">here</a>.


## Process of Project
Lorem ipsum dolor sit amet, consectetur adipisicing elit. Soluta, pariatur! Maxime, architecto quam, adipisci placeat tenetur in veniam ab aut deleniti sint porro, modi. Non repudiandae hic veritatis et aliquam.

### I.) Processing Data

Part A: converting pdf data
1. Obtain all the raw pdf files from the <a href="https://www.uvm.edu/~oir/?Page=base_pay.html&SM=submenu_fac_staff.html">UVM website</a>

2. User pdfMiner (python package) to convert the pdf into a text file:

    ```
    $ pdf2txt.py -o data/sr15_raw.text data/sr15.pdf 
    ```

3. Parse through the text file to make a csv file
4. write a test that accepts name and returns criteria to test random points

Part B: scraping uvm website
	
1. Get netID of each employee
2. Search directory of website 
3. * Scrap all information!!

### II.) Organize Data

1. Store all the data in mongoDB or JSON
2. Store data in csv --> dataframe object easily in pandas

Part A:

### III.) Display Data



<hr>


## Built With

* <a href="http://euske.github.io/pdfminer/index.html">pdfMiner</a> - a python package that converts pdf files to text
* pandas - dataframe python
* numpy - 


## Authors

* **Alan Chu** - *Initial work* - 

## Acknowledgments

* 
