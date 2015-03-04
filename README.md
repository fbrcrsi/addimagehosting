# addimagehosting
Add custom image hosting service on phpBB 3.1.3 message editor 

## Quick Install
You can install this on the latest release of phpBB 3.1.3 by following the steps below:

1. [Download the latest release](https://github.com/fbrcrsi/addimagehosting).
2. Unzip the downloaded release, and change the name of the folder to `addimagehosting`.
3. In the `ext` directory of your phpBB board, create a new directory named `fbrcrsi` (if it does not already exist). 
4. Copy the `addimagehosting` folder to `ext/fbrcrsi/` directory of your phpBB board.
5. To configure, edit `/ext/fbrcrsi/addimagehosting/styles/all/template/event/posting_editor_message_after.html` and add your code after <!-- Add your code after this line -->
6. Navigate in the ACP to `Customise -> Manage extensions`.
7. Look for `Add image hosting service` under the Disabled Extensions list, and click its `Enable` link.


You can use this generic code:

`<iframe src="http://www.hostingpics.net/iframe_mini.php" width="400" height="100" scrolling="no" frameborder="0" allowtransparency="true"></iframe>`

to hosting your image on Hostingpics service.

Remember to purge cache each time you edit the templates after the installation

## Uninstall

1. Navigate in the ACP to `Customise -> Extension Management -> Extensions`.
2. Look for `Add image hosting service` under the Enabled Extensions list, and click its `Disable` link.
3. To permanently uninstall, click `Delete Data` and then delete the `/ext/fbrcrsi/addimagehosting` directory.
