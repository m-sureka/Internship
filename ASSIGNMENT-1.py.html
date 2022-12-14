#!/usr/bin/env python
# coding: utf-8

# In[1]:


get_ipython().system('pip install bs4')
get_ipython().system('pip install requests')


# In[2]:


from bs4 import BeautifulSoup
import requests


# QUESTION-1

# In[3]:


page=requests.get('https://www.wikipedia.org/')
page


# In[4]:


soup=BeautifulSoup(page.content)
soup


# In[5]:


header=[]
for i in soup.find_all('h1',class_='central-textlogo-wrapper'):
    header.append(i.text.split('\n'))
header


# QUESTION-2

# In[6]:


page=requests.get('https://www.imdb.com/list/ls055592025/')
page


# In[7]:


soup=BeautifulSoup(page.content)
soup


# In[8]:


titles=[]
for i in soup.find_all('h3',class_='lister-item-header'):
    titles.append(i.text.split('\n')[2])
titles


# In[9]:


year=[]
for i in soup.find_all('span',class_='lister-item-year text-muted unbold'):
    year.append(i.text)
year


# In[10]:


ratings=[]
for i in soup.find_all('div',class_='ipl-rating-widget'):
    ratings.append(i.text.split('\n')[9])
ratings


# In[11]:


import pandas as pd
df=pd.DataFrame({'Titles':titles,'Ratings':ratings,'Year of release':year})
df


# QUESTION-3

# In[12]:


page=requests.get('https://www.imdb.com/list/ls561664100/')
page


# In[13]:


soup=BeautifulSoup(page.content)
soup


# In[14]:


titles=[]
for i in soup.find_all('h3',class_='lister-item-header'):
    titles.append(i.text.split('\n')[2])
year=[]
for i in soup.find_all('span',class_='lister-item-year text-muted unbold'):
    year.append(i.text)
ratings=[]
for i in soup.find_all('div',class_='ipl-rating-widget'):
    ratings.append(i.text.split('\n')[9])
df=pd.DataFrame({'Titles':titles,'Ratings':ratings,'Year of release':year})
df


# QUESTION-4

# In[15]:


page=requests.get('https://presidentofindia.nic.in/former-presidents.htm')
page


# In[16]:


soup=BeautifulSoup(page.content)
soup


# In[17]:


names=[]
for i in soup.find_all('div',class_='presidentListing'):
    names.append(i.text.split('\n')[1])
year=[]
for i in soup.find_all('div',class_='presidentListing'):
    year.append(i.text.split('\n')[2])
df=pd.DataFrame({'Names':names,'Term of Office':year})
df


# QUESTION-5

# In[18]:


page=requests.get('https://www.icc-cricket.com/rankings/mens/team-rankings/odi')
page


# In[19]:


soup=BeautifulSoup(page.content)
soup


# In[20]:


team=[]
for i in soup.find_all('span',class_='u-hide-phablet'):
    team.append(i.text)
team


# In[21]:


match=[]
for i in soup.find_all('td',class_='rankings-block__banner--matches'):
    match.append(i.text)
match


# In[22]:


matches1=[]
for i in soup.find_all('td',class_='table-body__cell u-center-text'):
    matches1.append(i.text.split(','))
matches1


# In[23]:


matches=[]
points=[]
for i in range(0,len(matches1)-1,2):
    matches.append(matches1[i])
    points.append(matches1[i+1])
points


# In[24]:


matches


# In[25]:


list1=match
list2=matches
merged=list1+list2


# In[26]:


merged


# In[27]:


point=[]
for i in soup.find_all('td',class_='rankings-block__banner--points'):
    point.append(i.text)
point


# In[28]:


list1=point
list2=points
merged_p=list1+list2
merged_p


# In[29]:


df=pd.DataFrame({'Team Names':team,'Matches':merged,'Points':merged_p})
df


# In[30]:


df=df.iloc[0:10,:]
df


# 5B

# In[31]:


page=requests.get('https://www.icc-cricket.com/rankings/mens/player-rankings/odi')
page


# In[32]:


soup=BeautifulSoup(page.content)
soup


# In[33]:


name=[]
for i in soup.find_all('div',class_='rankings-block__banner--name'):
    name.append(i.text)
