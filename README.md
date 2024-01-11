# **How Much of the World Has Access to the Internet?**
A DataCamp competition

**Background**

You work for a policy consulting firm. One of the firm's principals is preparing to give a presentation on the state of internet access in the world. She needs your help answering some questions about internet accessibility across the world.

**The data**

The research team compiled the following tables:
- **internet**
    - **Entity:** The name of the country, region, or group.
    - **Code:** Unique id for the country (null for other entities).
    - **Year:** Year from 1990 to 2019.
    - **Internet_usage:** The share of the entity's population who have used the Internet in the last three months.
- **people:**
    - **Entity:** The name of the country, region, or group.
    - **Code:** Unique id for the country (null for other entities).
    - **Year:** Year from 1990 to 2020.
    - **Users:** The number of people who have used the internet in the last three months for that country, region, or group.
- **broadband:**
    - **Entity:** The name of the country, region, or group.
    - **Code:** Unique id for the country (null for other entities).
    - **Year:** Year from 1998 to 2020.
    - **Broadband_Subscriptions:** The number of fixed subscriptions to high-speed internet at downstream speeds >= 256 kbit/s for that country, region, or group.
    
**Challenge**

Create a report to answer the principal's questions. Include:
- What are the top 5 countries with the highest internet use (by population share)?
- How many people had internet access in those countries in 2019?
- What are the top 5 countries with the highest internet use for each of the following regions: "Africa Eastern and Southern", "Africa Western and Central", "Latin America & Caribbean", "East Asia & Pacific", "South Asia", "North America", "European Union"?
- Create a visualization for those five regions' internet usage over time.
- What are the 5 countries with the most internet users?
- What is the correlation between internet usage (population share) and broadband subscriptions for 2019?
- Summarize your findings.
