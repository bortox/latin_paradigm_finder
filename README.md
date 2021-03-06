##### Italiano

## Paradigmi !

> Hai un noioso compito di scrivere tutti i paradigmi presenti in una versione? Questo è lo script che fa per te! Trova tutti i paradigmi di una versione, togli loro gli accenti e salvali in una pratica lista in un batter d' occhio!

<img src="https://raw.githubusercontent.com/bortox/latin_paradigm_finder/main/img/command-prompt.png" align="Center">

### Installazione

1. Installa Python3
2. Installa pip
3. Esegui il comando `pip install latin_paradigm finder`
    - se non funziona, allora scrivi `pip3 install latin_paradigm_finder`
4. Scrivi sul tuo terminale `paradigmi`

<sub> Se volete del <a href="mailto:borto@tuta.io">supporto tecnico</a> potrei rispondervi tardi, potete anche aprire una issue qui su GitHub. </sub>

---

#### Example video
<a href="https://asciinema.org/a/381561"><img src="https://asciinema.org/a/381561.png"></img></a>


---

##### English
## Latin paradigm finder
### Introduction

This code helps to find the paradigms present in a Latin version, and to create a text file of them.

It works by webscraping [Dizionario Latino Olivetti](https://www.dizionario-latino.com/) and checking if every word of the version is a verb. It can also find disambiguation pages and let you choose.

It makes a database where all  the words information is stored, so it doesn't webscrape too much.

### Installation ( compile from source )

> The code is cross platform, I will soon upload how to install on Windows and MacOS

**Steps for Ubuntu 20.04**
1. Open a terminal with CTRL + ALT + T
2. Copy and paste these commands for installation

      `sudo apt-get install python3 python3-pip git`
	  
      `git clone https://github.com/bortox/latin_paradigm_finder && cd latin_paradigm_finder && sudo python3 setup.py install && cd ../ && sudo rm -rf latin_paradigm_finder`

### Installation ( pip3 )
1. Open a terminal with CTRL + ALT + T
2. Copy and paste these commands for installation

      `sudo apt-get install python3 python3-pip git`
	  
      `sudo pip3 install latin_paradigm_finder`
   
#### Short video of compiling from source
<a href="https://asciinema.org/a/381560"><img src="https://asciinema.org/a/381560.png"></img></a>


### Open the program
**Type**  `paradigmi` in your terminal to open the program
###### Enjoy the time saved to you by this paradigm finder script!
