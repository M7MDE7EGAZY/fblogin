#facebook Login Page
First er design the body of the website in css related to <body>
  __________________________________________________________________
     html,
      body {
         width: 100%;
         height: 100%;
         font-family: "Helvetica Neue", Helvetica, sans-serif;
         color: #444;
         -webkit-font-smoothing: antialiased;
         background: #f2f4f7;
      }
  __________________________________________________________________
  
  we added a main contaoner for login form with ID "Container" that shape the main body of the form while centring it vertically and alighning it to the right via css
  __________________________________________________________________
  container {
         position: fixed;
         width: 340px;
         height: 317px;
         top: 50%;
         left: 80%;
         margin-top: -140px;
         margin-left: -170px;
         background: #fff;
         border-radius: 10px;
         border: 1px solid #ccc;
         box-shadow: 0px 0px 8px 2px rgba(126, 124, 124, 0.75);
         -webkit-box-shadow: 0px 0px 8px 2px rgba(126, 124, 124, 0.75);
         -moz-box-shadow: 0px 0px 8px 2px rgba(126, 124, 124, 0.75);
      }
  ___________________________________________________________________
  
  thirdly we added container for facebook logo and slogan  with id "Logo-container" while centring it verticaly and alighning it to the left
  __________________________________________________________________
  logo-container {
         position: fixed;
         width: 600px;
         height: 300px;
         top: 50%;
         left: 15%;
         margin-top: -140px;
         margin-left: -170px;
         background: transparent;
         border-radius: 10px;
         border: 0px solid #ccc;
         /*
        box-shadow: 0px 0px 8px 2px rgba(126, 124, 124, 0.75);
        -webkit-box-shadow: 0px 0px 8px 2px rgba(126, 124, 124, 0.75);
        -moz-box-shadow: 0px 0px 8px 2px rgba(126, 124, 124, 0.75);*/
      }
  __________________________________________________________________
  Here we added the margins of the form to make sure it won't colappse with container border
  form {
         margin: 0 auto;
         margin-top: 20px;
      }
  _____________________________________
  
  we added alse the css to change the names to input boxes to make user have no confusion
_____________________________________
      label {
         color: #555;
         display: inline-block;
         margin-left: 18px;
         padding-top: 10px;
         font-size: 15px;
      }
  ___________________________________
  
  we added a link to restore password id user forgot it with custonm blue design to be noticble

      p a {
         font-size: 11px;
         color: #aaa;
         float: right;
         margin-top: -13px;
         margin-right: 20px;
         -webkit-transition: all 0.4s ease;
         -moz-transition: all 0.4s ease;
         transition: all 0.4s ease;
      }
  & if the user hover over the link it will change color

      p a:hover {
         color: #555;
      }
  __________________________________________________________________
  
  
  here are the design of the main input to be exactly like the facebook
  _______________________________________________________________
  input {
         font-family: "Helvetica Neue", Helvetica, sans-serif;
         font-size: 17px;
         outline: none;
         border-radius: 7px !important;
      }

      input[type="text"],
      input[type="password"],
      input[type="time"] {
         color: #777;
         padding-left: 10px;
         margin: 10px;
         margin-top: 12px;
         margin-left: 18px;
         width: 290px;
         height: 42px;
         border: 1px solid #c7d0d2;
         border-radius: 2px;
         box-shadow: inset 0 1.5px 3px rgba(190, 190, 190, 0.4),
            0 0 0 5px #f5f7f8;
         -webkit-transition: all 0.4s ease;
         -moz-transition: all 0.4s ease;
         transition: all 0.4s ease;
      }

      input[type="text"]:hover,
      input[type="password"]:hover,
      input[type="time"]:hover {
         border: 1px solid #b6bfc0;
         box-shadow: inset 0 1.5px 3px rgba(190, 190, 190, 0.7),
            0 0 0 5px #f5f7f8;
      }

      input[type="text"]:focus,
      input[type="password"]:focus,
      input[type="time"]:focus {
         border: 1px solid #a8c9e4;
         box-shadow: inset 0 1.5px 3px rgba(190, 190, 190, 0.4),
            0 0 0 5px #e6f2f9;
      }
 ___________________________________________________________________
  
  we added a container to the lower half of the form container to add login button and the checkbox if the user want the user and password to be remembered
  #lower {
         background: #ecf2f5;
         width: 100%;
         height: 69px;
         margin-top: 20px;
         box-shadow: inset 0 1px 1px #fff;
         border-top: 1px solid #ccc;
         border-bottom-right-radius: 10px;
         border-bottom-left-radius: 10px;
      }

  
