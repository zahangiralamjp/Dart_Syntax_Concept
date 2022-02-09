void main() {
  Child details = new Child("BMW", "White", "VX 321", "3,54,24,852");
  print(details.carName);
  print(details.carColor);
  print(details.carModel);
  print(details.carPrice);
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
}

class Child extends Car {
  Child(carName, carColor, carModel, carPrice)
      : super(carName, carColor, carModel, carPrice);
}
