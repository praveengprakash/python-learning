

```python
name='richard'
```


```python
name
```




    'richard'




```python
len(name)
```




    7




```python
age=10
```


```python
name
```




    'richard'




```python
for i in name:
    print (i)
```

    r
    i
    c
    h
    a
    r
    d



```python
var=[1,2,3,4,5,6,7,8,9,10]
for i in var:
    print (i)
```

    1
    2
    3
    4
    5
    6
    7
    8
    9
    10



```python
name='richard'
```


```python
print(name)
```

    richard



```python
type(name)
```




    str




```python
number=20
```


```python
print(number)
```

    20



```python
number
```




    20




```python
type(number)
```




    int




```python
number=10.5
```


```python
number
```




    10.5




```python
type(number)
```




    float




```python
ip='1.2.1.2'
```


```python
ip
```




    '1.2.1.2'




```python
type(ip)
```




    str




```python
len(ip)
```




    7




```python
num=12345
```


```python
len(num)
```


    ---------------------------------------------------------------------------

    TypeError                                 Traceback (most recent call last)

    <ipython-input-20-04dd5b0b64a9> in <module>
    ----> 1 len(num)
    

    TypeError: object of type 'int' has no len()



```python
len(str(num))
```




    5




```python
sum=5+5
```


```python
sum
```




    10




```python
len(str(sum))
```




    2




```python
5>3
```




    True




```python
5==3
```




    False




```python
'x'*20
```




    'xxxxxxxxxxxxxxxxxxxx'




```python
fruit='orange'
```


```python
'g' in fruit
```




    True




```python
'i' in fruit
```




    False




```python
'i' not in fruit
```




    True




```python
var = None
```


```python
type(var)
```




    NoneType




```python
opin=1234
epin=123
if opin==epin:
    print('ok')
else:
    print('fail')
```

    fail



```python

```


```python
bool(1)
```




    True




```python
bool(0)
```




    False




```python
name='devon'
```


```python
name
```




    'devon'




```python
name[-1]
```




    'n'




```python
name[0]
```




    'd'




```python

```


```python
if name[0]==name[1]:
    print('ok')
else:
    print('no')
```

    no



```python
for i in 'praveen':
    print(i)
```

    p
    r
    a
    v
    e
    e
    n



```python
lang='malayalam'
```


```python
a=0
for i in lang:
    if i=='a':
        a+=1
print(a)
```

    4



```python
timeStamp = '24/Mar/2017:19:39:21'
```


```python
timeStamp[:11]
```




    '24/Mar/2017'




```python
timeStamp[12:]
```




    '19:39:21'




```python
lang
```




    'malayalam'




```python
if lang==lang[::-1]:
    print('yeah')
```

    yeah



```python
'praveen'[::-1]
```




    'neevarp'




```python
dir(name)
```




    ['__add__',
     '__class__',
     '__contains__',
     '__delattr__',
     '__dir__',
     '__doc__',
     '__eq__',
     '__format__',
     '__ge__',
     '__getattribute__',
     '__getitem__',
     '__getnewargs__',
     '__gt__',
     '__hash__',
     '__init__',
     '__init_subclass__',
     '__iter__',
     '__le__',
     '__len__',
     '__lt__',
     '__mod__',
     '__mul__',
     '__ne__',
     '__new__',
     '__reduce__',
     '__reduce_ex__',
     '__repr__',
     '__rmod__',
     '__rmul__',
     '__setattr__',
     '__sizeof__',
     '__str__',
     '__subclasshook__',
     'capitalize',
     'casefold',
     'center',
     'count',
     'encode',
     'endswith',
     'expandtabs',
     'find',
     'format',
     'format_map',
     'index',
     'isalnum',
     'isalpha',
     'isdecimal',
     'isdigit',
     'isidentifier',
     'islower',
     'isnumeric',
     'isprintable',
     'isspace',
     'istitle',
     'isupper',
     'join',
     'ljust',
     'lower',
     'lstrip',
     'maketrans',
     'partition',
     'replace',
     'rfind',
     'rindex',
     'rjust',
     'rpartition',
     'rsplit',
     'rstrip',
     'split',
     'splitlines',
     'startswith',
     'strip',
     'swapcase',
     'title',
     'translate',
     'upper',
     'zfill']




```python
name.count('n')
```




    1




```python
lang = 'MalaYalAM'
```


