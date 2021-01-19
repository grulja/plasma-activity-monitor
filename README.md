# Plasma timekeeper
Time tracking plasma applet

Author: Jan Grulich &lt;jgrulich@redhat.com&gt;

Released under GPL 2.0+

How to compile
-------------------------------
  mkdir build <br/>
  cd build <br/>
  cmake .. -DCMAKE_INSTALL_PREFIX=/usr -DQML_INSTALL_DIR:PATH=$(QT_SELECT=5 qmake -query QT_INSTALL_QML) <br/>
  make <br/>
  # As root: <br/>
  make install <br/>


Distributions
------------------------------
If you don't think that compilation is a good option for you, you can try to ask your distribution packagers to include it in official repositories.

List of distributions providing plasma-timekeeper in their repositories: <br/>
<b>Archlinux</b> - https://aur.archlinux.org/packages/timekeeper-git <br/>
