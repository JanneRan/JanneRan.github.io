**Github** lisäosa Visual Studio Codessa hoitaa tiedostojen siirron pääasiassa ilman terminaalia.  
Tässä kuitenkin tiedostojen siirtoon tarvittavat käskyt. Myös käyttäjänimi ja sähköpostiosoite on kätevä laittaa terminaalista.

##### Asetetaan käyttäjänimi ja sähköpostiosoite:  
_git config --global user.name "Janne Rantala"_  
_git config --global user.email "janne.rantala@centria.fi"_  
  
##### Tarkistetaan, että nimi ja mailiosoite meni oikein:  
_git config --global user.name_  
_git config --global user.email_  
  
##### Tarkistus, että oikeat tiedostot on valittu committia varten:  
_git status_  
  
##### Lisätään tiedosto lähetettäviin tiedoistoihin, esimerkissä index.md  
_git add index.md_  
  
##### Tehdään commit, eli tallennetaan projektin versio.  
_git commit -m "päivitystä"_  
  
##### Lähetetään projektin tiedostot githubiin  
_git push_  