```python
lang.count('a')
```




    3




```python
lang.lower().endswith('m')
```




    True




```python
f = '/etc/httpd/conf/httpd.conf'
```


```python
    f.endswith('.conf')
```




    True




```python
    f.endswith('nf')
```




    True




```python
f.startswith('/')
```




    True




```python
f.startswith('/et')
```




    True




```python
f.startswith('/ets')
```




    False




```python
f.isdigit()
```




    False




```python
num='12345'
```


```python
num.isdigit()
```




    True




```python
name='d3von'
```


```python
name.isalnum()
```




    True




```python
name.isalpha()
```




    False




```python
name
```




    'd3von'




```python
name=' ---strip---   '
```


```python
name
```




    ' ---strip---'




```python
name.rstrip()
```




    ' ---strip---'




```python
name.strip().lstrip('-')
```




    'strip---'




```python
name.strip().rstrip('-')
```




    '---strip'




```python
name.strip().strip('-')
```




    'strip'




```python
name
```




    ' ---strip---'




```python
name.replace('s','a')
```




    ' ---atrip---'




```python
name
```




    ' ---strip---'




```python
name.strip().replace('-','=')
```




    '===strip==='




```python
name
```




    ' ---strip---'




```python
name.replace('s','r')
```




    ' ---rtrip---'




```python
os=[]
```


```python
dir(os)
```




    ['__add__',
     '__class__',
     '__contains__',
     '__delattr__',
     '__delitem__',
     '__dir__',
     '__doc__',
     '__eq__',
     '__format__',
     '__ge__',
     '__getattribute__',
     '__getitem__',
     '__gt__',
     '__hash__',
     '__iadd__',
     '__imul__',
     '__init__',
     '__init_subclass__',
     '__iter__',
     '__le__',
     '__len__',
     '__lt__',
     '__mul__',
     '__ne__',
     '__new__',
     '__reduce__',
     '__reduce_ex__',
     '__repr__',
     '__reversed__',
     '__rmul__',
     '__setattr__',
     '__setitem__',
     '__sizeof__',
     '__str__',
     '__subclasshook__',
     'append',
     'clear',
     'copy',
     'count',
     'extend',
     'index',
     'insert',
     'pop',
     'remove',
     'reverse',
     'sort']




```python
len(os)
```




    0




```python
os.append('mint')
```


```python
os
```




    ['mint']




```python
os.append('ubuntu')
```


```python
os
```




    ['mint', 'ubuntu']




```python
os=['rhel']
```


```python
os
```




    ['rhel']




```python
os.append('mint')
```


```python
os.append('kali')
```


```python
os.append('ubuntu')
```


```python
os
```




    ['rhel', 'mint', 'kali', 'ubuntu']




```python
len(os)
```




    4




```python
os[0]
```




    'rhel'




```python
os[-1]
```




    'ubuntu'




```python
os[::-1]
```




    ['ubuntu', 'kali', 'mint', 'rhel']




```python
os.reverse()
```


```python
os
```




    ['ubuntu', 'kali', 'mint', 'rhel']




```python
os.reverse()
```


```python
os
```




    ['rhel', 'mint', 'kali', 'ubuntu']




```python
for i in os:
    print(i)
```

    rhel
    mint
    kali
    ubuntu



```python
os.count('rhel')
```




    1




```python
os.index('kali')
```




    2




```python
os.index('mint')
```




    1




```python
os[1][0]
```




    'm'




```python
os[3][3]
```




    'n'




```python
os[2][2]
```




    'l'




```python
os[1]
```




    'mint'




```python
os[1]='debian'
```


```python
os
```




    ['rhel', 'debian', 'kali', 'ubuntu']




```python
os[0]='debian'
```


```python
os
```




    ['debian', 'debian', 'kali', 'ubuntu']




```python
len(os)
```




    4




```python
os.remove('kali')
```


```python
os
```




    ['debian', 'debian', 'ubuntu']




```python
os
```




    ['debian', 'debian', 'ubuntu']




```python
os.pop(1)
```




    'debian'




```python
os
```




    ['debian', 'ubuntu']




```python
os.insert('kali','1')
```


    ---------------------------------------------------------------------------

    TypeError                                 Traceback (most recent call last)

    <ipython-input-213-58332388da5f> in <module>
    ----> 1 os.insert('kali','1')
    

    TypeError: 'str' object cannot be interpreted as an integer



