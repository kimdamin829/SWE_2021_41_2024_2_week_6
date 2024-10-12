# SWE_2021_41_2024_2_week_6
Summary of week4 and week5 assignments

## Week4 Assignment
In week4 assignment, I made a '.ipynb' file with Colab and uploaded it to my GitHub.
 - Download the colab notebook as ‘.ipynb’ file and change the name
 - Click ‘New’ button and create a new repository
 - Click “uploading an existing file” in the blue box
 - Drag (Upload) the file and write a commit message
 - Finally, click “Commit changes”

## Week5 Assignment
In week5 assignment, I set up an environment for a container. I had to meet the following requirements: Linux OS, Git installed, Python3 installed, bind mount.
<br>
I captured the output of the following commands and submit the screenshots

```bash
docker exec <container_name> cat /etc/os-release
```
```bash
docker exec <container_name> git --version
```
```bash
docker exec <container_name> python3 --version
```
```bash
docker inspect --format="{{ .HostConfig.Binds }}" <container_name>
```
