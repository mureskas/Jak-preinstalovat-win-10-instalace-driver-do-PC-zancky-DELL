# Přeinstalace win 10

ROČNÍKOVÝ PROJEKT 
Vybral jsem sis projekt, který se zaměřuje na přeinstalaci OS (windows10) pomocí flash disku a stažení driverů pro počítač značky DELL.
Na začátek si musíme připravit instalační flash disk budeme potřebovat alespoň 16GB dat, flash disk popř. jiné přenosové medium by mělo být úplně prázdné aby se instalační soubory správně nainstalovaly.

Instalační soubory stáhneme přímo ze stránek microsoftu: https://www.microsoft.com/cs-cz/software-download/windows10
Zde sjedete kousek dolů a kliknete na stáhnout nástroj. Poté se naistaluje na váš počítač program se jménem Media creaiton tool
Ten prokliknete a povolíte ho jako správce, po chvíli se vás program otáže, jestli souhlasíte s podmínkami a dostanete se do okna kde můžete buď udělat upgrade vašeho windowsu v počítači nebo vytvoříte instalační médium

![a](https://user-images.githubusercontent.com/106344975/170732859-e2a7c34d-f6c1-4266-bc95-2ea731e06a6d.png)


po kliknutí na další se objeví další okno kde se program ujišťuje jaké máte parametry windows (jazyk, architektura, …)
následně se do flashky naistalují potřebné soubory a můžete flashku nyní již používat pro boot vašeho zařízení
po zapnutí počítače přejdeme do nastavení bootu počítače (každý počítač používá jinou klávesu) 
nyní zde záleží jaký co se vám objeví, ale flash disk by měl vždy být jako UEFI boot (+ název disku nebo, nápis USB STORAGE) 
![IMG20220213195812](https://user-images.githubusercontent.com/106344975/170733083-0a8a38d5-d34d-4e4f-b4ee-c5501f46350d.jpg)

pokud zde tuto možnost nemáte lze si ji nastavit přímo v BIOSu počítače:

![IMG20220213200005](https://user-images.githubusercontent.com/106344975/170733829-73cdb961-409d-45ea-85f6-35b54b76c8f3.jpg)

poté co kliknete na možnost bootu UEFI (flashky) tak se vám zapne toto okno: 

![IMG20220213201121](https://user-images.githubusercontent.com/106344975/170733960-46908274-6b1a-4a3c-80eb-798ff1185625.jpg)


zde klikneme na další a poté na naistalovat: 

![IMG20220213201730](https://user-images.githubusercontent.com/106344975/170734098-798f38e6-d0cd-470d-a54a-20fb575aef41.jpg)


po spuštění instalace se vám ukáže okno pro zadání licenčního klíče pokud ho nemáte stačí kliknout nemám product kod: 




na dalším okně jste tázáni jak chcete instalovat OS a zde kliknete na jenom nainstalovat windows: 



Nyní musíme určit místo kam naistalovat OS popřípadě toto místo udělat vymazáním dat z disku zde kliknete na nový a poté na formátovat disk:    

Nyní klikneme na další a spustí se instalace:
 
Během instalace se bude počítač restartovat a máte chvíli času, než se doinstaluje.
Jakmile znovu naběhne objeví se okna, která se vás ptají na podmínky jako jsou jazyk, k čemu je počítač určen, microsoft účet, apod. 
Poté co si nastavíte počítač tak se spustí.
Nyní jdeme do finální fáze, a to je instalace ovladačů neboli driverů.
Po zapnutí prohlížeče si napíšete výrobce počítače (v mém případu DELL) a podpora nebo support
DELL má tu výhodu, že zde je program support assistant který když si stáhnete tak identifikuje váš počítač a najde určité drivery, ale samozřejmě je možné najít si je i po vlastní ose přes výrobní číslo nebo přes model vašeho PC. oté už jen jít do složky stažené soubory a proklikat instalace driverů.

