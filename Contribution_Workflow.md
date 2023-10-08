**Csq Contribution Workflow**

1. **Fork the Repository:**
   - Click "Fork" on the Csq repository on GitHub.

   ![GitHub Fork Button](https://github.com/CsqLang/Csq/fork)

2. **Clone Your Fork:**
   - Clone your fork locally.
     ```bash
     $ git clone https://github.com/YourUsername/csq
     $ cd csq
     ```

3. **Set Up Remote References:**
   - Add a reference to the original repository.
     ```bash
     $ git remote add upstream https://github.com/CsqLang/Csq.git
     $ git fetch upstream
     ```

4. **Create a Feature Branch:**
   - Create and switch to a new branch for your feature.
     ```bash
     $ git checkout -b my-feature
     ```

5. **Make Changes and Commit:**
   - Implement changes, stage, and commit.
     ```bash
     $ git add .
     $ git commit -m "Description of changes"
     ```

6. **Update Your Fork:**
   - Fetch changes from the original repository.
     ```bash
     $ git pull upstream master
     ```

7. **Push Changes to Your Fork:**
   - Push your changes to your GitHub fork.
     ```bash
     $ git push origin my-feature
     ```

8. **Create a Pull Request:**
   - Visit your fork on GitHub and create a pull request.
