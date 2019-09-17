# Invitation-form
Akader ibrahim's repo
<!DOCTYPE html>
<html lang="en">

<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <meta http-equiv="X-UA-Compatible" content="ie=edge">
  <script src="https://cdn.freecodecamp.org/testable-projects-fcc/v1/bundle.js"></script>
  <link rel="stylesheet" href="./style.css">
  <title>Akader Ibrahim</title>
  <link rel="stylesheet" type="text/css" href="mywebpage.css">
</head>

<body class="body">
  <div class="body-wrapper">
    <header class="header">
      <h1 class="title" id="title">Akader Ibrahim</h1>
    </header>

    <main class="main">
      <p class="main__description" id="description">Come, be a part of Akader Ibrahim's birthday party.</p>
      <section class="section">
        <form id="survey-form" class="form">
          <div class="form__item">
            <label class="form__label" id="name-label" for="name">* Name:</label>
            <input class="form__input" id="name" type="text" placeholder="John Snow" required/>
          </div>
          <div class="form__item">
            <label class="form__label" id="email-label" for="email">* Email:</label>
            <input class="form__input" id="email" type="email" placeholder="john.snow@gmail.com" required/>
          </div>
          <div class="form__item">
            <label class="form__label" id="number-label" for="number">Phone</label>
            <input type="tel" id="phone" name="phone"pattern="[0-9]{3}-[0-9]{3}-[0-9]{4}"required>/>
          </div>
          <div class="form__item">
            <label class="form__label">please select which drink you like:</label>
            <select class="form__input" id="dropdown" name="">
              <option value="1">red wine</option>
              <option value="1">Black rebel</option>
              <option value="1">Coka Coola</option>
              <option value="1">Other</option>
            </select>
          </div>
          <div class="form__item">
            <label class="form__label">please let us know number of friends or family who come wiht you</label>

            <div class="form__item">
            <label class="form__label" id="number-label" for="number">number:</label>
            <input class="form__input" id="number" type="number" min="1" max="4" placeholder="2" required />
          </div>
          <div class="form__item">
            <label class="form__label">Aditional comments</label>
            <textarea rows="8" class="form__input"></textarea>
          </div>
          <input class="form__submit" id="submit" type="submit" value="Submit" />
        </form>
      </section>
    </main>
  </div>
</body>

</html>
