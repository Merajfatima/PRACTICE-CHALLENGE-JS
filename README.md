# PRACTICE-CHALLENGE-JS
i am doing the practice questions on javascript using codeware etc...task
Implement a function that accepts 3 integer values a, b, c. The function should return true if a triangle can be built with the sides of given length and false in any other case.

(In this case, all triangles must have surface greater than 0 to be accepted).
const isTriangle = function (a, b, c) {
  //   let result;
  if (a + b > c && a + c > b && b + c > a) {
    return true;
  } else {
    return false;
  }
};

const resultTest = isTriangle(7, 2, 2);
console.log(isTriangle(1, 2, 2), resultTest);
