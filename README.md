## Latin paradigm translator

##### Introduction

This code helps to find the paradigms present in a Latin version, and to create a text file of them.

It works by webscraping [Dizionario Latino Olivetti](https://www.dizionario-latino.com/) and checking if every word of the version is a verb. It can also find disambiguation pages and let you choose.

<a href="https://asciinema.org/a/TvE5kF5kfrgZd1xhnmeiEn7fh"><img src="https://asciinema.org/a/381440.png"></img></a>

##### Installation

You need Python3 installed in your machine, along with PyPI ( pip3 ).

**Steps for Ubuntu 20.04**

1. Open a terminal with CTRL + ALT + T
2. Type 
   
      sudo apt-get install python3 python3-pip git
   
3. Type

      pip3 install -r requirements.txt

4. Type 
   
      git clone (nome repository)
   
5. Type 
   
      cd (nome repository)

4. Type

      python3 paradigmi.py

5. Enjoy the time saved to you by this paradigm finder!