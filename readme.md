1. download ngrok
2. run ngrok.exe -> ngrok http 5000 -> copy your server link ending with ".ngrok-free.app"
3. go to github developer settings -> generate new token -> give required permissions
4. copy token and paste it in Deployed.ipynb
5. open repository -> go to repository settings -> webhook -> create one with required permissions
6. the copied server from step 2, paste it in webhook payload url ending with "/api/issue"
7. run deployed.ipynb -> check whether script is working as intended
