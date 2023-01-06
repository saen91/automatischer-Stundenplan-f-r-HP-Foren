# automatischer-Plan
Automatischer Stundenplan für HP Foren. 
Diese zieht er sich über IF aus Profilfeldern. 
Man benötigt: 
PHP in Templates
Profilfeld für Jahrgang
Profilfeld für Kursbelegung


In der Member_profil folgendes einfügen:

ganz oben:<br>
<?php
eval("\$stundenplan = \"".$templates->get("profile_stundenplan")."\";");
?><br>

variable:<br>
{$stundenplan}

Die hier aufgeführten tpls sind in die globalen Templates einzufügen:<br>
profile_stundenplan<br>
stundenplan_eins<br>
stundenplan_zwei<br>
stundenplan_drei<br>
stundenplan_vier<br>
stundenplan_fuenf<br>
stundenplan_sechs<br>
stundenplan_sieben<br>
