# MAC Adressen

_Eine Zusammenfassung von René Barthel._

Eine MAC-Adresse (Media Access Control-Adresse) ist eine eindeutige Kennung, die Netzwerkgeräten auf der Datenlink-Ebene (Schicht 2) des OSI-Modells zugewiesen ist. Sie dient dazu, Geräte in einem lokalen Netzwerk (LAN) zu identifizieren und zu unterscheiden. Hier sind einige wichtige Informationen über MAC-Adressen:

1. Einzigartigkeit: Jede MAC-Adresse ist weltweit eindeutig. Dies bedeutet, dass keine zwei Netzwerkgeräte dieselbe MAC-Adresse haben dürfen. Diese Einzigartigkeit wird durch die Hersteller von Netzwerkadaptern gewährleistet, die die ersten sechs Zeichen der MAC-Adresse, die als OUI (Organizationally Unique Identifier) bezeichnet werden, vergeben. Die restlichen Zeichen sind von der Herstellerseite frei wählbar.

2. Physische Adresse: Die MAC-Adresse ist auch als physische Adresse bekannt, da sie in der Hardware des Netzwerkadapters eingebettet ist. Dies unterscheidet sie von IP-Adressen, die auf der logischen Ebene (Schicht 3) operieren.

3. Darstellung: Eine MAC-Adresse wird normalerweise als eine Zeichenfolge von zwölf Hexadezimalziffern dargestellt, die durch Doppelpunkte oder Bindestriche getrennt sind. Zum Beispiel: "00:80:41:ae:fd:7e".

4. Universell und Lokal administrierte Adressen: Es gibt zwei Hauptarten von MAC-Adressen: Universell administrierte Adressen (UAA) und lokal administrierte Adressen (LAA). UAAs werden von Geräteherstellern zugewiesen und sind weltweit eindeutig. LAAs können von den Benutzern manuell festgelegt werden und sind nicht unbedingt eindeutig.

5. Verwendung: MAC-Adressen spielen eine entscheidende Rolle bei der Steuerung des Datenverkehrs in einem lokalen Netzwerk. Sie werden verwendet, um sicherzustellen, dass Datenpakete an das richtige Zielgerät gesendet werden. Router und Switches verwenden MAC-Adressen, um Pakete im Netzwerk zu leiten.

6. Broadcast: Eine spezielle MAC-Adresse mit allen Bits auf "1" (FF:FF:FF:FF:FF:FF) wird als Broadcast-MAC-Adresse bezeichnet. Wenn ein Gerät Daten an diese Adresse sendet, werden sie an alle Geräte im Netzwerk gesendet.

7. Änderung der MAC-Adresse: In einigen Fällen kann es notwendig oder wünschenswert sein, die MAC-Adresse eines Netzwerkadapters zu ändern. Dies kann aus Sicherheitsgründen, zur Umgehung von Zugriffsbeschränkungen oder aus anderen Gründen erfolgen. Beachten Sie jedoch, dass nicht alle Netzwerkadapter die Möglichkeit zur Änderung der MAC-Adresse bieten.

8. MAC-Adressfilter: Netzwerke können MAC-Adressfilter verwenden, um den Zugriff auf das Netzwerk zu steuern. Nur Geräte mit spezifisch erlaubten MAC-Adressen können auf das Netzwerk zugreifen, während andere blockiert werden.

9. MAC-Adressen sind eine grundlegende Komponente in Netzwerken und ermöglichen die Identifizierung von Geräten in lokalen Netzwerken. Sie werden in vielen verschiedenen Netzwerkprotokollen und -technologien verwendet, einschließlich Ethernet und WLAN (Wi-Fi).

## Bitfolge

Die MAC-Adresse besteht aus einer Bitfolge, die aus 48 Bits (6 Oktetten à 8 Bits) besteht. Jedes dieser 48 Bits repräsentiert eine einzelne Binärziffer, entweder "0" oder "1". Hier ist eine Beispiel-MAC-Adresse in binärer Darstellung:

```
00:80:41:ae:fd:7e
00: 0000 0000
80: 1000 0000
41: 0100 0001
ae: 1010 1110
fd: 1111 1101
7e: 0111 1110
Die vollständige binäre Darstellung der MAC-Adresse "00:80:41:ae:fd:7e" lautet:
00000000100000000100000110101110111111010111110
```

Die Struktur einer MAC-Adresse in binärer Form ist wie folgt:

Die ersten 24 Bits (3 Oktette) repräsentieren normalerweise den OUI (Organizationally Unique Identifier), der dem Hersteller des Netzwerkadapters zugeordnet ist. Dieser Teil identifiziert den Hersteller oder die Organisation, die das Gerät hergestellt hat.

