# reddit_bot
scrape keyword frequency data and comments from reddit

reddit_bot.py scrapes keyword frequency data and comments from reddit
it records the comment ids in comment_ids.txt
it records the comments in comments.txt
it records the keywords and their frequencies in keyword_dict.txt

there is an additional necessary file called features.py which is necessary to run this program
this gives information about the reddit account which must be used to surf the website
i did not upload features.py because it contains sensitive information about the reddit account i used
a user must create their own features.py file and add their own account's features to use the program
below is the template for what features.py needs to look like:

client_id = --put client_id here--
client_secret = --put client secret here--
username = --put account username here--
password = --put account password here--
user_agent = --put user_agent here--

the parameters in reddit_bot.py can be modified to pick a subreddit to scrape as well as which keywords to search for and how many commetns to gather
