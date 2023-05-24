# How to start:

## Step 1. start the container, you can build from the code as well

```
docker pull pengzhile/pandora
docker run  -e PANDORA_CLOUD=cloud -e PANDORA_SERVER=0.0.0.0:8899 -p 8899:8899 -d pengzhile/pandora
```

## Step 2. Get your access token:

login into ChatGPT on your browser

Then http://chat.openai.com/api/auth/session

Find the access token.

# Step 3 start your project

go to http://localhost:8899

fill your access token there, enjoy!
