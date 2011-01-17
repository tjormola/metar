                                Lua METAR parser

   This library can be used to parse METAR coded weather reports and fetch
   current METAR reports from [1]NOAA [2]Internet Weather Service in Lua.

   The parser is pretty simple and by no means claims to support every
   feature one might find in METAR coded weather reports. For example,
   weather forecasts and automatic weather reports are not detected.
   Unsupported features in the weather reports are silently dropped.

                                  Dependencies

   [3]LuaSocket is required for fetching weather reports from the
   [4]Internet Weather Service.

   My [5]Lua weather library is required for doing some unit conversions.

                                  Downloading

   METAR parser home page is at [6]http://solitudo.net/software/lua/metar/
   and it can be downloaded from the public Git repository at
   git://scm.solitudo.net/metar.git. Gitweb interface is available at
   [7]http://scm.solitudo.net/gitweb/public/metar.git.

   Remember to download the submodules after cloning metar.git.
    1. $ git submodule init
    2. $ git submodule update

                                  Installation

   Install the src/metar.lua under some of the directories included in the
   default LUA_PATH for your Lua distribution, or install under desired
   location and set LUA_PATH accordingly. More info about LUA_PATH at
   [8]http://www.lua.org/pil/8.1.html.

                               API Documentation

   API documentation for metar is available under the api/ directory of
   the distribution.

                                   References

   The following material was used when researching METAR
     * [9]Federal Meteorological Handbook No. 1 - Surface Weather
       Observations and Reports
     * [10]Metar codes by Richard Ogley
     * [11]Meteorology @ West Moors - Metar decode
     * Source code of [12]libgweather
     * Source code of [13]Metar

                            Copyright and licensing

   Copyright: © 2010 Tuomas Jormola [14]tj@solitudo.net
   [15]http://solitudo.net

   Licensed under the terms of the [16]GNU General Public License Version
   2.0. License terms are included in the file COPYING.

References

   1. http://www.noaa.gov/
   2. http://weather.noaa.gov/
   3. http://www.cs.princeton.edu/~diego/professional/luasocket/
   4. http://weather.noaa.gov/
   5. http://solitudo.net/software/lua/weatherlib/
   6. http://solitudo.net/software/lua/metar/
   7. http://scm.solitudo.net/gitweb/public/metar.git
   8. http://www.lua.org/pil/8.1.html
   9. http://www.ofcm.gov/fmh-1/fmh1.htm
  10. http://www.astro.keele.ac.uk/oldusers/rno/Aviation/metar_codes.html
  11. http://booty.org.uk/booty.weather/metinfo/codes/METAR_decode.htm
  12. http://ftp.gnome.org/pub/GNOME/sources/libgweather/
  13. http://www.leune.org/metar/
  14. mailto:tj@solitudo.net
  15. http://solitudo.net/
  16. http://www.gnu.org/licenses/gpl-2.0.html
