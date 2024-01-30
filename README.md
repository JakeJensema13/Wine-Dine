# Wine&Dine
![]('https://ibb.co/w0WBqWm')

## Inspiration
My journey into the world of wine was sparked by a wine tasting class I attended with friends during the fall. While the class provided valuable insights into winemaking, tasting techniques, and the essence of a "good" wine, it left me with a hunger for knowledge about wine pairings. I often found myself leaving the class with a growling stomach, unsure of how to perfectly complement the wines we tasted.

## What it does
Wine&Dine comprises two core components. Firstly, it focuses on predicting wine quality, because who wants to indulge in subpar, cheap wine? Through an array of models, I honed in on a Random Forest model that achieved up to 72% accuracy in predicting wine quality. Building on this, I delved into research to identify the grape varieties that make up Portuguese Vinho Verde red wine. By analyzing articles and leveraging our dataset, I pinpointed key variables that distinguish the three primary grapes used in Portuguese Vinho Verde red wine. Armed with this knowledge, I created a user-friendly application where users can input the grape type of their Portuguese Vinho Verde red wine. In return, I provide a curated list of delectable foods to pair with the wine, along with links to online recipes. My quest for innovation led me to harness the power of the OpenAI API, enabling me to generate unique food pairing suggestions and recipe links based on the user's grape selection.

## How we built it
I employed SingleStore for data management and analysis, utilizing Python alongside an array of packages for data exploration, cleaning, visualization, and statistical modeling. Additionally, I harnessed Python's GUI packages to craft straightforward pop-up buttons and create a seamless user experience.

## Challenges we ran into
Integrating the ChatGPT API with SingleStore presented a significant challenge. It required dedicated time and effort to overcome, involving thorough research and a helpful tutorial from the SingleStore website.

## Accomplishments that we're proud of
I take pride in successfully navigating the complexities of APIs and achieving impressive accuracy in predicting wine quality. Additionally, I'm delighted to emphasize that wine appreciation is an accessible and enjoyable experience for anyone over the age of 21, regardless of their budget or prior knowledge.

## What we learned
Throughout this project, I've learned that the joys of wine and dining are universal and can be savored by people from all walks of life. Wine is a great equalizer, and sharing the experience with others is a wonderful way to connect and explore the world of flavors.

## What's next for Wine&Dine
Hosting my project to a web app would be what I want how to do next
