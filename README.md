# Richard Sesay: Academic Portfolio Website

A simple personal website with three files and no frameworks or build tools.

- `index.html` holds the text of the website.
- `styles.css` holds the design (colours, fonts, layout).
- `README.md` is this guide.

Live site: https://richies77.github.io

## 1. Edit the website
1. Open the repository on github.com and click `index.html`.
2. Click the **pencil icon** at the top right.
3. Press **Ctrl + F** (or **Cmd + F** on Mac) and search for `EDIT:`. Each marker tells you in plain English what you can change.
4. Change only the words between tags. Tags are the pieces inside `<` and `>`, such as `<p>` and `</p>`. Do not delete the `<` and `>` signs or the quote marks.
5. Click **Commit changes**, then **Commit changes** again.
6. Wait a minute and refresh the website. If you do not see the change, press **Ctrl + Shift + R**.
7. Update the "Last updated" date in the footer each time.

To change colours or fonts, edit `styles.css` in the same way.

## 2. The CV download button
The CV file lives in the main folder of the repository, next to `index.html`. The button in `index.html` must use the file's exact name, including capital letters.

At the moment the file is called `Richard_Sesay_CV-1.pdf`, and the button points to that name.

To replace your CV:
1. Rename the new file on your computer **before uploading** so it does not end in `(1)` or `-1` unless you want it to. Browsers add those endings when a file with the same name already exists.
2. In the repository, click **Add file**, then **Upload files**, drag the PDF in and click **Commit changes**.
3. If the new file has a different name from the current one, open `index.html`, find the CV button, and change the name after `href=` to match exactly. Commit the change.
4. Test the file directly at `https://richies77.github.io/` followed by the file name.

Your documents are public, so check that they contain nothing you do not want strangers to see.

## 3. Add the science communication files
1. Upload `ERL_Research_Dossier.docx` and `ERL_Video_Script_v2.pdf` to the main folder in the same way.
2. In `index.html`, find each download link that sits inside a comment and delete the comment marks around it, as the EDIT note explains.

## 4. Add a new card (project, job or degree)
1. Open `index.html` in edit mode (pencil icon).
2. Find an existing card. It starts with `<div class="card">` and ends with `</div>`.
3. Select the whole block, copy it, and paste it directly below the original.
4. Change the title and text in the copy. Commit your changes.

## 5. Restore an older version
1. Open the file in the repository and click **History**.
2. Click the date of the version you want.
3. Click the **three dots** next to the file name, then **View file**, then **Raw**.
4. Select everything (Ctrl + A) and copy it. Go back to the file, click the pencil icon, select all, paste, and commit.

GitHub keeps every version, so you cannot lose your work.

## 6. If something does not work
- The site shows an error: go to **Settings**, then **Pages**. Under **Build and deployment**, set **Source** to **Deploy from a branch**, choose **main** and **/ (root)**, and click **Save**.
- A download link shows a 404: the name in `index.html` does not match the file's name in the repository. Check capital letters, underscores and endings such as `(1)` or `-1`.
- A change does not appear: wait two minutes and press **Ctrl + Shift + R**.

## 7. Optional: a custom domain
Students can often get a free domain through the GitHub Student Developer Pack, for example a free `.me` domain from Namecheap or a `.TECH` domain. Offers change, so check https://education.github.com/pack.

1. Apply for the Student Developer Pack and claim the Namecheap or .TECH offer.
2. In your domain provider's DNS settings, add four **A records** for the main domain (`@`) with the values `185.199.108.153`, `185.199.109.153`, `185.199.110.153` and `185.199.111.153`.
3. Add a **CNAME record** with the host `www` that points to `richies77.github.io`.
4. In the repository go to **Settings**, then **Pages**, type your domain under **Custom domain** and click **Save**.
5. When it becomes available (it can take up to 24 hours), tick **Enforce HTTPS**.
