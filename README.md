# Vonaland Flutter Baslangic

Bu repo tablet uyumlu bir Flutter baslangic uygulamasi icerir.

## Hazirlananlar
- `lib/main.dart`: tablet (`>=600px`) ve telefon icin uyarlanmis acilis ekrani
- `pubspec.yaml`: Dart 3 uyumlu SDK araligi
- `.gitignore`: Flutter ve IDE dosyalari

## GitHub Repo'na Gonderme
Kendi GitHub repo URL'ni kullan:

```bash
cd /Users/emrahaslan/vonaland
git add .
git commit -m "Initial Flutter tablet-ready app"
git remote add origin <GITHUB_REPO_URL>
git push -u origin main
```

Eger remote zaten varsa:

```bash
git remote set-url origin <GITHUB_REPO_URL>
git push -u origin main
```

## Calistirma
Bu makinede `flutter` komutu kurulu olmadigi icin uygulamayi burada calistiramadim. Flutter kurulduktan sonra:

```bash
cd /Users/emrahaslan/vonaland
flutter create .
flutter pub get
flutter run
```

Tablet emulator/cihazda:

```bash
flutter devices
flutter run -d <deviceId>
```
