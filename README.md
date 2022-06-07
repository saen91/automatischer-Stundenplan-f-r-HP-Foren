# automatischer-Plan
Automatischer Stundenplan für HP Foren. 
Diese zieht er sich über IF aus Profilfeldern. 
Man benötigt: 
PHP in Templates
Profilfeld für Jahrgang
Profilfeld für Kursbelegung


In der Member_profil folgendes einfügen:

ganzoben:
<?php
eval("\$stundenplan = \"".$templates->get("profile_stundenplan")."\";");
?>

variable:
{$stundenplan}

Die hier aufgeführten tpls sind in die globalen Templates einzufügen:
profile_stundenplan

stundenplan _eins
stundenplan_zwei
stundenplan _drei
stundenplan_vier
stundenplan_fuenf
stundenplan_sechs
stundenplan_sieben
