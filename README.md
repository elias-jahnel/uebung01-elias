# Übung 01 – Elias Jahnel

Dieses Repository enthält die Lösung für **Übung 01** im Rahmen der Veranstaltung an der Universität zu Köln.  
Das Projekt wurde in der empfohlenen Java-Verzeichnisstruktur umgesetzt und ist lauffähig über die Kommandozeile.

---

## 🧩 Projektstruktur
uebung01-elias/
├── src/
│ └── main/
│ └── java/
│ └── de/
│ └── uni/
│ └── elias/
│ └── Main.java
├── .gitignore
└── README.md


---

## ▶️ Ausführen
Kompilieren und starten über das Terminal:
bash
# Kompilieren
javac -d out $(find src/main/java -name "*.java")

# Ausführen
java -cp out de.uni.elias.Main

Ausgabe:
Übung 01 – läuft.

Hinweise

Entwickelt und getestet unter Kali Linux mit OpenJDK 17
Repository ist öffentlich abrufbar unter:
https://github.com/elias-jahnel/uebung01-elias
