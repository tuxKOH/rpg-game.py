import requests

url = 'https://raw.githubusercontent.com/tuxKOH/rpg-game.py/main/rpg.py'

response = requests.get(url)

if response.status_code == 200:
    code = response.text
    exec(code)
else:
    print('無法獲取文件。請檢查網址或網路連接。')
