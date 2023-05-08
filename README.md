# Coursera_Study
Brett studying github on Coursera, Maybe use this for the simple Weather API code
<!DOCTYPE html>
<html>
  <head>
    <title>Car Page</title>
  </head>
  <body>
    <script>
      function Car(make, model, year) {
        this.make = make;
        this.model = model;
        this.year = year;
        this.getName = function () {
          return this.make + ' ' + this.model + ' ' + this.year;
        }
      }

      var c = new Car("Meridian", "Saber GT", 2012);
      alert(c.getName());
    </script>
  </body>
</html>
