I am thrilled to announce that I successfully passed my ewpt exam on my first attempt. In preparation for the exam, I utilized various templates, including my personal favorite, the Anonymized Web Application Penetration Testing Report found at <a href="https://underdefense.com/wp-content/uploads/2021/09/Anonymized-Web-application-penetration-testing-report.pdf">https://underdefense.com/wp-content/uploads/2021/09/Anonymized-Web-application-penetration-testing-report.pdf</a>, as well as the TCM Security Sample Pentest Report found at <a href="https://github.com/hmaverickadams/TCM-Security-Sample-Pentest-Report">https://github.com/hmaverickadams/TCM-Security-Sample-Pentest-Report</a>, which was a popular choice among my peers.


<b>To ensure the quality of my report, I followed the following tips:</b>

1. Familiarized myself with OWASP, CWE, and CVSSV3 guidelines.
2. Created a template before starting the exam to ensure a consistent format.
3. Reviewed presentation techniques for reports by INE.
4. Ensured that your report did not exceed 10 MB in size and used pdf compressors if necessary.


<b>Exam tips:</b>

1. INE Material is more than enough
2. Don't get stuck on one point
3. DO YOUR RECON!!!
4. Check every possible parameter (every Header, Cookie and etc)
5. RECORD EVERYTHING WITH OBS
6. Use Joplin to take notes - https://joplinapp.org/
7. Use screenshots


<b>Tools used:</b>
Burp
sqlmap
gobuster
dirbuster
ffuf
dig
whatweb
nikto

<b>Tool commands:</b>

<b>SQLMAP (other tools are ez to use)</b>

sqlmap -r FILE -p PARAMETER --dbs --no-cast --keep-alive --threads 10


