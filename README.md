<!DOCTYPE html>
<html><body><b><u><i><font size="4" color="red">Invitation</font></i></u></b><br/>
  <i><font size="2" color="green">You are heartily invited to the JANEU ceremony of Abhijeet Shukla</font></i>
  
  <marquee><img src="https://user-images.githubusercontent.com/79617246/109388285-2e76ed80-792c-11eb-96b1-d0cc3baa3d9c.jpg" width="200" height="200"><img src="https://user-images.githubusercontent.com/79617246/109388522-a72a7980-792d-11eb-83f4-93f937070fad.jpg" width="150" height="200"><img src="https://user-images.githubusercontent.com/79617246/109389462-bb24aa00-7932-11eb-93e4-260fe464f21e.jpg" width="200" height="200"><img src="https://user-images.githubusercontent.com/79617246/109389467-c37ce500-7932-11eb-965d-7244c31efb8a.jpg" width="300" height="200"></marquee>
  <button onclick="typeWriter()">Your Invite</button>
  <p id="demo"></p>
  <script>
  var i=0;
  var txt='Please come and bless us on 27 april';
  var speed=50;
  function typeWriter(){
  if(i<txt.length){
  document.getElementById("demo").innerHTML+=txt.charAt(i);
  i++;
  setTimeout(typeWriter,speed);
                    }
                    }
                    </script>
</body></html>
