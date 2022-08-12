## Oahu Surf Shop Analysis

### Overview
After a phenomenal vacation on Oahu last year, I decided it was time for a change in lifestyle. Combining my business knowhow and passion for an active, delicious lifestyle, I landed on a plan to open an ice cream surf shop for locals on the island. I drafted a business plan and shared it with W. Avy, an avid surfer and investor. He was enthusiastic but wanted us to look further into weather patters to ensure Oahu could support this shop year-round. We tracked down weather data from past years and I analyzed temperature and precipitation throughout the year, focusing on December and June to understand the contrasting seasons. W. Avy and I intend to share this data with our investors to demonstrate that Oahu truly is a great locale for an ice create surf shop. 

### Results
I used a combination of tools from the Python SQL toolkit to complete this analysis. The primary focus is on temperature. Comparing June temperatures to December temperatures from weather stations across the island of Oahu, I found the following differences:

- The average temperature in June is higher than December: 75F vs. 71F. What is notable here is that both temperatures are very comfortable - not too hot or too cold.

- June temperatures have a tighter temperature range compared to December temps.  In June, the min temp last year was 64F with a max high of 85F; this is a range of 21 degrees F. In December, the temperatures have a wider range with a minimum of 56F and high of 83F. The range here is 27 degrees F. While it does get slightly cooler in December, the low temp is again considered very comfortable, in general. 
- There were more temperature measurements taking in June (1700) compared with December (1517). This may be due to the holidays late in December.

#### June Temperature Summary Statistics:
![image]('June_Temps.png')

#### December Temperature Summary Statistics:
![image]('Dec_Temp.png')

### Summary
At a high-level, the differences observed in temperature between June and December are negligle. The temperature is not too cold in December (low of 56F) and not too hot in June (high of 85F). Based on temperature alone, it's hard to imagine much better weather year-round for surfing. Oahu has the perfect weather to encourage some sweet indulgence before or after a wave session. 

Given the great weather, I feel confident about Oahu but decided to double-check that rain wouldn't be a prohibitive factor. I compared June precipitation with December and found that on average, it rains a bit less in June but not significantly (0.13 inches of rain on average in June vs. 0.22 inches of rain in December). What I observe in the range of data, however, is that the majority of days have minimal rain as both June and December range from 0 to 0.02 and 0.03 for 50% of measured days. The max amount of rain measured on a given day is higher in December, however: 6.5 inches in December vs. 4.4 inches in June. Overall, it seems there may be some days with heavier rainfall in December but at least half of the days are rain-free and pleasant. 

#### June Precipitation Summary Statistics:
![image]('June_Rain.png')

#### December Precipitation Summary Statistics:
![image]('Dec_Rain.png')

W.Avy and I feel certain the investors will agree - Oahu is made for ice cream and surfing!