<!DOCTYPE html>
<html>
  <head>
    <title>NBA Legends</title>
    <!-- 引入jQuery库 -->
    <script src="https://code.jquery.com/jquery-3.6.0.min.js"></script>
  </head>
  <body>
    <main>
      <h1>NBA Legends</h1>
      <section>
        <h2>Top NBA Moments</h2>
        <p>Witness more <a target="_blank" href="https://nba.com">epic NBA moments</a> in our gallery.</p>
        <a href="https://nba.com">
          <img id="nba-image" src="https://ichef.bbci.co.uk/onesport/cps/624/cpsprodpb/1139B/production/_110655507_kb.jpg" alt="A dynamic NBA game in action.">
        </a>
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
          <img src="https://cdn.nba.com/manage/2021/08/michael-jordan-looks.jpg">
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
          <img src="https://media.zenfs.com/en/sportsv.net/c2aa805bf81ac2dc5318b34ae72417e1">
          <figcaption>The power of NBA teams.</figcaption>
        </figure>
      </section>
    </main>

    <!-- jQuery功能示例：在单击图像时弹出提示框 -->
    <script>
      $(document).ready(function() {
        // 使用jQuery为图像添加单击事件处理
        $("#nba-image").click(function() {
          alert("hi");
        });
      });
    </script>
  </body>
</html>
