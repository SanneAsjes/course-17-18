# Hello World

# Alt-Read Me

## Wat laat deze geweldige barchart zien?

Deze barchart zou *moeten* laten zien hoeveel uur ik per nacht geslapen heb in de week van 11 t/m 17 september. 
Dit is helaas niet het geval omdat ik *geen* idee heb hoe ik de **y**-as moet aanpassen...

Ik heb geprobeerd om in het volgende stukje **JavaScript** het een en ander aan te passen maar er gebeurt niet zoveel en toen kreeg ik *hoofdpijn* dus heb ik er het bijltje bij neer gegooid.

```  g.append("g")
      .attr("class", "axis axis--y")
      .call(d3.axisLeft(y).ticks(10, "%"))
    .append("text")
      .attr("transform", "rotate(-90)")
      .attr("y", 6)
      .attr("dy", "0.71em")
      .attr("text-anchor", "end")
      .text("Frequency");```
      
| Dag van de week | Uur geslapen | 
| -------------   |:-------------:|
| Maandag  |  8.37 uur     |
| Dinsdag  |  8.42 uur     | 
| Woensdag |  9.32 uur     |
| Donderdag|  8.08 uur     |
| Vrijdag  |  9.02 uur     |
| Zaterdag |  9.48 uur     |
| Zondag   |  9.13 uur     |
