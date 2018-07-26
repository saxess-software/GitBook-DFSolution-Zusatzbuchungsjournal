### Anlegen eines Buchungsjournals

#### Im XLS-Client

Wählen Sie die Option **Neues Produkt**

![](/Pictures/Datenerfassung/XLS_Neues Product_1.png)Wählen Sie das **Template** für das Zusatzbuchungsjournal aus und geben Sie das **Ziel-Produkt** an.

![](/Pictures/Datenerfassung/XLS_Neues Product_2.png)

Wählen Sie über die **DropDown-Funktion** das Jahr, den Monat und den Freigabestatus für das Buchungsjournal aus. Der Freigabestatus beschreibt, ob ein Buchungsjournal sich noch in Prüfung befindet, keine Freigabe erhalten hat oder freigegeben ist.

![](/Pictures/Datenerfassung/XLS_Neues Product_3.png)

#### Im Web-Client

Wählen Sie die Option **Neues Produkt**

![](/Pictures/Datenerfassung/Web_Neues Product_1.png)

Wählen Sie das **Template** für das Zusatzbuchungsjournal aus und geben Sie das **Ziel-Produkt** an.

![](/Pictures/Datenerfassung/Web_Neues Product_2.png)

Wählen Sie über die **DropDown-Funktion** das Jahr, den Monat und den Freigabestatus für das Buchungsjournal aus. Der Freigabestatus beschreibt, ob ein Buchungsjournal sich noch in Prüfung befindet, keine Freigabe erhalten hat oder freigegeben ist.

![](/Pictures/Datenerfassung/Web_Neues Product_3.png)

### Erfassung eines Buchungssatzes und Plausibilitätsprüfung

#### Im Excel-Client

Erfassen Sie die Werte in den Feldern **Buchungsnummer**, **Buchungstext **und **Soll. **Das **Kontrollfeld **zeigt Ihnen zunächst eine Warnung an, da die Gegenbuchung noch nicht erfasst wurde und damit der Saldo nicht null beträgt.

![](/Pictures/Datenerfassung/XLS_Buchung erfassen_1.png)

Nutzen Sie für die Erfassung der Daten in den Feldern **KostenstellenID **und **SachkontenID** die Flex-Option **FlexSuche**.

![](/Pictures/Datenerfassung/XLS_Buchung erfassen_2.png)

Gehen Sie bei der Erfassung der Gegenbuchung auf die gleich Weise vor und pflegen Sie das Feld **Haben**. Das **Kontrollfeld **zeigt Ihnen an, ob die zur Buchungsnummer erfassten Datensätze einen Saldo von null ausweisen.

![](/Pictures/Datenerfassung/XLS_Buchung erfassen_3.png)

### Verwaltung der Stati eines Buchungssatzes

Über das Feld **Status **auf Product-Ebene können Sie an einem Buchungsjournal hinterlegen, ob dieses Aktiv oder Passiv ist. Über das Feld **Freigabe **kann der Bearbeiter eines Buchungsjournals vermerken, ob sich dieses gerade in Bearbeitung befindet, freigegeben ist oder keine Freigabe erhalten hat. Über dieses Feld können Sie bspw. den Bearbeitungs-Workflow steuern.





