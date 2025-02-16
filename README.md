<!DOCTYPE html>
</html>
<head>
      <title>Exercise 3</title>
      <style>
            td {
                  text-align: center;
                  padding: 10px;
            }
            h1 {
                  text-align: center;
                  color:blue;
                  text-transform: uppercase;
            }
            .lab {
                  background-color: bisque;
                  text-transform: uppercase;
            }
            .day {
                  padding: 15px;
                  text-transform: uppercase;
                  color: blueviolet;
                  font-weight: bold;
            }
            .lunch {
                  background-color: greenyellow;
                  font-weight: bolder;
                  text-transform: uppercase;

            }
            .empty {
                  background-color: gray;
            }
            .bold{
                  font-weight: bold;
            }
      </style>
</head>

<body>
      <h1>Student Schedule</h1>
      <table border="1" style="width: 100%">
            <tr>
                  <td class="day">Day/Period</td>
                  <td class="bold">I</td>
                  <td class="bold">II</td>
                  <td class="lunch" rowspan="8">Lunch</td>
                  <td class="bold">III</td>
                  <td class="bold">IV</td>
            </tr>
            <tr>
                  <td class="day">Monday</td>
                  <td>Math</td>
                  <td>Physics</td>
                  <td class="empty" colspan="2" rowspan="2"></td>
            </tr>
            <tr>
                  <td class="day">Tuesday</td>
                  <td class="lab" colspan="2">Lab</td>
            </tr>
            <tr>
                  <td class="day">Wednesday</td>
                  <td>History</td>
                  <td>Music</td>
                  <td colspan="2">Seminar</td>
            </tr>
            <tr>
                  <td class="day">Thursday</td>
                  <td>Physical Education</td>
                  <td>Swimming</td>
                  <td>Chemistry</td>
                  <td>Biology</td>
            </tr>
            <tr>
                  <td class="day">Friday</td>
                  <td class="lab" colspan="2">Lab</td>
                  <td>Geography</td>
                  <td>Informatics</td>
            </tr>
            <tr>
                  <td class="day">Saturday</td>
                  <td>Math</td>
                  <td>Physics</td>
                  <td class="lab" colspan="2">Lab</td>
            </tr>
            <tr>
                  <td class="day">Sunday</td>         
                  <td class="empty" colspan="2"></td>
                  <td class="empty"></td>
                  <td>Homework</td>
            </tr>
      </tabl>

</body>
</html>
