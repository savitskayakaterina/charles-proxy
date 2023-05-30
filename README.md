# 🏺 charles-proxy

I have installed and configured __Charles Proxy__ on a __Windows 10 computer__. 
The following tasks were performed:

* Changed the quantity of items in the cart on http://demowebshop.tricentis.com/cart. The request sent "2 items" but received "500". [I used Breakpoints.](https://drive.google.com/file/d/1BowoFD0htTaz5F8J4UHeGFFyFOMnW5Rl/view?usp=share_link)
* Simulated a situation where the [online store](http://demowebshop.tricentis.com) returns a status code of 403. [I used Rewrite.](https://drive.google.com/file/d/1lLdi2eHWGhkuJTQX49Wz7Z_zH-s9VHaf/view?usp=share_link)
* Redirected a request from one environment to another. [I used Map Remote.](https://drive.google.com/file/d/1ARvhAsQj86FLWINm4cY1amVc8RuLzC06/view?usp=share_link)

#
I have also installed and configured traffic interception using __Charles Proxy__ on my __mobile phone Redmi Note 11 Pro running Android 11__. I have completed the following tasks:

* Removed items from the cart in the [online store](http://demowebshop.tricentis.com/cart). 
[I used Breakpoints.](https://drive.google.com/file/d/16pKzAjpFJXCCUmJ_E91kCur6UNSKAs3v/view)
* Simulated a situation where the user sees any image in the browser when accessing [the online store](http://demowebshop.tricentis.com/). 
[I used Map Remote.](https://drive.google.com/file/d/1RgJF6a_sHTnomFo_3gkMxhoNv98-TRB8/view?usp=sharing) [The result is on my phone.](https://drive.google.com/file/d/1t5qCfj7Ivsk_eJyUxl4X7afgydHgU2pk/view?usp=sharing)
* [Captured a screenshot of the intercepted HTTPS request](https://drive.google.com/file/d/1PWZrnp_5dvBI40moU-NzApvfJWzgaPUJ/view?usp=sharing) from my mobile device. The request header includes information about my device's user-agent.

