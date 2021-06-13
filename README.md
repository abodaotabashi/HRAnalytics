# HR Analytics - Einsatz vom Maschinellen Lernen zur Vorhersage der potenziellen Kandidaten


## Beschreibung

<p align="justify">Mit diesem Datensatz versucht ein Unternehmen, das im Bereich Big Data und Data Science tätig ist, neue Arbeitskräfte einzustellen. Für diesen Grund bietet das Unternehmen Kurse an, nach denen die Nachfrage groß ist. Deswegen zielt es mithilfe dieses Datensatzes darauf ab, die Kandidaten, die nach dem Abschluss des Kurses wirklich für das Unternehmen arbeiten möchten, vorherzuwissen, um Zeit- und Kostenaufwand zu sparen, sowie die Qualität des Kurses zu erhöhen.<p/>

<p align="justify">Dieser Datensatz besteht aus 13 Merkmalen und insgesamt 21287 (19158 Training + 2129 Test) gekennzeichnete Datenpunkte. Die Merkmale demonstrieren die Ausbildung und die praktischen Erfahrungen der Kandidaten. Jedoch ist dieser Datensatz unbalanziert und enthält fehlende Datenwerte (NaN-Werte), was den Training-Prozess beeinflussen kann.<p/>

**Quelle des Datensatzes:** <a href="https://www.kaggle.com/arashnic/hr-analytics-job-change-of-data-scientists" target="_blank">**Kaggle**</a>


## Projekt-Infos

**Projekt-Typ:** Machine Learning

**Technologien:** Python, Jupyter Notebook

## Team-Mitglieder
| **Team-Mitglied** |
| --- |
| Baraa ALSALEH |
| Abdurrahman ODABAŞI |
| Muhammed ŞİHEBİ |

## Ergebnis des Projekts

<p align="justify">Da unser Datensatz stark unbalanziert ist, scheint es, dass das Verwenden der Genauigkeitsmetrik als Evaluationsmetrik nicht geeignet für diesen Datensatz ist. Deshalb wurden alle Modelle mithilfe von ROC-AUC-Score evaluiert.<p/>
 
<p align="justify">Als Ergebnis erhält man, dass sich Soft-Voting-Klassifizerer die künftigen noch nicht gekennzeichneten Daten am besten vorhersagt. Mit diesem Modell wird eine Genauigkeit von 91.01% und ein ROC-AUC-Score von 93,4% über den Training-Datensatz erreicht. Auf der anderen Seite wird über den Test-Datensatz eine Genauigkeit von 73% und ein ROC-AUC-Score von 71.49% erreicht. Jedoch wurden diese hohen Noten nur dann erreicht, nachdem der Cut-Off-Wert manipuliert wurde.<p/>
