# input-field
In this we are using HTML and CSS to create the basic input field for the user to enter the username, and you can create the other input type 
like this by understanding the code.

# HTML(index.html)
Just copy the code and paste, and add the CSS file path.

html code:

<div class="inputbox">
    <input required="required" type="text">
    <span>Username</span>
    <i></i>
</div>



# CSS(styles.css)

css code:


.inputbox {
  position: relative;
  width: 196px;
}

.inputbox input {
  position: relative;
  width: 100%;
  padding: 20px 10px 10px;
  background: transparent;
  outline: none;
  box-shadow: none;
  border: none;
  color: #23242a;
  font-size: 1em;
  letter-spacing: 0.05em;
  transition: 0.5s;
  z-index: 10;
}

.inputbox span {
  position: absolute;
  left: 0;
  padding: 20px 10px 10px;
  font-size: 1em;
  color: #8f8f8f;
  letter-spacing: 00.05em;
  transition: 0.5s;
  pointer-events: none;
}

.inputbox input:valid ~span,
.inputbox input:focus ~span {
  color: #45f3ff;
  transform: translateX(-10px) translateY(-34px);
  font-size: 0,75em;
}

.inputbox i {
  position: absolute;
  left: 0;
  bottom: 0;
  width: 100%;
  height: 2px;
  background: #45f3ff;
  border-radius: 4px;
  transition: 0.5s;
  pointer-events: none;
  z-index: 9;
}

.inputbox input:valid ~i,
.inputbox input:focus ~i {
  height: 44px;
}
  
  

  


Just paste the css file anywhere and add the path to the HTML file..
I recommend that add both file to the one folder so, it's easy for you.



