<!DOCTYPE html>
<html>
  <body>
    <main>
      <h1>NBA Legends</h1>
      <section>
        <h2>Top NBA Moments</h2>
        <!-- TODO: Add link to NBA player photos -->
        <p>Witness more <a target="_blank" href="https://nba.com">epic NBA moments</a> in our gallery.</p>
        <a href="https://nba.com"><img src="https://example.com/nba-image.jpg" alt="A dynamic NBA game in action."></a>
      </section>
      <section>
        <h2>NBA Icons</h2>
        <h3>Legendary NBA players:</h3>
        <ul>
          <li>Michael Jordan</li>
          <li>LeBron James</li>
          <li>Kobe Bryant</li>
          <!-- Add more NBA players here -->
        </ul>
        <figure>
          <img src="https://example.com/nba-icon-image.jpg">
          <figcaption>Celebrating the NBA icons.</figcaption>
        </figure>
        <h3>Top NBA Teams:</h3>
        <ol>
          <li>Los Angeles Lakers</li>
          <li>Boston Celtics</li>
          <li>Chicago Bulls</li>
          <!-- Add more NBA teams here -->
        </ol>
        <figure>
          <img src="https://example.com/nba-teams-image.jpg">
          <figcaption>The power of NBA teams.</figcaption>
        </figure>
      </section>
      <section>
        <h2>Join the NBA Enthusiasts Community</h2>
        <form action="https://nba.com/submit-nba-photo">
          <fieldset>
            <legend>Are you an NBA enthusiast?</legend>
            <label><input id="yes" type="radio" name="enthusiast" value="yes"> Yes</label>
            <label><input id="no" type="radio" name="enthusiast" value="no"> No</label>
          </fieldset>
          <fieldset>
            <legend>Who is your favorite NBA player?</legend>
            <select name="favorite-player">
              <option value="jordan">Michael Jordan</option>
              <option value="lebron">LeBron James</option>
              <option value="kobe">Kobe Bryant</option>
              <!-- Add more NBA players here -->
            </select>
          </fieldset>
          <input type="text" name="nbaphotourl" placeholder="NBA photo URL" required>
          <button type="submit">Submit</button>
        </form>
      </section>
    </main>
  </body>
</html>