```python
os.insert?
```


```python
os.insert(1,'kali')
```


```python
os
```




    ['debian', 'kali', 'ubuntu']




```python
name
```




    ' ---strip---'




```python
list(name)
```




    [' ', '-', '-', '-', 's', 't', 'r', 'i', 'p', '-', '-', '-']




```python
r=[]
for i in name:
    r.append(i)
print(r)
```

    [' ', '-', '-', '-', 's', 't', 'r', 'i', 'p', '-', '-', '-']



```python
r
```




    [' ', '-', '-', '-', 's', 't', 'r', 'i', 'p', '-', '-', '-']




```python
name='my name is pgp'
```


```python
name.split()
```




    ['my', 'name', 'is', 'pgp']




```python
input('enter name')
```

    enter namepraveen





    'praveen'




```python
opin=1234
pin=input('enter pin')
if int(pin)==opin:
    print('ok')
else:
    print('no')
```

    enter pin124
    no



```python
ip='123.64.72.09'
```


```python
ip
```




    '123.64.72.09'




```python
ip.split('.')[::-1]
```




    ['09', '72', '64', '123']




```python
'.'.join(ip.split('.')[::-1])
```




    '09.72.64.123'




```python
ip='129.34.01.54'
```


```python
ip.split()
```




    ['129.34.01.54']




```python
ip.split('.')[::-1]
```




    ['54', '01', '34', '129']




```python
'.'.join(ip.split('.')[::-1])
```




    '54.01.34.129'




```python
ips=[['123.34.63.1',22],['64.62.15.1',10],['103.3.1.62',54]]
```


```python
ips
```




    [['123.34.63.1', 22], ['64.62.15.1', 10], ['103.3.1.62', 54]]




```python
for i in ips:
    print(i)
```

    ['123.34.63.1', 22]
    ['64.62.15.1', 10]
    ['103.3.1.62', 54]



```python
ips[1][0]
```




    '64.62.15.1'




```python
for i in ips:
    ip=i[0]
    port=i[1]
    print(ip,port)
```

    123.34.63.1 22
    64.62.15.1 10
    103.3.1.62 54



```python
for i in ips:
    ip=i[0]
    port=i[1]
    print('{:12}:{}'.format(ip,port))
```

    123.34.63.1 :22
    64.62.15.1  :10
    103.3.1.62  :54



```python
ips
```




    [['123.34.63.1', 22], ['64.62.15.1', 10], ['103.3.1.62', 54]]




```python
ip=[]
```


```python
ip
```




    []




```python
ip=[]
ip=input('enter ip: ')
octe=int(ip.split('.')[0])
if octe > 0 and octe <126:
    print('class A')
elif octe > 127 and octe < 191:
    print('class B')
elif octe > 192 and octe < 223:
    print('class C')
else:
    print('unknown class')
```

    enter ip: 220
    class C



```python
msg = """
A security hacker is someone who access explores methods for breaching defenses and exploiting 
weaknesses in a computer system  or network. Hackers may be motivated by a multitude of reasons,
such as profit, anna  protest, hat information syshacker gathering challenge, recreation, 
or to evaluate system weaknesses alex to assist in formulating defenses against potential hackers. 
The subculture that axe has evolved around hackers is often referred to as the computer underground
"""
```


```python
print(msg)
```

    
    A security hacker is someone who access explores methods for breaching defenses and exploiting 
    weaknesses in a computer system  or network. Hackers may be motivated by a multitude of reasons,
    such as profit, anna  protest, hat information syshacker gathering challenge, recreation, 
    or to evaluate system weaknesses alex to assist in formulating defenses against potential hackers. 
    The subculture that axe has evolved around hackers is often referred to as the computer underground
    



```python
msg.lower().count('hack')
```




    5




```python
msg.lower().replace(',','')
```




    '\na security hacker is someone who access explores methods for breaching defenses and exploiting \nweaknesses in a computer system  or network. hackers may be motivated by a multitude of reasons\nsuch as profit anna  protest hat information syshacker gathering challenge recreation \nor to evaluate system weaknesses alex to assist in formulating defenses against potential hackers. \nthe subculture that axe has evolved around hackers is often referred to as the computer underground\n'