Die restlichen 24 Bits (3 Oktette) sind normalerweise ein von der Organisation festgelegter eindeutiger Wert, der das konkrete Gerät innerhalb der Herstellerorganisation identifiziert.

Da eine MAC-Adresse aus 48 Bits besteht, gibt es insgesamt 2^48 (ca. 281.474.976.710.656) mögliche Kombinationen. Das bedeutet, dass theoretisch mehr als 281 Billionen verschiedene MAC-Adressen existieren können.

Es ist wichtig zu beachten, dass aufgrund der Notwendigkeit der Eindeutigkeit der MAC-Adressen weltweit, die tatsächliche Anzahl der in der Praxis verwendeten MAC-Adressen weit weniger ist. Die Nummernraumverwaltung wird von der IEEE (Institute of Electrical and Electronics Engineers) überwacht, um sicherzustellen, dass keine Kollisionen zwischen MAC-Adressen auftreten.

Eine 48-Bit-Bitfolge bietet eine enorme Anzahl von Kombinationen, was sicherstellt, dass jede Netzwerkschnittstelle ihre eigene eindeutige Adresse hat. Diese Eindeutigkeit ist von entscheidender Bedeutung, um den reibungslosen Betrieb von Netzwerken zu gewährleisten, da es wichtig ist, dass Datenpakete an das richtige Gerät gesendet werden können, ohne Konflikte oder Adresskollisionen zu verursachen.

## MAC-Adressfilter

Ein MAC-Adressfilter ist eine Sicherheitsfunktion, die in einigen Netzwerken verwendet wird, um den Zugriff auf das Netzwerk zu steuern. Es ermöglicht nur Geräten mit bestimmten MAC-Adressen, auf das Netzwerk zuzugreifen, während andere Geräte blockiert werden. MAC-Adressfilter werden häufig in drahtlosen Netzwerken (WLANs) verwendet, um den Zugriff auf das Netzwerk zu beschränken.

## MAC-Adressen und IP-Adressen

MAC-Adressen und IP-Adressen sind tatsächlich zwei verschiedene Arten von Adressen, die in Computernetzwerken verwendet werden. Sie dienen unterschiedlichen Zwecken und befinden sich auf verschiedenen Ebenen des OSI-Modells.

1. MAC-Adressen:
   Verwendet auf der Datenlink-Ebene (Schicht 2) des OSI-Modells.
   Eindeutige Kennungen, die auf Netzwerkadaptern (Hardware) eingebettet sind.
   Identifizieren Geräte in einem lokalen Netzwerk (LAN).
   Weltweit eindeutig, aber von Herstellern zugewiesen.
   Wird für die direkte Kommunikation innerhalb desselben LANs verwendet, insbesondere für die Switching- und Frame-Relay-Technologien.

2. IP-Adressen:
   Verwendet auf der Netzwerkebene (Schicht 3) des OSI-Modells.
   Identifizieren Geräte in einem Netzwerk, sowohl in lokalen Netzwerken als auch im Internet.
   Bestehen aus logischen Nummern und sind von Netzwerken oder Administratoren zugewiesen.
   Ermöglichen die Routing-Funktion und die Kommunikation zwischen Geräten in verschiedenen Netzwerken.
   Werden verwendet, um Geräte in einem größeren, möglicherweise globalen Netzwerk zu adressieren und zu identifizieren.
   Zusammenfassend können wir sagen, dass MAC-Adressen dazu dienen, Geräte in einem lokalen Netzwerk zu identifizieren und hauptsächlich auf der Schicht 2 des OSI-Modells verwendet werden, während IP-Adressen dazu dienen, Geräte in einem größeren Netzwerk, einschließlich des Internets, zu adressieren und zu identifizieren und auf der Schicht 3 verwendet werden. Beide Adressarten erfüllen wichtige Funktionen im Netzwerkbetrieb, jedoch auf unterschiedlichen Ebenen und mit unterschiedlichen Anwendungsbereichen.

### Quellen

Wikipedia: [MAC-Adresse](https://de.wikipedia.org/wiki/MAC-Adresse)  
Heise: [MAC-Adressen](https://www.heise.de/tipps-tricks/Was-ist-eine-MAC-Adresse-4949263.html)  
Wikipedia: [MAC-Adressfilter](https://de.wikipedia.org/wiki/MAC-Adressfilter)  
Wikipedia: [IP-Adresse](https://de.wikipedia.org/wiki/IP-Adresse)  
Verivox: [MAC-Adresse](https://www.verivox.de/internet/mac-adresse/)
