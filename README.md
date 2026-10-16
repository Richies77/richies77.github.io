# Richard Sesay: Academic Portfolio Website

A simple personal website. It has three files, no frameworks and no build tools.

- `index.html` holds the text of the website.
- `styles.css` holds the design (colours, fonts, layout).
- `README.md` is this guide.

Replace `USERNAME` below with your own GitHub username, in lower case.

## 1. Create your GitHub account
1. Go to https://github.com and click **Sign up**.
2. Choose your username carefully. It becomes part of your web address, for example `richardsesay` gives `https://richardsesay.github.io`.
3. Confirm your email address when GitHub sends you a message.

## 2. Create the repository
1. Click the **+** icon at the top right, then **New repository**.
2. In **Repository name**, type exactly `USERNAME.github.io`. It must match your username exactly.
3. Choose **Public**. The free version of GitHub Pages needs a public repository.
4. Tick **Add a README file** and click **Create repository**.

## 3. Upload your files
1. Open the repository and click **Add file**, then **Upload files**.
2. Drag in `index.html` and `styles.css`. Both are needed, otherwise the page loses its design.
3. Drag in your `files` folder if you have documents ready.
4. If GitHub asks about replacing `README.md`, you can upload this one over it.
5. Scroll down and click **Commit changes**.

## 4. See your website
1. Wait one to three minutes.
2. Open `https://USERNAME.github.io` in your browser.
3. If you see an error, go to **Settings**, then **Pages**. Under **Build and deployment**, set **Source** to **Deploy from a branch**, choose **main** and **/ (root)**, and click **Save**. Wait a few minutes and try again.

## 5. Edit your website later
1. Open your repository and click `index.html`.
2. Click the **pencil icon** at the top right.
3. Press **Ctrl + F** (or **Cmd + F** on Mac) and search for `EDIT:`. Each marker tells you in plain English what you can change.
4. Change only the words between tags. Tags are the pieces inside `<` and `>`, such as `<p>` and `</p>`. Do not delete the `<` and `>` signs or the quote marks.
5. Click **Commit changes**, then **Commit changes** again.
6. Wait a minute and refresh your website. If you do not see the change, press **Ctrl + Shift + R**.
7. Update the "Last updated" date in the footer each time.

To change colours or fonts, edit `styles.css` the same way and search for `EDIT:`.

## 6. Upload your CV so the button works
1. Name your CV file exactly `Richard_Sesay_CV.pdf`.
2. In your repository, click **Add file**, then **Upload files**.
3. Put the file inside a folder called `files`, so the final path is `files/Richard_Sesay_CV.pdf`. If the `files` folder already exists, open it first and upload the PDF inside it.
4. Click **Commit changes**.
5. To replace your CV later, upload a new file with the exact same name. GitHub overwrites the old one and the button keeps working.
6. For the two science communication files, upload `files/ERL_Research_Dossier.docx` and `files/ERL_Video_Script_v2.pdf`. Then in `index.html` find each download link that sits inside a comment and delete the comment marks around it, as the EDIT note explains.

Your documents will be public, so check that they contain nothing you do not want strangers to see.

## 7. Add a new project card
1. Open `index.html` in edit mode (pencil icon).
2. Find an existing card. It starts with `<div class="card">` and ends with `</div>`.
3. Select the whole block, copy it, and paste it directly below the original.
4. Change the title and text in the copy. Commit your changes.

## 8. Restore an older version
1. Open the file in your repository and click **History**.
2. Click the date of the version you want.
3. Click the **three dots** next to the file name, then **View file**, then **Raw**.
4. Select everything (Ctrl + A) and copy it. Go back to the file, click the pencil icon, select all, paste, and commit.

GitHub keeps every version, so you cannot lose your work.

## 9. Optional: a custom domain such as richard.me
Students can often get a free domain through the GitHub Student Developer Pack, for example a free `.me` domain from Namecheap or a `.TECH` domain. Offers change, so check https://education.github.com/pack.

1. Apply for the Student Developer Pack and claim the Namecheap or .TECH offer.
2. In your domain provider's DNS settings, add four **A records** for the main domain (`@`) with the values `185.199.108.153`, `185.199.109.153`, `185.199.110.153` and `185.199.111.153`.
3. Add a **CNAME record** with the host `www` that points to `USERNAME.github.io`.
4. In your repository go to **Settings**, then **Pages**, type your domain under **Custom domain** and click **Save**.
5. When it becomes available (it can take up to 24 hours), tick **Enforce HTTPS**.

If something goes wrong, first check the spelling of your repository name. It is the most common problem.
