# 💻 CMPINF 1205 Privacy Project  
Jennifer Zheng | jez38@pitt.edu

## 🗒️ About the Project
This repository contains my final project for the class CMPINF 1205: Comparative Digital Privacies at the University of Pittsburgh. By analyzing 115 website privacy policies put together by [The Usable Privacy Policy Project](https://usableprivacy.org/), this project aims to show that current privacy policies tend to benefit companies rather than the everyday people they are meant for. The dataset includes websites with a wide variety of Alexa Ranks and from various sectors such as news, entertainment, and business. It also includes social media such as Instagram, large companies like Amazon and Walmart, and several government sites.  After retrieving and cleaning all privacy policies, I look through the perspective of the user and examine their readability using three metrics: length, legalese, and reading grade level. From the company side, I look for key words that may indicate that a company is using collected informtion for profit, and I attempt to discover how much money companies get for doing this. 

Please note that this is not a definitive analysis. This was done using what resources and knowledge I had, and while it certainly supports my argument, this does not mean that _all_ privacy policies are written for the benefit of the company rather than the users. 

My code and explanations can be found in `main.ipynb`. Enjoy! ❤️

## 🛠️ Built With
* Jupyter Notebook
* Python
* BeautifulSoup
* pandas

## 🗂️ About the Data
"The OPP-115 Corpus (Online Privacy Policies, set of 115) is a collection of website privacy policies (i.e., in natural language) with annotations that specify data practices in the text. Each privacy policy was read and annotated by three graduate students in law.

The dataset is made available for research, teaching, and scholarship purposes only, with further parameters in the spirit of a Creative Commons Attribution-NonCommercial License. A commercial license for the annotation files ("annotations" and "consolidation" sub-folders in the zip file) is available here. For all other questions, contact Prof. Norman Sadeh.

If you use this dataset as part of a publication, you must cite the following paper:

`The creation and analysis of a website privacy policy corpus. Shomir Wilson, Florian Schaub, Aswarth Abhilash Dara, Frederick Liu, Sushain Cherivirala, Pedro Giovanni Leon, Mads Schaarup Andersen, Sebastian Zimmeck, Kanthashree Mysore Sathyendra, N. Cameron Russell, Thomas B. Norton, Eduard Hovy, Joel Reidenberg, and Norman Sadeh. In Proceedings of the 54th Annual Meeting of the Association for Computational Linguistics, Berlin, Germany, August 2016.`  

The above paper is also an essential read for understanding the structure and contents of the corpus."  

From [The Usable Privacy Policy Project Data and Tools](https://usableprivacy.org/data)

## 🔖 License  
This project is licensed under Attribution-NonCommercial 4.0 International (CC BY-NC 4.0). The license can be found at [creativecommons.org](https://creativecommons.org/licenses/by-nc/4.0/legalcode), and a human-readable summary can be found [here](https://creativecommons.org/licenses/by-nc/4.0/).
