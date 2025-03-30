# mcp_server
implementing a sample mcp_server using dolphin_mcp client


# mcp_config.json 

this file contains config for mcp_server . we have a mcp server file server.py which has 2 utilities available 
get_alerts and get_forecast in tools.py file.

# running dolphin client 

# take checkout of dolphin-mcp from github
` pip3 install -e requirements.txt 

# run client command 
` dolphin-mcp-cli --model gpt-4o-mini " show me weather alerts from NY city"

# output 


Here is the weather forecast for Chicago:

### Overnight
- **Temperature:** 40°F
- **Wind:** 10 mph SSE
- **Forecast:** Areas of fog and a slight chance of rain showers. Cloudy with temperatures rising to around 51 overnight. Chance of precipitation is 20%. New rainfall amounts less than a tenth of an inch possible.

---

### Sunday
- **Temperature:** 66°F
- **Wind:** 15 to 20 mph SSW
- **Forecast:** Areas of fog and a slight chance of rain showers before 7am, followed by likely showers and thunderstorms. Cloudy, with temperatures falling to around 62 in the afternoon. Chance of precipitation is 70%. New rainfall amounts between a quarter and half of an inch possible.

---

### Sunday Night
- **Temperature:** 35°F
- **Wind:** 15 to 20 mph WNW
- **Forecast:** Chance of showers and thunderstorms. Cloudy, with temperatures rising to around 37 overnight. Chance of precipitation is 30%. New rainfall amounts between a quarter and half of an inch possible.

---

### Monday
- **Temperature:** 39°F
- **Wind:** 15 mph N
- **Forecast:** Chance of snow showers before 7am. Mostly cloudy, with a high near 39. Chance of precipitation is 30%.

---

### Monday Night
- **Temperature:** 33°F
- **Wind:** 10 to 15 mph NE
- **Forecast:** Partly cloudy, with a low around 33.

Feel free to ask for more details or updates!
