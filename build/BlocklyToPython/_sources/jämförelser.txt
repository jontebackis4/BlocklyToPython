===============
Jämförelser
===============


Jämförelser i blockly
:::::::::::::::::::::

När du programmerar är det väldigt användbart att göra jämförelser på olika saker. Om du programmerar en bankautomat så vill du t.ex. bara att automaten ska ge ut pengar **om** användaren knappar in rätt pinkod. I detta avsnitt får du lära dig hur du gör sånt här!

Exempel: Får Pella köra moppe?
------------------------------

*I den här videon förklarar vi vad en så kallad if-sats är och hur du skriver en i Blockly.*

.. youtube:: Tdqa0uMoiis
    :height: 315
    :width: 560
    :align: left





Uppgift: Får Pella köra bil?
****************************

Testa nu att göra en egen if-sats i Blockly-rutan här nedanför. Din uppgift är att testa om Pella får köra bil eller inte. Låt först Pella vara 16 år och sen vara 23 år, genom att ändra värdet på variabeln Ålder.

* Börja med att testa om Pella är över 18 år, och säg att hon får köra bil om hon är det och att hon inte får det, annars.

.. blockly:: jämförelser

   * controls
   controls_if
   controls_repeat_ext
   controls_for
   ====
   * logic
   logic_compare
   ====
   * math
   math_number
   math_arithmetic
   ====
   * text
   text
   text_print
   ====
   variables

   preload::
   <xml>  
      <block type="variables_set" id="1" inline="true" x="25" y="9">    
         <field name="VAR">X</field>    
         <value name="VALUE">      
            <block type="math_number" id="2">
               <field name="NUM">10</field>
            </block>    
         </value>  
      </block>
   </xml>


* Egentligen så räcker det ju inte med att vara över 18 för att få köra bil, utan Pella behöver ju ha körkort också. Lägg till en variabel som håller koll på om Pella har körkort eller inte och döp den till “ja” eller “nej” och skriv bara ut att hon får köra bil om hon både är över 18 år **och** har körkort. Se “Tips” om du vill ha hjälp hur man gör detta!

Bra jobbat! Nu är vi redo att se hur vi skriver if-satser i Python.

If-satser i Python
::::::::::::::::::

*I den här videon förklarar vi hur du skriver en if-sats i Python.*

Uppgift: Nytt exempel liknande bil-exemplet
-------------------------------------------

[Beskrivning av uppgift]

* Info om att detta kallas för en if-sats.