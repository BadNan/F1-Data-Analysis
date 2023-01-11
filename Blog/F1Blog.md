# Are F1 cars getting slower?

Using Kaggle's F1 Data set, I try to answer this question but I do so by diving into 3 important sub questions that need attention first.

## Introduction
F1 is the pinnacle of motorsport where all constructor teams are competing to be the fastest. But is it possible for teams to constantly engineer faster F1 cars year after year or have we reached a plateau in development? 

I believe this question is very complex and many areas of F1 need to be considered before a decisive answer is given, however, any answer requires a starting point.

And I wish to start this off by answering the most fundamental question, are F1 cars getting slower?

Lets proceed in steps and answer the following questions first.

## Which year had the fastest lap time for each circuit?

Below you can see the fastest lap times in milliseconds for each track as well as the year the fastest lap was achieved. 

After summing the occurrences of each year, the year 1996 achieved the highest fastest lap times at 16 tracks. This is significantly higher than second place which was 1997 at 2 tracks. It is also worth noting that 1996 is the earliest year available in the dataset and it achieved the most fastest laps, so does that mean the current years are slower?

To answer that lets dive deeper into each track.

## Which track has the biggest improvement in lap time?

Below you can see a table grouped by name but the only column we will be focusing on is 'milliseconds_diff' because this column represents the difference between the slowest and fastest times for each circuit.

The table has been sorted in descending order so it can be seen that the Canadian Grand Prix has the largest difference, almost double that of second place, the British Grand Prix! 

However, there could be outliers and anomalies in the data which affect change in lap times so lets take a final look at the lap time trends over the years. 


## How do lap time vary throughout the years?

These plots show how the lap times vary throughout the years for each track. In general, lap times have stayed consistent through out the years although tracks such as the European Grand Prix saw its lap time getting slower over the years whilst the German Grand Prix saw a sharp decrease in lap times from the year ~2000 onwards.

It is also important to note that for those tracks that have been raced on for many years there are some years that recorded anomalous results such as Brazilian, British, Canadian, Japanese and Malaysian Grand Prix's. These outliers are also all significantly slower than the normal trend and explain why there was a large difference in lap times above.

## Are F1 cars getting slower then?

I tried to answer this question using lap times for each track and concluded that the answer is no and F1 cars are remaining steady throughout the years.

However, this is not the final answer to the question as more analyses need to be conducted such as have there been changes in tracks, rules, drivers impact and weather conditions.
