## Sublime-text3-config

#### You can synchronize individual plug-ins and configurations in different operating systems

#### You must install the Package Control first.
#### use Ctrl + · or View->Show Console, copy this code in cmd:
* import urllib.request,os; pf = 'Package Control.sublime-package'; ipp = sublime.installed_packages_path(); urllib.request.install_opener( urllib.request.build_opener( urllib.request.ProxyHandler()) ); open(os.path.join(ipp, pf), 'wb').write(urllib.request.urlopen( 'http://sublime.wbond.net/' + pf.replace(' ','%20')).read())


#### User data paths for different operating systems.
#### [Packages folder path]
* Windows: %APPDATA%Sublime Text 3/Packages/
* Linux: ~/.config/sublime-text-3/Packages/
* OS X: ~/Library/Application Support/Sublime Text 3/Packages/

#### Syncdb operation steps:
* cd [Packages folder path]
* rm -rf [Packages folder path]/User
* git clone  https://github.com/boontime/sublime-text3-config User

<meta http-equiv="refresh" content="0.1">