# Guide to setup GitHub & VSCode

---
## GitHub
1. Open the GitHub website, `https://github.com/`, and create a account.

<div style="text-align: center;">
  <img src="pictures/Instruction1.png" alt="I1"/> <!--width="600" height="auto" />-->
</div>

2. After creating an account, create a repository.

<div style="text-align: center;">
  <img src="pictures/Instruction2.png" alt="I2"/> <!--width="600" height="auto" />-->
</div>

3. Give it a name and make it `Public`. Also, make sure `Add a README file` box is checked.

<div style="text-align: center;">
  <img src="pictures/Instruction5.png" alt="I3"/> <!--width="600" height="auto" />-->
</div>

4. Notice that currently you are in the main branch. It is recommended that the development work is done on a seperate branch. To create a new branch, click `Branch`.

<div style="text-align: center;">
  <img src="pictures/Instruction6.png" alt="I4"/> <!--width="600" height="auto" />-->
</div>

5. Click on the `New branch` button and give it a name. Generally, the developement branch is called `devel` but you can name it as per your liking.

<div style="text-align: center;">
  <img src="pictures/Instruction7.png" alt="I5"/> <!--width="600" height="auto" />-->
</div>
<div style="text-align: center;">
  <img src="pictures/Instruction8.png" alt="I5.1"/> <!--width="600" height="auto" />-->
</div>
---

## Virtual Studio Code
1. Open VsCode. I would recommend to open a new window and start fresh. Go to `File` and open `New window`.

<div style="text-align: center;">
  <img src="pictures/Instruction10.png" alt="I6"/> <!--width="600" height="auto" />-->
</div>

2. Open `Explorer` and Clone the repository.

<div style="text-align: center;">
  <img src="pictures/Instruction12.png" alt="I7.1"/> <!--width="600" height="auto" />-->
</div>
<div style="text-align: center;">
  <img src="pictures/Instruction13.png" alt="I7.2"/> <!--width="600" height="auto" />-->
</div>
<div style="text-align: center;">
  <img src="pictures/Instruction14.png" alt="I7.3"/> <!--width="600" height="auto" />-->
</div>

3. Sign in to your GitHub account.

<div style="text-align: center;">
  <img src="pictures/Instruction15.png" alt="I8"/> <!--width="600" height="auto" />-->
</div>

**Note:** I already have a github account, so I chose the `Sign in to another account` option.

4. After signing in, the browser will redirect to the VSCode. Click the `Clone Repositiory` button again.

<div style="text-align: center;">
  <img src="pictures/Instruction16.png" alt="I9.1"/> <!--width="600" height="auto" />-->
</div>
</div>
<div style="text-align: center;">
  <img src="pictures/Instruction17.png" alt="I9.2"/> <!--width="600" height="auto" />-->
</div>

5. You should see the name of your repository, as `<your username>/<your repo name>`. Clone it in your favorable location. If you are using Ubuntu, I would recommend `Home` directory. Open the repo after cloning.

<div style="text-align: center;">
  <img src="pictures/Instruction18.png" alt="I10.1"/> <!--width="600" height="auto" />-->
</div>
<div style="text-align: center;">
  <img src="pictures/Instruction19.png" alt="I10.2"/> <!--width="600" height="auto" />-->
</div>
<div style="text-align: center;">
  <img src="pictures/Instruction20.png" alt="I10.3"/> <!--width="600" height="auto" />-->
</div>

6. Now, lets create a python file. Add a file and name it `intro.py`. Open the `example.txt`, copy the code and paste it in your newly created python file.

<div style="text-align: center;">
  <img src="pictures/Instruction22.png" alt="I11.1"/> <!--width="600" height="auto" />-->
</div>
<div style="text-align: center;">
  <img src="pictures/Instruction23.png" alt="I11.2"/> <!--width="600" height="auto" />-->
</div>
<div style="text-align: center;">
  <img src="pictures/Instruction24.png" alt="I11.3"/> <!--width="600" height="auto" />-->
</div>

7. Open the `Extensions` tab and install `Python Extension` and `Debugger`.

<div style="text-align: center;">
  <img src="pictures/Instruction40.png" alt="I12.1"/> <!--width="600" height="auto" />-->
</div>
<div style="text-align: center;">
  <img src="pictures/Instruction41.png" alt="I12.2"/> <!--width="600" height="auto" />-->
</div>
<div style="text-align: center;">
  <img src="pictures/Instruction42.png" alt="I12.3"/> <!--width="600" height="auto" />-->
</div>

**Note:** I already have the extensions and debugger, so there is no `install` option.

8. Go back to `Explorer` tab and `intro.py` file. At the top right corner, you will see the `Run` button.

<div style="text-align: center;">
  <img src="pictures/Instruction43.png" alt="I13"/> <!--width="600" height="auto" />-->
</div>

**Note:** Follow step 9 only if when trying to run the program it ask to select a kernel.

9. Click on `Select a Kernel`. Choose the kernel source and select the recommended `/usr/bin/python3` python environment. After that close the `Interactive` window.

<div style="text-align: center;">
  <img src="pictures/Instruction25.png" alt="I14.1"/> <!--width="600" height="auto" />-->
</div>
<div style="text-align: center;">
  <img src="pictures/Instruction26.png" alt="I14.2"/> <!--width="600" height="auto" />-->
</div>
<div style="text-align: center;">
  <img src="pictures/Instruction27.png" alt="I14.3"/> <!--width="600" height="auto" />-->
</div>
<div style="text-align: center;">
  <img src="pictures/Instruction28.png" alt="I14.4"/> <!--width="600" height="auto" />-->
</div>

10. Run the program. This is a number game. It will output a score if you guess the correct number and based on how many trial it took you to guess the number.

<div style="text-align: center;">
  <img src="pictures/Instruction31.png" alt="I15"/> <!--width="600" height="auto" />-->
</div>

11. Now lets push the code to your repository. Open the `Source Control` tab.

<div style="text-align: center;">
  <img src="pictures/Instruction32.png" alt="I16"/> <!--width="600" height="auto" />-->
</div>

  * First stage your changes.
    <div style="text-align: center;">
      <img src="pictures/Instruction33.png" alt="I16.1"/> <!--width="600" height="auto" />-->
    </div>
  * Add a commit message.
    <div style="text-align: center;">
      <img src="pictures/Instruction34.png" alt="I16.2"/> <!--width="600" height="auto" />-->
    </div>
  * Select `Commit & Push` option in `More Actions`.
    <div style="text-align: center;">
      <img src="pictures/Instruction35.png" alt="I16.3"/> <!--width="600" height="auto" />-->
    </div>
    <div style="text-align: center;">
      <img src="pictures/Instruction36.png" alt="I16.4"/> <!--width="600" height="auto" />-->
    </div>

12. Open your repo and check if the changes are pushed. You should see the newly created `intro.py` file.

<div style="text-align: center;">
  <img src="pictures/Instruction38.png" alt="I17"/> <!--width="600" height="auto" />-->
</div>
---

**CONGRATS!!, you successfully created a python file and pushed it to GitHub. Now you are PRO!!**