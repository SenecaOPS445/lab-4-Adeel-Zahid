[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-718a45dd9cf7e7f842a935f5ebbe5719a5e09af4491e668f4dbf3b35d5cca122.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15232863&assignment_repo_type=AssignmentRepo)
# Setup
This will download Lab 4 locally, allowing you to work on your scripts and upload (push) them back up to GitHub.

1. Clone your lab repository into your ~/ops445/lab4 directory using SSH:
```bash
git clone <ssh link> ~/ops445/lab4/
```
2. Copy your backed-up work into your new GitHub-linked directory:
```bash
cp ~/old_ops445/lab4/* ~/ops445/lab4/
```

# Submission
1. Run the checking script. Make sure you identify and correct any and all errors in your scripts:
```bash
cd ~/ops445/lab4/
pwd #confirm that you are in the right directory
python3 ./CheckLab4.py -f -v
```
2. Redirect the checking script output into *laboutput.txt*:
```bash
python3 ./CheckLab4.py -v &>  ~/ops445/lab4/laboutput.txt
```
Your repo should have the following additional files:
- [ ] lab4a.py
- [ ] lab4b.py
- [ ] lab4c.py
- [ ] lab4d.py
- [ ] lab4e.py
- [ ] laboutput.txt

3. Commit and push (upload) your lab work:
```bash
git add lab*
git commit -m "Individual message or note."
git push
```

You can make changes to your scripts and reupload as many times as you like. Make sure you commit+push to do so.

**Note:** Your lab is automatically submitted at the due date and time using the last published code. Any changes you publish after the due date won't be marked or seen by your professor.
