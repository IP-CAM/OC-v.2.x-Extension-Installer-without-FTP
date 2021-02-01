### Presentation

This modification was developed in the OCMOD format (replacing VQMOD), and adds the possibility of installing extensions without using FTP in OpenCart, however, it keeps the FTP function working.

One of the great advantages of this modification is that, when setting up your store in a local environment (on your pc or local server), you can install extensions through the OpenCart Extension Installer, without the need to use FTP.

#### Important

As of version 3.0.0.0 of OpenCart, this feature became native, eliminating the need for this modification.

### Installation

 1. Download the modification from the link: https://github.com/opencartbrasil/instalador-sem-ftp/archive/master.zip
 2. When downloading, unzip the contents of the zip file and locate the file "installer-without-ftp.ocmod.xml".
 3. In the store administration, access the menu ** Extensions → Installer ** (Extensions → Installer).
 4. On the installer page, click the ** Upload ** button, select the 'installer-without-ftp.ocmod.xml' file, and wait for the automatic installation to complete.
 5. After installation, access the menu ** Extensions → Modifications ** (Extensions → Modifications) and click the button ** Update ** (Refresh), so that the modification is added in the store, remembering that it is not the " Refresh "button of the browser, but the blue" Refresh "button next to the orange and red button on the OpenCart screen.

### Configuration

Access the store administration and go to the menu ** Settings → Stores ** (System → Settings), click the button ** Edit ** (Edit), click on the box ** FTP **, locate the field “** Enable FTP? ** "(Enable FTP), check the option" ** No ** "(No), and click the ** Save ** button.

### Uninstallation

To uninstall the modification, in the store administration, access the menu ** Extensions → Modifications ** (Extensions → Modifications), select the modification with the name '** Installer without FTP **', click the ** Delete ** button (Delete), and then the ** Refresh ** button.

### Update

Access the store administration and perform the Uninstall procedure, then perform the Installation procedure.

### Doubts

OCMOD (OpenCart Modification) is native to OpenCart, that is, it is not necessary to install any add-on in OpenCart to use modifications or extensions in the OCMOD format, for more information about OCMOD, follow the link for more information:

https://github.com/opencart/opencart/wiki/Modification-System

### The file changed virtually through OCMOD is:

admin / controller / extension / ** installer.php **
