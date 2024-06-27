# Linked Data Vokabulare und Ontologien

Die Deutsche Nationalbibliothek stellt mit dem [Linked-Data-Service](https://www.dnb.de/lds) im Standard Resource Description Framework (RDF) alle nationalbibliografischen Metadaten und alle Normdaten der [Gemeinsamen Normdatei](https://gnd.network/) (GND) kostenfrei zur Verfügung.

Für die Beschreibung der Daten werden sowohl Vokabulare nachgenutzt, als auch eigene erstellt und gepflegt. Es wird unterschieden zwischen strukturellen RDF-Vokabularen, die Klassen und Relationen zwischen Entitäten definieren (RDF-Element-Sets) und Vokabularen, die Entitäten definieren, wie zum Beispiel Klassifikationen oder Listen von Ländercodes (RDF-Value Vocabularies).

## RDF-Element-Sets

### GND-Ontologie
Die GND-Ontologie (GNDO) definiert Klassen und Relationen, mit denen wir die Daten der Gemeinsamen Normdatei (GND) im Format RDF beschreiben. Für die GND-Ontologie existiert ein eigenes Repository.

### DNB Metadata Terms
Die DNB Metadata Terms (DNBT) definiert Klassen und Relationen, die wir für die Beschreibung der Titeldaten verwenden, falls wir keine passenden Klassen oder Relationen in anderen Vokabularen vorgefunden haben.

### Agent Relationship Ontology
Die Agent Relationship Ontology (AgRelOn) definiert Beziehungen von Personen zu anderen Personen und zu Organisationen. AgRelOn entstand im Rahmen der Projekte ALEXANDRIA und CONTENTUS und wurde entwickelt, um einheitliche Erschließung sowie semantische Recherchierbarkeit von und via Relationen zwischen Agenten (Personen, Organisationen) zu fördern.

## RDF-Value-Vocabularies
Die Value-Vocabularies verstehen sich als Ergänzung zur GND-Ontologie und umfassen Codelisten und Klassifikationen, die bei der Beschreibung von GND-Entitäten verwendet werden.

### GND-Geschlecht
Das Vokabular „GND-Geschlecht“ (GND Gender) bildet die drei möglichen Geschlechtsangaben in der GND (männlich, weiblich, unbekannt) in RDF ab.

### GND-Ländercodes
Das Vokabular „GND-Ländercodes“ (GND Geographic Area Codes) bildet die in der GND verwendeten Ländercodes ab. Sie werden in RDF als skos:Concepts modelliert.

### GND-Systematik
Das Vokabular „GND-Sachgruppen“ (GND Subject Categories) bildet die GND-Sachgruppen ab, die einen systematischen Zugang zu Individualnamen und Sachschlagwörtern der GND ermöglichen. Sie werden in RDF als skos:Concepts modelliert.

### GND-Koordinatentyp
Das Vokabular „GND-Koordinatentyp“ (GND Type of Coordinates) bildet die möglichen Werte für Koordinatentypen in den Daten der GND ab. Sie werden in RDF als skos:Concepts modelliert. Dieses Vokabular wird aktuell nicht weitergepflegt, da wir für die RDF-Modellierung der GND-Daten nicht die GND-Ontologie verwenden, sondern GeoSPARQL.

### GND-Katalogisierungslevel
Das Vokabular „GND-Katalogisierungslevel“ (GND Description Level) bildet die möglichen Werte für das Katalogisierungslevel ab, das den Stand der redaktionellen Bearbeitung eines Datensatzes anzeigt. Sie werden in RDF als skos:Concepts modelliert.

# Kommunikation
Über Issues und Pull Requests können gerne Fehler oder Verbesserungsvorschläge eingebracht werden. Weitere Fragen oder Anregungen können über die [Linked-Data-Service Mailingliste](http://lists.dnb.de/mailman/listinfo/lds) mitgeteilt werden. Oder per Mail an [metadatendienste@dnb.de](mailto:metadatendienste@dnb.de).

# Lizenz

Die Vokabulare sind lizensiert unter [CC0](LICENSE).