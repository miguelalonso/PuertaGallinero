# Automatic-Chicken-Coop-Door-
NodeMCU Automatic Chicken Coop Door

Control automático con NodeMCU para puerta de Gallinero

con motor elevalunas de coche (de desguace)
un nodemcu 
relé de actuación
El elevalunas se alimenta con una fuente DC de 2A

es importante: Hubo un problam con los finales de carrera, se programaron como una entrada digital D1 y D7, con una resistencia pull-down.
cuando se intentaba abrir o cerrar se producía una señal falsa de cierre de los finales de carrera y el sistema paraba.
Se solucionó con un condensador entre +3V3 y la entrada digital (un condensador de 1 micro en cada uno D1 y D7)
