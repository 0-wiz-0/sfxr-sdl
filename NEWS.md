# unreleased

- Port to GTK 4.
- Finish PREFIX support.
- Use `.sfxr` extension by default.
- Port to SDL 2.

# 1.2.1

* Fixed bug, the loop function call in main was commented out by Johan Helsing (bobbaluba@gmail.com)
* Fixed broken target clean in Makefile

# 1.2

* Added support for gtk+-3.0 by Tim Oertel (toertel-sfxr@manax.org http://www.heroicproportions.org)
  (Sorry, you have to edit the makefile to switch back to gtk+-2.0)

# 1.1

* Various small improvements and 1 bugfix by Hans de Goede
  <hdegoede@redhat.com>:
  * Fix a small bug in the audio setup which could cause a quite noticeable
    delay between pressing a button and hearing the sound
  * Add an icon and .desktop file
  * Add a make install target, note:  hardcoded to /usr but it does understand
    the DESTDIR make parameter

# 1.0

* Initial SDL port of sfxr by mjau/GerryJJ
