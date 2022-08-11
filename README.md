- 👋 Hi, I’m @mwhodgson
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...

<!---
mwhodgson/mwhodgson is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->

This is what I did if you want to try again some day



1. Download and install Git: https://gitforwindows.org/
2. Open Git Bash
3. Enter this command:

ssh-keygen -t ed25519 -C "your_email@example.com"

4. Press Enter when prompted to save key
5. Enter a passphrase when prompted. You'll be asked to reconfirm it.
6. Start the SSH Agent with this command:

eval "$(ssh-agent -s)"

7. You should see a message with an Agent pid #
8. Add your ssh key with this command:

ssh-add ~/.ssh/id_ed25519

9. Login to your Github account on the Github website
10. Go into your account Settings, then the SSH and GPG Keys menu
11. Click New SSH Key
12. Enter a Title, such as 'My Work PC'
13. Enter your SSH Key. To retrieve your key, type this command into Git Bash to put the key in your clipboard:

 clip < ~/.ssh/id_ed25519.pub

If the clip command fails, navigate to your user/.ssh folder and open the .pub file in notepad to copy it manually.
14. Click Add SSH key to confirm it

Git for Windows

We bring the awesome Git VCS to Windows
