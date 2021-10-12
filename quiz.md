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

<input id="submit1" name="q1" type="button" value="submit"> <br>

<p id="res1"> </p>


<script>
var correct = new Audio('audio/AC.mp3');
var wrong = new Audio('audio/WA.mp3');
document.getElementById("submit1").addEventListener("click", function () {
  console.log('pls')

  var score=document.querySelector('input[name="q1"]:checked').value

  console.log(score)

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
