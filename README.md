# UVM Salary Project

This is a python datascience project exploring all publically available salary data for University of Vermont employees over 20 years.  The goal of this project is to make the data more accessible for the public eye, and to even allow users to interact with the data through a json of the data in a browser. 

The data is available <a href="https://www.uvm.edu/~oir/?Page=base_pay.html&SM=submenu_fac_staff.html">here</a>.


### Process of Project
Lorem ipsum dolor sit amet, consectetur adipisicing elit. Soluta, pariatur! Maxime, architecto quam, adipisci placeat tenetur in veniam ab aut deleniti sint porro, modi. Non repudiandae hic veritatis et aliquam.

## Processing Data
<ol>
	<li> Obtain all the raw pdf files from the <a href="https://www.uvm.edu/~oir/?Page=base_pay.html&SM=submenu_fac_staff.html"></a>UVM website</li>
	<li> User pdfMiner (python package) to convert the pdf into a text file</li>
    ```
	pdf2txt.py -o data/sr15_raw.text data/sr15.pdf 
    ``` 
</ol>

<hr>

## Built With

* <a href="http://euske.github.io/pdfminer/index.html">pdfMiner</a> - a python package that converts pdf files to text
* pandas - dataframe python
* numpy - 


## Authors

* **Alan Chu** - *Initial work* - 

## Acknowledgments

* 
