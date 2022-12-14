# README

Instalação de bibliotecas necessárias para automatizar o movimento e o clique do mouse:
```bash
sudo apt-get install python3-tk python3-dev
sudo pip3 install pyautogui pillow mouseinfo
```

Para definir as coordenados dos cliques é preciso utilizar o mouseInfo()
```bash
python
from mouseinfo import mouseInfo
mouseInfo()
```

Rodar

```bash
-- 1 opcao
python3 main.py
-- 2 opcao
python main.py
```

**Referência:** 

* https://pyautogui.readthedocs.io/en/latest/keyboard.html

* https://www.youtube.com/watch?v=pNBjC32nisg&ab_channel=DevAprender
