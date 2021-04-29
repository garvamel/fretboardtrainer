[Refresh or click this text for a new note](https://garvamel.github.io/fretboardtrainer)

##<div id="text"></div>
 
<script>
 var note = ["A", "B", "C", "D", "E", "F", "G"];
 var quality = ["Natural", "Sharp", "Flat"];
 var string = ["E", "A", "D", "G", "B", "e"];
 
 var rand_note = Math.floor(Math.random() * 7);
 var rand_quality = Math.floor(Math.random() * 3);
 var rand_string = Math.floor(Math.random() * 6);
 
document.getElementById("text").innerHTML = note[rand_note] + " " + quality[rand_quality] + " on " + string[rand_string] + " string"  ;
</script>
