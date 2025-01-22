# gerador-de-email
Um código utilizando a linguagem python com a biblioteca pyautogui com o propósito de gerar um e-mail aleatório para uso. O código abre um gerador de e-mail, copia o e-mail, cria uma conta no outlook válida e para no recaptcha pela incapacidade de solução pelo código



import pyautogui as pa
import time
import pyperclip


pa.press('win')
time.sleep(2)
pa.write("opera")
time.sleep(2)
pa.press('ENTER')
time.sleep(10)
#abrir opera

time.sleep(4)
pa.write('https://theonegenerator.com/pt/geradores/texto/gerador-de-email')
pa.press('enter')
#abrir gerador de email

time.sleep(4)
pa.click(x=1167, y=348)
#gerar email

time.sleep(4)
pa.click(x=924, y=304)
pa.click(x=924, y=304)
pa.hotkey('ctrl', 'c')
#copiar nome do email

pa.hotkey('ctrl', 't')
time.sleep(7)
pa.write('https://encurtador.com.br/fte9X')
pa.press('enter')
#abrir nova guia e entrar no outlook

time.sleep(3)
pa.press('tab')
time.sleep(3)
pa.press('enter')
time.sleep(2)
pa.hotkey('ctrl', 'v')
time.sleep(3)
pa.write('@hotmail.com')
time.sleep(3)
pa.write('daomsdo')
time.sleep(3)
pa.press('enter')
time.sleep(5)
pa.write('vasvsvasasf31231@')
time.sleep(3)
pa.press('enter')
time.sleep(4)
pa.write('saf')
time.sleep(3)
pa.press('tab')
time.sleep(3)
pa.write('vasvs')
time.sleep(3)
pa.press('enter')
time.sleep(3)
pa.press('tab')
time.sleep(3)
pa.press('2')
time.sleep(3)
pa.press('tab')
pa.press('m')
time.sleep(3)
pa.press('tab')
pa.write('2000')
time.sleep(3)
pa.press('tab')
pa.press('tab')
pa.press('enter')
#criar email novo
