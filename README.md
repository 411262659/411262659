<!DOCTYPE html>
<html>
  <body>
    <main>
      <h1>Rap Legends</h1>
      <section>
        <h2>Top Rap Moments</h2>
        <!-- TODO: Add link to rap artist photos -->
        <p>Witness more <a target="_blank" href="https://raplegends.com">epic rap moments</a> in our gallery.</p>
        <a href="https://raplegends.com"><img src="https://example.com/rap-artist-image.jpg" alt="A dynamic rap performance in action."></a>
      </section>
      <section>
        <h2>Rap Icons</h2>
        <h3>Legendary rap artists:</h3>
        <ul>
          <li>Eminem</li>
          <li>Tupac Shakur</li>
          <li>Notorious B.I.G.</li>
        </ul>
        <figure>
          <img src="https://example.com/eminem-image.jpg" alt="An iconic image of Eminem on stage.">
          <figcaption>Celebrating the rap icons.</figcaption>
        </figure>
        <h3>Top Rap Groups:</h3>
        <ol>
          <li>Wu-Tang Clan</li>
          <li>N.W.A</li>
          <li>Run-D.M.C.</li>
        </ol>
        <figure>
          <img src="https://example.com/wu-tang-clan.jpg" alt="Wu-Tang Clan members in a group shot.">
          <figcaption>The power of rap groups.</figcaption>
        </figure>
      </section>
      <section>
        <h2>Join the Rap Enthusiasts Community</h2>
        <form action="https://raplegends.com/submit-rap-photo">
          <fieldset>
            <legend>Are you a rap enthusiast?</legend>
            <label><input id="yes" type="radio" name="enthusiast" value="yes"> Yes</label>
            <label><input id="no" type="radio" name="enthusiast" value="no"> No</label>
          </fieldset>
          <fieldset>
            <legend>Who is your favorite rap artist?</legend>
            <select name="favorite-artist">
              <option value="eminem">Eminem</option>
              <option value="tupac">Tupac Shakur</option>
              <option value="biggie">Notorious B.I.G.</option>
              <!-- Add more rap artists here -->
            </select>
          </fieldset>
          <input type="text" name="rapphotourl" placeholder="Rap photo URL" required>
          <button type="submit">Submit</button>
        </form>
      </section>
    </main>
  </body>
</html>
