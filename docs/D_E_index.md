# Workflow D

## Technical Modification

Workflow D asks for a small technical change. I decided to do multiple small changes. I started by changing the "First 1000 characters" to only 100 characters. I didn't see the need to see that many characters, and I often get visually overwhelmed when I see such a large block of text in the terminal.

Ths second thing I did was change the "First 20 raw words" and the "First 20 clean words" to display 25 words in both instances. I just wanted to see that the change was as simple as changing the number. I also changed the display of the most frequent words from 20 to 25 as well.

I then changed the most frequent words displayed in the bar graph from 10 to 15, and I changed the colors used in the word cloud. I did this because I wanted to have results where it was easy to see that they were different from the original example.

![Bar Graph](/docs/images/workflow_4_bar.png)

![Word Cloud](/docs/images/workflow_4_wordcloud.png)

## Custom Application

For the custom application I changed the data source. I found the UK's breed standard for the American Pitbull Terrier. This is one of my favorite dog breeds but I know there are more restrictions on them in the UK. I was interested to see what they had to say and what they included in their breed standard.

I kept the majority of the settings the same between my technical change code (web_words_hummel.py) and this application. I did reduce the raw words and clean words display from 25 back down to 20. I kept the bar graph displaying the 15 most frequent words, and then changed the bar graph and the word cloud colors.

I found that the most frequent words were "hunting" and "events". I was happy to see this as I was nervous about how much it would focus on the breed's negative reputation. This shows that this article most likely focuses on the history of the breed and not their controversy.

One of the problems with dataset was that there were a lot of words that weren't specific to the text or to the meaning of the text. For example, the second most frequently used word was "with" which is not specific to the article. "from", "about", and "well" were also in the top 15 and do not have meanings specific to the article.

Next steps would be to remove the words that are not specific to the text and see how that changes the results. There are also some words that could use more context. For example, the word "forms" is the 5th most frequent word, but there is a possibility that there are links to fill out forms to register your pet, which could be skewing the number of times "forms" is counted.

![Pitbull Bar Graph](/docs/images/pitbull_bargraph.png)

![Pitbull Word Cloud](/docs/images/pitbull_wordcloud.png)
