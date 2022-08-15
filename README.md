# ScanReflectedXSS - Nuclei

This script allows to find XSS vulnerabilities with nuclei, taking advantage of this resource in its maximum analysis capacity.

In the community I have not seen XSS Fuzzing with nuclei in general, only focused on exploitations by CVE

# Testing Fuzzing GET

In the first instance they must collect the urls with the GET parameters.

![image](https://user-images.githubusercontent.com/66162160/184242706-dfe6a80a-e4cc-47c0-a5d4-e73b4f56ad21.png)

```sh
cat /home/hernan/test.txt | nuclei -t /home/hernan/Web/Vulnerabilidades/DAST/xss-hernan.yaml
```

![image](https://user-images.githubusercontent.com/66162160/184242024-b3904323-7f6b-4613-8c7b-eb83b64520db.png)

