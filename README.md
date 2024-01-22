# Projekts
## Cenas atrašana no tīmekļa vietnes
### Uzrakstītās programmas mērķis ir noteikt grāmatu cenu grāmatnīcas Jānis Rozes internetveikalā. Ir sagatavots Excel fails ar grāmatu nosaukumiem A kolonnā un attiecīgi grāmatas autoru vārdiem B kolonnā. Programmas uzdevums ir katrai grāmatais konkrētajā internetveikalā atrast cenu un izvadīt grāmatas nosaukumu, autora vārdu un cenu terminālī
## Izmantotās bibliotēkas
### ***Openpyxl***
### Tā kā grāmatu saraksts ar kuru ir jāstrādā atrodas tieši Excel failā, tad lai ar to strādātu, bija nepieciešams importēt openpyxl bibliotēku. Ar tās palīdzību tik atvērts nepieciešamais fails un lapa. Grāmatas nosaukums un autora vārds bija ierakstīti divās dažādās kolonnās. Lai atvieglotu meklēšanu tīmekļa vietnē, ar bibliotēkas palīdzību tika apvienots grāmatas nosaukums un autora vārds un rezultāts tika pievienots jaunā sarakstā ar nosaukumu GramatuSaraksts

### ***Selenium***
### Selenium ir bibliotēka, kas ļauj automatizēt tīmekļa pārlūkprogrammas darbību. Konkrēti šajā gadījumā tā tika izmantota, lai katram iepriekš minētā saraksta elementam(katrai grāmatai) atrastu cenu internetveikalā. Tika dotas komandas, kas ievada saraksta elementus meklēšanas laukā, nospiež pogu meklēt, un nolasa cenu konkrētajai grāmatai. Programmā tika norādīts, ka tiek strādāts tieši ar Chrome un importētas webdriver, Services un By klases.

### ***Time***
### Cenšoties palaist kodu es arī saskāros ar problēmu, ka man grāmatām terminālī nerāda cenu. Tāpēc es nolēmu importēt time, lai paspētu ielādēties tīmekļa vietne, pirms no tās tiek iegūta informācija.

## Programmatūras izmantošana
### Lai gan manis izstrādātajā programmā tika strādāts konkrēti ar grāmatu cenu atrašanu, šo kodu var izmantot, lai meklētu cenas jebkam tīmekļa vietnē. Vienīgi atkarībā no tīmekļa vietnes būtu nepieciešams pamainīt ID pēc kura meklē noteiktos lapas elementus.