```python
msg.lower().replace(',','').split()
```




    ['a',
     'security',
     'hacker',
     'is',
     'someone',
     'who',
     'access',
     'explores',
     'methods',
     'for',
     'breaching',
     'defenses',
     'and',
     'exploiting',
     'weaknesses',
     'in',
     'a',
     'computer',
     'system',
     'or',
     'network.',
     'hackers',
     'may',
     'be',
     'motivated',
     'by',
     'a',
     'multitude',
     'of',
     'reasons',
     'such',
     'as',
     'profit',
     'anna',
     'protest',
     'hat',
     'information',
     'syshacker',
     'gathering',
     'challenge',
     'recreation',
     'or',
     'to',
     'evaluate',
     'system',
     'weaknesses',
     'alex',
     'to',
     'assist',
     'in',
     'formulating',
     'defenses',
     'against',
     'potential',
     'hackers.',
     'the',
     'subculture',
     'that',
     'axe',
     'has',
     'evolved',
     'around',
     'hackers',
     'is',
     'often',
     'referred',
     'to',
     'as',
     'the',
     'computer',
     'underground']




```python
msg.lower().replace(',','').replace('.','').split()
```




    ['a',
     'security',
     'hacker',
     'is',
     'someone',
     'who',
     'access',
     'explores',
     'methods',
     'for',
     'breaching',
     'defenses',
     'and',
     'exploiting',
     'weaknesses',
     'in',
     'a',
     'computer',
     'system',
     'or',
     'network',
     'hackers',
     'may',
     'be',
     'motivated',
     'by',
     'a',
     'multitude',
     'of',
     'reasons',
     'such',
     'as',
     'profit',
     'anna',
     'protest',
     'hat',
     'information',
     'syshacker',
     'gathering',
     'challenge',
     'recreation',
     'or',
     'to',
     'evaluate',
     'system',
     'weaknesses',
     'alex',
     'to',
     'assist',
     'in',
     'formulating',
     'defenses',
     'against',
     'potential',
     'hackers',
     'the',
     'subculture',
     'that',
     'axe',
     'has',
     'evolved',
     'around',
     'hackers',
     'is',
     'often',
     'referred',
     'to',
     'as',
     'the',
     'computer',
     'underground']




```python
msg.lower().replace(',','').replace('.','').split().count('a')
```




    3




```python
vow_list=[]
for word in msg.lower().replace(',','').replace('.','').split():
    if word.startswith('a'):
        vow_list.append(word)
print(vow_list)
```

    ['a', 'access', 'and', 'a', 'a', 'as', 'anna', 'alex', 'assist', 'against', 'axe', 'around', 'as']



```python
vow_list
```




    ['a',
     'access',
     'and',
     'a',
     'a',
     'as',
     'anna',
     'alex',
     'assist',
     'against',
     'axe',
     'around',
     'as']




```python
vow_list=[]
for word in msg.lower().replace(',','').replace('.','').split():
    if word.startswith('a') or word.startswith('e') or word.startswith('i') or word.startswith('o') or word.startswith('u'):
        vow_list.append(word)
print(vow_list)
```

    ['a', 'is', 'access', 'explores', 'and', 'exploiting', 'in', 'a', 'or', 'a', 'of', 'as', 'anna', 'information', 'or', 'evaluate', 'alex', 'assist', 'in', 'against', 'axe', 'evolved', 'around', 'is', 'often', 'as', 'underground']



```python
'as' in vow_list
```




    True




```python
vow_list=[]
fchar=['a','e','i','o','u']
for word in msg.replace(',','').replace('.','').split():
    if word[0] in fchar:
        vow_list.append(word)
print(vow_list)
```

    ['is', 'access', 'explores', 'and', 'exploiting', 'in', 'a', 'or', 'a', 'of', 'as', 'anna', 'information', 'or', 'evaluate', 'alex', 'assist', 'in', 'against', 'axe', 'evolved', 'around', 'is', 'often', 'as', 'underground']



```python
import os
```


