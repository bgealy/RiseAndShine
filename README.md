# upon running program a webpage appears with multiple tabs

# containing links to things like sports, news, social media, email, etc.

import webbrowser <br />
import time <br />
socialMediaUrls = ['https://www.facebook.com/', 'https://www.reddit.com/'] <br />
sportsNewsUrls = ['http://www.espn.com/', 'https://football.fantasysports.yahoo.com/'] <br />
techNewsUrls = ['https://techcrunch.com/', 'https://www.theverge.com/tech'] <br />
workStuffUrls = ['https://mail.google.com/mail/u/0/', 'https://mail.yahoo.com/'] <br />
<br />
def open_tabs(url_list): <br />
    for element in url_list: <br />
        webbrowser.open_new_tab(element) <br />
def main (): <br />
    webbrowser.open('https://www.google.com/') v
    time.sleep(1) <br />
    open_tabs(socialMediaUrls) <br />
    open_tabs(sportsNewsUrls) <br />
    open_tabs(techNewsUrls) <br />
    open_tabs(workStuffUrls) <br />
<br />
main() <br />
