# ShappyAI site

GitHub Pages source for ShappyAI public pages.

- Site: https://shappyai.github.io/site/
- Terms: https://shappyai.github.io/site/terms
- Privacy Policy: https://shappyai.github.io/site/privacy
- app-ads.txt: https://shappyai.github.io/site/app-ads.txt

Before release, replace the placeholder publisher ID in `app-ads.txt` with the AdMob publisher ID.

From the Android repository root, run:

```powershell
powershell -ExecutionPolicy Bypass -File .\tools\update-app-ads.ps1 -PublisherId "<AdMob publisher ID>"
powershell -ExecutionPolicy Bypass -File .\tools\validate-public-site.ps1 -RequireLocalSite -RequireProductionAppAds
```
