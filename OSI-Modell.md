# OSI-Modell

_Eine Zusammenfassung von René Barthel._

Das OSI-Modell (Open Systems Interconnection) ist ein theoretisches Rahmenwerk, das zur Beschreibung und Standardisierung von Kommunikationssystemen und Computernetzwerken verwendet wird. Es wurde von der Internationalen Fernmeldeunion (ITU-T) entwickelt und besteht aus sieben Schichten, die die verschiedenen Aspekte der Kommunikation in einem Netzwerk definieren. Das OSI-Modell hilft dabei, Netzwerkarchitekturen zu verstehen, zu entwerfen, zu dokumentieren und zu vergleichen. Hier ist eine Übersicht der sieben Schichten des OSI-Modells von unten nach oben:

## 1. Physische Schicht (Layer 1)

- Die physische Schicht beschäftigt sich mit der physischen Verbindung zwischen Geräten, einschließlich der elektrischen, mechanischen und funktionellen Aspekte. Sie legt fest, wie Bits auf dem Medium übertragen werden, wie Kabel und Stecker funktionieren und wie Signale interpretiert werden.

## 2. Sicherungsschicht (Layer 2)

- Die Sicherungsschicht ist für die Fehlererkennung und Fehlerkorrektur auf der Bit-Ebene sowie für die Verwaltung des Zugriffs auf das Medium verantwortlich. Sie unterteilt die Daten in Frames und beinhaltet die MAC-Adressierung zur Identifizierung von Geräten im selben Netzwerk.

## 3. Netzwerkschicht (Layer 3)

- Die Netzwerkschicht ist für das Routing von Datenpaketen innerhalb eines Netzwerks verantwortlich. Sie verwendet IP-Adressen, um Geräte in verschiedenen Netzwerken zu identifizieren, und bestimmt den besten Weg für Datenpakete zwischen ihnen.

## 4. Transportschicht (Layer 4)

- Die Transportschicht bietet Kommunikationsdienste, die End-to-End-Verbindungen zwischen Geräten herstellen. Sie ist für die Fehlererkennung, Fehlerkorrektur und Flusskontrolle verantwortlich. Bekannte Protokolle auf dieser Ebene sind TCP (Transmission Control Protocol) und UDP (User Datagram Protocol).

## 5. Sitzungsschicht (Layer 5)

- Die Sitzungsschicht legt fest, wie Kommunikationssitzungen zwischen Geräten aufgebaut, verwaltet und beendet werden. Sie ermöglicht auch die Wiederherstellung von Verbindungen bei Verbindungsproblemen.

## 6. Darstellungsschicht (Layer 6)

- Die Darstellungsschicht kümmert sich um die Syntax und Semantik der Daten, die zwischen verschiedenen Geräten ausgetauscht werden. Sie kann Daten komprimieren, verschlüsseln oder konvertieren, um sicherzustellen, dass sie von Empfängern korrekt interpretiert werden.

## 7. Anwendungsschicht (Layer 7)

- Die Anwendungsschicht ist die oberste Schicht des OSI-Modells und stellt die Schnittstelle zwischen Anwendungen und dem Netzwerk dar. Hier laufen Anwendungen, die direkt mit Benutzern interagieren, wie Webbrowser, E-Mail-Clients und Dateiübertragungsprogramme.

Das OSI-Modell bietet ein abstraktes Rahmenwerk, um die verschiedenen Aspekte der Kommunikation in einem Netzwerk zu verstehen und zu organisieren. Es ermöglicht es Entwicklern und Netzwerkingenieuren, Netzwerke zu entwerfen und zu implementieren, indem sie die Funktionalität und Verantwortlichkeiten jeder Schicht verstehen und die richtigen Protokolle und Technologien auswählen können. Es dient auch als Grundlage für die Entwicklung von Netzwerkprotokollen, Standards und Technologien.