name


# In[34]:


team=[]
for i in soup.find_all('div',class_='rankings-block__banner--nationality'):
    team.append(i.text.split('\n')[2])
team


# In[35]:


rating=[]
for i in soup.find_all('div',class_='rankings-block__banner--rating'):
    rating.append(i.text)
rating


# In[36]:


df=pd.DataFrame({'Name':name,'Team':team,'Rating':rating})
df


# In[37]:


names=[]
for i in soup.find_all('td',class_='table-body__cell name'):
    names.append(i.text.split("\n")[1])
names


# In[38]:


teams=[]
for i in soup.find_all('span',class_='table-body__logo-text'):
    teams.append(i.text)
teams


# In[39]:


ratings=[]
for i in soup.find_all('td',class_='table-body__cell u-text-right rating'):
    ratings.append(i.text)
ratings


# In[40]:


list1=['Babar Azam']
list2=names
merge_n=list1+list2
merge_n


# In[41]:


list1=['PAK']
list2=teams
merge_t=list1+list2
merge_t


# In[42]:


list1=['890']
list2=ratings
merge_r=list1+list2
merge_r


# In[43]:


df=pd.DataFrame({'Names':merge_n,'Teams':merge_t,'Ratings':merge_r})
df


# In[44]:


df1=df.iloc[0:10,:]
df1


# 5C

# In[45]:


df2=df.iloc[10:19,:]
df2


# 6A

# In[46]:


page=requests.get('https://www.icc-cricket.com/rankings/womens/team-rankings/odi')
page


# In[47]:


soup=BeautifulSoup(page.content)
soup


# In[48]:


team=[]
for i in soup.find_all('span',class_='u-hide-phablet'):
    team.append(i.text)
team


# In[49]:


match=[]
for i in soup.find_all('td',class_='rankings-block__banner--matches'):
    match.append(i.text)
match


# In[50]:


point=[]
for i in soup.find_all('td',class_='rankings-block__banner--points'):
    point.append(i.text)
point


# In[51]:


matches=[]
for i in soup.find_all('td',class_='table-body__cell u-center-text'):
    matches.append(i.text)
matches


# In[52]:


matches1=[]
points1=[]
for i in range(0,len(matches)-1,2):
    matches1.append(matches[i])
    points1.append(matches[i+1])
points1


# In[53]:


matches1


# In[54]:


rating=[]
for i in soup.find_all('td',class_='rankings-block__banner--rating u-text-right'):
    rating.append(i.text.split('\n')[1])
rating


# In[55]:


ratings=[]
for i in soup.find_all('td',class_='table-body__cell u-text-right rating'):
    ratings.append(i.text)
ratings


# In[56]:


list1=match
list2=matches1
matches_m=list1+list2
matches_m


# In[57]:


list1=point
list2=points1
points_m=list1+list2
points_m


# In[58]:


list1=rating
list2=ratings
ratings_m=list1+list2
ratings_m


# In[59]:


df=pd.DataFrame({'Team Names':team,'Matches':matches_m,'Points':points_m,'Ratings':ratings_m})
df


# In[60]:


df.iloc[0:10,:]


# 6B

# In[61]:


page=requests.get('https://www.icc-cricket.com/rankings/womens/player-rankings/odi')
page


# In[62]:


soup=BeautifulSoup(page.content)
soup


# In[63]:


player=[]
for i in soup.find_all('div',class_='rankings-block__banner--name'):
    player.append(i.text)
player


# In[64]:


team=[]
for i in soup.find_all('div',class_='rankings-block__banner--nationality'):
    team.append(i.text.split('\n')[2])
team


# In[65]:


team=[]
for i in soup.find_all('div',class_='rankings-block__banner--nationality'):
    team.append(i.text.split('\n')[3])
team


# In[66]:


players=[]
for i in soup.find_all('td',class_='table-body__cell name'):
    players.append(i.text.split('\n')[1])
players


# In[67]:


teams=[]
for i in soup.find_all('td',class_='table-body__cell nationality-logo'):
    teams.append(i.text.split('\n')[2])
teams


# In[68]:


ratings=[]
for i in soup.find_all('td',class_='table-body__cell u-text-right rating'):
    ratings.append(i.text)
