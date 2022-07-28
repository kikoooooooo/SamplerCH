<h3 align="center"><em>Anyone Can Cook!</em></h3>
<h1 align="center">An image will be here because this is not out yet!!</h1>
<p align="right"><em>Version 1.0</em></p>
<hr/>
<details open="open">
  <summary><h2 style="display: inline-block">Table of Contents</h2></summary>
  <ol>
    <li><a href="#about">About</a></li>
    <li><a href="#installation">Installation</a></li>
    <li><a href="#usage">Usage</a></li>
    <li><a href="#configuration">Configuration</a></li>
    <li><a href="#legal">Legal</a></li>
    <li><a href="#roadmap">Roadmap</a></li>
  </ol>
</details>
<details>
  <summary><h2 style="display: inline-block">User Manual</h2></summary>
  <ol>
    <li><a href="#about">About</a></li>
    <li><a href="#installation">Installation</a></li>
    <li><a href="#requirements">Requirements (developers)</a></li>
    <li><a href="#assign-samples">Assign Samples</a></li>
    <li><a href="#create-samples">Create Samples</a></li>
    <li><a href="#sequence-audio">Sequence Audio</a></li>
    <li><a href="#isolate-stems">Isolate Stems</a></li>
    <li><a href="#assign-keybinds">Assign Keybinds</a></li>
    <li><a href="#assign-colors">Assign Colors</a></li>
    <li><a href="#thank-you-for-reading-">Closing</a></li>
  </ol>
</details>
<h2>About</h2>
<!--Please ignore the poor indentation. A-->
<p>
SamplerCh. is a simple, open source & free music production software. This software allows you to "chop" up audio files and turn them into samples--samples which you can assign to a 4x4 grid of "pads" that can be played with the press of a key. You then can record & sequence your preformances on the pads, allowing you to create songs; treat this software like an instrument, or in the words of Roger Linn: <em>"-think of it as the piano or violin of our time"</em>.
</p>
<p>
⠀⠀The software interface & functions are inspired by the early AKAI MPCs because I saw how <a href="https://www.youtube.com/watch?v=z73CcodfT_w&ab_channel=equiknockz">simple it was to create music on that machine</a> (not to undermine Pete). You are intended create music on the software as if you were preforming live on the hardware it is based off of, unlike a DAW software. Just click the record button & use all the features of the software at your disposal; please refer to the <a href="#user-manual">User Manual</a>.
</p>
<small>You can skip this section \/</small>
<p>
⠀⠀I began creating this software out of my personal passion for hip-hop beats: running out of storage on my phone from beats in Apple Garageband, I wanted to move my production to my computer. Early in development I gained a motive more than personal & decided to share this software as a freeware hoping to change the way "hip-hop" sounds in modern day. Basically (because I could go on about this): I believe modern day "hip-hop" is more like "hip-<strong>pop</strong>" because the capabilities & usage of the DAW softwares used by most producers today leads the producers to be satisfied with a bland, repetitive, "trap" sound to their music; bland & repetitive to a point I can compare their "hip-hop" music to pop. I feel that the capabilities & usage of <em>this</em> software will allow producers to have their own unique hip-hop productions just as the legendary producers who utilized the MPC during 90's-2000's did; not pop.
</p>
<p>
Basically--with this freeware, I hope to bring My & Linn's ideas about simplified music production to the digital environment.
<br/>
<strong><em>Anyone Can Cook!</em></strong>
</p>
<h2>Installation</h2>
<h3>Requirements</h3>
<h4>IGNORE THIS UNLESS YOU ARE GOING TO TINKER WITH THIS SOFTWARE; USERS SKIP TO <a href="#steps">STEPS</a>.</h4>
  <ul>
    <li>tkinter (Python 3 distribution)</li>
    <li></li> <!--audio library-->
    <li>pynput LATEST</li>
  </ul>
<h4>You should clone the repository and run <code>ch.py</code>, heavy notations are in the code; have fun & thank you :)</h4>
<h3>Steps</h3>
  <ol>
     <li>Download the latest release (<a href="#">Releases</a>)</li>
    <li>Extract Contents</li>
    <li>Launch Executable</li>
  </ol>
