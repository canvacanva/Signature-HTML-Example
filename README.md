# Signature-HTML-Example
### Requirements
1-Create a virtual host like https://signatures.banner/

2-Add one or more logo (png) on https://signatures.banner/logo.png


### Outlook app config
Outlook -> Create new empty signanture, save (eg TEST)

Navigate to %appdata%\Roaming\Microsoft\Signatures, edit TEST***.htm using notepad, delete all and copy as follow
```
<!DOCTYPE HTML PUBLIC "-//W3C//DTD HTML 4.0 Transitional//EN">
<html>
<head></head>
<body>
<div>&nbsp;</div>
<div><span style="font-family: 'arial'; font-size: 9pt;"><strong>%%displayname%%</strong><br />
<div><span style="font-family: 'arial'; font-size: 9pt;">------------------------------<br />
<div></span><span style="font-family: 'arial'; font-size: 9pt;">%%Phone%%</span></div>
<div>&nbsp;</div>
<div><img src="https://signatures.banner/logo.png" /></div>
<div><span style="font-family: 'arial';font-size: 7.5pt; color: #XXXXXX;"><strong>COMPANY NAME</strong> | Address </span><br />
<span style="font-family: 'arial';font-size: 7.5pt; color: #XXXXXX;">T <a href="callto:+123456789">+39 123456789</a></span><br />
<span style="font-family: 'arial';font-size: 7.5pt; color: #XXXXXX;"><span ><a href="https://www.website.company" style="color: #00722d;" target="_blank" rel="noopener">website.company</a></span></div>

```

Example:
```
<!DOCTYPE HTML PUBLIC "-//W3C//DTD HTML 4.0 Transitional//EN">
<html>
<head></head>
<body>
<div>&nbsp;</div>
<div><span style="font-family: 'arial'; font-size: 9pt;"><strong>Mattia Caneva</strong><br />
<div><span style="font-family: 'arial'; font-size: 9pt;">------------------------------<br />
<div></span><span style="font-family: 'arial'; font-size: 9pt;">+39 123456789</span></div>
<div>&nbsp;</div>
<div><img src="https://raw.githubusercontent.com/canvacanva/Signature-HTML-Example/main/mc-logo-little.png" /></div>
<div><span style="font-family: 'arial';font-size: 7.5pt; color: #XXXXXX;"><strong>My Great Company</strong> | Address </span><br />
<span style="font-family: 'arial';font-size: 7.5pt; color: #XXXXXX;">T <a href="callto:+123456789">+39 123456789</a></span><br />
<span style="font-family: 'arial';font-size: 7.5pt; color: #XXXXXX;"><span ><a href="https://www.website.company" style="color: #00722d;" target="_blank" rel="noopener">website.company</a></span></div>

```

Output:

![image](https://github.com/canvacanva/Signature-HTML-Example/assets/17501324/5e131584-4a94-43aa-93fc-876aa52d1d0e)

