# Note: Most of the templates are parameter based.
1. Collect parameter urls
2. Then give urls to nuclei and use the templates

# Installation
```
git clone https://github.com/freelancermijan/custom-nuclei-templates.git
nuclei -ud ~/custom-nuclei-templates/
```

# Usage
```
waymore -i "http://testphp.vulnweb.com" -n -mode U | gf sqli | nuclei -t ~/custom-nuclei-templates/ | tee sqlis.txt
```
# Updation
```
cd custom-nuclei-templates/
sudo git pull
cd
```
