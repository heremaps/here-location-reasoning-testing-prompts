# Testing Prompts (HERE tool-capability set)

Extracted from data/*_level*.csv — 240 prompts across 6 categories. Grouped by filename prefix (level digit stripped); the level (1–4) is the use_case.

### geocoding_and_search_level (40 prompts)

| #   | Prompt ID | Use Case | Prompt |
| --- | --------- | -------- | ------ |
| 1 | t_0001 | level 1 | Show me Italian restaurants near Union Square in San Francisco |
| 2 | t_0002 | level 1 | Find museums near the National Mall in Washington DC |
| 3 | t_0003 | level 1 | Find Starbucks locations near 200 Broadway, New York, NY |
| 4 | t_0004 | level 1 | Show me Apotheke near 52.5200, 13.4050 in Berlin |
| 5 | t_0005 | level 1 | Find hotels near Sagrada Familia in Barcelona |
| 6 | t_0006 | level 1 | Where are gas stations near zip code 75201 in Dallas |
| 7 | t_0007 | level 1 | Show me parks near Shibuya, Tokyo |
| 8 | t_0008 | level 1 | Find hospitals near Canary Wharf in London |
| 9 | t_0009 | level 1 | Find supermarkets near the corner of Broadway and 42nd Street in New York |
| 10 | t_0010 | level 1 | Show me EV charging stations near Amsterdam Centraal Station |
| 11 | t_0011 | level 2 | Show me Italian restaurants near Union Square in San Francisco and check traffic around there |
| 12 | t_0012 | level 2 | Find museums near the National Mall in Washington DC and walk me there from the Hilton on Capitol Hill |
| 13 | t_0013 | level 2 | Find Starbucks locations near 200 Broadway, New York, NY, which one is closest |
| 14 | t_0014 | level 2 | Show me Apotheke near 52.5200, 13.4050 in Berlin, check traffic around there |
| 15 | t_0015 | level 2 | Find hotels near Sagrada Familia in Barcelona, which one has the best rating |
| 16 | t_0016 | level 2 | Where are gas stations near zip code 75201 in Dallas, which one is closest |
| 17 | t_0017 | level 2 | Show me parks near Shibuya, Tokyo, check traffic around there |
| 18 | t_0018 | level 2 | Find hospitals near Canary Wharf in London, check traffic around the area |
| 19 | t_0019 | level 2 | Find supermarkets near the corner of Broadway and 42nd Street in New York, which one is closest |
| 20 | t_0020 | level 2 | Show me EV charging stations near Amsterdam Centraal Station, check traffic around there |
| 21 | t_0021 | level 3 | Show me Italian restaurants near Union Square in San Francisco and check traffic around there then tell me which one is closest to the square |
| 22 | t_0022 | level 3 | Find museums near the National Mall in Washington DC and walk me there from the Hilton on Capitol Hill then check traffic around the area |
| 23 | t_0023 | level 3 | Find Starbucks locations near 200 Broadway, New York, NY, which one is closest and walk me there |
| 24 | t_0024 | level 3 | Show me Apotheke near 52.5200, 13.4050 in Berlin, check traffic around there and tell me which one is closest |
| 25 | t_0025 | level 3 | Find hotels near Sagrada Familia in Barcelona, which one has the best rating, check traffic around it |
| 26 | t_0026 | level 3 | Where are gas stations near zip code 75201 in Dallas, which one is closest and drive me there |
| 27 | t_0027 | level 3 | Show me parks near Shibuya, Tokyo, check traffic around there and tell me which park is closest |
| 28 | t_0028 | level 3 | Find hospitals near Canary Wharf in London, check traffic around the area and drive me to the closest one |
| 29 | t_0029 | level 3 | Find supermarkets near the corner of Broadway and 42nd Street in New York, which one is closest and walk me there |
| 30 | t_0030 | level 3 | Show me EV charging stations near Amsterdam Centraal Station, check traffic around there and tell me which one is closest |
| 31 | t_0031 | level 4 | Show me Italian restaurants near Union Square in San Francisco and check traffic around there then tell me which one is closest to the square and give me directions to it |
| 32 | t_0032 | level 4 | Find museums near the National Mall in Washington DC and walk me there from the Hilton on Capitol Hill then check traffic around the area and tell me which roads are most congested |
| 33 | t_0033 | level 4 | Find Starbucks locations near 200 Broadway, New York, NY, which one is closest and walk me there, also check traffic around that area |
| 34 | t_0034 | level 4 | Show me Apotheke near 52.5200, 13.4050 in Berlin, check traffic around there and tell me which one is closest and walk me there |
| 35 | t_0035 | level 4 | Find hotels near Sagrada Familia in Barcelona, which one has the best rating, check traffic around it and drive me there |
| 36 | t_0036 | level 4 | Where are gas stations near zip code 75201 in Dallas, which one is closest and drive me there, also check traffic around that area |
| 37 | t_0037 | level 4 | Show me parks near Shibuya, Tokyo, check traffic around there and tell me which park is closest and walk me there |
| 38 | t_0038 | level 4 | Find hospitals near Canary Wharf in London, check traffic around the area and drive me to the closest one, then find pharmacies near it |
| 39 | t_0039 | level 4 | Find supermarkets near the corner of Broadway and 42nd Street in New York, which one is closest and walk me there, also check traffic around Times Square |
| 40 | t_0040 | level 4 | Show me EV charging stations near Amsterdam Centraal Station, check traffic around there and tell me which one is closest and drive me there |

### isoline_routing_level (40 prompts)

| #   | Prompt ID | Use Case | Prompt |
| --- | --------- | -------- | ------ |
| 41 | t_0041 | level 1 | Show me everywhere I can drive within 20 minutes from Portland |
| 42 | t_0042 | level 1 | How far can I get in 10 miles from downtown Denver |
| 43 | t_0043 | level 1 | Where can I walk to in 15 minutes from Faneuil Hall in Boston |
| 44 | t_0044 | level 1 | Where could fans drive from to reach Nissan Stadium in Nashville within 45 minutes |
| 45 | t_0045 | level 1 | What areas can I reach in 30 minutes from the Space Needle in Seattle |
| 46 | t_0046 | level 1 | Show me where I can cycle to in 15 minutes from 52.3676, 4.9041 in Amsterdam |
| 47 | t_0047 | level 1 | What area can a truck cover within 25 and 50 kilometers from zip code 60601 in Chicago |
| 48 | t_0048 | level 1 | Show me where people could drive from to reach Wembley Stadium in London within 30 minutes arriving by 7 PM |
| 49 | t_0049 | level 1 | How far can I walk within 2 kilometers from 350 Fifth Avenue in New York |
| 50 | t_0050 | level 1 | Show me what I can reach by car in 10, 20, and 30 minutes from the Arc de Triomphe in Paris departing at 8 AM |
| 51 | t_0051 | level 2 | Show me everywhere I can drive within 20 minutes from Portland, look for coffee shops in that area |
| 52 | t_0052 | level 2 | How far can I get in 10 miles from downtown Denver, see if there are any gas stations in that area |
| 53 | t_0053 | level 2 | Where can I walk to in 15 minutes from Faneuil Hall in Boston, check if there are lunch spots nearby |
| 54 | t_0054 | level 2 | Where could fans drive from to reach Nissan Stadium in Nashville within 45 minutes, also find hotels nearby |
| 55 | t_0055 | level 2 | What areas can I reach in 30 minutes from the Space Needle in Seattle, find breweries there |
| 56 | t_0056 | level 2 | Show me where I can cycle to in 15 minutes from 52.3676, 4.9041 in Amsterdam, find bike rental shops nearby |
| 57 | t_0057 | level 2 | What area can a truck cover within 25 and 50 kilometers from zip code 60601 in Chicago, find truck stops in that area |
| 58 | t_0058 | level 2 | Show me where people could drive from to reach Wembley Stadium in London within 30 minutes arriving by 7 PM, find pubs near the stadium |
| 59 | t_0059 | level 2 | How far can I walk within 2 kilometers from 350 Fifth Avenue in New York, find cafes nearby |
| 60 | t_0060 | level 2 | Show me what I can reach by car in 10, 20, and 30 minutes from the Arc de Triomphe in Paris departing at 8 AM, find restaurants in the area |
| 61 | t_0061 | level 3 | Show me everywhere I can drive within 20 minutes from Portland, look for coffee shops in that area, figure out which has the best rating |
| 62 | t_0062 | level 3 | How far can I get in 10 miles from downtown Denver, see if there are any gas stations in that area, also check traffic around there |
| 63 | t_0063 | level 3 | Where can I walk to in 15 minutes from Faneuil Hall in Boston, check if there are lunch spots nearby, let me know which one is closest |
| 64 | t_0064 | level 3 | Where could fans drive from to reach Nissan Stadium in Nashville within 45 minutes, also find hotels nearby, route me from the closest one to the stadium |
| 65 | t_0065 | level 3 | What areas can I reach in 30 minutes from the Space Needle in Seattle, find breweries there, check traffic around the area |
| 66 | t_0066 | level 3 | Show me where I can cycle to in 15 minutes from 52.3676, 4.9041 in Amsterdam, find bike rental shops nearby, which one is closest |
| 67 | t_0067 | level 3 | What area can a truck cover within 25 and 50 kilometers from zip code 60601 in Chicago, find truck stops in that area, check traffic around there |
| 68 | t_0068 | level 3 | Show me where people could drive from to reach Wembley Stadium in London within 30 minutes arriving by 7 PM, find pubs near the stadium, which one has the best rating |
| 69 | t_0069 | level 3 | How far can I walk within 2 kilometers from 350 Fifth Avenue in New York, find cafes nearby, which one is closest |
| 70 | t_0070 | level 3 | Show me what I can reach by car in 10, 20, and 30 minutes from the Arc de Triomphe in Paris departing at 8 AM, find restaurants in the area, check traffic around there |
| 71 | t_0071 | level 4 | Show me everywhere I can drive within 20 minutes from Portland, look for coffee shops in that area, figure out which has the best rating and give me directions to it |
| 72 | t_0072 | level 4 | How far can I get in 10 miles from downtown Denver, see if there are any gas stations in that area, also check traffic around there and tell me which is easiest to reach |
| 73 | t_0073 | level 4 | Where can I walk to in 15 minutes from Faneuil Hall in Boston, check if there are lunch spots nearby, let me know which one is closest and check traffic around it |
| 74 | t_0074 | level 4 | Where could fans drive from to reach Nissan Stadium in Nashville within 45 minutes, also find hotels nearby, route me from the closest one to the stadium and check traffic along the way |
| 75 | t_0075 | level 4 | What areas can I reach in 30 minutes from the Space Needle in Seattle, find breweries there, check traffic around the area and take me to the closest brewery |
| 76 | t_0076 | level 4 | Show me where I can cycle to in 15 minutes from 52.3676, 4.9041 in Amsterdam, find bike rental shops nearby, which one is closest and bike me there |
| 77 | t_0077 | level 4 | What area can a truck cover within 25 and 50 kilometers from zip code 60601 in Chicago, find truck stops in that area, check traffic around there and tell me which truck stop is closest |
| 78 | t_0078 | level 4 | Show me where people could drive from to reach Wembley Stadium in London within 30 minutes arriving by 7 PM, find pubs near the stadium, which one has the best rating and walk me there |
| 79 | t_0079 | level 4 | How far can I walk within 2 kilometers from 350 Fifth Avenue in New York, find cafes nearby, which one is closest and check traffic around there |
| 80 | t_0080 | level 4 | Show me what I can reach by car in 10, 20, and 30 minutes from the Arc de Triomphe in Paris departing at 8 AM, find restaurants in the area, check traffic around there and drive me to the best rated one |

### matrix_routing_level (40 prompts)

| #   | Prompt ID | Use Case | Prompt |
| --- | --------- | -------- | ------ |
| 81 | t_0081 | level 1 | I need to compare all the driving times between New York, Boston, Philadelphia, and Washington DC |
| 82 | t_0082 | level 1 | Which pair of these cities is closest by car: Chicago, Milwaukee, Indianapolis, Detroit, and St. Louis — show both times and distances |
| 83 | t_0083 | level 1 | I'm planning truck deliveries between Atlanta, Nashville, Charlotte, and Jacksonville — what are all the distances between them |
| 84 | t_0084 | level 1 | What are all the walking times between the Lincoln Memorial, the Capitol Building, the White House, the Washington Monument, and the Smithsonian |
| 85 | t_0085 | level 1 | What are all the driving distances between San Francisco, San Jose, Oakland, Berkeley, and Palo Alto optimizing for distance not speed |
| 86 | t_0086 | level 1 | How do cycling times look between Vondelpark, Rijksmuseum, Anne Frank House, and Dam Square in Amsterdam |
| 87 | t_0087 | level 1 | What are all the driving times between Buckingham Palace, Tower of London, British Museum, and Hyde Park in London |
| 88 | t_0088 | level 1 | What are the trucking distances between zip codes 77001 in Houston, 78201 in San Antonio, 75201 in Dallas, 73301 in Austin, and 76102 in Fort Worth |
| 89 | t_0089 | level 1 | What are all the driving distances between Paris, Brussels, Amsterdam, and Frankfurt |
| 90 | t_0090 | level 1 | I'm walking around Manhattan — compare walking times between 350 Fifth Avenue, Times Square, Grand Central Terminal, and Bryant Park |
| 91 | t_0091 | level 2 | I need to compare all the driving times between New York, Boston, Philadelphia, and Washington DC, also find hotels near each city |
| 92 | t_0092 | level 2 | Which pair of these cities is closest by car: Chicago, Milwaukee, Indianapolis, Detroit, and St. Louis — show both times and distances, find restaurants near the closest pair |
| 93 | t_0093 | level 2 | I'm planning truck deliveries between Atlanta, Nashville, Charlotte, and Jacksonville — what are all the distances between them, find gas stations near Jacksonville |
| 94 | t_0094 | level 2 | What are all the walking times between the Lincoln Memorial, the Capitol Building, the White House, the Washington Monument, and the Smithsonian, also find cafes nearby |
| 95 | t_0095 | level 2 | What are all the driving distances between San Francisco, San Jose, Oakland, Berkeley, and Palo Alto optimizing for distance not speed, find restaurants near the closest pair |
| 96 | t_0096 | level 2 | How do cycling times look between Vondelpark, Rijksmuseum, Anne Frank House, and Dam Square in Amsterdam, find bike rental shops nearby |
| 97 | t_0097 | level 2 | What are all the driving times between Buckingham Palace, Tower of London, British Museum, and Hyde Park in London, find pubs nearby |
| 98 | t_0098 | level 2 | What are the trucking distances between zip codes 77001 in Houston, 78201 in San Antonio, 75201 in Dallas, 73301 in Austin, and 76102 in Fort Worth, find gas stations near the closest pair |
| 99 | t_0099 | level 2 | What are all the driving distances between Paris, Brussels, Amsterdam, and Frankfurt, find hotels near the closest pair |
| 100 | t_0100 | level 2 | I'm walking around Manhattan — compare walking times between 350 Fifth Avenue, Times Square, Grand Central Terminal, and Bryant Park, find cafes nearby |
| 101 | t_0101 | level 3 | I need to compare all the driving times between New York, Boston, Philadelphia, and Washington DC, also find hotels near each city, figure out which has the best rating |
| 102 | t_0102 | level 3 | Which pair of these cities is closest by car: Chicago, Milwaukee, Indianapolis, Detroit, and St. Louis — show both times and distances, find restaurants near the closest pair, pick the best rated |
| 103 | t_0103 | level 3 | I'm planning truck deliveries between Atlanta, Nashville, Charlotte, and Jacksonville — what are all the distances between them, find gas stations near Jacksonville, check traffic around there |
| 104 | t_0104 | level 3 | What are all the walking times between the Lincoln Memorial, the Capitol Building, the White House, the Washington Monument, and the Smithsonian, also find cafes nearby, check traffic around the area |
| 105 | t_0105 | level 3 | What are all the driving distances between San Francisco, San Jose, Oakland, Berkeley, and Palo Alto optimizing for distance not speed, find restaurants near the closest pair, pick the best rated |
| 106 | t_0106 | level 3 | How do cycling times look between Vondelpark, Rijksmuseum, Anne Frank House, and Dam Square in Amsterdam, find bike rental shops nearby, which one is closest |
| 107 | t_0107 | level 3 | What are all the driving times between Buckingham Palace, Tower of London, British Museum, and Hyde Park in London, find pubs nearby, pick the best rated |
| 108 | t_0108 | level 3 | What are the trucking distances between zip codes 77001 in Houston, 78201 in San Antonio, 75201 in Dallas, 73301 in Austin, and 76102 in Fort Worth, find gas stations near the closest pair, check traffic around there |
| 109 | t_0109 | level 3 | What are all the driving distances between Paris, Brussels, Amsterdam, and Frankfurt, find hotels near the closest pair, pick the best rated |
| 110 | t_0110 | level 3 | I'm walking around Manhattan — compare walking times between 350 Fifth Avenue, Times Square, Grand Central Terminal, and Bryant Park, find cafes nearby, which one is closest |
| 111 | t_0111 | level 4 | I need to compare all the driving times between New York, Boston, Philadelphia, and Washington DC, also find hotels near each city, figure out which has the best rating and check traffic around it |
| 112 | t_0112 | level 4 | Which pair of these cities is closest by car: Chicago, Milwaukee, Indianapolis, Detroit, and St. Louis — show both times and distances, find restaurants near the closest pair, pick the best rated and route me there |
| 113 | t_0113 | level 4 | I'm planning truck deliveries between Atlanta, Nashville, Charlotte, and Jacksonville — what are all the distances between them, find gas stations near Jacksonville, check traffic around there and pick the closest gas station |
| 114 | t_0114 | level 4 | What are all the walking times between the Lincoln Memorial, the Capitol Building, the White House, the Washington Monument, and the Smithsonian, also find cafes nearby, check traffic around the area, pick the closest cafe |
| 115 | t_0115 | level 4 | What are all the driving distances between San Francisco, San Jose, Oakland, Berkeley, and Palo Alto optimizing for distance not speed, find restaurants near the closest pair, pick the best rated and route me there |
| 116 | t_0116 | level 4 | How do cycling times look between Vondelpark, Rijksmuseum, Anne Frank House, and Dam Square in Amsterdam, find bike rental shops nearby, which one is closest and bike me there |
| 117 | t_0117 | level 4 | What are all the driving times between Buckingham Palace, Tower of London, British Museum, and Hyde Park in London, find pubs nearby, pick the best rated and walk me there |
| 118 | t_0118 | level 4 | What are the trucking distances between zip codes 77001 in Houston, 78201 in San Antonio, 75201 in Dallas, 73301 in Austin, and 76102 in Fort Worth, find gas stations near the closest pair, check traffic around there and pick the closest gas station |
| 119 | t_0119 | level 4 | What are all the driving distances between Paris, Brussels, Amsterdam, and Frankfurt, find hotels near the closest pair, pick the best rated and route me there |
| 120 | t_0120 | level 4 | I'm walking around Manhattan — compare walking times between 350 Fifth Avenue, Times Square, Grand Central Terminal, and Bryant Park, find cafes nearby, which one is closest and check traffic around there |

### routing_level (40 prompts)

| #   | Prompt ID | Use Case | Prompt |
| --- | --------- | -------- | ------ |
| 121 | t_0121 | level 1 | How do I get from downtown Chicago to O'Hare Airport |
| 122 | t_0122 | level 1 | Give me walking directions from the Colosseum to the Vatican in Rome |
| 123 | t_0123 | level 1 | Find me a truck route from Dallas to Houston |
| 124 | t_0124 | level 1 | What's the best walking route from MIT to Harvard |
| 125 | t_0125 | level 1 | Can you plan the shortest drive from downtown Denver to Red Rocks Amphitheatre |
| 126 | t_0126 | level 1 | Give me a bike route from Central Park to the Brooklyn Bridge in New York |
| 127 | t_0127 | level 1 | Navigate me from 350 Fifth Avenue, New York to 1 MetLife Stadium Drive, East Rutherford, NJ |
| 128 | t_0128 | level 1 | Get me driving directions from 48.8584, 2.2945 to the Louvre Museum in Paris departing at 8 AM |
| 129 | t_0129 | level 1 | Plan a toll-free truck route from zip code 10001 to zip code 02101 |
| 130 | t_0130 | level 1 | How do I get by bus from King's Cross Station to Greenwich Observatory in London |
| 131 | t_0131 | level 2 | How do I get from downtown Chicago to O'Hare Airport, look for restaurants near the airport |
| 132 | t_0132 | level 2 | Give me walking directions from the Colosseum to the Vatican in Rome, see if there are any gelato shops nearby |
| 133 | t_0133 | level 2 | Find me a truck route from Dallas to Houston, tell me about traffic along the way |
| 134 | t_0134 | level 2 | What's the best walking route from MIT to Harvard, also find coffee shops near Harvard |
| 135 | t_0135 | level 2 | Can you plan the shortest drive from downtown Denver to Red Rocks Amphitheatre, check traffic on the way |
| 136 | t_0136 | level 2 | Give me a bike route from Central Park to the Brooklyn Bridge in New York, find bike shops near the Brooklyn Bridge |
| 137 | t_0137 | level 2 | Navigate me from 350 Fifth Avenue, New York to 1 MetLife Stadium Drive, East Rutherford, NJ, find parking near the destination |
| 138 | t_0138 | level 2 | Get me driving directions from 48.8584, 2.2945 to the Louvre Museum in Paris departing at 8 AM, find museums near the Louvre |
| 139 | t_0139 | level 2 | Plan a toll-free truck route from zip code 10001 to zip code 02101, check traffic along the route |
| 140 | t_0140 | level 2 | How do I get by bus from King's Cross Station to Greenwich Observatory in London, find cafes near Greenwich |
| 141 | t_0141 | level 3 | How do I get from downtown Chicago to O'Hare Airport, look for restaurants near the airport, figure out which has the best rating |
| 142 | t_0142 | level 3 | Give me walking directions from the Colosseum to the Vatican in Rome, see if there are any gelato shops nearby, also check traffic around there |
| 143 | t_0143 | level 3 | Find me a truck route from Dallas to Houston, tell me about traffic along the way, find gas stations near Houston |
| 144 | t_0144 | level 3 | What's the best walking route from MIT to Harvard, also find coffee shops near Harvard, let me know which is closest |
| 145 | t_0145 | level 3 | Can you plan the shortest drive from downtown Denver to Red Rocks Amphitheatre, check traffic on the way, find restaurants near Red Rocks |
| 146 | t_0146 | level 3 | Give me a bike route from Central Park to the Brooklyn Bridge in New York, find bike shops near the Brooklyn Bridge, which one is closest |
| 147 | t_0147 | level 3 | Navigate me from 350 Fifth Avenue, New York to 1 MetLife Stadium Drive, East Rutherford, NJ, find parking near the destination, also check traffic around East Rutherford |
| 148 | t_0148 | level 3 | Get me driving directions from 48.8584, 2.2945 to the Louvre Museum in Paris departing at 8 AM, find museums near the Louvre, which one has the highest rating |
| 149 | t_0149 | level 3 | Plan a toll-free truck route from zip code 10001 to zip code 02101, check traffic along the route, find rest stops near the destination |
| 150 | t_0150 | level 3 | How do I get by bus from King's Cross Station to Greenwich Observatory in London, find cafes near Greenwich, also check traffic around there |
| 151 | t_0151 | level 4 | How do I get from downtown Chicago to O'Hare Airport, look for restaurants near the airport, figure out which has the best rating and check traffic around it |
| 152 | t_0152 | level 4 | Give me walking directions from the Colosseum to the Vatican in Rome, see if there are any gelato shops nearby, also check traffic around there and tell me which is closest |
| 153 | t_0153 | level 4 | Find me a truck route from Dallas to Houston, tell me about traffic along the way, find gas stations near Houston and pick the closest one |
| 154 | t_0154 | level 4 | What's the best walking route from MIT to Harvard, also find coffee shops near Harvard, let me know which is closest and navigate me there |
| 155 | t_0155 | level 4 | Can you plan the shortest drive from downtown Denver to Red Rocks Amphitheatre, check traffic on the way, find restaurants near Red Rocks and take me to the best rated one |
| 156 | t_0156 | level 4 | Give me a bike route from Central Park to the Brooklyn Bridge in New York, find bike shops near the Brooklyn Bridge, which one is closest and bike me there |
| 157 | t_0157 | level 4 | Navigate me from 350 Fifth Avenue, New York to 1 MetLife Stadium Drive, East Rutherford, NJ, find parking near the destination, also check traffic around East Rutherford and get me directions to the closest parking lot |
| 158 | t_0158 | level 4 | Get me driving directions from 48.8584, 2.2945 to the Louvre Museum in Paris departing at 8 AM, find museums near the Louvre, which one has the highest rating and check traffic around it |
| 159 | t_0159 | level 4 | Plan a toll-free truck route from zip code 10001 to zip code 02101, check traffic along the route, find rest stops near the destination and pick the closest one |
| 160 | t_0160 | level 4 | How do I get by bus from King's Cross Station to Greenwich Observatory in London, find cafes near Greenwich, also check traffic around there and tell me which cafe is closest |

### tour_planning_level (40 prompts)

| #   | Prompt ID | Use Case | Prompt |
| --- | --------- | -------- | ------ |
| 161 | t_0161 | level 1 | Help me plan a walking tour of Prague starting and ending at Old Town Square — I want to visit the Dancing House, Prague Castle, Wenceslas Square, Charles Bridge, and Petrin Tower |
| 162 | t_0162 | level 1 | I'm driving around San Diego starting at the airport and finishing at Balboa Park — can you find the best order to visit Hotel del Coronado, La Jolla Cove, the Gaslamp Quarter, and Old Town San Diego? |
| 163 | t_0163 | level 1 | Plan the shortest truck delivery tour from Hartsfield-Jackson Airport with 15-minute stops at Target in Alpharetta, Costco in Brookhaven, Walmart Supercenter in Kennesaw, and Home Depot in Decatur — then back to the airport |
| 164 | t_0164 | level 1 | What's the best order to bike to Olympiapark, Viktualienmarkt, Nymphenburg Palace, and the English Garden if I'm starting and finishing at Marienplatz in Munich? |
| 165 | t_0165 | level 1 | I need to organize a bus tour of Boston starting and returning to South Station — schedule stops at Harvard Yard in Cambridge, the Museum of Fine Arts, Fenway Park, the New England Aquarium, MIT in Cambridge, and Faneuil Hall |
| 166 | t_0166 | level 1 | Help me plan a walking tour of Tokyo starting at Shibuya Crossing and ending at Tokyo Tower — I want to visit Meiji Jingu, Senso-ji Temple, and the Imperial Palace East Gardens |
| 167 | t_0167 | level 1 | What's the best scooter tour to visit the Lincoln Memorial, the Capitol Building, Georgetown Waterfront, the National Zoo, and the Washington Monument if I'm starting and returning to Union Station in DC? |
| 168 | t_0168 | level 1 | Can you organize a driving tour of Sydney starting and ending at Sydney Airport? I want to stop at Bondi Beach, the Sydney Opera House, Taronga Zoo, Manly Beach, Darling Harbour, the Royal Botanic Garden, and the Sydney Harbour Bridge |
| 169 | t_0169 | level 1 | I need to plan a tour using taxi from Gare du Nord to the Eiffel Tower as fast as possible, with stops at Sacre-Coeur, the Louvre Museum, Notre-Dame Cathedral, and the Arc de Triomphe |
| 170 | t_0170 | level 1 | Find the fastest truck delivery tour from the Port of Houston with 10-minute stops at Costco in Katy, Walmart Supercenter in Sugar Land, Target in Pearland, Home Depot in Humble, and Lowe's in Spring — then back to the port |
| 171 | t_0171 | level 2 | Help me plan a walking tour of Prague starting and ending at Old Town Square — I want to visit the Dancing House, Prague Castle, Wenceslas Square, Charles Bridge, and Petrin Tower, find restaurants near each stop |
| 172 | t_0172 | level 2 | I'm driving around San Diego starting at the airport and finishing at Balboa Park — can you find the best order to visit Hotel del Coronado, La Jolla Cove, the Gaslamp Quarter, and Old Town San Diego?, look for parking near each stop |
| 173 | t_0173 | level 2 | Plan the shortest truck delivery tour from Hartsfield-Jackson Airport with 15-minute stops at Target in Alpharetta, Costco in Brookhaven, Walmart Supercenter in Kennesaw, and Home Depot in Decatur — then back to the airport, see if there are gas stations near each store |
| 174 | t_0174 | level 2 | What's the best order to bike to Olympiapark, Viktualienmarkt, Nymphenburg Palace, and the English Garden if I'm starting and finishing at Marienplatz in Munich?, also find beer gardens near each landmark |
| 175 | t_0175 | level 2 | I need to organize a bus tour of Boston starting and returning to South Station — schedule stops at Harvard Yard in Cambridge, the Museum of Fine Arts, Fenway Park, the New England Aquarium, MIT in Cambridge, and Faneuil Hall, check if there are coffee shops near each stop |
| 176 | t_0176 | level 2 | Help me plan a walking tour of Tokyo starting at Shibuya Crossing and ending at Tokyo Tower — I want to visit Meiji Jingu, Senso-ji Temple, and the Imperial Palace East Gardens — also look for ramen restaurants near each stop |
| 177 | t_0177 | level 2 | What's the best scooter tour to visit the Lincoln Memorial, the Capitol Building, Georgetown Waterfront, the National Zoo, and the Washington Monument if I'm starting and returning to Union Station in DC?, search for food options near the National Mall |
| 178 | t_0178 | level 2 | Can you organize a driving tour of Sydney starting and ending at Sydney Airport? I want to stop at Bondi Beach, the Sydney Opera House, Taronga Zoo, Manly Beach, Darling Harbour, the Royal Botanic Garden, and the Sydney Harbour Bridge, see what cafes are near each landmark |
| 179 | t_0179 | level 2 | I need to plan a tour using taxi from Gare du Nord to the Eiffel Tower as fast as possible, with stops at Sacre-Coeur, the Louvre Museum, Notre-Dame Cathedral, and the Arc de Triomphe — find bakeries near each stop |
| 180 | t_0180 | level 2 | Find the fastest truck delivery tour from the Port of Houston with 10-minute stops at Costco in Katy, Walmart Supercenter in Sugar Land, Target in Pearland, Home Depot in Humble, and Lowe's in Spring — then back to the port, also find gas stations near each store |
| 181 | t_0181 | level 3 | Help me plan a walking tour of Prague starting and ending at Old Town Square — I want to visit the Dancing House, Prague Castle, Wenceslas Square, Charles Bridge, and Petrin Tower, find restaurants near each stop, check traffic around Old Town Prague |
| 182 | t_0182 | level 3 | I'm driving around San Diego starting at the airport and finishing at Balboa Park — can you find the best order to visit Hotel del Coronado, La Jolla Cove, the Gaslamp Quarter, and Old Town San Diego?, look for parking near each stop, also check traffic on I-5 |
| 183 | t_0183 | level 3 | Plan the shortest truck delivery tour from Hartsfield-Jackson Airport with 15-minute stops at Target in Alpharetta, Costco in Brookhaven, Walmart Supercenter in Kennesaw, and Home Depot in Decatur — then back to the airport, see if there are gas stations near each store, check traffic on I-285 |
| 184 | t_0184 | level 3 | What's the best order to bike to Olympiapark, Viktualienmarkt, Nymphenburg Palace, and the English Garden if I'm starting and finishing at Marienplatz in Munich?, also find beer gardens near each landmark, figure out traffic around Munich city center |
| 185 | t_0185 | level 3 | I need to organize a bus tour of Boston starting and returning to South Station — schedule stops at Harvard Yard in Cambridge, the Museum of Fine Arts, Fenway Park, the New England Aquarium, MIT in Cambridge, and Faneuil Hall, check if there are coffee shops near each stop, let me know about traffic around downtown Boston |
| 186 | t_0186 | level 3 | Help me plan a walking tour of Tokyo starting at Shibuya Crossing and ending at Tokyo Tower — I want to visit Meiji Jingu, Senso-ji Temple, and the Imperial Palace East Gardens — also look for ramen restaurants near each stop, check traffic around Shibuya |
| 187 | t_0187 | level 3 | What's the best scooter tour to visit the Lincoln Memorial, the Capitol Building, Georgetown Waterfront, the National Zoo, and the Washington Monument if I'm starting and returning to Union Station in DC?, search for food options near the National Mall — check traffic around Capitol Hill |
| 188 | t_0188 | level 3 | Can you organize a driving tour of Sydney starting and ending at Sydney Airport? I want to stop at Bondi Beach, the Sydney Opera House, Taronga Zoo, Manly Beach, Darling Harbour, the Royal Botanic Garden, and the Sydney Harbour Bridge, see what cafes are near each landmark, also check traffic on the Harbour Bridge |
| 189 | t_0189 | level 3 | I need to plan a tour using taxi from Gare du Nord to the Eiffel Tower as fast as possible, with stops at Sacre-Coeur, the Louvre Museum, Notre-Dame Cathedral, and the Arc de Triomphe — find bakeries near each stop, check traffic around the Champs-Elysees |
| 190 | t_0190 | level 3 | Find the fastest truck delivery tour from the Port of Houston with 10-minute stops at Costco in Katy, Walmart Supercenter in Sugar Land, Target in Pearland, Home Depot in Humble, and Lowe's in Spring — then back to the port, also find gas stations near each store, check traffic on I-610 |
| 191 | t_0191 | level 4 | Help me plan a walking tour of Prague starting and ending at Old Town Square — I want to visit the Dancing House, Prague Castle, Wenceslas Square, Charles Bridge, and Petrin Tower, find restaurants near each stop, check traffic around Old Town Prague and route me to the first stop |
| 192 | t_0192 | level 4 | I'm driving around San Diego starting at the airport and finishing at Balboa Park — can you find the best order to visit Hotel del Coronado, La Jolla Cove, the Gaslamp Quarter, and Old Town San Diego?, look for parking near each stop, also check traffic on I-5 and navigate me to the first stop |
| 193 | t_0193 | level 4 | Plan the shortest truck delivery tour from Hartsfield-Jackson Airport with 15-minute stops at Target in Alpharetta, Costco in Brookhaven, Walmart Supercenter in Kennesaw, and Home Depot in Decatur — then back to the airport, see if there are gas stations near each store, check traffic on I-285 and route me to the nearest gas station |
| 194 | t_0194 | level 4 | What's the best order to bike to Olympiapark, Viktualienmarkt, Nymphenburg Palace, and the English Garden if I'm starting and finishing at Marienplatz in Munich?, also find beer gardens near each landmark, figure out traffic around Munich city center and give me directions to the first stop |
| 195 | t_0195 | level 4 | I need to organize a bus tour of Boston starting and returning to South Station — schedule stops at Harvard Yard in Cambridge, the Museum of Fine Arts, Fenway Park, the New England Aquarium, MIT in Cambridge, and Faneuil Hall, check if there are coffee shops near each stop, let me know about traffic around downtown Boston and get me directions to the first stop |
| 196 | t_0196 | level 4 | Help me plan a walking tour of Tokyo starting at Shibuya Crossing and ending at Tokyo Tower — I want to visit Meiji Jingu, Senso-ji Temple, and the Imperial Palace East Gardens — also look for ramen restaurants near each stop, check traffic around Shibuya and navigate me to the nearest one |
| 197 | t_0197 | level 4 | What's the best scooter tour to visit the Lincoln Memorial, the Capitol Building, Georgetown Waterfront, the National Zoo, and the Washington Monument if I'm starting and returning to Union Station in DC?, search for food options near the National Mall — check traffic around Capitol Hill and take me to the first stop |
| 198 | t_0198 | level 4 | Can you organize a driving tour of Sydney starting and ending at Sydney Airport? I want to stop at Bondi Beach, the Sydney Opera House, Taronga Zoo, Manly Beach, Darling Harbour, the Royal Botanic Garden, and the Sydney Harbour Bridge, see what cafes are near each landmark, also check traffic on the Harbour Bridge and route me to the first stop |
| 199 | t_0199 | level 4 | I need to plan a tour using taxi from Gare du Nord to the Eiffel Tower as fast as possible, with stops at Sacre-Coeur, the Louvre Museum, Notre-Dame Cathedral, and the Arc de Triomphe — find bakeries near each stop, check traffic around the Champs-Elysees and give me directions to the first stop |
| 200 | t_0200 | level 4 | Find the fastest truck delivery tour from the Port of Houston with 10-minute stops at Costco in Katy, Walmart Supercenter in Sugar Land, Target in Pearland, Home Depot in Humble, and Lowe's in Spring — then back to the port, also find gas stations near each store, check traffic on I-610 and navigate me to the nearest gas station |

### traffic_level (40 prompts)

| #   | Prompt ID | Use Case | Prompt |
| --- | --------- | -------- | ------ |
| 201 | t_0201 | level 1 | How's traffic on I-405 through West LA right now |
| 202 | t_0202 | level 1 | What are the current traffic conditions around central London |
| 203 | t_0203 | level 1 | Show me traffic in downtown San Francisco |
| 204 | t_0204 | level 1 | What's the traffic on I-95 between Manhattan and Newark |
| 205 | t_0205 | level 1 | How's traffic on major highways around Houston |
| 206 | t_0206 | level 1 | Check traffic on the A10 ring road in Amsterdam |
| 207 | t_0207 | level 1 | Show me congested roads around downtown Chicago |
| 208 | t_0208 | level 1 | Which roads are flowing freely around downtown Dallas right now |
| 209 | t_0209 | level 1 | What's the highway traffic situation around central Paris |
| 210 | t_0210 | level 1 | How's traffic on all major roads around Midtown Manhattan |
| 211 | t_0211 | level 2 | How's traffic on I-405 through West LA right now, find gas stations along it |
| 212 | t_0212 | level 2 | What are the current traffic conditions around central London, find restaurants nearby |
| 213 | t_0213 | level 2 | Show me traffic in downtown San Francisco, find parking garages nearby |
| 214 | t_0214 | level 2 | What's the traffic on I-95 between Manhattan and Newark, find gas stations along the way |
| 215 | t_0215 | level 2 | How's traffic on major highways around Houston, find gas stations nearby |
| 216 | t_0216 | level 2 | Check traffic on the A10 ring road in Amsterdam, find bike rental shops nearby |
| 217 | t_0217 | level 2 | Show me congested roads around downtown Chicago, find cafes nearby |
| 218 | t_0218 | level 2 | Which roads are flowing freely around downtown Dallas right now, find restaurants nearby |
| 219 | t_0219 | level 2 | What's the highway traffic situation around central Paris, find hotels nearby |
| 220 | t_0220 | level 2 | How's traffic on all major roads around Midtown Manhattan, find cafes nearby |
| 221 | t_0221 | level 3 | How's traffic on I-405 through West LA right now, find gas stations along it, let me know which one is closest |
| 222 | t_0222 | level 3 | What are the current traffic conditions around central London, find restaurants nearby, which one has the best rating |
| 223 | t_0223 | level 3 | Show me traffic in downtown San Francisco, find parking garages nearby, which one is closest |
| 224 | t_0224 | level 3 | What's the traffic on I-95 between Manhattan and Newark, find gas stations along the way, tell me which has the shortest detour |
| 225 | t_0225 | level 3 | How's traffic on major highways around Houston, find gas stations nearby, pick the closest one |
| 226 | t_0226 | level 3 | Check traffic on the A10 ring road in Amsterdam, find bike rental shops nearby, which one is closest |
| 227 | t_0227 | level 3 | Show me congested roads around downtown Chicago, find cafes nearby, which one has the best rating |
| 228 | t_0228 | level 3 | Which roads are flowing freely around downtown Dallas right now, find restaurants nearby, pick the best rated |
| 229 | t_0229 | level 3 | What's the highway traffic situation around central Paris, find hotels nearby, which one has the best rating |
| 230 | t_0230 | level 3 | How's traffic on all major roads around Midtown Manhattan, find cafes nearby, which one is closest |
| 231 | t_0231 | level 4 | How's traffic on I-405 through West LA right now, find gas stations along it, let me know which one is closest and navigate me there |
| 232 | t_0232 | level 4 | What are the current traffic conditions around central London, find restaurants nearby, which one has the best rating and walk me there |
| 233 | t_0233 | level 4 | Show me traffic in downtown San Francisco, find parking garages nearby, which one is closest and drive me there |
| 234 | t_0234 | level 4 | What's the traffic on I-95 between Manhattan and Newark, find gas stations along the way, tell me which has the shortest detour and route me there |
| 235 | t_0235 | level 4 | How's traffic on major highways around Houston, find gas stations nearby, pick the closest one and navigate me there |
| 236 | t_0236 | level 4 | Check traffic on the A10 ring road in Amsterdam, find bike rental shops nearby, which one is closest and bike me there |
| 237 | t_0237 | level 4 | Show me congested roads around downtown Chicago, find cafes nearby, which one has the best rating and walk me there |
| 238 | t_0238 | level 4 | Which roads are flowing freely around downtown Dallas right now, find restaurants nearby, pick the best rated and drive me there |
| 239 | t_0239 | level 4 | What's the highway traffic situation around central Paris, find hotels nearby, which one has the best rating and route me there |
| 240 | t_0240 | level 4 | How's traffic on all major roads around Midtown Manhattan, find cafes nearby, which one is closest and check the walking route there |

