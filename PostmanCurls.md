curl --location 'https://www.your-app.com/chrome/screenshot?token=replace-with-a-strong-random-token&timeout=90000' \
--header 'Content-Type: application/json' \
--data '{
  "url": "https://freecodingcourses.xyz",
  "gotoOptions": {
    "waitUntil": "networkidle2",
    "timeout": 60000
  },
  "waitForTimeout": 5000,
  "scrollPage": true,
  "options": {
    "fullPage": true,
    "type": "png"
  }
}'




curl --location 'https://www.your-app.com/chrome/screenshot?token=replace-with-a-strong-random-token&timeout=90000' \
--header 'Content-Type: application/json' \
--data '{
  "url": "https://freecodingcourses.xyz",
  "viewport": {
    "width": 1920,
    "height": 1080,
    "deviceScaleFactor": 2,
    "isMobile": false
  },
  "gotoOptions": {
    "waitUntil": "networkidle2",
    "timeout": 60000
  },
  "waitForTimeout": 5000,
  "scrollPage": true,
  "options": {
    "fullPage": true,
    "type": "png"
  }
}'
