<script setup>
import SpoilerBlock from '@/components/widgets/SpoilerBlock.vue'
import ImageViewer from '@/components/widgets/ImageViewer.vue'
import { changeTitle } from '@/assets/tools.js'

changeTitle('Game Endings')
</script>

<template>
  <h1>Game Endings</h1>
  <h2>Description:</h2>
  <p>
    In Voices of the Void, there are multiple game endings. Each of these endings have different
    ways of being obtained and triggered.
  </p>

  <hr />

  <h3 id="normal">Normal Ending</h3>
  <p>To achieve this, you must play at least 44-45 days in story mode to unlock.</p>
  <SpoilerBlock>
    <p>
      This appears to be symbolic of Dr. Kel's insanity or the player's own character's insanity
      catching up to him.
    </p>
  </SpoilerBlock>

  <hr />

  <h3 id="worst">Worst Ending</h3>
  <p>
    To trigger this ending, you need to catch, download, process to level 3, and send over the
    <a href="../Signals/specialsigswiki.html#evil">Evil Signal</a>.
  </p>

  <ImageViewer src="/Images/GameEndings/1.png" alt="VOTV Archive Image" />

  <p>
    Once that is done, a bunch of warning emails or messages will appear telling you to delete that
    particular signal. And a white cube will appear below your world in front of the Kerfus facial
    animation, this is the Evil_C entity which spawned will give the player an X amount of time
    before the game over.
  </p>

  <ImageViewer src="/Images/GameEndings/2.png" alt="VOTV Archive Image" />

  <p>
    Assuming you ignore those messages and after a period of time you will be flashed a red screen
    which is essentally the evil texture just overlaying all over everything in you world.
  </p>

  <ImageViewer src="/Images/GameEndings/3.png" alt="VOTV Archive Image" />
  <ImageViewer src="/Images/GameEndings/4.png" alt="VOTV Archive Image" />
  <ImageViewer src="/Images/GameEndings/5.png" alt="VOTV Archive Image" />

  <p>
    Then you are shown a terminal in which it explains what happens to you. You are terminated and
    converted by some mysterious beings. In this ending you kill and convert everything on Earth.
    This is the result of the Evil spreading towards Earth.
  </p>

  <ImageViewer src="/Images/GameEndings/6.png" alt="VOTV Archive Image" />

  <SpoilerBlock>
    <p>
      While it is unknown who types out this message, it has been theorized to be the Arirals. The
      reason for this is the due to the fact that the only race that has gotten close to Dr Kel is
      the Arirals. So it would explain the Subject and State lines for it. This also explains the
      summary they give for Earth especially after what just happened to it. The conclusion they
      give seems to align with their mission and story.
    </p>
  </SpoilerBlock>
  <p></p>
  <h4>Transcript:</h4>
  <pre>
&gt;BEGIN

SUBJECT: DR_KEL
STATUS: TERMINATED

LOCATION: EARTH
STATUS: CONVERTED

CONCLUSION: CANCEL MISSION, RETURN BACK HOME, RETRIEVE RESOURCES, FOLLOW THE OBJECT

&gt;END

[GAME OVER]</pre
  >

  <hr />

  <h3 id="rufus">Secret Rufus Ending</h3>
  <p>
    There is no way to obtain this ending in the newer versions as the developers have removed the
    <a href="../Entities/entitieswiki.html#rufus">Rufus's</a> ability to trigger it, however in
    previous versions you would need to go to the command console and type in the
    <a href="../ConsoleCommands/consolecommandswiki.html#rufus">Console Command</a>. Soon after a
    <a href="../Entities/entitieswiki.html#rufus">Rufus Entity</a>
    will spawn in your world and will begin chasing you down. You can either walk in the direction
    of the
    <a href="../Objects/objectswiki.html#scp432">SCP-432</a> and cross paths with the
    <a href="../Entities/entitieswiki.html#rufus">Rufus Entity</a> or wait until it catches you.
  </p>

  <ImageViewer src="/Images/GameEndings/7.png" alt="VOTV Archive Image" />

  <p>
    As soon as you are caught it will promptly bring up a terminal screen similar to that of the
    Worst Ending however in this one you are killed due to "skill issue".
  </p>

  <ImageViewer src="/Images/GameEndings/8.png" alt="VOTV Archive Image" />

  <h4>Transcript:</h4>
  <pre>
    &gt;Begin
    skill issue
    get fukced
    lmao
    &gt;End</pre
  >

  <hr />

  <h3 id="badsun">Bad Sun Ending</h3>
  <p>
    When the
    <a href="../Events/triggerableeventswiki.html#badsun">Bad Sun Event</a>
    occurs, in order to trigger the ending you must die to the Bad Sun during the event.
  </p>

  <ImageViewer src="/Images/GameEndings/9.png" alt="VOTV Archive Image" />

  <p>
    As soon as you are killed it will promptly bring up a terminal screen similar to that of the
    <a href="#worst">Worst Ending</a> and <a href="#rufus">Secret Rufus Ending</a>. However in this
    one, more mysterious beings annihilate the sun and capture light.
  </p>

  <ImageViewer src="/Images/GameEndings/10.png" alt="VOTV Archive Image" />

  <SpoilerBlock>
    <p>
      It is also unknown who types out this message but it is theorized to be Rozitals. Since this
      message is very robotic like and mentions "All Units". This disproves the group of 3 Arirals
      present in this scene and would most likely align with the periodic Rozital entities that show
      up. Another thing to consider is the fact that the Rozitals don't know who Dr Kel is and don't
      interact with him. Due to this, the Rozitals only state only broad things such as "Location:
      Solar System" and "Status Unknown".
    </p>
  </SpoilerBlock>
  <p></p>
  <h4>Transcript:</h4>
  <pre>
>BEGIN

LOCATION: SOLAR SYSTEM
STATUS: UNKNOWN

CONCLUSION: IGNORE PROTOCOLS, ANNIHILATE THE SUN, RETRIEVE ALL UNITS, CAPTURE THE REMAINING LIGHT.

>END

[GAME OVER]</pre
  >
</template>
