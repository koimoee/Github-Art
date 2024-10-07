# GitHub Contribution Graph Painter 🎨


<h3 align="left"><a href="https://github-painter.vercel.app/">Try the editor</a></h3>
<img src="https://raw.githubusercontent.com/mattrltrent/random_assets/main/gh_painter.png" width="100%" height="" style="display: block"/>

<h3 align="left"><a href="https://github.com/mattrltrent?tab=overview&from=2018-12-01&to=2018-12-31#:~:text=January,Jan">Live profile example</a></h3>
<img src="https://raw.githubusercontent.com/mattrltrent/github_painter/main/github/ex_1.JPG" width="100%" height="" style="display: block"/>


### Usage

1. Add your repo URL to the spot seen above. **I highly reccomend using a new empty private repo in case something goes wrong.**
2. Select the year you want to paint to, for the best results, ensure this year is *free from commits* on your GitHub profile. This tool assumes you have none.
3. Paint on the canvas using the different colors.
4. Download the script, as seen above. You may have to run the command `chmod 701 github_painter.sh` to give executable permission to the file. Then, run `sudo ./github_painter.sh` to run the script.

In Windows, `.sh` scripts are not natively executable like they are on Unix-based systems. To run a `.sh` script in Windows, you typically need to use WSL or a compatible shell environment. Here’s how to address the issue:

### Method 2: Using Git Bash

If you don’t want to use WSL, you can also run `.sh` scripts using Git Bash:

1. **Install Git for Windows**: Download and install from [git-scm.com](https://git-scm.com/).

2. **Open Git Bash**: After installation, open Git Bash from the Start menu.

3. **Navigate to Your Script**: Use `cd` to navigate to your script's directory:
   ```bash
   cd /c/path/to/your/github_painter.sh
   ```

4. **Run the Script**: You might not need to use `sudo` in Git Bash, but you can run the script with:
   ```bash
   chmod +x github_painter.sh   # Make it executable (if needed)
   ./github_painter.sh           # Execute the script
   ```

### Troubleshooting

- To delete the art, you can always delete the repository that the commits took place in. This is the easy way out. For more complex cases, refer to [this](https://stackoverflow.com/questions/448919/how-can-i-remove-a-commit-on-github) Stack Overflow question.
- If you're not seeing the art appear, please toggle the "Private Contributions" setting on your GitHub profile. It seems to help things sync up:


    <img src="https://raw.githubusercontent.com/mattrltrent/github_painter/main/github/demo_2.JPG" width="auto" height="200px" style="display: inline"/>




### Notes

- Use at your own risk, because I feel like committing a bunch of times could mess something up if used incorrectly. So, be careful, know what you're doing, and check the outputted `github_painter.sh` script before using it.

### Feel free to create Issues or PRs!

- Issues [here](https://github.com/mattrltrent/github_painter/issues).
- PRs [here](https://github.com/mattrltrent/github_painter/pulls).
