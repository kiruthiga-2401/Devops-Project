# Monitor Aws Resource usage with shell scripting
Monitoring AWS Resources usage with shell scripting is done by using AWS command Line Interface(CLI) commands within a simple bash scripting.

This allow you to quickly list and track resources like ec2 instance, s3 buckets, Lambda functions without using the aws management console.
## Steps
The Aws configure command is the primary tool for setting up the aws command line interface with your credentials and default settings.


```bash
  aws configure
```
<img width="918" height="505" alt="Screenshot 2026-03-11 115916" src="https://github.com/user-attachments/assets/79a539b1-c7fe-4553-a910-636964775676" />


Writing the shell script involves creating a text file with a sequence of commands and then making it executable.

1.Open a text editor:
```bash
vim file.sh
```
2.Write your commands:

<img width="598" height="488" alt="Screenshot 2026-03-22 120501" src="https://github.com/user-attachments/assets/d70f971d-b54f-4a62-bb6e-2cc851644c28" />

3.Make the script executable:
 
Use the chmod command to grant execute permissions
 ```bash
 chmod 777 file.sh
 ```
4.Run the Script:
```bash
./file.sh
```
<img width="646" height="614" alt="Screenshot 2026-03-22 121134" src="https://github.com/user-attachments/assets/20e3f6ec-879d-4ab0-8d1b-3bb38ebb0f1b" />

