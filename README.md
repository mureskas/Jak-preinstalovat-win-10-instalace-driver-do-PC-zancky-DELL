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

![IMG20220213201747](https://user-images.githubusercontent.com/106344975/170735960-493c0aa3-1287-402a-be7b-c58267d95669.jpg)



na dalším okně jste tázáni jak chcete instalovat OS a zde kliknete na jenom nainstalovat windows: 

![IMG20220213201807](https://user-images.githubusercontent.com/106344975/170736039-de425a04-982d-48f1-a12c-e1c3e8253fb1.jpg)


Nyní musíme určit místo kam naistalovat OS popřípadě toto místo udělat vymazáním dat z disku zde kliknete na nový a poté na formátovat disk:    

![IMG20220213201844](https://user-images.githubusercontent.com/106344975/170736063-dd74e558-d0ce-4e5b-82e2-1501f8084b09.jpg)

![IMG20220213201851](https://user-images.githubusercontent.com/106344975/170736076-bb27e87a-bab7-4b20-bd7a-1c9f0e69b945.jpg)

![IMG20220213201911](https://user-images.githubusercontent.com/106344975/170736088-087fe45a-4bb7-4233-88d3-e31f682574df.jpg)



Nyní klikneme na další a spustí se instalace:

 ![IMG20220213201917](https://user-images.githubusercontent.com/106344975/170736142-b8116f6e-31ce-46b3-b002-0ebe0aeadaa9.jpg)

Během instalace se bude počítač restartovat a máte chvíli času, než se doinstaluje.
Jakmile znovu naběhne objeví se okna, která se vás ptají na podmínky jako jsou jazyk, k čemu je počítač určen, microsoft účet, apod. 

![IMG20220213202629](https://user-images.githubusercontent.com/106344975/170736181-1ea93314-a955-4b1c-9acf-01799a50a7ec.jpg)

Poté co si nastavíte počítač tak se spustí.

Nyní jdeme do finální fáze, a to je instalace ovladačů neboli driverů.
Po zapnutí prohlížeče si napíšete výrobce počítače (v mém případu DELL) a podpora nebo support
DELL má tu výhodu, že zde je program support assistant který když si stáhnete tak identifikuje váš počítač a najde určité drivery, ale samozřejmě je možné najít si je i po vlastní ose přes výrobní číslo nebo přes model vašeho PC. oté už jen jít do složky stažené soubory a proklikat instalace driverů.

