# ABB - TheCrypticWebsite

En CTF uppgift för skolan. Deltagarna ska hitta och knäcka ett python-script för att få flaggan.

Länk till hemsidan: [TheCrypticWebsite](https://gustavs-ctf.webflow.io)

## Beskrivning

TheCrypticWebsite är en CTF uppgift för skolan. Deltagarna ska hitta och knäcka ett python-script för att få flaggan. Scriptet är skrivet i python och är krypterat med hjälp av en hemlig nyckel. Deltagarna ska hitta nyckeln och dekryptera scriptet för att få flaggan.

### Dependencies

- Python
- Webbläsare

## Hjälp / Hints

### Ledtråd 1

Var nogrann med att inspektera webbsidan...

### Ledtråd 2

Använd 'Inspect Element' och studera lågt. Kanske finns det något gömt?

### Ledtråd 3

En av de mest använda css-metoderna för att göra saker genomskinligt är 'opacity: 0'. Kan du hitta något som är dolt?

### Ledtråd 4

Kika på hemsidans css under klassen 'banana-secret'. Se något tokigt ut?

### Ledtråd 5

Du sköker ett hemligt Python-script. Det gömmer sig på hemsidans nedre del. 

### Ledtråd 6

Python scriptet är krypterat med en hemlig nyckel. Kan du hitta nyckeln? Hemsidan kan vara till hjälp...

### Ledtråd 7

Python scriptets hemliga nyckel är 'banana'

### Lösning:

1. Inspektera hemsidan och hitta den gömda scriptet.
2. Använd nyckeln 'banana' för att dekryptera python scriptet.
3. Flagga: '210s{cr1515_pull_6a476c8f}'

## Version History

- 0.2
  - Förtydligade ledtrådar
  - See [commit change]() or See [release history]()
- 0.1
  - Första verisonen