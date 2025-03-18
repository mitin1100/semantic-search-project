# semantic-search-project

### 1. Make data
#### 1.1. How to get google developer api key
 - Go to https://console.cloud.google.com/
 - At Quick access: Select APIs & Services -> Credentials -> CREATE CREDENTIALS -> API Key
 - At API Keys: Select SHOW KEY

python transcript_download.py

#### 1.2. I use ollama for free so if you want to use another, you can skip this 
 - Down ollama app, run it and download models you want to use (mxbai-embed-large, llama3)

#### 1.3. Run these file:
- python transcript_enrich_speaker.py

- python transcript_enrich_bucket.py

- python transcript_enrich_summaries.py

- python transcript_enrich_embedding.py

- python transcript_enrich_lite.py 

#### 1.4. Put data into mongodb atla
How to get mongo uri:
 + Go to https://account.mongodb.com/

 + Go to Cluster -> Connect -> Connect to your application -> Drivers -> Copy connection string

Run  **python convert_json_to_mongo.py**

### 2. Test on local

▶️ [[Video demo]](https://youtu.be/KMbVC_cVaUY)

_updating . . ._

### 3. Dockerize app and ollama

_updating . . ._