Tarkastelin Pythonin linttaus, testaus ja build -työkaluja.
Staattisiin testeihin löytyi lintereitä moneen eri tarkoitukseen erikoistuneena, näistä itselleni ennestään tuttu on Pylint, jolla voidaan tarkastaa koodin virheitä, asetetun koodistandardin noudattamista ja koodihajua. 
Löytyi myös lintereitä, jotka olivat eri käyttötarkoituksen omaavien lintereiden yhdistelmiä.
Löytyneitä yhdistelmälintereitä on mm.
Flake8, joka yhdistää ohjelman analysointiin ja virheiden ilmoittamiseen erikoistuneen PyFlakes -lintterin, tyylin noudattamisen pyCodeStyle -lintterin ja ohjelman monimutkaisuutta tarkastelevan Mccaben.
Pylamessa on edellä mainittujen lisäksi yhdistettynä vielä Pylint, Redon ja gjslint.
Lintterit voivat erikoistua tarkastelemaan koodausvirheitä, koodihajua, valittujen standardien noudattamista, tyylin noudattamista, docstringien oikeellisuutta, turvallisuutta, ohjelman monimutkaisuutta ja jopa itse formatoida koodin noudattamaan tarkasti määriteltyjä standardeja Black -lintterin tapaan.
Yksikkötestauksessa käytettävä Pythonin oma unittest on pohjana myös paljon käytetylle ja laajalle Pytest -testikirjastolle. Pytest-cov taas keskittyy testien peiton mittaamiseen, jotta voidaan varmistaa, että koodi testataan riittävän kattavasti. 
End-to-end testeihin löysin itsellenikin tutut Seleniumin ja Robotin, joita olen käyttänyt vaihtelevalla menestyksellä :D Pylonium tai SeleniumBase -plugin vaikuttaisi kokeilemisen arvoiselta Pytestin kanssa seuraavia Python -projekteja ajatellen e2e -testaukseen. Löytyi myös Nose2 -kirjasto, jolla voidaan Pytestin tavoin tehdä yksikkötestien lisäksi myös integraatiotestejä.
Build on Python -sovelluksissa normaalia yksinkertaisempi johtuen Python tulkista, jonka johdosta varsinaista kääntämistä ei tarvitse suorittaa. Löysinkin lähinnä paketointiin liittyvää tietoa, varsinaisia build -työkaluja oli vaikeampi löytää, ehkä Pypa build voitaisiin laskea sellaiseksi.