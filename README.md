# HDB-resale-transactions
Explore hotspots and the resiliency of HDB prices using this kepler.gl visualisation of HDB resale transactions.

Visualisation provides a high level understanding of price changes, and guides analysts in narrowing down their research for deeper analyses into price trends across towns and flat sizes.

Feel free to download the html file to explore, or visit this visualisation [here](https://kepler.gl/demo/map?mapUrl=https://dl.dropboxusercontent.com/scl/fi/llh1jqa4jegoltxqyysa5/keplergl_9msmwt6.json?rlkey=kkcqlrg96sywpl1z9dx9gwjmg&dl=0).

I personally prefer to set the time playback to _incremental time window_ to show changes over time. At a glance, interesting observations can be made such as the effectiveness of 2018 cooling measures.

![Screenshot 2022-01-22 at 3 02 20 PM](https://user-images.githubusercontent.com/65649754/150628624-2a2e28f4-77da-43c0-853b-7dfb1fa05fc6.png)

Resale HDB Transactions from data.gov.sg

---

Additional notes:
Addresses were reverse geocoded using OneMap and Google Maps since data.gov.sg does not provide postal codes. 
CSV was too large to commit via Github UI (max size of 22mb) - used VS Code to commit csv file.
Might explore Streamlit to deploy this repo and geocoder repo next time so I can deploy codes directly.
<img width="1070" alt="Screenshot 2024-04-11 at 11 28 32 PM" src="https://github.com/gilbertmak/HDB-resale-transactions/assets/65649754/e3ae9c61-fef5-4017-a02f-95471fe3c40d">
