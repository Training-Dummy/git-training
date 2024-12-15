# Version Control Training

This is a practice repo for learning to use Git

1. **Clone this repo on your local machine**  
   ```bash
   git clone https://github.com/Training-Dummy/git-training.git
   ```

2. **Create a new branch with your first and last name**  
   ```bash
   git checkout -b <first name>_<last name>
   ```
   - For example:  
     ```bash
     git checkout -b first_last
     ```

3. **Create a new text file named `[current semester]/[last name]/[first name].txt`**
   - In the text file, write your name, email, and GitHub.com username
   - Example:  
     `2024FALL/last/first.txt`

4. **Commit your changes**
   ```bash
   git add .
   git commit -m "a useful message"
   ```

5. **Push your changes to GitHub**
   ```bash
   git push origin <branch name>
   ```
   - For example:  
     ```bash
     git push origin first_last
     ```
   - Or simply:  
     ```bash
     git push
     ```
</br></br>

6. **Submit a pull request**
   - Navigate to GitHub and under the "Pull requests" tab, select your branch to merge into `main`.

7. **Add 2 of your neighbor as reviewers**.
   - Note: Add them as reviewers, not assignees

8. **Wait for a review**. Review your neighbor's pull request.

9. **Upon approval, Squash and Merge changes**.
