# Lab Report 4

## Step 1: Log into ieng6:

### Keys typed: `ssh cs15lsp23ji@ieng6.ucsd.edu` -> `<Enter>`
![image](https://github.com/Reckswell/cse-15L-lab-report-4/assets/73510375/2a041ace-2518-4de0-983a-341b9221cf0d)

### Keys typed: `<Shift> + <Insert>` (pasting password from clipboard):
Note: `<Ctrl> + V` doesn't work in my Bash terminal for some reason, so I used `<Shift> + <Insert>` instead, for every instance of pasting.
![image](https://github.com/Reckswell/cse-15L-lab-report-4/assets/73510375/90e3c38e-0edb-4d46-8913-05370d51006c)

## Step 2: Cloning fork of repository from personal Github Account

### Keys typed: `git clone` -> `space` -> `<Shift> + <Insert>` -> `<Enter>`
Note: repository was cloned prior to this lab report. Link can be found at [https://github.com/Reckswell/lab7]([url](https://github.com/Reckswell/lab7))
![image](https://github.com/Reckswell/cse-15L-lab-report-4/assets/73510375/bc4b5cb3-4d08-49d0-97b9-a98c554fb11c)

## Step 3: Running test to demonstrate they fail:

### Keys typed: `ls` -> `<Enter>` (to check files in main directory)
Note: extra files are present since lab report is submitted late
![image](https://github.com/Reckswell/cse-15L-lab-report-4/assets/73510375/5de3b9b5-ca63-4a71-9425-86bb99aaa22c)

### Keys typed: `cd lab7` -> `<Enter>` -> `ls` -> `<Enter>` (to change directory to and check files in lab7)
![image](https://github.com/Reckswell/cse-15L-lab-report-4/assets/73510375/4ee3d6d5-069e-426a-b675-5fa638081ac7)

### Keys typed: `bash test.sh` -> `<Enter>` (to run bash script)
![image](https://github.com/Reckswell/cse-15L-lab-report-4/assets/73510375/1e4a73d4-bb9f-4c3f-836e-578f9ff63dfe)

## Step 4: Editing code to fix the failing test:

### Keys typed: `vim ListExamples.java` + `enter` (to enter editor)
![image](https://github.com/Reckswell/cse-15L-lab-report-4/assets/73510375/3b896a1d-39d0-4ff6-910a-d6d2e82f447b)

### Keys typed: `/` -> `index1` -> `<Enter>` -> `<Shift> + N` (to find index1)
Note: `N` on it's own cycles chronologically forwards, while `<Shift> + N` cycles chronologically backwards. It's used here since the line of index1 we need to fix is towards the end of the program. Additionally, the line number is at the correct position corresponding to where the junit test failed.
![image](https://github.com/Reckswell/cse-15L-lab-report-4/assets/73510375/363aa9fc-d7b6-478e-bd9e-5ed9e9e95a0a)

### Keys typed: `E` -> `<Delete>` (to delete the 1 from index1)
Note: `E` skips to the end of the word `index`. `<Delete>` deletes the 1 in `index1` to make it just `index`.
![image](https://github.com/Reckswell/cse-15L-lab-report-4/assets/73510375/29dd9fcc-11b2-401a-91ab-ea9ec9d4259f)

### Keys typed: `I` -> `2` -> `<Esc>` (to insert a 2 after index)
Note: `I` changes vim to insert mode. `<Esc>` changes vim back to normal mode.
![image](https://github.com/Reckswell/cse-15L-lab-report-4/assets/73510375/02393829-71dc-405b-bdb6-f7ec5b9f9a5e)

### Keys typed: `:wq` -> `<Enter>` (exit and save changes in vim)
![image](https://github.com/Reckswell/cse-15L-lab-report-4/assets/73510375/c7c52ad1-3680-4278-870f-2a497051b604)

## Step 5: Running tests to demonstrate they succeed:

### Keys typed: `bash test.sh` -> `<Enter>` (to run bash script)
![image](https://github.com/Reckswell/cse-15L-lab-report-4/assets/73510375/0ea5e0ff-c019-420a-937a-6be9461ca53c)

## Step 6: Committing and pushing results to Github:

### Keys typed: `git add -all` -> `<Enter>` -> `git commit -m "Change index1 to index2 to fix Junit Test"` -> `<Enter>`
![image](https://github.com/Reckswell/cse-15L-lab-report-4/assets/73510375/20ae9ef5-1bd5-4ec4-be71-4271357e2ad3)

### Keys typed: `git push` -> `<Enter>`
Note: Username and Password were typed separately to push file.
