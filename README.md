# PokeDex
This web-application version of the PokeDex is one of my first projects! 

Access here: http://grakamoli.pythonanywhere.com/pokeMain

## Summary
This web application web-scraped off of Bulbapedia, and took information provided by the PokeAPI to create a multiple tables in SQLite. Using Bottle, a Python framework, I created a comprehensive encyclopedia of all Pokemon regions, pokemons, and gym leaders.

### Goal
PokeDex's goal is to be a simple and intuitive web-application that anyone could easily navigate for Pokemon information. 

I also wanted PokeDex to be able to stay updated with all new releases of the games. As such, the login system is made uniquely for an Administrator, who can choose to 'update' my database holding all the Pokemon information. The update process takes several minutes and, if abruptly halted, can ruin the database. Hence, this option is locked behind an Administrator login.

Lastly, the Gym Leader information was a result of web-scrapping from Bulbapedia. The pages are by no means perfect, but illustrate an understanding of using recursion where appropiate.

### Core Concepts
Core concepts included in this project include:
- Python, HTML
- server-side _and_ client-side web development
- web-scrapping
- API accessing
- database operations with SQLite
- basic log-in system (not secure!)

# Sources
All pokemon information were provided by PokeAPI and Bulbapedia. Pokemon is the property of Nintendo. None of the information belongs to me. I only took all the information out there and converged it into one project. 
