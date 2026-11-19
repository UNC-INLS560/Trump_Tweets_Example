# Trump_Tweets_Example
This repository includes data from the Data Driven Decision Lab (https://datadrivendecisionlab.com/). They archived over 90,0000 posts from Donald Trump's official account on Twitter, X, and Truth Social from 2009 to Jan 8, 2026.

# An initial prompt we can use to start our exercise

Goal: Create a console-based application that allows users to search for keywords in Trump's social media posts. The app should allow users to type a keyword. The system should respond with a text-based histogram showing the frequency of posts over time for the specific keyword. The system should also show the most recent and least recent matching posts (assuming there are at least two matching posts). If there is just one matching post, show that one. If there are no matching posts, tell the user.

Inputs: A CSV file containing Trump posts to Twitter, X, and Truth Social. The CSV file includes data of the post, as well as the channel (Twitter, X, Truth Social) and the content of the post.

Output: An interactive console that shows the histogram in text. The histogram should be color-coded based on the site posted to: blue for Twitter, white for X, and red for Truth Social.

Rules: The histogram should include 3-month intervals for the timeline. The search should be case-insensitive.

Edge cases: If a search has no match, tell the user to try again.

Examples: Searches could include "Clinton", "Biden", "Tariffs", and "election fraud"

Constraints: Use the CSV library for parsing the input file. Do not use type hints or docstrings. Comment code carefully. Make code legible for a beginner.

Before writing any code, interview me one question at a time until nothing in this prompt is unclear. Then rewrite it as a detailed spec using the same seven parts, and wait for my approval.

Also interview me about testing, and set up pytest tests in a separate test file that you never edit unless I ask.

After I approve, build the program in small steps. After each step, stop and tell me what changed so I can check it and commit.


