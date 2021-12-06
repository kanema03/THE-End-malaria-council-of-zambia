<!DOCTYPE html>
<html>

<head>
<style>
* { box-sizing: border-box; }
body {
  background: #1f1f1f;
  font-family: arial;
}

.donations {
  position: relative;
  border: 1px solid #eee;
  border-radius: 3px;
  padding: 2em;
  max-width: 400px;
  margin: 10em auto;
  background: white;
  overflow: hidden;
}

.donations__progress-bar {
  background: orange;
  height: 1em;
  position: absolute;
  top: 0;
  left: 0;
  transform: translate3D(-100%, 0, 0);
  width: 100%;
  transition: transform 500ms ease;
}


.donations__progress {
  text-align: center;
}


.donations__text {
  margin-bottom: 1em;
  line-height: 1.5;
}

.donations__donors {
  font-weight: bold;
}

.donations__form {
  display: flex;
  justify-content: space-between;
  flex-wrap: wrap;
  font-size: 1.3em;
}

.donations__input,
.donations__submit,
.donations__reset {
  font-size: inherit;
  border: none;
  padding: 0.5em 0.8em;
  border-radius: 5px;
  width: 45%;
  min-width: 100px;
  margin-bottom: 1em;
}

.donations__submit {
  background: #1cbc2c;
  color: white;
  
}

.donations__reset {
  color: white;
  flex-grow: 1
}

.donations__input {
  border: 1px solid #eee;
  padding-left: 1em;
}

.donations__input-icon {
  position: absolute;
  color: gray;
  line-height: 1.3;
  padding: 0.5em 0.3em;
  pointer-events: none;
}


</style>

</head>
<body>
    <script>
        var $form = $('.donations__form')
var $input = $('.donations__input')
var $sumbit = $('.donations__submit')
var $reset = $('.donations__reset')
var $progress = $('.donations__amount')
var $donors = $('.donations__donors')
var $progressBar = $('.donations__progress-bar')

var numDonors = 0;
var amountDonated = 0;
var goal = 75000;

$form.on('submit', function (e) {
  // Stop form default behavior
  e.preventDefault();
  
  // Get donation amount
  var donation = parseInt($input.val());
  var percentage;
  
  // Update State
  numDonors += 1;
  amountDonated += donation;
  percentage = 100 - ((amountDonated / goal) * 100)
  
  // Update DOM
  $donors.text(numDonors)
  $progress.text(amountDonated.toLocaleString())
  
  if (amountDonated >= goal) {
    $progressBar.css({
      'background': '#1cbc2c',
      'transform': 'none'
    })
  }
  $progressBar.css(
    'transform',
    `translate3D(-${percentage}%, 0, 0)`
  )
  
})

$reset.on('click', function (e) {
  e.preventDefault()
  
  // Reset State
  numDonors = 0;
  amountDonated = 0;
  
  // Reset DOM
  $donors.text(numDonors)
  $progress.text(amountDonated.toLocaleString())
  $progressBar.css({
    'background': 'orange',
    'transform': 'translate3D(-100%, 0, 0)'
  })
})

    </script>
    <form action="payment.html">
    <div class="donations">
        <div class="donations__progress-bar"></div>
        <h2 class="donations__progress">
          K<span class="donations__amount">0</span> / K75,000</h2>
        <div class="donations__text">
          Join the 
          <span class="donations__donors">0</span>
          other donors who have already supported this project.
        </div>
        <form class="donations__form">
          <span class="donations__input-icon">K</span>
          <input class="donations__input" type="number" value="50" title="$"/>
          <input type="submit" class="donations__submit" />
          <button class="donations__reset">Reset</button>
        </form>
      </form>
      </div>
</body>
</html>