# luckroy-overlay
Misc ebuilds. Use at your own risk

# Overlay XML
Put this into `/etc/layman/overlays/luckroy.xml`
~~~XML
<?xml version="1.0" encoding="UTF-8"?>
<!DOCTYPE repositories SYSTEM "http://www.gentoo.org/dtd/repositories.dtd">
<repositories xmlns="" version="1.0">
  <repo quality="experimental" status="unofficial">
    <name>luckroy</name>
    <description lang="en">Misc ebuilds</description>
    <homepage>https://github.com/marklacroix/luckroy-overlay</homepage>
    <owner type="person">
      <email>marklacroix@users.noreply.github.com</email>
      <name>Mark LaCroix</name>
    </owner>
    <source type="git">https://github.com/marklacroix/luckroy-overlay.git</source>
    <source type="git">git://github.com/marklacroix/luckroy-overlay.git</source>
    <source type="git">git@github.com:marklacroix/luckroy-overlay.git</source>
    <feed>https://github.com/marklacroix/luckroy-overlay/commits/master.atom</feed>
  </repo>
</repositories>
~~~
