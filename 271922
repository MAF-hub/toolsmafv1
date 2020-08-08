# -*- coding: utf-8 -*-
import sys, os, webbrowser, platform
from time import sleep
from sys import stdout, exit
RED, WHITE, CYAN, GREEN, END = '\033[91m', '\33[46m', '\033[36m', '\033[1;32m', '\033[0m'
##Def funciones
def limpiar():
	if os.name == 'nt':
		os.system('cls')
	else:
		os.system('clear')
def logo():
      print '''        
       {0}    ``      {2}T O O L S{0}      ``            
          -h-`                        -           
          dMMy     `::`     ```      :N-          
         `MMMm`.:+shMNy+-./ohNd+:.` /NM/          
         .MMMmdNMMMMMMMh/-yMMMMMMNdsyMM+          
         `NMM+yMMMMMMMm/+o:dMMMMMMMNoNM+          
          yMm`-dNMNNmNNMMMMdhmNMMMm/`dM+          
          +MN-``:++/oNMMMMMMh/+oo/-``hM/          
          `dMm/::hmNMMNMMMMMMNmho-../hm`          
         ` /MMMMNmMMMmdmmmmmNMMNNNmmMM: `         
    `-+ydmo.dMMMMMMmhy/---:ohdNMMMMMMm:hmhs/-     
./shmNMMMMMd+dMMMMMms-.-.-..:hmMMMMMddNMMMMMNdy+: 
:hNMMMMMMMMMNNMMNMMNo-.-----/dNMNNMMNMMMMMMMMMMNs 
 -sMMMMMmyys+dMMNmMNNhyo+oydNmhNmNNMsoyyyNMMMMN+` 
  :dNs::o.`:dNMMNNmNmhhyyhyyydmNNMMMNy.`:o:/hMo-  
   +do-.ym+NMMMMd.`:mNmmddmNNs.`/MMMMMhsN/`/hh.   
    -ddmMMNNMMMMM/ :hMMMMMMMNs. hMMMMMdMMNdds     
     ..yMMMMMMMMd+ -mMMMdNMMMs``yNMMMMMMMM-.      
       .mMMMdy/.   {2}MERETEC AND FLYEAD{1}{0}   `-ohNMMMs`       
       `+y+.           ```           `-sy:                             
       {3}SOLO MUESTRA LOS TOOLS MAS INTERESANTES 
  Este script esta hecho con fines eduacativos{2} '''.format(GREEN, END, CYAN, RED)
limpiar()
logo()
sleep(0.7)
limpiar()
sleep(0.3)
logo()
sleep(0.3)
limpiar()
sleep(0.3)
logo()
sleep(0.3)
limpiar()
sleep(0.3)
logo()
sleep(1.5)
for i in range(101):
        sleep(0.01)
        stdout.write("\r{0}[{3}*{0}]{2} Preparando el Script... %d%%".format(GREEN, END, CYAN, RED, WHITE) % i)
        stdout.flush()
limpiar()

def menuc():
    print '''
{3}*{1}{0} Este Script esta hecho con la Colaboracion de MERETEC AND FLYEAD
                Esperamos que les sea util{1} {3}MAF{0}'''.format(GREEN, END, CYAN, RED, WHITE)


print("falta poco para ingresar a la zona oscura")
print("")

EDAD_DEL_GIL=int(input("esta no es  una zona para niños pon tu edad: "))

print("")
print("")

