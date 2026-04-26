# NetScan
Schneller Netzwerkscanner für IP‑Bereiche mit DNS‑Auflösung, Ping‑Erkennung und Port‑Checks.

NetScan ist ein kompaktes, portables Tool zur schnellen Analyse von lokalen Netzwerken.  
Es ermöglicht das Scannen beliebiger IP‑Bereiche, erkennt aktive Hosts, löst Hostnamen auf und prüft offene Ports – ideal für Administratoren, Homelab‑Setups und schnelle Netzwerkdiagnosen.

## Funktionen

### 🔍 IP‑Bereich‑Scan
- Scannt einzelne IPs, ganze Bereiche oder Subnetze
- Erkennt aktive Hosts per Ping oder ARP

### 🌐 DNS‑Auflösung
- Automatische Hostnamen‑Erkennung
- Reverse‑DNS‑Lookup für gefundene Geräte

### 🔒 Port‑Checks
- Schnelle Prüfung definierter Ports
- Erkennung offener Dienste (z. B. SSH, HTTP, RDP)

### ⚡ Performance
- Multithread‑Scan für hohe Geschwindigkeit
- Optimierte UI für schnelle Übersicht

### 🧰 Portabel
- Keine Installation notwendig  
- Läuft direkt als portable EXE  
- Keine Telemetrie, keine Cloud‑Abhängigkeiten

## Einsatzgebiete
- Netzwerk‑ und Systemadministration  
- Homelab‑Umgebungen  
- Fehlersuche und Diagnose  
- Geräte‑Inventarisierung  
- Sicherheits‑ und Port‑Checks

## Download

NetScan wird in zwei Varianten bereitgestellt:

- **Framework‑Dependent** – kleiner Download, benötigt .NET Desktop Runtime  
- **Self‑Contained** – größer, aber vollständig eigenständig und ohne Abhängigkeiten

Beide Versionen sind portabel, funktional identisch und benötigen keine Installation.

Die aktuellen Versionen findest du unter **Releases**: https://github.com/Dyonis89/NetScan/releases

## Sicherheit
NetScan führt ausschließlich lokale Netzwerk‑Scans aus.  
Es werden keine Daten an externe Dienste übertragen.

## Verwendete Bibliotheken

NetScan verwendet verschiedene Drittanbieter‑Bibliotheken.  
Die zugehörigen Lizenzinformationen befinden sich in der Datei `THIRD_PARTY_LICENSES.md`.

## Unterstütze das Projekt

NetScan entsteht komplett in meiner Freizeit.

Wenn dir das Tool gefällt oder du die Weiterentwicklung unterstützen möchtest, freue ich mich über eine kleine Anerkennung: [Unterstützen / Donate](DONATE.md)

## 📄 Lizenz

Die Anwendung ist Closed Source. Die Nutzung und Weitergabe der Binaries ist erlaubt.
Der Quellcode bleibt privat.
