
![](resources/logo.png)

Airtable - https://airtable.com/tblaQEA2frSeaxME3/viwvE9UUeOIOuSWPP?blocks=hide

# Resursi
**Data**:

https://proteopedia.org/wiki/index.php/Atomic_coordinate_file

**Visualization:**

3d-force-graph = https://github.com/vasturiano/3d-force-graph

3dmolecule (spominju se kemijski file formati) - http://3dmol.csb.pitt.edu/index.html 

d3-molecule = https://github.com/arpitnarechania/d3-molecule

# Funkcionalna specifikacija - 1. faza (frontend only)

> Cilj - stvoriti edukativnu aplikaciju za učenik. Aplikacija pokriva određena znanja iz kemije, većinski poznavanje formule i strukture poznatijih i važnijih spojeva, kao i temeljna znanja s područja organske kemije.

> chemical compound = molecule  

> kemijski spojevi popularni na laičkim nazivima:
> - modra galica
> - soda bikarbona..

> anorganske kiseline i molekule uključene u opće poznate kemijske procese
> - npr. stvaranje šećera prilikom fotosinteze

## Chemical compound card
- kartica s vizualnim prikazom strukture kemijskih spojeva
- on hover animacija: prikaže podataka i zavrti molekulu
- click na otvara `Chemical compound`

## Chemical compound
- polustranica kemijskog spoja
- informacije o kemijskom spoju
    - 
    - url na wiki (dinamički)
        - restAPI sa informacijama kemijskih spojeva
        - web scrape 
        -  
- vizualni prikaz strukture kemijskih spojeva

## Chemical process
- animacija `Chemical compound` komponenti

## Quiz  
- bez backenda i baze
- kvizovi kojima učenici provjeravaju znanje

# Funkcionalna specifikacija - 2. faza (+ backend)

> Poželjno je da aplikacija ima user login i do neke mjere prati napredak osobe koja ju koristi. Nakon prijave, aplikacija treba prikazati nekoliko kartica


## Login/register 
- email
- password
- Login button
- keep me signed in
- "new to chemedu ?"
- Create your chemedu account

## User profile 
- prikaz user podataka
- mijenjanje user podataka
- statiske kvizova



