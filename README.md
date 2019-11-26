
#FERRAMENTA CRIADA POR: Carlos Oliveira.
#Todos os direitos reservados.
#Conhecimento não é crime.
from time import sleep
import os,sys
print ("ATUALIZANDO OS REPOSITORIOS, AGUARDE...")
sleep (2)
os.system ("clear")
os.system ("apt upgrade && apt update -y")
os.system ("clear")
print ("""\033[32m Criador: VIRUS
\033[m\033[31m Team: FR13NDS\033[m""")
print ("""
█▀▀ ▄▀▀ ▄▀▀ . ▀█▀ ▄▀▀▄ ▄▀▀▄ █░░ ▄▀▀ .
█▀▀ ░▀▄ █░░ . ░█░ █░░█ █░░█ █░░ ░▀▄ .
▀░░ ▀▀░ ░▀▀ . ░▀░ ░▀▀░ ░▀▀░ ▀▀▀ ▀▀░ .""")
print ()
print ("\033[32m Não me responsabilizo por seus atos\033[m")
print()
sleep (1)
print ("(1) continuar")
print ("(2) sair")
print ()
continuar = (input ("Deseja continuar? "))
print ()
if continuar == "2":
	print ("Obrigado por usar a ferramenta, BYE!")
	while False:
		break
if continuar == "1":
	print ("\033[31mLISTA DE FERRAMENTAS DISPONIVEIS:\033[m ")
	print ("\033[23m(1) Sqlmap")
	print ("(2) Weeman")
	print ("(3) Shellphish")
	print ("(4) Xerxes")
	print ("(5) Hulk")
	print ("(6) Metasploit")
	print ("(7) HiddenEye")
	print ("Websploit")
	print ("(9) Nmap")
	print ("(10) Hydra")
print ()
sleep (1)
tool = (input ("Qual deseja? "))
if tool == "1":
	os.system ("git clone https://github.com/sqlmapproject/sqlmap")
if tool == "2":
	os.system ("git clone https://github.com/evait-security/weeman")
if tool == "3":
	os.system ("git clone https://github.com/thelinuxchoice/shellphish")
if tool == "4":
	os.system ("git clone https://github.com/XCHADXFAQ77X/XERXES")
if tool == "5":
	os.system ("git clone https://github.com/Hyperclaw79/HULK-v2")
if tool == "6":
	os.system ("pkg install unstable-repo && pkg install metasploit -y")
if tool == "7":
	os.system ("git clone https://github.com/DarkSecDevelopers/HiddenEye")
if tool == "8":
	os.system ("git clone https://github.com/websploit/websploit")
if tool == "9":
	os.system ("pkg install nmap -y")
if tool == "10":
	os.system ("git clone https://github.com/vanhauser-thc/thc-hydra")
else:
	print ("Por favor, selecione uma das alternativas.")
	sleep (1)
	print ("Encerrando.")
