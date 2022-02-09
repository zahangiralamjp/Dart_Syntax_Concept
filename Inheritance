void main() {
  Child details = new Child("BMW", "White", "VX 321", "3,54,24,852");
  print(details.carName);
  details.killometter();
}

class Car {
  var carName;
  var carColor;
  var carModel;
  var carPrice;

  Car(var carName, var carColor, var carModel, var carPrice) {
    this.carName = carName;
    this.carColor = carColor;
    this.carModel = carModel;
    this.carPrice = carPrice;
  }

  void killometter() {}
}

class Child extends Car {
  Child(carName, carColor, carModel, carPrice)
      : super(carName, carColor, carModel, carPrice);

  @override
  void killometter() {
    var Liter = 20;
    var metter = 100;
    var milles = Liter * metter;
    print("Per Liter ${milles}");
  }
}
