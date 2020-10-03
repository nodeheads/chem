# Funkcionalna specifikacija - 1. faza (frontend only)

> Cilj - stvoriti edukativnu aplikaciju za učenik. Aplikacija pokriva određena znanja iz kemije, većinski poznavanje formule i strukture poznatijih i važnijih spojeva, kao i temeljna znanja s područja organske kemije.

# Infomacije
chemical compound = molecule  

kemijski spojevi popularni na laičkim nazivima:
- modra galica
- soda bikarbona..

anorganske kiseline i molekule uključene u opće poznate kemijske procese
- npr. stvaranje šećera prilikom fotosinteze

# Components 
## Chemical compound card
- kartica s vizualnim prikazom strukture kemijskih spojeva
- on hover animacija: prikaže podataka i zavrti molekulu
- click na otvara `Chemical compound`

## Chemical compound
- polustranica kemijskog spoja
- informacije o kemijskom spoju
    - 
    - url na wiki (dinamički)
- vizualni prikaz strukture kemijskih spojeva

## Chemical process
- animacija `Chemical compound` komponenti

## Quiz  
- bez backenda i baze
- kvizovi kojima učenici provjeravaju znanje

# Funkcionalna specifikacija - 2. faza (+ backend)

> Poželjno je da aplikacija ima user login i do neke mjere prati napredak osobe koja ju koristi. Nakon prijave, aplikacija treba prikazati nekoliko kartica

# Components 

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


