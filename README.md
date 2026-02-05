## 使用
1. .env 內密碼完善
2. 部署 render
    1. 在 Render 中，點擊 "New" > "Web Service"
    2. env 設置
        1. LINE_TOKEN=your_line_channel_access_token
        2. LINE_SECRET=your_line_channel_secret
        3. GOOGLE_PLACES_API_KEY=your_google_places_apikey
        4. CLOUDINARY_CLOUD_NAME=your_cloud_name
        5. CLOUDINARY_API_KEY=your_api_key
        6. CLOUDINARY_API_SECRET=your_api_secret
        7. GEMINI_API_KEY=your_gemini_apikey
    2. 設定 
        1. Start Command：python app.py
        2. Build Command：pip install -r requirements.txt
