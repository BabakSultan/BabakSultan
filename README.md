<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>RPS</title>
  </head>
  <body>
    <p>Rock Paper Scissors</p>
    <button
      onclick=" 
           const   ran = Math.random();



          let computerMove = '' ;
              if (ran >= 0  &&  ran < 1/3 ) {
                computerMove = ' rock' ;
              
              } else if ( ran >= 1/3  &&  ran < 2/3 ) {
                
                computerMove = ' paper' ;
              } else if (ran >= 2/3  &&  ran < 3/3 ) {
              
                computerMove = ' scissors' ;
              }
            

            let result = '' ;

              if ( computerMove === 'rock' ) {
                result = 'Tie.';
              } else if ( computerMove === 'paper') {
                result = 'You lose.';
              } else if (computerMove === 'scissors' ) {
                result = 'You win.';
              }


              alert( ` You picked rock . Computer picked ${computerMove} ${result} `);
              "
    >
      Rock
    </button>
    <button
      onclick="
    const ran = Math.random();



            let computerMove = '' ;
                  if (ran >= 0  &&  ran < 1/3 ) {
                    computerMove = ' rock' ;
                  
                  } else if ( ran >= 1/3  &&  ran < 2/3 ) {
                    
                    computerMove = ' paper' ;
                  } else if (ran >= 2/3  &&  ran < 3/3 ) {
                  
                    computerMove = ' scissors' ;
                  }
                

              let result = '' ;

                  if ( computerMove === 'paper' ) {
                    result = 'You lose ';
                  } else if ( computerMove === 'paper') {
                    result = 'Tie';
                  } else if (computerMove === 'scissors' ) {
                    result = 'You win.';
      }


    alert( ` You picked paper . Computer picked ${computerMove} ${result} `);
    "
    >
      Paper
    </button>

    <button
      onclick="
              const ran = Math.random();



          let computerMove = '' ;
              if (ran >= 0  &&  ran < 1/3 ) {
                computerMove = ' rock' ;
              
              } else if ( ran >= 1/3  &&  ran < 2/3 ) {
                
                computerMove = ' paper' ;
              } else if (ran >= 2/3  &&  ran < 3/3 ) {
              
                computerMove = ' scissors' ;
              }
            

            let result = '' ;

              if ( computerMove === 'scissors' ) {
                result = 'You win ';
              } else if ( computerMove === 'paper') {
                result = 'You lose';
              } else if (computerMove === 'scissors' ) {
                result = 'Tie';
              }


              alert( ` You picked scissors . Computer picked ${computerMove} ${result} `);
              "
    >
      Scissors
    </button>

    <script></script>
  </body>
</html>
