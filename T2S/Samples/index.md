###### Please enter your email ID and rate the generated audio files
<head>
    <link rel="stylesheet" href="w3.css">
    <title>Text To Singing MOS</title>
    <style>
         h1 {
            text-align: center;
            margin: 20px;
            }
  h3{
    text-align: center;
    text-justify: inter-word;
  }
  h6{
    text-align: justify;
    text-justify: inter-word;
  }
  .grrp{
  text-align: center;
  padding: 10px;
  margin: 10px;
  border: 1px solid #c6c6c6;
    }
  .grrp1{
  text-align: center;
  padding: 10px;
  margin: 10px;
    }
  .button1 {
  background-color: white;
  color: black;
  border: 2px solid #008CBA; /* Blue */
}
.button1:hover {
  background-color: #008CBA; /* Blue */
  color: white;
}
    </style>
</head>
<body>
<div class="grrp1">
  <form id="fs-frm" name="survey-form-test" accept-charset="utf-8" action="https://formspree.io/f/xaylrgvl" method="post">
    <fieldset id="fs-frm-inputs" style="border:0px solid black;">
      <label for="email-address">Email Address</label>
      <input type="email" name="_replyto" id="email-address" placeholder="email@domain.com" required=""><br><br>
      <p style="text-align:justify;background-color: lightblue; color: darkblue; "> <i> Listen to the target melody and target speaker's voice first. Then analyze synthesized song with two models - How well the synthesized song matches to target speaker's voice and how well it matches to the melody/tune of the target melody. Kindly listen to the Audio files of 4 different singers  and provide feedback on the synthesized waveforms produced using two systems.</i></p>
      <br>
      <!-- <table>
      <tr>
      <td>
       <div  style="background-color: lightblue;white-space:nowrap;height:30px;min-width: 240px">
                 Problem Statement in Malayalam</div>  
              <audio controls controlsList="nodownload" preload="none" style="height:30px"><source src="https://ismir21.github.io/T2S/Samples/Speech/Malayalam.ogg" type="audio/mpeg">audio not supported</audio>  
              </td>
              <td>
              <div  style="background-color: lightblue;white-space:nowrap;height:30px;min-width: 240px">
                 Problem Statement in English</div>  
              <audio controls controlsList="nodownload" preload="none" style="height:30px"><source src="https://ismir21.github.io/T2S/Samples/Speech/English.ogg" type="audio/mpeg">audio not supported</audio> 
              </td>
              </tr>
        </table>          -->
 <div class='grrp'>  
    <h3>Singer1</h3>
              <table border="0" style="font-size:16px">
              <tbody>
                <tr>                
                <th bgcolor="lightblue" style="white-space:nowrap;height:30px;min-width: 240px">
                 </th>               
                <th bgcolor="lightblue" style="white-space:nowrap;height:30px;min-width: 240px">
                 Synthesized Song with Model 1</th>                
                <th bgcolor="lightblue" style="white-space:nowrap;height:30px;min-width: 240px">
                 Synthesized Song with Model 2</th></tr>
              <tr>
              <td>
              <div  style="background-color: lightblue;white-space:nowrap;height:30px;min-width: 240px">
                 Lyrics</div> 
                 <div> Edelweiss, Edelweiss Every morning you greet me Small and white clean and bright You look happy to meet me Blossom of snow, may you bloom and grow Bloom and grow forever Edelweiss, Edelweiss Bless my homeland forever</div>
                    <div  style="background-color: lightblue;white-space:nowrap;height:30px;min-width: 240px">
                 Target Melody</div>  
              <audio controls controlsList="nodownload" preload="none" style="height:30px"><source src="https://ismir21.github.io/T2S/Samples/Recordings/1_msinging.wav" type="audio/mpeg">audio not supported</audio>            
              <div  style="background-color: lightblue;white-space:nowrap;height:30px;min-width: 240px">
                 Target Singer Voice</div>                  
                 <audio controls controlsList="nodownload" preload="none" style="height:30px"><source src="https://ismir21.github.io/T2S/Samples/Speech/Singer2_Voice.wav" type="audio/mpeg">audio not supported</audio> 
                </td>
              <td>
              <audio controls controlsList="nodownload" preload="none" style="height:30px"><source src="https://ismir21.github.io/T2S/Samples/WithoutGAN/SAMF/samf_1_sing.wav" type="audio/mpeg">audio not supported</audio>
              <div style="font-size:14px;text-align: left;">
              <table>
              <tr>
              <td>
              <label for="sim_mel">How well does synthesized song adapts to target melody</label></td>
              <td>
              <select name="sim_mel" id="sim_mel" required="">
                <option value="" selected disabled>Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br>
              </td>
              </tr>
              <tr>
              <td>
             <label for="sim_qlty">How would you rate the singing Quality (clarity)</label>
             </td>
             <td>
              <select name="sim_qlty" id="sim_qlty" required="">
                <option value="" selected disabled>Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br>
              </td>
              </tr>
              <tr>
              <td>
     <label for="synth_phoneme">How would you rate the phoneme quality of synthesized audio<br>
     </label></td>
     <td>
              <select name="synth_phoneme" id="synth_phoneme" required="">
                <option value="" selected disabled>Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br>
              </td>
              </tr>
              <tr>
              <td>
               <label for="synth_speaker">How well does synthesized song adapts to reference speaker voice<br></label>
               </td>
               <td>
              <select name="synth_speaker" id="synth_speaker" required="">
                <option value="" selected disabled>Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br> 
              </td>
              </tr>
              </table>
              </div>
                </td>
                 <td><audio controls controlsList="nodownload" preload="none" style="height:30px">
                  <source src="https://ismir21.github.io/T2S/Samples/WithGAN/SAMF/samf_1_sing.wav" type="audio/mpeg">audio not supported</audio>
                    <div style="font-size:14px;text-align: left;">
              <table>
              <tr>
              <td>
              <label for="sim_mel_t2s">How well does synthesized song adapts to target melody</label></td>
              <td>
              <select name="sim_mel_t2s" id="sim_mel_t2s" required="">
                <option value="" selected disabled>Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br>
              </td>
              </tr>
              <tr>
              <td>
             <label for="sim_qlty_t2s">How would you rate the singing Quality (clarity)</label>
             </td>
             <td>
              <select name="sim_qlty_t2s" id="sim_qlty_t2s" required="">
                <option value="" selected disabled>Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br>
              </td>
              </tr>
              <tr>
              <td>
     <label for="synth_phoneme_t2s">How would you rate the phoneme quality of synthesized audio<br>
     </label></td>
     <td>
              <select name="synth_phoneme_t2s" id="synth_phoneme_t2s" required="">
                <option value="" selected disabled>Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br>
              </td>
              </tr>
              <tr>
              <td>
               <label for="synth_speaker_t2s">How well does synthesized song adapts to reference speaker voice<br></label>
               </td>
               <td>
              <select name="synth_speaker_t2s" id="synth_speaker_t2s" required="">
                <option value="" selected disabled>Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br> 
              </td>
              </tr>
              </table>
              </div>
                  </td>
                  </tr>
              <tr>
              <td>
              <div  style="background-color: lightblue;white-space:nowrap;height:30px;min-width: 240px">
                 Lyrics</div> 
                 <div> Edelweiss, Edelweiss Every morning you greet me Small and white clean and bright You look happy to meet me Blossom of snow, may you bloom and grow Bloom and grow forever Edelweiss, Edelweiss Bless my homeland forever</div>
                    <div  style="background-color: lightblue;white-space:nowrap;height:30px;min-width: 240px">
                 Target Melody</div>  
              <audio controls controlsList="nodownload" preload="none" style="height:30px"><source src="https://ismir21.github.io/T2S/Samples/Recordings/1_mhumming.wav" type="audio/mpeg">audio not supported</audio>            
             </td>
              <td>
              <audio controls controlsList="nodownload" preload="none" style="height:30px"><source src="https://ismir21.github.io/T2S/Samples/WithoutGAN/SAMF/samf_1_hum.wav" type="audio/mpeg">audio not supported</audio>
              <div style="font-size:14px;text-align: left;">
              <table>
              <tr>
              <td>
              <label for="sim_mel">How well does synthesized song adapts to target melody</label></td>
              <td>
              <select name="sim_mel" id="sim_mel" required="">
                <option value="" selected disabled>Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br>
              </td>
              </tr>
              <tr>
              <td>
             <label for="sim_qlty">How would you rate the singing Quality (clarity)</label>
             </td>
             <td>
              <select name="sim_qlty" id="sim_qlty" required="">
                <option value="" selected disabled>Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br>
              </td>
              </tr>
              <tr>
              <td>
     <label for="synth_phoneme">How would you rate the phoneme quality of synthesized audio<br>
     </label></td>
     <td>
              <select name="synth_phoneme" id="synth_phoneme" required="">
                <option value="" selected disabled>Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br>
              </td>
              </tr>
              <tr>
              <td>
               <label for="synth_speaker">How well does synthesized song adapts to reference speaker voice<br></label>
               </td>
               <td>
              <select name="synth_speaker" id="synth_speaker" required="">
                <option value="" selected disabled>Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br> 
              </td>
              </tr>
              </table>
              </div>
                </td>
                 <td><audio controls controlsList="nodownload" preload="none" style="height:30px">
                  <source src="https://ismir21.github.io/T2S/Samples/WithGAN/SAMF/samf_1_hum.wav" type="audio/mpeg">audio not supported</audio>
                    <div style="font-size:14px;text-align: left;">
              <table>
              <tr>
              <td>
              <label for="sim_mel_t2s">How well does synthesized song adapts to target melody</label></td>
              <td>
              <select name="sim_mel_t2s" id="sim_mel_t2s" required="">
                <option value="" selected disabled>Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br>
              </td>
              </tr>
              <tr>
              <td>
             <label for="sim_qlty_t2s">How would you rate the singing Quality (clarity)</label>
             </td>
             <td>
              <select name="sim_qlty_t2s" id="sim_qlty_t2s" required="">
                <option value="" selected disabled>Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br>
              </td>
              </tr>
              <tr>
              <td>
     <label for="synth_phoneme_t2s">How would you rate the phoneme quality of synthesized audio<br>
     </label></td>
     <td>
              <select name="synth_phoneme_t2s" id="synth_phoneme_t2s" required="">
                <option value="" selected disabled>Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br>
              </td>
              </tr>
              <tr>
              <td>
               <label for="synth_speaker_t2s">How well does synthesized song adapts to reference speaker voice<br></label>
               </td>
               <td>
              <select name="synth_speaker_t2s" id="synth_speaker_t2s" required="">
                <option value="" selected disabled>Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br> 
              </td>
              </tr>
              </table>
              </div>
              </td>
              </tr>
               <tr>
              <td>
              <div  style="background-color: lightblue;white-space:nowrap;height:30px;min-width: 240px">
                 Lyrics</div> 
                 <div> Love in your eyes Sitting silent by my side</div>
                    <div  style="background-color: lightblue;white-space:nowrap;height:30px;min-width: 240px">
                 Target Melody</div>  
              <audio controls controlsList="nodownload" preload="none" style="height:30px"><source src="https://ismir21.github.io/T2S/Samples/Recordings/2_msinging.wav" type="audio/mpeg">audio not supported</audio>            
              </td>
              <td>
              <audio controls controlsList="nodownload" preload="none" style="height:30px"><source src="https://ismir21.github.io/T2S/Samples/WithoutGAN/SAMF/samf_2_sing.wav" type="audio/mpeg">audio not supported</audio>
              <div style="font-size:14px;text-align: left;">
              <table>
              <tr>
              <td>
              <label for="sim_mel">How well does synthesized song adapts to target melody</label></td>
              <td>
              <select name="sim_mel" id="sim_mel" required="">
                <option value="" selected disabled>Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br>
              </td>
              </tr>
              <tr>
              <td>
             <label for="sim_qlty">How would you rate the singing Quality (clarity)</label>
             </td>
             <td>
              <select name="sim_qlty" id="sim_qlty" required="">
                <option value="" selected disabled>Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br>
              </td>
              </tr>
              <tr>
              <td>
     <label for="synth_phoneme">How would you rate the phoneme quality of synthesized audio<br>
     </label></td>
     <td>
              <select name="synth_phoneme" id="synth_phoneme" required="">
                <option value="" selected disabled>Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br>
              </td>
              </tr>
              <tr>
              <td>
               <label for="synth_speaker">How well does synthesized song adapts to reference speaker voice<br></label>
               </td>
               <td>
              <select name="synth_speaker" id="synth_speaker" required="">
                <option value="" selected disabled>Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br> 
              </td>
              </tr>
              </table>
              </div>
                </td>
                 <td><audio controls controlsList="nodownload" preload="none" style="height:30px">
                  <source src="https://ismir21.github.io/T2S/Samples/WithGAN/SAMF/samf_2_sing.wav" type="audio/mpeg">audio not supported</audio>
                    <div style="font-size:14px;text-align: left;">
              <table>
              <tr>
              <td>
              <label for="sim_mel_t2s">How well does synthesized song adapts to target melody</label></td>
              <td>
              <select name="sim_mel_t2s" id="sim_mel_t2s" required="">
                <option value="" selected disabled>Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br>
              </td>
              </tr>
              <tr>
              <td>
             <label for="sim_qlty_t2s">How would you rate the singing Quality (clarity)</label>
             </td>
             <td>
              <select name="sim_qlty_t2s" id="sim_qlty_t2s" required="">
                <option value="" selected disabled>Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br>
              </td>
              </tr>
              <tr>
              <td>
     <label for="synth_phoneme_t2s">How would you rate the phoneme quality of synthesized audio<br>
     </label></td>
     <td>
              <select name="synth_phoneme_t2s" id="synth_phoneme_t2s" required="">
                <option value="" selected disabled>Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br>
              </td>
              </tr>
              <tr>
              <td>
               <label for="synth_speaker_t2s">How well does synthesized song adapts to reference speaker voice<br></label>
               </td>
               <td>
              <select name="synth_speaker_t2s" id="synth_speaker_t2s" required="">
                <option value="" selected disabled>Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br> 
              </td>
              </tr>
              </table>
              </div>
                  </td>
                  </tr>
                   <tr>
              <td>
              <div  style="background-color: lightblue;white-space:nowrap;height:30px;min-width: 240px">
                 Lyrics</div> 
                 <div> Love in your eyes Sitting silent by my side</div>
                    <div  style="background-color: lightblue;white-space:nowrap;height:30px;min-width: 240px">
                 Target Melody</div>  
              <audio controls controlsList="nodownload" preload="none" style="height:30px"><source src="https://ismir21.github.io/T2S/Samples/Recordings/2_mhumming.wav" type="audio/mpeg">audio not supported</audio>            
              </td>
              <td>
              <audio controls controlsList="nodownload" preload="none" style="height:30px"><source src="https://ismir21.github.io/T2S/Samples/WithoutGAN/SAMF/samf_2_hum.wav" type="audio/mpeg">audio not supported</audio>
              <div style="font-size:14px;text-align: left;">
              <table>
              <tr>
              <td>
              <label for="sim_mel">How well does synthesized song adapts to target melody</label></td>
              <td>
              <select name="sim_mel" id="sim_mel" required="">
                <option value="" selected disabled>Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br>
              </td>
              </tr>
              <tr>
              <td>
             <label for="sim_qlty">How would you rate the singing Quality (clarity)</label>
             </td>
             <td>
              <select name="sim_qlty" id="sim_qlty" required="">
                <option value="" selected disabled>Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br>
              </td>
              </tr>
              <tr>
              <td>
     <label for="synth_phoneme">How would you rate the phoneme quality of synthesized audio<br>
     </label></td>
     <td>
              <select name="synth_phoneme" id="synth_phoneme" required="">
                <option value="" selected disabled>Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br>
              </td>
              </tr>
              <tr>
              <td>
               <label for="synth_speaker">How well does synthesized song adapts to reference speaker voice<br></label>
               </td>
               <td>
              <select name="synth_speaker" id="synth_speaker" required="">
                <option value="" selected disabled>Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br> 
              </td>
              </tr>
              </table>
              </div>
                </td>
                 <td><audio controls controlsList="nodownload" preload="none" style="height:30px">
                  <source src="https://ismir21.github.io/T2S/Samples/WithGAN/SAMF/samf_2_hum.wav" type="audio/mpeg">audio not supported</audio>
                    <div style="font-size:14px;text-align: left;">
              <table>
              <tr>
              <td>
              <label for="sim_mel_t2s">How well does synthesized song adapts to target melody</label></td>
              <td>
              <select name="sim_mel_t2s" id="sim_mel_t2s" required="">
                <option value="" selected disabled>Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br>
              </td>
              </tr>
              <tr>
              <td>
             <label for="sim_qlty_t2s">How would you rate the singing Quality (clarity)</label>
             </td>
             <td>
              <select name="sim_qlty_t2s" id="sim_qlty_t2s" required="">
                <option value="" selected disabled>Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br>
              </td>
              </tr>
              <tr>
              <td>
     <label for="synth_phoneme_t2s">How would you rate the phoneme quality of synthesized audio<br>
     </label></td>
     <td>
              <select name="synth_phoneme_t2s" id="synth_phoneme_t2s" required="">
                <option value="" selected disabled>Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br>
              </td>
              </tr>
              <tr>
              <td>
               <label for="synth_speaker_t2s">How well does synthesized song adapts to reference speaker voice<br></label>
               </td>
               <td>
              <select name="synth_speaker_t2s" id="synth_speaker_t2s" required="">
                <option value="" selected disabled>Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br> 
              </td>
              </tr>
              </table>
              </div>
                  </td>
                  </tr>
                                 <tr>
              <td>
              <div  style="background-color: lightblue;white-space:nowrap;height:30px;min-width: 240px">
                 Lyrics</div> 
                 <div> I'm just a little bit caught in the middle Life is a maze, and love is a riddle</div>
                    <div  style="background-color: lightblue;white-space:nowrap;height:30px;min-width: 240px">
                 Target Melody</div>  
              <audio controls controlsList="nodownload" preload="none" style="height:30px"><source src="https://ismir21.github.io/T2S/Samples/Recordings/3_msinging.wav" type="audio/mpeg">audio not supported</audio>            
              </td>
              <td>
              <audio controls controlsList="nodownload" preload="none" style="height:30px"><source src="https://ismir21.github.io/T2S/Samples/WithoutGAN/SAMF/samf_3_sing.wav" type="audio/mpeg">audio not supported</audio>
              <div style="font-size:14px;text-align: left;">
              <table>
              <tr>
              <td>
              <label for="sim_mel">How well does synthesized song adapts to target melody</label></td>
              <td>
              <select name="sim_mel" id="sim_mel" required="">
                <option value="" selected disabled>Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br>
              </td>
              </tr>
              <tr>
              <td>
             <label for="sim_qlty">How would you rate the singing Quality (clarity)</label>
             </td>
             <td>
              <select name="sim_qlty" id="sim_qlty" required="">
                <option value="" selected disabled>Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br>
              </td>
              </tr>
              <tr>
              <td>
     <label for="synth_phoneme">How would you rate the phoneme quality of synthesized audio<br>
     </label></td>
     <td>
              <select name="synth_phoneme" id="synth_phoneme" required="">
                <option value="" selected disabled>Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br>
              </td>
              </tr>
              <tr>
              <td>
               <label for="synth_speaker">How well does synthesized song adapts to reference speaker voice<br></label>
               </td>
               <td>
              <select name="synth_speaker" id="synth_speaker" required="">
                <option value="" selected disabled>Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br> 
              </td>
              </tr>
              </table>
              </div>
                </td>
                 <td><audio controls controlsList="nodownload" preload="none" style="height:30px">
                  <source src="https://ismir21.github.io/T2S/Samples/WithGAN/SAMF/samf_3_sing.wav" type="audio/mpeg">audio not supported</audio>
                    <div style="font-size:14px;text-align: left;">
              <table>
              <tr>
              <td>
              <label for="sim_mel_t2s">How well does synthesized song adapts to target melody</label></td>
              <td>
              <select name="sim_mel_t2s" id="sim_mel_t2s" required="">
                <option value="" selected disabled>Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br>
              </td>
              </tr>
              <tr>
              <td>
             <label for="sim_qlty_t2s">How would you rate the singing Quality (clarity)</label>
             </td>
             <td>
              <select name="sim_qlty_t2s" id="sim_qlty_t2s" required="">
                <option value="" selected disabled>Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br>
              </td>
              </tr>
              <tr>
              <td>
     <label for="synth_phoneme_t2s">How would you rate the phoneme quality of synthesized audio<br>
     </label></td>
     <td>
              <select name="synth_phoneme_t2s" id="synth_phoneme_t2s" required="">
                <option value="" selected disabled>Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br>
              </td>
              </tr>
              <tr>
              <td>
               <label for="synth_speaker_t2s">How well does synthesized song adapts to reference speaker voice<br></label>
               </td>
               <td>
              <select name="synth_speaker_t2s" id="synth_speaker_t2s" required="">
                <option value="" selected disabled>Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br> 
              </td>
              </tr>
              </table>
              </div>
                  </td>
                  </tr>
                   <tr>
              <td>
              <div  style="background-color: lightblue;white-space:nowrap;height:30px;min-width: 240px">
                 Lyrics</div> 
                 <div> I'm just a little bit caught in the middle Life is a maze, and love is a riddle</div>
                    <div  style="background-color: lightblue;white-space:nowrap;height:30px;min-width: 240px">
                 Target Melody</div>  
              <audio controls controlsList="nodownload" preload="none" style="height:30px"><source src="https://ismir21.github.io/T2S/Samples/Recordings/3_mhumming.wav" type="audio/mpeg">audio not supported</audio>            
              </td>
              <td>
              <audio controls controlsList="nodownload" preload="none" style="height:30px"><source src="https://ismir21.github.io/T2S/Samples/WithoutGAN/SAMF/samf_3_hum.wav" type="audio/mpeg">audio not supported</audio>
              <div style="font-size:14px;text-align: left;">
              <table>
              <tr>
              <td>
              <label for="sim_mel">How well does synthesized song adapts to target melody</label></td>
              <td>
              <select name="sim_mel" id="sim_mel" required="">
                <option value="" selected disabled>Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br>
              </td>
              </tr>
              <tr>
              <td>
             <label for="sim_qlty">How would you rate the singing Quality (clarity)</label>
             </td>
             <td>
              <select name="sim_qlty" id="sim_qlty" required="">
                <option value="" selected disabled>Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br>
              </td>
              </tr>
              <tr>
              <td>
     <label for="synth_phoneme">How would you rate the phoneme quality of synthesized audio<br>
     </label></td>
     <td>
              <select name="synth_phoneme" id="synth_phoneme" required="">
                <option value="" selected disabled>Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br>
              </td>
              </tr>
              <tr>
              <td>
               <label for="synth_speaker">How well does synthesized song adapts to reference speaker voice<br></label>
               </td>
               <td>
              <select name="synth_speaker" id="synth_speaker" required="">
                <option value="" selected disabled>Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br> 
              </td>
              </tr>
              </table>
              </div>
                </td>
                 <td><audio controls controlsList="nodownload" preload="none" style="height:30px">
                  <source src="https://ismir21.github.io/T2S/Samples/WithGAN/SAMF/samf_3_hum.wav" type="audio/mpeg">audio not supported</audio>
                    <div style="font-size:14px;text-align: left;">
              <table>
              <tr>
              <td>
              <label for="sim_mel_t2s">How well does synthesized song adapts to target melody</label></td>
              <td>
              <select name="sim_mel_t2s" id="sim_mel_t2s" required="">
                <option value="" selected disabled>Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br>
              </td>
              </tr>
              <tr>
              <td>
             <label for="sim_qlty_t2s">How would you rate the singing Quality (clarity)</label>
             </td>
             <td>
              <select name="sim_qlty_t2s" id="sim_qlty_t2s" required="">
                <option value="" selected disabled>Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br>
              </td>
              </tr>
              <tr>
              <td>
     <label for="synth_phoneme_t2s">How would you rate the phoneme quality of synthesized audio<br>
     </label></td>
     <td>
              <select name="synth_phoneme_t2s" id="synth_phoneme_t2s" required="">
                <option value="" selected disabled>Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br>
              </td>
              </tr>
              <tr>
              <td>
               <label for="synth_speaker_t2s">How well does synthesized song adapts to reference speaker voice<br></label>
               </td>
               <td>
              <select name="synth_speaker_t2s" id="synth_speaker_t2s" required="">
                <option value="" selected disabled>Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br> 
              </td>
              </tr>
              </table>
              </div>
                  </td>
                  </tr>
                                 <tr>
              <td>
              <div  style="background-color: lightblue;white-space:nowrap;height:30px;min-width: 240px">
                 Lyrics</div> 
                 <div> Slow it down, make it stop Or else my heart is going to pop</div>
                    <div  style="background-color: lightblue;white-space:nowrap;height:30px;min-width: 240px">
                 Target Melody</div>  
              <audio controls controlsList="nodownload" preload="none" style="height:30px"><source src="https://ismir21.github.io/T2S/Samples/Recordings/4_msinging.wav" type="audio/mpeg">audio not supported</audio>            
              </td>
              <td>
              <audio controls controlsList="nodownload" preload="none" style="height:30px"><source src="https://ismir21.github.io/T2S/Samples/WithoutGAN/SAMF/samf_4_sing.wav" type="audio/mpeg">audio not supported</audio>
              <div style="font-size:14px;text-align: left;">
              <table>
              <tr>
              <td>
              <label for="sim_mel">How well does synthesized song adapts to target melody</label></td>
              <td>
              <select name="sim_mel" id="sim_mel" required="">
                <option value="" selected disabled>Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br>
              </td>
              </tr>
              <tr>
              <td>
             <label for="sim_qlty">How would you rate the singing Quality (clarity)</label>
             </td>
             <td>
              <select name="sim_qlty" id="sim_qlty" required="">
                <option value="" selected disabled>Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br>
              </td>
              </tr>
              <tr>
              <td>
     <label for="synth_phoneme">How would you rate the phoneme quality of synthesized audio<br>
     </label></td>
     <td>
              <select name="synth_phoneme" id="synth_phoneme" required="">
                <option value="" selected disabled>Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br>
              </td>
              </tr>
              <tr>
              <td>
               <label for="synth_speaker">How well does synthesized song adapts to reference speaker voice<br></label>
               </td>
               <td>
              <select name="synth_speaker" id="synth_speaker" required="">
                <option value="" selected disabled>Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br> 
              </td>
              </tr>
              </table>
              </div>
                </td>
                 <td><audio controls controlsList="nodownload" preload="none" style="height:30px">
                  <source src="https://ismir21.github.io/T2S/Samples/WithGAN/SAMF/samf_4_sing.wav" type="audio/mpeg">audio not supported</audio>
                    <div style="font-size:14px;text-align: left;">
              <table>
              <tr>
              <td>
              <label for="sim_mel_t2s">How well does synthesized song adapts to target melody</label></td>
              <td>
              <select name="sim_mel_t2s" id="sim_mel_t2s" required="">
                <option value="" selected disabled>Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br>
              </td>
              </tr>
              <tr>
              <td>
             <label for="sim_qlty_t2s">How would you rate the singing Quality (clarity)</label>
             </td>
             <td>
              <select name="sim_qlty_t2s" id="sim_qlty_t2s" required="">
                <option value="" selected disabled>Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br>
              </td>
              </tr>
              <tr>
              <td>
     <label for="synth_phoneme_t2s">How would you rate the phoneme quality of synthesized audio<br>
     </label></td>
     <td>
              <select name="synth_phoneme_t2s" id="synth_phoneme_t2s" required="">
                <option value="" selected disabled>Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br>
              </td>
              </tr>
              <tr>
              <td>
               <label for="synth_speaker_t2s">How well does synthesized song adapts to reference speaker voice<br></label>
               </td>
               <td>
              <select name="synth_speaker_t2s" id="synth_speaker_t2s" required="">
                <option value="" selected disabled>Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br> 
              </td>
              </tr>
              </table>
              </div>
                  </td>
                  </tr>
                   <tr>
              <td>
              <div  style="background-color: lightblue;white-space:nowrap;height:30px;min-width: 240px">
                 Lyrics</div> 
                 <div> Slow it down, make it stop Or else my heart is going to pop</div>
                    <div  style="background-color: lightblue;white-space:nowrap;height:30px;min-width: 240px">
                 Target Melody</div>  
              <audio controls controlsList="nodownload" preload="none" style="height:30px"><source src="https://ismir21.github.io/T2S/Samples/Recordings/4_mhumming.wav" type="audio/mpeg">audio not supported</audio>            
              </td>
              <td>
              <audio controls controlsList="nodownload" preload="none" style="height:30px"><source src="https://ismir21.github.io/T2S/Samples/WithoutGAN/SAMF/samf_4_hum.wav" type="audio/mpeg">audio not supported</audio>
              <div style="font-size:14px;text-align: left;">
              <table>
              <tr>
              <td>
              <label for="sim_mel">How well does synthesized song adapts to target melody</label></td>
              <td>
              <select name="sim_mel" id="sim_mel" required="">
                <option value="" selected disabled>Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br>
              </td>
              </tr>
              <tr>
              <td>
             <label for="sim_qlty">How would you rate the singing Quality (clarity)</label>
             </td>
             <td>
              <select name="sim_qlty" id="sim_qlty" required="">
                <option value="" selected disabled>Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br>
              </td>
              </tr>
              <tr>
              <td>
     <label for="synth_phoneme">How would you rate the phoneme quality of synthesized audio<br>
     </label></td>
     <td>
              <select name="synth_phoneme" id="synth_phoneme" required="">
                <option value="" selected disabled>Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br>
              </td>
              </tr>
              <tr>
              <td>
               <label for="synth_speaker">How well does synthesized song adapts to reference speaker voice<br></label>
               </td>
               <td>
              <select name="synth_speaker" id="synth_speaker" required="">
                <option value="" selected disabled>Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br> 
              </td>
              </tr>
              </table>
              </div>
                </td>
                 <td><audio controls controlsList="nodownload" preload="none" style="height:30px">
                  <source src="https://ismir21.github.io/T2S/Samples/WithGAN/SAMF/samf_4_hum.wav" type="audio/mpeg">audio not supported</audio>
                    <div style="font-size:14px;text-align: left;">
              <table>
              <tr>
              <td>
              <label for="sim_mel_t2s">How well does synthesized song adapts to target melody</label></td>
              <td>
              <select name="sim_mel_t2s" id="sim_mel_t2s" required="">
                <option value="" selected disabled>Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br>
              </td>
              </tr>
              <tr>
              <td>
             <label for="sim_qlty_t2s">How would you rate the singing Quality (clarity)</label>
             </td>
             <td>
              <select name="sim_qlty_t2s" id="sim_qlty_t2s" required="">
                <option value="" selected disabled>Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br>
              </td>
              </tr>
              <tr>
              <td>
     <label for="synth_phoneme_t2s">How would you rate the phoneme quality of synthesized audio<br>
     </label></td>
     <td>
              <select name="synth_phoneme_t2s" id="synth_phoneme_t2s" required="">
                <option value="" selected disabled>Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br>
              </td>
              </tr>
              <tr>
              <td>
               <label for="synth_speaker_t2s">How well does synthesized song adapts to reference speaker voice<br></label>
               </td>
               <td>
              <select name="synth_speaker_t2s" id="synth_speaker_t2s" required="">
                <option value="" selected disabled>Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br> 
              </td>
              </tr>
              </table>
              </div>
                  </td>
                  </tr>
                                 <tr>
              <td>
              <div  style="background-color: lightblue;white-space:nowrap;height:30px;min-width: 240px">
                 Lyrics</div> 
                 <div> Love me tender,Love me sweet,Never let me go</div>
                    <div  style="background-color: lightblue;white-space:nowrap;height:30px;min-width: 240px">
                 Target Melody</div>  
              <audio controls controlsList="nodownload" preload="none" style="height:30px"><source src="https://ismir21.github.io/T2S/Samples/Recordings/5_msinging.wav" type="audio/mpeg">audio not supported</audio>            
              </td>
              <td>
              <audio controls controlsList="nodownload" preload="none" style="height:30px"><source src="https://ismir21.github.io/T2S/Samples/WithoutGAN/SAMF/samf_5_sing.wav" type="audio/mpeg">audio not supported</audio>
              <div style="font-size:14px;text-align: left;">
              <table>
              <tr>
              <td>
              <label for="sim_mel">How well does synthesized song adapts to target melody</label></td>
              <td>
              <select name="sim_mel" id="sim_mel" required="">
                <option value="" selected disabled>Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br>
              </td>
              </tr>
              <tr>
              <td>
             <label for="sim_qlty">How would you rate the singing Quality (clarity)</label>
             </td>
             <td>
              <select name="sim_qlty" id="sim_qlty" required="">
                <option value="" selected disabled>Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br>
              </td>
              </tr>
              <tr>
              <td>
     <label for="synth_phoneme">How would you rate the phoneme quality of synthesized audio<br>
     </label></td>
     <td>
              <select name="synth_phoneme" id="synth_phoneme" required="">
                <option value="" selected disabled>Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br>
              </td>
              </tr>
              <tr>
              <td>
               <label for="synth_speaker">How well does synthesized song adapts to reference speaker voice<br></label>
               </td>
               <td>
              <select name="synth_speaker" id="synth_speaker" required="">
                <option value="" selected disabled>Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br> 
              </td>
              </tr>
              </table>
              </div>
                </td>
                 <td><audio controls controlsList="nodownload" preload="none" style="height:30px">
                  <source src="https://ismir21.github.io/T2S/Samples/WithGAN/SAMF/samf_5_sing.wav" type="audio/mpeg">audio not supported</audio>
                    <div style="font-size:14px;text-align: left;">
              <table>
              <tr>
              <td>
              <label for="sim_mel_t2s">How well does synthesized song adapts to target melody</label></td>
              <td>
              <select name="sim_mel_t2s" id="sim_mel_t2s" required="">
                <option value="" selected disabled>Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br>
              </td>
              </tr>
              <tr>
              <td>
             <label for="sim_qlty_t2s">How would you rate the singing Quality (clarity)</label>
             </td>
             <td>
              <select name="sim_qlty_t2s" id="sim_qlty_t2s" required="">
                <option value="" selected disabled>Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br>
              </td>
              </tr>
              <tr>
              <td>
     <label for="synth_phoneme_t2s">How would you rate the phoneme quality of synthesized audio<br>
     </label></td>
     <td>
              <select name="synth_phoneme_t2s" id="synth_phoneme_t2s" required="">
                <option value="" selected disabled>Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br>
              </td>
              </tr>
              <tr>
              <td>
               <label for="synth_speaker_t2s">How well does synthesized song adapts to reference speaker voice<br></label>
               </td>
               <td>
              <select name="synth_speaker_t2s" id="synth_speaker_t2s" required="">
                <option value="" selected disabled>Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br> 
              </td>
              </tr>
              </table>
              </div>
                  </td>
                  </tr>
                   <tr>
              <td>
              <div  style="background-color: lightblue;white-space:nowrap;height:30px;min-width: 240px">
                 Lyrics</div> 
                 <div> Love me tender,Love me sweet,Never let me go</div>
                    <div  style="background-color: lightblue;white-space:nowrap;height:30px;min-width: 240px">
                 Target Melody</div>  
              <audio controls controlsList="nodownload" preload="none" style="height:30px"><source src="https://ismir21.github.io/T2S/Samples/Recordings/5_mhumming.wav" type="audio/mpeg">audio not supported</audio>            
              </td>
              <td>
              <audio controls controlsList="nodownload" preload="none" style="height:30px"><source src="https://ismir21.github.io/T2S/Samples/WithoutGAN/SAMF/samf_5_hum.wav" type="audio/mpeg">audio not supported</audio>
              <div style="font-size:14px;text-align: left;">
              <table>
              <tr>
              <td>
              <label for="sim_mel">How well does synthesized song adapts to target melody</label></td>
              <td>
              <select name="sim_mel" id="sim_mel" required="">
                <option value="" selected disabled>Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br>
              </td>
              </tr>
              <tr>
              <td>
             <label for="sim_qlty">How would you rate the singing Quality (clarity)</label>
             </td>
             <td>
              <select name="sim_qlty" id="sim_qlty" required="">
                <option value="" selected disabled>Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br>
              </td>
              </tr>
              <tr>
              <td>
     <label for="synth_phoneme">How would you rate the phoneme quality of synthesized audio<br>
     </label></td>
     <td>
              <select name="synth_phoneme" id="synth_phoneme" required="">
                <option value="" selected disabled>Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br>
              </td>
              </tr>
              <tr>
              <td>
               <label for="synth_speaker">How well does synthesized song adapts to reference speaker voice<br></label>
               </td>
               <td>
              <select name="synth_speaker" id="synth_speaker" required="">
                <option value="" selected disabled>Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br> 
              </td>
              </tr>
              </table>
              </div>
                </td>
                 <td><audio controls controlsList="nodownload" preload="none" style="height:30px">
                  <source src="https://ismir21.github.io/T2S/Samples/WithGAN/SAMF/samf_5_hum.wav" type="audio/mpeg">audio not supported</audio>
                    <div style="font-size:14px;text-align: left;">
              <table>
              <tr>
              <td>
              <label for="sim_mel_t2s">How well does synthesized song adapts to target melody</label></td>
              <td>
              <select name="sim_mel_t2s" id="sim_mel_t2s" required="">
                <option value="" selected disabled>Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br>
              </td>
              </tr>
              <tr>
              <td>
             <label for="sim_qlty_t2s">How would you rate the singing Quality (clarity)</label>
             </td>
             <td>
              <select name="sim_qlty_t2s" id="sim_qlty_t2s" required="">
                <option value="" selected disabled>Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br>
              </td>
              </tr>
              <tr>
              <td>
     <label for="synth_phoneme_t2s">How would you rate the phoneme quality of synthesized audio<br>
     </label></td>
     <td>
              <select name="synth_phoneme_t2s" id="synth_phoneme_t2s" required="">
                <option value="" selected disabled>Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br>
              </td>
              </tr>
              <tr>
              <td>
               <label for="synth_speaker_t2s">How well does synthesized song adapts to reference speaker voice<br></label>
               </td>
               <td>
              <select name="synth_speaker_t2s" id="synth_speaker_t2s" required="">
                <option value="" selected disabled>Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br> 
              </td>
              </tr>
              </table>
              </div>
                  </td>
                  </tr>
              </tbody></table>  
   </div> 
  <div class='grrp'>  
    <h3>Singer2</h3>
          <table border="0" style="font-size:16px">
              <tbody>
                <tr>                
                <th bgcolor="lightblue" style="white-space:nowrap;height:30px;min-width: 240px">
                 </th>               
                <th bgcolor="lightblue" style="white-space:nowrap;height:30px;min-width: 240px">
                 Synthesized Song with Model 1</th>                
                <th bgcolor="lightblue" style="white-space:nowrap;height:30px;min-width: 240px">
                 Synthesized Song with Model 2</th></tr>
              <tr>
              <td>
              <div  style="background-color: lightblue;white-space:nowrap;height:30px;min-width: 240px">
                 Lyrics</div> 
                 <div> Edelweiss, Edelweiss Every morning you greet me</div>
                    <div  style="background-color: lightblue;white-space:nowrap;height:30px;min-width: 240px">
                 Target Melody</div>  
              <audio controls controlsList="nodownload" preload="none" style="height:30px"><source src="https://ismir21.github.io/T2S/Samples/Recordings/1_singing.mp3" type="audio/mpeg">audio not supported</audio>            
              <div  style="background-color: lightblue;white-space:nowrap;height:30px;min-width: 240px">
                 Target Singer Voice</div>                  
                 <audio controls controlsList="nodownload" preload="none" style="height:30px"><source src="https://ismir21.github.io/T2S/Singer_1/Singer1_Voice.wav" type="audio/mpeg">audio not supported</audio> 
                </td>
              <td>
              <audio controls controlsList="nodownload" preload="none" style="height:30px"><source src="https://ismir21.github.io/T2S/Samples/WithoutGAN/ADIZ/adiz_1_sing.wav" type="audio/mpeg">audio not supported</audio>
              <div style="font-size:14px;text-align: left;">
              <table>
              <tr>
              <td>
              <label for="sim_mel">How well does synthesized song adapts to target melody</label></td>
              <td>
              <select name="sim_mel" id="sim_mel" required="">
                <option value="" selected disabled>Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br>
              </td>
              </tr>
              <tr>
              <td>
             <label for="sim_qlty">How would you rate the singing Quality (clarity)</label>
             </td>
             <td>
              <select name="sim_qlty" id="sim_qlty" required="">
                <option value="" selected disabled>Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br>
              </td>
              </tr>
              <tr>
              <td>
     <label for="synth_phoneme">How would you rate the phoneme quality of synthesized audio<br>
     </label></td>
     <td>
              <select name="synth_phoneme" id="synth_phoneme" required="">
                <option value="" selected disabled>Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br>
              </td>
              </tr>
              <tr>
              <td>
               <label for="synth_speaker">How well does synthesized song adapts to reference speaker voice<br></label>
               </td>
               <td>
              <select name="synth_speaker" id="synth_speaker" required="">
                <option value="" selected disabled>Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br> 
              </td>
              </tr>
              </table>
              </div>
                </td>
                 <td><audio controls controlsList="nodownload" preload="none" style="height:30px">
                  <source src="https://ismir21.github.io/T2S/Samples/WithGAN/ADIZ/adiz_1_sing.wav" type="audio/mpeg">audio not supported</audio>
                    <div style="font-size:14px;text-align: left;">
              <table>
              <tr>
              <td>
              <label for="sim_mel_t2s">How well does synthesized song adapts to target melody</label></td>
              <td>
              <select name="sim_mel_t2s" id="sim_mel_t2s" required="">
                <option value="" selected disabled>Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br>
              </td>
              </tr>
              <tr>
              <td>
             <label for="sim_qlty_t2s">How would you rate the singing Quality (clarity)</label>
             </td>
             <td>
              <select name="sim_qlty_t2s" id="sim_qlty_t2s" required="">
                <option value="" selected disabled>Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br>
              </td>
              </tr>
              <tr>
              <td>
     <label for="synth_phoneme_t2s">How would you rate the phoneme quality of synthesized audio<br>
     </label></td>
     <td>
              <select name="synth_phoneme_t2s" id="synth_phoneme_t2s" required="">
                <option value="" selected disabled>Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br>
              </td>
              </tr>
              <tr>
              <td>
               <label for="synth_speaker_t2s">How well does synthesized song adapts to reference speaker voice<br></label>
               </td>
               <td>
              <select name="synth_speaker_t2s" id="synth_speaker_t2s" required="">
                <option value="" selected disabled>Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br> 
              </td>
              </tr>
              </table>
              </div>
                  </td>
                  </tr>
              <tr>
              <td>
              <div  style="background-color: lightblue;white-space:nowrap;height:30px;min-width: 240px">
                 Lyrics</div> 
                 <div> Edelweiss, Edelweiss Every morning you greet me</div>
                    <div  style="background-color: lightblue;white-space:nowrap;height:30px;min-width: 240px">
                 Target Melody</div>  
              <audio controls controlsList="nodownload" preload="none" style="height:30px"><source src="https://ismir21.github.io/T2S/Samples/Recordings/1_humming.mp3" type="audio/mpeg">audio not supported</audio>            
             </td>
              <td>
              <audio controls controlsList="nodownload" preload="none" style="height:30px"><source src="https://ismir21.github.io/T2S/Samples/WithoutGAN/ADIZ/adiz_1_hum.wav" type="audio/mpeg">audio not supported</audio>
              <div style="font-size:14px;text-align: left;">
              <table>
              <tr>
              <td>
              <label for="sim_mel">How well does synthesized song adapts to target melody</label></td>
              <td>
              <select name="sim_mel" id="sim_mel" required="">
                <option value="" selected disabled>Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br>
              </td>
              </tr>
              <tr>
              <td>
             <label for="sim_qlty">How would you rate the singing Quality (clarity)</label>
             </td>
             <td>
              <select name="sim_qlty" id="sim_qlty" required="">
                <option value="" selected disabled>Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br>
              </td>
              </tr>
              <tr>
              <td>
     <label for="synth_phoneme">How would you rate the phoneme quality of synthesized audio<br>
     </label></td>
     <td>
              <select name="synth_phoneme" id="synth_phoneme" required="">
                <option value="" selected disabled>Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br>
              </td>
              </tr>
              <tr>
              <td>
               <label for="synth_speaker">How well does synthesized song adapts to reference speaker voice<br></label>
               </td>
               <td>
              <select name="synth_speaker" id="synth_speaker" required="">
                <option value="" selected disabled>Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br> 
              </td>
              </tr>
              </table>
              </div>
                </td>
                 <td><audio controls controlsList="nodownload" preload="none" style="height:30px">
                  <source src="https://ismir21.github.io/T2S/Samples/WithGAN/ADIZ/adiz_1_hum.wav" type="audio/mpeg">audio not supported</audio>
                    <div style="font-size:14px;text-align: left;">
              <table>
              <tr>
              <td>
              <label for="sim_mel_t2s">How well does synthesized song adapts to target melody</label></td>
              <td>
              <select name="sim_mel_t2s" id="sim_mel_t2s" required="">
                <option value="" selected disabled>Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br>
              </td>
              </tr>
              <tr>
              <td>
             <label for="sim_qlty_t2s">How would you rate the singing Quality (clarity)</label>
             </td>
             <td>
              <select name="sim_qlty_t2s" id="sim_qlty_t2s" required="">
                <option value="" selected disabled>Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br>
              </td>
              </tr>
              <tr>
              <td>
     <label for="synth_phoneme_t2s">How would you rate the phoneme quality of synthesized audio<br>
     </label></td>
     <td>
              <select name="synth_phoneme_t2s" id="synth_phoneme_t2s" required="">
                <option value="" selected disabled>Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br>
              </td>
              </tr>
              <tr>
              <td>
               <label for="synth_speaker_t2s">How well does synthesized song adapts to reference speaker voice<br></label>
               </td>
               <td>
              <select name="synth_speaker_t2s" id="synth_speaker_t2s" required="">
                <option value="" selected disabled>Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br> 
              </td>
              </tr>
              </table>
              </div>
              </td>
              </tr>
               <tr>
              <td>
              <div  style="background-color: lightblue;white-space:nowrap;height:30px;min-width: 240px">
                 Lyrics</div> 
                 <div> Love in your eyes Sitting silent by my side</div>
                    <div  style="background-color: lightblue;white-space:nowrap;height:30px;min-width: 240px">
                 Target Melody</div>  
              <audio controls controlsList="nodownload" preload="none" style="height:30px"><source src="https://ismir21.github.io/T2S/Samples/Recordings/2_singing.mp3" type="audio/mpeg">audio not supported</audio>            
              </td>
              <td>
              <audio controls controlsList="nodownload" preload="none" style="height:30px"><source src="https://ismir21.github.io/T2S/Samples/WithoutGAN/ADIZ/adiz_2_sing.wav" type="audio/mpeg">audio not supported</audio>
              <div style="font-size:14px;text-align: left;">
              <table>
              <tr>
              <td>
              <label for="sim_mel">How well does synthesized song adapts to target melody</label></td>
              <td>
              <select name="sim_mel" id="sim_mel" required="">
                <option value="" selected disabled>Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br>
              </td>
              </tr>
              <tr>
              <td>
             <label for="sim_qlty">How would you rate the singing Quality (clarity)</label>
             </td>
             <td>
              <select name="sim_qlty" id="sim_qlty" required="">
                <option value="" selected disabled>Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br>
              </td>
              </tr>
              <tr>
              <td>
     <label for="synth_phoneme">How would you rate the phoneme quality of synthesized audio<br>
     </label></td>
     <td>
              <select name="synth_phoneme" id="synth_phoneme" required="">
                <option value="" selected disabled>Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br>
              </td>
              </tr>
              <tr>
              <td>
               <label for="synth_speaker">How well does synthesized song adapts to reference speaker voice<br></label>
               </td>
               <td>
              <select name="synth_speaker" id="synth_speaker" required="">
                <option value="" selected disabled>Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br> 
              </td>
              </tr>
              </table>
              </div>
                </td>
                 <td><audio controls controlsList="nodownload" preload="none" style="height:30px">
                  <source src="https://ismir21.github.io/T2S/Samples/WithGAN/ADIZ/adiz_2_sing.wav" type="audio/mpeg">audio not supported</audio>
                    <div style="font-size:14px;text-align: left;">
              <table>
              <tr>
              <td>
              <label for="sim_mel_t2s">How well does synthesized song adapts to target melody</label></td>
              <td>
              <select name="sim_mel_t2s" id="sim_mel_t2s" required="">
                <option value="" selected disabled>Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br>
              </td>
              </tr>
              <tr>
              <td>
             <label for="sim_qlty_t2s">How would you rate the singing Quality (clarity)</label>
             </td>
             <td>
              <select name="sim_qlty_t2s" id="sim_qlty_t2s" required="">
                <option value="" selected disabled>Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br>
              </td>
              </tr>
              <tr>
              <td>
     <label for="synth_phoneme_t2s">How would you rate the phoneme quality of synthesized audio<br>
     </label></td>
     <td>
              <select name="synth_phoneme_t2s" id="synth_phoneme_t2s" required="">
                <option value="" selected disabled>Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br>
              </td>
              </tr>
              <tr>
              <td>
               <label for="synth_speaker_t2s">How well does synthesized song adapts to reference speaker voice<br></label>
               </td>
               <td>
              <select name="synth_speaker_t2s" id="synth_speaker_t2s" required="">
                <option value="" selected disabled>Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br> 
              </td>
              </tr>
              </table>
              </div>
                  </td>
                  </tr>
                   <tr>
              <td>
              <div  style="background-color: lightblue;white-space:nowrap;height:30px;min-width: 240px">
                 Lyrics</div> 
                 <div> Love in your eyes Sitting silent by my side</div>
                    <div  style="background-color: lightblue;white-space:nowrap;height:30px;min-width: 240px">
                 Target Melody</div>  
              <audio controls controlsList="nodownload" preload="none" style="height:30px"><source src="https://ismir21.github.io/T2S/Samples/Recordings/2_humming.mp3" type="audio/mpeg">audio not supported</audio>            
              </td>
              <td>
              <audio controls controlsList="nodownload" preload="none" style="height:30px"><source src="https://ismir21.github.io/T2S/Samples/WithoutGAN/ADIZ/adiz_2_hum.wav" type="audio/mpeg">audio not supported</audio>
              <div style="font-size:14px;text-align: left;">
              <table>
              <tr>
              <td>
              <label for="sim_mel">How well does synthesized song adapts to target melody</label></td>
              <td>
              <select name="sim_mel" id="sim_mel" required="">
                <option value="" selected disabled>Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br>
              </td>
              </tr>
              <tr>
              <td>
             <label for="sim_qlty">How would you rate the singing Quality (clarity)</label>
             </td>
             <td>
              <select name="sim_qlty" id="sim_qlty" required="">
                <option value="" selected disabled>Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br>
              </td>
              </tr>
              <tr>
              <td>
     <label for="synth_phoneme">How would you rate the phoneme quality of synthesized audio<br>
     </label></td>
     <td>
              <select name="synth_phoneme" id="synth_phoneme" required="">
                <option value="" selected disabled>Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br>
              </td>
              </tr>
              <tr>
              <td>
               <label for="synth_speaker">How well does synthesized song adapts to reference speaker voice<br></label>
               </td>
               <td>
              <select name="synth_speaker" id="synth_speaker" required="">
                <option value="" selected disabled>Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br> 
              </td>
              </tr>
              </table>
              </div>
                </td>
                 <td><audio controls controlsList="nodownload" preload="none" style="height:30px">
                  <source src="https://ismir21.github.io/T2S/Samples/WithGAN/ADIZ/adiz_2_hum.wav" type="audio/mpeg">audio not supported</audio>
                    <div style="font-size:14px;text-align: left;">
              <table>
              <tr>
              <td>
              <label for="sim_mel_t2s">How well does synthesized song adapts to target melody</label></td>
              <td>
              <select name="sim_mel_t2s" id="sim_mel_t2s" required="">
                <option value="" selected disabled>Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br>
              </td>
              </tr>
              <tr>
              <td>
             <label for="sim_qlty_t2s">How would you rate the singing Quality (clarity)</label>
             </td>
             <td>
              <select name="sim_qlty_t2s" id="sim_qlty_t2s" required="">
                <option value="" selected disabled>Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br>
              </td>
              </tr>
              <tr>
              <td>
     <label for="synth_phoneme_t2s">How would you rate the phoneme quality of synthesized audio<br>
     </label></td>
     <td>
              <select name="synth_phoneme_t2s" id="synth_phoneme_t2s" required="">
                <option value="" selected disabled>Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br>
              </td>
              </tr>
              <tr>
              <td>
               <label for="synth_speaker_t2s">How well does synthesized song adapts to reference speaker voice<br></label>
               </td>
               <td>
              <select name="synth_speaker_t2s" id="synth_speaker_t2s" required="">
                <option value="" selected disabled>Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br> 
              </td>
              </tr>
              </table>
              </div>
                  </td>
                  </tr>
                                 <tr>
              <td>
              <div  style="background-color: lightblue;white-space:nowrap;height:30px;min-width: 240px">
                 Lyrics</div> 
                 <div> I'm just a little bit caught in the middle Life is a maze, and love is a riddle</div>
                    <div  style="background-color: lightblue;white-space:nowrap;height:30px;min-width: 240px">
                 Target Melody</div>  
              <audio controls controlsList="nodownload" preload="none" style="height:30px"><source src="https://ismir21.github.io/T2S/Samples/Recordings/3_singing.mp3" type="audio/mpeg">audio not supported</audio>            
              </td>
              <td>
              <audio controls controlsList="nodownload" preload="none" style="height:30px"><source src="https://ismir21.github.io/T2S/Samples/WithoutGAN/ADIZ/adiz_3_sing.wav" type="audio/mpeg">audio not supported</audio>
              <div style="font-size:14px;text-align: left;">
              <table>
              <tr>
              <td>
              <label for="sim_mel">How well does synthesized song adapts to target melody</label></td>
              <td>
              <select name="sim_mel" id="sim_mel" required="">
                <option value="" selected disabled>Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br>
              </td>
              </tr>
              <tr>
              <td>
             <label for="sim_qlty">How would you rate the singing Quality (clarity)</label>
             </td>
             <td>
              <select name="sim_qlty" id="sim_qlty" required="">
                <option value="" selected disabled>Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br>
              </td>
              </tr>
              <tr>
              <td>
     <label for="synth_phoneme">How would you rate the phoneme quality of synthesized audio<br>
     </label></td>
     <td>
              <select name="synth_phoneme" id="synth_phoneme" required="">
                <option value="" selected disabled>Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br>
              </td>
              </tr>
              <tr>
              <td>
               <label for="synth_speaker">How well does synthesized song adapts to reference speaker voice<br></label>
               </td>
               <td>
              <select name="synth_speaker" id="synth_speaker" required="">
                <option value="" selected disabled>Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br> 
              </td>
              </tr>
              </table>
              </div>
                </td>
                 <td><audio controls controlsList="nodownload" preload="none" style="height:30px">
                  <source src="https://ismir21.github.io/T2S/Samples/WithGAN/ADIZ/adiz_3_sing.wav" type="audio/mpeg">audio not supported</audio>
                    <div style="font-size:14px;text-align: left;">
              <table>
              <tr>
              <td>
              <label for="sim_mel_t2s">How well does synthesized song adapts to target melody</label></td>
              <td>
              <select name="sim_mel_t2s" id="sim_mel_t2s" required="">
                <option value="" selected disabled>Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br>
              </td>
              </tr>
              <tr>
              <td>
             <label for="sim_qlty_t2s">How would you rate the singing Quality (clarity)</label>
             </td>
             <td>
              <select name="sim_qlty_t2s" id="sim_qlty_t2s" required="">
                <option value="" selected disabled>Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br>
              </td>
              </tr>
              <tr>
              <td>
     <label for="synth_phoneme_t2s">How would you rate the phoneme quality of synthesized audio<br>
     </label></td>
     <td>
              <select name="synth_phoneme_t2s" id="synth_phoneme_t2s" required="">
                <option value="" selected disabled>Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br>
              </td>
              </tr>
              <tr>
              <td>
               <label for="synth_speaker_t2s">How well does synthesized song adapts to reference speaker voice<br></label>
               </td>
               <td>
              <select name="synth_speaker_t2s" id="synth_speaker_t2s" required="">
                <option value="" selected disabled>Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br> 
              </td>
              </tr>
              </table>
              </div>
                  </td>
                  </tr>
                   <tr>
              <td>
              <div  style="background-color: lightblue;white-space:nowrap;height:30px;min-width: 240px">
                 Lyrics</div> 
                 <div> I'm just a little bit caught in the middle Life is a maze, and love is a riddle</div>
                    <div  style="background-color: lightblue;white-space:nowrap;height:30px;min-width: 240px">
                 Target Melody</div>  
              <audio controls controlsList="nodownload" preload="none" style="height:30px"><source src="https://ismir21.github.io/T2S/Samples/Recordings/3_humming.mp3" type="audio/mpeg">audio not supported</audio>            
              </td>
              <td>
              <audio controls controlsList="nodownload" preload="none" style="height:30px"><source src="https://ismir21.github.io/T2S/Samples/WithoutGAN/ADIZ/adiz_3_hum.wav" type="audio/mpeg">audio not supported</audio>
              <div style="font-size:14px;text-align: left;">
              <table>
              <tr>
              <td>
              <label for="sim_mel">How well does synthesized song adapts to target melody</label></td>
              <td>
              <select name="sim_mel" id="sim_mel" required="">
                <option value="" selected disabled>Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br>
              </td>
              </tr>
              <tr>
              <td>
             <label for="sim_qlty">How would you rate the singing Quality (clarity)</label>
             </td>
             <td>
              <select name="sim_qlty" id="sim_qlty" required="">
                <option value="" selected disabled>Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br>
              </td>
              </tr>
              <tr>
              <td>
     <label for="synth_phoneme">How would you rate the phoneme quality of synthesized audio<br>
     </label></td>
     <td>
              <select name="synth_phoneme" id="synth_phoneme" required="">
                <option value="" selected disabled>Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br>
              </td>
              </tr>
              <tr>
              <td>
               <label for="synth_speaker">How well does synthesized song adapts to reference speaker voice<br></label>
               </td>
               <td>
              <select name="synth_speaker" id="synth_speaker" required="">
                <option value="" selected disabled>Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br> 
              </td>
              </tr>
              </table>
              </div>
                </td>
                 <td><audio controls controlsList="nodownload" preload="none" style="height:30px">
                  <source src="https://ismir21.github.io/T2S/Samples/WithGAN/ADIZ/adiz_3_hum.wav" type="audio/mpeg">audio not supported</audio>
                    <div style="font-size:14px;text-align: left;">
              <table>
              <tr>
              <td>
              <label for="sim_mel_t2s">How well does synthesized song adapts to target melody</label></td>
              <td>
              <select name="sim_mel_t2s" id="sim_mel_t2s" required="">
                <option value="" selected disabled>Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br>
              </td>
              </tr>
              <tr>
              <td>
             <label for="sim_qlty_t2s">How would you rate the singing Quality (clarity)</label>
             </td>
             <td>
              <select name="sim_qlty_t2s" id="sim_qlty_t2s" required="">
                <option value="" selected disabled>Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br>
              </td>
              </tr>
              <tr>
              <td>
     <label for="synth_phoneme_t2s">How would you rate the phoneme quality of synthesized audio<br>
     </label></td>
     <td>
              <select name="synth_phoneme_t2s" id="synth_phoneme_t2s" required="">
                <option value="" selected disabled>Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br>
              </td>
              </tr>
              <tr>
              <td>
               <label for="synth_speaker_t2s">How well does synthesized song adapts to reference speaker voice<br></label>
               </td>
               <td>
              <select name="synth_speaker_t2s" id="synth_speaker_t2s" required="">
                <option value="" selected disabled>Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br> 
              </td>
              </tr>
              </table>
              </div>
                  </td>
                  </tr>
                                 <tr>
              <td>
              <div  style="background-color: lightblue;white-space:nowrap;height:30px;min-width: 240px">
                 Lyrics</div> 
                 <div> Slow it down, make it stop Or else my heart is going to pop</div>
                    <div  style="background-color: lightblue;white-space:nowrap;height:30px;min-width: 240px">
                 Target Melody</div>  
              <audio controls controlsList="nodownload" preload="none" style="height:30px"><source src="https://ismir21.github.io/T2S/Samples/Recordings/4_singing.mp3" type="audio/mpeg">audio not supported</audio>            
              </td>
              <td>
              <audio controls controlsList="nodownload" preload="none" style="height:30px"><source src="https://ismir21.github.io/T2S/Samples/WithoutGAN/ADIZ/adiz_4_sing.wav" type="audio/mpeg">audio not supported</audio>
              <div style="font-size:14px;text-align: left;">
              <table>
              <tr>
              <td>
              <label for="sim_mel">How well does synthesized song adapts to target melody</label></td>
              <td>
              <select name="sim_mel" id="sim_mel" required="">
                <option value="" selected disabled>Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br>
              </td>
              </tr>
              <tr>
              <td>
             <label for="sim_qlty">How would you rate the singing Quality (clarity)</label>
             </td>
             <td>
              <select name="sim_qlty" id="sim_qlty" required="">
                <option value="" selected disabled>Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br>
              </td>
              </tr>
              <tr>
              <td>
     <label for="synth_phoneme">How would you rate the phoneme quality of synthesized audio<br>
     </label></td>
     <td>
              <select name="synth_phoneme" id="synth_phoneme" required="">
                <option value="" selected disabled>Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br>
              </td>
              </tr>
              <tr>
              <td>
               <label for="synth_speaker">How well does synthesized song adapts to reference speaker voice<br></label>
               </td>
               <td>
              <select name="synth_speaker" id="synth_speaker" required="">
                <option value="" selected disabled>Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br> 
              </td>
              </tr>
              </table>
              </div>
                </td>
                 <td><audio controls controlsList="nodownload" preload="none" style="height:30px">
                  <source src="https://ismir21.github.io/T2S/Samples/WithGAN/ADIZ/adiz_4_sing.wav" type="audio/mpeg">audio not supported</audio>
                    <div style="font-size:14px;text-align: left;">
              <table>
              <tr>
              <td>
              <label for="sim_mel_t2s">How well does synthesized song adapts to target melody</label></td>
              <td>
              <select name="sim_mel_t2s" id="sim_mel_t2s" required="">
                <option value="" selected disabled>Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br>
              </td>
              </tr>
              <tr>
              <td>
             <label for="sim_qlty_t2s">How would you rate the singing Quality (clarity)</label>
             </td>
             <td>
              <select name="sim_qlty_t2s" id="sim_qlty_t2s" required="">
                <option value="" selected disabled>Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br>
              </td>
              </tr>
              <tr>
              <td>
     <label for="synth_phoneme_t2s">How would you rate the phoneme quality of synthesized audio<br>
     </label></td>
     <td>
              <select name="synth_phoneme_t2s" id="synth_phoneme_t2s" required="">
                <option value="" selected disabled>Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br>
              </td>
              </tr>
              <tr>
              <td>
               <label for="synth_speaker_t2s">How well does synthesized song adapts to reference speaker voice<br></label>
               </td>
               <td>
              <select name="synth_speaker_t2s" id="synth_speaker_t2s" required="">
                <option value="" selected disabled>Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br> 
              </td>
              </tr>
              </table>
              </div>
                  </td>
                  </tr>
                   <tr>
              <td>
              <div  style="background-color: lightblue;white-space:nowrap;height:30px;min-width: 240px">
                 Lyrics</div> 
                 <div> Slow it down, make it stop Or else my heart is going to pop</div>
                    <div  style="background-color: lightblue;white-space:nowrap;height:30px;min-width: 240px">
                 Target Melody</div>  
              <audio controls controlsList="nodownload" preload="none" style="height:30px"><source src="https://ismir21.github.io/T2S/Samples/Recordings/4_humming.mp3" type="audio/mpeg">audio not supported</audio>            
              </td>
              <td>
              <audio controls controlsList="nodownload" preload="none" style="height:30px"><source src="https://ismir21.github.io/T2S/Samples/WithoutGAN/ADIZ/adiz_4_hum.wav" type="audio/mpeg">audio not supported</audio>
              <div style="font-size:14px;text-align: left;">
              <table>
              <tr>
              <td>
              <label for="sim_mel">How well does synthesized song adapts to target melody</label></td>
              <td>
              <select name="sim_mel" id="sim_mel" required="">
                <option value="" selected disabled>Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br>
              </td>
              </tr>
              <tr>
              <td>
             <label for="sim_qlty">How would you rate the singing Quality (clarity)</label>
             </td>
             <td>
              <select name="sim_qlty" id="sim_qlty" required="">
                <option value="" selected disabled>Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br>
              </td>
              </tr>
              <tr>
              <td>
     <label for="synth_phoneme">How would you rate the phoneme quality of synthesized audio<br>
     </label></td>
     <td>
              <select name="synth_phoneme" id="synth_phoneme" required="">
                <option value="" selected disabled>Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br>
              </td>
              </tr>
              <tr>
              <td>
               <label for="synth_speaker">How well does synthesized song adapts to reference speaker voice<br></label>
               </td>
               <td>
              <select name="synth_speaker" id="synth_speaker" required="">
                <option value="" selected disabled>Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br> 
              </td>
              </tr>
              </table>
              </div>
                </td>
                 <td><audio controls controlsList="nodownload" preload="none" style="height:30px">
                  <source src="https://ismir21.github.io/T2S/Samples/WithGAN/ADIZ/adiz_4_hum.wav" type="audio/mpeg">audio not supported</audio>
                    <div style="font-size:14px;text-align: left;">
              <table>
              <tr>
              <td>
              <label for="sim_mel_t2s">How well does synthesized song adapts to target melody</label></td>
              <td>
              <select name="sim_mel_t2s" id="sim_mel_t2s" required="">
                <option value="" selected disabled>Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br>
              </td>
              </tr>
              <tr>
              <td>
             <label for="sim_qlty_t2s">How would you rate the singing Quality (clarity)</label>
             </td>
             <td>
              <select name="sim_qlty_t2s" id="sim_qlty_t2s" required="">
                <option value="" selected disabled>Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br>
              </td>
              </tr>
              <tr>
              <td>
     <label for="synth_phoneme_t2s">How would you rate the phoneme quality of synthesized audio<br>
     </label></td>
     <td>
              <select name="synth_phoneme_t2s" id="synth_phoneme_t2s" required="">
                <option value="" selected disabled>Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br>
              </td>
              </tr>
              <tr>
              <td>
               <label for="synth_speaker_t2s">How well does synthesized song adapts to reference speaker voice<br></label>
               </td>
               <td>
              <select name="synth_speaker_t2s" id="synth_speaker_t2s" required="">
                <option value="" selected disabled>Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br> 
              </td>
              </tr>
              </table>
              </div>
                  </td>
                  </tr>
                                 <tr>
              <td>
              <div  style="background-color: lightblue;white-space:nowrap;height:30px;min-width: 240px">
                 Lyrics</div> 
                 <div> Love me tender,Love me sweet,Never let me go</div>
                    <div  style="background-color: lightblue;white-space:nowrap;height:30px;min-width: 240px">
                 Target Melody</div>  
              <audio controls controlsList="nodownload" preload="none" style="height:30px"><source src="https://ismir21.github.io/T2S/Samples/Recordings/5_singing.mp3" type="audio/mpeg">audio not supported</audio>            
              </td>
              <td>
              <audio controls controlsList="nodownload" preload="none" style="height:30px"><source src="https://ismir21.github.io/T2S/Samples/WithoutGAN/ADIZ/adiz_5_sing.wav" type="audio/mpeg">audio not supported</audio>
              <div style="font-size:14px;text-align: left;">
              <table>
              <tr>
              <td>
              <label for="sim_mel">How well does synthesized song adapts to target melody</label></td>
              <td>
              <select name="sim_mel" id="sim_mel" required="">
                <option value="" selected disabled>Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br>
              </td>
              </tr>
              <tr>
              <td>
             <label for="sim_qlty">How would you rate the singing Quality (clarity)</label>
             </td>
             <td>
              <select name="sim_qlty" id="sim_qlty" required="">
                <option value="" selected disabled>Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br>
              </td>
              </tr>
              <tr>
              <td>
     <label for="synth_phoneme">How would you rate the phoneme quality of synthesized audio<br>
     </label></td>
     <td>
              <select name="synth_phoneme" id="synth_phoneme" required="">
                <option value="" selected disabled>Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br>
              </td>
              </tr>
              <tr>
              <td>
               <label for="synth_speaker">How well does synthesized song adapts to reference speaker voice<br></label>
               </td>
               <td>
              <select name="synth_speaker" id="synth_speaker" required="">
                <option value="" selected disabled>Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br> 
              </td>
              </tr>
              </table>
              </div>
                </td>
                 <td><audio controls controlsList="nodownload" preload="none" style="height:30px">
                  <source src="https://ismir21.github.io/T2S/Samples/WithGAN/ADIZ/adiz_5_sing.wav" type="audio/mpeg">audio not supported</audio>
                    <div style="font-size:14px;text-align: left;">
              <table>
              <tr>
              <td>
              <label for="sim_mel_t2s">How well does synthesized song adapts to target melody</label></td>
              <td>
              <select name="sim_mel_t2s" id="sim_mel_t2s" required="">
                <option value="" selected disabled>Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br>
              </td>
              </tr>
              <tr>
              <td>
             <label for="sim_qlty_t2s">How would you rate the singing Quality (clarity)</label>
             </td>
             <td>
              <select name="sim_qlty_t2s" id="sim_qlty_t2s" required="">
                <option value="" selected disabled>Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br>
              </td>
              </tr>
              <tr>
              <td>
     <label for="synth_phoneme_t2s">How would you rate the phoneme quality of synthesized audio<br>
     </label></td>
     <td>
              <select name="synth_phoneme_t2s" id="synth_phoneme_t2s" required="">
                <option value="" selected disabled>Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br>
              </td>
              </tr>
              <tr>
              <td>
               <label for="synth_speaker_t2s">How well does synthesized song adapts to reference speaker voice<br></label>
               </td>
               <td>
              <select name="synth_speaker_t2s" id="synth_speaker_t2s" required="">
                <option value="" selected disabled>Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br> 
              </td>
              </tr>
              </table>
              </div>
                  </td>
                  </tr>
                   <tr>
              <td>
              <div  style="background-color: lightblue;white-space:nowrap;height:30px;min-width: 240px">
                 Lyrics</div> 
                 <div> Love me tender,Love me sweet,Never let me go</div>
                    <div  style="background-color: lightblue;white-space:nowrap;height:30px;min-width: 240px">
                 Target Melody</div>  
              <audio controls controlsList="nodownload" preload="none" style="height:30px"><source src="https://ismir21.github.io/T2S/Samples/Recordings/5_humming.mp3" type="audio/mpeg">audio not supported</audio>            
              </td>
              <td>
              <audio controls controlsList="nodownload" preload="none" style="height:30px"><source src="https://ismir21.github.io/T2S/Samples/WithoutGAN/ADIZ/adiz_5_hum.wav" type="audio/mpeg">audio not supported</audio>
              <div style="font-size:14px;text-align: left;">
              <table>
              <tr>
              <td>
              <label for="sim_mel">How well does synthesized song adapts to target melody</label></td>
              <td>
              <select name="sim_mel" id="sim_mel" required="">
                <option value="" selected disabled>Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br>
              </td>
              </tr>
              <tr>
              <td>
             <label for="sim_qlty">How would you rate the singing Quality (clarity)</label>
             </td>
             <td>
              <select name="sim_qlty" id="sim_qlty" required="">
                <option value="" selected disabled>Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br>
              </td>
              </tr>
              <tr>
              <td>
     <label for="synth_phoneme">How would you rate the phoneme quality of synthesized audio<br>
     </label></td>
     <td>
              <select name="synth_phoneme" id="synth_phoneme" required="">
                <option value="" selected disabled>Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br>
              </td>
              </tr>
              <tr>
              <td>
               <label for="synth_speaker">How well does synthesized song adapts to reference speaker voice<br></label>
               </td>
               <td>
              <select name="synth_speaker" id="synth_speaker" required="">
                <option value="" selected disabled>Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br> 
              </td>
              </tr>
              </table>
              </div>
                </td>
                 <td><audio controls controlsList="nodownload" preload="none" style="height:30px">
                  <source src="https://ismir21.github.io/T2S/Samples/WithGAN/ADIZ/adiz_5_hum.wav" type="audio/mpeg">audio not supported</audio>
                    <div style="font-size:14px;text-align: left;">
              <table>
              <tr>
              <td>
              <label for="sim_mel_t2s">How well does synthesized song adapts to target melody</label></td>
              <td>
              <select name="sim_mel_t2s" id="sim_mel_t2s" required="">
                <option value="" selected disabled>Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br>
              </td>
              </tr>
              <tr>
              <td>
             <label for="sim_qlty_t2s">How would you rate the singing Quality (clarity)</label>
             </td>
             <td>
              <select name="sim_qlty_t2s" id="sim_qlty_t2s" required="">
                <option value="" selected disabled>Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br>
              </td>
              </tr>
              <tr>
              <td>
     <label for="synth_phoneme_t2s">How would you rate the phoneme quality of synthesized audio<br>
     </label></td>
     <td>
              <select name="synth_phoneme_t2s" id="synth_phoneme_t2s" required="">
                <option value="" selected disabled>Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br>
              </td>
              </tr>
              <tr>
              <td>
               <label for="synth_speaker_t2s">How well does synthesized song adapts to reference speaker voice<br></label>
               </td>
               <td>
              <select name="synth_speaker_t2s" id="synth_speaker_t2s" required="">
                <option value="" selected disabled>Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br> 
              </td>
              </tr>
              </table>
              </div>
                  </td>
                  </tr>
              </tbody></table>  
              </div> 
                <div class='grrp'>  
    <h3>Singer3</h3>
              <table border="0" style="font-size:16px">
              <tbody>
                <tr>                
                <th bgcolor="lightblue" style="white-space:nowrap;height:30px;min-width: 240px">
                 </th>               
                <th bgcolor="lightblue" style="white-space:nowrap;height:30px;min-width: 240px">
                 Synthesized Song with Model 1</th>                
                <th bgcolor="lightblue" style="white-space:nowrap;height:30px;min-width: 240px">
                 Synthesized Song with Model 2</th></tr>
              <tr>
              <td>
              <div  style="background-color: lightblue;white-space:nowrap;height:30px;min-width: 240px">
                 Lyrics</div> 
                 <div> Edelweiss, Edelweiss Every morning you greet me</div>
                    <div  style="background-color: lightblue;white-space:nowrap;height:30px;min-width: 240px">
                 Target Melody</div>  
              <audio controls controlsList="nodownload" preload="none" style="height:30px"><source src="https://ismir21.github.io/T2S/Samples/Recordings/1_msinging.wav" type="audio/mpeg">audio not supported</audio>            
              <div  style="background-color: lightblue;white-space:nowrap;height:30px;min-width: 240px">
                 Target Singer Voice</div>                  
                 <audio controls controlsList="nodownload" preload="none" style="height:30px"><source src="https://ismir21.github.io/T2S/Samples/Speech/Singer4_Voice.wav" type="audio/mpeg">audio not supported</audio> 
                </td>
              <td>
              <audio controls controlsList="nodownload" preload="none" style="height:30px"><source src="https://ismir21.github.io/T2S/Samples/WithoutGAN/SAMU/samu_1_sing.wav" type="audio/mpeg">audio not supported</audio>
              <div style="font-size:14px;text-align: left;">
              <table>
              <tr>
              <td>
              <label for="sim_mel">How well does synthesized song adapts to target melody</label></td>
              <td>
              <select name="sim_mel" id="sim_mel" required="">
                <option value="" selected disabled>Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br>
              </td>
              </tr>
              <tr>
              <td>
             <label for="sim_qlty">How would you rate the singing Quality (clarity)</label>
             </td>
             <td>
              <select name="sim_qlty" id="sim_qlty" required="">
                <option value="" selected disabled>Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br>
              </td>
              </tr>
              <tr>
              <td>
     <label for="synth_phoneme">How would you rate the phoneme quality of synthesized audio<br>
     </label></td>
     <td>
              <select name="synth_phoneme" id="synth_phoneme" required="">
                <option value="" selected disabled>Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br>
              </td>
              </tr>
              <tr>
              <td>
               <label for="synth_speaker">How well does synthesized song adapts to reference speaker voice<br></label>
               </td>
               <td>
              <select name="synth_speaker" id="synth_speaker" required="">
                <option value="" selected disabled>Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br> 
              </td>
              </tr>
              </table>
              </div>
                </td>
                 <td><audio controls controlsList="nodownload" preload="none" style="height:30px">
                  <source src="https://ismir21.github.io/T2S/Samples/WithGAN/SAMU/samu_1_sing.wav" type="audio/mpeg">audio not supported</audio>
                    <div style="font-size:14px;text-align: left;">
              <table>
              <tr>
              <td>
              <label for="sim_mel_t2s">How well does synthesized song adapts to target melody</label></td>
              <td>
              <select name="sim_mel_t2s" id="sim_mel_t2s" required="">
                <option value="" selected disabled>Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br>
              </td>
              </tr>
              <tr>
              <td>
             <label for="sim_qlty_t2s">How would you rate the singing Quality (clarity)</label>
             </td>
             <td>
              <select name="sim_qlty_t2s" id="sim_qlty_t2s" required="">
                <option value="" selected disabled>Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br>
              </td>
              </tr>
              <tr>
              <td>
     <label for="synth_phoneme_t2s">How would you rate the phoneme quality of synthesized audio<br>
     </label></td>
     <td>
              <select name="synth_phoneme_t2s" id="synth_phoneme_t2s" required="">
                <option value="" selected disabled>Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br>
              </td>
              </tr>
              <tr>
              <td>
               <label for="synth_speaker_t2s">How well does synthesized song adapts to reference speaker voice<br></label>
               </td>
               <td>
              <select name="synth_speaker_t2s" id="synth_speaker_t2s" required="">
                <option value="" selected disabled>Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br> 
              </td>
              </tr>
              </table>
              </div>
                  </td>
                  </tr>
              <tr>
              <td>
              <div  style="background-color: lightblue;white-space:nowrap;height:30px;min-width: 240px">
                 Lyrics</div> 
                 <div> Edelweiss, Edelweiss Every morning you greet me</div>
                    <div  style="background-color: lightblue;white-space:nowrap;height:30px;min-width: 240px">
                 Target Melody</div>  
              <audio controls controlsList="nodownload" preload="none" style="height:30px"><source src="https://ismir21.github.io/T2S/Samples/Recordings/1_mhumming.wav" type="audio/mpeg">audio not supported</audio>            
             </td>
              <td>
              <audio controls controlsList="nodownload" preload="none" style="height:30px"><source src="https://ismir21.github.io/T2S/Samples/WithoutGAN/SAMU/samu_1_hum.wav" type="audio/mpeg">audio not supported</audio>
              <div style="font-size:14px;text-align: left;">
              <table>
              <tr>
              <td>
              <label for="sim_mel">How well does synthesized song adapts to target melody</label></td>
              <td>
              <select name="sim_mel" id="sim_mel" required="">
                <option value="" selected disabled>Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br>
              </td>
              </tr>
              <tr>
              <td>
             <label for="sim_qlty">How would you rate the singing Quality (clarity)</label>
             </td>
             <td>
              <select name="sim_qlty" id="sim_qlty" required="">
                <option value="" selected disabled>Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br>
              </td>
              </tr>
              <tr>
              <td>
     <label for="synth_phoneme">How would you rate the phoneme quality of synthesized audio<br>
     </label></td>
     <td>
              <select name="synth_phoneme" id="synth_phoneme" required="">
                <option value="" selected disabled>Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br>
              </td>
              </tr>
              <tr>
              <td>
               <label for="synth_speaker">How well does synthesized song adapts to reference speaker voice<br></label>
               </td>
               <td>
              <select name="synth_speaker" id="synth_speaker" required="">
                <option value="" selected disabled>Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br> 
              </td>
              </tr>
              </table>
              </div>
                </td>
                 <td><audio controls controlsList="nodownload" preload="none" style="height:30px">
                  <source src="https://ismir21.github.io/T2S/Samples/WithGAN/SAMU/samu_1_hum.wav" type="audio/mpeg">audio not supported</audio>
                    <div style="font-size:14px;text-align: left;">
              <table>
              <tr>
              <td>
              <label for="sim_mel_t2s">How well does synthesized song adapts to target melody</label></td>
              <td>
              <select name="sim_mel_t2s" id="sim_mel_t2s" required="">
                <option value="" selected disabled>Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br>
              </td>
              </tr>
              <tr>
              <td>
             <label for="sim_qlty_t2s">How would you rate the singing Quality (clarity)</label>
             </td>
             <td>
              <select name="sim_qlty_t2s" id="sim_qlty_t2s" required="">
                <option value="" selected disabled>Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br>
              </td>
              </tr>
              <tr>
              <td>
     <label for="synth_phoneme_t2s">How would you rate the phoneme quality of synthesized audio<br>
     </label></td>
     <td>
              <select name="synth_phoneme_t2s" id="synth_phoneme_t2s" required="">
                <option value="" selected disabled>Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br>
              </td>
              </tr>
              <tr>
              <td>
               <label for="synth_speaker_t2s">How well does synthesized song adapts to reference speaker voice<br></label>
               </td>
               <td>
              <select name="synth_speaker_t2s" id="synth_speaker_t2s" required="">
                <option value="" selected disabled>Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br> 
              </td>
              </tr>
              </table>
              </div>
              </td>
              </tr>
               <tr>
              <td>
              <div  style="background-color: lightblue;white-space:nowrap;height:30px;min-width: 240px">
                 Lyrics</div> 
                 <div> Love in your eyes Sitting silent by my side</div>
                    <div  style="background-color: lightblue;white-space:nowrap;height:30px;min-width: 240px">
                 Target Melody</div>  
              <audio controls controlsList="nodownload" preload="none" style="height:30px"><source src="https://ismir21.github.io/T2S/Samples/Recordings/2_msinging.wav" type="audio/mpeg">audio not supported</audio>            
              </td>
              <td>
              <audio controls controlsList="nodownload" preload="none" style="height:30px"><source src="https://ismir21.github.io/T2S/Samples/WithoutGAN/SAMU/samu_2_sing.wav" type="audio/mpeg">audio not supported</audio>
              <div style="font-size:14px;text-align: left;">
              <table>
              <tr>
              <td>
              <label for="sim_mel">How well does synthesized song adapts to target melody</label></td>
              <td>
              <select name="sim_mel" id="sim_mel" required="">
                <option value="" selected disabled>Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br>
              </td>
              </tr>
              <tr>
              <td>
             <label for="sim_qlty">How would you rate the singing Quality (clarity)</label>
             </td>
             <td>
              <select name="sim_qlty" id="sim_qlty" required="">
                <option value="" selected disabled>Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br>
              </td>
              </tr>
              <tr>
              <td>
     <label for="synth_phoneme">How would you rate the phoneme quality of synthesized audio<br>
     </label></td>
     <td>
              <select name="synth_phoneme" id="synth_phoneme" required="">
                <option value="" selected disabled>Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br>
              </td>
              </tr>
              <tr>
              <td>
               <label for="synth_speaker">How well does synthesized song adapts to reference speaker voice<br></label>
               </td>
               <td>
              <select name="synth_speaker" id="synth_speaker" required="">
                <option value="" selected disabled>Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br> 
              </td>
              </tr>
              </table>
              </div>
                </td>
                 <td><audio controls controlsList="nodownload" preload="none" style="height:30px">
                  <source src="https://ismir21.github.io/T2S/Samples/WithGAN/SAMU/samu_2_sing.wav" type="audio/mpeg">audio not supported</audio>
                    <div style="font-size:14px;text-align: left;">
              <table>
              <tr>
              <td>
              <label for="sim_mel_t2s">How well does synthesized song adapts to target melody</label></td>
              <td>
              <select name="sim_mel_t2s" id="sim_mel_t2s" required="">
                <option value="" selected disabled>Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br>
              </td>
              </tr>
              <tr>
              <td>
             <label for="sim_qlty_t2s">How would you rate the singing Quality (clarity)</label>
             </td>
             <td>
              <select name="sim_qlty_t2s" id="sim_qlty_t2s" required="">
                <option value="" selected disabled>Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br>
              </td>
              </tr>
              <tr>
              <td>
     <label for="synth_phoneme_t2s">How would you rate the phoneme quality of synthesized audio<br>
     </label></td>
     <td>
              <select name="synth_phoneme_t2s" id="synth_phoneme_t2s" required="">
                <option value="" selected disabled>Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br>
              </td>
              </tr>
              <tr>
              <td>
               <label for="synth_speaker_t2s">How well does synthesized song adapts to reference speaker voice<br></label>
               </td>
               <td>
              <select name="synth_speaker_t2s" id="synth_speaker_t2s" required="">
                <option value="" selected disabled>Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br> 
              </td>
              </tr>
              </table>
              </div>
                  </td>
                  </tr>
                   <tr>
              <td>
              <div  style="background-color: lightblue;white-space:nowrap;height:30px;min-width: 240px">
                 Lyrics</div> 
                 <div> Love in your eyes Sitting silent by my side</div>
                    <div  style="background-color: lightblue;white-space:nowrap;height:30px;min-width: 240px">
                 Target Melody</div>  
              <audio controls controlsList="nodownload" preload="none" style="height:30px"><source src="https://ismir21.github.io/T2S/Samples/Recordings/2_mhumming.wav" type="audio/mpeg">audio not supported</audio>            
              </td>
              <td>
              <audio controls controlsList="nodownload" preload="none" style="height:30px"><source src="https://ismir21.github.io/T2S/Samples/WithoutGAN/SAMU/samu_2_hum.wav" type="audio/mpeg">audio not supported</audio>
              <div style="font-size:14px;text-align: left;">
              <table>
              <tr>
              <td>
              <label for="sim_mel">How well does synthesized song adapts to target melody</label></td>
              <td>
              <select name="sim_mel" id="sim_mel" required="">
                <option value="" selected disabled>Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br>
              </td>
              </tr>
              <tr>
              <td>
             <label for="sim_qlty">How would you rate the singing Quality (clarity)</label>
             </td>
             <td>
              <select name="sim_qlty" id="sim_qlty" required="">
                <option value="" selected disabled>Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br>
              </td>
              </tr>
              <tr>
              <td>
     <label for="synth_phoneme">How would you rate the phoneme quality of synthesized audio<br>
     </label></td>
     <td>
              <select name="synth_phoneme" id="synth_phoneme" required="">
                <option value="" selected disabled>Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br>
              </td>
              </tr>
              <tr>
              <td>
               <label for="synth_speaker">How well does synthesized song adapts to reference speaker voice<br></label>
               </td>
               <td>
              <select name="synth_speaker" id="synth_speaker" required="">
                <option value="" selected disabled>Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br> 
              </td>
              </tr>
              </table>
              </div>
                </td>
                 <td><audio controls controlsList="nodownload" preload="none" style="height:30px">
                  <source src="https://ismir21.github.io/T2S/Samples/WithGAN/SAMU/samu_2_hum.wav" type="audio/mpeg">audio not supported</audio>
                    <div style="font-size:14px;text-align: left;">
              <table>
              <tr>
              <td>
              <label for="sim_mel_t2s">How well does synthesized song adapts to target melody</label></td>
              <td>
              <select name="sim_mel_t2s" id="sim_mel_t2s" required="">
                <option value="" selected disabled>Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br>
              </td>
              </tr>
              <tr>
              <td>
             <label for="sim_qlty_t2s">How would you rate the singing Quality (clarity)</label>
             </td>
             <td>
              <select name="sim_qlty_t2s" id="sim_qlty_t2s" required="">
                <option value="" selected disabled>Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br>
              </td>
              </tr>
              <tr>
              <td>
     <label for="synth_phoneme_t2s">How would you rate the phoneme quality of synthesized audio<br>
     </label></td>
     <td>
              <select name="synth_phoneme_t2s" id="synth_phoneme_t2s" required="">
                <option value="" selected disabled>Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br>
              </td>
              </tr>
              <tr>
              <td>
               <label for="synth_speaker_t2s">How well does synthesized song adapts to reference speaker voice<br></label>
               </td>
               <td>
              <select name="synth_speaker_t2s" id="synth_speaker_t2s" required="">
                <option value="" selected disabled>Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br> 
              </td>
              </tr>
              </table>
              </div>
                  </td>
                  </tr>
                                 <tr>
              <td>
              <div  style="background-color: lightblue;white-space:nowrap;height:30px;min-width: 240px">
                 Lyrics</div> 
                 <div> I'm just a little bit caught in the middle Life is a maze, and love is a riddle</div>
                    <div  style="background-color: lightblue;white-space:nowrap;height:30px;min-width: 240px">
                 Target Melody</div>  
              <audio controls controlsList="nodownload" preload="none" style="height:30px"><source src="https://ismir21.github.io/T2S/Samples/Recordings/3_msinging.wav" type="audio/mpeg">audio not supported</audio>            
              </td>
              <td>
              <audio controls controlsList="nodownload" preload="none" style="height:30px"><source src="https://ismir21.github.io/T2S/Samples/WithoutGAN/SAMU/samu_3_sing.wav" type="audio/mpeg">audio not supported</audio>
              <div style="font-size:14px;text-align: left;">
              <table>
              <tr>
              <td>
              <label for="sim_mel">How well does synthesized song adapts to target melody</label></td>
              <td>
              <select name="sim_mel" id="sim_mel" required="">
                <option value="" selected disabled>Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br>
              </td>
              </tr>
              <tr>
              <td>
             <label for="sim_qlty">How would you rate the singing Quality (clarity)</label>
             </td>
             <td>
              <select name="sim_qlty" id="sim_qlty" required="">
                <option value="" selected disabled>Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br>
              </td>
              </tr>
              <tr>
              <td>
     <label for="synth_phoneme">How would you rate the phoneme quality of synthesized audio<br>
     </label></td>
     <td>
              <select name="synth_phoneme" id="synth_phoneme" required="">
                <option value="" selected disabled>Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br>
              </td>
              </tr>
              <tr>
              <td>
               <label for="synth_speaker">How well does synthesized song adapts to reference speaker voice<br></label>
               </td>
               <td>
              <select name="synth_speaker" id="synth_speaker" required="">
                <option value="" selected disabled>Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br> 
              </td>
              </tr>
              </table>
              </div>
                </td>
                 <td><audio controls controlsList="nodownload" preload="none" style="height:30px">
                  <source src="https://ismir21.github.io/T2S/Samples/WithGAN/SAMU/samu_3_sing.wav" type="audio/mpeg">audio not supported</audio>
                    <div style="font-size:14px;text-align: left;">
              <table>
              <tr>
              <td>
              <label for="sim_mel_t2s">How well does synthesized song adapts to target melody</label></td>
              <td>
              <select name="sim_mel_t2s" id="sim_mel_t2s" required="">
                <option value="" selected disabled>Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br>
              </td>
              </tr>
              <tr>
              <td>
             <label for="sim_qlty_t2s">How would you rate the singing Quality (clarity)</label>
             </td>
             <td>
              <select name="sim_qlty_t2s" id="sim_qlty_t2s" required="">
                <option value="" selected disabled>Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br>
              </td>
              </tr>
              <tr>
              <td>
     <label for="synth_phoneme_t2s">How would you rate the phoneme quality of synthesized audio<br>
     </label></td>
     <td>
              <select name="synth_phoneme_t2s" id="synth_phoneme_t2s" required="">
                <option value="" selected disabled>Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br>
              </td>
              </tr>
              <tr>
              <td>
               <label for="synth_speaker_t2s">How well does synthesized song adapts to reference speaker voice<br></label>
               </td>
               <td>
              <select name="synth_speaker_t2s" id="synth_speaker_t2s" required="">
                <option value="" selected disabled>Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br> 
              </td>
              </tr>
              </table>
              </div>
                  </td>
                  </tr>
                   <tr>
              <td>
              <div  style="background-color: lightblue;white-space:nowrap;height:30px;min-width: 240px">
                 Lyrics</div> 
                 <div> I'm just a little bit caught in the middle Life is a maze, and love is a riddle</div>
                    <div  style="background-color: lightblue;white-space:nowrap;height:30px;min-width: 240px">
                 Target Melody</div>  
              <audio controls controlsList="nodownload" preload="none" style="height:30px"><source src="https://ismir21.github.io/T2S/Samples/Recordings/3_mhumming.wav" type="audio/mpeg">audio not supported</audio>            
              </td>
              <td>
              <audio controls controlsList="nodownload" preload="none" style="height:30px"><source src="https://ismir21.github.io/T2S/Samples/WithoutGAN/SAMU/samu_3_hum.wav" type="audio/mpeg">audio not supported</audio>
              <div style="font-size:14px;text-align: left;">
              <table>
              <tr>
              <td>
              <label for="sim_mel">How well does synthesized song adapts to target melody</label></td>
              <td>
              <select name="sim_mel" id="sim_mel" required="">
                <option value="" selected disabled>Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br>
              </td>
              </tr>
              <tr>
              <td>
             <label for="sim_qlty">How would you rate the singing Quality (clarity)</label>
             </td>
             <td>
              <select name="sim_qlty" id="sim_qlty" required="">
                <option value="" selected disabled>Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br>
              </td>
              </tr>
              <tr>
              <td>
     <label for="synth_phoneme">How would you rate the phoneme quality of synthesized audio<br>
     </label></td>
     <td>
              <select name="synth_phoneme" id="synth_phoneme" required="">
                <option value="" selected disabled>Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br>
              </td>
              </tr>
              <tr>
              <td>
               <label for="synth_speaker">How well does synthesized song adapts to reference speaker voice<br></label>
               </td>
               <td>
              <select name="synth_speaker" id="synth_speaker" required="">
                <option value="" selected disabled>Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br> 
              </td>
              </tr>
              </table>
              </div>
                </td>
                 <td><audio controls controlsList="nodownload" preload="none" style="height:30px">
                  <source src="https://ismir21.github.io/T2S/Samples/WithGAN/SAMU/samu_3_hum.wav" type="audio/mpeg">audio not supported</audio>
                    <div style="font-size:14px;text-align: left;">
              <table>
              <tr>
              <td>
              <label for="sim_mel_t2s">How well does synthesized song adapts to target melody</label></td>
              <td>
              <select name="sim_mel_t2s" id="sim_mel_t2s" required="">
                <option value="" selected disabled>Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br>
              </td>
              </tr>
              <tr>
              <td>
             <label for="sim_qlty_t2s">How would you rate the singing Quality (clarity)</label>
             </td>
             <td>
              <select name="sim_qlty_t2s" id="sim_qlty_t2s" required="">
                <option value="" selected disabled>Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br>
              </td>
              </tr>
              <tr>
              <td>
     <label for="synth_phoneme_t2s">How would you rate the phoneme quality of synthesized audio<br>
     </label></td>
     <td>
              <select name="synth_phoneme_t2s" id="synth_phoneme_t2s" required="">
                <option value="" selected disabled>Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br>
              </td>
              </tr>
              <tr>
              <td>
               <label for="synth_speaker_t2s">How well does synthesized song adapts to reference speaker voice<br></label>
               </td>
               <td>
              <select name="synth_speaker_t2s" id="synth_speaker_t2s" required="">
                <option value="" selected disabled>Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br> 
              </td>
              </tr>
              </table>
              </div>
                  </td>
                  </tr>
                                 <tr>
              <td>
              <div  style="background-color: lightblue;white-space:nowrap;height:30px;min-width: 240px">
                 Lyrics</div> 
                 <div> Slow it down, make it stop Or else my heart is going to pop</div>
                    <div  style="background-color: lightblue;white-space:nowrap;height:30px;min-width: 240px">
                 Target Melody</div>  
              <audio controls controlsList="nodownload" preload="none" style="height:30px"><source src="https://ismir21.github.io/T2S/Samples/Recordings/4_msinging.wav" type="audio/mpeg">audio not supported</audio>            
              </td>
              <td>
              <audio controls controlsList="nodownload" preload="none" style="height:30px"><source src="https://ismir21.github.io/T2S/Samples/WithoutGAN/SAMU/samu_4_sing.wav" type="audio/mpeg">audio not supported</audio>
              <div style="font-size:14px;text-align: left;">
              <table>
              <tr>
              <td>
              <label for="sim_mel">How well does synthesized song adapts to target melody</label></td>
              <td>
              <select name="sim_mel" id="sim_mel" required="">
                <option value="" selected disabled>Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br>
              </td>
              </tr>
              <tr>
              <td>
             <label for="sim_qlty">How would you rate the singing Quality (clarity)</label>
             </td>
             <td>
              <select name="sim_qlty" id="sim_qlty" required="">
                <option value="" selected disabled>Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br>
              </td>
              </tr>
              <tr>
              <td>
     <label for="synth_phoneme">How would you rate the phoneme quality of synthesized audio<br>
     </label></td>
     <td>
              <select name="synth_phoneme" id="synth_phoneme" required="">
                <option value="" selected disabled>Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br>
              </td>
              </tr>
              <tr>
              <td>
               <label for="synth_speaker">How well does synthesized song adapts to reference speaker voice<br></label>
               </td>
               <td>
              <select name="synth_speaker" id="synth_speaker" required="">
                <option value="" selected disabled>Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br> 
              </td>
              </tr>
              </table>
              </div>
                </td>
                 <td><audio controls controlsList="nodownload" preload="none" style="height:30px">
                  <source src="https://ismir21.github.io/T2S/Samples/WithGAN/SAMU/samu_4_sing.wav" type="audio/mpeg">audio not supported</audio>
                    <div style="font-size:14px;text-align: left;">
              <table>
              <tr>
              <td>
              <label for="sim_mel_t2s">How well does synthesized song adapts to target melody</label></td>
              <td>
              <select name="sim_mel_t2s" id="sim_mel_t2s" required="">
                <option value="" selected disabled>Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br>
              </td>
              </tr>
              <tr>
              <td>
             <label for="sim_qlty_t2s">How would you rate the singing Quality (clarity)</label>
             </td>
             <td>
              <select name="sim_qlty_t2s" id="sim_qlty_t2s" required="">
                <option value="" selected disabled>Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br>
              </td>
              </tr>
              <tr>
              <td>
     <label for="synth_phoneme_t2s">How would you rate the phoneme quality of synthesized audio<br>
     </label></td>
     <td>
              <select name="synth_phoneme_t2s" id="synth_phoneme_t2s" required="">
                <option value="" selected disabled>Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br>
              </td>
              </tr>
              <tr>
              <td>
               <label for="synth_speaker_t2s">How well does synthesized song adapts to reference speaker voice<br></label>
               </td>
               <td>
              <select name="synth_speaker_t2s" id="synth_speaker_t2s" required="">
                <option value="" selected disabled>Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br> 
              </td>
              </tr>
              </table>
              </div>
                  </td>
                  </tr>
                   <tr>
              <td>
              <div  style="background-color: lightblue;white-space:nowrap;height:30px;min-width: 240px">
                 Lyrics</div> 
                 <div> Slow it down, make it stop Or else my heart is going to pop</div>
                    <div  style="background-color: lightblue;white-space:nowrap;height:30px;min-width: 240px">
                 Target Melody</div>  
              <audio controls controlsList="nodownload" preload="none" style="height:30px"><source src="https://ismir21.github.io/T2S/Samples/Recordings/4_mhumming.wav" type="audio/mpeg">audio not supported</audio>            
              </td>
              <td>
              <audio controls controlsList="nodownload" preload="none" style="height:30px"><source src="https://ismir21.github.io/T2S/Samples/WithoutGAN/SAMU/samu_4_hum.wav" type="audio/mpeg">audio not supported</audio>
              <div style="font-size:14px;text-align: left;">
              <table>
              <tr>
              <td>
              <label for="sim_mel">How well does synthesized song adapts to target melody</label></td>
              <td>
              <select name="sim_mel" id="sim_mel" required="">
                <option value="" selected disabled>Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br>
              </td>
              </tr>
              <tr>
              <td>
             <label for="sim_qlty">How would you rate the singing Quality (clarity)</label>
             </td>
             <td>
              <select name="sim_qlty" id="sim_qlty" required="">
                <option value="" selected disabled>Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br>
              </td>
              </tr>
              <tr>
              <td>
     <label for="synth_phoneme">How would you rate the phoneme quality of synthesized audio<br>
     </label></td>
     <td>
              <select name="synth_phoneme" id="synth_phoneme" required="">
                <option value="" selected disabled>Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br>
              </td>
              </tr>
              <tr>
              <td>
               <label for="synth_speaker">How well does synthesized song adapts to reference speaker voice<br></label>
               </td>
               <td>
              <select name="synth_speaker" id="synth_speaker" required="">
                <option value="" selected disabled>Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br> 
              </td>
              </tr>
              </table>
              </div>
                </td>
                 <td><audio controls controlsList="nodownload" preload="none" style="height:30px">
                  <source src="https://ismir21.github.io/T2S/Samples/WithGAN/SAMU/samu_4_hum.wav" type="audio/mpeg">audio not supported</audio>
                    <div style="font-size:14px;text-align: left;">
              <table>
              <tr>
              <td>
              <label for="sim_mel_t2s">How well does synthesized song adapts to target melody</label></td>
              <td>
              <select name="sim_mel_t2s" id="sim_mel_t2s" required="">
                <option value="" selected disabled>Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br>
              </td>
              </tr>
              <tr>
              <td>
             <label for="sim_qlty_t2s">How would you rate the singing Quality (clarity)</label>
             </td>
             <td>
              <select name="sim_qlty_t2s" id="sim_qlty_t2s" required="">
                <option value="" selected disabled>Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br>
              </td>
              </tr>
              <tr>
              <td>
     <label for="synth_phoneme_t2s">How would you rate the phoneme quality of synthesized audio<br>
     </label></td>
     <td>
              <select name="synth_phoneme_t2s" id="synth_phoneme_t2s" required="">
                <option value="" selected disabled>Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br>
              </td>
              </tr>
              <tr>
              <td>
               <label for="synth_speaker_t2s">How well does synthesized song adapts to reference speaker voice<br></label>
               </td>
               <td>
              <select name="synth_speaker_t2s" id="synth_speaker_t2s" required="">
                <option value="" selected disabled>Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br> 
              </td>
              </tr>
              </table>
              </div>
                  </td>
                  </tr>
                                 <tr>
              <td>
              <div  style="background-color: lightblue;white-space:nowrap;height:30px;min-width: 240px">
                 Lyrics</div> 
                 <div> Love me tender,Love me sweet,Never let me go</div>
                    <div  style="background-color: lightblue;white-space:nowrap;height:30px;min-width: 240px">
                 Target Melody</div>  
              <audio controls controlsList="nodownload" preload="none" style="height:30px"><source src="https://ismir21.github.io/T2S/Samples/Recordings/5_msinging.wav" type="audio/mpeg">audio not supported</audio>            
              </td>
              <td>
              <audio controls controlsList="nodownload" preload="none" style="height:30px"><source src="https://ismir21.github.io/T2S/Samples/WithoutGAN/SAMU/samu_5_sing.wav" type="audio/mpeg">audio not supported</audio>
              <div style="font-size:14px;text-align: left;">
              <table>
              <tr>
              <td>
              <label for="sim_mel">How well does synthesized song adapts to target melody</label></td>
              <td>
              <select name="sim_mel" id="sim_mel" required="">
                <option value="" selected disabled>Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br>
              </td>
              </tr>
              <tr>
              <td>
             <label for="sim_qlty">How would you rate the singing Quality (clarity)</label>
             </td>
             <td>
              <select name="sim_qlty" id="sim_qlty" required="">
                <option value="" selected disabled>Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br>
              </td>
              </tr>
              <tr>
              <td>
     <label for="synth_phoneme">How would you rate the phoneme quality of synthesized audio<br>
     </label></td>
     <td>
              <select name="synth_phoneme" id="synth_phoneme" required="">
                <option value="" selected disabled>Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br>
              </td>
              </tr>
              <tr>
              <td>
               <label for="synth_speaker">How well does synthesized song adapts to reference speaker voice<br></label>
               </td>
               <td>
              <select name="synth_speaker" id="synth_speaker" required="">
                <option value="" selected disabled>Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br> 
              </td>
              </tr>
              </table>
              </div>
                </td>
                 <td><audio controls controlsList="nodownload" preload="none" style="height:30px">
                  <source src="https://ismir21.github.io/T2S/Samples/WithGAN/SAMU/samu_5_sing.wav" type="audio/mpeg">audio not supported</audio>
                    <div style="font-size:14px;text-align: left;">
              <table>
              <tr>
              <td>
              <label for="sim_mel_t2s">How well does synthesized song adapts to target melody</label></td>
              <td>
              <select name="sim_mel_t2s" id="sim_mel_t2s" required="">
                <option value="" selected disabled>Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br>
              </td>
              </tr>
              <tr>
              <td>
             <label for="sim_qlty_t2s">How would you rate the singing Quality (clarity)</label>
             </td>
             <td>
              <select name="sim_qlty_t2s" id="sim_qlty_t2s" required="">
                <option value="" selected disabled>Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br>
              </td>
              </tr>
              <tr>
              <td>
     <label for="synth_phoneme_t2s">How would you rate the phoneme quality of synthesized audio<br>
     </label></td>
     <td>
              <select name="synth_phoneme_t2s" id="synth_phoneme_t2s" required="">
                <option value="" selected disabled>Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br>
              </td>
              </tr>
              <tr>
              <td>
               <label for="synth_speaker_t2s">How well does synthesized song adapts to reference speaker voice<br></label>
               </td>
               <td>
              <select name="synth_speaker_t2s" id="synth_speaker_t2s" required="">
                <option value="" selected disabled>Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br> 
              </td>
              </tr>
              </table>
              </div>
                  </td>
                  </tr>
                   <tr>
              <td>
              <div  style="background-color: lightblue;white-space:nowrap;height:30px;min-width: 240px">
                 Lyrics</div> 
                 <div> Love me tender,Love me sweet,Never let me go</div>
                    <div  style="background-color: lightblue;white-space:nowrap;height:30px;min-width: 240px">
                 Target Melody</div>  
              <audio controls controlsList="nodownload" preload="none" style="height:30px"><source src="https://ismir21.github.io/T2S/Samples/Recordings/5_mhumming.wav" type="audio/mpeg">audio not supported</audio>            
              </td>
              <td>
              <audio controls controlsList="nodownload" preload="none" style="height:30px"><source src="https://ismir21.github.io/T2S/Samples/WithoutGAN/SAMU/samu_5_hum.wav" type="audio/mpeg">audio not supported</audio>
              <div style="font-size:14px;text-align: left;">
              <table>
              <tr>
              <td>
              <label for="sim_mel">How well does synthesized song adapts to target melody</label></td>
              <td>
              <select name="sim_mel" id="sim_mel" required="">
                <option value="" selected disabled>Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br>
              </td>
              </tr>
              <tr>
              <td>
             <label for="sim_qlty">How would you rate the singing Quality (clarity)</label>
             </td>
             <td>
              <select name="sim_qlty" id="sim_qlty" required="">
                <option value="" selected disabled>Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br>
              </td>
              </tr>
              <tr>
              <td>
     <label for="synth_phoneme">How would you rate the phoneme quality of synthesized audio<br>
     </label></td>
     <td>
              <select name="synth_phoneme" id="synth_phoneme" required="">
                <option value="" selected disabled>Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br>
              </td>
              </tr>
              <tr>
              <td>
               <label for="synth_speaker">How well does synthesized song adapts to reference speaker voice<br></label>
               </td>
               <td>
              <select name="synth_speaker" id="synth_speaker" required="">
                <option value="" selected disabled>Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br> 
              </td>
              </tr>
              </table>
              </div>
                </td>
                 <td><audio controls controlsList="nodownload" preload="none" style="height:30px">
                  <source src="https://ismir21.github.io/T2S/Samples/WithGAN/SAMU/samu_5_hum.wav" type="audio/mpeg">audio not supported</audio>
                    <div style="font-size:14px;text-align: left;">
              <table>
              <tr>
              <td>
              <label for="sim_mel_t2s">How well does synthesized song adapts to target melody</label></td>
              <td>
              <select name="sim_mel_t2s" id="sim_mel_t2s" required="">
                <option value="" selected disabled>Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br>
              </td>
              </tr>
              <tr>
              <td>
             <label for="sim_qlty_t2s">How would you rate the singing Quality (clarity)</label>
             </td>
             <td>
              <select name="sim_qlty_t2s" id="sim_qlty_t2s" required="">
                <option value="" selected disabled>Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br>
              </td>
              </tr>
              <tr>
              <td>
     <label for="synth_phoneme_t2s">How would you rate the phoneme quality of synthesized audio<br>
     </label></td>
     <td>
              <select name="synth_phoneme_t2s" id="synth_phoneme_t2s" required="">
                <option value="" selected disabled>Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br>
              </td>
              </tr>
              <tr>
              <td>
               <label for="synth_speaker_t2s">How well does synthesized song adapts to reference speaker voice<br></label>
               </td>
               <td>
              <select name="synth_speaker_t2s" id="synth_speaker_t2s" required="">
                <option value="" selected disabled>Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br> 
              </td>
              </tr>
              </table>
              </div>
                  </td>
                  </tr>
              </tbody></table>  
              </div>    
                <div class='grrp'>  
    <h3>Singer4</h3>
              <table border="0" style="font-size:16px">
              <tbody>
                <tr>                
                <th bgcolor="lightblue" style="white-space:nowrap;height:30px;min-width: 240px">
                 </th>               
                <th bgcolor="lightblue" style="white-space:nowrap;height:30px;min-width: 240px">
                 Synthesized Song with Model 1</th>                
                <th bgcolor="lightblue" style="white-space:nowrap;height:30px;min-width: 240px">
                 Synthesized Song with Model 2</th></tr>
              <tr>
              <td>
              <div  style="background-color: lightblue;white-space:nowrap;height:30px;min-width: 240px">
                 Lyrics</div> 
                 <div> Edelweiss, Edelweiss Every morning you greet me</div>
                    <div  style="background-color: lightblue;white-space:nowrap;height:30px;min-width: 240px">
                 Target Melody</div>  
              <audio controls controlsList="nodownload" preload="none" style="height:30px"><source src="https://ismir21.github.io/T2S/Samples/Recordings/1_singing.mp3" type="audio/mpeg">audio not supported</audio>            
              <div  style="background-color: lightblue;white-space:nowrap;height:30px;min-width: 240px">
                 Target Singer Voice</div>                  
                 <audio controls controlsList="nodownload" preload="none" style="height:30px"><source src="https://ismir21.github.io/T2S/Samples/Speech/Singer3_Voice.mp3" type="audio/mpeg">audio not supported</audio> 
                </td>
              <td>
              <audio controls controlsList="nodownload" preload="none" style="height:30px"><source src="https://ismir21.github.io/T2S/Samples/WithoutGAN/RESNA/resna_1_sing.wav" type="audio/mpeg">audio not supported</audio>
              <div style="font-size:14px;text-align: left;">
              <table>
              <tr>
              <td>
              <label for="sim_mel">How well does synthesized song adapts to target melody</label></td>
              <td>
              <select name="sim_mel" id="sim_mel" required="">
                <option value="" selected disabled>Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br>
              </td>
              </tr>
              <tr>
              <td>
             <label for="sim_qlty">How would you rate the singing Quality (clarity)</label>
             </td>
             <td>
              <select name="sim_qlty" id="sim_qlty" required="">
                <option value="" selected disabled>Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br>
              </td>
              </tr>
              <tr>
              <td>
     <label for="synth_phoneme">How would you rate the phoneme quality of synthesized audio<br>
     </label></td>
     <td>
              <select name="synth_phoneme" id="synth_phoneme" required="">
                <option value="" selected disabled>Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br>
              </td>
              </tr>
              <tr>
              <td>
               <label for="synth_speaker">How well does synthesized song adapts to reference speaker voice<br></label>
               </td>
               <td>
              <select name="synth_speaker" id="synth_speaker" required="">
                <option value="" selected disabled>Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br> 
              </td>
              </tr>
              </table>
              </div>
                </td>
                 <td><audio controls controlsList="nodownload" preload="none" style="height:30px">
                  <source src="https://ismir21.github.io/T2S/Samples/WithGAN/RESNA/resna_1_sing.wav" type="audio/mpeg">audio not supported</audio>
                    <div style="font-size:14px;text-align: left;">
              <table>
              <tr>
              <td>
              <label for="sim_mel_t2s">How well does synthesized song adapts to target melody</label></td>
              <td>
              <select name="sim_mel_t2s" id="sim_mel_t2s" required="">
                <option value="" selected disabled>Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br>
              </td>
              </tr>
              <tr>
              <td>
             <label for="sim_qlty_t2s">How would you rate the singing Quality (clarity)</label>
             </td>
             <td>
              <select name="sim_qlty_t2s" id="sim_qlty_t2s" required="">
                <option value="" selected disabled>Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br>
              </td>
              </tr>
              <tr>
              <td>
     <label for="synth_phoneme_t2s">How would you rate the phoneme quality of synthesized audio<br>
     </label></td>
     <td>
              <select name="synth_phoneme_t2s" id="synth_phoneme_t2s" required="">
                <option value="" selected disabled>Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br>
              </td>
              </tr>
              <tr>
              <td>
               <label for="synth_speaker_t2s">How well does synthesized song adapts to reference speaker voice<br></label>
               </td>
               <td>
              <select name="synth_speaker_t2s" id="synth_speaker_t2s" required="">
                <option value="" selected disabled>Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br> 
              </td>
              </tr>
              </table>
              </div>
                  </td>
                  </tr>
              <tr>
              <td>
              <div  style="background-color: lightblue;white-space:nowrap;height:30px;min-width: 240px">
                 Lyrics</div> 
                 <div> Edelweiss, Edelweiss Every morning you greet me</div>
                    <div  style="background-color: lightblue;white-space:nowrap;height:30px;min-width: 240px">
                 Target Melody</div>  
              <audio controls controlsList="nodownload" preload="none" style="height:30px"><source src="https://ismir21.github.io/T2S/Samples/Recordings/1_humming.mp3" type="audio/mpeg">audio not supported</audio>            
             </td>
              <td>
              <audio controls controlsList="nodownload" preload="none" style="height:30px"><source src="https://ismir21.github.io/T2S/Samples/WithoutGAN/RESNA/resna_1_hum.wav" type="audio/mpeg">audio not supported</audio>
              <div style="font-size:14px;text-align: left;">
              <table>
              <tr>
              <td>
              <label for="sim_mel">How well does synthesized song adapts to target melody</label></td>
              <td>
              <select name="sim_mel" id="sim_mel" required="">
                <option value="" selected disabled>Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br>
              </td>
              </tr>
              <tr>
              <td>
             <label for="sim_qlty">How would you rate the singing Quality (clarity)</label>
             </td>
             <td>
              <select name="sim_qlty" id="sim_qlty" required="">
                <option value="" selected disabled>Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br>
              </td>
              </tr>
              <tr>
              <td>
     <label for="synth_phoneme">How would you rate the phoneme quality of synthesized audio<br>
     </label></td>
     <td>
              <select name="synth_phoneme" id="synth_phoneme" required="">
                <option value="" selected disabled>Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br>
              </td>
              </tr>
              <tr>
              <td>
               <label for="synth_speaker">How well does synthesized song adapts to reference speaker voice<br></label>
               </td>
               <td>
              <select name="synth_speaker" id="synth_speaker" required="">
                <option value="" selected disabled>Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br> 
              </td>
              </tr>
              </table>
              </div>
                </td>
                 <td><audio controls controlsList="nodownload" preload="none" style="height:30px">
                  <source src="https://ismir21.github.io/T2S/Samples/WithGAN/RESNA/resna_1_hum.wav" type="audio/mpeg">audio not supported</audio>
                    <div style="font-size:14px;text-align: left;">
              <table>
              <tr>
              <td>
              <label for="sim_mel_t2s">How well does synthesized song adapts to target melody</label></td>
              <td>
              <select name="sim_mel_t2s" id="sim_mel_t2s" required="">
                <option value="" selected disabled>Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br>
              </td>
              </tr>
              <tr>
              <td>
             <label for="sim_qlty_t2s">How would you rate the singing Quality (clarity)</label>
             </td>
             <td>
              <select name="sim_qlty_t2s" id="sim_qlty_t2s" required="">
                <option value="" selected disabled>Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br>
              </td>
              </tr>
              <tr>
              <td>
     <label for="synth_phoneme_t2s">How would you rate the phoneme quality of synthesized audio<br>
     </label></td>
     <td>
              <select name="synth_phoneme_t2s" id="synth_phoneme_t2s" required="">
                <option value="" selected disabled>Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br>
              </td>
              </tr>
              <tr>
              <td>
               <label for="synth_speaker_t2s">How well does synthesized song adapts to reference speaker voice<br></label>
               </td>
               <td>
              <select name="synth_speaker_t2s" id="synth_speaker_t2s" required="">
                <option value="" selected disabled>Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br> 
              </td>
              </tr>
              </table>
              </div>
              </td>
              </tr>
               <tr>
              <td>
              <div  style="background-color: lightblue;white-space:nowrap;height:30px;min-width: 240px">
                 Lyrics</div> 
                 <div> Love in your eyes Sitting silent by my side</div>
                    <div  style="background-color: lightblue;white-space:nowrap;height:30px;min-width: 240px">
                 Target Melody</div>  
              <audio controls controlsList="nodownload" preload="none" style="height:30px"><source src="https://ismir21.github.io/T2S/Samples/Recordings/2_singing.mp3" type="audio/mpeg">audio not supported</audio>            
              </td>
              <td>
              <audio controls controlsList="nodownload" preload="none" style="height:30px"><source src="https://ismir21.github.io/T2S/Samples/WithoutGAN/RESNA/resna_2_sing.wav" type="audio/mpeg">audio not supported</audio>
              <div style="font-size:14px;text-align: left;">
              <table>
              <tr>
              <td>
              <label for="sim_mel">How well does synthesized song adapts to target melody</label></td>
              <td>
              <select name="sim_mel" id="sim_mel" required="">
                <option value="" selected disabled>Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br>
              </td>
              </tr>
              <tr>
              <td>
             <label for="sim_qlty">How would you rate the singing Quality (clarity)</label>
             </td>
             <td>
              <select name="sim_qlty" id="sim_qlty" required="">
                <option value="" selected disabled>Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br>
              </td>
              </tr>
              <tr>
              <td>
     <label for="synth_phoneme">How would you rate the phoneme quality of synthesized audio<br>
     </label></td>
     <td>
              <select name="synth_phoneme" id="synth_phoneme" required="">
                <option value="" selected disabled>Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br>
              </td>
              </tr>
              <tr>
              <td>
               <label for="synth_speaker">How well does synthesized song adapts to reference speaker voice<br></label>
               </td>
               <td>
              <select name="synth_speaker" id="synth_speaker" required="">
                <option value="" selected disabled>Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br> 
              </td>
              </tr>
              </table>
              </div>
                </td>
                 <td><audio controls controlsList="nodownload" preload="none" style="height:30px">
                  <source src="https://ismir21.github.io/T2S/Samples/WithGAN/RESNA/resna_2_sing.wav" type="audio/mpeg">audio not supported</audio>
                    <div style="font-size:14px;text-align: left;">
              <table>
              <tr>
              <td>
              <label for="sim_mel_t2s">How well does synthesized song adapts to target melody</label></td>
              <td>
              <select name="sim_mel_t2s" id="sim_mel_t2s" required="">
                <option value="" selected disabled>Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br>
              </td>
              </tr>
              <tr>
              <td>
             <label for="sim_qlty_t2s">How would you rate the singing Quality (clarity)</label>
             </td>
             <td>
              <select name="sim_qlty_t2s" id="sim_qlty_t2s" required="">
                <option value="" selected disabled>Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br>
              </td>
              </tr>
              <tr>
              <td>
     <label for="synth_phoneme_t2s">How would you rate the phoneme quality of synthesized audio<br>
     </label></td>
     <td>
              <select name="synth_phoneme_t2s" id="synth_phoneme_t2s" required="">
                <option value="" selected disabled>Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br>
              </td>
              </tr>
              <tr>
              <td>
               <label for="synth_speaker_t2s">How well does synthesized song adapts to reference speaker voice<br></label>
               </td>
               <td>
              <select name="synth_speaker_t2s" id="synth_speaker_t2s" required="">
                <option value="" selected disabled>Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br> 
              </td>
              </tr>
              </table>
              </div>
                  </td>
                  </tr>
                   <tr>
              <td>
              <div  style="background-color: lightblue;white-space:nowrap;height:30px;min-width: 240px">
                 Lyrics</div> 
                 <div> Love in your eyes Sitting silent by my side</div>
                    <div  style="background-color: lightblue;white-space:nowrap;height:30px;min-width: 240px">
                 Target Melody</div>  
              <audio controls controlsList="nodownload" preload="none" style="height:30px"><source src="https://ismir21.github.io/T2S/Samples/Recordings/2_humming.mp3" type="audio/mpeg">audio not supported</audio>            
              </td>
              <td>
              <audio controls controlsList="nodownload" preload="none" style="height:30px"><source src="https://ismir21.github.io/T2S/Samples/WithoutGAN/RESNA/resna_2_hum.wav" type="audio/mpeg">audio not supported</audio>
              <div style="font-size:14px;text-align: left;">
              <table>
              <tr>
              <td>
              <label for="sim_mel">How well does synthesized song adapts to target melody</label></td>
              <td>
              <select name="sim_mel" id="sim_mel" required="">
                <option value="" selected disabled>Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br>
              </td>
              </tr>
              <tr>
              <td>
             <label for="sim_qlty">How would you rate the singing Quality (clarity)</label>
             </td>
             <td>
              <select name="sim_qlty" id="sim_qlty" required="">
                <option value="" selected disabled>Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br>
              </td>
              </tr>
              <tr>
              <td>
     <label for="synth_phoneme">How would you rate the phoneme quality of synthesized audio<br>
     </label></td>
     <td>
              <select name="synth_phoneme" id="synth_phoneme" required="">
                <option value="" selected disabled>Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br>
              </td>
              </tr>
              <tr>
              <td>
               <label for="synth_speaker">How well does synthesized song adapts to reference speaker voice<br></label>
               </td>
               <td>
              <select name="synth_speaker" id="synth_speaker" required="">
                <option value="" selected disabled>Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br> 
              </td>
              </tr>
              </table>
              </div>
                </td>
                 <td><audio controls controlsList="nodownload" preload="none" style="height:30px">
                  <source src="https://ismir21.github.io/T2S/Samples/WithGAN/RESNA/resna_2_hum.wav" type="audio/mpeg">audio not supported</audio>
                    <div style="font-size:14px;text-align: left;">
              <table>
              <tr>
              <td>
              <label for="sim_mel_t2s">How well does synthesized song adapts to target melody</label></td>
              <td>
              <select name="sim_mel_t2s" id="sim_mel_t2s" required="">
                <option value="" selected disabled>Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br>
              </td>
              </tr>
              <tr>
              <td>
             <label for="sim_qlty_t2s">How would you rate the singing Quality (clarity)</label>
             </td>
             <td>
              <select name="sim_qlty_t2s" id="sim_qlty_t2s" required="">
                <option value="" selected disabled>Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br>
              </td>
              </tr>
              <tr>
              <td>
     <label for="synth_phoneme_t2s">How would you rate the phoneme quality of synthesized audio<br>
     </label></td>
     <td>
              <select name="synth_phoneme_t2s" id="synth_phoneme_t2s" required="">
                <option value="" selected disabled>Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br>
              </td>
              </tr>
              <tr>
              <td>
               <label for="synth_speaker_t2s">How well does synthesized song adapts to reference speaker voice<br></label>
               </td>
               <td>
              <select name="synth_speaker_t2s" id="synth_speaker_t2s" required="">
                <option value="" selected disabled>Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br> 
              </td>
              </tr>
              </table>
              </div>
                  </td>
                  </tr>
                                 <tr>
              <td>
              <div  style="background-color: lightblue;white-space:nowrap;height:30px;min-width: 240px">
                 Lyrics</div> 
                 <div> I'm just a little bit caught in the middle Life is a maze, and love is a riddle</div>
                    <div  style="background-color: lightblue;white-space:nowrap;height:30px;min-width: 240px">
                 Target Melody</div>  
              <audio controls controlsList="nodownload" preload="none" style="height:30px"><source src="https://ismir21.github.io/T2S/Samples/Recordings/3_singing.mp3" type="audio/mpeg">audio not supported</audio>            
              </td>
              <td>
              <audio controls controlsList="nodownload" preload="none" style="height:30px"><source src="https://ismir21.github.io/T2S/Samples/WithoutGAN/RESNA/resna_3_sing.wav" type="audio/mpeg">audio not supported</audio>
              <div style="font-size:14px;text-align: left;">
              <table>
              <tr>
              <td>
              <label for="sim_mel">How well does synthesized song adapts to target melody</label></td>
              <td>
              <select name="sim_mel" id="sim_mel" required="">
                <option value="" selected disabled>Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br>
              </td>
              </tr>
              <tr>
              <td>
             <label for="sim_qlty">How would you rate the singing Quality (clarity)</label>
             </td>
             <td>
              <select name="sim_qlty" id="sim_qlty" required="">
                <option value="" selected disabled>Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br>
              </td>
              </tr>
              <tr>
              <td>
     <label for="synth_phoneme">How would you rate the phoneme quality of synthesized audio<br>
     </label></td>
     <td>
              <select name="synth_phoneme" id="synth_phoneme" required="">
                <option value="" selected disabled>Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br>
              </td>
              </tr>
              <tr>
              <td>
               <label for="synth_speaker">How well does synthesized song adapts to reference speaker voice<br></label>
               </td>
               <td>
              <select name="synth_speaker" id="synth_speaker" required="">
                <option value="" selected disabled>Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br> 
              </td>
              </tr>
              </table>
              </div>
                </td>
                 <td><audio controls controlsList="nodownload" preload="none" style="height:30px">
                  <source src="https://ismir21.github.io/T2S/Samples/WithGAN/RESNA/resna_3_sing.wav" type="audio/mpeg">audio not supported</audio>
                    <div style="font-size:14px;text-align: left;">
              <table>
              <tr>
              <td>
              <label for="sim_mel_t2s">How well does synthesized song adapts to target melody</label></td>
              <td>
              <select name="sim_mel_t2s" id="sim_mel_t2s" required="">
                <option value="" selected disabled>Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br>
              </td>
              </tr>
              <tr>
              <td>
             <label for="sim_qlty_t2s">How would you rate the singing Quality (clarity)</label>
             </td>
             <td>
              <select name="sim_qlty_t2s" id="sim_qlty_t2s" required="">
                <option value="" selected disabled>Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br>
              </td>
              </tr>
              <tr>
              <td>
     <label for="synth_phoneme_t2s">How would you rate the phoneme quality of synthesized audio<br>
     </label></td>
     <td>
              <select name="synth_phoneme_t2s" id="synth_phoneme_t2s" required="">
                <option value="" selected disabled>Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br>
              </td>
              </tr>
              <tr>
              <td>
               <label for="synth_speaker_t2s">How well does synthesized song adapts to reference speaker voice<br></label>
               </td>
               <td>
              <select name="synth_speaker_t2s" id="synth_speaker_t2s" required="">
                <option value="" selected disabled>Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br> 
              </td>
              </tr>
              </table>
              </div>
                  </td>
                  </tr>
                   <tr>
              <td>
              <div  style="background-color: lightblue;white-space:nowrap;height:30px;min-width: 240px">
                 Lyrics</div> 
                 <div> I'm just a little bit caught in the middle Life is a maze, and love is a riddle</div>
                    <div  style="background-color: lightblue;white-space:nowrap;height:30px;min-width: 240px">
                 Target Melody</div>  
              <audio controls controlsList="nodownload" preload="none" style="height:30px"><source src="https://ismir21.github.io/T2S/Samples/Recordings/3_humming.mp3" type="audio/mpeg">audio not supported</audio>            
              </td>
              <td>
              <audio controls controlsList="nodownload" preload="none" style="height:30px"><source src="https://ismir21.github.io/T2S/Samples/WithoutGAN/RESNA/resna_3_hum.wav" type="audio/mpeg">audio not supported</audio>
              <div style="font-size:14px;text-align: left;">
              <table>
              <tr>
              <td>
              <label for="sim_mel">How well does synthesized song adapts to target melody</label></td>
              <td>
              <select name="sim_mel" id="sim_mel" required="">
                <option value="" selected disabled>Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br>
              </td>
              </tr>
              <tr>
              <td>
             <label for="sim_qlty">How would you rate the singing Quality (clarity)</label>
             </td>
             <td>
              <select name="sim_qlty" id="sim_qlty" required="">
                <option value="" selected disabled>Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br>
              </td>
              </tr>
              <tr>
              <td>
     <label for="synth_phoneme">How would you rate the phoneme quality of synthesized audio<br>
     </label></td>
     <td>
              <select name="synth_phoneme" id="synth_phoneme" required="">
                <option value="" selected disabled>Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br>
              </td>
              </tr>
              <tr>
              <td>
               <label for="synth_speaker">How well does synthesized song adapts to reference speaker voice<br></label>
               </td>
               <td>
              <select name="synth_speaker" id="synth_speaker" required="">
                <option value="" selected disabled>Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br> 
              </td>
              </tr>
              </table>
              </div>
                </td>
                 <td><audio controls controlsList="nodownload" preload="none" style="height:30px">
                  <source src="https://ismir21.github.io/T2S/Samples/WithGAN/RESNA/resna_3_hum.wav" type="audio/mpeg">audio not supported</audio>
                    <div style="font-size:14px;text-align: left;">
              <table>
              <tr>
              <td>
              <label for="sim_mel_t2s">How well does synthesized song adapts to target melody</label></td>
              <td>
              <select name="sim_mel_t2s" id="sim_mel_t2s" required="">
                <option value="" selected disabled>Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br>
              </td>
              </tr>
              <tr>
              <td>
             <label for="sim_qlty_t2s">How would you rate the singing Quality (clarity)</label>
             </td>
             <td>
              <select name="sim_qlty_t2s" id="sim_qlty_t2s" required="">
                <option value="" selected disabled>Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br>
              </td>
              </tr>
              <tr>
              <td>
     <label for="synth_phoneme_t2s">How would you rate the phoneme quality of synthesized audio<br>
     </label></td>
     <td>
              <select name="synth_phoneme_t2s" id="synth_phoneme_t2s" required="">
                <option value="" selected disabled>Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br>
              </td>
              </tr>
              <tr>
              <td>
               <label for="synth_speaker_t2s">How well does synthesized song adapts to reference speaker voice<br></label>
               </td>
               <td>
              <select name="synth_speaker_t2s" id="synth_speaker_t2s" required="">
                <option value="" selected disabled>Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br> 
              </td>
              </tr>
              </table>
              </div>
                  </td>
                  </tr>
                                 <tr>
              <td>
              <div  style="background-color: lightblue;white-space:nowrap;height:30px;min-width: 240px">
                 Lyrics</div> 
                 <div> Slow it down, make it stop Or else my heart is going to pop</div>
                    <div  style="background-color: lightblue;white-space:nowrap;height:30px;min-width: 240px">
                 Target Melody</div>  
              <audio controls controlsList="nodownload" preload="none" style="height:30px"><source src="https://ismir21.github.io/T2S/Samples/Recordings/4_singing.mp3" type="audio/mpeg">audio not supported</audio>            
              </td>
              <td>
              <audio controls controlsList="nodownload" preload="none" style="height:30px"><source src="https://ismir21.github.io/T2S/Samples/WithoutGAN/RESNA/resna_4_sing.wav" type="audio/mpeg">audio not supported</audio>
              <div style="font-size:14px;text-align: left;">
              <table>
              <tr>
              <td>
              <label for="sim_mel">How well does synthesized song adapts to target melody</label></td>
              <td>
              <select name="sim_mel" id="sim_mel" required="">
                <option value="" selected disabled>Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br>
              </td>
              </tr>
              <tr>
              <td>
             <label for="sim_qlty">How would you rate the singing Quality (clarity)</label>
             </td>
             <td>
              <select name="sim_qlty" id="sim_qlty" required="">
                <option value="" selected disabled>Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br>
              </td>
              </tr>
              <tr>
              <td>
     <label for="synth_phoneme">How would you rate the phoneme quality of synthesized audio<br>
     </label></td>
     <td>
              <select name="synth_phoneme" id="synth_phoneme" required="">
                <option value="" selected disabled>Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br>
              </td>
              </tr>
              <tr>
              <td>
               <label for="synth_speaker">How well does synthesized song adapts to reference speaker voice<br></label>
               </td>
               <td>
              <select name="synth_speaker" id="synth_speaker" required="">
                <option value="" selected disabled>Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br> 
              </td>
              </tr>
              </table>
              </div>
                </td>
                 <td><audio controls controlsList="nodownload" preload="none" style="height:30px">
                  <source src="https://ismir21.github.io/T2S/Samples/WithGAN/RESNA/resna_4_sing.wav" type="audio/mpeg">audio not supported</audio>
                    <div style="font-size:14px;text-align: left;">
              <table>
              <tr>
              <td>
              <label for="sim_mel_t2s">How well does synthesized song adapts to target melody</label></td>
              <td>
              <select name="sim_mel_t2s" id="sim_mel_t2s" required="">
                <option value="" selected disabled>Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br>
              </td>
              </tr>
              <tr>
              <td>
             <label for="sim_qlty_t2s">How would you rate the singing Quality (clarity)</label>
             </td>
             <td>
              <select name="sim_qlty_t2s" id="sim_qlty_t2s" required="">
                <option value="" selected disabled>Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br>
              </td>
              </tr>
              <tr>
              <td>
     <label for="synth_phoneme_t2s">How would you rate the phoneme quality of synthesized audio<br>
     </label></td>
     <td>
              <select name="synth_phoneme_t2s" id="synth_phoneme_t2s" required="">
                <option value="" selected disabled>Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br>
              </td>
              </tr>
              <tr>
              <td>
               <label for="synth_speaker_t2s">How well does synthesized song adapts to reference speaker voice<br></label>
               </td>
               <td>
              <select name="synth_speaker_t2s" id="synth_speaker_t2s" required="">
                <option value="" selected disabled>Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br> 
              </td>
              </tr>
              </table>
              </div>
                  </td>
                  </tr>
                   <tr>
              <td>
              <div  style="background-color: lightblue;white-space:nowrap;height:30px;min-width: 240px">
                 Lyrics</div> 
                 <div> Slow it down, make it stop Or else my heart is going to pop</div>
                    <div  style="background-color: lightblue;white-space:nowrap;height:30px;min-width: 240px">
                 Target Melody</div>  
              <audio controls controlsList="nodownload" preload="none" style="height:30px"><source src="https://ismir21.github.io/T2S/Samples/Recordings/4_humming.mp3" type="audio/mpeg">audio not supported</audio>            
              </td>
              <td>
              <audio controls controlsList="nodownload" preload="none" style="height:30px"><source src="https://ismir21.github.io/T2S/Samples/WithoutGAN/RESNA/resna_4_hum.wav" type="audio/mpeg">audio not supported</audio>
              <div style="font-size:14px;text-align: left;">
              <table>
              <tr>
              <td>
              <label for="sim_mel">How well does synthesized song adapts to target melody</label></td>
              <td>
              <select name="sim_mel" id="sim_mel" required="">
                <option value="" selected disabled>Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br>
              </td>
              </tr>
              <tr>
              <td>
             <label for="sim_qlty">How would you rate the singing Quality (clarity)</label>
             </td>
             <td>
              <select name="sim_qlty" id="sim_qlty" required="">
                <option value="" selected disabled>Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br>
              </td>
              </tr>
              <tr>
              <td>
     <label for="synth_phoneme">How would you rate the phoneme quality of synthesized audio<br>
     </label></td>
     <td>
              <select name="synth_phoneme" id="synth_phoneme" required="">
                <option value="" selected disabled>Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br>
              </td>
              </tr>
              <tr>
              <td>
               <label for="synth_speaker">How well does synthesized song adapts to reference speaker voice<br></label>
               </td>
               <td>
              <select name="synth_speaker" id="synth_speaker" required="">
                <option value="" selected disabled>Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br> 
              </td>
              </tr>
              </table>
              </div>
                </td>
                 <td><audio controls controlsList="nodownload" preload="none" style="height:30px">
                  <source src="https://ismir21.github.io/T2S/Samples/WithGAN/RESNA/resna_4_hum.wav" type="audio/mpeg">audio not supported</audio>
                    <div style="font-size:14px;text-align: left;">
              <table>
              <tr>
              <td>
              <label for="sim_mel_t2s">How well does synthesized song adapts to target melody</label></td>
              <td>
              <select name="sim_mel_t2s" id="sim_mel_t2s" required="">
                <option value="" selected disabled>Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br>
              </td>
              </tr>
              <tr>
              <td>
             <label for="sim_qlty_t2s">How would you rate the singing Quality (clarity)</label>
             </td>
             <td>
              <select name="sim_qlty_t2s" id="sim_qlty_t2s" required="">
                <option value="" selected disabled>Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br>
              </td>
              </tr>
              <tr>
              <td>
     <label for="synth_phoneme_t2s">How would you rate the phoneme quality of synthesized audio<br>
     </label></td>
     <td>
              <select name="synth_phoneme_t2s" id="synth_phoneme_t2s" required="">
                <option value="" selected disabled>Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br>
              </td>
              </tr>
              <tr>
              <td>
               <label for="synth_speaker_t2s">How well does synthesized song adapts to reference speaker voice<br></label>
               </td>
               <td>
              <select name="synth_speaker_t2s" id="synth_speaker_t2s" required="">
                <option value="" selected disabled>Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br> 
              </td>
              </tr>
              </table>
              </div>
                  </td>
                  </tr>
                                 <tr>
              <td>
              <div  style="background-color: lightblue;white-space:nowrap;height:30px;min-width: 240px">
                 Lyrics</div> 
                 <div> Love me tender,Love me sweet,Never let me go</div>
                    <div  style="background-color: lightblue;white-space:nowrap;height:30px;min-width: 240px">
                 Target Melody</div>  
              <audio controls controlsList="nodownload" preload="none" style="height:30px"><source src="https://ismir21.github.io/T2S/Samples/Recordings/5_singing.mp3" type="audio/mpeg">audio not supported</audio>            
              </td>
              <td>
              <audio controls controlsList="nodownload" preload="none" style="height:30px"><source src="https://ismir21.github.io/T2S/Samples/WithoutGAN/RESNA/resna_5_sing.wav" type="audio/mpeg">audio not supported</audio>
              <div style="font-size:14px;text-align: left;">
              <table>
              <tr>
              <td>
              <label for="sim_mel">How well does synthesized song adapts to target melody</label></td>
              <td>
              <select name="sim_mel" id="sim_mel" required="">
                <option value="" selected disabled>Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br>
              </td>
              </tr>
              <tr>
              <td>
             <label for="sim_qlty">How would you rate the singing Quality (clarity)</label>
             </td>
             <td>
              <select name="sim_qlty" id="sim_qlty" required="">
                <option value="" selected disabled>Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br>
              </td>
              </tr>
              <tr>
              <td>
     <label for="synth_phoneme">How would you rate the phoneme quality of synthesized audio<br>
     </label></td>
     <td>
              <select name="synth_phoneme" id="synth_phoneme" required="">
                <option value="" selected disabled>Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br>
              </td>
              </tr>
              <tr>
              <td>
               <label for="synth_speaker">How well does synthesized song adapts to reference speaker voice<br></label>
               </td>
               <td>
              <select name="synth_speaker" id="synth_speaker" required="">
                <option value="" selected disabled>Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br> 
              </td>
              </tr>
              </table>
              </div>
                </td>
                 <td><audio controls controlsList="nodownload" preload="none" style="height:30px">
                  <source src="https://ismir21.github.io/T2S/Samples/WithGAN/RESNA/resna_5_sing.wav" type="audio/mpeg">audio not supported</audio>
                    <div style="font-size:14px;text-align: left;">
              <table>
              <tr>
              <td>
              <label for="sim_mel_t2s">How well does synthesized song adapts to target melody</label></td>
              <td>
              <select name="sim_mel_t2s" id="sim_mel_t2s" required="">
                <option value="" selected disabled>Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br>
              </td>
              </tr>
              <tr>
              <td>
             <label for="sim_qlty_t2s">How would you rate the singing Quality (clarity)</label>
             </td>
             <td>
              <select name="sim_qlty_t2s" id="sim_qlty_t2s" required="">
                <option value="" selected disabled>Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br>
              </td>
              </tr>
              <tr>
              <td>
     <label for="synth_phoneme_t2s">How would you rate the phoneme quality of synthesized audio<br>
     </label></td>
     <td>
              <select name="synth_phoneme_t2s" id="synth_phoneme_t2s" required="">
                <option value="" selected disabled>Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br>
              </td>
              </tr>
              <tr>
              <td>
               <label for="synth_speaker_t2s">How well does synthesized song adapts to reference speaker voice<br></label>
               </td>
               <td>
              <select name="synth_speaker_t2s" id="synth_speaker_t2s" required="">
                <option value="" selected disabled>Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br> 
              </td>
              </tr>
              </table>
              </div>
                  </td>
                  </tr>
                   <tr>
              <td>
              <div  style="background-color: lightblue;white-space:nowrap;height:30px;min-width: 240px">
                 Lyrics</div> 
                 <div> Love me tender,Love me sweet,Never let me go</div>
                    <div  style="background-color: lightblue;white-space:nowrap;height:30px;min-width: 240px">
                 Target Melody</div>  
              <audio controls controlsList="nodownload" preload="none" style="height:30px"><source src="https://ismir21.github.io/T2S/Samples/Recordings/5_humming.mp3" type="audio/mpeg">audio not supported</audio>            
              </td>
              <td>
              <audio controls controlsList="nodownload" preload="none" style="height:30px"><source src="https://ismir21.github.io/T2S/Samples/WithoutGAN/RESNA/resna_5_hum.wav" type="audio/mpeg">audio not supported</audio>
              <div style="font-size:14px;text-align: left;">
              <table>
              <tr>
              <td>
              <label for="sim_mel">How well does synthesized song adapts to target melody</label></td>
              <td>
              <select name="sim_mel" id="sim_mel" required="">
                <option value="" selected disabled>Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br>
              </td>
              </tr>
              <tr>
              <td>
             <label for="sim_qlty">How would you rate the singing Quality (clarity)</label>
             </td>
             <td>
              <select name="sim_qlty" id="sim_qlty" required="">
                <option value="" selected disabled>Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br>
              </td>
              </tr>
              <tr>
              <td>
     <label for="synth_phoneme">How would you rate the phoneme quality of synthesized audio<br>
     </label></td>
     <td>
              <select name="synth_phoneme" id="synth_phoneme" required="">
                <option value="" selected disabled>Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br>
              </td>
              </tr>
              <tr>
              <td>
               <label for="synth_speaker">How well does synthesized song adapts to reference speaker voice<br></label>
               </td>
               <td>
              <select name="synth_speaker" id="synth_speaker" required="">
                <option value="" selected disabled>Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br> 
              </td>
              </tr>
              </table>
              </div>
                </td>
                 <td><audio controls controlsList="nodownload" preload="none" style="height:30px">
                  <source src="https://ismir21.github.io/T2S/Samples/WithGAN/RESNA/resna_5_hum.wav" type="audio/mpeg">audio not supported</audio>
                    <div style="font-size:14px;text-align: left;">
              <table>
              <tr>
              <td>
              <label for="sim_mel_t2s">How well does synthesized song adapts to target melody</label></td>
              <td>
              <select name="sim_mel_t2s" id="sim_mel_t2s" required="">
                <option value="" selected disabled>Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br>
              </td>
              </tr>
              <tr>
              <td>
             <label for="sim_qlty_t2s">How would you rate the singing Quality (clarity)</label>
             </td>
             <td>
              <select name="sim_qlty_t2s" id="sim_qlty_t2s" required="">
                <option value="" selected disabled>Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br>
              </td>
              </tr>
              <tr>
              <td>
     <label for="synth_phoneme_t2s">How would you rate the phoneme quality of synthesized audio<br>
     </label></td>
     <td>
              <select name="synth_phoneme_t2s" id="synth_phoneme_t2s" required="">
                <option value="" selected disabled>Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br>
              </td>
              </tr>
              <tr>
              <td>
               <label for="synth_speaker_t2s">How well does synthesized song adapts to reference speaker voice<br></label>
               </td>
               <td>
              <select name="synth_speaker_t2s" id="synth_speaker_t2s" required="">
                <option value="" selected disabled>Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br> 
              </td>
              </tr>
              </table>
              </div>
                  </td>
                  </tr>
              </tbody></table>  
              </div>              
    <br><br>
     <button class="button1" type="submit">Send Responses</button>
     