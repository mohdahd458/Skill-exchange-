<!DOCTYPE html>
<html lang="en" dir="ltr">
<head>
<meta charset="UTF-8" />
<meta name="viewport" content="width=device-width, initial-scale=1" />
<title>Skill Exchange</title>
<style>
  @import url('https://fonts.googleapis.com/css2?family=Cairo&display=swap');
  body {
    font-family: 'Cairo', sans-serif;
    margin: 0; padding: 0;
    background: linear-gradient(135deg, #A3D8F4, #F4E6D7);
    color: #333;
    min-height: 100vh;
    display: flex; justify-content: center; align-items: center;
    padding: 20px;
  }
  .container {
    background: #fff;
    border-radius: 15px;
    padding: 30px 40px;
    max-width: 400px;
    box-shadow: 0 6px 15px rgba(0,0,0,0.1);
    text-align: center;
  }
  h1 {
    margin-bottom: 10px;
    color: #0277BD;
  }
  p.description {
    font-size: 1.1em;
    margin-bottom: 30px;
    color: #555;
  }
  button.join-btn {
    background: #FF7043;
    color: #fff;
    border: none;
    border-radius: 30px;
    padding: 12px 30px;
    font-size: 1.1em;
    cursor: pointer;
    transition: background 0.3s ease, transform 0.2s ease;
    box-shadow: 0 5px 15px rgba(255,112,67,0.5);
  }
  button.join-btn:hover {
    background: #E64A19;
    transform: scale(1.05);
  }
  .skills {
    margin-top: 35px;
    display: flex;
    justify-content: space-around;
  }
  .skill-item {
    flex: 1;
    margin: 0 5px;
    background: #E3F2FD;
    border-radius: 15px;
    padding: 15px 10px;
    box-shadow: 0 4px 10px rgba(3,169,244,0.2);
    transition: background 0.3s ease;
  }
  .skill-item:hover {
    background: #BBDEFB;
  }
  .skill-icon {
    font-size: 2.2em;
    margin-bottom: 10px;
    color: #0288D1;
  }
  .skill-name {
    font-weight: 600;
    color: #01579B;
  }
</style>
</head>
<body>
  <div class="container">
    <h1>Skill Exchange</h1>
    <p class="description">A platform for exchanging skills between people in a fun and free way.</p>
    <button class="join-btn" onclick="alert('Thank you for your interest! Announcement coming soon.')">Join Soon</button>
    <div class="skills" aria-label="Skill categories">
      <div class="skill-item" title="Languages">
        <div class="skill-icon">🌐</div>
        <div class="skill-name">Languages</div>
      </div>
      <div class="skill-item" title="Programming">
        <div class="skill-icon">💻</div>
        <div class="skill-name">Programming</div>
      </div>
      <div class="skill-item" title="Drawing">
        <div class="skill-icon">🎨</div>
        <div class="skill-name">Drawing</div>
      </div>
      <div class="skill-item" title="Sports">
        <div class="skill-icon">🏃‍♂️</div>
        <div class="skill-name">Sports</div>
      </div>
    </div>
  </div>
</body>
</html>