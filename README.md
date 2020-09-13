# HandJs library
HandJs library is a library for hand posture detection via a webcam.
More info: https://hand-js.com/

The library is **locked** against the localhost domain. If you want to use it on your page please contact: contact@hand-js.com


### Sample

    var handJS = new HandJS(gesture => 
    {
        if (gesture === 'HandDetected') 
           console.log('Hand detected :-)');
        else
           console.log('Hand lost :-(');
    });

    handJS.start()
          .catch(/* handle error */);
