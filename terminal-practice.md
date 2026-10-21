# Terminal Navigation Practice

1. Current path: `C:\Users\zainul abadin\Desktop\webdev-day01-setup-practice`
2. `dir` showed: `css`, `images`, `js`, `screenshots`, `index.html`, `README.md`, `network-inspection.md`
3. Created `terminal-practice` with: `mkdir terminal-practice`
4. Entered it with: `cd terminal-practice`
5. Created a subfolder with: `mkdir notes` (confirmed with `dir`, which showed `notes`)
6. Created a file with: `type nul > notes\commands.txt` (confirmed with `dir notes`, which showed `commands.txt`)
7. Moved up one folder with: `cd ..`
8. `tree /f` showed the project folder with `index.html`, `README.md`, `network-inspection.md`, the folders `css`, `images`, `js` and `screenshots` (with my four PNG files), and `terminal-practice\notes\commands.txt`.
9. Returned to the project folder with: `cd /d "C:\Users\zainul abadin\Desktop\webdev-day01-setup-practice"`
10. Removed the practice folder with: `rmdir /s /q terminal-practice`

## Tree output

```
C:.
│   index.html
│   network-inspection.md
│   README.md
│
├───css
│       style.css
│
├───images
├───js
│       script.js
│
├───screenshots
│       live-server-page.png
│       network-panel.png
│       node-version.png
│       vscode-project.png
│
└───terminal-practice
    └───notes
            commands.txt
```