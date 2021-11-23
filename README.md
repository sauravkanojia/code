<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    <h3>square pattern 1</h3>
<script>

        for(let i = 0; i < 5; i++) {
            for(let y = 0; y < 5; y++ )
            {
            document.write("*&nbsp;&nbsp;&nbsp;");
            }
            document.write("<br/>");
        }
    </script>
    <h3>pattern 2</h3>
    <script>
        
        for(let i = 1; i <= 5; i++){
            for(let y = 1; y <= i; y++){
                document.write("* &nbsp;&nbsp;");
            }
            document.write("<br/>");
        }
    </script>
     <h3>pattern 3</h3>
     <script>
         
         for(let i = 1; i <= 5; i++){
             for(let y = i; y <= 5; y++){
                 document.write("* &nbsp;&nbsp;");
             }
             document.write("<br/>");
         }
     </script>
     <h3>pattern 4</h3>
     <script>
         
         for(let i = 1; i <= 5; i++){
             for(let y = i; y < 5; y++){
                 document.write("  &nbsp;&nbsp;&nbsp;");
             }
             for(let y = 1; y <=i; y++){
                 document.write("*&nbsp;&nbsp;");
             }
             document.write("<br/>");
         }
     </script>
          <h3>pattern 5</h3>
          <script>
              
              for(let i = 1; i <= 5; i++){
                  for(let y = i; y < 5; y++){
                      document.write("  &nbsp;&nbsp;&nbsp;");
                  }
                  for(let y = 1; y < i; y++){
                      document.write("*&nbsp;&nbsp;");
                  }
                  for(let y = 1; y <=i; y++){
                      document.write("*&nbsp;&nbsp;");
                  }
                  document.write("<br/>");
              }
          </script>
           <h3>pattern 6</h3>
          <script>
              
              for(let i = 1; i <= 5; i++){
                  for(let y = 1; y < i; y++){
                      document.write(" &nbsp;&nbsp;&nbsp;");
                  }
                  for(let y = i; y < 5; y++){
                      document.write("*&nbsp;&nbsp;");
                  }
                  for(let y = i; y <= 5; y++){
                      document.write("*&nbsp;&nbsp;");
                  }
                  document.write("<br/>");
              }
          </script>
          <h3>pattern 7</h3>
          <script>
               for(let i = 1; i < 5; i++){
                  for(let y = i; y < 5; y++){
                      document.write("  &nbsp;&nbsp;&nbsp;");
                  }
                  for(let y = 1; y < i; y++){
                      document.write("*&nbsp;&nbsp;");
                  }
                  for(let y = 1; y <=i; y++){
                      document.write("*&nbsp;&nbsp;");
                  }
                  document.write("<br/>");
              }
              for(let i = 1; i <= 5; i++){
                  for(let y = 1; y < i; y++){
                      document.write(" &nbsp;&nbsp;&nbsp;");
                  }
                  for(let y = i; y < 5; y++){
                      document.write("*&nbsp;&nbsp;");
                  }
                  for(let y = i; y <= 5; y++){
                      document.write("*&nbsp;&nbsp;");
                  }
                  document.write("<br/>");
              }
          </script>

<h3>pattern 8</h3>
<script>
    for(let i = 1; i < 5; i++){
             for(let y = i; y <= 5; y++){
                 document.write("* &nbsp;&nbsp;");
             }
             document.write("<br/>");
         }
         for(let i = 1; i <= 5; i++){
            for(let y = 1; y <= i; y++){
                document.write("* &nbsp;&nbsp;");
            }
            document.write("<br/>");
        }
</script>
<h3>pattern 9</h3>
<script>
    
    for(let i = 1; i < 5; i++){
        for(let y = 1; y <= i; y++){
            document.write("* &nbsp;&nbsp;");
        }
        document.write("<br/>");
    }
     for(let i = 1; i <= 5; i++){
         for(let y = i; y <= 5; y++){
             document.write("* &nbsp;&nbsp;");
         }
         document.write("<br/>");
     }
 </script>
 <h3>pattern 10</h3> 
 <script>
     for(let i = 1; i <= 2; i++){
            for(let y = 1; y <= i; y++){
                document.write("* ");
            }
            document.write("<br/>");
        }
        for(let i = 1; i <= 3; i++){
            for(let y = 1; y <= i; y++){
                document.write("* ");
            }
            document.write("<br/>");
        }
 </script> 
</body>
</html>
