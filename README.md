# server-file-python3
Servidor de arquivos em Python3. Caso SSH não funcione.

bash
cd ~/IoMT
python3 -m http.server 8000

(O terminal vai ficar travado dizendo que está escutando na porta 8000. Deixe ele assim).

Primeiro descubra o IP do servidor que acabou de criar (vamos supor que o IP seja 192.168.16.10), rode:

wget http://IP_DO_SEU_COMPUTADOR:8000/arquivo-que-vai-baixar
De um Ctrl + C para fechar o servidor temporário.
