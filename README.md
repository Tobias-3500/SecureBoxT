<style>
/* Fjerner den grimme standard trekant */
details > summary {
  list-style: none;
}
details > summary::-webkit-details-marker {
  display: none;
}

/* Designet af selve boksen */
details {
  border: 1px solid #e1e4e8;
  border-radius: 8px;
  padding: 0;
  margin-bottom: 20px;
  background: #ffffff;
  box-shadow: 0 3px 6px rgba(0,0,0,0.05); /* En lille lækker skygge */
  overflow: hidden;
  transition: all 0.3s ease;
}

/* Når man holder musen over */
details:hover {
  box-shadow: 0 6px 12px rgba(0,0,0,0.1);
  transform: translateY(-2px); /* Løfter boksen en lille smule */
}

/* Designet af overskriften (Knappen) */
summary {
  background-color: #f6f8fa;
  padding: 15px 20px;
  cursor: pointer;
  font-weight: bold;
  font-size: 1.2em;
  color: #24292e;
  position: relative;
  display: flex;
  align-items: center;
  justify-content: space-between;
}

summary:hover {
  background-color: #e1e4e8; /* Mørkere når man peger */
}

/* Indholdet (Teksten) */
.content {
  padding: 20px;
  border-top: 1px solid #e1e4e8;
  background-color: #fff;
}

/* Det lille plus/minus ikon ude til højre */
summary::after {
  content: '+'; 
  font-size: 1.5em;
  font-weight: bold;
  color: #0366d6;
  transition: transform 0.2s;
}

/* Når boksen er åben, skift plus til minus */
details[open] summary::after {
  content: '-';
  color: #d73a49;
}
details[open] summary {
  background-color: #f1f8ff; /* Lys blå baggrund når åben */
  border-bottom: 1px solid #c8e1ff;
}
</style>

# 🚀 Min Praktik Logbog

Her dokumenterer jeg min rejse som selvstændig. Klik på ugerne for at se detaljerne.

<br>

<details open>
<summary>📅 Uge 3: Sikkerhed & Overvågning</summary>
<div class="content" markdown="1">

**Fokus:** Sikkerhedsopgradering, privatlivs-implementering (DNS/Adblock) og netværksovervågning.

---

### **Mandag**
**Research & Analyse.** Fortsatte arbejdet med konkurrentanalysen. Fordybede mig desuden i teknisk dokumentation for kommende implementeringer: Wireguard, OISD adblock og DNS over HTTPS.

---

### **Tirsdag**
**Sikkerhed & Segmentering.** Færdiggjorde konfigurationen af firewall-regler og VLAN-segmentering for at sikre netværkets integritet.

---

### **Onsdag**
**Privatliv & Filtrering.** Implementerede OISD adblocker på netværksniveau for at fjerne reklamer og tracking, samt opsatte krypteret DNS (DNS over HTTPS).

---

### **Torsdag**
**Overvågning.** Opsatte værktøjer til analyse af netværkstrafik på routeren for at kunne monitorere dataflow og ydeevne i realtid.

</div>
</details>

<details>
<summary>📅 Uge 2: Analyse & Aftaler</summary>
<div class="content" markdown="1">

**Fokus:** Konkurrentanalyse, forretningsaftaler og avanceret netværkskonfiguration.

---

### **Mandag**
**Netværk & Strategi.** Implementerede Bridge VLAN Filtering. Påbegyndte konkurrentanalyse for at kortlægge markedet.

---

### **Tirsdag**
**Mødeaktivitet.** Deltog i månedsmøde i Boxen og arbejdede videre med dybdegående konkurrentanalyse.

---

### **Onsdag**
**Aftaler & Hardware.** Afholdt kontraktmøde i Boxen. Implementerede teknisk support for ekstern USB-adapter.

---

### **Torsdag**
**Port-konfiguration.** Konfigurerede de fysiske porte på Raspberry Pi-enheden og udførte fejlfinding på systemet.

---

### **Fredag**
**Status & Sikring.** Afholdt møde med mentor og gennemgik projektets status. Implementerede feedback i projektplanen (herunder tilføjelse af Wireguard VPN). Sikrede desuden systemet ved at lave et fuldt backup-image.

</div>
</details>

<details>
<summary>📅 Uge 1: Opstart & Setup</summary>
<div class="content" markdown="1">

**Fokus:** Administrativ opstart, systemetablering og grundlæggende netværksarkitektur.

---

### **Mandag**
**Praktisk opstart.** Bestilte komponenter, fik CVR-nummer på plads og registrerede praktikken formelt.

---

### **Tirsdag**
**Planlægning.** Udarbejdede netværksdiagram og indgik lejekontrakt med Boxen.

**Netværksdiagram:**
![Mit Netværksdiagram](diagram.png)

---

### **Onsdag**
**System Etablering.** Installerede styresystem (OpenWRT) på hardwaren og etablerede sikker adgang via SSH.

---

### **Torsdag**
**Netværk & Drivere.** Konfigurerede WAN (Internet) og LAN interfaces. Løste udfordringer med drivere og fik succesfuldt hul igennem til internettet via USB-adapter.

---

### **Fredag**
**VLAN & Fejlfinding.** Arbejdede med opsætning af VLANs (Virtual LANs) for at segmentere netværket, samt fejlfinding på konfigurationen.

</div>
</details>
