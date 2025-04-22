The Problem I Wanted to Solve

In an age where news is everywhere and bias is hard to avoid I wanted to build something that could help classify political leanings in articles.

"What if we could build a tool that reads a news article and assigns it a political bias Left, Center, or Right along with a score from 1 to 10, where 1 is most Left and 10 is most Right?"
That led to this experiment — running LLaMA 3.2 locally to build a simple, secure, and insightful tool that helps analyze the political tilt of news content.
Stored this articles and looked if these articles are written based on any political scenarios creating a commotion?

My Approach
I broke this down into a few key phases:
1. Getting LLaMA 3.2 Running Locally
Downloaded the model and explored how to run it.
This was my first time ever running an LLM locally.

2. Designing the Classifier
Used carefully crafted prompts to ask the model:
To read a news article.
To classify it as Left (1-3), Center (4-6), or Right (7-10).
To provide a reasoning/explanation behind the score.

3. Testing with Real News
I used a mix of articles from various known sources to check how consistently the model responds.
The idea was not just raw classification, but to build explain ability into every result.
