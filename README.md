# prueba
PruebaChatBot
<input pattern="(hi|hello) *">
  <output value="Hi! What is your favorite color?"/>

  <context>
    <sample>
      <item>Green</item>
      <item>Blue</item>
      <item>Red</item>
    </sample>
    <input pattern="* $Color *">
      <output value="Nice! I like it too!"/>
    </input>
  </context>
</input>
