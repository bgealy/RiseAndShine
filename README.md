# upon running program a webpage appears with multiple tabs

# containing links to things like sports, news, social media, email, etc.

import webbrowser
import time
socialMediaUrls = ['https://www.facebook.com/', 'https://www.reddit.com/']
sportsNewsUrls = ['http://www.espn.com/', 'https://football.fantasysports.yahoo.com/']
techNewsUrls = ['https://techcrunch.com/', 'https://www.theverge.com/tech']
workStuffUrls = ['https://mail.google.com/mail/u/0/', 'https://mail.yahoo.com/']

def open_tabs(url_list):
    for element in url_list:
        webbrowser.open_new_tab(element)
def main ():
    webbrowser.open('https://www.google.com/')
    time.sleep(1)
    open_tabs(socialMediaUrls)
    open_tabs(sportsNewsUrls)
    open_tabs(techNewsUrls)
    open_tabs(workStuffUrls)

main()
