# Emoji roll bot
Bot that telling a future generating 4 random Emoji 

# Run
`
docker run --name emoji --restart unless-stopped -v $(pwd)/logs:/var/www/logs -v $(pwd)/.env:/var/www/.env -d vetermanve/emoji_roll
`
