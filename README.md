# CracktheCode
A simple login pentesting application. Alpha prototype.

**README**

A simple bruteforcing and reverse engineering vulnerable application for pentesting. Bruteforce to crack the password for admin and use reverse engineering to find the other credentials and their accompanying success code.

This is the alpha prototype, more to come.

Windows only so far.

<h2>More Details</h2>

It's a Windows application written in C# which is why it is installed with a setup file. There are 2 levels of practice excercises, bruteforcing the common password for the username "admin" and reverse engineering to find the other 2 credentials by finding the source code. For those who tried and were totally confused, here's a somewhat hint: <details><summary>Hint</summary>The app verifies credentials based on simple offline variables stored in the RAM, they are all saved in the program. Thus, data interception and online bruteforcing software like Burpsuite and Hydra are of no use here, use an offline password cracker. Also, 5 bruteforce attempts results in the app closing as of the newest toughest release, good luck. If that's too hard, check out an older release before that security update.</details>
