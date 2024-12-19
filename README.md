# Agribay-main
Crop management Dashboard

# Starting Next app

```bash
cd next-app/

npm install

follow the format of .env.example and create your own .env

npx prisma generate

npx prisma migrate dev

npm run dev
```
visit http://localhost:3000 on your browser to view the application

To run the various services 

Service 1
```
cd services/Plant-Disease-Detection
pip install -r requirements.txt
streamlit run app.py 
```

Service 2 
```
cd services/llama2-master
pip install -r requirements.txt
streamlit run app.py
```

Service 3 
```
cd services/services/sensor-notif-app-main

Start the index.html as a live server on VSCode on port:5500
```

