## Latin paradigm translator

##### Introduction

This code helps to find the paradigms present in a Latin version, and to create a text file of them.

It works by webscraping [Dizionario Latino Olivetti](https://www.dizionario-latino.com/) and checking if every word of the version is a verb. It can also find disambiguation pages and let you choose.

It makes a database where all  the words information is stored, so it doesn't webscrape too much.



**Short video of how it works**
<a href="https://asciinema.org/a/TvE5kF5kfrgZd1xhnmeiEn7fh"><img src="https://asciinema.org/a/381440.png"></img></a>

##### Installation

You need Python3 installed in your machine, along with PyPI ( pip3 ).

**Steps for Ubuntu 20.04**

1. Open a terminal with CTRL + ALT + T
2. Type 
   
      sudo apt-get install python3 python3-pip git

3. Type 
   
      git clone https://github.com/bortox/latin_paradigm_finder
   
5. Type 
   
      cd latin_paradigm_finder

4. Type

      sudo python3 setup.py install

5. Type

      paradigmi

   in your terminal to open the program
5. Enjoy the time saved to you by this paradigm finder!