
![](resources/logo.png)

# Funkcionalna specifikacija - 1. faza (frontend only)

> Cilj - stvoriti edukativnu aplikaciju za učenik. Aplikacija pokriva određena znanja iz kemije, većinski poznavanje formule i strukture poznatijih i važnijih spojeva, kao i temeljna znanja s područja organske kemije.

> chemical compound = molecule  

> kemijski spojevi popularni na laičkim nazivima:
> - modra galica
> - soda bikarbona..

> anorganske kiseline i molekule uključene u opće poznate kemijske procese
> - npr. stvaranje šećera prilikom fotosinteze

## ChemicalCard (Matej)
- kartica s vizualnim prikazom strukture kemijskih spojeva
- on hover animacija: prikaže podataka i zavrti molekulu
- click na otvara `Chemical compound`

## ChemicalPage (Uršula)
- polustranica kemijskog spoja
- informacije o kemijskom spoju
    - url na wiki (dinamički) (matej?)
        - restAPI sa informacijama kemijskih spojeva
        - web scrape 
        - ...
- vizualni prikaz strukture kemijskih spojeva

## ChemicalProcess
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
