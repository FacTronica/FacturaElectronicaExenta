# FacturaElectronicaExenta
Factura Electrónica Exenta Tipo 34

Para generar una Factura Electrónica Exenta, el proceso y esquema del txt y xml es similar.
Solamente se deben tomar las siguientes consideraciones.

TIPO DE DOCUMENTO FV=34 FACTURA ELECTRONICA EXENTA                                                                       
$IdDoc["TipoDTE"]="34";

EL INDICADOR DE LINEAS EN VALORES BRUTOS 1=SI 0=NO                                                              
$IdDoc["MntBruto"]="0";

EN CADA ITEM DEL DETALLE SE DEBE MARCAR COMO EXENTO
$detalle["1"]["IndExe"]="1";


