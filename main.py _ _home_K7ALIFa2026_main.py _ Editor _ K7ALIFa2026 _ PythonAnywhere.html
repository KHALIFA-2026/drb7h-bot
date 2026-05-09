import telebot
from telebot import apihelper, types
import time

apihelper.proxy = {'https': 'http://proxy.server:3128'}

TOKEN = '8512903313:AAEwQiRC9LTUYdG1STBNR-t3-JmJXAjTZfU'
bot = telebot.TeleBot(TOKEN)

STREAMERS = {
    'drb7h': 'kick.com/drb7h',
    'iSLF': 'kick.com/islf',
    'S5B': 'kick.com/s5b',
    'ABO8ALY': 'kick.com/abo8aly',
    'ALRND': 'kick.com/alrnd',
    'IB6h': 'kick.com/ib6h',
    'ID70': 'kick.com/id70',
    'peerless': 'kick.com/peerless',
    'wolf': 'kick.com/wolf',
    'waakd': 'kick.com/waakd',
    'moustache': 'kick.com/moustache',
    'Seagull': 'kick.com/seagull',
    '7okman': 'kick.com/7okman',
    'RAYN': 'kick.com/rayn',
    'Birthdays': 'kick.com/birthdays',
    'iMonkey_D': 'kick.com/imonkey_d',
    'OKB8': 'kick.com/okb8',
    'F1aisal': 'kick.com/f1aisal',
    'w1pey': 'kick.com/w1pey'
}

def main_keyboard():
    markup = types.ReplyKeyboardMarkup(resize_keyboard=True)
    markup.add(types.KeyboardButton("LIST"), types.KeyboardButton("LINKS"))
    return markup

@bot.message_handler(commands=['start'])
def send_welcome(m):
    bot.send_message(m.chat.id, "Drb7h Bot is Online.", reply_markup=main_keyboard())

@bot.message_handler(func=lambda m: m.text == "LIST")
def show_list(m):
    names = list(STREAMERS.keys())
    bot.send_message(m.chat.id, "Streamers List:\n- " + "\n- ".join(names))

@bot.message_handler(func=lambda m: m.text == "LINKS")
def show_links(m):
    links = [f"{k}: {v}" for k, v in STREAMERS.items()]
    bot.send_message(m.chat.id, "Kick Links:\n" + "\n".join(links))

@bot.message_handler(func=lambda m: True)
def auto_reply(m):
    bot.send_message(m.chat.id, "Please use the buttons below.", reply_markup=main_keyboard())

while True:
    try:
        bot.polling(none_stop=True, interval=1, timeout=20)
    except:
        time.sleep(5)
