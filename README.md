

<html>
  <body>
    <main>
      <h1>嘿嘿嘿</h1>
      <section>
        <h2>閃電十一人</h2>
        <!-- TODO: Add link to 閃電十一人 photos -->
        <p>See more <a target="_blank" href="https://freecatphotoapp.com">閃電十一人 photos</a> in our gallery.</p>
        <a href="https://freecatphotoapp.com"><img src="https://cdn.freecodecamp.org/curriculum/cat-photo-app/relaxing-cat.jpg" alt="A cute orange cat lying on its back."></a>
      </section>
      <section>
        <h2>Cat Lists</h2>
        <h3>Things 閃電十一人 love:</h3>
        <ul>
          <li>soccer</li>
          <li>friends</li>
          <li>rice balls</li>
        </ul>
        <figure>
          <img src="https://cdn.freecodecamp.org/curriculum/cat-photo-app/lasagna.jpg" alt="A slice of lasagna on a plate.">
          <figcaption>閃電十一人 <em>love</em> rice balls.</figcaption>  
        </figure>
        <h3>Top 3 things 閃電十一人 hate:</h3>
        <ol>
          <li>flea treatment</li>
          <li>thunder</li>
          <li>other 閃電十一人</li>
        </ol>
        <figure>
          <img src="https://cdn.freecodecamp.org/curriculum/cat-photo-app/cats.jpg" alt="Five 閃電十一人 looking around a field.">
          <figcaption>閃電十一人 <strong>hate</strong> other 閃電十一人.</figcaption>  
        </figure>
      </section>
      <section>
        <h2>Cat Form</h2>
        <form action="https://freecatphotoapp.com/submit-cat-photo">
          <fieldset>
            <legend>Is your 閃電十一人 an indoor or outdoor 閃電十一人?</legend>
            <label><input id="indoor" type="radio" name="indoor-outdoor" value="indoor"> Indoor</label>
            <label><input id="outdoor" type="radio" name="indoor-outdoor" value="outdoor"> Outdoor</label>
          </fieldset>
          <fieldset>
            <legend>What's your 閃電十一人's personality?</legend>
            <input id="loving" type="checkbox" name="personality" value="loving"> <label for="loving">Loving</label>
            <input id="lazy" type="checkbox" name="personality" value="lazy"> <label for="lazy">Lazy</label>
            <input id="energetic" type="checkbox" name="personality" value="energetic"> <label for="energetic"> Energetic</label>
          </fieldset>
          <input type="text" name="catphotourl" placeholder="閃電十一人 photo URL" required>
          <button type="submit">Submit</button>
        </form>
      </section>
    </main>
  </body>
</html>
