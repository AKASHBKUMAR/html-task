#  HTML PAGE TO RE-CREATE THE IMAGE

### AIM:
    To re-create a HTML page based on the given image.

### HTML CODE:
    <!DOCTYPE html>
    <html lang="en">
    <head>
        <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <link rel="stylesheet" href="./assets/css/style.css">
        <link rel="preconnect" href="https://fonts.googleapis.com">
        <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
        <link href="https://fonts.googleapis.com/css2?family=Roboto:ital,wght@0,100;0,300;0,400;0,500;0,700;0,900;1,100;1,300;1,400;1,500;1,700;1,900&display=swap" rel="stylesheet">   
        <title>Assignment-01</title>
      </head>
      <body>
        <main class="main">
          <table class="outer-table">
            <thead >
                <tr>
                  <td colspan="2" class="outer-table-heading">My Day</td>
                </tr>
            </thead>
            <tbody>
              <tr>
                <td>
                  <ol>
                    <li>wake up early</li>
                  </ol>
                  <ul>
                    <li class ="list-squared">5AM</li>
                    <br>
                    <li>walk</li>
                    <li>jog</li>
                  </ul>
                </td>
                <td class="second-table" rowspan="3">
                  <table class="inner-table" >
                    <thead>
                      <tr>
                        <td colspan="2">Things to watch</td>
                      </tr>
                    </thead>
                    <tbody>
                      <tr>
                        <td><img src="./assets/images/sunrise-image.jpg" alt = "sunrise-image"></td>
                        <td><img src="./assets/images/sandwich-image.jpg" alt="sandwich-image"></td>
                      </tr>
                      <tr>
                        <td><img src="./assets/images/coffee-image.jpg" alt="coffee-image"></td>
                        <td><img src="./assets/images/teaching-image.jpg" alt="teaching-image"></td>
                      </tr>
                    </tbody>
                  </table>
                </td>
              </tr>
              <tr>
                <td><ol start="2"><li>breakfast</li></ol>
                  <ul>
                    <li class ="list-squared">8AM</li>
                    <br>
                    <li>eggs</li>
                    <li>coffee</li>
                  </ul>
                </td>
              </tr>
              <tr>
                <td><ol start="3"><li>go to saveetha</li></ol>
                <ul>
                  <li class ="list-squared">8AM</li>
                  <br>
                  <li>attend classes</li>
                  <li>to be continued</li>
                  </ul>
                </td>
              </tr>
            </tbody>
          </table>
        </main>
    </body>
    </html>


### OUTPUT
![](https://github.com/AKASHBKUMAR/html-task/blob/main/output.jpg?raw=true)
  
### RESULT
    Thus the program has been completed successfully.  
