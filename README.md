=== Web Audio Loop Mixer - An experiment by Middle Ear Media. ===

Author: Obadiah Metivier
Author URI: http://middleearmedia.com/webaudioloopmixer/
Tags: web audio api, mixer, loop, html5, css3, javascript, jquery, middle ear media, obadiah metivier
Stable tag: 2.2.1

Web Audio Loop Mixer is a four channel mixer with effects. To get the party started, select an audio source file (mp3 or wav, etc.) from your hard drive for each channel.

== Description ==

Web Audio Loop Mixer is a four channel mixer with effects. To get the party started, select an audio source file (mp3 or wav, etc.) from your hard drive for each channel. It uses the Web Audio API, jQuery, jQuery Knob, and is based on Channel Strip.

== Changelog ==

= 1.0 =
* Start coding. Style vertical slider and knob controls for interface. Style strip. 04/25/2013.

* Add and style file select input for audio source. Add and style checkboxes for EQ, Compression, and Mute. Tweek performance of knob, slider, and checkbox controls. Add strip sections. Add description below. 04/30/2013.

* Finish coding. Clean up all files. Update readme.txt. 05/01/2013.

= 1.1 =
* Update code to match new spec. Remove webkit prefix. Replace noteOn() and noteOff() methods with start() and stop() methods. Replace createGainNode with createGain. 12/20/2014.

= 1.5 =
* Switch from vertical to horizontal strip. Remove strip background image. Change toggle switches from square to round. Fix slider and remove styles from slider. Change wording in browser note. 02/08/2015.

= 2.0 =
* Convert Channel Strip into four channel mixer. Fluidify CSS styles and convert all px into em. 02/08/2015.
* Rename variables and rewire into proper mixer matrix. Rename project Web Audio Loop Mixer. 02/09/2015.

= 2.1 =
* Add Delay knobs. Wire up FX and FX sends. Add Delay controls. 02/11/2015.
* Add Strip Titles. Get delay to work properly. 02/12/2015.

= 2.2 =
* Add Distortion function. Add Distortion knobs. Wire up FX and FX sends. Add Distortion controls. Add webkit fallback to audioContext. Change color of delay to pink. Change color of distortion to purple. Update readme.txt. 02/14/2015.

= 2.2.1 =
* Add CSS styles for the input range slider. 02/21/2015.