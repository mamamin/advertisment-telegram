# a project to optimize advertisment in telgram platform
The entire project we are currently working on is aimed at optimizing advertisement algorithms to improve advertising within the Telegram application. 
Our primary goal is to display our advertisements to as many people as possible who require our product while adhering to a fixed budget.
We refer to these individuals as our "target audience." The number of target individuals is contingent on various factors, such as a channel's subscriber count, 
the engagement rate of subscribers with channel posts, and the desire of those subscribers to purchase our product. When we mention the "engagement rate,"
we are referring to the cumulative reactions, comments, and views a post receives within different timeframes and on various days of the week.
To accomplish this, our first step is to collect data from different Telegram channels. This data includes the number of subscribers, 
the engagement rate of these subscribers, advertisement prices for each channel, and the main topic related to the channel's posts, which we term the "community label."
Gathering data on the engagement rate is particularly challenging since it necessitates collecting data from numerous posts on each channel. To address this challenge,
we've trained a neural network model that can predict the engagement rate of a channel using specific data from that channel. You can find detailed information about
this process in "result1.pdf" within the repository.
The subsequent tasks involve identifying community labels that closely align with our product and determining the overlap of subscribers across different channels. 
Advertising on channels with overlapping subscribers results in reduced exposure to our advertisements. To address these tasks, we've trained distinct neural networks. 
As a result, we've developed a highly intricate model capable of optimizing the Telegram platform as we originally intended. We also have plans to expand its use to
Instagram and other platforms. Our system has undergone extensive testing and can cater to a variety of usage scenarios. We have already attracted numerous customers 
and generated 50 million Tomans in revenue from this project.
