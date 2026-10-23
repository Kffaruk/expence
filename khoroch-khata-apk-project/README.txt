APK BANANOR NIYOM (free, Android Studio lagbe na)
1. github.com e free account kholo > New repository (nam: khoroch-khata, Public) > Create.
2. "uploading an existing file" e click kore ei folder-er SOB file/folder (www, icons, package.json,
   capacitor.config.json, .github) drag-drop koro > Commit changes.
   (.github folder upload na hole: Add file > Create new file > nam e likho  .github/workflows/build-apk.yml
    ar ei folder-er build-apk.yml-er content paste koro > Commit.)
3. Repository-r "Actions" tab e jao > "Build APK" > Run workflow (5-8 minute lage).
4. Sesh hole run-e click koro > nicher "Artifacts" theke khoroch-khata-apk download koro (zip, bhitore app-debug.apk).
5. APK phone e pathao > open koro > "Install unknown apps" allow koro > Install.

SUPABASE PAUSE ATKANO (optional):
Repository > Settings > Secrets and variables > Actions > New repository secret:
  SUPABASE_URL = https://xxxx.supabase.co     SUPABASE_KEY = anon public key
Tarpor Actions > Supabase Keepalive > Run workflow (ekbar test). Er por protí 3 din por por nije ping korbe.
