

    Yb  dP  dP"Yb  88   88 888888 88   88 88""Yb 888888
     YbdP  dP   Yb 88   88   88   88   88 88__dP 88__   
      8P   Yb   dP Y8   8P   88   Y8   8P 88""Yb 88""   
     dP     YbodP  `YbodP'   88   `YbodP' 88oodP 888888 

                         Yb    dP 88 888888 Yb        dP 888888 88""Yb 
                          Yb  dP  88 88__    Yb  db  dP  88__   88__dP 
                           YbdP   88 88""     YbdPYbdP   88""   88"Yb  
                            YP    88 888888    YP  YP    888888 88  Yb

# YouTube Viewer
Simple program to increase YouTube views written in Python. Works with live stream too.





# Requirements
 * **Python 3.7.x-3.11.x**
 * High speed Internet Connection
 * Good proxy list (http, https, socks4, socks5)
 * Google Chrome installed on your OS (not Chromium)


# Features
 * YouTube default, live streaming and YouTube Music support
 * Multithreaded and Dynamic thread support
 * Auto download updated chrome driver whenever user's Google Chrome version is updated
 * Patch chrome driver on the start of every thread by undetected-chromedriver
 * Proxy support 
      * location : text file (must be on path) / proxy API (should work with most of the proxy providers)
      * type : http, https, socks4, socks5
      * format : `ip:port`, `user:pass@ip:port`, `ip:port:user:pass`
      * proxy refresh after a certain time specified by the user
      * rotating proxy support
 * chrome v80+ randomized user agent based on platform
 * canvas,audio,font,webgl fingerprint defender and IP leak prevent by webrtc control
 * geolocation, timezone, referer spoofing
 * can add extra extensions in the `extension/custom_extension/` folder
 * direct link or search *keyword* on YouTube then watch the video by matching exact video *title*
 * modify **urls.txt, search.txt and config.json** on the fly without restarting program
 * HTTP api on localhost and a database to store view count
 * config.json to save settings
 * bypass consent page and several other pop up 
 * save bandwidth by reducing video quality 
 * can set higher(100%) watch duration percentage to increase *Watch time*, change playback speed
 * #### Traffic Sources
   * YouTube Search
   * Suggested Videos
   * External (Google, Yahoo, DuckDuckGo, Bing, Twitter)
   * End Screens
   * Channel Pages
   * Direct or unknown


