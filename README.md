# AbgabeJannis_MaschinelleEigenschaftsanalyse

Im Kurs: "Sprechstile - maschinelle Eigenschaftsanalyse", im SoSe 2021 geleitet von Prof. Dr. Felix Burkhardt, haben wir in diesem Semester unsere eigene Stimme analysiert.
Zu Beginn des Kurses haben die Studierenden drei Minuten frei gesprochen. Dies wurde dann im Rahmen des Kurses aufgenommen. Der Grundgedanke war, dass wir die Aufregung des jeweiligen Teilnehmenden analysieren. Da jedoch kaum Aufregung zu hören war in den unterschiedlichen Stimmen, mutmaßlich da in einem Studiengang namens "Sprache und Kommunikation" die meisten Studierenden gut vor Publikum sprechen können, gerade in einem Online-Semester via Video-Konferenz, entschieden wir uns um und analysierten stattdessen die Stimme mit der Valenz als Hauptparameter.
Für mich habe ich die Valenz als ein postives Element der Stimme definiert. Desto höher die Valenz, desto postiver empfand ich in bestimmten Passagen den Klang bzw. Ausdruck meiner Stimme.

Mittels eines Skripts von audEERING wurden unsere Aufnahmen von Herrn Prof. Dr. Burkhardt in ähnlich große Anteile segmentiert. Zwar blieb mir die genaue Funktionsweise des Skripts verborgen, da es sich hierbei um Betriebsinterna von audEERING handelt, jedoch wurden die einzelnen Segmente mittels des Skripts scheinbar bei charakteristischen (Atem-)pausen getrennt. Somit entstanden ähnlich große Segmente.

Unsere Aufgabe daraufhin war, dass wir diese Segmente mit Hilfe des von Herrn Prof. Dr. Burkhardt programmierten "Speechalyzer" zu annotieren. Speechalyzer ist dabei das Serverprogramm und Labeltool ist das Benutzerprogramm,  welches als grafische Benutzeroberfläche genutzt wird um die vorher generierten Segmente zu labeln und zu segmentieren.

Mit Hilfe dieses Programms bzw. dieser Programme haben die Studierenden die Segmente ihrer eigenen Aufnahme nach der jeweiligen Valenz annotiert und gelabelt. Wie bereits oben erwähnt, habe ich das für mich als die jeweilige Positivität definiert und dementsprechend meine Labels gesetzt.

Daraufhin entstand eine CSV-Datei, also eine Datei, in welcher die Werte durch Kommas separiert werden. Mit der sogenannten labels.txt Datei habe ich dann mittels Jupyter Notebook weitergearbeitet.
Dies kann man hier finden [implemented here](Sprechstile_maschinelle_Eigenschaftsanalyse_Nellesen.ipynb).

Hier wird alles genauestens analysiert und grafisch dargestellt. Schlussendlich wurden diese Inhalte sogar statistisch ausgewertet. Als eigene Leistung wurden die einzelnen Arbeitsschritte genauestens mittels Markdown kommentiert, damit man mein Verständnis der Arbeitsschritte nachvollziehen kann.
Auch wurden am Ende kleine grafische Repräsentationen als Eigenleistung hinzugefügt, welche zeigen sollen, dass der Inhalt und die Befehle prinzipiell verstanden wurden.

Da es im markierten Notebook auf Grund meiner Markdown-Kommentare und der jeweiligen Befehle ersichtbar ist, inwiefern diese Analyse und grafische Aufarbeitung von statten läuft, werde ich im Rahmen dieses Readmes nicht weiter darauf eingehen, da diese Informationen ansonsten redundant wären.

Mit Hilfe der PraatScripts von Prof. Dr. David R. Feinberg, Lehrender an der McMaster University in Kanada, konnten wir unserer Analyse unterschiedliche Parameter hinzufügen. Diese wurden als pickle-Datei mit in der Abgabe hochgeladen und somit auch in mein Haupt-Notebook importiert. Da ich keine eigene Leistung in den Praat-Skripts-Notebooks erbracht habe, habe ich diese selbstverständlich auch nicht der Abgabe hinzugefügt.

Nachdem wir uns fast das ganze Semester mit der Einführung in Jupyter Notebook, Python und Pandas, sowie mit der Analyse unserer eigenen Stimme bzw. Rede beschäftigt hatten, wollten wir uns nun auch mit den Reden bzw. den analysierten Werten der anderen Studierenden auseinander setzen.
Dementsprechend haben alle Student*innen ihre Dataframes als Pickle-Datei abgespeichert und diese in die Cloud geladen. Die Studierenden wurden dazu angeleitet, alle Dataframes auf einmal herunterzuladen. Dabei gab es einige Anlaufschwierigkeiten. Manche Studierenden haben ihre Dataframes erst nachträglich hinzugefügt. Auch hatten einige Fehler bei der Analyse ihrer eigenen Stimme begangen, sodass bei einigen Studierenden bestimmte Analyseparameter fehlten. Bestimmte Parameter wie bspw. "JitterPCA" oder "ShimmerPCA" funktionierten bei relativ vielen nicht. Beispielsweise auch bei Herrn Prof. Dr. Burkhardt. Die Befehle, welche diese Werte ermitteln sollten, wurden dann extra in den früher erwähnten PraatSkripts von Feinberg auskommentiert, sodass das Notebook ohne Fehler durchlaufen konnte. Dementsprechend fehlten diese Parameter bei einigen Studierenden.

Den weiteren Verlauf der Analyse der Stimmen bzw. Reden von allen Teilnehmenden kann man sich im folgenden Notebook anschauen [implemented here](all_dataframes.ipynb)
Als Eigenleistung wurden hier ebenfalls die Zeilen mittels Markdown kommentiert und schlussendlich eigene grafische Repräsentationen hinzugefügt. Somit kann angezeigt werden, dass der vermittelte Inhalt verstanden wurde und nicht einfach nur kopiert und abgegeben wurde.

Resümierend kann man sagen, dass in diesem Seminar unglaublich viele neue Inhalte gelernt wurden. Sei es die Arbeit mit Jupyter Notebook, Grundzüge von Python und Pandas und sogar die Arbeit mit Repositorys wit GitHub. Die Ergebnisse der Analyse empfand ich persönlich nicht als überraschend, dennoch war es ideal um diese Grundlagen zu lernen.
