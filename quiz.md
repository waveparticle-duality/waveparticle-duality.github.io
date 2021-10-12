---
layout: default
---

{% include navigation.html %}
{% include latex.html %}

Q1) A particular blackbody radiates a maximum wavelength of 1449nm. Determine the temperature of the object in K.  <br>

<input type="radio" name="q1" value="0"> $$500$$ <br>
<input type="radio" name="q1" value="0"> $$1000$$ <br>
<input type="radio" name="q1" value="1"> $$2000$$ <br>
<input type="radio" name="q1" value="0" > $$4000$$ <br>
<input id="submit1" type="button" value="submit"> <br>
<p id="res1"> </p>
<br>
<br>
<br>
<br>

<script>
var correct = new Audio('audio/AC.mp3');
var wrong = new Audio('audio/WA.mp3');
document.getElementById("submit1").addEventListener("click", function () {
  var score=document.querySelector('input[name="q1"]:checked').value
  
  if (score=="1"){
  	document.getElementById("res1").innerHTML="CORRECT"
  	correct.play();
  }
  else{
  	document.getElementById("res1").innerHTML="WRONG"
  	wrong.play();
  }
});
</script>



Q2) Xiao Ming is sitting in an aircon room which is at $$25$$ degrees celcius. Xiao Ming has a temperature of $$36.9$$ degrees celcius. Assume that Xiao Ming can be modelled as a square cuboid with square sidelengths of $$0.5~m$$ and height $$2~m$$. Also, assume that Xiao Ming is a perfect blackbody. <br>

<input type="radio" name="q2" value="1"> $$447~W$$ <br>
<input type="radio" name="q2" value="0"> $$894~W$$ <br>
<input type="radio" name="q2" value="0"> $$1441~W$$ <br>
<input type="radio" name="q2" value="0" > $$2882~W$$ <br>
<input id="submit2" type="button" value="submit"> <br>
<p id="res2"> </p>
<br>
<br>
<br>
<br>

<script>
var correct = new Audio('audio/AC.mp3');
var wrong = new Audio('audio/WA.mp3');
document.getElementById("submit2").addEventListener("click", function () {
  var score=document.querySelector('input[name="q2"]:checked').value
  
  if (score=="1"){
  	document.getElementById("res2").innerHTML="CORRECT"
  	correct.play();
  }
  else{
  	document.getElementById("res2").innerHTML="WRONG"
  	wrong.play();
  }
});
</script>


Q3) Usain Bolt has a weight of $$94~kg$$. Usain bolt can run $$100~m$$ in $$9.58~s$$. Assuming that during this run his speed is constant, find Usain bolt’s De Brogile wavelength. <br>

<input type="radio" name="q3" value="0"> $$3.378 \cdot 10^{-36}~m$$ <br>
<input type="radio" name="q3" value="0"> $$6.757 \cdot 10^{-36}~m$$ <br>
<input type="radio" name="q3" value="0"> $$3.378 \cdot 10^{-37}~m$$ <br>
<input type="radio" name="q3" value="1" > $$6.757 \cdot 10^{-37}~m$$ <br>
<input id="submit3" type="button" value="submit">  <br>
<p id="res3"> </p>
<br>
<br>
<br>
<br>

<script>
var correct = new Audio('audio/AC.mp3');
var wrong = new Audio('audio/WA.mp3');
document.getElementById("submit3").addEventListener("click", function () {
  var score=document.querySelector('input[name="q3"]:checked').value
  
  if (score=="1"){
  	document.getElementById("res3").innerHTML="CORRECT"
  	correct.play();
  }
  else{
  	document.getElementById("res3").innerHTML="WRONG"
  	wrong.play();
  }
});
</script>



Q4) Usain Bolt has a weight of $$94~kg$$. Usain bolt can run $$100~m$$ in $$9.58~s$$. Assume Usain Bolt is running towards a double slit. Find the maximal slit distance such that any non-central peak is observed using the De Brogile wavelength obtained in Q3. <br>

<input type="radio" name="q4" value="0"> $$3.378 \cdot 10^{-36}~m$$ <br>
<input type="radio" name="q4" value="0"> $$6.757 \cdot 10^{-36}~m$$ <br>
<input type="radio" name="q4" value="0"> $$3.378 \cdot 10^{-37}~m$$ <br>
<input type="radio" name="q4" value="1" > $$6.757 \cdot 10^{-37}~m$$ <br>
<input id="submit4" type="button" value="submit">  <br>
<p id="res4"> </p>
<br>
<br>
<br>
<br>

<script>
var correct = new Audio('audio/AC.mp3');
var wrong = new Audio('audio/WA.mp3');
document.getElementById("submit4").addEventListener("click", function () {
  var score=document.querySelector('input[name="q4"]:checked').value
  
  if (score=="1"){
  	document.getElementById("res4").innerHTML="CORRECT"
  	correct.play();
  }
  else{
  	document.getElementById("res4").innerHTML="WRONG"
  	wrong.play();
  }
});
</script>


Q5) Light of wavelength $$400~nm$$ is shone through $$2$$ slits separated by $$0.2~mm$$. A wall is $$5~m$$ away. $$How far would the first non-central peak be from the central peak?$$
 <br>

<input type="radio" name="q5" value="1"> $$1~cm$$ <br>
<input type="radio" name="q5" value="0"> $$10~cm$$ <br>
<input type="radio" name="q5" value="0"> $$1~m$$ <br>
<input type="radio" name="q5" value="0" > $$10~m$$ <br>
<input id="submit5" type="button" value="submit"> <br>
<p id="res1"> </p>
<br>
<br>
<br>
<br>


<script>
var correct = new Audio('audio/AC.mp3');
var wrong = new Audio('audio/WA.mp3');
document.getElementById("submit5").addEventListener("click", function () {
  var score=document.querySelector('input[name="q5"]:checked').value
  
  if (score=="1"){
  	document.getElementById("res5").innerHTML="CORRECT"
  	correct.play();
  }
  else{
  	document.getElementById("res5").innerHTML="WRONG"
  	wrong.play();
  }
});
</script>

Q6) Light of wavelength $$400~nm$$ is shone through $$2$$ slits separated by $$0.2~mm$$. A wall is $$5~m$$ away. How many peaks can be seen on the wall?
 <br>

<input type="radio" name="q5" value="0"> $$251$$ <br>
<input type="radio" name="q5" value="0"> $$501$$ <br>
<input type="radio" name="q5" value="1"> $$1001$$ <br>
<input type="radio" name="q5" value="0" > $$2001$$ <br>
<input id="submit6" type="button" value="submit"> <br>
<p id="res1"> </p>
<br>
<br>
<br>
<br>


<script>
var correct = new Audio('audio/AC.mp3');
var wrong = new Audio('audio/WA.mp3');
document.getElementById("submit6").addEventListener("click", function () {
  var score=document.querySelector('input[name="q6"]:checked').value
  
  if (score=="1"){
  	document.getElementById("res6").innerHTML="CORRECT"
  	correct.play();
  }
  else{
  	document.getElementById("res6").innerHTML="WRONG"
  	wrong.play();
  }
});
</script>
