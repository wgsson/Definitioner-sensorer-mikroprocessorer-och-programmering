# 🚀 AI-genererad Introduktion till sensorer, mikrocontrollers och IoT (baserad av anteckningar från föreläsning)
En nybörjarvänlig sammanfattning

Den här README:n ger en enkel och tydlig genomgång av viktiga begrepp som används i projekt med sensorer, mikrocontrollers och IoT-system. Perfekt för dig som är ny student utan förkunskaper.

---

## 📌 Scope of Interest – Vad projektet handlar om
- Sensorer som kommunicerar med andra enheter  
- Skicka data till molnet  
- Hämta data från molnet  
- Visualisera data  
- Använda open source-verktyg  
- Sensor → Mikroprocessor → Mobil enhet  

---

## 🎯 Projektets kunskapsbehov
För att genomföra projektet behöver vi:
- Förstå användare och deras kontext  
- Förstå sensorteknik, mikroprocessorer och programmering  
- Förstå hur kommunikation mellan enheter fungerar  

---

# 🔌 Sensorer – Introduktion

### Vad är en sensor?
En sensor mäter ofta **inte direkt** det vi vill mäta. I stället mäter den en fysisk förändring och omvandlar den till en elektrisk signal.

Exempel:
- En temperatursensor mäter egentligen förändringar i **spänning** orsakade av värme.
- Ljussensorer och fuktsensorer fungerar på liknande sätt.
- Vissa sensorer har flera "ben" och kan mäta flera parametrar.
- Vissa sensorer har inbyggd elektronik och kan ge färdiga digitala värden.

### Viktiga begrepp
- **Pull-up/Pull-down-resistorer:** stabiliserar signaler, t.ex. från knappar.
- **ADC (Analog-to-Digital Converter):** behövs för analoga sensorer så att mikroprocessorn kan tolka värdet i digital form (1/0).

---

# 🧠 Mikrocontrollers – Introduktion

En **mikrocontroller (uC)** är en liten dator som består av:
- **CPU (Central Processing Unit)** – utför beräkningar  
- **Minne** – lagrar data och program  
- **Interface (gränssnitt)** – där två system möts  
- **I/O (Input/Output)** – tar emot och skickar signaler  

### Inbyggda system (Embedded Systems)
- Har ett **specifikt syfte**  
- Används i t.ex. diskmaskiner, sensorer, smarta lampor  
- Är billiga och energieffektiva  

---

# 🌐 IoT – Internet of Things

**Internet of Things (IoT)** innebär att vardagliga föremål är uppkopplade mot internet.  
De kan:
- Samla data  
- Skicka och ta emot information  
- Kommunicera med andra enheter  
- Styras automatiskt eller via mobil  

Exempel: smarta klockor, lampor, bilar, kylskåp, sensorer.

---

# ⚡ ESD – Electrostatic Discharge

- Elektroner kan hoppa mellan objekt → skapar laddning  
- Laddningar strävar efter att utjämnas  
- Statisk elektricitet kan uppnå flera tusen volt  
- **Låg luftfuktighet ökar risken** för statisk elektricitet  
- Viktigt att hantera elektronik försiktigt för att undvika skador  

---

# 🧱 Programmeringsbegrepp

## 📄 Source Code (källkod)
Kod som människor skriver i ett programmeringsspråk som C, Java eller Python.

## ⚙️ Compiler (kompilator)
Program som översätter källkod till **object code** (maskinkod i form av 1:or och 0:or).

## 💾 Object Code
Maskinkod som en dator eller mikrocontroller kan köra direkt.

## 📚 Library (bibliotek)
Färdigskriven kod som kan återanvändas i projekt.

## 🔗 Linker (länkare)
Sätter ihop:
- Object code  
- Bibliotek  

→ skapar ett färdigt körbart program.

## 🧩 Firmware
Programvara som ligger lagrad i **NVM (Non-Volatile Memory)** på t.ex. en mikrocontroller.

---

# 🔄 Sammanfattning av kompilationsprocessen

1. Du skriver **källkod**  
2. Kompilatorn översätter den till **object code**  
3. Linkern sätter ihop object code med **bibliotek**  
4. Resultatet blir ett **körbart program**  

---

# 🧰 Abstraktionsnivåer

## Black Box Approach
Du behöver inte förstå allt som händer inuti ett system – det viktiga är att veta:
- Vad du stoppar in  
- Vad du får ut  

Det förenklar komplexa system.

---

# 🔌 Kommunikation: Serial vs Parallel

| Begrepp | Förklaring |
|---------|------------|
| **Serial Port** | Skickar 1 bit åt gången (lägre bandbredd) |
| **Parallel Port** | Skickar 8 bitar åt gången (högre bandbredd) |
| **Bit** | En 1:a eller 0:a |
| **Byte** | 8 bitar |

---

# 📎 Sammanfattning
Den här README:n ger en grundförståelse för:
- Sensorer  
- Mikrocontrollers  
- Kommunikation  
- IoT  
- Kompilering och firmware  
- Elektrostatiska risker  
- Abstraktionsnivåer  

Perfekt som startpunkt för projekt med uppkopplade sensorer och embedded systems.

---
