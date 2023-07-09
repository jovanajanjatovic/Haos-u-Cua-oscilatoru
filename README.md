# Haos-u-Cua-oscilatoru
Projekat rađen u Istraživačkoj stanici Petnica, na seminaru elektronike. Ciklus seminara 2023. godine. 
Cilj projekta je simulacija i sinhronizacija haosa u Čua oscilatoru. Na zimskom seminaru, potrebno je konstruisati Čua kola na protobordu i u LTspice-u (postoje 2 načina) i uveriti se da haos postoji. Sledeći korak je dizaj PCB ploče u Altium-u i slanje iste na proizvodnju. Zatim, plan je da napravim simulaciju sa mogućnošću menjanja parametara u MATLAB-u, Simulink. Zatim, sinhronizovati ploče (po principu Master i Slave Chua) i naći dolučiti se za primenu tako sinhronizovanog haosa. Postoji nekoliko opcija: šifrovanje biomedicinske slike sa memristorom, neuromuskularna električna stimulacija poistovećenu haosom nastalim u Čua kolu (capacitor-switch model of excitatory and inhibitory neuron), simulacije nervnih impulsa tokom epileptičnog napada.

<br>šema kola 1: 
<br>
![image](https://github.com/jovanajanjatovic/Haos-u-Cua-oscilatoru/assets/112614758/719c2451-1889-43fe-b120-76d9445a2498)
<br>šema kola 2: 
<br>
![image](https://github.com/jovanajanjatovic/Haos-u-Cua-oscilatoru/assets/112614758/00af0b39-693f-4411-8c2f-7b293482dc22)

<br>
GIF haosa uočenom na digitalnom osciloskopu:
<br>

![cua_haos_10](https://github.com/jovanajanjatovic/Haos-u-Cua-oscilatoru/assets/112614758/c219bf27-c3d6-48cd-948f-6a3f467e32fd)



<br>

![cua_haos](https://github.com/jovanajanjatovic/Haos-u-Cua-oscilatoru/assets/112614758/89ae54bb-868d-467a-a895-32ad4264c8f9)



