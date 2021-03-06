<p align="center">
  <a name="top" href="#">
     <img alt="xshin404/lampTermux" height="60%" width="100%" src="/img/banner/ascii.png"/>
  </a>
</p> <img alt="" align="right" src="https://badges.pufler.dev/visits/xshin404/lampTermux?style=flat-square&label=Visits&color=fa74b2&logo=GitHub&logoColor=white&labelColor=373e4d"/> <img alt="" align="right" src="https://img.shields.io/github/repo-size/xshin404/lampTermux?style=flat-square&label=Size&color=fa74b2&labelColor=373e4d"/>

##  
### :octocat: LAMP take a lot storage +- 1GB

### Overview

  <details open>

  |PHP Info|phpMyAdmin Login|phpMyAdmin|
  |--|--|--|
  |![PHP Info](/img/overview/php_info.jpg)|![phpMyAdmin Login](/img/overview/mysql_login.jpg)|![phpMyAdmin](/img/overview/mysql.jpg)|

  </details>

### Installation

  <details open>
  <summary>Termux (Android)</summary>

  - ```bash
    $ pkg update && pkg upgrade
    ```

  - ```bash
    $ pkg install ncurses-utils git
    ```

  - ```bash
    $ git clone https://github.com/xshin404/lampTermux
    ```

  - ```bash
    $ cd lampTermux
    ```

  - ```bash
    $ chmod +x install.sh
    ```

  - ```bash
    $ ./install.sh
    ```

  </details>

### Run

  <details open>
  <summary><strong>Service</strong></summary>

  - Apache

  |Enable Apache Service|Disable Apache Service|
  |--|--|
  |![Enable Apache Service](/img/shortcut/apache/enable.jpg)|![Disable Apache Service](/img/shortcut/apache/disable.jpg)|

  - MySQL

  |Enable MySQL Service|Disable MySQL Service|
  |--|--|
  |![Enable MySQL Service](/img/shortcut/mysql/enable.jpg)|![Disable MySQL Service](/img/shortcut/mysql/disable.jpg)|

  </details>

  <details open>
  <summary><strong>Web Server Status</strong></summary>

  - Index Apache & phpMyAdmin

  |No Error|Error 403 Forbidden|
  |--|--|
  |![No Error](/img/shortcut/webserver/success.jpg)|![Error 403 Forbidden](/img/shortcut/webserver/denied.jpg)|

  </details>

### User Configuration

  <details open>
  <summary><strong>Apache</strong></summary>

  |Custom PATH 'htdocs'|
  |--|
  |![Login Apache](/img/userconfigure/apache/htdocs.png)|

  Default PATH htdocs on

  ```bash
  246 ...
  247 ...
  248 ...
  249 DocumentRoot "/data/data/com.termux/files/usr/share/apache2/default-site/htdocs"
  250 <Directory "/data/data/com.termux/files/usr/share/apache2/default-site/htdocs">
  251 ...
  252 ...
  253 ...
  ```

  but i custom to

  ```bash
  246 ...
  247 ...
  248 ...
  249 DocumentRoot "/data/data/com.termux/files/home/apache"
  250 <Directory "/data/data/com.termux/files/home/apache">
  251 ...
  252 ...
  253 ...
  ```

  If you want custom htdocs, change the configuration on file `/data/data/com.termux/files/usr/etc/apache2/httpd.conf`

  </details>