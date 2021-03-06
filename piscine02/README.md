[한국어](README.kr.md)
# Chapter Ⅰ<br>Instruction

- Fork the Piscine02 repository.
- You can use **`git push` at the `main` branch** to push to the server.
- You always can restart the project if you didn't get the right result.
- Commit with the message you want.
- Try the command `git log --oneline --graph --all` and it will show you all the commits you've made.

<br>
<br>
<br>

# Chapter Ⅱ<br>Exercise 00 : Fast-forword merge

| Turn-in branch | Turn-in directory | Files to turn in | Allowed commands |
|:--:|:--:|:--:|:--:|
| main | ex00/ | answer.txt | git branch, git merge |

<br>

- Move to the `dev00` branch.
- Make some commits to the `dev00` branch.
- Go back to the `main` branch and merge the `dev00` branch into the `main` branch.
- Try the command `git reflog` to make sure that the type of the merge was fast-forward.
- Submit your answer(**the result when you get with the command `git reflog`**) in a file named `answer.txt`.

<br>
<br>
<br>

# Chapter Ⅲ<br>Exercise 01 : Git merge

| Turn-in branch | Turn-in directory | Files to turn in | Allowed commands |
|:--:|:--:|:--:|:--:|
| main | ex01/ | answer.txt | git branch --merged, git branch --no-merged|

<br>

- Submit your answer(**the result when you get with the command `git branch --merged`**) in a file named `answer.txt`. 

<br>
<br>
<br>


# Chapter Ⅳ<br>Exercise 02: Cancel merge

| Turn-in branch | Turn-in directory | Files to turn in | Allowed commands |
|:--:|:--:|:--:|:--:|
| main | ex02/ | answer.txt | git merge , git merge --abort|

<br>

- Merge `feature` branch into `dev01` branch.
- If you get the conflict, cancel the merge with some commands.


! You don't need to reset the branches when you get conflicts. Cancel the merge only when it was a mistake. !