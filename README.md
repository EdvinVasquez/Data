# Data
DATABASE_URL=tu_url_postgres CLOUD_NAME=tu_cloud_name API_KEY=tu_api_key API_SECRET=tu_api_secret


UPDATE productos
SET imagen = stock,
    stock = 10
WHERE stock LIKE '%.jpg';
