# Hackolingo
![Static Badge](https://img.shields.io/badge/REPO-grey?style=for-the-badge)
![GitHub last commit](https://img.shields.io/github/last-commit/Eli-Zac/Hackolingo?style=for-the-badge)
![GitHub Repo stars](https://img.shields.io/github/stars/Eli-Zac/Hackolingo?style=for-the-badge&link=https%3A%2F%2Fgithub.com%2FEli-Zac%2FHackolingo)
![GitHub watchers](https://img.shields.io/github/watchers/Eli-Zac/Hackolingo?style=for-the-badge)
![GitHub forks](https://img.shields.io/github/forks/Eli-Zac/Hackolingo?style=for-the-badge)
<br>
![Static Badge](https://img.shields.io/badge/USER-grey?style=for-the-badge)
![GitHub followers](https://img.shields.io/github/followers/Eli-Zac?style=for-the-badge)
![Discord](https://img.shields.io/discord/1067349282660814929?style=for-the-badge&label=Discord&link=https%3A%2F%2Fdiscord.spectracraft.com.au)
![Website](https://img.shields.io/website?url=https%3A%2F%2Fspectracraft.com.au%2F&style=for-the-badge&label=WEBSITE&link=https%3A%2F%2Fspectracraft.com.au%2F)
<br>
[View My Profile](https://github.com/Eli-Zac)

Auto XP Farmer for Duolingo.

### Preperation (required)
1. Duolingo Auth Token
    - To get this information run the following code in your web browser console:
```
    document.cookie
        .split(';')
        .map(cookie => cookie.trim())
        .find(cookie => cookie.includes('jwt_token'))
        ?.split('=')[1];
```
2. Duolingo User ID
    - To get this information run the following code in your web browser console:
```
    document.cookie
        .split(';')
        .map(cookie => cookie.trim())
        .find(cookie => cookie.includes('logged_out_uuid'))
        ?.split('=')[1];
```
3. After obtaining these values, store each of them as repository secrets. 
    - Go to repository Settings > Secrets and variables > Actions
    - Click "New repository secret"
    - Once in the page, fill out the name for the secret.
        - If entering your token, name should be: TOKEN
        - If entering your user ID, name should be: USER_ID
    - Click add secret
    - Repeat for both token and user ID.


This upgraded and Optimized Hack have
- Streak Keeper (Auto do 1 lesson every day to save your streak)
- 10K XP Daily ( Auto do 50 lessons every day, can change your own lesson you want in the code

### How to use:
1. At the top of the page, navigate to the Actions button. 
2. If prompted, click the button to enable workflows.
3. On the left of the page, click the hack you want to run. 
4. On the right of the page click the Run Workflow button. 
5. Fill out all information requested by the hack, and click Run Workflow.
6. The hack will start the attack, and you can refresh your Duolingo website to see it's affect after it has been completed.

### FAQ:
- Will the XP hack affect my Duolingo learning path (complete lessons?)
    - No, it will not. This hack creates fake "practice" lessons so it won't affect your learning path.
- Is this hack detectable (will I get banned)?
    - No, it is not. I tested all hacks overnight before I release them. I got 1,000,000 XP on Duolingo account in one night with XP hack, and it's been weeks with no ban.
