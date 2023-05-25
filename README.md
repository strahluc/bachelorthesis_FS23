Im GitHub Repository "bachelorthesis_FS23" befinden sich alle Codes zu den erstellen Plots<br>
und den durchgeführten Berechnungen für die Bachelorarbeit von Luca Strahm an der ZHAW (Abgabe: 31.05.2023)<br>

Die Forschungsfrage der Arbeit lautet: Wie hoch ist die geschätzte Wahrscheinlichkeit, in der Zukunft einen Sonnensturm<br>
von der Intensität des Carrington-Ereignisses zu beobachten?<br>

Hier ist kurz aufgeführt, welche Dateien das Repository enthält<br>


sunspot_data<br>
  - "data_sunspots.csv": Datenset de Sonnenfleckendaten von SILO<br>
  - "Datenanalyse_Sonnenflecken.ipynb": ausführbare Python-Datei mit Datenaufbereitung und analyse der Sonnenfleckendaten<br>
  - "Datenanalyse_Sonnenflecken.html": Den Code der Python-Datei als nicht ausführbare HTML-Datei<br>

solar_flare_data<br>
  - "Datenaufbereitung_Sonneneruptionen.ipynb": ausführbare Python-Datei für die Aufbereitung aller CSV-Dateien im Ordner "data_files"<br>
  - "Datenaufbereitung_Sonneneruptionen.html": Python-Code als nicht ausführbare HTML-Datei<br>
  - "Datenanalyse_Sonneneruptionen.html": ausführbare Python-Datei für die Datenanalyse der Daten über die Sonneneruptionen (basiert auf "df_extreme.csv")<br>
  - "Datenanalyse_Sonneneruptionen.html": Python-Code als nicht ausführbare HTML-Datei<br>
  - "Python_EVT_calc.ipynb": ausführbare Python-Datei für die EVT-Berechnung der Wahrscheinlichkeit mit der POT-Methode. Verwendetes Package: pyextremes<br>
  - "Python_EVT_calc.html": Python-Code als nicht ausführbare HTML-Datei<br>
  - "R_EVT_calc.Rmd": ausführbare R-Datei mit Datenanalyse und Berechnungen in R (basiert auf "R_df_solarflare.csv")<br>
  - data_files: Überordner für alle Daten-Files. Enthält folgende Dateien:<br>
    - data_solar_flare_raw: weiterer Unterordner mit einzelnen CSV-Dateien mit Daten über Sonneneruptionen pro Jahr<br>
    - "solar_flare_new.csv": Enthält Daten von Sonneneruptionen 1975-2016 unaufbereitet<br>
    - "solar_flare_prepared.csv": Enthält aufbereitete Daten von Sonneneruptionen 1975-2016<br>
    - "df_extreme.csv": Enthält aufbereitete Daten von Sonneneruptionen 1975-2016 mit pro Tag exakt einem Wert<br>
    - "R_df_solarflare.csv": Enthält aufbereitete Daten von Sonneneruptionen 1975-2016 mit pro Tag exakt einem Wert für die Berechnungen in R<br>
    - "survival_sf.csv": Enthält die Daten für die Überlebensfunktion<br>
    - "R_df_solarflare_zipf_1.csv": Enthält Daten für den einfach aggregierten Zipf-Plot basierend auf den Daten der Überlebensfunktion<br>
    - "R_df_solarflare_zipf_2.csv": Enthält Daten für den zweifach aggregierten Zipf-Plot basierend auf den Daten der Überlebensfunktion<br>
    - "R_df_solarflare_zipf_3.csv": Enthält Daten für den dreifach aggregierten Zipf-Plot basierend auf den Daten der Überlebensfunktion<br>
