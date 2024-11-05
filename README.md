# **SPOTIFY X NASA**

This project combines music and space data to offer a unique experience: each month, discover the fastest-tempo songs on Spotify and the most intense coronal mass ejections (CMEs) from NASA. A CME is a powerful burst of solar plasma that can disrupt Earth's radio and magnetic fields. With this code, you’ll find a novel way to connect the solar system’s high-energy events with high-tempo tracks, letting you explore the speed of the cosmos through sound.

### **Requirements**

- **Spotify API Key** – [Get yours here](https://developer.spotify.com/documentation/web-api)
- **NASA API Key** – [Get yours here](https://api.nasa.gov/)

### **How It Works**

1. **Set Your Dates**:
   - Define the month and year you'd like to search for CMEs by updating `start_date_cme` and `end_date_cme` in cell 3.
   - Run `nasa_cme` in cell 7 to display the list of coronal mass ejections for your selected timeframe.
2. **Search for Fast-Tempo Songs**:
   - Use the same dates to find Spotify songs for that month, filtering by the highest BPM within a specific genre.
   - Set your preferred year, month, and genre on Spotify to ensure it aligns with the CME search month.
3. **Organize Data**:
   - Retrieve track IDs for your specified month and genre, then list them in descending order based on BPM, similar to how CME speeds are sorted.
4. **Create Your Playlist**:
   - Name your playlist according to the month and year, featuring the top 30 high-tempo songs. In the playlist description, list the top 30 CME speeds from NASA for the same period in order from fastest to slowest.