if EDAD_DEL_GIL>=18 and EDAD_DEL_GIL<100:
  def menu():
    print '''
      {3}1.{1} {2} PENTESTING(necesitas SQLMAP)
      {3}2.{1} {2} GENERAR PAYLOAD(metasploit) 						
      {3}3.{1} {2} INSTALAR HERRAMIENTAS						
      {3}4.{1} {2} BUSCADORES DE LA DEEP WEB											
      {3}5.{1} {2} RECOPILAR INFORMACION(LINUX)												
      {3}6.{1} {2} INFORMACION HACKING											
      {3}7.{1} {2} EN MANTENIMIENTO								
      {3}8.{1} {2} Youtube MAF					
      {3}9.{1}{2} Salir						
				'''.format(GREEN, END, CYAN, RED)
  limpiar()
  menuc()
  menu()
  d = raw_input('\033[1;32m TOOLS MAF > \033[0m')
  if d == "4":
    print """
     NOT EVIL:
              http://hss3uro2hsxfogfq.onion/
     AHMIA:
              http://msydqstlz2kzerdg.onion/
     TORCH:
              http://xmh57jrzrnw6insl.onion/
     HAYSTAK:
              http://haystakvxad7wbk5.onion/
     DUCKDUCKGO:
              https://3g2upl4pq6kufc4m.onion/
     SEARX: 
              http://5plvrsgydwy2sgce.onion/
     """
  elif d == "3":
	    os.system("clear")
	    os.system("figlet herramientas")
	    print("""
         1)nmap(termux)
         2)SQLiv(LINUX)
         3)metasploit(termux)
         4)sqlmap(termux)
                                                """)
	    e = raw_input('\033[1;32m opciones > \033[0m')
	    if e == "2":
	    	os.system("sudo apt update")
	    	os.system("sudo apt upgrade")
	    	os.system("sudo git clone https://github.com/the-robot/sqliv")
	    elif e == "4":
	    	os.system("apt install unstable-repo")
	    	os.system("apt install sqliv")
	    elif e == "1":
	    	os.system("sudo apt-get install nmap")
	    	os.system("clear")
	    	os.system("toilet -f future FINISH")
	    elif e == "3":
	    	os.system("apt install unstable-repo")
	    	os.system("apt install metasploit")
  elif d == "8" :
        os.system("clear")
        os.system("figlet GRACIAS BRO")
        print("")
        print("""
         gracias por haber elegido esta d bro, solo
         te queremos agradecer por usar nuestro script y 
         quisieramos pedirte que porfavor que te suscribas 
         a nuestro canal 

         -> https://www.youtube.com/channel/UCplxfPaS6e5-ELl7zqjdPHg

         psdt: se que no es tu edad real pillin >:c
         """)
  elif d == "1" :
  	os.system("setterm -foreground red")
  	os.system("clear")
  	os.system("figlet PENTESTING")
  	print("")
  	os.system("setterm -foreground white")
  	pagina=raw_input("ingrese la pagina > ")
  	os.system("sqlmap -u "+str(pagina)+" --dbs -random-agent")
  	DBS=raw_input("se cumplio el analisis?[Y]|[N] > ")
  	DBS_lower=DBS.lower()
  	if DBS_lower == "y":
  		print("")
  		database=raw_input("ingrese la base de datos > ")
  		os.system("sqlmap -u " + str(pagina)+" -D " + str(database) + " --tables")
  		BASE=raw_input("se cumplio el analisis? [Y]|[N] > ")
  		BASE_L=BASE.lower()
  		if BASE_L == "y":
  			option=raw_input("escriba la tabla que desea > ")
  			os.system("sqlmap -u " +str(pagina)+" -D " + str(database)+" -T " +str(option)+" --dump")
  			print("")
  			print("GRACIAS")
  		elif BASE_L == "n":
  			os.system("clear")
  			print("pagina no vulnerable")
  			sleep(0.3)
  			os.system("clear")
  	elif DBS_lower =="n":
  		os.system("clear")
  		print("le recomendamos usar paginas sacadas con sqliv")
  		print("")
  elif d == "5":
  	os.system("clear")
  	os.system("setterm -foreground green")
  	os.system("figlet RPI")
  	print("")
  	RPI=raw_input("ingrese la pagina que desea analizar > ")
  	print("")
  	os.system("setterm -foreground yellow")
  	os.system("dmitry -winsepfb -o " + str(RPI))
  	print("")
  	print("gracias")
  elif d == "6":
  	os.system("clear")
  	os.system("toilet -f future INFORMACION HACKING")
  	print("")
  	nombre=raw_input("ingrese su nombre > ")
  	sleep(0.6)
  	print("")
  	print("bienvenido amo " +str(nombre)+" , qué desea aprender hoy? , por cierto me llamo cort.")
  	print("")
  	
  	print ("""
  		+------------------|------------------+
  		|1)ip  2)dns       |                  |
  		|3)puerta tracera  |                  |
  		|(conexion windows)|en mantenimiento  |
  		|                  |                  |
  		|                  |                  |
  		+------------------|------------------+""")
  	print("")
  	asd=int(input("opcion > "))
  	if asd ==1:
  		    print("")
  		    print("""
  			una direccion ip es un numero
  			que identifica de forma unica
  			a un dispositivo dentro de una
  			red""")
  		    print("")
  	elif asd == 2 :
  		     print("")
  		     print("""
  			DNS es una tecnologia basada
  			en base de datos que sirve
  			para resolver nombres de una
  			una direccion IP dentro de 
  			una red""")
  		     print("")
  	elif asd == 3 :
  		      print(""" esta es informacion valiosa debido:
  			  a que con esto puedes obtener las direcciones
  			  IP dentro de una red y esto puede servir para 
  			  hacer MIM(man in the middle)
  			  basicamente una puerta tracera dentro de una red
  			  wifi es la que nos conecta a nuestro servidor
  			  y su direccion se puede obtener ṕoniendo:
  			  --> ipconfig/all
  			  en el CMD """)
  	while asd > 3:
  		print("hola")
else:
	os.system("clear")
	os.system("setterm -foreground red")
	os.system("figlet F")
	os.system("setterm -foreground white")
	print("no puedes pasar")
