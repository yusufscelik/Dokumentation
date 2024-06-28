28-06-2024 11:14

### Dokumentation für Energie Dashboard

Bei dieser Dokumentation geht es um das Energie-Dashboard. 

**Regeln**;
* Die technischen Bezeichnungen sind auf Englisch eingesetzt, um es später leichter zu programmieren. Die technischen Variablen sind auf Englisch und kursiv geschrieben. 
	* Bespiel; *state_of_gas*

* Damit es leichter wird, den Unterschied zwischen den verschiedenen States zu erkennen, wird die Struktur bei der Benennung immer gleich gehalten:
	* Beispiel: _state_of_SOMETHING_


## Hauptzustände (states)

Es gibt insgesamt 3 Hauptzustände bzw 3 Energie Werte.
Damit bildet man 3 Haupt Tabs auf der Startseite.

![Selection_013](https://github.com/yusufscelik/Dokumentation/assets/95184239/abbfcaf5-3078-44e8-8c5b-3fccd9251540)

1. Strom *(state_of_electricity)* <br>
2. Erdgas *(state_of_gas)* <br>
3. Wasser *(state_of_water)* <br>
   
Diese drei Hauptzustände werden im Default State als **Tabs** angezeigt. Dadurch kann man leicht zwischen ihnen navigieren.


Bei allen drei Tabs gibt es noch drei Untertabs.

![struktur](https://github.com/yusufscelik/Dokumentation/assets/95184239/9b7b5227-f819-464a-9c80-7c62c4586661)

1. **Zählerliste** *(list)*
2. **Vergleich** *(compare)*
3. **Zeitanalyse** (_details)

Alle drei Hauptzustände haben ihre eigene Zählerliste, Vergleich und Zeitanalyse. 

Die Untertabs haben ihre eigene Bennungsstruktur und lautet so;

Für **Zählerliste**;

* _state_list_of_electricity_
* _state_list_of_gas
* state_list_of_water

Für **Vergleich**;


* *state_compare_electricty*
* *state_compare_gas*
* *state_compare_water*

Für **Zeitanalyse**;
* *state_details_electricity*
* *state_details_gas*
* *state_details_water*

Ansonsten gibt es bei der Zählerliste die Möglichkeit, eine Liegenschaft (_select_properties_) zu wählen und diese in der Karte (_state_map_) zu sehen. 

![map](https://github.com/yusufscelik/Dokumentation/assets/95184239/1c4f3ed0-497e-4249-9682-691b26a28bd0)


* Diese zwei States sind zusammen durch eine HTML-Karte aufgebaut.
* Es ermöglicht, bei allen Zählerlisten die Liegenschaften in der Karte zu sehen.

Zurzeit kann man die Liegenschaft nur mit einem Switch-Button auswählen, aber später wird es auch so funktionieren, dass man gleichzeitig verschiedene Liegenschaften mit einem Check-Button anzeigen kann.
