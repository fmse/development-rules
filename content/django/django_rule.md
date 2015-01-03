django-development-rules
========================

Beberapa hal yang harus diperhatikan adalam django-development :

1. Apps
    - Apps dalam django sebaiknya minimalis dan ramping
    - Setiap apps terdiri dari model, view, form dll nya sendiri
    - Sebelum membuat apps baru untuk pengolahan sebuah data, tolong perhatikan ERD anda jika harus membuat apps baru silakan, jika tidak masukan saja ke dalam apps yang berkaitan dan sudah ada saat ini
  
2. URLs
    - "A clean, elegant URL scheme is an important detail in a high-quality Web application" - buku django
    - Silakan gunakan pattern yang ada saat ini, jika memiliki ide untuk mengubah pattern harap kasih tau tim yang lainnya

3. Templates
     - Templating dalam django konsepnya sama dengan framework lainnya namun implementasinya sedikit berbeda. Templating dilakukan di file html yang anda buat, jadi memerlukan sedikit usaha lebih dibandingkan dengan framework php. Untuk lebih jelasnya silakan perhatikan kode yang sudah ada
