function checkGrade(evt) {
  var grade =parseFloat(evt.currentTarget.value);

  if (grade > 100 || grade < 0) {
    console.log("Wrong value")
    evt.currentTarget.style.color = "red"
  } else {
    console.log("Correct Value")
    evt.currentTarget.style.color = "black"

  }

}

function calculateGrade() {
  var Homework = 0
  var Quiz = 0
  var Project1 = 0
  var Project2 = 0

  var hwpercent = parseInt(document.getElementById("homeworkpercent").innerHTML)

  var homework_grade = parseFloat(document.getElementById("hwGrade").value)

  var q_percent = parseInt(document.getElementById("quizpercent").innerHTML)

  var q_grade = parseFloat(document.getElementById("quizGrade").value)

  var p1_percent = parseInt(document.getElementById("project1percent").innerHTML)

  var p1_grade = parseFloat(document.getElementById("P1Grade").value)

  var p2_percent = parseInt(document.getElementById("project2percent").innerHTML)

  var p2_grade = parseFloat(document.getElementById("P2Grade").value)

  var calculategrade = homework_grade * hwpercent /100 + 
                      q_grade * q_percent/100  + 
                      p1_grade * p1_percent/100 +
                       p2_grade * p2_percent/100 
  
  console.log(calculategrade)

  document.getElementById("currentGradeValue").innerHTML = calculategrade
}