ratings


# In[69]:


list1=['Alyssa Healy']
list2=players
players_m=list1+list2
players_m


# In[70]:


list1=['AUS']
list2=teams
teams_m=list1+list2
teams_m


# In[71]:


list1=['785']
list2=ratings
ratings_m=list1+list2
ratings_m


# In[72]:


df=pd.DataFrame({'Player Name':players_m,'Team':teams_m,'Rating':ratings_m})
df


# In[73]:


df.iloc[0:10,:]


# 6C

# In[74]:


players=[]
for i in soup.find_all('td','table-body__cell name'):
    players.append(i.text.split('\n')[1])
players


# In[75]:


teams=[]
for i in soup.find_all('td',class_='table-body__cell nationality-logo'):
    teams.append(i.text.split('\n')[2])
teams


# In[76]:


ratings=[]
for i in soup.find_all('td',class_='table-body__cell u-text-right rating'):
    ratings.append(i.text)
ratings


# In[77]:


df=pd.DataFrame({'Player Name':players,'Team':teams,'Ratings':ratings})
df


# In[78]:


df.iloc[18:27,:]


# 7A

# In[79]:


page=requests.get('https://www.cnbc.com/world/?region=world')
page


# In[80]:


soup=BeautifulSoup(page.content)
soup


# In[81]:


headline=[]
for i in soup.find_all('div',class_='FeaturedCard-contentText'):
    headline.append(i.text)
headline


# In[82]:


headlines=[]
for i in soup.find_all('div',class_='SecondaryCard-headline'):
    headlines.append(i.text)
headlines


# In[83]:


head1=[]
for i in soup.find_all('div',class_='RiverHeadline-headline RiverHeadline-hasThumbnail'):
    head1.append(i.text)
head1


# In[84]:


list1=headline
list2=headlines
list3=head1
head_m=list1+list2+list3
head_m


# 8(i)

# In[85]:


page=requests.get('https://www.journals.elsevier.com/artificial-intelligence/most-downloaded-articles')
page


# In[86]:


soup=BeautifulSoup(page.content)
soup


# In[87]:


name=[]
for i in soup.find_all('h2',class_='sc-1qrq3sd-1 gRGSUS sc-1nmom32-0 sc-1nmom32-1 btcbYu goSKRg'):
    name.append(i.text)
name


# In[88]:


author=[]
for i in soup.find_all('span',class_='sc-1w3fpd7-0 dnCnAO'):
    author.append(i.text)
author


# In[89]:


date=[]
for i in soup.find_all('span',class_='sc-1thf9ly-2 dvggWt'):
    date.append(i.text)
date


# In[90]:


url=[]
for i in soup.find_all('article',class_='sc-5smygv-0 fIXTHm'):
    url.append(i.text)
url


# In[91]:


df=pd.DataFrame({'Paper Title':name,'Author':author,'Date of Publish':date})
df


# 9

# In[92]:


page=requests.get('https://www.dineout.co.in/delhi-restaurants/buffet-special')
page


# In[93]:


soup=BeautifulSoup(page.content)
soup


# In[94]:


titles=[]
for i in soup.find_all('a',class_='restnt-name ellipsis'):
    titles.append(i.text)

titles


# In[95]:


location=[]
for i in soup.find_all('div',class_='restnt-loc ellipsis'):
    location.append(i.text)

location


# In[96]:


cuisine=[]
for i in soup.find_all('span',class_='double-line-ellipsis'):
    cuisine.append(i.text)

cuisine


# In[97]:


images=[]
for i in soup.find_all('img',class_='no-img'):
    images.append(i.get('data-src'))
images


# In[98]:


rating=[]
for i in soup.find_all('div',class_='restnt-rating rating-4'):
    rating.append(i.text)
rating


# In[99]:


import pandas as pd
df=pd.DataFrame({'Titles':titles,'Locations':location,'Price and Cuisine':cuisine,'Ratings':rating,'Image_url':images})
df


# 10

# In[100]:


page=requests.get('https://scholar.google.com/citations?view_op=top_venues&hl=en')
page


# RESPONSE IS NOT 200, WE CANNOT SCRAPE DATA FROM THIS WEBSITE

# In[ ]:




