
var button1=0;
var button2=0;
var button3=0;
var button4=0;

$("#button1").val(button1);
$("#button2").val(button2);
$("#button3").val(button3);
$("#button4").val(button4);

$(".crop-audio").click(function(){
	// send the URL of the mp3 to the <audio> element, in #bigAudio div
	$("#bigAudio").attr('src',"http://dev.eng.gr/html/JS/jsJukebox/"+$(this).attr('alt') + ".mp3");
	// console.log("http://dev.eng.gr/html/JS/jsJukebox/"+$(this).attr('alt') + ".mp3");

  // set some fadein
  $("#bigAudio")[0].volume = 0.1;
	$("#bigAudio").animate({volume: 1}, 3000);
  // a couple of debugging
	//	console.log($(this).attr('alt') + ".mp3");
  //  console.log($(this).attr('id'));

  // Display song information
		$("#mainViewer").html($(this).attr('alt'));
//	console.log($(this).attr('alt'));

 // get activated button ID
var active_ID = $(this).attr("id");
// console.log(active_ID);

// Now, update the corresponding synonymous variable 'button$', increasing its value +1
window[active_ID]=eval(active_ID)+1;
// console.log(eval(active_ID));

// Finally, update the button value to appear as counter increasing
$("#"+active_ID).val(eval(active_ID));


});
