# cordova-in-app-provisioning
1. Define var 
    declare var appWallet:any;

# determine If the Creidt Card is exist in iphone or apple watch or both 
   let data = {
        "cardPan": cardPan,
        "action":action
      };

    appWallet.determineCardCanAdd(resolve, reject, data);