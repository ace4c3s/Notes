**Key Points**
- Learnt how to use wfuzz and gobuster tools. 
- wfuzz is also used to do directory enumeration. 
- The following is the syntax:

```
- wfuzz -c -z file,wordlist --hw 0  http://10.10.244.142/api/site-log.php/?date=FUZZ 
```

- The above was used to fuzz the value of the parameter date. 
- -c displays the a colorful output/
- -z replaces the file with the actual wordlist/file to be used.
- -hw hides files with 0 words.

![[Pasted image 20240904161238.png]]