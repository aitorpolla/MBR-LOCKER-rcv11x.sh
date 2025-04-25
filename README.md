!!!!ATENCION!!!!!

Este ransomware Cifra la MBR a grado militar, tiene el mismo peligro que muchos ransomware tipo Petya...
Si usted ejecuta el archivo en una maquina real, accede a la WinRE lo mas rapido posible con:
shutdown /r /o /f /t 0

Si nada de eso funciona, instala un CD-ROM con una iso de windows 7 ultimate y cuando loe des a reparar pc:
En el cmd pon
bootrec /fixmbr (Porque cifra la mbr)
bootrec /fixboot (Porque se carga tambien el bootloader)
bootrec /rebuildbcd (Porque se carga el arranque BCD del sistema)

Si ninguno de esos comandos funciona, opta por restaurart su PC