```python
os.listdir('/etc')
```




    ['mailcap',
     'legal',
     'apparmor',
     'inxi.conf',
     'securetty',
     'mtab',
     'init',
     'mono',
     'resolvconf',
     'hosts',
     'guest-session',
     'gtk-2.0',
     'python',
     'logrotate.d',
     'services',
     'host.conf',
     'debconf.conf',
     'shadow',
     'ca-certificates.conf',
     'drirc',
     'sysctl.conf',
     'PackageKit',
     'speech-dispatcher',
     'bash_completion',
     'brltty.conf',
     'libreoffice',
     'dictionaries-common',
     'xdg',
     'hosts.allow',
     'modules',
     'python2.7',
     'zsh_command_not_found',
     'issue.net',
     'gshadow-',
     'pki',
     'upstream-release',
     'xml',
     'thermald',
     'avahi',
     'magic.mime',
     'sensors3.conf',
     'ucf.conf',
     'inputrc',
     'netplan',
     'sudoers',
     'group',
     'rsyslog.conf',
     'opt',
     'gconf',
     'pnm2ppa.conf',
     'profile',
     'ld.so.conf.d',
     'hostname',
     'console-setup',
     'apparmor.d',
     'vdpau_wrapper.cfg',
     'rc5.d',
     'initramfs-tools',
     'logcheck',
     'ppp',
     'issue',
     'sudoers.d',
     'gnome-app-install',
     'ltrace.conf',
     'cracklib',
     'manpath.config',
     '.pwd.lock',
     'menu-methods',
     'passwd',
     'usb_modeswitch.d',
     'ifplugd',
     'request-key.conf',
     'environment',
     'fstab',
     'init.d',
     'rc6.d',
     'pm',
     'debian_version',
     'chatscripts',
     'cron.daily',
     'bindresvport.blacklist',
     'ca-certificates',
     'gufw',
     'shadow-',
     'udisks2',
     'crontab',
     'pam.conf',
     'newt',
     'pulse',
     'acpi',
     'request-key.d',
     'subuid',
     'hdparm.conf',
     'apport',
     'mtools.conf',
     'shells',
     'gss',
     'lintianrc',
     'polkit-1',
     'rc3.d',
     'cron.weekly',
     'nsswitch.conf',
     'hp',
     'rc4.d',
     'wpa_supplicant',
     'kernel-img.conf',
     'timezone',
     'security',
     'modprobe.d',
     'locale.alias',
     'network',
     'magic',
     'lightdm',
     'gshadow',
     'localtime',
     'firefox',
     'python3.6',
     'adduser.conf',
     'libnl-3',
     'ssl',
     'networkd-dispatcher',
     'tmpfiles.d',
     'wgetrc',
     'lvm',
     'gimp',
     'rsyslog.d',
     'gdb',
     'depmod.d',
     'grub.d',
     'cryptsetup-initramfs',
     'alternatives',
     'ghostscript',
     'cron.d',
     'rc1.d',
     'protocols',
     'sysctl.d',
     'libblockdev',
     'apt',
     'hddtemp.db',
     'casper.conf',
     'rc2.d',
     'cupshelpers',
     'default',
     'rmt',
     'subgid',
     'ufw',
     'usb_modeswitch.conf',
     'deluser.conf',
     'gtk-3.0',
     'doc-base',
     'adjtime',
     'gnome',
     'NetworkManager',
     'emacs',
     'libao.conf',
     'pam.d',
     'ldap',
     'locale.gen',
     'binfmt.d',
     'samba',
     'modules-load.d',
     'lsb-release',
     'obex-data-server',
     'anacrontab',
     'subuid-',
     'glvnd',
     'apm',
     'libaudit.conf',
     'rc0.d',
     'fwupd',
     'dhcp',
     'cron.hourly',
     'calendar',
     'ImageMagick-6',
     'brltty',
     'fuse.conf',
     'python3',
     'mime.types',
     'cifs-utils',
     'vim',
     'bash.bashrc',
     'passwd-',
     'thunderbird',
     'rcS.d',
     'logrotate.conf',
     'skel',
     'kernel',
     'brlapi.key',
     'selinux',
     'udev',
     'java-11-openjdk',
     'UPower',
     'linuxmint',
     'ssh',
     'machine-id',
     'gai.conf',
     'kerneloops.conf',
     'group-',
     'systemd',
     'apg.conf',
     'login.defs',
     'os-release',
     'cron.monthly',
     'X11',
     'ld.so.cache',
     'rpc',
     'subgid-',
     'ld.so.conf',
     'update-motd.d',
     'profile.d',
     'papersize',
     'openvpn',
     'updatedb.conf',
     'dkms',
     'appstream.conf',
     'resolv.conf',
     'cups',
     'perl',
     'libpaper.d',
     'terminfo',
     'sensors.d',
     'sgml',
     'sane.d',
     'dpkg',
     'pcmcia',
     '.java',
     'iproute2',
     'vtrgb',
     'groff',
     'hosts.deny',
     'nanorc',
     'fonts',
     'dbus-1',
     'bash_completion.d',
     'geoclue',
     'mailcap.order',
     'bluetooth',
     'networks',
     'mke2fs.conf']




