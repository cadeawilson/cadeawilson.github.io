# Data Analyst

## Education
- M.S. Information Science | University of Colorado, Boulder (_May 2024_)
_Honors_: Graduate Student Association Master's Representative
- B.S. Information Science | University of Colorado, Boulder (_May 2023_)
_Honors_: Graduated with distinction, Dean’s List, Chancellor’s Achievement Scholarship recipient
- B.S. Public Relations | University of Colorado, Boulder (_Dec 2022_)
_Honors_: Graduated with distinction, Dean's List

_What is Information Science?_

Information Science is an interdisciplinary program combining elements from social science, computer science, and humanities to have conceptual knowledge and technical skills needed to design, create, and understand technology. There is a large focus on analyzing data, communicating technical information to stakeholders, and creating innovative solutions. Areas of study include data science, human-computer interaction, information visualization, machine learning, and technology ethics. 


## Certificates
- Certified in Planning and Inventory Management (CPIM) | Association for Supply Chain Management (ASCM) (_In Progress_)
- [Hyperledger Aries Developer Certification](https://courses.edx.org/certificates/e241341666264fcf8ac11ee9c57941e5) | The Linux Foundation (_Aug 2023_)
- [Hyperledger Self-Sovereign Identity Certification](https://courses.edx.org/certificates/80f37e43839f49119ecca06cb0ec8f88) | The Linux Foundation (_Jul 2023_)
- [Financial Markets (with Honors)](https://www.coursera.org/account/accomplishments/certificate/WWA8HC8A6M2N) | Yale School of Management (_Dec 2022_)
- [The Science of Well-Being](https://www.coursera.org/account/accomplishments/certificate/YVJMVX74S9VA) | Yale University (_Jun 2020_)


## Experience

**Graduate Research Assistant: Colorado Laboratory for Users, Media, and Networks (University of Colorado, Boulder)** (_Mar 2022 - May 2024_)
- Conducted multi-platform social and financial analyses of major cryptocurrencies during market shock events. Insights were utilized to propose broader research methodologies and refine predictive models for cryptocurrency market dynamics. 
- Utilized data mining and network analysis on GameStop’s NFT Marketplace, producing an exploratory study on paid, earned, shared, and owned marketing models, leading to insights on consumer behavior in decentralized markets.
  
**Developer (Intern): Colvin Run Networks, Inc** (_May 2023 - Feb 2024_)
- Developed localized large language models (LLMs) using Python, streamlining Air Force maintenance tasks by integrating PDFs into a custom, queryable UI.
- Designed a blockchain network prototype using Hyperledger and Go, facilitating secure data transmission between drones and operators via command-line interface, in collaboration with Microsoft and IBM partners.  
- Conducted market research for the DoD Small Business Innovation Research (SBIR) program, identifying opportunities for enhancing secure data transmission, influencing R&D focus.

**Public Relations Strategist (Intern): Imagination Videobooks/Storybooks** (_August 2022 – Dec 2022_)
- Developed and executed a comprehensive PR plan, leveraging traditional and digital PR strategies, to expand the outreach of a local non-profit supporting inclusive reading tools.    
- Conducted demographic analysis using Python and Tableau, identifying schools with high target populations, leading to increased outreach efforts for potential partnerships.

_Student Roles_

**Grader: University of Colorado, Boulder** (_Sep 2023 - May 2024_)
- Graded assignments for three upper-division classes (data visualization, data mining in Python) with 40-60 students, providing detailed feedback to enhance students' technical skills and understanding.

**Learning Assistant: University of Colorado, Boulder** (_Apr 2021 - Dec 2021_)
- Applied active learning techniques and facilitated group discussions to improve understanding of key concepts for 66 freshman students
- Led discussions on communication, information science, media studies, and journalism, helping students critically analyze course material and apply concepts to real-world scenarios.


## Projects
### Information Science Master's Thesis: Beyond the Ledger: A Cross-Platform Analysis of Cryptocurrency Dynamics (_2024_)
[Thesis](assets/pdf/MSThesis-WILSON.pdf)

This thesis explores the intricate dynamics between major cryptocurrencies and online platforms, focusing on how development, community activity, and market trends intersect. By collecting and analyzing data across platforms like GitHub, Reddit, and Discord, the project delves into how these platforms shape the development and social sentiment of cryptocurrencies such as Bitcoin, Ethereum, Solana, and Dogecoin. It also evaluates how market shocks, such as the Ethereum Merge and FTX collapse, impact these interactions and drive community and developer behavior.

_Methodology_:
- _Data Collection_: Historical cryptocurrency price data was gathered alongside GitHub commits, Reddit posts, and Discord messages. This cross-platform data was integrated to build a comprehensive view of how social and technical elements interact.
  - _Reddit and Discord_: Data was collected from Reddit and Discord communities to assess sentiment and activity levels around major market events.
  - _GitHub_: Commit metadata (timestamps, messages) from the major repositories of top cryptocurrencies was gathered using GitHub’s API to analyze developer contributions.
- _Statistical Analysis_: Granger causality tests and correlation matrices were applied to uncover patterns and predictive relationships between platform activity and cryptocurrency price movements. Market events, such as the Ethereum Merge, were also examined to see their influence across platforms.
- _Visualization_: Various visual representations (time-series plots, correlation heatmaps) were created using Python libraries to depict the interaction between price data, developer activity, and community discussions.

_Findings_: The study uncovered significant insights into how different platforms drive cryptocurrency dynamics:
- _Reddit_: Primarily a platform for speculation, Reddit activity was found to correlate with short-term market movements, particularly during significant events such as price spikes or crashes.
- _Discord_: Real-time discussions on Discord surged during market shocks, such as the FTX collapse, indicating the platform's role as a space for immediate community interaction during crises.
- _GitHub_: Development trends on GitHub reflected longer-term project evolution and stability, showing less volatility compared to Reddit and Discord.

The analysis also revealed that while Bitcoin operates somewhat independently of other cryptocurrencies, altcoins such as Ethereum, Solana, and Cardano are more intertwined with platform activity and market trends.

_Conclusion_: This project illustrates the complex socio-technical ecosystem of cryptocurrencies, demonstrating how market shocks can amplify cross-platform dynamics. The findings show that Reddit and Discord play critical roles in influencing market sentiment and behavior, while GitHub remains a space for long-term development activity. Understanding these dynamics provides a nuanced view of how information and development flow within the decentralized blockchain environment.

_Skills Highlighted_:
- Cross-platform data analysis
- Time series and causal analysis
- Cryptocurrency market dynamics
- Data collection via APIs (Reddit, Discord, GitHub)
- Python programming (Pandas, Numpy, Matplotlib)
- Visualization of complex datasets

### Exploratory Text Mining using Machine Learning: Security and Ethical Implications of Blockchain Technology (_2024_)
[Project Website](https://sites.google.com/colorado.edu/blockchain-text-mining/home)

This project focuses on the application of text mining and machine learning techniques to analyze public sentiment around blockchain technology across multiple platforms, including NewsAPI, Reddit, and Medium. The primary goal was to understand the nuanced opinions, trends, and concerns associated with blockchain by extracting and interpreting text data from these platforms. Advanced Natural Language Processing (NLP) models were employed to uncover patterns in the discussions, providing insights into the evolving public discourse on blockchain technology.

_Methodology_:
- _Data Collection_: The text data was gathered from NewsAPI, Reddit, and Medium using APIs and web scraping. The data included articles, posts, and discussions centered around blockchain topics. Titles, comments, and full-text descriptions were collected and processed.
- _Data Preprocessing_: The data underwent preprocessing steps such as lemmatization, stemming, and tokenization to clean and standardize it for further analysis. Stop words were removed, and text was transformed into numerical formats using count vectorization and TF-IDF techniques.
- _Machine Learning Models_:
  - Latent Dirichlet Allocation (LDA): Used for topic modeling to identify major themes and trends within blockchain discussions on each platform​
  - Sentiment Analysis with SVMs and Naïve Bayes: Supervised models like Support Vector Machines (SVMs)​ and Naïve Bayes​ were trained to classify sentiments as positive, neutral, or negative.
  - Decision Trees: Decision Trees were implemented to classify and analyze the features contributing most to sentiment predictions, providing an interpretable model for sentiment categorization​
  - Clustering (K-Means and Hierarchical): Unsupervised clustering methods were used to discover patterns in the text data, revealing how different clusters of blockchain-related discussions formed across platforms​
  - Association Rule Mining (ARM): Apriori algorithms were applied to discover relationships between common terms in discussions, offering insights into frequently co-occurring terms in blockchain-related topics
- _Visualization & Evaluation_: Results were visualized using bar charts, dendrograms, and confusion matrices to assess model performance and interpret the findings.

_Findings_:
- _Sentiment Insights_: Analysis revealed that discussions around blockchain across all platforms were dominated by financial and technological themes, with a significant portion of the discourse focused on cryptocurrency, blockchain security, and future technological applications. Reddit and Medium discussions showed more polarized sentiments (both highly positive and negative), while news articles remained more neutral​
- _Topic Modeling_: LDA uncovered recurring themes such as ‘cryptocurrency,’ ‘investment,’ ‘security,’ and ‘smart contracts,’ highlighting that discussions are often centered around blockchain's financial and developmental impact​
- _Clustering_: K-means and hierarchical clustering revealed that Reddit discussions were more fragmented into specific subtopics compared to NewsAPI and Medium, where broader themes emerged​
- _Association Rules_: ARM identified strong associations between blockchain-specific terms such as 'halving' and 'bitcoin,' and 'smart' and 'contract,' providing insights into the key drivers of blockchain discussions across platforms​

_Conclusion_: The Blockchain Text Mining project provided valuable insights into public discourse surrounding blockchain technology. By analyzing sentiment, identifying major topics, and discovering patterns in textual data, the project offers a comprehensive understanding of how blockchain is perceived across different online platforms. The results emphasize the importance of monitoring and interpreting public sentiment in shaping the future of blockchain technology, particularly in terms of investment, regulation, and security concerns.

_Skills Highlighted_:
- Text mining and Natural Language Processing (NLP)
- Machine learning for sentiment analysis and clustering
- Data visualization and interpretation
- Python (Numpy, Pandas, Scikit-learn, NLTK)
- Data collection via APIs and web scraping (NewsAPI, Reddit, Medium)

### Web Data Science Analysis: Exploring the Correlation Between Cryptocurrency Price Fluctuations and GitHub Commits (_2023_)
[Paper](assets/pdf/WebDataScience-WILSON.pdf)

This project investigates the relationship between cryptocurrency price volatility and the corresponding level of developer activity on GitHub. The core objective was to analyze how daily market price fluctuations impact the frequency of code contributions within open-source blockchain ecosystems, focusing on popular cryptocurrencies such as Bitcoin, Ethereum, Solana, and Cardano. By collecting and analyzing data over a one-year period (2022-2023), the study aimed to identify whether market instability influences developer engagement in these decentralized networks.

The project utilized a dual data collection approach:
- _Cryptocurrency Pricing Data_: Using Selenium for web automation, daily historical price data (open, high, low, close, adjusted close, and volume) was gathered from Yahoo Finance for each cryptocurrency in the study.
- _Developer Activity Data_: GitHub’s API was employed to extract commit history metadata (timestamps, messages) from each cryptocurrency’s primary repository.

_Methodology_:
- _Data Collection_: Python-based web scraping (Selenium) and API integration (GitHub) were utilized to gather pricing and commit data over the selected one-year period.
- _Statistical Analysis_: Linear regression models and time-series analyses were applied to examine potential correlations between daily price fluctuations and developer activity.
- _Visualizations_: Data trends were depicted through graphical outputs, highlighting key price movements and commit frequency.

_Findings_: Despite initial hypotheses suggesting that price volatility could either catalyze or deter developer activity, the analysis revealed no significant correlation between market price fluctuations and GitHub commit activity. The regression model showed an extremely low R-squared value (0.001), indicating that only 0.1% of commit frequency variation could be explained by changes in cryptocurrency prices. Further statistical tests also supported the conclusion that daily price movements do not predict changes in developer activity.

_Conclusion_: The project demonstrates that developer activity in the cryptocurrency space is largely unaffected by short-term market price volatility, suggesting that the motivations and workflows of open-source contributors are insulated from immediate market speculation. While the findings indicate a weak link between prices and commit activity, the study opens pathways for future research to examine other factors influencing blockchain development.

_Skills Highlighted_:
- Web data scraping (Selenium)
- API integration (GitHub)
- Data analysis and visualization (Pandas, Matplotlib)
- Linear regression and time-series analysis
- Python programming (Numpy, Scipy, Sklearn)

### COLUMN Lab Research: Decentralized Markets Versus the PESO Model (_2022_)
[Paper](assets/pdf/GameStopNFTMarketEDA-WILSON.pdf)

This project examines the application and limitations of traditional marketing models, particularly the PESO Model (Paid, Earned, Shared, Owned), within decentralized markets. Focusing on the GameStop NFT Marketplace, which launched in July 2022, this exploratory data analysis (EDA) investigates the effectiveness of various marketing tactics used by NFT projects like MetaBoy and CYBER CREW [C4]. By analyzing social media activity on Twitter and Discord, the study aims to uncover how decentralized marketing frameworks diverge from traditional ones and whether the PESO Model requires adaptation in these new digital environments.

_Methodology_:
- _Data Collection_: Using Twitter API v2 and DiscordChatExporter, social media data was collected from the Twitter accounts and Discord servers of two NFT projects: MetaBoy and CYBER CREW [C4]. Metrics such as tweet engagement (retweets, favorites) and Discord activity (unique message authors, total messages) were gathered and organized into CSV files for analysis.
- _Data Cleaning & Preparation_: Tableau Prep was used to clean the datasets, organizing the data by date and engagement metrics.
- _Analysis & Visualization_: In Tableau Desktop, the data was visualized to compare Twitter and Discord engagement trends. Bar charts were used to depict retweets, favorites, and overall message volume over time, allowing cross-platform comparisons of activity.

Case Studies:
- _MetaBoy_: A collection of 10,000 NFTs that launched on the GameStop Marketplace in July 2022. MetaBoy used a highly successful marketing strategy centered around giveaways of rare assets, which incentivized users to engage with the brand through social media. MetaBoy funneled users into its Discord server for deeper community engagement, resulting in a significant growth in community size and activity.
- _CYBER CREW [C4]_: This project took a slightly different approach, emphasizing asset utility and partnering with other creators for cross-promotion. CYBER CREW also used giveaways and social media to generate hype but focused on building a unique brand personality through user-generated content and consistent community engagement on Discord.

_Findings_:
- _Shared and Owned Media Dominance_: Both MetaBoy and CYBER CREW [C4] relied heavily on shared and owned media (Twitter and Discord) for their marketing success, without any significant use of paid advertising. This finding challenges the traditional PESO Model, which prioritizes paid advertising, by showing that shared and owned media are more critical in decentralized markets.
- _Successful Tactics_: Giveaways, asset teasers, highlighting utility, and user-generated content were the most successful tactics for engaging the community. Discord engagement often spiked following high-impact tweets or announcements, confirming the importance of cross-platform synergy in decentralized marketing efforts.

_Conclusion_: The project reveals that the PESO Model, as traditionally applied, is outdated for decentralized markets like the GameStop NFT Marketplace. Instead, a revised framework—an SOE (Shared, Owned, Earned) Model—should be adopted, where shared and owned media are prioritized. This EDA shows that decentralized marketing thrives on community engagement, hype generation, and direct consumer interactions through social platforms. Brands and projects in decentralized markets should focus on leveraging shared and owned media to maximize their impact.

Skills Highlighted:
- Data collection via APIs (Twitter, Discord)
- Social media analysis
- Data visualization (Tableau)
- Exploratory data analysis (EDA)
- Marketing strategy evaluation for decentralized platforms
