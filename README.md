# Web
# Antud skript paigaldab automaatselt domeeni kontrolleri ja dhcp serveri
#Skripti käivitamise õpetus:

1. Lae alla skript kasutades WGET käsku:

wget https://github.com/BlackHawk171/Domeen-DHCP/raw/master/domeen2.bash

2. Anna käivititamise õigused skriptile:

chmod +x domeen2.bash

NB!!! Kui skript ei tööta sisesta järgnev käsk:

sed -i -e 's/\r$//' domeen2.bash

3. Käivita skript:

.\domeen2.bash
