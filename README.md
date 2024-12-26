# Deutsche Nachrichtenklassifizierung und NLP-Analyse

## Projektbeschreibung

Dieses Projekt implementiert verschiedene NLP-Techniken zur Klassifizierung deutscher Nachrichtentexte unter Verwendung des GNAD10-Datensatzes. Es kombiniert traditionelle Machine Learning-Ansätze mit modernen Deep Learning-Methoden.

## Implementierte Funktionen

### 1. Datenvorverarbeitung

- Textbereinigung und Normalisierung
- Entfernung von Satzzeichen
- Konvertierung in Kleinbuchstaben
- Integration von NLTK und spaCy für deutsche Texte

### 2. Textanalyse und Visualisierung

- Erstellung von Word Clouds zur Visualisierung häufiger Begriffe
- Named Entity Recognition (NER) mit spaCy
- Visualisierung von Entitäten mit displacy

### 3. Word Embeddings

- Implementation von Word2Vec-Modellen
- Erstellung von Dokumentenvektoren
- Analyse von Wortähnlichkeiten

### 4. Klassifizierungsmodelle

- Support Vector Machine (SVM) mit Hyperparameter-Tuning
- BERT-basierte Klassifizierung (deepset/gbert-base)
- Evaluierung der Modellleistung

## Verwendete Technologien

- Python
- PyTorch
- Transformers (Hugging Face)
- NLTK
- spaCy
- scikit-learn

## Modellleistung

- Implementierung verschiedener Evaluierungsmetriken
- Vergleich der Klassifizierungsgenauigkeit
- Analyse von Fehlklassifizierungen

## Projektergebnisse

- Erfolgreiche Implementierung der Nachrichtenklassifizierung
- Vergleich verschiedener Modellansätze
- Visualisierung der Ergebnisse

## Installation und Verwendung
- Erforderliche Pakete installieren

  - pip install transformers torch nltk spacy pandas numpy matplotlib seaborn
- Deutsches Sprachmodell für spaCy installieren

    - python -m spacy download de_core_news_sm
 
## Zukünftige Verbesserungen

- Integration weiterer Sprachmodelle
- Optimierung der Hyperparameter
- Erweiterung der Textvorverarbeitung
- Implementierung von Cross-Validation
-------------------------------------------
Dieses Projekt wurde im Rahmen einer NLP-Analyse deutscher Nachrichtentexte entwickelt und demonstriert verschiedene Techniken der modernen Textverarbeitung und -klassifizierung.
