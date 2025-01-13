
Introducing 47 Very Important CheatSheats You'll Ever Need

 1. Python : https://lnkd.in/grD8XUS6
 2. Pandas : https://lnkd.in/g4yTJ7CP
 3. NumPy : https://lnkd.in/gg9Uw-km
 4. Matplotlib https://lnkd.in/gahrGicD
 5. Seaborn https://lnkd.in/gcu4UKpw
 6. Scikit-learn https://lnkd.in/gGfkNu5i
 7. TensorFlow : https://lnkd.in/g3fw3uRV
 8. Keras : https://lnkd.in/gfPTfbgg
 9. PyTorch https://bit.ly/3lnsiIz
10. SQL : https://lnkd.in/gnwe4qcb
11. R : https://lnkd.in/gEgJ6A8j
12. Git : https://lnkd.in/gyzhztvH
13. AWS https://bit.ly/3ZQWMS1
14. Azure https://bit.ly/42f4N4V
15. Google Cloud Platform : https://bit.ly/3JJADzv
16. Docker : https://bit.ly/3Lt2zJe
17. Kubernetes https://lnkd.in/gjXCT7Mb
18. Linux Command Line : https://bit.ly/3FtcTgw
19. Jupyter Notebook https://lnkd.in/g7cPmgHQ
20. Data Wrangling :https://bit.ly/3TiMibP
21. Data Visualization : https://lnkd.in/gQ52Jd_J
22. Statistical Inference https://lnkd.in/grNXVQh5
23. Probability : https://lnkd.in/gvnWCphc
24. Linear Algebra : https://lnkd.in/gty6XpVF
25. Calculus https://lnkd.in/gjhsmsxu
26. Time Series : https://bit.ly/3Fvuep4
27. NLP: https://bit.ly/3Fvursm
28. Neural Network : https://lnkd.in/gThs2AAp
29. Deep Learning : https://lnkd.in/gVbSPae2
30. Machine Learning : https://bit.ly/3mZ5Wh3
31. Apache Spark : https://lnkd.in/ge7Rj-Yr
32. Hadoop : https://bit.ly/3Lq34DR
33. Big-O Notation t: https://lnkd.in/gfYqM8WU
34. Regular Expression : https://lnkd.in/gE9kZTZW
35. Unix/Linux Permissions https://bit.ly/3ZUfwA8
36. Python String Formatting https://lnkd.in/gHi26Uk2
37. Flask : https://lnkd.in/gGzbSTgU
38. Django : https://lnkd.in/grZcWz8y
39. SQL : https://lnkd.in/gyierV3f
40. PostgreSQL : https://lnkd.in/gzfiW7zB
41. MySQL: https://lnkd.in/g4JnPVTe
42. MongoDB : https://lnkd.in/gHc4F4ER
43. TensorFlow Probability Cheat Sheet: https://lnkd.in/gr3bgDGP
44. OpenAI GPT-3 Documentation: https://lnkd.in/gawB_SC9
45. GPT-3 API Reference: https://lnkd.in/gtCGZvX8
46. GPT-3 GitHub Repository: https://lnkd.in/g56cQQPD
47. Chat GPT Cheat Sheet : https://lnkd.in/e43cDB9q


## Linux Performance Analysis in 60 seconds 

In 60 seconds you can get a high level idea of system resource usage and running processes by running the following ten commands


1. uptime

This is a quick way to view the load averages, which indicate the number of tasks (processes) wanting to run

2. dmesg | tail

This views the last 10 system messages, if there are any. Look for errors that can cause performance issues.



3. vmstat 1


Short for virtual memory stat, vmstat(8) is a commonly available tool (first created for BSD decades ago). It prints a summary of key server statistics on each line.



4. mpstat -P ALL 1

This command prints CPU time breakdowns per CPU, which can be used to check for an imbalance. A single hot CPU can be evidence of a single-threaded application.

5. pidstat 1

Pidstat is a little like top’s per-process summary, but prints a rolling summary instead of clearing the screen. This can be useful for watching patterns over time, and also recording what you saw (copy-n-paste) into a record of your investigation.


6. iostat -xz 1

This is a great tool for understanding block devices (disks), both the workload applied and the resulting performance.

7. free -m


8. sar -n DEV 1

check network interface throughput: rxkB/s and txkB/s, as a measure of workload, and also to check if any limit has been reached


9. sar -n TCP,ETCP 1

This is a summarized view of some key TCP metrics

10. top

The top command includes many of the metrics we checked earlier. It can be handy to run it to see if anything looks wildly different from the earlier commands, which would indicate that load is variable.


![image](https://github.com/user-attachments/assets/de189eef-5759-4152-ba39-32b7b40a8999)



