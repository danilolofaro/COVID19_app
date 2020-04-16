Covid-19 Italian Data Dashboard
================

Quest’applicazione è stata sviluppata dell’Ing. Danilo Lofaro del
[de-Health Lab](http://www.dehealthlab.it/) - [DIMEG
(UNICAL)](https://www.unical.it/portale/strutture/dipartimenti_240/dimeg/)
nell’ambito dell’iniziativa [UNICAL vs
Covid](https://www.unicalvscovid.it/).

<br>

I dati analizzati in questa applicazione provengono da fonti ufficiali e
aggiornati quotidianamente.  
In particolare:

  - i dati relativi all’epidemia da **Covid-19** sono messi a
    disposizione dalla protezione civile e accessibili alla repository
    GitHub [COVID-19](https://github.com/pcm-dpc/COVID-19).

  - I dati relativi alla popolazione residente (anno 2019), sia a
    livello nazionale che regionale, sono messi a disposizione
    dall’ISTAT e accessibili all’indirizzo
    [http://dati.istat.it/QueryId=46313](http://dati.istat.it//Index.aspx?QueryId=46313).

  - I dati relativi alle cause di morte (anno 2017) sono messi a
    disposizione dall’ISTAT e accessibili all’indirizzo
    [http://dati.istat.it/QueryId=46315](http://dati.istat.it//Index.aspx?QueryId=46315).

<br>

L’applicazione è stata costruita con il framework
[Shiny](http://shiny.rstudio.com) per [R](https://www.r-project.org/).
Il layout è stato prodotto con il pacchetto
[flexdashboard](http://rstudio.github.io/flexdashboard/index.html) e i
grafici con i pacchetti [Plotly](http://plot.ly),
[ggplot2](http://ggplot2.org/) e
[geo-facet](https://hafen.github.io/geofacet/).

<br>

Eventuali feedback o suggerimenti possono essere inviati all’indirizzo
<danilo.lofaro@unical.it>
