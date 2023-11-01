# Sentiment_Analysis_Projekt
Projektüberblick

Das Projekt kann in mehrere Abschnitte unterteilt werden:

1. Datenzusammenführung:
Zu Beginn hatten wir eine Sammlung von separaten Tweets. Diese Daten wurden eingelesen und in einem Dataframe zusammengeführt.

2. Datenbereinigung:
In diesem Schritt haben wir den Datensatz von Duplikaten und ähnlichen Tweets befreit. Nach dieser Reinigung verfügten wir über 40.000 analysierbare Tweets.
Darüber hinaus wurden unerwünschte Symbole und andere irrelevanten Informationen aus den Tweets entfernt.

3. Sentiment-Analyse:
Das Hauptziel dieses Abschnitts war die Zuordnung des Sentiments zu den einzelnen Tweets.
Zunächst wurde ein kleinerer Dataframe erstellt, um verschiedene Transformer-Modelle zu testen.
Insgesamt haben wir vier verschiedene Transformer ausprobiert.
Schlussendlich haben wir uns für den Roberta Transformer entschieden, da dieser die Stimmung der Tweets am genauesten wiedergab.