<h2>Usage</h2>
  <h3>Assign Samples</h3>
    <ol>
      <li>Click the pad you want the audio file to be assigned to</li>
      <li>Select desired audio file in the explorer (see: <a href="https://en.wikipedia.org/wiki/FFmpeg#Supported_codecs_and_formats" target="blank">FFMPEG Supported codecs and formats</a> {Wikipedia})</li>
      <li>Trigger assigned pad & audio will play</li>
    </ol>
   <h4>Your audio files should be stored in <code>./user/audio</code>.</h4>
  <h3>Create Samples</h3>
  <h4>Chop audio & make samples.</h4>
    <ol>
      <li>Open sampler</li>
      <li>Click import & select audio file</li>
      <li>Scrub to desired length</li>
      <li>Click Export</li> 
    </ol>
  <h3>Record Preformance</h3>
    <ol>
      <li>Click the record button</li>
      <li>Play your song on the pads</li>
      <li>Click the stop button</li>
      <li>Recording is saved to the user audio directory <code>./user/audio</code></li>
    </ol>
  <h3>Sequence Audio</h3>
  <h4>Loop audio while you record & preform.</h4>
    <ol>
      <li></li>
    </ol>
  <h3>Isolate Stems</h3>
  <h4>Isolate the various elements that make up a song, allows for clearer or more specific samples.</h4>
    <ol>
      <li>Select Audio File</li>
      <li>Choose Stem(s)</li>
      <li>Save Stem Where Desired</li>
    </ol>
<h2>Legal</h2>
  <h4>Copyright of kiko-o under a <a href="https://www.gnu.org/licenses/gpl-3.0.en.html">GNU General Public License (v3.0)</a> 2022</h4>
  <h3>License Declares:</h3>
    <ol>
      <li>Copyright is asserted upon this directory.</li>
      <li>You are free to copy and distribute modified versions of files in this directory.</li>
      <li>When you distribute a copy of files, you are obligated to pass on the same liberties to consumers of your distribution.</li>
      <li>Modified files are to be marked as changed.</li>
    </ol>
<h2>Configuration</h2>
<h4>Configure the application to your liking in the Settings Window.</h4>
  <h3>Assign Keybinds</h3>
  <h4>Reassign the keybinds in a way that you can trigger the pads comfortably.</h4>
    <ol>
      <li>Open Settings</li>
      <li>Default Keybinds are Listed</li>
      <li>Reassign Accordingly</li>
      <li>Save</li>
    </ol>
    <p>Note: Using keybinds does not trigger the pad graphic.</p>
  <h3>Assign Colors</h3>
    <ol>
      <li>Open Settings</li>
      <li>Input hex color code (<code>#XXXXX</code>) into desired widget.</li>
      <li>Save</li>
    </ol>
<h2>Roadmap</h2>
<h4>This software is currently under development, this is the development roadmap:</h4>
  ☑️ User Interface <em>7/17/22</em><br/>
  ☑️ User Config <em>7/28/22</em><br/>
  ⬜ Pads <em>x/x/xx</em><br/>
  ⬜ Sampler <em>x/x/xx</em><br/>
  ⬜ Recorder <em>x/x/xx</em><br/>
  ⬜ Sequencer <em>x/x/xx</em><br/>
  ⬜ Stem Isolater (?) <em>x/x/xx</em><br/>
  ⬜ Publication (Version 1.0) <em>x/x/xx</em> <!--🎉-->
<hr/>
 <h2 align="center"><a href="#anyone-can-cook">Thank You For Reading :)</a></h2>
 
 <h3 align="center">SamplerCh.</h3>
 <p align="center">
 [⠀][⠀][⠀][⠀]<br/>
 [⠀][⠀][⠀][⠀]<br/>
 [⠀][⠀][⠀][⠀]<br/>
 [⠀][⠀][⠀][⠀]<br/>
 </p>
 
 <h3 align="center">Contact Me: https://kiko-o.netlify.app/personal</h3>
