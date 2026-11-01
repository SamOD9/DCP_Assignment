# DCP_Assignment
## Study Session Tracker
I have chosen to do my dataset on my study sessions as its something i do most days and is easily measured

## Questions
Q1. Which subject gets my best focus, and which gets my worst?  
Q2. Does caffeine make a difference?  
Q3. Where do i focus best, and where do i get the most distractions?  

## Data Dictionary
| Column | Type | Unit / values | How I measure it |
|---|---|---|---|
| date | date | YYYY-MM-DD | Day of the session |
| start_time | time | 24h HH:MM | Read from the clock when I start |
| minutes_studied | numeric | minutes | Stopwatch, paused for breaks |
| subject | category | Fixed List | Fixed list, picked at the start |
| location | category | library ,home, other | Fixed list, where I sat |
| num_of_distractions | numeric | count | Pen tally during the session |
| focus | numeric | 1-5 | Rated immediately after (scale below) |
| caffeine | category | y / n | Tea or coffee in the 2 hours before |

### Subject List
-----------------
Maths  
DCP (Data Centric Programming)  
Databases  
HCD (Human Centered Design)  
ADM (Analytics for Desicion Making)  
WebDev (Web developement)  

### Location List
------------------
Library  
Home  
Other  

### Focus scale
----------------
| Rating | Meaning |
|---|---|
| 1 | Barely worked |
| 2 | Very distracted |
| 3 | Okay |
| 4 | Good  |
| 5 | Deep focus |
