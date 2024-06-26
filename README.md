# Membangun API dengan Django dan Nextjs

Ini adalah contoh sederhana tentang cara membangun API dengan Django, dan React.

## Memulai dengan Django dan React

Pertama, jalankan server API.

```bash
cd django-api-nextjs
python3.11 -m venv venv
pip install -r requirements.txt

python manage.py migrate
python manage.py runserver
```

Server API akan tersedia di http://localhost:8000/.

Kemudian jalankan klien React.

```bash
cd menu-frontend
npm install
npm run dev
```

Klien React akan tersedia di http://localhost:3000/.

Feel free to open issues on the [GitHub repository](https://github.com/z0zero/django-api-nextjs) if you have any questions.
