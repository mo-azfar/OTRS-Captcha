# OTRS-Goole-reCaptcha-for-Sign-Up-Form
- For OTRS CE v6.0
- Google reCaptcha at OTRS customer portal (sign-up form)
- All this require modification in following files:

		$OTRS_HOME/Custom/Kernel/Output/HTML/Layout.pm (To generate captcha form)
		$OTRS_HOME/Custom/Kernel/Output/HTML/Templates/Standard/CustomerLogin.tt (To output captcha form)
		$OTRS_HOME/Custom/Kernel/System/Web/InterfaceCustomer.pm (To validate captcha form response)
		$OTRS_HOME/var/httpd/htdocs/skin/Customer/default/css/Core.Login.css (Do play around with this to get best result especially on Slider and Login)
		
- Modification has been tag with [#begin recaptcha  CODE	#end recaptcha]	


Signup without completing captcha  
[![captcha1.png](https://i.postimg.cc/ZKYQ4NkF/captcha1.png)](https://postimg.cc/QVPmqHdH)  

[![captcha2.png](https://i.postimg.cc/jSLkJrSD/captcha2.png)](https://postimg.cc/3kQZPVph)  