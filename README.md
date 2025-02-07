# spotify-dbt-duckdb
In this project, I optimized **40GB of Spotify Playlist data stored in JSON format** and efficiently processed it into **6GB parquet file** using DuckDB and JQ.

This process significantly reduced storage size while maintaining the usability of the data for analysis and transformation later in **dbt.**

**Dataset Source:**

- **Resource:** [Spotify Million Playlist Dataset Challenge](https://www.aicrowd.com/challenges/spotify-million-playlist-dataset-challenge)
- **Format:** JSON files (unstructured data)

**Challenge:** Handle efficiently storing and querying large JSON datasets without traditional database infrastructure
