# Hitachi - TheCrypticWebsite

En CTF uppgift för skolan. Deltagarna ska hitta och knäcka ett python-script för att få flaggan.

Länk till hemsidan: [TheCrypticWebsite](https://gustavs-ctf.webflow.io)

## Beskrivning

TheCrypticWebsite är en CTF uppgift för skolan. Deltagarna ska hitta och knäcka ett python-script för att få flaggan. Scriptet är skrivet i python och är krypterat med hjälp av en hemlig nyckel via en XOR-chiper. Deltagarna ska hitta nyckeln och dekryptera scriptet för att få flaggan.

### Dependencies

- Python
- Webbläsare

## Hjälp / Hints

### Ledtråd 1

'Var nogrann med att inspektera webbsidan...'

Försöker peta deltagarna åt rätt håll. Använda inspector/inspect element.

### Ledtråd 2

'Använd 'Inspect Element' och studera lågt. Kanske finns det något gömt?'

Att man ska använda inspektorn och leta på hemsidans nedre del.

### Ledtråd 3

'En av de mest använda css-metoderna för att göra saker genomskinligt är 'opacity: 0'. Kan du hitta något som är dolt?'

Försöker visa deltagarna att python-scriptet är gömt med opacity 0

### Ledtråd 4

'Kika på hemsidans css under klassen 'banana-secret'. Se något tokigt ut?'

Ger användarna rätt klass att modifera css med.

### Ledtråd 5

'Du sköker ett hemligt Python-script. Det gömmer sig på hemsidans nedre del. '

Berättar för användarna att de söker ett pythonskript och vart det finns.

### Ledtråd 6

'Python scriptet är krypterat med en hemlig nyckel. Kan du hitta nyckeln? Hemsidan kan vara till hjälp...'

Säger till deltagarna att de behöver modifera pythonskiptets nyckel för att kunna decrypte XOR enkryperade flaggan.

### Ledtråd 7

'Python scriptets hemliga nyckel är 'banana''

Ger användarna rätt nyckel.

### Lösning:

1. Inspektera hemsidan och hitta den gömda scriptet.
2. Använd nyckeln 'banana' för att dekryptera python scriptet.
3. Flagga: '210s{cr1515_pull_6a476c8f}'
