Live Templates & Files Templates Python Odoo (formerly OpenERP) for Pycharm.

# Install live templates

Linux

Template python Odoo
```
cp ./templates/Python.xml /home/[user]/.PyCharm30/config/templates/Python.xml
```
Template xml Odoo
```
cp ./templates/html_xml.xml /home/[user]/.PyCharm30/config/templates/html_xml.xml
```
MaxOS

Template python Odoo
```
cp ./templates/Python.xml /Users/[user]/Library/Preferences/PyCharm30/templates/Python.xml
```
Template xml Odoo
```
cp ./templates/html_xml.xml /Users/[user]/Library/Preferences/PyCharm30/templates/html_xml.xml
```

# Install files templates

Linux
```
cp ./fileTemplates/*.py /home/[user]/.PyCharm30/config/fileTemplates/*.py
```
MacOS
```
cp -r ./fileTemplates/ /Users/[user]/Library/Preferences/PyCharm30/fileTemplates/
```

Restart Pycharm

Contributors
```

   * Julien Drecq
   * Maxime Jacquet
```

# Todo : 
* Odoo new api integration (decorator, function, views, etc.)
