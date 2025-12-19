# Case 3: Econsultancy — *Six Insightful Data Storytelling Case Studies*
**Source:** [Econsultancy](https://econsultancy.com/six-insightful-data-storytelling-case-studies/)

---

## Business Context


The Econsultancy article “Six Insightful Data Storytelling Case Studies” illustrates how various businesses, including charities such as Marie Curie, retailers like Topshop and Homebase, and B2B companies like Farnell element14, leverage data not only for reporting but also to enhance personalization, make informed decisions, and foster more standard customer experiences. The common theme in these examples is that data gains strength when it's transcribed into a narrative with a defined audience and objective, rather than merely existing as a dashboard or table.


Starting from that objective, I aimed for Case Study 3 to implement the same concept of data storytelling, but within a different field than the first two case studies. The goal was to analyze famous data-intensive sectors that heavily rely on digital data, such as streaming, e-commerce, and digital media. Therefore,  I selected Spotify and music streaming as my focal point. Spotify is well-suited as it intercepts the crossroads of technology, culture, and data where each stream, skip, and save generates insights into how individuals engage with music.


Rather than examining one marketing campaign like those presented in the Econsultancy piece, this case study utilizes a publicly accessible Spotify audio-features dataset to analyze listening habits on a large scale. The dataset features track-level attributes like genre, popularity, energy, danceability, mood valence, tempo, and length. In analyzing this data, I aimed to comply with the principle emphasized in the article. It mentions about transforming a sizable and unstructured dataset into a narrative that reveals trends, helps in decision-making, and simplifies the numbers for non-technical audiences.


In this context, this case study represents my interpretation of a “data storytelling case study” influenced by Econsultancy’s model, but tailored to the music streaming industry, which is not only a well-known business but also critically important for data-informed decisions regarding personalization and product development.

---

## Communication Goals


The communication goal of this case study is to illustrate how large digital data can be transformed into a meaningful narrative through effective storytelling. I don't aim to predict any individual music taste or behavior. Through this dataset, the goal is to illustrate how patterns and trends in genres, mood, popularity, etc. can be visualized to make informed business decisions, product personalization, and optimization. 
This analysis aims to move beyond the raw data and answer some insightful questions regarding music choices, influence behavior, and attention span across the platform. The ultimate goal is to show that raw data can be presented as a narrative that is easier to understand and visualize. 
Audience


The target audience for this case study is Product managers, marketing teams, and data analysts who work in digital media and streaming platforms. Artists, record labels, and content creators who wish to learn more about the relationship between track attributes and listener interaction will also find it useful. This is also useful for Students and non-technical audiences who want to see how complicated datasets may be transformed into understandable visual narratives.

---
## Key Story Elements


The case study is  structured around some simple elements that follow the data storytelling emphasized in the article:


Context:  Streaming Platforms like Spotify generate vast amounts of raw data, which alone do not explain users' listening patterns.
 Exploration: We can examine genre mode and audio features from the data and understand how listeners interact with music. 
  Insights: The audience can visualize certain patterns like sound profiles and emotional tones 
Implication: these insights are useful to make informed business decisions,  product optimization, and personalization.

---
## Data and visualization


For this case study, I used a publicly accessible Spotify data set that includes popularity measures and track-level audio attributes. I walked with a pre-structured data set and focused on choosing quantifiable factors for analysis rather than generating a new data set.  The visualizations were made using Jupyter notebook to understand and analyze Trends across genres, mood, and popularity level. Rather than using sophisticated models, High prioritized clarity and interpretability using the same methodology as in the article; each graph was created to answer a particular query and a broader narrative. Request more than just complex Analytics; it also needs careful framing and presentation 



---

## 5. Visualizations & Analytical Questions
Visualization 1 — Average Track Popularity by Genre

Question:
Which music genres achieve the highest average popularity on Spotify?

Insight:
The visualization shows that a small number of genres consistently outperform others in average popularity. This indicates that listener attention is concentrated within specific genre categories, while many niche genres attract smaller but stable audiences.

Visualization 2 — Danceability vs Track Popularity

Question:
Does higher danceability correlate with greater track popularity?

Insight:
The scatter plot reveals a weak relationship between danceability and popularity, suggesting that danceability alone does not determine listener engagement. Popular tracks span a wide range of danceability levels.

Visualization 3 — Energy Level vs Track Popularity

Question:
Is there a relationship between a song’s energy level and its popularity?

Insight:
Tracks with moderate energy levels tend to cluster at higher popularity scores, while extremely low or high energy tracks show more variable performance. This suggests listener preference for balanced energy rather than extremes.

Visualization 4 — Track Duration and Popularity

Question:
How does track length influence listener popularity on Spotify?

Insight:
Songs with mid-range durations (approximately 2.5 to 5 minutes) show higher average popularity compared to very short or very long tracks. This reflects listener attention patterns and playlist optimization norms.

Visualization 5 — Valence (Mood) vs Track Popularity

Question:
Does the emotional tone of a song affect its popularity?

Insight:
Tracks with moderate valence scores tend to achieve higher popularity, while extremely positive or negative moods show greater dispersion. This suggests that emotionally balanced songs appeal to a broader audience.

Visualization 6 — Popularity Distribution Across Tracks

Question:
How evenly is popularity distributed across all tracks in the dataset?

Insight:
The distribution is heavily right-skewed, with a small number of tracks achieving very high popularity while most remain relatively obscure. This highlights the competitive and winner-take-most nature of music streaming platforms.

Visualization 7 — Top Tracks by Combined Audio Features

Question:
How do multiple audio features collectively characterize highly popular tracks?

Insight:
Highly popular tracks tend to share balanced combinations of danceability, energy, and mood rather than extreme values in any single feature. This reinforces the importance of multi-dimensional recommendation strategies.
