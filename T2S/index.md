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
      <p>Listen to the original audio files of 5 different singers and provide feedback on the synthesized waveforms produced using two systems</p>
      <div class='grrp'>
       <table border="0" width="20%" style="font-size:16px">
          <tbody><tr>
         <th bgcolor="lightblue" style="white-space:nowrap;height:30px;min-width: 240px">
          Lyrics</th></tr>
          <tr>
           <td>"Edelweiss, Edelweiss 
          Every morning you greet me
          Small and white clean and bright
          You look happy to meet me
          Blossom of snow, may you bloom and grow
          Bloom and grow forever
          Edelweiss, Edelweiss"</td>
          </tr></tbody>
          </table>
      </div>
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
                 Target Melody</div>  
              <audio controls="" preload="none" style="height:30px"><source src="https://ismir21.github.io/T2S/Singer_1/ADIZ.wav" type="audio/mpeg">audio not supported</audio>            
              <div  style="background-color: lightblue;white-space:nowrap;height:30px;min-width: 240px">
                 Target Singer Voice</div>                  
                 <audio controls="" preload="none" style="height:30px"><source src="https://ismir21.github.io/T2S/Singer_1/Singer1_Voice.wav" type="audio/mpeg">audio not supported</audio> 
                </td>
              <td>
              <audio controls="" preload="none" style="height:30px"><source src="https://ismir21.github.io/T2S/Singer_1/Song1.wav" type="audio/mpeg">audio not supported</audio>
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
                 <td><audio controls="" preload="none" style="height:30px">
                  <source src="https://ismir21.github.io/T2S/Singer_1/Song2.wav" type="audio/mpeg">audio not supported</audio>
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
                 Target Melody</div>  
              <audio controls="" preload="none" style="height:30px"><source src="https://ismir21.github.io/T2S/Singer_1/Edelwise_hum.wav" type="audio/mpeg">audio not supported</audio>            
             </td>
              <td>
              <audio controls="" preload="none" style="height:30px"><source src="https://ismir21.github.io/T2S/Singer_1/pred_humming_adiz.wav" type="audio/mpeg">audio not supported</audio>
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
                 <td><audio controls="" preload="none" style="height:30px">
                  <source src="https://ismir21.github.io/T2S/Singer_1/synth_humming_adiz.wav" type="audio/mpeg">audio not supported</audio>
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
                 Target Melody</div>  
              <audio controls="" preload="none" style="height:30px"><source src="https://ismir21.github.io/T2S/Singer_2/Target_Melody.wav" type="audio/mpeg">audio not supported</audio>            
              <div  style="background-color: lightblue;white-space:nowrap;height:30px;min-width: 240px">
                 Target Singer Voice</div>                  
                 <audio controls="" preload="none" style="height:30px"><source src="https://ismir21.github.io/T2S/Singer_2/Speech.wav" type="audio/mpeg">audio not supported</audio> 
                </td>
              <td>
              <audio controls="" preload="none" style="height:30px"><source src="https://ismir21.github.io/T2S/Singer_2/Song1.wav" type="audio/mpeg">audio not supported</audio>
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
                 <td><audio controls="" preload="none" style="height:30px">
                  <source src="https://ismir21.github.io/T2S/Singer_2/Song2.wav" type="audio/mpeg">audio not supported</audio>
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
                 Target Melody</div>  
              <audio controls="" preload="none" style="height:30px"><source src="https://ismir21.github.io/T2S/Singer_2/humming 64.wav" type="audio/mpeg">audio not supported</audio>            
             </td>
              <td>
              <audio controls="" preload="none" style="height:30px"><source src="https://ismir21.github.io/T2S/Singer_2/pred_humming_samf.wav" type="audio/mpeg">audio not supported</audio>
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
                 <td><audio controls="" preload="none" style="height:30px">
                  <source src="https://ismir21.github.io/T2S/Singer_2/nus_SAMF_sing_Pair_2.output.wav" type="audio/mpeg">audio not supported</audio>
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
                 Target Melody</div>  
              <audio controls="" preload="none" style="height:30px"><source src="https://ismir21.github.io/T2S/Singer_1/ADIZ.wav" type="audio/mpeg">audio not supported</audio>            
              <div  style="background-color: lightblue;white-space:nowrap;height:30px;min-width: 240px">
                 Target Singer Voice</div>                  
                 <audio controls="" preload="none" style="height:30px"><source src="https://ismir21.github.io/T2S/Singer_6/test_emilia.wav" type="audio/mpeg">audio not supported</audio> 
                </td>
              <td>
              <audio controls="" preload="none" style="height:30px"><source src="https://ismir21.github.io/T2S/Singer_6/Song1.wav" type="audio/mpeg">audio not supported</audio>
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
                 <td><audio controls="" preload="none" style="height:30px">
                  <source src="https://ismir21.github.io/T2S/Singer_6/Song2.wav" type="audio/mpeg">audio not supported</audio>
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
                 Target Melody</div>  
              <audio controls="" preload="none" style="height:30px"><source src="https://ismir21.github.io/T2S/Singer_1/Edelwise_hum.wav" type="audio/mpeg">audio not supported</audio>            
             </td>
              <td>
              <audio controls="" preload="none" style="height:30px"><source src="https://ismir21.github.io/T2S/Singer_6/pred_humming_emilia.wav" type="audio/mpeg">audio not supported</audio>
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
                 <td><audio controls="" preload="none" style="height:30px">
                  <source src="https://ismir21.github.io/T2S/Singer_6/nus_EMIL_sing_Pair_6.output.wav" type="audio/mpeg">audio not supported</audio>
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
                 Target Melody</div>  
              <audio controls="" preload="none" style="height:30px"><source src="https://ismir21.github.io/T2S/Singer_2/Target_Melody.wav" type="audio/mpeg">audio not supported</audio>            
              <div  style="background-color: lightblue;white-space:nowrap;height:30px;min-width: 240px">
                 Target Singer Voice</div>                  
                 <audio controls="" preload="none" style="height:30px"><source src="https://ismir21.github.io/T2S/Singer_5/samuel_speech_inp" type="audio/mpeg">audio not supported</audio> 
                </td>
              <td>
              <audio controls="" preload="none" style="height:30px"><source src="https://ismir21.github.io/T2S/Singer_5/Song1.wav" type="audio/mpeg">audio not supported</audio>
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
                 <td><audio controls="" preload="none" style="height:30px">
                  <source src="https://ismir21.github.io/T2S/Singer_5/Song2.wav" type="audio/mpeg">audio not supported</audio>
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
                 Target Melody</div>  
              <audio controls="" preload="none" style="height:30px"><source src="https://ismir21.github.io/T2S/Singer_2/humming 64.wav" type="audio/mpeg">audio not supported</audio>            
             </td>
              <td>
              <audio controls="" preload="none" style="height:30px"><source src="https://ismir21.github.io/T2S/Singer_5/pred_humming_sam.wav" type="audio/mpeg">audio not supported</audio>
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
                 <td><audio controls="" preload="none" style="height:30px">
                  <source src="https://ismir21.github.io/T2S/Singer_5/nus_SAM_sing_Pair_5.output.wav" type="audio/mpeg">audio not supported</audio>
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
     