```python
for i in os.listdir('/etc'):
    if i.endswith('.conf'):
        print(i)
```

    inxi.conf
    host.conf
    debconf.conf
    ca-certificates.conf
    sysctl.conf
    brltty.conf
    sensors3.conf
    ucf.conf
    rsyslog.conf
    pnm2ppa.conf
    ltrace.conf
    request-key.conf
    pam.conf
    hdparm.conf
    mtools.conf
    nsswitch.conf
    kernel-img.conf
    adduser.conf
    casper.conf
    usb_modeswitch.conf
    deluser.conf
    libao.conf
    libaudit.conf
    fuse.conf
    logrotate.conf
    gai.conf
    kerneloops.conf
    apg.conf
    ld.so.conf
    updatedb.conf
    appstream.conf
    resolv.conf
    mke2fs.conf



```python
os.path.getsize('/etc/resolv.conf')
```




    701




```python
os.path.join('/etc/','resolv.conf')
```




    '/etc/resolv.conf'




```python
for file in os.listdir('/etc'):
    if file.endswith('.conf'):
        abspath=os.path.join('/etc/',file)
        size=os.path.getsize(abspath)
        print('{:<21}: {}'.format(file,size))
```

    inxi.conf            : 71
    host.conf            : 92
    debconf.conf         : 2969
    ca-certificates.conf : 5898
    sysctl.conf          : 2683
    brltty.conf          : 25341
    sensors3.conf        : 10368
    ucf.conf             : 1260
    rsyslog.conf         : 1358
    pnm2ppa.conf         : 7649
    ltrace.conf          : 14867
    request-key.conf     : 1889
    pam.conf             : 552
    hdparm.conf          : 4861
    mtools.conf          : 624
    nsswitch.conf        : 556
    kernel-img.conf      : 110
    adduser.conf         : 3028
    casper.conf          : 429
    usb_modeswitch.conf  : 1523
    deluser.conf         : 604
    libao.conf           : 27
    libaudit.conf        : 191
    fuse.conf            : 280
    logrotate.conf       : 703
    gai.conf             : 2584
    kerneloops.conf      : 1308
    apg.conf             : 433
    ld.so.conf           : 34
    updatedb.conf        : 403
    appstream.conf       : 769
    resolv.conf          : 701
    mke2fs.conf          : 812



```python
for file in os.listdir('/etc'):
    if file.endswith('.conf'):
        abspath=os.path.join('/etc/',file)
        size=os.path.getsize(abspath)
        if size > 1024:
            print('{:<21}: {}'.format(file,size))
```

    debconf.conf         : 2969
    ca-certificates.conf : 5898
    sysctl.conf          : 2683
    brltty.conf          : 25341
    sensors3.conf        : 10368
    ucf.conf             : 1260
    rsyslog.conf         : 1358
    pnm2ppa.conf         : 7649
    ltrace.conf          : 14867
    request-key.conf     : 1889
    hdparm.conf          : 4861
    adduser.conf         : 3028
    usb_modeswitch.conf  : 1523
    gai.conf             : 2584
    kerneloops.conf      : 1308



```python
ips = [ ['192.168.0.10', 2020] ,['12.45.56.87' , 22] , ['192.168.100.234', 22 ] , ['12.45.56.87' , 2200]  ]
```


```python
ips
```




    [['192.168.0.10', 2020],
     ['12.45.56.87', 22],
     ['192.168.100.234', 22],
     ['12.45.56.87', 2200]]




```python
i=input('enter ip: ')
for ip in ips:
    if i in ip:
        print(ip[1])
        break
```

    enter ip: 192.168.100.234
    22



```python
s='12345'
```


```python
s[-5]
```




    '1'




```python
tupl=('192.168.1.1',)
```


```python
tupl
```




    ('192.168.1.1',)




