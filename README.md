# Gastro Kitabı

## Yayınlama (tek seferlik, ~10 dk)
1. github.com → New repository: `gastro-kitabi` (Public, boş).
2. Bu klasörün içeriğini yükle ("uploading an existing file" → sürükle-bırak; `.github` klasörü dahil) → Commit.
3. Actions sekmesi → "Deploy" yeşil olana kadar bekle (1–2 dk). Bu, `gh-pages` dalını oluşturur.
4. Settings → Pages → Source: Deploy from a branch → Branch: `gh-pages` / `/ (root)` → Save.
5. Adres: `https://KULLANICI.github.io/gastro-kitabi/` — telefonda aç → tarayıcı menüsü → Ana ekrana ekle.

## Yeni sayfa
`docs/` altına `.md` koy, `mkdocs.yml` içindeki `nav`'a satır ekle, push = otomatik yayın (GitHub'ın web editöründen telefonla da düzenlenebilir).

## Lokal önizleme
`pip install mkdocs-material` → `mkdocs serve` → http://127.0.0.1:8000
