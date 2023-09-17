### trello_keisan
- From a Trello page with a list starting with お金
- We want to calculate the costs each initials have raked up
- Manual steps
  - Input format for each card = {``initials``} {``cost with mathetical symbol if any``} {``description``}
  - Run the command to get ``String was copied to clipboard.``
  - All Card in List "お金*" will be copied
- Using the data, we calculate the cost for each ``initials``

### selenium_rakutenticket
- From a rakuten ticket performance page, we want to check if a seat becomes open
  
### selenium_tukuoki
- From the user favourites page in [つくおき](https://cookien.com/favorite/)
- Extract all recipes found inside
  - Title
  - Storage period
  - Ingredients
  - Instructions
- Install Chrome
  - Add repo
    ``sudo sh -c 'echo "deb http://dl.google.com/linux/chrome/deb/ stable main" >> /etc/apt/sources.list.d/google.list'``
    ``sudo wget -q -O - https://dl-ssl.google.com/linux/linux_signing_key.pub | sudo apt-key add -``

  - Update packge list
    ``sudo apt update``
  
  - Install
    ``sudo apt install google-chrome-stable``

  - Check verison
    ``google-chrome --version``

- Install Chrome driver
  - Based on chrome version above, find pip version here: https://pypi.org/project/chromedriver-binary/#history