```python
dir(tupl)
```




    ['__add__',
     '__class__',
     '__contains__',
     '__delattr__',
     '__dir__',
     '__doc__',
     '__eq__',
     '__format__',
     '__ge__',
     '__getattribute__',
     '__getitem__',
     '__getnewargs__',
     '__gt__',
     '__hash__',
     '__init__',
     '__init_subclass__',
     '__iter__',
     '__le__',
     '__len__',
     '__lt__',
     '__mul__',
     '__ne__',
     '__new__',
     '__reduce__',
     '__reduce_ex__',
     '__repr__',
     '__rmul__',
     '__setattr__',
     '__sizeof__',
     '__str__',
     '__subclasshook__',
     'count',
     'index']




```python
type(tupl)
```




    tuple




```python
tupl=('ubuntu','mint','debian','rhel','centos','ubuntu',10,23)
```


```python
tupl
```




    ('ubuntu', 'mint', 'debian', 'rhel', 'centos', 'ubuntu', 10, 23)




```python
tupl[2]
```




    'debian'




```python
tupl[1]
```




    'mint'




```python
tupl.count('ubuntu')
```




    2




```python
tupl.index('ubuntu')
```




    0




```python
tupl[0]
```




    'ubuntu'




```python
x=('freedom')
```


```python
type(x)
```




    str




```python
x=('freedom',)
```


```python
type(x)
```




    tuple




```python
x=('freedom','independence',[1,2,3])
```


```python
x
```




    ('freedom', 'independence', [1, 2, 3])




```python
del x[2]
```


    ---------------------------------------------------------------------------

    TypeError                                 Traceback (most recent call last)

    <ipython-input-27-c25053568b00> in <module>
    ----> 1 del x[2]
    

    TypeError: 'tuple' object doesn't support item deletion



```python
del x[2][0]
```


```python
x
```




    ('freedom', 'independence', [2, 3])




```python
type(x)
```




    tuple




```python
type(x[2])
```




    list




```python
list(x)
```




    ['freedom', 'independence', [2, 3]]




```python
x
```




    ('freedom', 'independence', [2, 3])




```python
list('praveen',)
```




    ['p', 'r', 'a', 'v', 'e', 'e', 'n']




```python
person=['alex',27,30000]
```


```python
name=person[0]
```


```python
age=person[1]
```


```python
sal=person[2]
```


```python
name
```




    'alex'




```python
age
```




    27




```python
sal
```




    30000




```python
name,age,sal=['john',37,0]
```


```python
name
```




    'john'




```python
age
```




    37




```python
sal
```




    0




```python
servers = [ ['192.168.0.10', 2020] ,['12.45.56.87' , 22] , ['192.168.100.234', 22 ] , ['12.45.56.87' , 2200]  ]
```


```python
host=input('enter ip: ')
for ip in servers:
    ipa=ip[0]
    port=ip[1]
    if ipa==host:
        print(port)
```

    enter ip: 12.45.56.87
    22
    2200



```python
host=input('enter ip: ')
for ip,port in servers:
    if ip==host:
        print(port)
```

    enter ip: 12.45.56.87
    22
    2200



```python
d={}
```


```python
type(d)
```




    dict




```python
dir(d)
```




    ['__class__',
     '__contains__',
     '__delattr__',
     '__delitem__',
     '__dir__',
     '__doc__',
     '__eq__',
     '__format__',
     '__ge__',
     '__getattribute__',
     '__getitem__',
     '__gt__',
     '__hash__',
     '__init__',
     '__init_subclass__',
     '__iter__',
     '__le__',
     '__len__',
     '__lt__',
     '__ne__',
     '__new__',
     '__reduce__',
     '__reduce_ex__',
     '__repr__',
     '__setattr__',
     '__setitem__',
     '__sizeof__',
     '__str__',
     '__subclasshook__',
     'clear',
     'copy',
     'fromkeys',
     'get',
     'items',
     'keys',
     'pop',
     'popitem',
     'setdefault',
     'update',
     'values']




```python
len(d)
```




    0




```python
d['name']='neo'
```


```python
d
```




    {'age': 29, 'sal': 10000, 'name': 'neo'}




```python
d['age']=29
```


```python
d
```




    {'name': 'neo', 'age': 29}




```python
d['sal']=10000
```


```python
d
```




    {'age': 29, 'sal': 10000}




```python
del d['name']
```


```python
d
```




    {'age': 29, 'sal': 0}




```python
'sal' in d
```




    True




```python
k=input('enter key: ')
if k in d:
    print(d[k])
else:
    print(0)
```

    enter key: sal
    10000



```python

```
