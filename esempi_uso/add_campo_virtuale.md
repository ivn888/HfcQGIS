# add\_campo\_virtuale

## Come aggiungere un campo virtuale

Facciamo un esempio, geopackage con vettore lineare:

![](../.gitbook/assets/add_campo_virt3.png)

selezionare il layer \(presente nel _Layer Panel_\), tasto destro mouse 'Apri tabella attributi' oppure cliccare sull'icona ![icona\_tab\_attr](https://docs.qgis.org/2.18/it/_images/mActionOpenTable.png) oppure tasto funzione F6

![](../.gitbook/assets/add_campo_virt1%20%281%29.png)

1. attivare editing;
2. aprire calcolatore di campi ![calc](https://docs.qgis.org/testing/en/_images/mActionCalculateField.png)
3. crea nuovo campo, crea campo virtuale;
4. digittare nome campo **lunghezza\_dinamica**;
5. tipo campo uscita Real e lunghezza uscita 10 e 2;
6. nella casella ricerca digitiamo il nome della funzione: **$length**
7. doppio clic sulla funzione **$lenght** per aggiungerla;
8. **OK** per eseguire;

![](../.gitbook/assets/add_campo_virt2.png)

verrà aggiunta la colonna _lunghezza\_dimanica_ popolata con la funzione [$lenght](https://github.com/pigreco/HfcQGIS/tree/68652d038e50a3a61763c7cb4b0f4062018bd82d/gr_funzioni/geometria/funzioni/$lenght.md)

## Osservazioni

Un campo virtuale è un campo che si aggiorna dimanicamente e non modifica la tabella attributi in quanto viene memorizzata nel progetto e non nel layer.

{% embed data="{\"url\":\"https://www.youtube.com/watch?v=IymSgXmbAFM&list=PLqDFjeQq7NBjz5PWb66PNUqMgN1fce4cu&inde\",\"type\":\"video\",\"title\":\"QGIS: Calcolatore di campi \(Field calculator\) Part 3  campi virtuali\",\"description\":\"Calcolatore di campi: potenzialità, come usarlo, cosa può fare.\nFields Calculator : potential, how to use it, what it can do.\n\nTerzaparte:\nCreare nuovo campo\nCalcolo Lunghezza\nCreare campo virtuale\n\nhttp://qgis.it/\nhttp://www.qgis.org/it/site/\nhttp://docs.qgis.org/2.2/it/docs/user\_manual/working\_with\_vector/field\_calculator.html\nhttps://pigrecoinfinito.wordpress.com/\",\"icon\":{\"type\":\"icon\",\"url\":\"https://www.youtube.com/yts/img/favicon\_144-vfliLAfaB.png\",\"width\":144,\"height\":144,\"aspectRatio\":1},\"thumbnail\":{\"type\":\"thumbnail\",\"url\":\"https://i.ytimg.com/vi/IymSgXmbAFM/mqdefault.jpg\",\"width\":320,\"height\":180,\"aspectRatio\":0.5625},\"embed\":{\"type\":\"player\",\"url\":\"https://www.youtube.com/embed/IymSgXmbAFM?rel=0&showinfo=0\",\"html\":\"<div style=\\"left: 0; width: 100%; height: 0; position: relative; padding-bottom: 56.2493%;\\"><iframe src=\\"https://www.youtube.com/embed/IymSgXmbAFM?rel=0&amp;showinfo=0\\" style=\\"border: 0; top: 0; left: 0; width: 100%; height: 100%; position: absolute;\\" allowfullscreen scrolling=\\"no\\"></iframe></div>\",\"aspectRatio\":1.7778}}" %}



il geopackage è scaricabile [qui](https://github.com/pigreco/HfcQGIS/tree/68652d038e50a3a61763c7cb4b0f4062018bd82d/esempi_uso/dati_esempi.gpkg)
