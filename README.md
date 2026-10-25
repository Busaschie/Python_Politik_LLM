# Python_Politik_LLM

Aufbau eines eigenen LLM für eine politische Diskussionsrunde, die per KI simuliert wird.

## Überblick

Das Projekt entstand als Abschlussprojekt im Python/KI-Kurs. Verschiedene KI-Teilnehmer diskutieren politische Themen miteinander; die Oberfläche läuft über Streamlit.

## Tech-Stack

- Python
- PyTorch
- Streamlit

## Projektstruktur

```text
├── app.py     # Streamlit-App (Einstiegspunkt)
├── src/       # Modell- und Anwendungslogik
├── data/      # Trainings-/Diskussionsdaten
└── .idea/     # IDE-Konfiguration
```

## Installation

```bash
git clone https://github.com/Busaschie/Python_Politik_LLM.git
cd Python_Politik_LLM
python -m venv .venv
# Windows: .venv\Scripts\activate | Linux/macOS: source .venv/bin/activate
pip install streamlit torch
```

## Nutzung

```bash
streamlit run app.py
```

Die App öffnet sich unter `http://localhost:8501`.

## Hinweis

Die Ausgaben sind KI-generiert, stellen keine politischen Positionen des Autors dar und können fehlerhaft oder verzerrt sein.
