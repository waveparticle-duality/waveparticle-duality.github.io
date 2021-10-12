---
layout: default
---

{% include navigation.html %}
{% include latex.html %}

What is $$1+1$$? <br>

<input type="radio" name="q1" value="0"> $$1$$ <br>

<input type="radio" name="q1" value="1"> $$2$$ <br>

<input type="radio" name="q1" value="0"> $$3$$ <br>

<input type="radio" name="q1" value="0" > $$4$$ <br>

<input id="submit1" type="button" value="submit"> <br>

<p id="res1"> </p>


<script>
var correct = new Audio('audio/AC.mp3');
var wrong = new Audio('audio/WA.mp3');
document.getElementById("submit1").addEventListener("click", function () {
  var score=document.querySelector('input[name="q1"]:checked').value
  
  if (score=="1"){
  	document.getElementById("res1").innerHTML="Correct"
  	correct.play();
  }
  else{
  	document.getElementById("res1").innerHTML="Wrong"
  	wrong.play();
  }
});
</script>


What is $$1+2$$? <br>

<input type="radio" name="q2" value="0"> $$1$$ <br>

<input type="radio" name="q2" value="0"> $$2$$ <br>

<input type="radio" name="q2" value="1"> $$3$$ <br>

<input type="radio" name="q2" value="0" > $$4$$ <br>

<input id="submit2" type="button" value="submit"> <br>

<p id="res2"> </p>


<script>
var correct = new Audio('audio/AC.mp3');
var wrong = new Audio('audio/WA.mp3');
document.getElementById("submit2").addEventListener("click", function () {
  var score=document.querySelector('input[name="q2"]:checked').value

  if (score=="1"){
  	document.getElementById("res2").innerHTML="Correct"
  	correct.play();
  }
  else{
  	document.getElementById("res2").innerHTML="Wrong"
  	wrong.play();
  }
});
</script>


