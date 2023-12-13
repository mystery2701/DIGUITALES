# DIGITALES
proyecto digitales ; HUEVOS
/// este proyecto abarca la solucion de un problema planteado que indica que; /////

##################################################################################

Se desea diseñar un sistema de clasificación automática de huevos, según su
tamaño. El sistema deberá distinguir entre huevos pequeños, medianos y grandes.
Para ello se dispone de 3 sensores de presencia, cuya salida será “1” si hay un ob-
jeto delante de ellos, colocados en una cinta transportadora por la que se mueven
los huevos. Diremos que un huevo es grande cuando los tres sensores se activen
simultáneamente; el huevo será considerado mediano cuando sólo interfiera en
los sensores 2o y 3o, y pequeño cuando al llegar al tercero los otros dos estén libres.
En el cronograma adjunto se observan estas tres posibilidades.

![image](https://github.com/mystery2701/DIGUITALES/assets/153778632/29e6f15f-1f72-4108-ac96-ed74828fc006)

####################################################################################

%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%
El sistema a diseñar tendrá que activar un robot articulado que hará que el
huevo vaya a un recipiente distinto, según su tamaño. Para ello, tendré que poner
las señales de salida T1 y T2 según la tabla adjunta, todo el tiempo en el que S3
esté activo.
![image](https://github.com/mystery2701/DIGUITALES/assets/153778632/da2ea7da-ea77-424d-902c-8421037006a3)


%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%
Además, se irán contando cuántos huevos hay de
cada tipo, ya que éstos se van colocando en cartones
estándar (dos docenas y media = 30 huevos). Cuando se
llene un cartón, se activará la señal correspondiente,
CG, CM ó CP. Tras cambiar el cartón ade-
cuado, el robot mandará una señal,

“OK”, para informar que ya se ha
realizado el cambio. En la figura se
observa un esquema general del
montaje deseado.
%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%
![image](https://github.com/mystery2701/DIGUITALES/assets/153778632/94f0adad-056c-4c99-ac60-37d1bb883fba)
°°°°°°°°°°°°°°°°°°°°°°°°°°°°°°°°°°°°°°°°°°°°°°°°°°°°°°°°°°°°°°°°°°°°°°°°°°°°°°°°°°°°°°°°°°°°°°°°°°°°°°°°
Para el diseño de los bloques 1 y 2 se tendrán en cuenta las siguientes consi-
deraciones:

• La frecuencia del reloj se supondrá mucho mayor que la velocidad de movi-
miento de la cinta transportadora, por lo que las señales S1, S2, S3, T1, T2, CG,

CM y CP durarán muchos ciclos de reloj.
• No se tendrá en cuenta la posibilidad de que un huevo retroceda, desaparezca

o aparezca directamente al final de la cinta. Tampoco se considerará la posibi-
lidad de huevos “con agujeros”.

• Los bloques 1 y 2 son SÍNCRONOS, y usan la misma señal de reloj.
°°°°°°°°°°°°°°°°°°°°°°°°°°°°°°°°°°°°°°°°°°°°°°°°°°°°°°°°°°°°°°°°°°°°°°°°°°°°°°°°°°°°°°°°°°°°°°°°°°°°°°°°°°°°°°°°°°°°°°°°°°°°°°°°°°°°°°°°°°°°°°°°°°°°°°°°°°°°°
Feliz★* 。 • ˚ ˚ ˛ ˚ ˛ ......................................................................................................................................
•。★Navidad★ 。* 。..........................................................................................................................................
° 。 ° ˛˚˛ * _Π_____*。*˚....................................................................................................................................
˚ ˛ •˛•˚ */______/~＼。˚ ˚˛..................................................................................................................................
˚ ˛ •˛• ˚ ｜ 田田 ｜門｜ ˚....................................................................................................................................
.............................................................................................................................................................
Un feliz año nuevo...........................................................................................................................................


