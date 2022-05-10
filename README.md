# CC-Autoclicker

NONE OF THIS IS MINE - CREDITS GO TO Jacob Streib FOR CREATING THIS AUTOCLICKER! I'm just posting this for a friend of mine to get it.


var autoclicker = setInterval(function(){
  try {
    document.getElementById('bigCookie').click();
  } catch (err) {
    clearInterval();
  }
}, 10);


to stop autoclicker - copy and paste line 17 into browser console

clearInterval(autoclicker);
