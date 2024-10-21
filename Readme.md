This project intends to predict anticipated movements in S&P 500 index which are being influenced by Fed Chair FOMC meetings.

We have tried different strategies 

1. Trading on sentiments of transcripts at 1 minute timestamps. We broke it to 1 minute period intervals
2. Trading on sentiments of rolling text to capture the sentiment so far. 
3. Trading on sentiment of rolling text along with MAV

In all the above strategies our threshold sentiment score was 0.1 and beyond 0.1 sentiment, we will take a long position and with a sentiment score less than 0.1 we will take a short position. 

We close all the positions at the last minute of FOMC meeting.

4. Trading on sentiment of whole FOMC meeting by taking position after the meeting along with MAV.
5. Trading on just the sentiments of whole FOMC meeting



