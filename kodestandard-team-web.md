
# Team Web's Standarder :rocket:

Hej! Det er sjovere og nemmere at arbejde sammen, når vi er enige om et par standarder. Når vi lærer mere, så opdaterer vi standarden.

## Versioner 
- Python >= 3.6 [[Nyeste er 3.8]](https://docs.python.org/3/)
- Django >= 2.2 [[Nyeste er 2.2.7]](https://docs.djangoproject.com/en/2.2/)
- HTML5 [[Nyeste]](https://www.w3schools.com/html/html5_intro.asp)
- JavaScript >= ES6 [[Nyeste er ES6]](https://www.w3schools.com/js/js_es6.asp)
- C++ >= C++11 

## Kodestandarder
Det giver mest mening at følge typiske standarder for de sprog, vi bruger.

### Python
- De fleste skriver Python efter [PEP8](https://www.python.org/dev/peps/pep-0008/). Så det prøver vi også.
- Det er en lang kodestandard, vi kan slå op i efter behov.
- Væsentligst til at komme i gang:
	* Benyt 4 mellemrum til hver indrykning.
		> Use 4 spaces per indentation level.
		> Spaces are the preferred indentation method.
		> Python 3 disallows mixing the use of tabs and spaces for indentation.
	* Linjelænger, prøv at holde dem under 80 tegn
		> Limit all lines to a maximum of 79 characters.
		> ...makes it possible to have several files open side-by-side, and works well when using code review tools that present the two versions in adjacent columns.
	* Filer gemmes i UTF-8, men lad nu være med at bruge ikke-ascii-tegn i koden
	* Selvom det er sjovt, så går *my_:monkey:_function(:banana:, :beer:)* nok ikke...
		> Code in the core Python distribution should always use UTF-8.
		> All identifiers in the Python standard library MUST use ASCII-only identifiers, and SHOULD use English words wherever feasible.
	* Slå op i standarden for at se, hvordan man navngiver en funktion, en klasse, en variabel, osv...

### HTML5
- Vi følger [HTML5 Style Guide](https://www.w3schools.com/html/html5_syntax.asp) fra w3schools.

### JavaScript
- Vi følger [JS Style Guide](https://www.w3schools.com/js/js_conventions.asp)

### C/C++
- Vi benytter AU's kodestandard.

## Dokumentation

- Vi dokumenterer vores kode, mens vi skriver.
- Der er forskel på at kommentere og dokumentere. Det er godt at kommentere. Det er krævet at dokumentere.
- Vi brug de værktøjer, der er naturlige til det sprog, vi skriver i.
	* **Python**:
		- Vi bruger docstrings til at dokumentere alle moduler, klasser og funktioner. Se fx [Documenting Python code](https://realpython.com/documenting-python-code/). 
		- Vi bruger Sphinx til at samle dokumentation senere.
		- Hvis vi har lyst, kan vi derfor skrive formattere dokumentationen med [ReStructuredText](https://en.wikipedia.org/wiki/ReStructuredText).
	* **HTML**:
		- Er nærmest selv-dokumterende, så no worries.
		- Blokke kan indsættes med `<!-- block doc -->` 
	* **JavaScript**:
		- Vi må vurdere, om der er et behov, hvis vi skal skrive en væsentlig mængde. 
	* **C/C++**:


## Testing


## Versionsstyring



> Written with [StackEdit](https://stackedit.io/).
<!--stackedit_data:
eyJoaXN0b3J5IjpbMTIwODA3NzU3MSwtMjA1MTY0MTg4NSw1OD
Y2MjgxOTVdfQ==
-->