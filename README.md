# denemee

Vercel için Node.js + PHP başlangıç projesi. Ek paket veya build adımı yok.

Vercel'e repoyu import et ve Deploy'a bas. Framework: Other; ayarlar `vercel.json` içinde hazır.

- `public/index.html`: dört butonlu basit deneme sayfası.
- `/api/hello`: Node.js endpoint.
- `/api/hello.php`: PHP endpoint.

Yerelde çalıştırmak için: `npx vercel dev` (PHP endpoint için yerel PHP kurulumu gerekir).

PHP, topluluk tarafından geliştirilen [vercel-php](https://github.com/vercel-community/php) runtime'ını kullanır.
