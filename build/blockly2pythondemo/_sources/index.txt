.. role:: red

==================
Jämförelser
==================

När du programmerar är det väldigt användbart att göra jämförelser på olika saker. Om du programmerar en bankautomat så vill du t.ex. bara att automaten ska ge ut pengar om användaren knappar in rätt pinkod. I detta avsnitt får du lära dig hur du gör sånt här!

Jämförelser i Blockly
::::::::::::::::::::::

Exempel: Får Pella köra moppe?
******************************
*I den här videon förklarar vi vad en så kallad if-sats är och hur du skriver en i Blockly.*

.. youtube:: Tdqa0uMoiis
    :height: 315
    :width: 560
    :align: left

Uppgift: Får Pella köra bil?
****************************

Nu ska du testa på att göra en egen jämförelse i Blockly. Din uppgift blir att skriva ut om Pella får köra bil eller inte.

* Vi säger att alla som är över 18 år får köra bil. Du ska nu göra ett litet program som har en variabel med Pellas ålder och som antingen skriver ut att hon får köra bil, eller inte, beroende på hennes ålder. Testa först med åldern 16 år och sedan 23 år.

.. blockly:: jamforelser

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
          <field name="VAR">age</field>
          <value name="VALUE">
             <block type="math_number" id="2">
                <field name="NUM">16</field>
             </block>
          </value>
       </block>
    </xml>


* Egentligen så räcker det ju inte med att vara över 18 för att få köra bil, utan Pella behöver ju ha körkort också. Lägg till en variabel som håller koll på om Pella har körkort eller inte och döp den till “ja” eller “nej” och skriv bara ut att hon får köra bil om hon både är över 18 år **och** har körkort. Tryck på Tips-knappen nedan om du vill ha tips hur du kan göra detta.

.. reveal:: reveal1
    :showtitle: Visa tips
    :hidetitle: Göm tips

    *Det går att ha if-satser inuti if-satser.*

Bra jobbat! Nu är vi redo att se hur vi gör jämförelser i Python.

Jämförelser i Python
::::::::::::::::::::

*I den här videon förklarar vi hur du skriver en if-sats i Python-kod.*

.. youtube:: D9gG74yMUec
    :height: 315
    :width: 560
    :align: left
