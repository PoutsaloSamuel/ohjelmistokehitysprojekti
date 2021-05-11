# ohjelmistokehitysprojekti

## Testin suoritus
1. Asenna tarvittavat kirjastot kuten Robot Framework, Appium ja muut
2. Käynnistä ohjelmistoprojekti 2 kurssin ApiNaattorit projekti consolessa
   ```
   Console:
   cd C:\Example-folder\ApiNaattorit-main
   expo start
   ```
3. Käynnistä Android Emulaattori consolessa tai Android Studiossa
   ```
   Console:
   cd C:\Users\YOURUSER\AppData\Local\Android\Sdk\emulator
   emulator -list-avds ---> emulaattorin nimi
   ./emulator.exe -avd "Emulaattorin nimi"
   ```
4. Käynnistä Appium serveri consolessa
   ```
   Console:
   appium
   ```
5. Vaihda oikeaan kansioon
   ```
   Console:
   cd C:\Example-folder\Tests
   ```
6. Kopio Expon linkki leikepöydälle ennen kohdan 7. suorittamista
   ```
   Example: exp://192.168.42.87:19000
   ```

7. Suorita testi
   ```
   Console:
   robot testi.robot
   ```
