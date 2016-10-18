Live Templates & Files Templates Python Odoo (formerly OpenERP) for Pycharm.

# Install live templates

Windows

Template python Odoo
```
COPY .\templates\Python.xml <your home directory>\<product name><version number>\config\templates\Python.xml
```
Template xml Odoo
```
COPY .\templates\html_xml.xml <your home directory>\<product name><version number>\config\templates\html_xml.xml
```

Linux

Template python Odoo
```
cp ./templates/Python.xml <your home directory>/.<product name><version number>/config/templates/Python.xml
```
Template xml Odoo
```
cp ./templates/html_xml.xml <your home directory>/.<product name><version number>/config/templates/html_xml.xml
```
MacOS

Template python Odoo
```
cp ./templates/Python.xml <your home directory>/Library/Preferences/<product name><version number>/templates/Python.xml
```
Template xml Odoo
```
cp ./templates/html_xml.xml <your home directory>/Library/Preferences/<product name><version number>/templates/html_xml.xml
```

# Install files templates

Windows
```
COPY .\fileTemplates\*.py  <your home directory>\<product name><version number>\config\fileTemplates\
```

Linux
```
cp ./fileTemplates/*.py <your home directory>/.<product name><version number>/config/fileTemplates/
```
MacOS
```
cp -r ./fileTemplates/ <your home directory>/Library/Preferences/<product name><version number>/fileTemplates/
```

Restart Pycharm

Contributors
```

   * Julien Drecq
   * Maxime Jacquet
   * mynameisshiy
   * Jeffery Chen Fan
```

# Todo : 
* Odoo new api integration (decorator, function, views, etc.)
