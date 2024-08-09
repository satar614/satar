
# Bash Scripts

Bash scripts are a collection of bash commands which are kept in a text file that automates task for you to execute on a computer.

The Bash script "weather.sh" checks the weather using the geolocation of the ip address.





<img width="1021" alt="Screenshot 2024-08-09 at 19 58 02" src="https://github.com/user-attachments/assets/fa1bef8d-6911-4972-b0d5-8b94f912b703">

## Running the Script

The first thing i done was create a new branch

```bash
  git checkout -b learning

```

I then pushed the new branch to the remote repository


```bash
  git push -u origin learning


```
I then saved the bash script to a file named "weather.sh"
I then added, committed and pushed the file to the new branch


```bash
git add weather.sh
git commit -m "Add weather.sh script"
git push



```
Theres 3 ways to run the script

```bash
  bash weather.sh
  ./weather.sh
  sh weather.sh


```
