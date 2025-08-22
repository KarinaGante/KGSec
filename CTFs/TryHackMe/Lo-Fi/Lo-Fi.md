<a href="https://git.io/typing-svg"><img src="https://readme-typing-svg.demolab.com?font=Fira+Code&duration=10000&pause=1000&color=AA07FF&width=435&lines=TryHackMe+-+Lo-Fi" alt="Typing SVG" /></a> 

<table style="width:100%; table-layout:fixed;">
  <tr>
    <td rowspan="2" style="width:20%;">
      <img src="./images/icon.png" style="width:100%; max-width:150px; height:auto;" alt="Lo-Fi Icon" />
    </td>
    <td>
      <p align="justify">Want to hear some lo-fi beats, to relax or study to? We've got you covered!</p>
    </td>
  </tr>
  <tr>
    <td>
      <p align="justify"><strong>Write Up CTF Lo-Fi TryHackMe by <a href="https://karinagante.github.io/" target="_blank" rel="noopener noreferrer">Karina Gante</a>.</strong></p>
    </td>
  </tr>
</table>

##

### Access room here:

👉 [https://tryhackme.com/room/lofi](https://tryhackme.com/room/lofi)

----

### Task: 
<p align="justify">Navigate to the following URL: <code>http://MACHINE_IP</code> and find the flag in the root of the filesystem.</p>

----

### Recon:
<p align="justify">If we click on any link in right side, we can see that URL can change dynamically:</p>

![Pages](./images/pages.png)

##

<p align="justify"> May we could try to access root of the filesystem on the server, using common paths like: <code>../../../../etc/passwd</code></p>

![Passwd](./images/passwd.png)

##

<p align="justify"> It seems like we found something! Now, we can try to find our flag by manipulating the server URL. Let's try access some flag file, like <code>flags.txt</code>, sounds obvious, right? 🤨</p>

![Flag](./images/flag.png)

##

<p align="justify"> 😳 What?! 😭 It was obvious at all! There it is! 🥳 We found our flag at <code>../../../../flag.txt</code>!</p>

![Done](./images/done.png)

----

*Flag Discovered with💜 by [Karina Gante](https://karinagante.github.io/).* 

[![LinkedIn](https://skillicons.dev/icons?i=linkedin&theme=dark)](https://www.linkedin.com/in/karina-gante/)
[![GitHub](https://skillicons.dev/icons?i=github&theme=dark)](https://www.github.com/KarinaGante/)
[![gmail](https://skillicons.dev/icons?i=gmail&theme=dark)](mailto:karina.gante1@gmail.com)
[![Instagram](https://skillicons.dev/icons?i=instagram&theme=dark)](https://www.instagram.com/karinovisk02/)

##

*Official Member of [CVE-Hunters](https://www.cvehunters.com/)🏹*