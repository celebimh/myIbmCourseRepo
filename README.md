
<!DOCTYPE html>
<html>
  <head>
    <!-- This is your page title that appears on the browser window or tab -->
    <title>Unit Conversions</title>
  </head>
  <body>
  <section id="home">
        <!-- This is the main heading -->
        <header><b>Unit Conversions</b></header>
  </section>
  <nav>
    <!-- Button for redirecting users to the temperature section -->
    <a href="#temperature"><button>Temperature</button></a>
    <!-- Button for redirecting users to the weight section -->
    <a href="#weight"><button>Weight</button></a>
    <!-- Button for redirecting users to the distance section -->
    <a href="#distance"><button>Distance</button></a>
  </nav>
  <div id="all-conversion-sections">
    <!-- This will have the conversion sections for Temperature, Weight, and Distance -->
    <section id="temperature">
        <div id="tmp">
          <figure>
            <!-- Figure and its caption will come here -->
          </figure>
        </div>
      </section>
      <figure>
        <img src="https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBMDeveloperSkillsNetwork-CD0101EN-SkillsNetwork/labs/Theia%20Labs/02%20-%20HTML5%20Elements/images/thermo.png" width="200px"/>
        <figcaption>Celsius to Fahrenheit Conversion</figcaption>
      </figure>
  </div>
  <div id="tmp">

    <article>
      <!-- This contains the specific elements for temperature conversion-->
    </article>
  </div>
  <fieldset>
    <legend>Temperature</legend>
    <!-- Label for Temperature input -->
    <label for="Temperature">Celsius</label> <br/>
    <input type="number" id="c"> <br/>
    <!-- The conversion button -->
    <button id="temperature"> Convert </button> <br/>
    <!-- Label for Temperature output -->
    <input type="number" id="f"> <br/>
    <label for="Temperature">Fahrenheit</label>
  </fieldset>
  <aside>
    To convert celsuis to fahrenheit yourself, use this formula replacing the `C` with your temperature in celsuis: (C × 9/5) + 32
  </aside>
  <section id="weight">
    <!-- Weight conversion section -->
    <div id="wgt">
        <figure>
            <img src="https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBMDeveloperSkillsNetwork-CD0101EN-SkillsNetwork/labs/Theia%20Labs/02%20-%20HTML5%20Elements/images/weight.png" width="200px"/>
            <figcaption>Kilogram to Pound Conversion</figcaption>
        </figure>
        <article>
            <!-- This contains the specific elements for weight conversion -->
            <fieldset>
                <legend>Weight</legend>
                <!-- Label for Weight input -->
                <label for="Weight">Kilograms</label> <br/>
                <input type="number" id="kg"> <br/>
                <!-- The conversion button -->
                <button id="weight"> Convert </button> <br/>
                <!-- Label for Weight output -->
                <input type="number" id="lbs"> <br/>
                <label for="Weight">Pounds</label>
            </fieldset>
        </article>
        <aside>
            To convert kilograms to pounds yourself, use this formula replacing the `kg` with your weight in kilograms: kg x 2.205
        </aside>
    </div>
</section>
<section id="distance">
    <!-- Distance conversion section -->
    <div id="dst">
        <figure>
            <img src="https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBMDeveloperSkillsNetwork-CD0101EN-SkillsNetwork/labs/Theia%20Labs/02%20-%20HTML5%20Elements/images/speedo.png" width="200px"/>
            <figcaption>Kilometer to Mile Conversion</figcaption>
        </figure>
        <article>
            <!-- This contains the specific elements for distance conversion -->
            <fieldset>
                <legend>Distance</legend>
                <!-- Label for Distance input -->
                <label for="Distance">Kilometers</label> <br/>
                <input type="number" id="km"> <br/>
                <!-- The conversion button -->
                <button id="distance"> Convert </button> <br/>
                <!-- Label for Distance output -->
                <input type="number" id="m"> <br/>
                <label for="Distance">Miles</label>
            </fieldset>
        </article>
        <aside>
            To convert kilometers to miles yourself, use this formula replacing the `km` with your distance in kilometers: km &divide; 1.609
        </aside>
    </div>
</section>
<div id="go-home">
    <a href="#home">
        <img src="https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBMDeveloperSkillsNetwork-CD0101EN-SkillsNetwork/labs/Theia%20Labs/02%20-%20HTML5%20Elements/images/home.svg"/>
    </a>
</div>

<footer>Learn more about HTML as a part of the IBM Fullstack Cloud Developer Certification</footer>

  </body>
</html>
