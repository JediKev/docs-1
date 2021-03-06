.. |br| raw:: html

    <br>

Google Two Factor Authentication
================================

The Google Two Factor Authentication plugin allows allows Agents to use the Google Authenticator application
on their phone for 2FA.

.. raw:: html

    <div style="position: relative; padding-bottom: 2%; height: 0; overflow: hidden; max-width: 100%; height: auto;">
        <iframe width="560" height="315" src="https://www.youtube.com/embed/E6O8axLZq8o" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
    </div>

If configured, the Agent must scan a QR code from the app, and when they go to log into
the helpdesk, they will be prompted to enter a
|br|
6-digit code displayed in the app to finish logging in.

This plugin requires downloading the Google Authenticator app on your phone. It can be found `here <https://www.google.com/url?sa=t&rct=j&q=&esrc=s&source=web&cd=&cad=rja&uact=8&ved=2ahUKEwiF0Laq4qzrAhVFLK0KHWOsAfUQFjAAegQIAxAB&url=https%3A%2F%2Fplay.google.com%2Fstore%2Fapps%2Fdetails%3Fid%3Dcom.google.android.apps.authenticator2%26hl%3Den_US&usg=AOvVaw0uNewdEdn3o8Rdb2Ksudwu>`_
for Android and `here <https://apps.apple.com/us/app/google-authenticator/id388497605>`_ for Apple.

Once the app has been installed on your smart phone, you will need to add and enable the plugin in osTicket.

Go to:

Admin Panel | Manage | Plugins | Add New Plugin

.. image:: ../_static/images/g2fa1.png
  :alt: Add Plugin

|br|

.. image:: ../_static/images/g2fa2.png
  :alt: Install Plugin

|br|

.. image:: ../_static/images/g2fa3.png
  :alt: Enable Plugin

|br|

.. image:: ../_static/images/g2fa4.png
  :alt: Confirm Enable

Once the plugin is enabled, Agents can configure Google Authenticator as their Default 2FA method by going to their profile.

Google Authenticator will be greyed out in the list until it has been configured.

.. image:: ../_static/images/g2fa5.png
  :alt: User Profile

|br|

.. image:: ../_static/images/g2fa6.png
  :alt: 2FA Options

|br|

.. image:: ../_static/images/g2fa7.png
  :alt: Google 2FA QR Code

Once you see the QR code, you will need to scan the code using the Google Authenticator app on your phone.

.. image:: ../_static/images/g2fa8.png
  :alt: Add QR Code

Click 'Scan barcode'.

.. image:: ../_static/images/g2fa9.png
  :alt: Scan QR Code

Once you have scanned the barcode, you will see an entry on the app for osTicket.

.. image:: ../_static/images/g2fa10.png
  :alt: Google 2FA QR Code

|br|

.. image:: ../_static/images/g2fa11.png
  :alt: QR Code Next

Enter the code displayed in the app and verify that it is correct.

.. image:: ../_static/images/g2fa12.png
  :alt: QR Code Next

|br|

.. image:: ../_static/images/g2fa13.png
  :alt: Setup Complete

Once the configuration is complete, you can choose Google Authenticator as your Default 2FA method.

.. image:: ../_static/images/g2fa14.png
  :alt: Choose Google 2FA

The next time you log into the helpdesk, you will be prompted to enter the code shown in your Google Authenticator app to finish logging into the helpdesk.

.. image:: ../_static/images/g2fa15.png
  :alt: Help Desk Login

|br|

.. image:: ../_static/images/g2fa16.png
  :alt: Google 2FA Code

|br|

.. image:: ../_static/images/g2fa17.png
  :alt: Enter 2FA Code

Once verfied, you will be redirected to the helpdesk.
